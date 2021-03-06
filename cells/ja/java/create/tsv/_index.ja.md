---
title: Javaを介してTSVファイルを作成する 
url: /ja/java/create-tsv/ 
description: JavaTSVドキュメントを生成するためのサンプルコード。このコードを使用して、JavaベースのデスクトップまたはWebアプリケーション内にTSVファイルを作成します。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Javaを介してTSVドキュメントを作成する" h2="Javaライブラリを使用してプログラムでネイティブおよび高性能のTSV（タブ区切り値）を作成します。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="TSV" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="" %}}

 実行中のアプリケーション内でTSVファイルを動的に生成するのは簡単です。 MS Officeを必要とせずにTSVドキュメントを最初から作成するために、
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 Javaプラットフォームを使用したスプレッドシートの作成、操作、変換にさまざまな機能を提供するAPI。開発者は、セルデータの更新、チャートやグラフの生成、ピボットテーブルの作成、セルレベルの数式の追加などのコードを簡単に拡張できます。
{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Javaを介してTSVを作成する方法" %}}

{{% blocks/products/pf/agp/text %}}

 開発者は、わずか数行のコードでデータ処理用のさまざまなレポートアプリケーションを実行しながら、TSV（タブ区切り値）を簡単に作成、ロード、変更、および変換できます。

{{% /blocks/products/pf/agp/text %}}

1. のインスタンスを作成します [ワークブッククラス](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook)。1. getWorksheets.get（）メソッドを使用して関連するワークシートにアクセスします。1. 関連するセルを選択し、A1、B3などのセル名を使用して目的のセルに値を入力します。1. save（）メソッドを使用して、ブックをTSV形式で保存します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="システム要求" %}}

{{% blocks/products/pf/agp/text %}}

Java変換サンプルソースコードを実行する前に、次の前提条件があることを確認してください。  

{{% /blocks/products/pf/agp/text %}}

- MicrosoftWindowsまたはJSP/JSFアプリケーションおよびデスクトップアプリケーション用のJavaランタイム環境と互換性のあるOS。- Aspose.Cells for Javaは、次のJavaバージョンをサポートします：J2SE 6.0（1.6）、J2SE 7.0（1.7）、またはそれ以降。- [Mavenから直接Aspose.Cellsfor Javaの最新バージョンを入手します。](https://docs.aspose.com/cells/java/installation/) 
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="次のソースコードは、Javaを使用してTSVファイルを作成する方法を示しています。" offSpacer="" %}}

```cs

// 新しいブックを作成する
Workbook wkb = new Workbook();

// ブックの最初のワークシートにアクセスします。
Worksheet worksheet = wkb.getWorksheets().get(0);

// セルに関連するコンテンツを追加する
worksheet.getCells().get("A1").putValue("ColumnA");
worksheet.getCells().get("B1").putValue("ColumnB")
worksheet.getCells().get("A2").putValue("ValueA")
worksheet.getCells().get("B2").putValue("ValueB")

// ブックをTSVファイルとして保存します
wkb.save("Excel.tsv"); 

// さらなる機能のためにコードを強化するために、ここにもっと多くの機能があります
// セルの内容を変更するためのgetCells（）およびsetValue
// getCharts（）。add（）を使用してチャートを追加します
// ピボットテーブルを作成するためのgetPivotTables（）。add（）
// getCells（）。get（int cell id）.setFormulaセルレベルの数式を追加する


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<!-- aboutfile Starts -->

     
     {{% blocks/products/pf/agp/content h2="" %}}

 TSVファイルを生成、変更、変換、レンダリング、および印刷する機能を備えたクロスプラットフォームアプリケーションを構築できるExcelスプレッドシートプログラミングライブラリ。 Java Excel APIは、スプレッドシート形式間で変換するだけでなく、Excelファイルを画像、PDF、HTML、ODSなどとしてレンダリングできるため、業界標準の形式でドキュメントを交換するのに最適です。



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="TSV" readMoreLink="https://docs.fileformat.com/spreadsheet/tsv/" >}}

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< /blocks/products/pf/agp/about-file-section >}}

          

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされているスプレッドシートの生成" subTitle="以下にリストされているいくつかを含む他のMicrosoftExcelフォーマットを作成することもできます。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create-xls/" name="XLS" description="Microsoft Excelスプレッドシート（レガシー）" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create-xlsx/" name="XLSX" description="XMLワークブックを開く" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create-xlsb/" name="XLSB" description="Excelバイナリワークブック" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create-xlsm/" name="XLSM" description="マクロ対応スプレッドシート" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create-xlt/" name="XLT" description="Excel97-2003テンプレート" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create-xltx/" name="XLTX" description="Excelテンプレート" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create-xltm/" name="XLTM" description="Excelマクロ対応テンプレート" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create-csv/" name="CSV" description="カンマ区切り値" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create-tsv/" name="TSV" description="タブ区切り値" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create-ods/" name="ODS" description="OpenDocumentスプレッドシート" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
