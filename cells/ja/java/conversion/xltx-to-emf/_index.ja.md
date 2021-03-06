---
title: Javaを介してXLTXをEMFに変換します 
weight: 6710
url: /ja/java/conversion/xltx-to-emf/ 
description: XLTX形式からEMFファイルへのサンプルJava変換コード。プログラマーは、このサンプルコードを使用して、ExcelおよびOpenOfficeスプレッドシートを任意のWebまたはデスクトップJavaベースのアプリケーション内のEMFにエクスポートできます。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Javaを介してXLTXをEMFに変換します" h2="オンプレミスJavaライブラリを使用して単一または複数のページをEMFに変換するXLTXからEMFJavaへの変換。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="EMF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLTX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Javaを使用してXLTXをEMFに変換する方法" %}}

 XLTXをEMFにレンダリングするために、
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

{{% blocks/products/pf/agp/feature-section-col title="Javaを介してXLTXをEMFに変換する手順" %}}

{{% blocks/products/pf/agp/text %}}

 Java開発者は、わずか数行のコードでXLTXファイルをEMFに簡単に変換できます。

{{% /blocks/products/pf/agp/text %}}

1. ワークブックのインスタンスを含むXLTXファイルをロードします1. コレクションからデフォルトまたは任意のワークシートを選択します1. ImageOrPrintOptionsのオブジェクトを作成および設定します1. Worksheet＆ImageOrPrintOptionsオブジェクトを使用してSheetRenderを作成する1. SheetRender.toImageメソッドを呼び出して、結果をEMF形式で保存します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="システム要求" %}}

{{% blocks/products/pf/agp/text %}}

 Java変換ソースコードを実行する前に、次の前提条件があることを確認してください。

{{% /blocks/products/pf/agp/text %}}

- MicrosoftWindowsまたはJSP/JSFアプリケーションおよびデスクトップアプリケーション用のJavaランタイム環境と互換性のあるOS。- Mavenから直接Aspose.Cellsfor Javaの最新バージョンを入手します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XLTXからEMFJavaへの変換ソースコード" offSpacer="" %}}

```cs
// レンダリングするXLTXファイルをロードします
Workbook workbook = new Workbook("sourceFile.xltx");
// コレクションからデフォルトのワークシートにアクセスする
Worksheet worksheet = workbook.getWorksheets().get(0);
// 結果の画像のパラメータを定義する
ImageOrPrintOptions options = new ImageOrPrintOptions();
options.setOnePagePerSheet(true);
options.setImageType(ImageType.EMF);
// ワークシートをEMF形式の画像に変換します
SheetRender renderer = new SheetRender(worksheet, options);
renderer.toImage(0, "output.emf");   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="XLTXからEMFへの変換ライブデモ" sectionDescription="[XLTXをEMFに変換する](https://products.aspose.app/cells/conversion/xltx-to-emf) 今すぐライブデモのウェブサイトにアクセスしてください。ライブデモには次の利点があります。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" AsposeAPIをダウンロードする必要はありません。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" コードを書く必要はありません。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" XLTXファイルをアップロードするだけで、すぐにEMFに変換されます。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" ダウンロードリンクが表示されます。" >}}

    {{% blocks/products/pf/agp/content h2="Javaスプレッドシート操作ライブラリ" %}}

 Excel APIを使用して、Microsoft Excel形式を作成、編集、変換、およびさまざまな形式にレンダリングできます。さらに、ソフトウェアアプリケーション内での包括的なグラフ作成、スケーラブルなレポート作成、および信頼性の高い計算に使用できます。 Aspose.CellsはスタンドアロンAPIであり、MicrosoftやOpenOfficeなどのソフトウェアは必要ありません。  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLTX" readMoreLink="https://docs.fileformat.com/spreadsheet/xltx/" >}}

XLTX拡張子の付いたファイルは、OfficeOpenXMLファイル形式の仕様に基づくMicrosoftExcelテンプレートファイルを表します。これは、XLTXファイルで指定されたものと同じ設定を示すXLSXファイルを生成するために使用できる標準テンプレートファイルを作成するために使用されます。


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="EMF" readMoreLink="https://docs.fileformat.com/image/emf/" >}}

拡張メタファイル形式（EMF）は、グラフィック画像をデバイスに依存せずに保存します。 EMFのメタファイルは、任意の出力デバイスで解析した後、保存された画像をレンダリングできる時系列の可変長レコードで構成されます。これらの可変長レコードは、囲まれたオブジェクトの定義、描画用のコマンド、および画像を正確にレンダリングするために重要なグラフィックスプロパティにすることができます。デバイスが独自のグラフィックス環境を使用してEMFメタファイルを開くと、開いているデバイスプラットフォームに関係なく、元の画像の比率、寸法、色、およびその他のグラフィックプロパティは同じままです。


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている変換" subTitle="XLTXは、以下にリストされているものを含む他の多くのファイル形式に変換することもできます。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-bmp/" name="XLTXからBMP" description="ビットマップ画像" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-csv/" name="XLTXからCSVへ" description="カンマ区切り値" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-dif/" name="XLTX TO DIF" description="データ交換フォーマット" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-gif/" name="XLTX TO GIF" description="グラフィカルな交換形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-html/" name="XLTXからHTMLへ" description="ハイパーテキストマークアップ言語" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-jpeg/" name="XLTXからJPEGへ" description="JPEG画像" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-mhtml/" name="XLTXからMHTML" description="Webページのアーカイブ形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-ods/" name="XLTX TO ODS" description="OpenDocumentスプレッドシートファイル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-pdf/" name="XLTXからPDFへ" description="ポータブルドキュメントフォーマット" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-png/" name="XLTXからPNG" description="ポータブルネットワークグラフィックス" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-svg/" name="XLTXからSVGへ" description="スケーラブルベクターグラフィックス" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-tiff/" name="XLTXからTIFF" description="タグ付き画像形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-tsv/" name="XLTXからTSV" description="タブ区切り値" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-txt/" name="XLTXからTXT" description="テキストドキュメント" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-xlm/" name="XLTXからXLM" description="Excelマクロファイル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-xls/" name="XLTXからXLS" description="Excelバイナリ形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-xlsb/" name="XLTXからXLSB" description="バイナリExcelワークブックファイル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-xlsx/" name="XLTXからXLSX" description="OOXMLExcelファイル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-xlt/" name="XLTXからXLT" description="MicrosoftExcelテンプレート" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-xltm/" name="XLTXからXLTM" description="Excelマクロ対応テンプレート" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-xps/" name="XLTXからXPS" description="XML用紙仕様" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-json/" name="XLTXからJSONへ" description="JavaScriptオブジェクト表記" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}