---
title: C++アプリケーションを介してMHTMLをEMFに変換する 
weight: 2140
url: /ja/cpp/conversion/mhtml-to-emf/ 
description: MHTMLドキュメントからEMF形式へのサンプルC++変換コード。プログラマーは、このソースコードを使用して、任意のC++アプリケーション内でMHTMLからEMFへのバッチ変換を行うことができます。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="C++を介してMHTMLをEMFに変換する" h2="Microsoft Excel、OpenOffice、またはAdobeAcrobatをインストールせずにC++ライブラリを使用した高性能MHTMLからEMFへの変換。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="EMF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="MHTML" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C++を使用してMHTMLをEMFに変換する方法" %}}

 MHTMLをEMFに変換するには、
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

{{% blocks/products/pf/agp/feature-section-col title="C++を介してMHTMLをEMFに変換する手順" %}}

{{% blocks/products/pf/agp/text %}}

 C++開発者は、わずか数行のコードでMHTMLファイルをEMFに簡単に変換できます。

{{% /blocks/products/pf/agp/text %}}

1. Factory::CreateIWorkbookを使用してMHTMLファイルをロードします。1. 最初のワークシートを選択します。1. セット（EMF）オプション。1. シートの各ページを繰り返してレンダリングします。1. 互換性のあるプログラムでEMFファイルを開きます。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="システム要求" %}}

{{% blocks/products/pf/agp/text %}}

 C++変換サンプルコードを実行する前に、次の前提条件があることを確認してください。

{{% /blocks/products/pf/agp/text %}}

- MicrosoftWindowsまたはWindows32ビット、Windows 64ビット、およびLinux64ビット用のC++ランタイム環境と互換性のあるOS。- プロジェクトで参照されているC++DLLの場合はAspose.Cells。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="MHTMLからEMFC++への変換ソースコード" offSpacer="" %}}

