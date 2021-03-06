---
title: Javaを介してSXCをPNGに変換する 
url: /ja/java/conversion/sxc-to-png/ 
description: SXC形式からPNGファイルへのサンプルJava変換コード。プログラマーは、このサンプルコードを使用して、WebまたはデスクトップJavaベースのアプリケーション内でExcelおよびOpenOfficeスプレッドシートをPNGにエクスポートできます。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Javaを介してSXCをPNGに変換する" h2="オンプレミスJavaライブラリを使用して単一または複数のページをPNGに変換するSXCからPNGJavaへの変換。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PNG" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="SXC" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Javaを使用してSXCをPNGに変換する方法" %}}

 SXCをPNGにレンダリングするために、
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

{{% blocks/products/pf/agp/feature-section-col title="Javaを介してSXCをPNGに変換する手順" %}}

{{% blocks/products/pf/agp/text %}}

 Java開発者は、わずか数行のコードでSXCファイルをPNGに簡単に変換できます。

{{% /blocks/products/pf/agp/text %}}

1. Workbookのインスタンスを含むSXCファイルをロードします1. コレクションからデフォルトまたは任意のワークシートを選択します1. ImageOrPrintOptionsのオブジェクトを作成および設定します1. Worksheet＆ImageOrPrintOptionsオブジェクトを使用してSheetRenderを作成する1. SheetRender.toImageメソッドを呼び出して、結果をPNG形式で保存します

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="システム要求" %}}

{{% blocks/products/pf/agp/text %}}

 Java変換ソースコードを実行する前に、次の前提条件があることを確認してください。

{{% /blocks/products/pf/agp/text %}}

- MicrosoftWindowsまたはJSP/JSFアプリケーションおよびデスクトップアプリケーション用のJavaランタイム環境と互換性のあるOS。- Mavenから直接Aspose.Cellsfor Javaの最新バージョンを入手します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="SXCからPNGJavaへの変換ソースコード" offSpacer="" %}}

```cs
// レンダリングするSXCファイルをロードします
Workbook workbook = new Workbook("sourceFile.sxc");
// コレクションからデフォルトのワークシートにアクセスする
Worksheet worksheet = workbook.getWorksheets().get(0);
// 結果の画像のパラメータを定義する
ImageOrPrintOptions options = new ImageOrPrintOptions();
options.setOnePagePerSheet(true);
options.setImageType(ImageType.PNG);
// ワークシートをPNG形式の画像に変換します
SheetRender renderer = new SheetRender(worksheet, options);
renderer.toImage(0, "output.png");   
   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="SXCからPNGへの変換ライブデモ" sectionDescription="[SXCをPNGに変換する](https://products.aspose.app/cells/conversion/sxc-to-png) 今すぐライブデモのウェブサイトにアクセスしてください。ライブデモには次の利点があります。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" AsposeAPIをダウンロードする必要はありません。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" コードを書く必要はありません。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" SXCファイルをアップロードするだけで、すぐにPNGに変換されます。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" ダウンロードリンクが表示されます。" >}}

    {{% blocks/products/pf/agp/content h2="Javaスプレッドシート操作ライブラリ" %}}

 Excel APIを使用して、Microsoft Excel形式を作成、編集、変換、およびさまざまな形式にレンダリングできます。さらに、ソフトウェアアプリケーション内での包括的なグラフ作成、スケーラブルなレポート作成、および信頼性の高い計算に使用できます。 Aspose.CellsはスタンドアロンAPIであり、MicrosoftやOpenOfficeなどのソフトウェアは必要ありません。  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="SXC" readMoreLink="https://docs.fileformat.com/spreadsheet/sxc/" >}}

ファイル形式SXC（Sun XML Calc）は、OpenOffice.orgというオフィススイートに属しています。この形式は、XMLベースのスプレッドシートファイル形式であるため、通常、ユーザーのスプレッドシートのニーズに対応します。 SXC形式は、数式、関数、マクロ、チャートをDataPilotとともにサポートします。これは、インポートされた生データの要約を自動的に個別化して提供するため、すばらしい機能です。このソフトウェアで作成されたファイルは、拡張子.sxcで保存されます。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PNG" readMoreLink="https://docs.fileformat.com/image/png/" >}}

PNG（Portable Network Graphics）は、ロスレス圧縮を使用するラスターイメージファイル形式の一種を指します。このファイル形式は、Graphics Interchange Format（GIF）の代わりとして作成されたものであり、著作権の制限はありません。ただし、PNGファイル形式はアニメーションをサポートしていません。 PNGファイル形式は、ユーザーの間で人気のあるロスレス画像圧縮をサポートしています。時間の経過とともに、PNGは最もよく使用される画像ファイル形式の1つとして進化してきました。ほとんどすべてのオペレーティングシステムは、PNGファイルを開くことをサポートしています。たとえば、Microsoft Windowsビューアには、OSがデフォルトでインストールの一部として利用可能なサポートを備えているため、PNGファイルを開く機能があります。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}