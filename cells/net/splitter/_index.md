---
title: Split Excel Worksheet into Panes in C#
url: /net/splitter/
description: C# source codes that explains how to split Microsoft Excel files into multiple panes in Visual C#.NET applications.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel File splitting via .NET" h2="Split single Excel file into panes using C# code within .NET based applications" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Excel Library](/cells/net/) is capable to split Excel document into panes within .NET based applications. Supported file formats include XLS, XLSX, XLSB, XLSM, ODS.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Split Excel File into Panes" %}}
The simplest way to split Excel files into panes is by calling the [Worksheet.Split](https://apireference.aspose.com/cells/net/aspose.cells/worksheet/methods/split) method. Then saving it into a specified path. After splitting it into panes, one can easily view and compare data in different parts of the same worksheet.

+  Load the Excel file with full path using [Workbook class](https://apireference.aspose.com/cells/net/aspose.cells/workbook).
+  Iterate throug each sheet
+  Create a new Workbook class object
+  Copy the sheet via [Copy method](https://apireference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy)
+  Call the Save() method and pass the file name (full path) having relevant SaveFormat.

{{% blocks/products/pf/feature-page-code h3="C# Code to Split Excel Files" %}}

```cs
var wkb = new Workbook("D:\\book3.xlsx");
foreach(Worksheet sht in wkb.Worksheets)
{
    var bk = new Workbook();
    bk.Worksheets[0].Copy(sht);
    bk.Save("D:\\" + sht.Name + ".xlsx", SaveFormat.Xlsx);
}
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter">}}