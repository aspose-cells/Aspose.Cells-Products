---
title: Javaを介してXLSBをJSONに変換する 
weight: 9970
url: /ja/java/conversion/xlsb-to-json/ 
description: XLSB形式からJSONファイルへのサンプルJava変換コード。プログラマーは、このサンプルコードを使用して、任意のWebまたはデスクトップJavaベースのアプリケーション内でExcelおよびOpenOfficeスプレッドシートをJSONにエクスポートできます。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Javaを介してXLSBをJSONに変換する" h2="オンプレミスJavaライブラリを使用して単一または複数のページをJSONに変換するためのXLSBからJSONJavaへの変換。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="JSON" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSB" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Javaを使用してXLSBをJSONに変換する方法" %}}

 XLSBをJSONにレンダリングするために、
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

{{% blocks/products/pf/agp/feature-section-col title="Javaを介してXLSBをJSONに変換する手順" %}}

{{% blocks/products/pf/agp/text %}}

 Java開発者は、わずか数行のコードでXLSBファイルをJSONに簡単に変換できます。

{{% /blocks/products/pf/agp/text %}}

1. Workbookクラスのインスタンスを含むXLSBファイルをロードします1. Cells.createRangeメソッドを使用してエクスポートするデータの範囲を作成します1. RangeとExportRangeToJsonOptionsを参照して、JsonUtility.exportRangeToJsonメソッドを呼び出します。1. BufferedWriter.writeメソッドを介して文字列JSONデータをファイルに書き込みます
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="システム要求" %}}

{{% blocks/products/pf/agp/text %}}

 Java変換ソースコードを実行する前に、次の前提条件があることを確認してください。

{{% /blocks/products/pf/agp/text %}}

- MicrosoftWindowsまたはJSP/JSFアプリケーションおよびデスクトップアプリケーション用のJavaランタイム環境と互換性のあるOS。- Mavenから直接Aspose.Cellsfor Javaの最新バージョンを入手します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XLSBからJSONJavaへの変換ソースコード" offSpacer="" %}}

```cs
// ワークブックのインスタンスを含むXLSXファイルをロードします
Workbook workbook = new Workbook("template.xlsx");
// 変換するデータを含むワークシートのCellsCollectionにアクセスします
Cells cells = workbook.getWorksheets().get(0).getCells();
// 詳細オプションのExportRangeToJsonOptionsを作成および設定します
ExportRangeToJsonOptions exportOptions = new ExportRangeToJsonOptions();
// エクスポートするデータを含むセルの範囲を作成します
Range range = cells.createRange(0, 0, cells.getLastCell().getRow() + 1, cells.getLastCell().getColumn() + 1);
// 範囲をJSONデータとしてエクスポート
String jsonData = JsonUtility.exportRangeToJson(range, exportOptions);
// JSON形式でディスクにデータを書き込む
BufferedWriter writer = new BufferedWriter(new FileWriter("output.json"));
writer.write(jsonData);
writer.close();   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="XLSBからJSONへの変換ライブデモ" sectionDescription="[XLSBをJSONに変換する](https://products.aspose.app/cells/conversion/xlsb-to-json) 今すぐライブデモのウェブサイトにアクセスしてください。ライブデモには次の利点があります。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" AsposeAPIをダウンロードする必要はありません。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" コードを書く必要はありません。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" XLSBファイルをアップロードするだけで、すぐにJSONに変換されます。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" ダウンロードリンクが表示されます。" >}}

    {{% blocks/products/pf/agp/content h2="Javaスプレッドシート操作ライブラリ" %}}

 Excel APIを使用して、Microsoft Excel形式を作成、編集、変換、およびさまざまな形式にレンダリングできます。さらに、ソフトウェアアプリケーション内での包括的なグラフ作成、スケーラブルなレポート作成、および信頼性の高い計算に使用できます。 Aspose.CellsはスタンドアロンAPIであり、MicrosoftやOpenOfficeなどのソフトウェアは必要ありません。  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSB" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsb/" >}}

XLSBファイル形式は、Excelブックの内容を指定するレコードと構造のコレクションであるExcelバイナリファイル形式を指定します。コンテンツには、数値、テキスト、または数値とテキストの両方の非構造化または半構造化テーブル、数式、外部データ接続、チャート、および画像を含めることができます。 XLSX（Open XMLファイル形式に基づく）とは異なり、XLSBはバイナリExcelワークブックファイルを表します。 XLSBファイルは、より高速に読み書きできるため、大きなファイルでの作業に役立ちます。 XLSX（および以前のXLS）は、ワークブックを保存するためにユーザーが選択する最も一般的なファイル形式であるため、XLSBがワークブックの保存に使用されることはめったにありません。 MicrosoftOffice2007以降で開くことができます。


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="JSON" readMoreLink="https://docs.fileformat.com/web/json/" >}}

JSON（JavaScript Object Notation）は、人間が読み取れるテキストを使用してデータを保存および送信する、データを共有するためのオープンスタンダードのファイル形式です。 JSONファイルは.json拡張子で保存されます。 JSONはフォーマットが少なくて済み、XMLの優れた代替手段です。 JSONはJavaScriptから派生していますが、言語に依存しないデータ形式です。 JSONの生成と解析は、多くの最新のプログラミング言語でサポートされています。 application / jsonは、JSONに使用されるメディアタイプです。


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている変換" subTitle="XLSBを、以下にリストされているものを含む他の多くのファイル形式に変換することもできます。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-bmp/" name="XLSBからBMP" description="ビットマップ画像" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-csv/" name="XLSBからCSV" description="カンマ区切り値" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-dif/" name="XLSB TO DIF" description="データ交換フォーマット" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-emf/" name="XLSBからEMF" description="強化されたメタファイル形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-gif/" name="XLSBからGIF" description="グラフィカルな交換形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-html/" name="XLSBからHTML" description="ハイパーテキストマークアップ言語" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-jpeg/" name="XLSBからJPEG" description="JPEG画像" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-mhtml/" name="XLSBからMHTML" description="Webページのアーカイブ形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-ods/" name="XLSBからODS" description="OpenDocumentスプレッドシートファイル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-pdf/" name="XLSBからPDF" description="ポータブルドキュメントフォーマット" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-png/" name="XLSBからPNG" description="ポータブルネットワークグラフィックス" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-svg/" name="XLSBからSVG" description="スケーラブルベクターグラフィックス" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-tiff/" name="XLSBからTIFF" description="タグ付き画像形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-tsv/" name="XLSBからTSV" description="タブ区切り値" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-txt/" name="XLSBからTXT" description="テキストドキュメント" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-xls/" name="XLSBからXLS" description="Excelバイナリ形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-xlsm/" name="XLSBからXLSM" description="Spreasheetファイル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-xlsx/" name="XLSBからXLSX" description="OOXMLExcelファイル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-xlt/" name="XLSBからXLT" description="MicrosoftExcelテンプレート" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-xltm/" name="XLSBからXLTM" description="Excelマクロ対応テンプレート" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-xltx/" name="XLSBからXLTX" description="OfficeOpenXMLExcelテンプレート" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-xps/" name="XLSBからXPS" description="XML用紙仕様" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}