---
title:  C++ 経由で開かずに TXT ドキュメントを検索
weight: 5090
description: C++ 32 ビット、Windows 64 ビットおよび Linux 64 ビット用の C++ ランタイム環境上の TXT ファイル内のパターンを持つ単語を検索する C++ サンプル コード。
keywords: [C++ Aspose.Cells., C++ search words with pattern in txt file., C++ find words with pattern in txt file., C++ search string with pattern in txt file., C++ find words with pattern in txt file., C++ search words in txt file., C++ find words in txt file., C++ search string in txt file., C++ find string in txt file]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="TXT で TXT の形式を検索" h2="Microsoft や Adobe PDF などのソフトウェアを使用せずに、サーバー側の Aspose.Cells for C++ API を使用したネイティブで高性能の TXT ドキュメント検索。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="TXT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C++を使用してTXTファイルを検索する方法" %}}

TXT ファイルを検索するには、次を使用します。
 [Aspose.Cells for C++](https://products.aspose.com/cells/cpp) 
API は、機能が豊富で強力で使いやすいドキュメント検索 API for C++ プラットフォームです。最新バージョンを直接ダウンロードできます。開くだけです。
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
パッケージマネージャー、検索
 **Aspose.Cells.Cpp** 
そしてインストールします。パッケージ マネージャー コンソールから次のコマンドを使用することもできます。

{{% blocks/products/pf/agp/code-block title="指示" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="C++でTXTファイルを検索する手順" %}}

{{% blocks/products/pf/agp/text %}}

Aspose.Cells API を使用した基本的なドキュメント検索は、わずか数行のコードで実行できます。

{{% /blocks/products/pf/agp/text %}}

+ Workbook クラスをインスタンス化して TXT ファイルをロードします。
+ ReplaceOptions クラスをインスタンス化します。
+ SetCaseSensitive(bool value)、SetMatchEntireCellContents(bool value) などの必要なパターンを設定します。
関連するオプションを指定して Workbook::Replace(...) メソッドを使用します。
+ Workbook::Save(...) メソッドを使用して TXT ファイルを保存します。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="システム要求" %}}

{{% blocks/products/pf/agp/text %}}

Aspose.Cells for C++ は、すべての主要なプラットフォームとオペレーティング システムでサポートされています。次の前提条件を満たしていることを確認してください。

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows、または Windows 32 ビット、Windows 64 ビット、および Linux 64 ビットの C++ ランタイム環境と互換性のある OS。
- プロジェクトに Aspose.Cells for C++ DLL への参照を追加します。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="TXT ファイルを検索 - C++" offSpacer="" %}}

```cs

Aspose::Cells::Startup();

// Source directory path.
U16String srcDir(u"SourcePath\\");

// Output directory path.
U16String outDir(u"OutputPath\\");

// Load TXT file
Workbook  wkb(srcDir + u"sourceFile.txt");

// Create an instance of the IReplaceOptions class
ReplaceOptions replaceOptions;

// Set case sensitivity option
replaceOptions.SetCaseSensitive(false);

// Set text matching option
replaceOptions.SetMatchEntireCellContents(false);

// Replace text
wkb.Replace(u"Text to find", u"Text replacement", replaceOptions);

// Save as TXT file
wkb.Save(outDir + u"outputFile.txt");

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

    {{< blocks/products/pf/agp/demobox sectionTitle="オンライン TXT ライブデモを検索" sectionDescription="にアクセスして、TXT 文書内のテキスト、単語、フレーズを今すぐ検索してください。[ライブデモ Web サイト](https://products.aspose.app/cells/search)。ライブデモには次の利点があります" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Aspose API をダウンロードする必要はありません。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text="コードを記述する必要はありません。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text="TXT ファイルをアップロードするだけです。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text="検索結果は即座に表示されます。" >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="TXT " readMoreLink="https://docs.fileformat.com/word-processing/txt/" >}}
.TXT 拡張子を持つファイルは、行形式のプレーン テキストを含むテキスト ドキュメントを表します。テキスト文書内の段落は改行によって認識され、ファイルの内容をより適切に配置するために使用されます。標準のテキスト文書は、さまざまなオペレーティング システム上の任意のテキスト エディタまたはワード プロセッシング アプリケーションで開くことができます。このようなファイルに含まれるテキストはすべて人間が判読できる形式であり、一連の文字で表されます。

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている検索ドキュメント" subTitle="C++ を使用すると、次のファイルを含む他のファイルも検索できます。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/csv/" name="CSV" description="カンマ区切り値" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/ods/" name="ODS" description="OpenDocument スプレッドシート ファイル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/tsv/" name="TSV" description="タブ区切りの値" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/xls/" name="XLS" description="Excel バイナリ形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/xlsb/" name="XLSB" description="バイナリ Excel ワークブック ファイル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/xlsm/" name="XLSM" description="スプレッドシート ファイル" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
