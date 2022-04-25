---
title: Split Excel Worksheet sheet wise in C#
url: /net/splitter/
description: C# source codes that explains how to split Microsoft Excel files into multiple files in Visual C#.NET applications
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel File Splitting via .NET" h2="Split single Excel document into different files using C# code within .NET based applications" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Excel Library](/cells/net/) is capable to split Excel document into multiple spreadsheets within .NET based applications. Supported file formats include XLS, XLSX, XLSB, XLSM, ODS.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Split Excel Document into Multiple Files" %}}
The simplest way to split Excel files sheet wise is, Accessing all sheets via [Worksheets](https://apireference.aspose.com/cells/net/aspose.cells/workbook/properties/worksheets), Iterating through each sheet and calling the [Copy](https://apireference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy) method. Finally saving it into a specified path. 

+  Load the Excel file with full path using [Workbook class](https://apireference.aspose.com/cells/net/aspose.cells/workbook).
+  Iterate throug each sheet
+  Create a new Workbook class object
+  Copy the sheet via [Copy method](https://apireference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy)
+  Call the Save() method and pass the file name (full path) having relevant SaveFormat.

{{% blocks/products/pf/feature-page-code h3="C# Code to Split Excel Files" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter">}}

{{% blocks/products/pf/feature-page-section  h2="Split Excel Worksheet into Panes" %}}

For splitting worksheet window into panes, API provides [Split method](https://apireference.aspose.com/cells/net/aspose.cells/worksheet/methods/split) of worksheet class, that provides the splitted view of worksheet. To remove splitted view API provides [RemoveSplit method](https://apireference.aspose.com/cells/net/aspose.cells/worksheet/methods/removesplit). Finally save it into a specified path. 

{{% blocks/products/pf/feature-page-code h3="C# Code to Split Excel Worksheet Window" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet-into-pane.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% blocks/products/pf/feature-page-code h3="C# Code to Remove Splitted Pan View" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "remove-splitted-spreadsheet-pane-view.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}
