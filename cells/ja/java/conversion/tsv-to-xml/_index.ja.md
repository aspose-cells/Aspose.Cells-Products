---
title: Javaを介してTSVをXMLに変換します 
url: /ja/java/conversion/tsv-to-xml/ 
description: TSV形式からXMLファイルへのサンプルJava変換コード。プログラマーは、このサンプルコードを使用して、任意のWebまたはデスクトップJavaベースのアプリケーション内でExcelおよびOpenOfficeスプレッドシートをXMLにエクスポートできます。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Javaを介してTSVをXMLに変換します" h2="オンプレミスJavaライブラリを使用して単一または複数のページをXMLに変換するためのTSVからXMLJavaへの変換。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XML" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="TSV" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Javaを使用してTSVをXMLに変換する方法" %}}

 TSVをXMLにレンダリングするために、
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

{{% blocks/products/pf/agp/feature-section-col title="Javaを介してTSVをXMLに変換する手順" %}}

{{% blocks/products/pf/agp/text %}}

 Java開発者は、わずか数行のコードでTSVファイルをXMLに簡単に変換できます。

{{% /blocks/products/pf/agp/text %}}

1. Workbookクラスのインスタンスを含むTSVファイルをロードします1. Workbook.saveメソッドを呼び出す1. XML拡張子とSaveFormatをパラメータとして出力パスを渡します1. 結果のXMLファイルの指定されたパスを確認してください

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="システム要求" %}}

{{% blocks/products/pf/agp/text %}}

 Java変換ソースコードを実行する前に、次の前提条件があることを確認してください。

{{% /blocks/products/pf/agp/text %}}

- MicrosoftWindowsまたはJSP/JSFアプリケーションおよびデスクトップアプリケーション用のJavaランタイム環境と互換性のあるOS。- Mavenから直接Aspose.Cellsfor Javaの最新バージョンを入手します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="TSVからXMLへの変換ソースコード" offSpacer="" %}}

```cs
// WorkbookのインスタンスにTSVファイルをロードします
Workbook book = new Workbook("template.tsv");
// TSVをXMLとして保存
book.save("output.xml", SaveFormat.AUTO);   
   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="TSVからXMLへの変換ライブデモ" sectionDescription="[TSVをXMLに変換する](https://products.aspose.app/cells/conversion/tsv-to-xml) 今すぐライブデモのウェブサイトにアクセスしてください。ライブデモには次の利点があります。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" AsposeAPIをダウンロードする必要はありません。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" コードを書く必要はありません。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" TSVファイルをアップロードするだけで、すぐにXMLに変換されます。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" ダウンロードリンクが表示されます。" >}}

    {{% blocks/products/pf/agp/content h2="Javaスプレッドシート操作ライブラリ" %}}

 Excel APIを使用して、Microsoft Excel形式を作成、編集、変換、およびさまざまな形式にレンダリングできます。さらに、ソフトウェアアプリケーション内での包括的なグラフ作成、スケーラブルなレポート作成、および信頼性の高い計算に使用できます。 Aspose.CellsはスタンドアロンAPIであり、MicrosoftやOpenOfficeなどのソフトウェアは必要ありません。  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="TSV" readMoreLink="https://docs.fileformat.com/spreadsheet/tsv/" >}}

タブ区切り値（TSV）ファイル形式は、プレーンテキスト形式のタブで区切られたデータを表します。 CSVと同様のファイル形式は、異なるアプリケーション間でインポートおよびエクスポートするために、構造化された方法でデータを整理するために使用されます。この形式は、主にスプレッドシートアプリケーションおよびデータベースでのデータのインポート/エクスポートおよび交換に使用されます。 TSVファイルの各レコードは、各フィールド値がタブ文字で区切られた1行のテキストファイルに含まれています。 TSVファイル形式のメディアタイプはtext/tab-separated-valuesです。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XML" readMoreLink="https://docs.fileformat.com/web/xml/" >}}

XMLはExtensibleMarkupLanguageの略で、HTMLに似ていますが、オブジェクトを定義するためのタグの使用が異なります。 XMLファイル形式の作成の背後にある全体的な考え方は、ソフトウェアやハードウェアのツールに依存することなくデータを保存および転送することでした。その人気は、人間と機械の両方で読み取り可能であるためです。これにより、World Wide Web（WWW）などのネットワークを介して保存および共有されるオブジェクトの形式で共通のデータプロトコルを作成できます。 XMLの「X」は拡張可能であり、ユーザーの要件に応じて言語を任意の数の記号に拡張できることを意味します。 Microsoft Open XML、LibreOffice OpenDocument、XHTML、SVGなど、多くの標準ファイル形式で使用されるのはこれらの機能のためです。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている変換" subTitle="TSVを、以下にリストされているものを含む他の多くのファイル形式に変換することもできます。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-bmp/" name="TSVからBMP" description="ビットマップ画像" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-csv/" name="TSVからCSVへ" description="カンマ区切り値" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-dif/" name="TSV TO DIF" description="データ交換フォーマット" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-emf/" name="TSVからEMF" description="強化されたメタファイル形式" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-gif/" name="TSV TO GIF" description="グラフィカルな交換形式" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-html/" name="TSVからHTMLへ" description="ハイパーテキストマークアップ言語" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-jpeg/" name="TSVからJPEG" description="JPEG画像" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-mhtml/" name="TSVからMHTML" description="Webページのアーカイブ形式" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-ods/" name="TSVからODS" description="OpenDocumentスプレッドシートファイル" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-pdf/" name="TSVからPDFへ" description="ポータブルドキュメントフォーマット" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-png/" name="TSVからPNG" description="ポータブルネットワークグラフィックス" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-svg/" name="TSVからSVG" description="スケーラブルベクターグラフィックス" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-tiff/" name="TSVからTIFF" description="タグ付き画像形式" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-txt/" name="TSVからTXT" description="テキストドキュメント" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-xlm/" name="TSVからXLM" description="Excelマクロファイル" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-xls/" name="TSVからXLS" description="Excelバイナリ形式" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-xlsb/" name="TSVからXLSB" description="バイナリExcelワークブックファイル" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-xlsx/" name="TSVからXLSX" description="OOXMLExcelファイル" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-xlt/" name="TSVからXLT" description="MicrosoftExcelテンプレート" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-xltm/" name="TSVからXLTM" description="Excelマクロ対応テンプレート" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-xltx/" name="TSVからXLTX" description="OfficeOpenXMLExcelテンプレート" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-xps/" name="XPSへのTSV" description="XML用紙仕様" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-json/" name="TSVからJSON" description="JavaScriptオブジェクト表記" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}