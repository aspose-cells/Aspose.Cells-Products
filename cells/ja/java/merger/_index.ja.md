---
title: Java で異なる Excel ファイルを 1 つの Excel ファイルに結合する
description: Java を使用して Excel ファイルを複数のシートまたは単一のシートに結合します。 Excel ドキュメントを PDF、画像、および HTML にマージ、結合、または連結します。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel ファイルの結合 via Java" h2="Java コードを使用して、2 つ以上の Excel ファイルを 1 つのスプレッドシートに結合します。" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java エクセルライブラリ](/cells/ja/java/)は、数式、画像、データ、グラフなどのさまざまなタイプのコンテンツを含むワークブックを 1 つのスプレッドシート ドキュメントに結合する複数の方法を提供します。サポートされているファイル形式には、XLS、XLSX、XLSB、XLT、XLTX、XLTM、ODS、CSV、TSVなどが含まれます。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel ファイルと画像やグラフを結合する" %}}
画像とグラフを含む 2 つの Excel ファイルを結合する最も簡単な方法は、[ワークブック.結合](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#combine(com.aspose.cells.Workbook)） 方法。同様のタイプの Excel ファイルを 1 つのスプレッドシートに結合できます。
{{% blocks/products/pf/feature-page-code h3="Java Excel ファイルを結合するコード" %}}

```cs
// load first Excel file
var book1 = new Workbook("with-charts.xlsx");
// load second Excel file into a separate instance
var book2 = new Workbook("with-images.xlsx");

// merge two workbooks
book1.combine(book2);
// save the target workbook 
book1.save("combined.xlsx");
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="複数の Excel ファイルを結合する" %}}
[CellsHelper.mergeFiles](https://reference.aspose.com/cells/java/com.aspose.cells/cellshelper#mergeFiles)このメソッドは、Excel ファイルのデータ、スタイル、数式を同じ形式の新しいスプレッドシートに結合することをサポートします。これは、キャッシュを使用しながら複数のファイルをマージする効率的な方法です。
{{% blocks/products/pf/feature-page-code h3="Java 複数の Excel ファイルを結合するコード" %}}

```cs
// create an Array (length=2)
String[] files = new String[2];
// specify file paths to be merged
files[0] = "Book1.xls";
files[1] = "Book2.xls";
// merge the files to save the result
CellsHelper.mergeFiles(files, "cache", "merged.xls");

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="ワークシートをコピーして Excel ファイルを結合する" %}}
[ワークシート.コピー](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet#copy(com.aspose.cells.Worksheet)を使用して、ソース ワークシートからワークブック内またはワークブック間の別のワークシートにデータと書式設定をコピーできます。このメソッドは、ソース ワークシート オブジェクトをパラメータとして受け取ります。
{{% blocks/products/pf/feature-page-code h3="Java ワークブック間でワークシートをコピーするコード" %}}

```cs
// Create a Workbook.
Workbook excelWorkbook0 = new Workbook(dataDir + "book1.xls");

// Create another Workbook.
Workbook excelWorkbook1 = new Workbook();

// Copy the first sheet of the first book into second book.
excelWorkbook1.getWorksheets().get(0).copy(excelWorkbook0.getWorksheets().get(0));

// Save the file.
excelWorkbook1.save(dataDir + "out.xls", FileFormatType.EXCEL_97_TO_2003);
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている結合形式" subTitle="Java を使用すると、.." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/csv/" name="CSV" description="カンマ区切り値" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/html/" name="HTML" description="ハイパーテキストマークアップ言語" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/mhtml/" name="MHTML" description="Web ページのアーカイブ形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/ods/" name="ODS" description="OpenDocument スプレッドシート ファイル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/tsv/" name="TSV" description="タブ区切りの値" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/txt/" name="TXT" description="テキストドキュメント" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xls/" name="XLS" description="Excel バイナリ形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsb/" name="XLSB" description="バイナリ Excel ワークブック ファイル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsm/" name="XLSM" description="スプレッドシート ファイル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsx/" name="XLSX" description="OOXML Excel ファイル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlt/" name="XLT" description="Microsoft Excel テンプレート" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xltm/" name="XLTM" description="Excel マクロ有効テンプレート" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}
