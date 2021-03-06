---
title: C++アプリケーションを介してXLTをGIFに変換する 
url: /ja/cpp/conversion/xlt-to-gif/ 
description: XLTドキュメントからGIF形式へのサンプルC++変換コード。プログラマーは、このソースコードを使用して、任意のC++アプリケーション内でXLTからGIFへのバッチ変換を行うことができます。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="C++を介してXLTをGIFに変換する" h2="Microsoft Excel、OpenOffice、Adobe Acrobatをインストールせずに、C++ライブラリを使用した高性能のXLTからGIFへの変換。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="GIF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C++を使用してXLTをGIFに変換する方法" %}}

 XLTをGIFに変換するには、
 [C++の場合はAspose.Cells](https://products.aspose.com/cells/cpp) 
 APIは、機能が豊富で、強力で、使いやすいドキュメント操作と変換APIforC++プラットフォームです。最新バージョンを直接ダウンロードできます。開くだけです。
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 パッケージマネージャー、検索
 Aspose.Cells .Cpp 
 とインストールします。パッケージマネージャーコンソールから次のコマンドを使用することもできます。

{{% blocks/products/pf/agp/code-block title="指示" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="C++を介してXLTをGIFに変換する手順" %}}

{{% blocks/products/pf/agp/text %}}

 C++開発者は、わずか数行のコードでXLTファイルをGIFに簡単に変換できます。

{{% /blocks/products/pf/agp/text %}}

1. Factory::CreateIWorkbookを使用してXLTファイルをロードします。1. 最初のワークシートを選択します。1. （GIF）オプションを設定します。1. シートの各ページを繰り返してレンダリングします。1. 互換性のあるプログラムでGIFファイルを開きます。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="システム要求" %}}

{{% blocks/products/pf/agp/text %}}

 C++変換サンプルコードを実行する前に、次の前提条件があることを確認してください。

{{% /blocks/products/pf/agp/text %}}

- MicrosoftWindowsまたはWindows32ビット、Windows 64ビット、およびLinux64ビット用のC++ランタイム環境と互換性のあるOS。- プロジェクトで参照されているC++DLLの場合はAspose.Cells。
- MicrosoftWindowsまたはWindows32ビット、Windows 64ビット、およびLinux64ビット用のC++ランタイム環境と互換性のあるOS。- プロジェクトで参照されているC++DLLの場合はAspose.Cells。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XLTからGIFC++への変換ソースコード" offSpacer="" %}}

```cs
// 出力ディレクトリパス。
StringPtr outDir = new String("OutputDirectoryPath");

// XLTをロードします。
intrusive_ptr<Aspose::Cells::IWorkbook> workbook = Factory::CreateIWorkbook(u"sourceFile.xlt");

// 最初のワークシートにアクセスします。
intrusive_ptr<Aspose::Cells::IWorksheet> worksheet = workbook->GetIWorksheets()->GetObjectByIndex(0);

// 画像または印刷オプションオブジェクトを作成します。
intrusive_ptr<Aspose::Cells::Rendering::IImageOrPrintOptions> imgOptions = Factory::CreateIImageOrPrintOptions();

// 画像形式を指定します。
imgOptions->SetImageFormat(Aspose::Cells::Systems::Drawing::Imaging::ImageFormat::GetGif());

// 水平および垂直解像度を指定します
imgOptions->SetHorizontalResolution(200);
imgOptions->SetVerticalResolution(200);

// 指定された画像または印刷オプションに関してシートをレンダリングします。
intrusive_ptr<Aspose::Cells::Rendering::ISheetRender> sr = Factory::CreateISheetRender(worksheet, imgOptions);

// ページ数を取得します。
Aspose::Cells::Systems::Int32 pageCount = sr->GetPageCount();

// 文字列連結用の文字列ビルダーオブジェクトを作成します。
intrusive_ptr<Aspose::Cells::Systems::Text::StringBuilder> sb = new Aspose::Cells::Systems::Text::StringBuilder();

// 各ページを1つずつgif画像にレンダリングします。
for (int i = 0; i Clear();
	sb->Append(outDir);
	sb->Append((StringPtr)new String("outputConvertingWorksheetToImageGIF_"));
	sb->Append(i);
	sb->Append((StringPtr)new String(".gif"));

	// 出力画像パスを取得します。
	StringPtr outputGIF = sb->ToString();

	// ワークシートをgif画像に変換します。
	sr->ToImage(i, outputGIF);
}


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="XLTからGIFへの変換ライブデモ" sectionDescription="[XLTをGIFに変換する](https://products.aspose.app/cells/conversion/xlt-to-gif) 今すぐライブデモのウェブサイトにアクセスしてください。ライブデモには次の利点があります。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" AsposeAPIをダウンロードする必要はありません。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" コードを書く必要はありません。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" XLTファイルをアップロードするだけで、すぐにGIFに変換されます。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" ダウンロードリンクが表示されます。" >}}

    {{% blocks/products/pf/agp/content h2="C++Excelファイル操作ライブラリ" %}}

 Excel APIを使用して、Microsoft Excel形式を作成、編集、変換、およびさまざまな形式にレンダリングできます。さらに、ソフトウェアアプリケーション内での包括的なグラフ作成、スケーラブルなレポート作成、および信頼性の高い計算に使用できます。 Aspose.CellsはスタンドアロンAPIであり、MicrosoftやOpenOfficeなどのソフトウェアは必要ありません。  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLT" readMoreLink="https://docs.fileformat.com/spreadsheet/xlt/" >}}

拡張子が.XLTのファイルは、MicrosoftOfficeスイートの一部として提供されるスプレッドシートアプリケーションであるMicrosoftExcelで作成されたテンプレートファイルです。 Microsoft Office 97-2003は、新しいXLTファイルの作成とそれらのオープンをサポートしていました。最新バージョンのExcelでも、この古い形式のテンプレートファイルを開くことができます。このようなテンプレートファイルは、デフォルトのデータと、ページの書式設定、フォントサイズ、余白、グラフなどの設定を使用して新しいExcelファイルをすばやく作成するために使用され、新しい.XLSファイルとしてさらに保存できます。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="GIF" readMoreLink="https://docs.fileformat.com/image/gif/" >}}

GIFまたはGraphicalInterchangeFormatは、高度に圧縮された画像の一種です。 Unisysが所有するGIFは、画質を低下させないLZW圧縮アルゴリズムを使用します。画像ごとに、GIFは通常、ピクセルあたり最大8ビットを許可し、画像全体で最大256色を許可します。最大1600万色を表示でき、人間の目の限界にかなり触れるJPEG画像とは対照的です。インターネットが登場したとき、GIFは低帯域幅を必要とし、色の単色領域を消費するグラフィックスと互換性があるため、依然として最良の選択でした。アニメーションGIFは、多数の画像またはフレームを1つのファイルに結合し、それらを順番に表示して、アニメーションクリップまたは短いビデオを生成します。色の制限は、フレームごとに最大256であり、カラーグラデーションを使用して他の画像や写真を再現するのに最も適していない可能性があります。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}