```cs
// 出力ディレクトリパス。
StringPtr outDir = new String("OutputDirectoryPath");

// MHTMLをロードします。
intrusive_ptr<Aspose::Cells::IWorkbook> workbook = Factory::CreateIWorkbook(u"sourceFile.mhtml");

// 最初のワークシートにアクセスします。
intrusive_ptr<Aspose::Cells::IWorksheet> worksheet = workbook->GetIWorksheets()->GetObjectByIndex(0);

// 画像または印刷オプションオブジェクトを作成します。
intrusive_ptr<Aspose::Cells::Rendering::IImageOrPrintOptions> imgOptions = Factory::CreateIImageOrPrintOptions();

// 画像形式を指定します。
imgOptions->SetImageFormat(Aspose::Cells::Systems::Drawing::Imaging::ImageFormat::GetEmf());

// 水平および垂直解像度を指定します
imgOptions->SetHorizontalResolution(200);
imgOptions->SetVerticalResolution(200);

// 指定された画像または印刷オプションに関してシートをレンダリングします。
intrusive_ptr<Aspose::Cells::Rendering::ISheetRender> sr = Factory::CreateISheetRender(worksheet, imgOptions);

// ページ数を取得します。
Aspose::Cells::Systems::Int32 pageCount = sr->GetPageCount();

// 文字列連結用の文字列ビルダーオブジェクトを作成します。
intrusive_ptr<Aspose::Cells::Systems::Text::StringBuilder> sb = new Aspose::Cells::Systems::Text::StringBuilder();

// 各ページをレンダリングして、画像を1つずつemfします。
for (int i = 0; i Clear();
	sb->Append(outDir);
	sb->Append((StringPtr)new String("outputConvertingWorksheetToImageEMF_"));
	sb->Append(i);
	sb->Append((StringPtr)new String(".emf"));

	// 出力画像パスを取得します。
	StringPtr outputEMF = sb->ToString();

	// ワークシートをemf画像に変換します。
	sr->ToImage(i, outputEMF);
}


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="MHTMLからEMFへの変換ライブデモ" sectionDescription="[MHTMLをEMFに変換する](https://products.aspose.app/cells/conversion/mhtml-to-emf) 今すぐライブデモのウェブサイトにアクセスしてください。ライブデモには次の利点があります。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" AsposeAPIをダウンロードする必要はありません。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" コードを書く必要はありません。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" MHTMLファイルをアップロードするだけで、すぐにEMFに変換されます。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" ダウンロードリンクが表示されます。" >}}

    {{% blocks/products/pf/agp/content h2="C++Excelファイル操作ライブラリ" %}}

 Excel APIを使用して、Microsoft Excel形式を作成、編集、変換、およびさまざまな形式にレンダリングできます。さらに、ソフトウェアアプリケーション内での包括的なグラフ作成、スケーラブルなレポート作成、および信頼性の高い計算に使用できます。 Aspose.CellsはスタンドアロンAPIであり、MicrosoftやOpenOfficeなどのソフトウェアは必要ありません。  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="MHTML" readMoreLink="https://docs.fileformat.com/web/mhtml/" >}}

MHTML拡張子の付いたファイルは、さまざまなアプリケーションで作成できるWebページのアーカイブ形式を表しています。この形式は、Web HTMLコードと関連リソースを単一のファイルに保存するため、アーカイブ形式と呼ばれます。これらのリソースには、画像、アプレット、アニメーション、オーディオファイルなど、Webページにリンクされているものがすべて含まれます。 MHTMLファイルは、InternetExplorerやMicrosoftWordなどのさまざまなアプリケーションで開くことができます。 Microsoft Windowsは、問題を引き起こすWindows上のアプリケーションの使用中に観察された問題のシナリオを記録するために、MHTMLファイル形式を使用します。 MHTMLファイル形式は、プレーンテキストの電子メール関連の仕様であるmessage/rfc822で定義された仕様と同様のページコンテンツをエンコードします。フォーマットの実際の仕様は、RFC2557で詳しく説明されています。


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="EMF" readMoreLink="https://docs.fileformat.com/image/emf/" >}}

拡張メタファイル形式（EMF）は、グラフィック画像をデバイスに依存せずに保存します。 EMFのメタファイルは、任意の出力デバイスで解析した後、保存された画像をレンダリングできる時系列の可変長レコードで構成されます。これらの可変長レコードは、囲まれたオブジェクトの定義、描画用のコマンド、および画像を正確にレンダリングするために重要なグラフィックスプロパティにすることができます。デバイスが独自のグラフィックス環境を使用してEMFメタファイルを開くと、開いているデバイスプラットフォームに関係なく、元の画像の比率、寸法、色、およびその他のグラフィックプロパティは同じままです。


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている変換" subTitle="MHTMLを、以下にリストされているものを含む他の多くのファイル形式に変換することもできます。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-bmp/" name="MHTMLからBMP" description="ビットマップ画像" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-csv/" name="MHTMLからCSV" description="カンマ区切り値" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-dif/" name="MHTML TO DIF" description="データ交換フォーマット" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-gif/" name="MHTMLからGIF" description="グラフィカルな交換形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-html/" name="MHTMLからHTML" description="ハイパーテキストマークアップ言語" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-jpeg/" name="MHTMLからJPEGへ" description="JPEG画像" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-ods/" name="MHTMLからODSへ" description="OpenDocumentスプレッドシートファイル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-pdf/" name="MHTMLからPDF" description="ポータブルドキュメントフォーマット" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-png/" name="MHTMLからPNG" description="ポータブルネットワークグラフィックス" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-svg/" name="MHTMLからSVG" description="スケーラブルベクターグラフィックス" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-tiff/" name="MHTMLからTIFF" description="タグ付き画像形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-tsv/" name="MHTMLからTSV" description="タブ区切り値" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-xls/" name="MHTMLからXLS" description="Excelバイナリ形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-xlsb/" name="MHTMLからXLSB" description="バイナリExcelワークブックファイル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-xlsm/" name="MHTMLからXLSM" description="Spreasheetファイル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-xlsx/" name="MHTMLからXLSX" description="OOXMLExcelファイル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-xltm/" name="MHTMLからXLTM" description="Excelマクロ対応テンプレート" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-xltx/" name="MHTMLからXLTX" description="OfficeOpenXMLExcelテンプレート" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-xps/" name="MHTMLからXPSへ" description="XML用紙仕様" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}