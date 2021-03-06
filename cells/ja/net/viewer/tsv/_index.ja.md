---
title: .NET経由でTSVファイル形式を表示 
weight: 3090
url: /ja/net/viewer/tsv/ 
description: .NETフレームワーク、.NETコア、Mono、またはXamarinプラットフォームでTSVドキュメントをロード、レンダリング、表示するためのC#ソースコード。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="TSVファイルビューアfor .NET" h2="MicrosoftExcelやOfficeAutomationを必要とせずに、TSVなどのExcelおよびOpenOfficeスプレッドシートを表示します。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="TSV" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="TSV" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C#を使用してTSVファイルを表示する方法" %}}

 TSVファイルを表示するには、
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 APIは、機能が豊富で、強力で、使いやすいAPIforC#プラットフォームで任意のビューアで使用できます。開ける
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 パッケージマネージャー、検索
 ** Aspose.Cells ** 
 とインストールします。パッケージマネージャーコンソールから次のコマンドを使用することもできます。

{{% blocks/products/pf/agp/code-block title="パッケージマネージャーコンソールコマンド" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="C#を介してTSVを表示する手順" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cellsを使用すると、開発者は数行のコードでTSVファイルを簡単に表示できます。

{{% /blocks/products/pf/agp/text %}}

1. ワークブックのインスタンスにTSVファイルをロードします1. HtmlSaveOptionsのインスタンスを作成し、ExportHeadingsプロパティをtrueに設定します1. Workbook.Saveメソッドを使用してTSVファイルをHTML形式で保存します1. Process.Startを使用してデフォルトのブラウザに結果のHTMLをロードします
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="システム要求" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for .NETは、すべての主要なオペレーティングシステムでサポートされています。次の前提条件があることを確認してください。

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windowsまたは.NETフレームワーク、.NETコア、Mono、またはXamarinプラットフォームと互換性のあるOS- MicrosoftVisualStudioのような開発環境- プロジェクトで参照されているAspose.Cellsfor .NET
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="TSVファイルを表示するためのC#サンプルコード" offSpacer="" %}}

```cs

string output = System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".html";

// WorkbookのインスタンスにTSVファイルをロードします
var book = new Aspose.Cells.Workbook("template.tsv");
// HtmlSaveOptionsのインスタンスを作成し、ExportHeadingsプロパティをtrueに設定します
var options = new Aspose.Cells.HtmlSaveOptions();
options.ExportHeadings = true;

// TSVファイルをHTML形式で保存します
book.Save(output, options);
// 結果のHTMLをデフォルトのブラウザにロードする
System.Diagnostics.Process.Start(output);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="約Aspose.Cellsfor .NETAPI" %}}

 Aspose.Cells APIは、Microsoft Excel形式を作成、編集、変換、およびさまざまな形式にレンダリングするために使用できます。さらに、ソフトウェアアプリケーション内での包括的なグラフ作成、スケーラブルなレポート作成、および信頼性の高い計算に使用できます。 Aspose.CellsはスタンドアロンのAPIであり、MicrosoftやOpenOfficeなどのソフトウェアは必要ありません。  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="TSVを表示する無料アプリ" sectionDescription="ライブデモをチェックして [TSVを表示](https://products.aspose.app/cells/viewer/tsv) 以下の利点があります。" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" 何かをダウンロードしたりセットアップしたりする必要はありません" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" コードを書いたりコンパイルしたりする必要はありません" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" TSVファイルをアップロードして[表示]ボタンを押すだけです" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" 必要に応じて、リンクからTSVファイルをダウンロードします" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="TSV" readMoreLink="https://docs.fileformat.com/spreadsheet/tsv/" >}}
タブ区切り値（TSV）ファイル形式は、プレーンテキスト形式のタブで区切られたデータを表します。 CSVと同様のファイル形式は、異なるアプリケーション間でインポートおよびエクスポートするために、構造化された方法でデータを整理するために使用されます。この形式は、主にスプレッドシートアプリケーションおよびデータベースでのデータのインポート/エクスポートおよび交換に使用されます。 TSVファイルの各レコードは、各フィールド値がタブ文字で区切られた1行のテキストファイルに含まれています。 TSVファイル形式のメディアタイプはtext/tab-separated-valuesです。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされているビューア形式" subTitle="C#を使用すると、を含む他の多くのファイル形式を表示することもできます。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/csv/" name="CSV" description="カンマ区切り値" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/ods/" name="ODS" description="OpenDocumentスプレッドシートファイル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/txt/" name="TXT" description="テキストドキュメント" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xls/" name="XLS" description="Excelバイナリ形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xlsb/" name="XLSB" description="バイナリExcelワークブックファイル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xlsm/" name="XLSM" description="Spreasheetファイル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xlsx/" name="XLSX" description="OOXMLExcelファイル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xlt/" name="XLT" description="MicrosoftExcelテンプレート" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xltm/" name="XLTM" description="Excelマクロ対応テンプレート" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xltx/" name="XLTX" description="OfficeOpenXMLExcelテンプレート" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}