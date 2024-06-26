---
title: 透かし XLS 文書 via Java
weight: 2210
description: Java サンプル コード。JSP/JSF アプリケーションおよびデスクトップ アプリケーションの Java ランタイム環境の XLS ファイルに透かしを追加または削除します。
keywords: [Java Aspose.Cells., Java add watermark to xls file., Java insert watermark to xls file., Java create watermark in xls file., remove watermark from xls file using Java., Java operate watermark in xls file., Java access watermark in xls file]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="XLS via Java にテキスト透かしを追加" h2="サーバー側 API を使用して XLS ファイルに透かしを入れるための独自の Java アプリを構築します。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLS" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Java を使用して XLS ファイルに透かしを入れる方法" %}}

XLSファイルに透かしを入れるには、[Aspose.Cells for Java](https://products.aspose.com/cells/java) API は、機能が豊富で強力で使いやすいウォーターマーク API for Java プラットフォームです。最新バージョンは、以下から直接ダウンロードできます。[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) pom.xml に次の構成を追加して、Maven ベースのプロジェクト内にインストールします。

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

{{% blocks/products/pf/agp/feature-section-col title="XLS via Java に透かしを追加する手順" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. 新しいワークブックオブジェクトを作成する
1. インデックスからワークシートを選択
1. シェイプを作成し、addTextEffect関数を使用する
1. 色、透明度などを設定する
1. ワークブックを XLS 形式で保存

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="システム要求" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java はすべての主要なプラットフォームとオペレーティング システムでサポートされています。次の前提条件を満たしていることを確認してください。

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows または Java JSP/JSF アプリケーションおよびデスクトップ アプリケーション用のランタイム環境を備えた互換性のある OS。
- Maven から直接、Aspose.Cells for Java の最新バージョンを入手してください。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XLS - Java に透かしを追加する" offSpacer="" %}}

```cs

// Instantiate a new Workbook
Workbook workbook = new Workbook();

// Get the first default sheet
Worksheet sheet = workbook.getWorksheets().get(0);

// Add Watermark
Shape wordart = sheet.getShapes().addTextEffect(MsoPresetTextEffect.TEXT_EFFECT_1, "CONFIDENTIAL",
		"Arial Black", 50, false, true, 18, 8, 1, 1, 130, 800);

// Get the fill format of the word art
FillFormat wordArtFormat = wordart.getFill();

// Set the color
wordArtFormat.setOneColorGradient(Color.getRed(), 0.2, GradientStyleType.HORIZONTAL, 2);

// Set the transparency
wordArtFormat.setTransparency(0.9);

// Make the line invisible
LineFormat lineFormat = wordart.getLine();
lineFormat.setWeight(0.0);

// Save the file
workbook.save(dataDir + "AWArtWToWorksheet_out.xls");  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Aspose.Cells for Java APIについて" %}}

Aspose.Cells API は、Microsoft Excel 形式をさまざまな形式に作成、編集、変換、レンダリングするために使用できます。さらに、ソフトウェア アプリケーション内で包括的なグラフ作成、スケーラブルなレポート作成、信頼性の高い計算に使用できます。Aspose.Cells はスタンドアロンの API であり、Microsoft や OpenOffice などのソフトウェアは必要ありません。



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="ウォーターマーク XLS オンラインアプリ経由" sectionDescription="XLS文書に透かしを追加するには、[ライブデモのウェブサイト](https://products.aspose.app/cells/watermark)ライブデモには以下の利点があります" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text="ダウンロードや設定は一切不要" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text="コードを書く必要はありません" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="XLSファイルをアップロードし、透かしを設定して「追加」ボタンを押すだけです" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text="結果ファイルのダウンロードリンクを即座に取得" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}
XLS 拡張子のファイルは、Excel バイナリ ファイル形式を表します。このようなファイルは、Microsoft Excel だけでなく、OpenOffice Calc や Apple Numbers などの他の同様のスプレッドシート プログラムでも作成できます。Excel によって保存されたファイルはワークブックと呼ばれ、各ワークブックには 1 つ以上のワークシートを含めることができます。データはワークシートにテーブル形式で保存され、ユーザーに表示されます。データは数値、テキスト データ、数式、外部データ接続、画像、グラフにまたがることができます。Microsoft Excel などのアプリケーションでは、PDF、CSV、XLSX、TXT、HTML、XPS など、さまざまな形式でワークブック データをエクスポートできます。 XLS ファイル形式は、Microsoft Excel 2007 のリリースにより、よりオープンで構造化された形式である XLSX に置き換えられました。最新バージョンでは、XLS ファイルの作成と読み取りが引き続きサポートされていますが、現在は XLSX が第一選択として使用されています。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="サポートされているその他の透かしフォーマット" subTitle="Java を使用すると、次のようなさまざまな形式に簡単に透かしを入れることができます。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/watermark/ods/" name="ODS" description="OpenDocument スプレッドシート ファイル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/watermark/xlsb/" name="XLSB" description="バイナリ Excel ワークブック ファイル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/watermark/xlsm/" name="XLSM" description="スプレッドシートファイル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/watermark/xlsx/" name="XLSX" description="OOXML Excel ファイル" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
