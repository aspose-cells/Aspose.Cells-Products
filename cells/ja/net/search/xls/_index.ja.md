---
title:  via .NET を開かずに XLS ドキュメントを検索
weight: 1490
description: C# フレームワーク、.NET コア、Mono または Xamarin プラットフォーム上の XLS ファイル内のパターンを持つ単語を検索するための C# ソース コード。
keywords: [C# Aspose.Cells., c# search words with pattern in xls file., c# find words with pattern in xls file., c# search string with pattern in xls file., c# find words with pattern in xls file., c# search words in xls file., c# find words in xls file., c# search string in xls file., c# find string in xls file]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="XLS で XLS の形式を検索" h2="Microsoft や Adobe PDF などのソフトウェアを使用せずに、サーバー側の Aspose.Cells for .NET API を使用したネイティブで高性能の XLS ドキュメント検索。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C#を使用してXLSファイルを検索する方法" %}}

XLS ファイルを検索するには、次を使用します。
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API は、機能が豊富で強力で使いやすい、C# プラットフォーム用のドキュメント検索 API です。開ける
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
パッケージマネージャー、検索
 **Aspose.Cells** 
そしてインストールします。パッケージ マネージャー コンソールから次のコマンドを使用することもできます。

{{% blocks/products/pf/agp/code-block title="指示" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="C#でXLSファイルを検索する手順" %}}

{{% blocks/products/pf/agp/text %}}

基本的なドキュメント検索
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
API はわずか数行のコードで実行できます。

{{% /blocks/products/pf/agp/text %}}

Workbook クラスを使用して XLS ファイルをロードします。
該当するシートのセルを取得します。
+ Find メソッドを使用して Numbers、日付とテキストを検索

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="システム要求" %}}

{{% blocks/products/pf/agp/text %}}

当社の API は、すべての主要なプラットフォームとオペレーティング システムでサポートされています。以下のコードを実行する前に、システムに次の前提条件が満たされていることを確認してください。

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows、または .NET フレームワーク、.NET コア、Mono または Xamarin プラットフォームと互換性のある OS
-  Microsoft Visual Studio のような開発環境
- プロジェクトに Aspose.Cells for .NET DLL への参照を追加します - 上の [ダウンロード] ボタンを使用して NuGet からインストールします

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XLS ファイルを検索 - C#" offSpacer="" %}}

```cs
// searching cells containing specified string value or number
Workbook workbook = new Workbook("book1.xls");

// get cells collection
Cells cells = workbook.Worksheets[0].Cells;

FindOptions opts = new FindOptions();
opts.LookInType = LookInType.Values;
opts.LookAtType = LookAtType.EntireContent;

// find the cell with the input integer or double
Cell cell1 = cells.Find(205, null, opts);

if (cell1 != null){
    Console.WriteLine("Name of the cell containing the value: " + cell1.Name);
}else{
    Console.WriteLine("Record not found ");
}

// find the cell with the input string
Aspose.Cells.Cell cell2 = cells.Find("Items A", null, opts);

if (cell2 != null){
    Console.WriteLine("Name of the cell containing the value: " + cell2.Name);
}else{
    Console.WriteLine("Record not found ");
}

// find the cell containing with the input string
opts.LookAtType = LookAtType.Contains;
Cell cell3 = cells.Find("Data", null, opts);

if (cell3 != null){
    Console.WriteLine("Name of the cell containing the value: " + cell3.Name);
}else{
    Console.WriteLine("Record not found ");
}  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="約 Aspose.Cells for .NET API" %}}

 Aspose.Cells API は、Excel 形式を作成、編集、変換し、さまざまな形式にレンダリングするために使用できます。さらに、ソフトウェア アプリケーション内で包括的なグラフ作成、スケーラブルなレポート作成、および信頼性の高い計算に使用できます。 Aspose.Cells はスタンドアロンの API であり、Microsoft や OpenOffice などのソフトウェアは必要ありません。



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="オンライン XLS ライブデモを検索" sectionDescription="にアクセスして、XLS 文書内のテキスト、単語、フレーズを今すぐ検索してください。[ライブデモ Web サイト](https://products.aspose.app/cells/search)。ライブデモには次の利点があります" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Aspose API をダウンロードする必要はありません。" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text="コードを記述する必要はありません。" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="XLS ファイルをアップロードするだけです。" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text="検索結果は即座に表示されます。" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS " readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}
拡張子が XLS のファイルは、Excel バイナリ ファイル形式を表します。このようなファイルは、Microsoft Excel だけでなく、OpenOffice Calc や Apple Numbers などの他の同様のスプレッドシート プログラムでも作成できます。Excel で保存されたファイルはワークブックとして知られており、各ワークブックには 1 つ以上のワークシートを含めることができます。データはワークシートに表形式で保存され、ユーザーに表示されます。データには、数値、テキスト データ、数式、外部データ接続、画像、グラフなどを含めることができます。 Microsoft Excel のようなアプリケーションでは、ワークブック データを、PDF、CSV、XLSX、TXT、HTML、XPS などのさまざまな形式にエクスポートできます。 XLS ファイル形式は、Microsoft Excel 2007 のリリースにより、よりオープンで構造化された形式 XLSX に置き換えられました。最新バージョンでも XLS ファイルの作成と読み取りのサポートは提供されていますが、現在は XLSX が使用の第一の選択肢です。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている検索形式" subTitle="C# を使用すると、次のような他の形式も検索できます。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/search/csv/" name="CSV" description="カンマ区切り値" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/search/ods/" name="ODS" description="OpenDocument スプレッドシート ファイル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/search/tsv/" name="TSV" description="タブ区切りの値" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/search/txt/" name="TXT" description="テキストドキュメント" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/search/xlsb/" name="XLSB" description="バイナリ Excel ワークブック ファイル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/search/xlsm/" name="XLSM" description="スプレッドシート ファイル" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
