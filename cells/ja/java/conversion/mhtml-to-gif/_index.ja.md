---
title: Javaを介してMHTMLをGIFに変換する 
weight: 2000
url: /ja/java/conversion/mhtml-to-gif/ 
description: MHTML形式からGIFファイルへのサンプルJava変換コード。プログラマーは、このサンプルコードを使用して、ExcelおよびOpenOfficeスプレッドシートを任意のWebまたはデスクトップJavaベースのアプリケーション内のGIFにエクスポートできます。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Javaを介してMHTMLをGIFに変換する" h2="オンプレミスJavaライブラリを使用して単一または複数のページをGIFに変換するためのMHTMLからGIFJavaへの変換。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="GIF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="MHTML" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Javaを使用してMHTMLをGIFに変換する方法" %}}

 MHTMLをGIFにレンダリングするために、
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 APIは、機能が豊富で、強力で、使いやすい変換APIfor Javaプラットフォームです。最新バージョンはから直接ダウンロードできます
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) 
 次の構成をpom.xmlに追加して、Mavenベースのプロジェクトにインストールします。

{{% blocks/products/pf/agp/code-block title="リポジトリ" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/ </ url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="依存" offSpacer="true" %}}

```cs
<dependency>
<groupId>com.aspose</groupId>
<artifactId>aspose-cells</artifactId>
<version>version of aspose-cells API</version>
<classifier>jdk17</classifier>
</dependency>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Javaを介してMHTMLをGIFに変換する手順" %}}

{{% blocks/products/pf/agp/text %}}

 Java開発者は、わずか数行のコードでMHTMLファイルをGIFに簡単に変換できます。

{{% /blocks/products/pf/agp/text %}}

1. Workbookのインスタンスを含むMHTMLファイルをロードします1. コレクションからデフォルトまたは任意のワークシートを選択します1. ImageOrPrintOptionsのオブジェクトを作成および設定します1. Worksheet＆ImageOrPrintOptionsオブジェクトを使用してSheetRenderを作成する1. SheetRender.toImageメソッドを呼び出して、結果をGIF形式で保存します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="システム要求" %}}

{{% blocks/products/pf/agp/text %}}

 Java変換ソースコードを実行する前に、次の前提条件があることを確認してください。

{{% /blocks/products/pf/agp/text %}}

- MicrosoftWindowsまたはJSP/JSFアプリケーションおよびデスクトップアプリケーション用のJavaランタイム環境と互換性のあるOS。- Mavenから直接Aspose.Cellsfor Javaの最新バージョンを入手します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="MHTMLからGIFへの変換ソースコード" offSpacer="" %}}

```cs
// レンダリングするMHTMLファイルをロードします
Workbook workbook = new Workbook("sourceFile.mhtml");
// コレクションからデフォルトのワークシートにアクセスする
Worksheet worksheet = workbook.getWorksheets().get(0);
// 結果の画像のパラメータを定義する
ImageOrPrintOptions options = new ImageOrPrintOptions();
options.setOnePagePerSheet(true);
options.setImageType(ImageType.GIF);
// ワークシートをGIF形式の画像に変換します
SheetRender renderer = new SheetRender(worksheet, options);
renderer.toImage(0, "output.gif");   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="MHTMLからGIFへの変換ライブデモ" sectionDescription="[MHTMLをGIFに変換する](https://products.aspose.app/cells/conversion/mhtml-to-gif) 今すぐライブデモのウェブサイトにアクセスしてください。ライブデモには次の利点があります。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" AsposeAPIをダウンロードする必要はありません。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" コードを書く必要はありません。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" MHTMLファイルをアップロードするだけで、すぐにGIFに変換されます。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" ダウンロードリンクが表示されます。" >}}

    {{% blocks/products/pf/agp/content h2="Javaスプレッドシート操作ライブラリ" %}}

 Excel APIを使用して、Microsoft Excel形式を作成、編集、変換、およびさまざまな形式にレンダリングできます。さらに、ソフトウェアアプリケーション内での包括的なグラフ作成、スケーラブルなレポート作成、および信頼性の高い計算に使用できます。 Aspose.CellsはスタンドアロンAPIであり、MicrosoftやOpenOfficeなどのソフトウェアは必要ありません。  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="MHTML" readMoreLink="https://docs.fileformat.com/web/mhtml/" >}}

