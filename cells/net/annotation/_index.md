---
title: Excel File Annotations NET C#
url: /net/annotation/
description: Add or remove data annotation of Excel and OpenOffice spreadsheets with just few lines of C# code.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Remove Microsoft<sup>&reg;</sup> Excel File Annotations via .NET" h2="Add or delete Excel files annotations using C# code within .NET based applications." >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Excel Library](/cells/net/) provides support to manage annotations at cell level by adding, accessing and removing comments. Using comments at cell level, relevant information can be stored for end users. Supported file formats include ODS, XLS, XLSX, XLSB and XLSM.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Excel Files Data Annotations" %}}
Managing Comments in Worksheets - There is not any limit that how many comments a sheet has in MS Excel. One can add as much as of application requirement. We will use the [Comment Class](https://apireference.aspose.com/cells/net/aspose.cells/comment) for all of this functionality.

+  Load Excel file using Workbook class object
+  Acess the relevant Worksheet and its relevant Cell index
+  Call RemoveAt with the Cell Id to remove it
+  Use [Note property](https://apireference.aspose.com/cells/net/aspose.cells/comment/properties/note) for adding comments content 
+  Save the workbook before & after calling RemoveAt method to compare

{{% blocks/products/pf/feature-page-code h3="C# Code to Access, Insert and Delete Excel Files Cell Comments" %}}

```cs
// load an existing ODS
var wkb = new Workbook("source-file.ods");

// add comment to cell A1 of first worksheet
int commentIndex = wkb.Worksheets[0].Comments.Add("A1");

// access to comment object to set its text
var comment = wkb.Worksheets[0].Comments[commentIndex];

comment.Note = "This is my comment";
// save as ODS file
wkb.Save("annotation-inserted.xlsx");

// remove comments on cell A2
wkb.Worksheets[0].Comments.RemoveAt("A2");

// save the book again to compare
wkb.Save("annotation-deleted.ods");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation">}}