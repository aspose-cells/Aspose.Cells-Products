---
title: Pythonを介してHTMLファイルを作成する 
url: /ja/python-java/create-html/ 
description: PythonHTMLドキュメントを生成するためのサンプルコード。このコードを使用して、Pythonアプリケーション内でHTMLファイルを作成します。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Pythonを介してHTMLドキュメントを作成する" h2="Python APIを使用してプログラムでネイティブで高性能なHTML（ハイパーテキストマークアップ言語）を作成します。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-python-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="HTML" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Python" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-python-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/pythonjava" installationsDocsLink="https://docs.aspose.com/cells/pythonjava" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/python" learnAsLink="https://docs.aspose.com/cells/pythonjava" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="" %}}

 実行中のアプリケーション内で動的にHTMLファイルを生成するのは簡単です。 MS Officeを必要とせずにHTMLドキュメントを最初から作成するために、
 [Pythonの場合はAspose.Cells](https://pypi.org/project/aspose-cells) 
 Pythonプラットフォームを使用したスプレッドシートの作成、操作、変換にさまざまな機能を提供するAPI。開発者は、データの書き込み、チャートやグラフの生成、およびスプレッドシートでのテーブルの作成のためのコードを簡単に拡張できます。
{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Pythonを介してHTMLを作成する方法" %}}

{{% blocks/products/pf/agp/text %}}

 開発者は、わずか数行のコードでデータ処理用のさまざまなレポートアプリケーションを実行しながら、HTML（ハイパーテキストマークアップ言語）を簡単に作成、ロード、変更、および変換できます。

{{% /blocks/products/pf/agp/text %}}

1. asposecellsをコードファイルにインポートします。1. Workbookクラスインスタンスを作成します。1. ブックの最初のワークシートにアクセスします。1. ワークシートの目的のセルを取得し、その値をセルに入力します。1. Saveメソッドを使用して、ワークブックをHTMLファイルとして保存します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="システム要求" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Python via Javaはプラットフォームに依存しないAPIであり、任意のプラットフォーム（Windows、Linux、MacOS）で使用できます。システムがJava1.8以上であることを確認してください。 [Python](https://www.python.org/downloads/) 3.5以上。 

{{% /blocks/products/pf/agp/text %}}

- Javaをインストールし、PATH環境変数に追加します。次に例を示します。 <code>PATH=C:\Program Files\Java\jdk1.8.0_131;</code>。- からJavaを介してPythonのAspose.Cellsをインストールします <a href="https://pypi.org/project/aspose-cells/">pypi</a>、コマンドを次のように使用します。 <code>$ pip install aspose-cells</code>。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="次のソースコードは、Pythonを使用してHTMLファイルを作成する方法を示しています。" offSpacer="" %}}

```cs

import jpype
import asposecells
jpype.startJVM()
from asposecells.api import Workbook, FileFormatType

// Workbookオブジェクトを作成します。
workbook = Workbook(FileFormatType.HTML)

// ブックの最初のワークシートにアクセスします。
worksheet = workbook.getWorksheets().get(0)

// ワークシートの目的のセルを取得し、その値をセルに入力します。
worksheet.getCells().get("A1").putValue("ColumnA")
worksheet.getCells().get("B1").putValue("ColumnB")
worksheet.getCells().get("A2").putValue("ValueA")
worksheet.getCells().get("B2").putValue("ValueB")

// ブックをHTMLファイルとして保存します。
workbook.save("output.html")

jpype.shutdownJVM()


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<!-- aboutfile Starts -->

     
     {{% blocks/products/pf/agp/content h2="" %}}

 HTMLファイルを生成、変更、変換、レンダリング、および印刷する機能を備えたクロスプラットフォームアプリケーションを構築できるExcelスプレッドシートプログラミングライブラリ。 Python APIは、スプレッドシート形式間で変換するだけでなく、Excelファイルを画像、PDF、HTML、ODSなどとしてレンダリングできるため、業界標準の形式でドキュメントを交換するのに最適です。

    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="HTML" readMoreLink="https://docs.fileformat.com/web/html/" >}}
HTML（ハイパーテキストマークアップ言語）は、ブラウザで表示するために作成されたWebページの拡張機能です。 Webの言語として知られるHTMLは、Webページの一部として表示される新しい情報要件の要件とともに進化してきました。最新のバリアントはHTML5として知られており、言語を操作するための多くの柔軟性を提供します。 HTMLページは、ホストされているサーバーから受信するか、ローカルシステムからロードすることもできます。各HTMLページは、フォーム、テキスト、画像、アニメーション、リンクなどのHTML要素で構成されています。これらの要素は、タグと、各タグに開始と終了がある他のいくつかの要素で表されます。また、JavaScriptやスタイルシート（CSS）などのスクリプト言語で記述されたアプリケーションを埋め込んで、全体的なレイアウトを表現することもできます。
        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< /blocks/products/pf/agp/about-file-section >}}   

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされているスプレッドシートの生成" subTitle="以下にリストされているいくつかを含む他のMicrosoftExcelフォーマットを作成することもできます。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-xls/" name="XLS" description="Microsoft Excelスプレッドシート（レガシー）" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-xlsx/" name="XLSX" description="XMLワークブックを開く" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-xlsb/" name="XLSB" description="Excelバイナリワークブック" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-xlsm/" name="XLSM" description="マクロ対応スプレッドシート" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-xlt/" name="XLT" description="Excel97-2003テンプレート" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-xltx/" name="XLTX" description="Excelテンプレート" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-xltm/" name="XLTM" description="Excelマクロ対応テンプレート" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-csv/" name="CSV" description="カンマ区切り値" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-tsv/" name="TSV" description="タブ区切り値" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-ods/" name="ODS" description="OpenDocumentスプレッドシート" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
