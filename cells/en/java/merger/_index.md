---
title: Merge Different Excel Files into a Single One in Java
url: /java/merger/
description: Merge Excel files using Java into multiple sheets or single sheet. Merge, combine, or concatenate Excel documents to PDF, Images and HTML as well.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel File Merging via Java" h2="Combine two or more Excel files in a single spreadsheet using Java code" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Excel Library](/cells/java/) provides multiple ways to combine workbooks with various types of content like formulas, images, data, charts etc into a single spreadsheet document. Supported file formats include XLS, XLSX, XLSB, XLT, XLTX, XLTM, ODS, CSV, TSV and more.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Combine Excel Files with Images and Charts" %}}
The simplest way to combine two Excel files having images & charts is by calling the [Workbook.combine](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#combine(com.aspose.cells.Workbook)) method. It allows to merge Excel files of similar type into a single spreadsheet.
{{% blocks/products/pf/feature-page-code h3="Java Code to Combine Excel Files" %}}

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
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Merge Multiple Excel Files" %}}
[CellsHelper.mergeFiles](https://apireference.aspose.com/cells/java/com.aspose.cells/cellshelper#mergeFiles) method supports merging data, style and formulas of an Excel file to a new spreadsheet of same format. It is an efficient way to merge several files while using caching. 
{{% blocks/products/pf/feature-page-code h3="Java Code to Merge Several Excel Files" %}}

```cs
// create an Array (length=2)
String[] files = new String[2];
// specify file paths to be merged
files[0] = "Book1.xls";
files[1] = "Book2.xls";
// merge the files to save the result
CellsHelper.mergeFiles(files, "cache", "merged.xls");

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Merge Excel Files by Copying Worksheets" %}}
[Worksheet.copy](https://apireference.aspose.com/cells/java/com.aspose.cells/worksheet#copy(com.aspose.cells.Worksheet)) can used to copy data and formatting from a source worksheet to another worksheet within or between workbooks. The method takes the source worksheet object as a parameter.
{{% blocks/products/pf/feature-page-code h3="Java Code to Copy Worksheets between Workbooks" %}}

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
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Merger">}}