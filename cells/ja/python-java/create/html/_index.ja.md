---
title: HTML を作成 - Python に HTML ファイルを作成
description: Aspose エクセル。 Python Aspose.Cells を使用して HTML ファイルをすばやく簡単に作成します。 Python を使用して HTML ファイルを生成します。 Python に HTML を作成します。 Python HTML 作成者。
keywords: [Aspose Excel., Python Aspose.Cells., Python Create HTML file., Generate HTML file in Python., Create HTML file using Python., Write data to HTML file via Python., Create a HTML file in Python., Python Generate a HTML file., Python HTML Creater]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="PythonにHTMLファイルを作成" h2="HTMLファイルを作成するための高速Pythonライブラリ。これは、XLSX、PDF、および Python を使用する他の多くの形式をインポートおよびエクスポートするためのプロフェッショナル ソフトウェア ソリューションです。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-python-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="HTML" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Python" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-python-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/pythonjava" installationsDocsLink="https://docs.aspose.com/cells/pythonjava" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://releases.aspose.com/cells/python-java/" learnAsLink="https://docs.aspose.com/cells/pythonjava" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Pythonを使用してHTMLファイルを作成" %}}

 HTMLファイルを作成するにはどうすればよいですか? Aspose.Cells for Python via Java ライブラリを使用すると、数行のコードでプログラム的に HTML ファイルを簡単に作成できます。[Aspose.Cells for Python](https://pypi.org/project/aspose-cells)すべての Excel ファイルを生成、変更、変換、レンダリング、印刷できるクロスプラットフォーム アプリケーションを構築できます。 Python Excel API は、スプレッドシート形式間で変換するだけでなく、Excel ファイルを画像 PDF, HTML, ODS, CSV, SVG, JSON, WORD, PPT などとしてレンダリングすることもできるため、業界標準形式でドキュメントを交換するのに最適です。

{{% /blocks/products/pf/agp/content %}}



{{% blocks/products/pf/agp/content h2="PythonでHTMLを作成する方法" %}}

{{% blocks/products/pf/agp/text %}}

開発者は、データ処理用のさまざまなレポート アプリケーションを実行しながら、わずか数行のコードで HTML ファイルの作成、読み込み、変更、変換を簡単に行うことができます。

{{% /blocks/products/pf/agp/text %}}

1. コード ファイルに asposecell をインポートします。
1.  Workbookクラスのインスタンスを作成します。
1. ワークブックの最初のワークシートにアクセスします。
1. ワークシートの目的のセルを取得し、そのセルに値を入力します。
1.  Save メソッドを使用して、ワークブックを HTML ファイルとして保存します。

{{% blocks/products/pf/agp/code-block title="サンプルコードは、PythonにHTMLファイルを作成する方法を示しています。" offSpacer="" %}}

```cs

import jpype
import asposecells
jpype.startJVM()
from asposecells.api import Workbook, FileFormatType

# Create Workbook object.
workbook = Workbook(FileFormatType.HTML)

# Access the first worksheet of the workbook.
worksheet = workbook.getWorksheets().get(0)

# Get the desired cell(s) of the worksheet and input the value into the cell(s).
worksheet.getCells().get("A1").putValue("ColumnA")
worksheet.getCells().get("B1").putValue("ColumnB")
worksheet.getCells().get("A2").putValue("ValueA")
worksheet.getCells().get("B2").putValue("ValueB")

# Save the workbook as HTML file.
workbook.save("output.html")

jpype.shutdownJVM()

```

{{% /blocks/products/pf/agp/code-block %}}
{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="Python ファイルを作成するための Python ライブラリ" %}}

{{% blocks/products/pf/agp/text %}}

「Aspose.Cells for Python via Java」をシステムにインストールするには 3 つのオプションがあります。ニーズに近いものを選択し、ステップバイステップの指示に従ってください。

{{% /blocks/products/pf/agp/text %}}

1.  Aspose.Cells for Python via Java を Windows にインストールします。を参照してください。[ドキュメンテーション](https://docs.aspose.com/cells/python-java/getting-started/#windows)
1.  Linux に Aspose.Cells for Python via Java をインストールします。見る[ドキュメンテーション](https://docs.aspose.com/cells/python-java/getting-started/#linux)
1. Aspose.Cells for Python via Java を macOS にインストールします。見る[ドキュメンテーション](https://docs.aspose.com/cells/python-java/getting-started/#macos)

{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="システム要求" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Python via Java はプラットフォームに依存しない API で、どのプラットフォーム (Windows、Linux および MacOS) でも使用できます。システムに Java 1.8 以降が搭載されていることを確認してください。[Python](https://www.python.org/downloads/)3.5以上。

{{% /blocks/products/pf/agp/text %}}

-  Java をインストールし、PATH 環境変数に追加します。次に例を示します。<code>PATH=C:\Program Files\Java\jdk1.8.0_131;</code>.
-  Aspose.Cells for Python via Java をからインストールします<a href="https://pypi.org/project/aspose-cells/">pypi</a>、次のようにコマンドを使用します。<code>$ pip install aspose-cells</code>.

{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->
    {{< blocks/products/pf/agp/about-file-section >}}
        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="HTML" readMoreLink="https://docs.fileformat.com/web/html/" >}}HTML (Hyper Text Markup Language) は、ブラウザーで表示するために作成された Web ページの拡張子です。 Web の言語として知られる HTML は、Web ページの一部として表示される新しい情報要件の要件とともに進化してきました。最新の亜種は HTML 5 として知られており、この言語を使用する際の柔軟性が大幅に高まります。 HTML ページは、ホストされているサーバーから受信されるか、ローカル システムから読み込まれることもあります。各 HTML ページは、フォーム、テキスト、画像、アニメーション、リンクなどの HTML 要素で構成されています。これらの要素は、タグと、各タグに開始点と終了点があるその他のいくつかの要素によって表されます。また、全体的なレイアウト表現のために、JavaScript やスタイル シート (CSS) などのスクリプト言語で記述されたアプリケーションを埋め込むこともできます。{{< /blocks/products/pf/agp/i18n/about-file-text >}}
    {{< /blocks/products/pf/agp/about-file-section >}}
<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされているスプレッドシート生成" subTitle="以下にリストされているいくつかの形式を含む、他の Microsoft Excel 形式を作成することもできます。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xls/" name="XLS" description="Microsoft Excel スプレッドシート (レガシー)" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xlsx/" name="XLSX" description="XML ワークブックを開く" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xlsb/" name="XLSB" description="Excel バイナリ ワークブック" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xlsm/" name="XLSM" description="マクロが有効なスプレッドシート" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xlt/" name="XLT" description="Excel 97 - 2003 テンプレート" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xltx/" name="XLTX" description="Excel テンプレート" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xltm/" name="XLTM" description="Excel マクロ有効テンプレート" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/csv/" name="CSV" description="カンマ区切り値" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/tsv/" name="TSV" description="タブ区切りの値" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/ods/" name="ODS" description="OpenDocument スプレッドシート" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/pdf/" name="PDF" description="ポータブルドキュメントフォーマット" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/html/" name="HTML" description="ハイパーテキストマークアップ言語" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
