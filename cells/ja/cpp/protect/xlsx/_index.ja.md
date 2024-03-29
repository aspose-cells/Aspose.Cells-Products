---
title:  C++ 経由で XLSX ドキュメントを保護およびロックする
weight: 1140
description: Windows 32 ビット、Windows 64 ビット、および Linux 64 ビットの C++ ランタイム環境でパスワードを使用して XLSX ファイルをロックする C++ サンプル コード。
keywords: [C++ Aspose.Cells., C++ Lock XLSX files., C++ How to Protect and lock XLSX document., C++ Protect XLSX files., Encrypt XLSX Files using C++]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="XLSX 経由で XLSX ファイルを暗号化する" h2=".NET ライブラリを使用して、XLSX 形式を含む Excel スプレッドシートをパスワードで保護します。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSX" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp/" installationsDocsLink="https://docs.aspose.com/cells/cpp/" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C++を使用してXLSXファイルを保護する方法" %}}

XLSX ファイルを保護するには、次を使用します。
 [Aspose.Cells for C++](https://products.aspose.com/cells/cpp) 
 API は、機能が豊富で強力で使いやすいドキュメント暗号化プラットフォームです。 API for C++最新バージョンを直接ダウンロードできます。開くだけです。
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
パッケージマネージャー、検索
 **Aspose.Cells.Cpp** 
そしてインストールします。パッケージ マネージャー コンソールから次のコマンドを使用することもできます。

{{% blocks/products/pf/agp/code-block title="Aspose.Cells" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="C++ 経由で XLSX ファイルを保護する手順" %}}

{{% blocks/products/pf/agp/text %}}

Aspose.Cells API を使用したドキュメントの保護は、わずか数行のコードで実行できます。

{{% /blocks/products/pf/agp/text %}}

1.  Workbookクラスを使用してXLSXファイルをロードします
1. ProtectionType と Password を指定して Protect(..) メソッドを使用する
1. Save() メソッドで保護された XLSX ファイルを保存します

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="システム要求" %}}

{{% blocks/products/pf/agp/text %}}

Aspose.Cells for C++ は、すべての主要なプラットフォームとオペレーティング システムでサポートされています。次の前提条件を満たしていることを確認してください。

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows、または Windows 32 ビット、Windows 64 ビット、および Linux 64 ビットの C++ ランタイム環境と互換性のある OS。
- プロジェクトに Aspose.Cells for C++ DLL への参照を追加します。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="指示" offSpacer="" %}}

```cs

Aspose::Cells::Startup();

// load the ODS Excel file 
Workbook book(u"unlocked.xlsx");

// access the first worksheet
Worksheet worksheet = book.GetWorksheets().Get(0);

// protect the worksheet with password
worksheet.Protect(ProtectionType::All, u"password", nullptr);

// protect the whole workbook with password
book.Protect(ProtectionType::All, u"password");

// save the modified file in default format
book.Save(u"protected.xlsx");

Aspose::Cells::Cleanup();

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="約 Aspose.Cells for C++ API" %}}

 Aspose.Cells API は、Excel 形式を作成、編集、変換し、さまざまな形式にレンダリングするために使用できます。さらに、ソフトウェア アプリケーション内で包括的なグラフ作成、スケーラブルなレポート作成、および信頼性の高い計算に使用できます。 Aspose.Cells はスタンドアロンの API であり、Microsoft や OpenOffice などのソフトウェアは必要ありません。



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="保護する無料アプリ XLSX" sectionDescription="ライブデモをチェックしてください[XLSX ファイルを暗号化する](https://products.aspose.app/cells/protect/xlsx)以下の特典付き。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text="何もダウンロードしたり設定したりする必要はありません" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text="コードを書いたりコンパイルしたりする必要はありません" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text="XLSX ファイルをアップロードして「ロック解除」ボタンを押すだけです" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text="結果の XLSX ファイルをリンクからダウンロードします。" >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSX" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsx/" >}}
XLSX は、Microsoft Office 2007 のリリースで Microsoft によって導入された、Microsoft Excel ドキュメントのよく知られた形式です。OOXML 標準 ECMA-376 のパート 2 で概説されている Open Packaging Conventions に従って整理された構造に基づいて、新しい形式は次のようになります。多数の XML ファイルを含む zip パッケージ。基礎となる構造とファイルは、.xlsx ファイルを解凍するだけで調べることができます。

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている保護文書" subTitle="C++ を使用すると、次のような他のファイルを保護できます。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/protect/ods/" name="ODS" description="OpenDocument スプレッドシート ファイル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/protect/xls/" name="XLS" description="Excel バイナリ形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/protect/xlsb/" name="XLSB" description="バイナリ Excel ワークブック ファイル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/protect/xlsm/" name="XLSM" description="スプレッドシート ファイル" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
