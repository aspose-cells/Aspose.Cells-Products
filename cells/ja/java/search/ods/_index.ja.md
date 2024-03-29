---
title:  via Java を開かずに ODS ドキュメントを検索
weight: 8140
description: JSP/JSF アプリケーションおよびデスクトップ アプリケーション用の Java ランタイム環境の ODS ファイル内のパターンを持つ単語を検索するための Java サンプル コード。
keywords: [Java Aspose.Cells., Java search words with pattern in ods file., Java find words with pattern in ods file., Java search string with pattern in ods file., Java find words with pattern in ods file., Java search words in ods file., Java find words in ods file., Java search string in ods file., Java find string in ods file]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="ODS で ODS の形式を検索" h2="Microsoft や Adobe PDF などのソフトウェアを使用せずに、サーバー側の Aspose.Cells for Java API を使用したネイティブで高性能の ODS ドキュメント検索。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="ODS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Javaを使用してODSファイルを検索する方法" %}}

ODS ファイルを検索するには、次を使用します。
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API は、機能が豊富で強力で使いやすい検索 API for Java プラットフォームです。最新バージョンはから直接ダウンロードできます。
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) 
次の構成を pom.xml に追加して、Maven ベースのプロジェクト内にインストールします。

{{% blocks/products/pf/agp/code-block title="リポジトリ" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
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

{{% blocks/products/pf/agp/feature-section-col title="JavaでODSファイルを検索する手順" %}}

{{% blocks/products/pf/agp/text %}}

Aspose.Cells API を使用した基本的なドキュメント検索は、わずか数行のコードで実行できます。

{{% /blocks/products/pf/agp/text %}}

+ Workbook オブジェクトをインスタンス化して ODS ファイルをロードします。
+ ODS ファイルの最初のワークシートにアクセスします。
+ 指定した数式を含むセルを検索します。
+ FindOptions をインスタンス化します。
+ 文字列値を含むセルを検索します。
検索結果の後に見つかったセルを印刷します

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="システム要求" %}}

{{% blocks/products/pf/agp/text %}}

Aspose.Cells for Java は、すべての主要なプラットフォームとオペレーティング システムでサポートされています。次の前提条件を満たしていることを確認してください。

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows、または JSP/JSF アプリケーションおよびデスクトップ アプリケーション用の Java ランタイム環境と互換性のある OS。
-  Aspose.Cells for Java の最新バージョンを次から直接入手します。
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells)  .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="ODS ファイルを検索 - Java" offSpacer="" %}}

```cs
// Instantiating a Workbook object
Workbook workbook = new Workbook(dataDir + "book1.ods");

// Accessing the first worksheet in the ODS file
Worksheet worksheet = workbook.getWorksheets().get(0);

// Finding the cell containing the specified formula
Cells cells = worksheet.getCells();

// Instantiate FindOptions
FindOptions findOptions = new FindOptions();

// Finding the cell containing a string value that starts with Or
findOptions.setLookAtType(LookAtType.START_WITH);

Cell cell = cells.find("SH", null, findOptions);

// Printing the name of the cell found after searching 
System.out.println("Name of the cell containing String: " + cell.getName());  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="約 Aspose.Cells for Java API" %}}

 Aspose.Cells API は、Excel 形式を作成、編集、変換し、さまざまな形式にレンダリングするために使用できます。さらに、ソフトウェア アプリケーション内で包括的なグラフ作成、スケーラブルなレポート作成、および信頼性の高い計算に使用できます。 Aspose.Cells はスタンドアロンの API であり、Microsoft や OpenOffice などのソフトウェアは必要ありません。



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="オンライン ODS ライブデモを検索" sectionDescription="にアクセスして、ODS 文書内のテキスト、単語、フレーズを今すぐ検索してください。[ライブデモ Web サイト](https://products.aspose.app/cells/search)。ライブデモには次の利点があります" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Aspose API をダウンロードする必要はありません。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text="コードを記述する必要はありません。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text="ODS ファイルをアップロードするだけです。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text="検索結果は即座に表示されます。" >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODS " readMoreLink="https://docs.fileformat.com/spreadsheet/ods/" >}}
拡張子 ODS のファイルは、ユーザーが編集可能な OpenDocument スプレッドシート ドキュメント形式を表します。データは ODF ファイル内の行と列に保存されます。これは XML ベースの形式であり、Open Document Formats (ODF) ファミリのいくつかのサブタイプの 1 つです。この形式は、OASIS によって公開および保守されている ODF 1.2 仕様の一部として指定されています。 Windows 上の多くのアプリケーションや他のオペレーティング システムでは、ODS Excel、NeoOffice、LibreOffice などの ODS ファイルを開いて編集および操作できます。 ODS ファイルは、別のアプリケーションで XLS、XLSX などの他のスプレッドシート形式に変換することもできます。

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている検索ドキュメント" subTitle="Java を使用すると、次のファイルを含む他のファイルも検索できます。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/csv/" name="CSV" description="カンマ区切り値" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/tsv/" name="TSV" description="タブ区切りの値" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/txt/" name="TXT" description="テキストドキュメント" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/xls/" name="XLS" description="Excel バイナリ形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/xlsb/" name="XLSB" description="バイナリ Excel ワークブック ファイル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/xlsm/" name="XLSM" description="スプレッドシート ファイル" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