MHTML拡張子の付いたファイルは、さまざまなアプリケーションで作成できるWebページのアーカイブ形式を表しています。この形式は、Web HTMLコードと関連リソースを単一のファイルに保存するため、アーカイブ形式と呼ばれます。これらのリソースには、画像、アプレット、アニメーション、オーディオファイルなど、Webページにリンクされているものがすべて含まれます。 MHTMLファイルは、InternetExplorerやMicrosoftWordなどのさまざまなアプリケーションで開くことができます。 Microsoft Windowsは、問題を引き起こすWindows上のアプリケーションの使用中に観察された問題のシナリオを記録するために、MHTMLファイル形式を使用します。 MHTMLファイル形式は、プレーンテキストの電子メール関連の仕様であるmessage/rfc822で定義された仕様と同様のページコンテンツをエンコードします。フォーマットの実際の仕様は、RFC2557で詳しく説明されています。


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="GIF" readMoreLink="https://docs.fileformat.com/image/gif/" >}}

GIFまたはGraphicalInterchangeFormatは、高度に圧縮された画像の一種です。 Unisysが所有するGIFは、画質を低下させないLZW圧縮アルゴリズムを使用します。画像ごとに、GIFは通常、ピクセルあたり最大8ビットを許可し、画像全体で最大256色を許可します。最大1600万色を表示でき、人間の目の限界にかなり触れるJPEG画像とは対照的です。インターネットが登場したとき、GIFは低帯域幅を必要とし、色の単色領域を消費するグラフィックスと互換性があるため、依然として最良の選択でした。アニメーションGIFは、多数の画像またはフレームを1つのファイルに結合し、それらを順番に表示して、アニメーションクリップまたは短いビデオを生成します。色の制限は、フレームごとに最大256であり、カラーグラデーションを使用して他の画像や写真を再現するのに最も適していない可能性があります。


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている変換" subTitle="MHTMLを、以下にリストされているものを含む他の多くのファイル形式に変換することもできます。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-bmp/" name="MHTMLからBMP" description="ビットマップ画像" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-csv/" name="MHTMLからCSV" description="カンマ区切り値" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-dif/" name="MHTML TO DIF" description="データ交換フォーマット" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-emf/" name="MHTMLからEMF" description="強化されたメタファイル形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-html/" name="MHTMLからHTML" description="ハイパーテキストマークアップ言語" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-jpeg/" name="MHTMLからJPEGへ" description="JPEG画像" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-ods/" name="MHTMLからODSへ" description="OpenDocumentスプレッドシートファイル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-pdf/" name="MHTMLからPDF" description="ポータブルドキュメントフォーマット" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-png/" name="MHTMLからPNG" description="ポータブルネットワークグラフィックス" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-svg/" name="MHTMLからSVG" description="スケーラブルベクターグラフィックス" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-tiff/" name="MHTMLからTIFF" description="タグ付き画像形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-tsv/" name="MHTMLからTSV" description="タブ区切り値" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-txt/" name="MHTMLからTXT" description="テキストドキュメント" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-xlm/" name="MHTMLからXLM" description="Excelマクロファイル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-xls/" name="MHTMLからXLS" description="Excelバイナリ形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-xlsb/" name="MHTMLからXLSB" description="バイナリExcelワークブックファイル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-xlsx/" name="MHTMLからXLSX" description="OOXMLExcelファイル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-xlt/" name="MHTMLからXLT" description="MicrosoftExcelテンプレート" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-xltm/" name="MHTMLからXLTM" description="Excelマクロ対応テンプレート" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-xltx/" name="MHTMLからXLTX" description="OfficeOpenXMLExcelテンプレート" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-xps/" name="MHTMLからXPSへ" description="XML用紙仕様" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-json/" name="MHTMLからJSONへ" description="JavaScriptオブジェクト表記" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}