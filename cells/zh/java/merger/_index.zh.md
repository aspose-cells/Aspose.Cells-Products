---
title: 在 Java 中将不同的 Excel 文件合并为一个
url: /zh/java/merger/
description: 使用 Java 将 Excel 文件合并到多个工作表或单个工作表中。也可以将 Excel 文档合并、合并或连接为 PDF、图像和 HTML。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> 通过 Java 合并 Excel 文件" h2="使用 Java 代码将两个或多个 Excel 文件合并到一个电子表格中" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Excel 库](/cells/java/) 提供多种方式将工作簿与各种类型的内容（如公式、图像、数据、图表等）组合到单个电子表格文档中。支持的文件格式包括 XLS、XLSX、XLSB、XLT、XLTX、XLTM、ODS、CSV、TSV 等。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="将 Excel 文件与图像和图表相结合" %}}
合并两个具有图像和图表的 Excel 文件的最简单方法是调用 [工作簿.combine](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#combine(com.aspose.cells.Workbook)） 方法。它允许将类似类型的 Excel 文件合并到一个电子表格中。
{{% blocks/products/pf/feature-page-code h3="Java 合并 Excel 文件的代码" %}}

```cs
// 加载第一个 Excel 文件
var book1 = new Workbook("with-charts.xlsx");
// 将第二个 Excel 文件加载到单独的实例中
var book2 = new Workbook("with-images.xlsx");

// 合并两个工作簿
book1.combine(book2);
// 保存目标工作簿 
book1.save("combined.xlsx");

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="合并多个 Excel 文件" %}}
[CellsHelper.mergeFiles](https://apireference.aspose.com/cells/java/com.aspose.cells/cellshelper#mergeFiles) 方法支持将 Excel 文件的数据、样式和公式合并到相同格式的新电子表格中。这是在使用缓存时合并多个文件的有效方法。 
{{% blocks/products/pf/feature-page-code h3="Java 合并多个 Excel 文件的代码" %}}

```cs
// 创建一个数组（长度=2）
String[] files = new String[2];
// 指定要合并的文件路径
files[0] = "Book1.xls";
files[1] = "Book2.xls";
// 合并文件以保存结果
CellsHelper.mergeFiles(files, "cache", "merged.xls");


```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="通过复制工作表合并 Excel 文件" %}}
[工作表.copy](https://apireference.aspose.com/cells/java/com.aspose.cells/worksheet#copy(com.aspose.cells.Worksheet)可用于将数据和格式从源工作表复制到工作簿内或工作簿之间的另一个工作表。该方法将源工作表对象作为参数。
{{% blocks/products/pf/feature-page-code h3="Java 在工作簿之间复制工作表的代码" %}}

```cs
// 创建工作簿。
Workbook excelWorkbook0 = new Workbook(dataDir + "book1.xls");

// 创建另一个工作簿。
Workbook excelWorkbook1 = new Workbook();

// 将第一本书的第一页复制到第二本书中。
excelWorkbook1.getWorksheets().get(0).copy(excelWorkbook0.getWorksheets().get(0));

// 保存文件。
excelWorkbook1.save(dataDir + "out.xls", FileFormatType.EXCEL_97_TO_2003);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Merger" >}}