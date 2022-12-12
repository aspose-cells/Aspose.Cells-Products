---
title: 異なるExcelファイルをJavaの1つのファイルにマージします

description: Javaを使用してExcelファイルを複数のシートまたは単一のシートにマージします。 ExcelドキュメントをPDF、画像、HTMLにマージ、結合、または連結します。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft <sup>＆reg; </sup>Javaを介したExcelファイルのマージ" h2="Javaコードを使用して、2つ以上のExcelファイルを1つのスプレッドシートに結合します" >}}
{{% blocks/products/pf/feature-page-summary %}}
[JavaExcelライブラリ](/cells/java/) ワークブックを数式、画像、データ、チャートなどのさまざまなタイプのコンテンツと組み合わせて1つのスプレッドシートドキュメントにする複数の方法を提供します。サポートされているファイル形式には、XLS、XLSX、XLSB、XLT、XLTX、XLTM、ODS、CSV、TSVなどがあります。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excelファイルを画像やグラフと組み合わせる" %}}
画像とグラフを含む2つのExcelファイルを組み合わせる最も簡単な方法は、 [Workbook.combine](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#combine(com.aspose.cells.Workbook)） 方法。これにより、同様のタイプのExcelファイルを1つのスプレッドシートにマージできます。
{{% blocks/products/pf/feature-page-code h3="JavaExcelファイルを結合するコード" %}}

```cs
// 最初のExcelファイルをロードする
var book1 = new Workbook("with-charts.xlsx");
// 2番目のExcelファイルを別のインスタンスにロードします
var book2 = new Workbook("with-images.xlsx");

// 2つのワークブックをマージする
book1.combine(book2);
// ターゲットワークブックを保存します 
book1.save("combined.xlsx");

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="複数のExcelファイルをマージする" %}}
[CellsHelper.mergeFiles](https://reference.aspose.com/cells/java/com.aspose.cells/cellshelper#mergeFiles) methodは、Excelファイルのデータ、スタイル、および式を同じ形式の新しいスプレッドシートにマージすることをサポートします。これは、キャッシングを使用しながら複数のファイルをマージする効率的な方法です。 
{{% blocks/products/pf/feature-page-code h3="Java複数のExcelファイルをマージするコード" %}}

```cs
// 配列を作成します（長さ= 2）
String[] files = new String[2];
// マージするファイルパスを指定します
files[0] = "Book1.xls";
files[1] = "Book2.xls";
// ファイルをマージして結果を保存します
CellsHelper.mergeFiles(files, "cache", "merged.xls");


```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="ワークシートをコピーしてExcelファイルをマージする" %}}
[Worksheet.copy](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet#copy(com.aspose.cells.Worksheet)）ワークブック内またはワークブック間でソースワークシートから別のワークシートにデータとフォーマットをコピーするために使用できます。このメソッドは、ソースワークシートオブジェクトをパラメーターとして受け取ります。
{{% blocks/products/pf/feature-page-code h3="Javaワークブック間でワークシートをコピーするためのコード" %}}

```cs
// ワークブックを作成します。
Workbook excelWorkbook0 = new Workbook(dataDir + "book1.xls");

// 別のワークブックを作成します。
Workbook excelWorkbook1 = new Workbook();

// 最初の本の最初のシートを2番目の本にコピーします。
excelWorkbook1.getWorksheets().get(0).copy(excelWorkbook0.getWorksheets().get(0));

// ファイルを保存します。
excelWorkbook1.save(dataDir + "out.xls", FileFormatType.EXCEL_97_TO_2003);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Merger" >}}
