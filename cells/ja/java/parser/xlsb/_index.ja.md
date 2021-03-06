---
title: Javaを介してXLSBドキュメントからテキストと画像を抽出します 
weight: 440
url: /ja/java/parser/xlsb/ 
description: JSP/JSFアプリケーションおよびデスクトップアプリケーションのJavaランタイム環境でXLSBファイルからテキストと画像を抽出するためのJavaサンプルコード。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="JavaのXLSBフォーマットを解析する" h2="MicrosoftやAdobePDFなどのソフトウェアを使用せずに、サーバー側のAspose.Cellsfor JavaAPIを使用したネイティブで高性能なXLSBドキュメントの解析。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLSB" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Javaを使用してXLSBファイルを解析する方法" %}}

 XLSBファイルを解析するために、
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 APIは、機能が豊富で、強力で、使いやすい構文解析APIfor Javaプラットフォームです。最新バージョンはから直接ダウンロードできます
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

{{% blocks/products/pf/agp/feature-section-col title="JavaのXLSBファイルを解析する手順" %}}

{{% blocks/products/pf/agp/text %}}

 で解析する基本的なドキュメント
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 APIは、ほんの数行のコードで実行できます。 Microsoft Excel XLS、XLSX、XLSM、XLSB、およびOpenDocumentODSファイルからテキストと画像を解析します。

{{% /blocks/products/pf/agp/text %}}

+Workbookクラスを使用してXLSBドキュメントをロードします。
+ getWorksheets（）。getメソッドを使用して必要なシートを選択します。
+ getCells（）を使用して、選択したシートのすべてのセルを取得します。
+各セルを繰り返し処理し、そのテキストを取得します。
+各セルの値を出力するか、StringBuilderのappend（）メソッドを使用して全体を表示します

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="システム要求" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Javaは、すべての主要なプラットフォームとオペレーティングシステムでサポートされています。次の前提条件があることを確認してください。

{{% /blocks/products/pf/agp/text %}}

- MicrosoftWindowsまたはJSP/JSFアプリケーションおよびデスクトップアプリケーション用のJavaランタイム環境と互換性のあるOS。- Aspose.Cellsfor Javaの最新バージョンを直接入手する [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells)  。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XLSBファイルの解析-Java" offSpacer="" %}}

```cs
StringBuilder stringBuilder = new StringBuilder();
Workbook book = new Workbook(dir + "book1.xlsb");
Worksheet sheet = book.getWorksheets().get(0);
Cells cells = sheet.getCells();
Iterator iterator = cells.iterator();
while(iterator.hasNext())
{
Cell cell = (Cell)iterator.next();
stringBuilder.append(cell.getStringValue());
stringBuilder.append(" ");
}
System.out.println(stringBuilder.toString());  

    


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="約Aspose.Cellsfor JavaAPI" %}}

 Aspose.Cells APIは、Microsoft Excel形式を作成、編集、変換、およびさまざまな形式にレンダリングするために使用できます。さらに、ソフトウェアアプリケーション内での包括的なグラフ作成、スケーラブルなレポート作成、および信頼性の高い計算に使用できます。 Aspose.CellsはスタンドアロンのAPIであり、MicrosoftやOpenOfficeなどのソフトウェアは必要ありません。  



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="オンラインXLSBパーサーライブデモ" sectionDescription="XLSBドキュメントからテキストと画像を今すぐ抽出するには、 [ライブデモのウェブサイト](https://products.aspose.app/cells/parser)。ライブデモには次の利点があります" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" AsposeAPIをダウンロードする必要はありません。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" コードを書く必要はありません。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" XLSBファイルをアップロードするだけです。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" 即座に解析されます。" >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSB" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsb/" >}}
XLSBファイル形式は、Excelブックの内容を指定するレコードと構造のコレクションであるExcelバイナリファイル形式を指定します。コンテンツには、数値、テキスト、または数値とテキストの両方の非構造化または半構造化テーブル、数式、外部データ接続、チャート、および画像を含めることができます。 XLSX（Open XMLファイル形式に基づく）とは異なり、XLSBはバイナリExcelワークブックファイルを表します。 XLSBファイルは、より高速に読み書きできるため、大きなファイルでの作業に役立ちます。 XLSX（および以前のXLS）は、ワークブックを保存するためにユーザーが選択する最も一般的なファイル形式であるため、XLSBがワークブックの保存に使用されることはめったにありません。 MicrosoftOffice2007以降で開くことができます。 

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている解析ドキュメント" subTitle="Javaを使用すると、を含む他の形式を簡単に解析できます。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/parser/ods/" name="ODS" description="OpenDocumentスプレッドシートファイル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/parser/xls/" name="XLS" description="Excelバイナリ形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/parser/xlsm/" name="XLSM" description="Spreasheetファイル" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}