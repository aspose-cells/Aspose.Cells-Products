---
title: Excel File Merger API .NET C#
url: /net/merger/
description: Concatenate Excel & OpenOffice spreadsheet files with just few lines of C# code.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel File Merging via .NET" h2="Combine 2 or more spreadsheets in a single file using C# code" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Excel Library](/cells/net/) provides multiple ways to combine workbooks with various types of content like formulas, data, images, charts and so on into a single spreadsheet file. Supported file formats include XLS, XLSX, XLSB, XLT, XLTX, XLTM, ODS, CSV, TSV and more.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Combine Excel Files with Images and Charts" %}}
The simplest way to combine 2 Excel files having images & charts is by calling the [Workbook.Combine](https://apireference.aspose.com/cells/net/aspose.cells/workbook/methods/combine) method. It allows to merge Excel files of similar type into a single spreadsheet.
{{% blocks/products/pf/feature-page-code h3="C# Code for Excel File Format conversion" %}}

```cs
// load first Excel file
Workbook SourceBook1 = new Workbook("SampleChart.xlsx");
// load second Excel file into a separate instance
Workbook SourceBook2 = new Workbook("SampleImage.xlsx");

// combine two workbooks
SourceBook1.Combine(SourceBook2);
// save the target workbook 
SourceBook1.Save("combined.xlsx");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Merge Multiple Excel Files" %}}
[CellsHelper.MergeFiles](https://apireference.aspose.com/cells/net/aspose.cells/cellshelper/methods/mergefiles) method supports merging data, style and formulas of an Excel file to a new spreadsheet of same format. It is an efficient way to merge several files while using caching. 
{{% blocks/products/pf/feature-page-code h3="C# Code to Merge Several Excel Files" %}}

```cs
// create an Array (length=2)
String[] files = new String[2];
// specify file paths to be merged
files[0] = "Book1.xls";
files[1] = "Book2.xls";
// merge the files to save the result
Aspose.Cells.CellsHelper.MergeFiles(files, "cache", "merged.xls");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Merge Excel Files by Copying Worksheets" %}}
[Worksheet.Copy](https://apireference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy/index) can used to copy data and formatting from a source worksheet to another worksheet within or between workbooks. The method takes the source worksheet object as a parameter.
{{% blocks/products/pf/feature-page-code h3="C# Code to Copy Worksheets Across Excel Files" %}}

```cs
// load spreadsheet files into 2 instances of Workbook
var book1 = new Aspose.Cells.Workbook("input.xlsx");
var book2 = new Aspose.Cells.Workbook("input.ods");
// loop over the worksheet collection
foreach (var sheet in book1.Worksheets)
{
    // add a blank worksheet
    book2.Worksheets.Add(sheet.Name);
    // copy worksheet from source to target
    book2.Worksheets[sheet.Name].Copy(sheet);
}
// Save the file in any spreadsheet format
book2.Save("combined.xls", Aspose.Cells.SaveFormat.Auto);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Merger">}}