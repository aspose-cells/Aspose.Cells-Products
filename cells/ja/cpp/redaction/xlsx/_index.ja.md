---
title: C++ 経由で XLSX ドキュメント内のテキストを検索して置換します
weight: 9570
description: C++ サンプル コード。Windows 32 ビット、Windows 64 ビット、および Linux 64 ビットの C++ ランタイム環境上の XLSX ファイル内の機密情報を編集します。
keywords: [C++ Aspose.Cells., C++ Search and replace text in XLSX file., C++ redact XLSX file., C++ edit XLSX file., C++ XLSX file redaction., C++ Search and replace string in XLSX file]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="C++ の XLSX 形式を編集する" h2="Microsoft や Adobe PDF などのソフトウェアを使用せずに、サーバー側の Aspose.Cells for C++ API を使用して、ネイティブで高性能な XLSX ドキュメントの機密編集情報を作成します。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C++ を使用して XLSX ファイルを編集する方法" %}}

XLSXファイルを編集するには、[Aspose.Cells for C++](https://products.aspose.com/cells/cpp) APIは、機能が豊富で強力で使いやすい文書編集プラットフォームです。最新バージョンを直接ダウンロードするには、[NuGet](https://www.nuget.org/packages/aspose.cells)パッケージマネージャー、検索**Aspose.Cells.Cpp**インストールします。パッケージ マネージャー コンソールから次のコマンドを使用することもできます。

{{% blocks/products/pf/agp/code-block title="指示" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="C++ 内の XLSX ファイルを編集する手順" %}}

{{% blocks/products/pf/agp/text %}}

基本的なドキュメント検索とコンテンツ、コメント、メタデータ内のテキストの置換[Aspose.Cells for C++](https://products.aspose.com/cells/cpp)API はわずか数行のコードで実現できます。

{{% /blocks/products/pf/agp/text %}}

+ XLSX ファイルをロードします。
+ 置換オプションを定義します。
大文字と小文字の区別オプションを設定します。
+ テキスト一致オプションを設定する
Replace(...) メソッドを使用してテキストを置換する
ワークブックを保存します。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="システム要求" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for C++ はすべての主要なプラットフォームとオペレーティング システムでサポートされています。次の前提条件を満たしていることを確認してください。

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows または、Windows 32 ビット、Windows 64 ビット、および Linux 64 ビット用の C++ ランタイム環境を備えた互換性のある OS。
- プロジェクトに Aspose.Cells for C++ DLL への参照を追加します。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XLSX ファイルを編集 - C++" offSpacer="" %}}

```cs

Aspose::Cells::Startup();

// Load XLSX file
Workbook wb(u"Input.xlsx");
//Create an instance of the ReplaceOptions class
ReplaceOptions replaceOptions;
// Set text matching option
replaceOptions.SetRegexKey(true);
// Set case sensitivity option
replaceOptions.SetCaseSensitive(false);
// Set text matching option
replaceOptions.SetMatchEntireCellContents(false);
// Replace text
wb.Replace(u"\bKIM\b", u"^^^^^^^^", replaceOptions);
// Save as XLSX file
wb.Save("output.xlsx");

Aspose::Cells::Cleanup();

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="Aspose.Cells for C++ APIについて" %}}

Aspose.Cells API は、Microsoft Excel 形式をさまざまな形式に作成、編集、変換、レンダリングするために使用できます。さらに、ソフトウェア アプリケーション内で包括的なグラフ作成、スケーラブルなレポート作成、信頼性の高い計算に使用できます。Aspose.Cells はスタンドアロンの API であり、Microsoft や OpenOffice などのソフトウェアは必要ありません。



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="オンライン XLSX 編集ライブデモ" sectionDescription="XLSX文書のコンテンツ、コメント、メタデータ内のテキストを検索して置換するには、今すぐ[ライブデモのウェブサイト](https://products.aspose.app/cells/redaction)ライブデモには以下の利点があります" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text="Aspose API をダウンロードする必要はありません。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text="コードを書く必要はありません。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" XLSX ファイルをアップロードするだけです。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text="すぐに編集されます。" >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSX" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsx/" >}}
XLSX は、Microsoft Office 2007 のリリースで Microsoft によって導入された、Microsoft Excel ドキュメントのよく知られた形式です。OOXML 標準 ECMA-376 のパート 2 で概説されている Open Packaging Conventions に従って編成された構造に基づいて、新しい形式は、多数の XML ファイルを含む zip パッケージです。基礎となる構造とファイルは、.xlsx ファイルを解凍するだけで調べることができます。

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている編集ドキュメント" subTitle="C++ を使用すると、次のようなさまざまな形式を簡単に編集できます。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/redaction/ods/" name="ODS" description="OpenDocument スプレッドシート ファイル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/redaction/xls/" name="XLS" description="Excel バイナリ形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/redaction/xlsb/" name="XLSB" description="バイナリ Excel ワークブック ファイル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/redaction/xlsm/" name="XLSM" description="スプレッドシートファイル" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
