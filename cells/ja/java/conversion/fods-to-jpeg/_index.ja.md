---
title: Javaを介してFODSをJPEGに変換します 
url: /ja/java/conversion/fods-to-jpeg/ 
description: FODS形式からJPEGファイルへのサンプルJava変換コード。プログラマーは、このサンプルコードを使用して、任意のWebまたはデスクトップJavaベースのアプリケーション内でExcelおよびOpenOfficeスプレッドシートをJPEGにエクスポートできます。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Javaを介してFODSをJPEGに変換します" h2="オンプレミスJavaライブラリを使用して単一または複数のページをJPEGに変換するためのFODSからJPEGJavaへの変換。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="JPEG" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="FODS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Javaを使用してFODSをJPEGに変換する方法" %}}

 FODSをJPEGにレンダリングするために、
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

{{% blocks/products/pf/agp/feature-section-col title="Javaを介してFODSをJPEGに変換する手順" %}}

{{% blocks/products/pf/agp/text %}}

 Java開発者は、わずか数行のコードでFODSファイルをJPEGに簡単に変換できます。

{{% /blocks/products/pf/agp/text %}}

1. Workbookのインスタンスを含むFODSファイルをロードします1. コレクションからデフォルトまたは任意のワークシートを選択します1. ImageOrPrintOptionsのオブジェクトを作成および設定します1. Worksheet＆ImageOrPrintOptionsオブジェクトを使用してSheetRenderを作成する1. SheetRender.toImageメソッドを呼び出して、結果をJPEG形式で保存します

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="システム要求" %}}

{{% blocks/products/pf/agp/text %}}

 Java変換ソースコードを実行する前に、次の前提条件があることを確認してください。

{{% /blocks/products/pf/agp/text %}}

- MicrosoftWindowsまたはJSP/JSFアプリケーションおよびデスクトップアプリケーション用のJavaランタイム環境と互換性のあるOS。- Mavenから直接Aspose.Cellsfor Javaの最新バージョンを入手します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="FODSからJPEGJavaへの変換ソースコード" offSpacer="" %}}

```cs
// レンダリングするFODSファイルをロードします
Workbook workbook = new Workbook("sourceFile.fods");
// コレクションからデフォルトのワークシートにアクセスする
Worksheet worksheet = workbook.getWorksheets().get(0);
// 結果の画像のパラメータを定義する
ImageOrPrintOptions options = new ImageOrPrintOptions();
options.setOnePagePerSheet(true);
options.setImageType(ImageType.JPEG);
// ワークシートをJPEG形式の画像に変換します
SheetRender renderer = new SheetRender(worksheet, options);
renderer.toImage(0, "output.jpeg");   
   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="FODSからJPEGへの変換ライブデモ" sectionDescription="[FODSをJPEGに変換する](https://products.aspose.app/cells/conversion/fods-to-jpeg) 今すぐライブデモのウェブサイトにアクセスしてください。ライブデモには次の利点があります。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" AsposeAPIをダウンロードする必要はありません。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" コードを書く必要はありません。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" FODSファイルをアップロードするだけで、すぐにJPEGに変換されます。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" ダウンロードリンクが表示されます。" >}}

    {{% blocks/products/pf/agp/content h2="Javaスプレッドシート操作ライブラリ" %}}

 Excel APIを使用して、Microsoft Excel形式を作成、編集、変換、およびさまざまな形式にレンダリングできます。さらに、ソフトウェアアプリケーション内での包括的なグラフ作成、スケーラブルなレポート作成、および信頼性の高い計算に使用できます。 Aspose.CellsはスタンドアロンAPIであり、MicrosoftやOpenOfficeなどのソフトウェアは必要ありません。  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="FODS" readMoreLink="https://docs.fileformat.com/spreadsheet/fods/" >}}

拡張子が.fodsのファイルは、データを行と列に格納するOpenDocumentスプレッドシートドキュメント形式の一種です。このフォーマットは、OASISによって公開および保守されているODF1.2仕様の一部として指定されています。 FODSファイルは、Microsoftの別のスプレッドシートソフトウェアアプリケーションであるExcelで開くことはできません。 FODSファイルはLibreOfficeを使用してODSとして保存でき、XLSやXLSXなどの他の形式に変換できます。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="JPEG" readMoreLink="https://docs.fileformat.com/image/jpeg/" >}}

JPEGは、非可逆圧縮方式を使用して保存される画像形式の一種です。圧縮の結果としての出力画像は、ストレージサイズと画質の間のトレードオフです。ユーザーは、圧縮レベルを調整して目的の品質レベルを達成すると同時に、ストレージサイズを減らすことができます。 10：1の圧縮が画像に適用されている場合、画質への影響はごくわずかです。圧縮値が高いほど、画質の低下が大きくなります。 JPEG画像ファイル形式はJointPhotographicExperts Groupによって標準化されたため、JPEGという名前が付けられました。このフォーマットは、写真画像をWeb上に保存および送信するための選択肢です。現在、ほとんどすべてのオペレーティングシステムには、JPEG画像の視覚化をサポートするビューアがあります。JPEG画像は、JPG拡張子で保存されることもよくあります。 WebブラウザでさえJPEG画像の視覚化をサポートしています。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}