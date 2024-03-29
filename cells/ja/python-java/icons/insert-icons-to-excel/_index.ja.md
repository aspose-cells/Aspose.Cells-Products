---
title:  Python via Javaを使用してSVG画像/アイコンをExcelに挿入します
weight: 200
description: Python via SVG 画像/アイコンを Excel に挿入するための Java ソース コード。
keywords: [Python via Java Aspose.Cells., Python via Java add SVG images/Icons into Excel., Python via Java insert SVG images/Icons into Excel., Python via Java create SVG images/Icons in Excel]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Python via Javaを使用してSVG画像/アイコンをExcelに挿入します" h2="Microsoft や Open Office、Adobe PDF などのソフトウェアを使用せずに、Aspose.Cells\' API を使用して SVG 画像/アイコンを挿入します。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-python-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for Python via Java" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Python via Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-python-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/python" installationsDocsLink="https://docs.aspose.com/cells/python" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://releases.aspose.com/cells/python-java/" learnAsLink="https://docs.aspose.com/cells/python" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content %}}

どのデバイスでも画像を引き伸ばしたり圧縮したりしたくないですか?

ズームインしたときに画像がぼやけたくないですか?

高解像度で画像が歪んだくないですか?

おそらく SVG が良い選択です。SVG 画像はどのズーム レベルでも見栄えがよく、解像度に依存しません。SVG 画像の忠実度が高いため、Excel ユーザーの間で非常に人気があります。

Excel を使用すると、次の問題が発生する場合があります。

+ 対象の Excel ファイルを手動で直接操作することはできず、処理するにはプログラムが必要です。
+ 多数の SVG 画像を同じ Excel ファイルに挿入します。
+ SVG 画像を多数の異なる Excel ファイルに挿入します。

これらの問題を解決するには、次の使用をお勧めします。[Aspose.Cells](https://products.aspose.com/cells/)ライブラリ。Excel ファイルを処理するための一般的なインターフェイスが多数含まれており、非常に便利なツールです。

{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="Microsoft Excelを使用してSVGの画像/アイコンをExcelファイルに挿入する方法" %}}

![](/cells/ja/net/icons/insert-icons-to-excel/sample.png)

Microsoft Excel では、SVG を挿入する 3 つの方法が提供されています。

+  **ローカル SVG 画像/アイコンを挿入**

SVG ファイルをドキュメント内の特定の場所にドラッグ アンド ドロップするだけです。または、リボンから「*挿入 -> 画像 -> このデバイス...*」パスを選択することもできます。

+  **プリセット SVG 画像/アイコンを挿入**

Microsoft Excel は、選択できるプリセットの SVG 画像を提供してくれました。リボンから「*挿入 -> 画像 -> ストック画像...*」パスを選択すると、選択ダイアログを開くことができます。ほとんどの svg ファイルはストック画像の「アイコン」オプションの下にあります。

+  **Web から SVG の画像/アイコンを挿入します**

上記の方法のいずれでもニーズを満たせない場合は、Microsoft Excel を通じてインターネットから必要な結果を検索することもできます。[*挿入 -> 画像 -> オンライン画像...*] を選択すると、選択ダイアログを開くことができます。 " リボンからのパス。

{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="Python via Javaを使用してSVG画像/アイコンをExcelファイルに挿入する方法" %}}

SVG の画像/アイコンを Excel ファイルに挿入するには、次を使用します。
 [Aspose.Cells for Python Java経由](https://pypi.org/project/aspose-cells/) 
 API は、機能が豊富で強力で使いやすい、Java プラットフォーム経由のドキュメント操作 API for Python です。API は、Excel ファイルの作成、操作、変換、レンダリングを提供します。 Microsoft Office または Excel アプリケーションに依存せずにすべて。次のコマンドを使用してコンソールからインストールできます。

{{% blocks/products/pf/agp/code-block title="指示" offSpacer="true" %}}

```cs

> pip install aspose-cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Python via Javaを使用してSVG画像/アイコンをExcelファイルに挿入する手順" %}}

{{% blocks/products/pf/agp/text %}}

自分の環境で次のワークフローを試すには、Aspose.Cells が必要です。

{{% /blocks/products/pf/agp/text %}}

Workbook オブジェクトをインスタンス化します。(または -> XLSX ファイルをフルパスでロードします。)
+ インデックスからワークシートを選択します。
 + シェイプコレクションの使用[メソッドの追加](https://reference.aspose.com/cells/python-java/asposecells.api/shapecollection#addIcons(int,%20int,%20int,%20int,%20int,%20int,%20byte[],%20byte[])をクリックして、選択したワークシートにアイコンを挿入します。
ワークブックを XLSX 形式で保存します。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="システム要求" %}}

{{% blocks/products/pf/agp/text %}}

 Java 経由の Aspose.Cells for Python はプラットフォームに依存しない API で、どのプラットフォーム (Windows、Linux および MacOS) でも使用できます。システムに Java 1.8 以降がインストールされていることを確認してください。[Python](https://www.python.org/downloads/)3.5以上。
 
{{% /blocks/products/pf/agp/text %}}

-  Python via Java スクリプトを実行できるオペレーティング システム (Windows、Linux、MacOS など)
- Java をインストールし、PATH 環境変数に追加します。次に例を示します。<code>PATH=C:\Program Files\Java\jdk1.8.0_131;</code>.
-  Java 経由で Aspose.Cells for Python をインストールします。<a href="https://pypi.org/project/aspose-cells/">pypi</a>、次のようにコマンドを使用します。<code>$ pip install aspose-cells</code>.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="SVG 画像/アイコンを挿入 - Python via java" offSpacer="" %}}

{{< gist "aspose-cells-gists" "32e50c6aabc547111966569f3fd39694" "InsertIconsIntoWorksheet.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="Aspose.Cells API について" %}}

Aspose.Cells API クロスプラットフォーム アプリケーションを構築でき、Excel 形式をさまざまな形式 (画像、PDF、HTML、ODS など) の作成、編集、変換、レンダリングに使用できます。さらに、包括的なグラフ作成にも使用できます。ソフトウェア アプリケーション内でスケーラブルなレポートと信頼性の高い計算を実行できるため、業界標準形式でドキュメントを交換するのに最適です。 Aspose.Cells はスタンドアロンの API であり、Microsoft や OpenOffice などのソフトウェアを必要としないことが重要です。

{{% /blocks/products/pf/agp/content %}}



<!-- aboutfile Ends -->
<!--
{{< blocks/products/pf/agp/other-supported-section title="Other Supported Splitting Formats" subTitle="Using Python via Java, One can also split large file into chunks of many other file formats including." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/splitter/ods/" name="ODS" description="OpenDocument Spreadsheet File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/splitter/xls/" name="XLS" description="Excel Binary Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/splitter/xlsb/" name="XLSB" description="Binary Excel Workbook File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/splitter/xlsm/" name="XLSM" description="Spreadsheet File" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

-->

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
