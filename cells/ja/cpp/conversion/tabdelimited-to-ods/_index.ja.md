---
title: C++アプリケーションを介してTABDELIMITEDをODSに変換します 
url: /ja/cpp/conversion/tabdelimited-to-ods/ 
description: TABDELIMITEDドキュメントのサンプルC++変換コードからODS形式へ。プログラマーは、このソースコードを使用して、任意のC++アプリケーション内でTABDELIMITEDからODSへのバッチ変換を行うことができます。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="C++を介してTABDELIMITEDをODSに変換します" h2="Microsoft Excel、OpenOffice、またはAdobe Acrobatをインストールすることなく、C++ライブラリを使用した高性能のTABDELIMITEDからODSへの変換。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODS" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="TABDELIMITED" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C++を使用してTABDELIMITEDをODSに変換する方法" %}}

 TABDELIMITEDをODSに変換するには、
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

{{% blocks/products/pf/agp/feature-section-col title="C++を介してTABDELIMITEDをODSに変換する手順" %}}

{{% blocks/products/pf/agp/text %}}

 C++開発者は、わずか数行のコードでTABDELIMITEDファイルをODSに簡単に変換できます。

{{% /blocks/products/pf/agp/text %}}

1. Factory::CreateIWorkbookを使用してTABDELIMITEDファイルをロードします。1. Save（）メソッドを呼び出します。1. （ODS）ファイル拡張子を持つ出力ファイルパスを渡します。1. ODSファイルは指定されたパスに保存されます。1. 互換性のあるプログラムでODSファイルを開きます。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="システム要求" %}}

{{% blocks/products/pf/agp/text %}}

 C++変換サンプルコードを実行する前に、次の前提条件があることを確認してください。

{{% /blocks/products/pf/agp/text %}}

- MicrosoftWindowsまたはWindows32ビット、Windows 64ビット、およびLinux64ビット用のC++ランタイム環境と互換性のあるOS。- プロジェクトで参照されているC++DLLの場合はAspose.Cells。
- MicrosoftWindowsまたはWindows32ビット、Windows 64ビット、およびLinux64ビット用のC++ランタイム環境と互換性のあるOS。- プロジェクトで参照されているC++DLLの場合はAspose.Cells。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="TABDELIMITED toODSC++変換ソースコード" offSpacer="" %}}

```cs
// TABDELIMITEDをロードします。
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.tabdelimited");

// ODS形式で保存します。
wkb->Save(u"convertedFile.ods", SaveFormat_Ods);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="ODS変換ライブデモにTABDELIMITED" sectionDescription="[TABDELIMITEDをODSに変換する](https://products.aspose.app/cells/conversion/tabdelimited-to-ods) 今すぐライブデモのウェブサイトにアクセスしてください。ライブデモには次の利点があります。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" AsposeAPIをダウンロードする必要はありません。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" コードを書く必要はありません。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" TABDELIMITEDファイルをアップロードするだけで、すぐにODSに変換されます。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" ダウンロードリンクが表示されます。" >}}

    {{% blocks/products/pf/agp/content h2="C++Excelファイル操作ライブラリ" %}}

 Excel APIを使用して、Microsoft Excel形式を作成、編集、変換、およびさまざまな形式にレンダリングできます。さらに、ソフトウェアアプリケーション内での包括的なグラフ作成、スケーラブルなレポート作成、および信頼性の高い計算に使用できます。 Aspose.CellsはスタンドアロンAPIであり、MicrosoftやOpenOfficeなどのソフトウェアは必要ありません。  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="TABDELIMITED" readMoreLink="/{{tabdelimited_url}}" >}}

{{tabdelimited}}

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODS" readMoreLink="https://docs.fileformat.com/spreadsheet/ods/" >}}

ODS拡張子の付いたファイルは、ユーザーが編集できるOpenDocumentスプレッドシートドキュメント形式を表します。データはODFファイル内の行と列に保存されます。これはXMLベースの形式であり、Open Document Formats（ODF）ファミリのいくつかのサブタイプの1つです。この形式は、OASISによって公開および保守されているODF1.2仕様の一部として指定されています。 Windowsやその他のオペレーティングシステム上の多くのアプリケーションは、Microsoft Excel、NeoOffice、LibreOfficeなど、編集や操作のためにODSファイルを開くことができます。 ODSファイルは、さまざまなアプリケーションによってXLS、XLSXなどの他のスプレッドシート形式に変換することもできます。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}