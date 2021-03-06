---
title: C++アプリケーションを介してODSをXMLに変換する 
url: /ja/cpp/conversion/ods-to-xml/ 
description: ODSドキュメントからXML形式へのサンプルC++変換コード。プログラマーは、このソースコードを使用して、任意のC++アプリケーション内でODSからXMLへのバッチ変換を行うことができます。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="C++を介してODSをXMLに変換する" h2="Microsoft Excel、OpenOffice、またはAdobe Acrobatをインストールすることなく、C++ライブラリを使用した高性能ODSからXMLへの変換。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="XML" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="ODS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C++を使用してODSをXMLに変換する方法" %}}

 ODSをXMLに変換するために、
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

{{% blocks/products/pf/agp/feature-section-col title="C++を介してODSをXMLに変換する手順" %}}

{{% blocks/products/pf/agp/text %}}

 C++開発者は、わずか数行のコードでODSファイルをXMLに簡単に変換できます。

{{% /blocks/products/pf/agp/text %}}

1. Factory::CreateIWorkbookを使用してODSファイルをロードします。1. Save（）メソッドを呼び出します。1. （XML）ファイル拡張子を付けて出力ファイルパスを渡します。1. XMLファイルは指定されたパスに保存されます。1. 互換性のあるプログラムでXMLファイルを開きます。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="システム要求" %}}

{{% blocks/products/pf/agp/text %}}

 C++変換サンプルコードを実行する前に、次の前提条件があることを確認してください。

{{% /blocks/products/pf/agp/text %}}

- MicrosoftWindowsまたはWindows32ビット、Windows 64ビット、およびLinux64ビット用のC++ランタイム環境と互換性のあるOS。- プロジェクトで参照されているC++DLLの場合はAspose.Cells。
- MicrosoftWindowsまたはWindows32ビット、Windows 64ビット、およびLinux64ビット用のC++ランタイム環境と互換性のあるOS。- プロジェクトで参照されているC++DLLの場合はAspose.Cells。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="ODSからXMLへの変換ソースコード" offSpacer="" %}}

```cs
// ODSをロードします。
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.ods");

// XML形式で保存します。
wkb->Save(u"convertedFile.xml", SaveFormat_Xml);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="ODSからXMLへの変換ライブデモ" sectionDescription="[ODSをXMLに変換する](https://products.aspose.app/cells/conversion/ods-to-xml) 今すぐライブデモのウェブサイトにアクセスしてください。ライブデモには次の利点があります。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" AsposeAPIをダウンロードする必要はありません。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" コードを書く必要はありません。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" ODSファイルをアップロードするだけで、すぐにXMLに変換されます。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" ダウンロードリンクが表示されます。" >}}

    {{% blocks/products/pf/agp/content h2="C++Excelファイル操作ライブラリ" %}}

 Excel APIを使用して、Microsoft Excel形式を作成、編集、変換、およびさまざまな形式にレンダリングできます。さらに、ソフトウェアアプリケーション内での包括的なグラフ作成、スケーラブルなレポート作成、および信頼性の高い計算に使用できます。 Aspose.CellsはスタンドアロンAPIであり、MicrosoftやOpenOfficeなどのソフトウェアは必要ありません。  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODS" readMoreLink="https://docs.fileformat.com/spreadsheet/ods/" >}}

ODS拡張子の付いたファイルは、ユーザーが編集できるOpenDocumentスプレッドシートドキュメント形式を表します。データはODFファイル内の行と列に保存されます。これはXMLベースの形式であり、Open Document Formats（ODF）ファミリのいくつかのサブタイプの1つです。この形式は、OASISによって公開および保守されているODF1.2仕様の一部として指定されています。 Windowsやその他のオペレーティングシステム上の多くのアプリケーションは、Microsoft Excel、NeoOffice、LibreOfficeなど、編集や操作のためにODSファイルを開くことができます。 ODSファイルは、さまざまなアプリケーションによってXLS、XLSXなどの他のスプレッドシート形式に変換することもできます。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XML" readMoreLink="https://docs.fileformat.com/web/xml/" >}}

XMLはExtensibleMarkupLanguageの略で、HTMLに似ていますが、オブジェクトを定義するためのタグの使用が異なります。 XMLファイル形式の作成の背後にある全体的な考え方は、ソフトウェアやハードウェアのツールに依存することなくデータを保存および転送することでした。その人気は、人間と機械の両方で読み取り可能であるためです。これにより、World Wide Web（WWW）などのネットワークを介して保存および共有されるオブジェクトの形式で共通のデータプロトコルを作成できます。 XMLの「X」は拡張可能であり、ユーザーの要件に応じて言語を任意の数の記号に拡張できることを意味します。 Microsoft Open XML、LibreOffice OpenDocument、XHTML、SVGなど、多くの標準ファイル形式で使用されるのはこれらの機能のためです。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている変換" subTitle="また、ODSを、以下にリストされているいくつかを含む他の多くのファイル形式に変換することもできます。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-bmp/" name="BMPへのODS" description="ビットマップ画像" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-csv/" name="CSVへのODS" description="カンマ区切り値" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-dif/" name="ODS TO DIF" description="データ交換フォーマット" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-emf/" name="ODS TO EMF" description="強化されたメタファイル形式" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-gif/" name="GIFへのODS" description="グラフィカルな交換形式" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-html/" name="ODS TO HTML" description="ハイパーテキストマークアップ言語" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-jpeg/" name="JPEGへのODS" description="JPEG画像" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-mhtml/" name="MHTMLへのODS" description="Webページのアーカイブ形式" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-pdf/" name="PDFへのODS" description="ポータブルドキュメントフォーマット" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-png/" name="PNGへのODS" description="ポータブルネットワークグラフィックス" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-svg/" name="ODS TO SVG" description="スケーラブルベクターグラフィックス" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-tiff/" name="ODS TO TIFF" description="タグ付き画像形式" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-tsv/" name="TSVへのODS" description="タブ区切り値" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-xls/" name="XLSへのODS" description="Excelバイナリ形式" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-xlsb/" name="XLSBへのODS" description="バイナリExcelワークブックファイル" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-xlsm/" name="XLSMへのODS" description="Spreasheetファイル" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-xlsx/" name="XLSXへのODS" description="OOXMLExcelファイル" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-xltm/" name="ODS TO XLTM" description="Excelマクロ対応テンプレート" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-xltx/" name="XLTXへのODS" description="OfficeOpenXMLExcelテンプレート" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-xps/" name="XPSへのODS" description="XML用紙仕様" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}