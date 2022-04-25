---
title: Insert shapes in Excel via .NET
url: /net/shapes/
description: C# source codes that how to insert a shape into Microsoft Excel files using .NET Library. 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel shapes insertion via .NET" h2="Create Excel documents and insert shapes using server-side APIs in .NET-based applications." >}}
{{% blocks/products/pf/feature-page-summary %}}

In excel you can add shapes such as boxes, circles and arrows to documents, emails, slides and spreadsheets.To free you from a lot of manual insertion, the [.NET Excel Library](/cells/net/) API provides the same functionality.These APIs are very easy to use, usually only one line of code is needed to insert a specific shape, and a few lines of code can complete the insertion of batches of shapes.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Insert shapes in Excel File" %}}

Insertting shapes using Excel API is simple. Process is, Create [Workbook class](https://apireference.aspose.com/cells/net/aspose.cells/workbook) object and select the first worksheet or the relevant sheet by providing its index. Add a shape to the worksheet by using [shapecollection](https://apireference.aspose.com/cells/net/aspose.cells.drawing/shapecollection)’s Add method.

{{% blocks/products/pf/feature-page-code h3="C# Code to Insert Shape in Excel" %}}

{{< gist "aspose-cells-gists" "59a1901d62ea9ceb08456a818431a898" "InsertShape.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}
