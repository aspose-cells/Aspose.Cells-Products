---
title: C++アプリケーションを介してSPREADSHEETMLをMHTMLに変換します 
url: /ja/cpp/conversion/spreadsheetml-to-mhtml/ 
description: SPREADSHEETMLドキュメントのサンプルC++変換コードからMHTML形式へ。プログラマーは、このソースコードを使用して、任意のC++アプリケーション内でSPREADSHEETMLからMHTMLへのバッチ変換を行うことができます。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="C++を介してSPREADSHEETMLをMHTMLに変換します" h2="Microsoft Excel、OpenOffice、またはAdobe Acrobatをインストールすることなく、C++ライブラリを使用した高性能SPREADSHEETMLからMHTMLへの変換。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="MHTML" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="SPREADSHEETML" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C++を使用してSPREADSHEETMLをMHTMLに変換する方法" %}}

 SPREADSHEETMLをMHTMLに変換するには、
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

{{% blocks/products/pf/agp/feature-section-col title="C++を介してSPREADSHEETMLをMHTMLに変換する手順" %}}

{{% blocks/products/pf/agp/text %}}

 C++開発者は、わずか数行のコードでSPREADSHEETMLファイルをMHTMLに簡単に変換できます。

{{% /blocks/products/pf/agp/text %}}

1. Factory::CreateIWorkbookを使用してSPREADSHEETMLファイルをロードします。1. Save（）メソッドを呼び出します。1. （MHTML）ファイル拡張子を持つ出力ファイルパスを渡します。1. MHTMLファイルは指定されたパスに保存されます。1. 互換性のあるプログラムでMHTMLファイルを開きます。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="システム要求" %}}

{{% blocks/products/pf/agp/text %}}

 C++変換サンプルコードを実行する前に、次の前提条件があることを確認してください。

{{% /blocks/products/pf/agp/text %}}

- MicrosoftWindowsまたはWindows32ビット、Windows 64ビット、およびLinux64ビット用のC++ランタイム環境と互換性のあるOS。- プロジェクトで参照されているC++DLLの場合はAspose.Cells。
- MicrosoftWindowsまたはWindows32ビット、Windows 64ビット、およびLinux64ビット用のC++ランタイム環境と互換性のあるOS。- プロジェクトで参照されているC++DLLの場合はAspose.Cells。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="SPREADSHEETMLからMHTMLC++への変換ソースコード" offSpacer="" %}}

```cs
// SPREADSHEETMLをロードします。
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.spreadsheetml");

// MHTML形式で保存します。
wkb->Save(u"convertedFile.mhtml", SaveFormat_Mhtml);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="SPREADSHEETMLからMHTMLへの変換ライブデモ" sectionDescription="[SPREADSHEETMLをMHTMLに変換する](https://products.aspose.app/cells/conversion/spreadsheetml-to-mhtml) 今すぐライブデモのウェブサイトにアクセスしてください。ライブデモには次の利点があります。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" AsposeAPIをダウンロードする必要はありません。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" コードを書く必要はありません。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" SPREADSHEETMLファイルをアップロードするだけで、すぐにMHTMLに変換されます。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" ダウンロードリンクが表示されます。" >}}

    {{% blocks/products/pf/agp/content h2="C++Excelファイル操作ライブラリ" %}}

 Excel APIを使用して、Microsoft Excel形式を作成、編集、変換、およびさまざまな形式にレンダリングできます。さらに、ソフトウェアアプリケーション内での包括的なグラフ作成、スケーラブルなレポート作成、および信頼性の高い計算に使用できます。 Aspose.CellsはスタンドアロンAPIであり、MicrosoftやOpenOfficeなどのソフトウェアは必要ありません。  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="SPREADSHEETML" readMoreLink="/{{spreadsheetml_url}}" >}}

{{spreadsheetml}}

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="MHTML" readMoreLink="https://docs.fileformat.com/web/mhtml/" >}}

MHTML拡張子の付いたファイルは、さまざまなアプリケーションで作成できるWebページのアーカイブ形式を表しています。この形式は、Web HTMLコードと関連リソースを単一のファイルに保存するため、アーカイブ形式と呼ばれます。これらのリソースには、画像、アプレット、アニメーション、オーディオファイルなど、Webページにリンクされているものがすべて含まれます。 MHTMLファイルは、InternetExplorerやMicrosoftWordなどのさまざまなアプリケーションで開くことができます。 Microsoft Windowsは、問題を引き起こすWindows上のアプリケーションの使用中に観察された問題のシナリオを記録するために、MHTMLファイル形式を使用します。 MHTMLファイル形式は、プレーンテキストの電子メール関連の仕様であるmessage/rfc822で定義された仕様と同様のページコンテンツをエンコードします。フォーマットの実際の仕様は、RFC2557で詳しく説明されています。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}