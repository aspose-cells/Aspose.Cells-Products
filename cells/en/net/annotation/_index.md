---
title: Excel File Annotations NET C#

description: Add or remove data annotation of Excel and OpenOffice spreadsheets with just few lines of C# code.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Remove Microsoft<sup>&reg;</sup> Excel File Annotations via .NET" h2="Add or delete Excel files annotations using C# code within .NET based applications." >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Excel Library](/cells/net/) provides support to manage annotations at cell level by adding, accessing and removing comments. Using comments at cell level, relevant information can be stored for end users. Supported file formats include ODS, XLS, XLSX, XLSB and XLSM.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Excel Files Data Annotations" %}}
Managing Comments in Worksheets - There is not any limit that how many comments a sheet has in MS Excel. One can add as much as of application requirement. We will use the [Comment Class](https://reference.aspose.com/cells/net/aspose.cells/comment) for all of this functionality.

+  Load Excel file using Workbook class object
+  Acess the relevant Worksheet and its relevant Cell index
+  Call RemoveAt with the Cell Id to remove it
+  Use [Note property](https://reference.aspose.com/cells/net/aspose.cells/comment/properties/note) for adding comments content 
+  Save the workbook before & after calling RemoveAt method to compare

{{% blocks/products/pf/feature-page-code h3="C# Code to Access, Insert and Delete Excel Files Cell Comments" %}}


{{< gist "aspose-com-gists" "e3dcb9c341b81d4db3a404ca7cd6e4cf" "access-insert-and-delete-excel-files-cell-comments.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation">}}
