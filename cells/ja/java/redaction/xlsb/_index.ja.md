---
title: XLSB 文書 via Java 内のテキストを検索して置換する
weight: 4590
description: Java サンプル コードは、JSP/JSF アプリケーションおよびデスクトップ アプリケーションの Java ランタイム環境の XLSB ファイル内の機密情報を編集します。
keywords: [Java Aspose.Cells., Java Search and replace text in XLSB file., Java redact XLSB file., Java edit XLSB file., Java XLSB file redaction., Java Search and replace string in XLSB file]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Java の XLSB 形式を編集する" h2="Microsoft や Adobe PDF などのソフトウェアを使用せずに、サーバー側の Aspose.Cells for Java API を使用して、ネイティブで高性能な XLSB ドキュメントの機密編集情報を作成します。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLSB" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Java を使用して XLSB ファイルを編集する方法" %}}

XLSBファイルを編集するには、[Aspose.Cells for Java](https://products.aspose.com/cells/java) API は、機能が豊富で強力で使いやすい編集プラットフォームです。最新バージョンは、以下から直接ダウンロードできます。[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) pom.xml に次の構成を追加して、Maven ベースのプロジェクト内にインストールします。

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

{{% blocks/products/pf/agp/feature-section-col title="Java 内の XLSB ファイルを編集する手順" %}}

{{% blocks/products/pf/agp/text %}}

基本的なドキュメント検索とコンテンツ、コメント、メタデータ内のテキストの置換[Aspose.Cells for Java](https://products.aspose.com/cells/java)API はわずか数行のコードで実現できます。

{{% /blocks/products/pf/agp/text %}}

+ XLSB ファイルをロードします。
+ 該当するシートを選択します。
+ FindOptions を定義して指定します。
+ 検索したい範囲を指定します
各セルをループし、getCells().find(...) を使用します。
+ 値を置き換えます。
ワークブックを保存します。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="システム要求" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java はすべての主要なプラットフォームとオペレーティング システムでサポートされています。次の前提条件を満たしていることを確認してください。

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows または Java JSP/JSF アプリケーションおよびデスクトップ アプリケーション用のランタイム環境を備えた互換性のある OS。
-  Aspose.Cells for Javaの最新バージョンを直接入手
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells)  .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XLSB ファイルを編集 - Java" offSpacer="" %}}

```cs
Workbook workbook = new Workbook(dataDir + "sourceFile.xlsb");

Worksheet worksheet = workbook.getWorksheets().get(0);

// Specify the range where you want to search
// Here the range is E3:H6
CellArea area = CellArea.createCellArea("E3", "H6");

// Specify Find options
FindOptions opts = new FindOptions();
opts.setLookInType(LookInType.VALUES);
opts.setLookAtType(LookAtType.ENTIRE_CONTENT);
opts.setRange(area);

Cell cell = null;

do {
	// Search the cell with value search within range
	cell = worksheet.getCells().find("search", cell, opts);

	// If no such cell found, then break the loop
	if (cell == null)
		break;

	// Replace the cell with value replace
	cell.putValue("replace");

} while (true);

// Save the workbook
workbook.save(dataDir + "output.xlsb");

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="Aspose.Cells for Java APIについて" %}}

Aspose.Cells API は、Microsoft Excel 形式をさまざまな形式に作成、編集、変換、レンダリングするために使用できます。さらに、ソフトウェア アプリケーション内で包括的なグラフ作成、スケーラブルなレポート作成、信頼性の高い計算に使用できます。Aspose.Cells はスタンドアロンの API であり、Microsoft や OpenOffice などのソフトウェアは必要ありません。



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="オンライン XLSB 編集ライブデモ" sectionDescription="XLSB文書のコンテンツ、コメント、メタデータ内のテキストを検索して置換するには、今すぐ[ライブデモのウェブサイト](https://products.aspose.app/cells/redaction)ライブデモには以下の利点があります" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text="Aspose API をダウンロードする必要はありません。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text="コードを書く必要はありません。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" XLSB ファイルをアップロードするだけです。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text="すぐに編集されます。" >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSB" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsb/" >}}
XLSB ファイル形式は、Excel ブックの内容を指定するレコードと構造のコレクションである Excel バイナリ ファイル形式を指定します。内容には、数値、テキスト、または数値とテキストの両方、数式、外部データ接続、グラフ、および画像からなる非構造化または半構造化テーブルを含めることができます。XLSX (Open XML ファイル形式に基づく) とは異なり、XLSB はバイナリ Excel ブック ファイルを表します。XLSB ファイルは読み取りと書き込みが高速であるため、大きなファイルの操作に役立ちます。XLSB はブックの保存にはあまり使用されません。XLSX (および以前の XLS) は、ブックを保存するためにユーザーが選択する最も一般的なファイル形式です。Microsoft Office 2007 以降で開くことができます。

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている編集ドキュメント" subTitle="Java を使用すると、次のようなさまざまな形式を簡単に編集できます。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/redaction/ods/" name="ODS" description="OpenDocument スプレッドシート ファイル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/redaction/xls/" name="XLS" description="Excel バイナリ形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/redaction/xlsm/" name="XLSM" description="スプレッドシートファイル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/redaction/xlsx/" name="XLSX" description="OOXML Excel ファイル" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
