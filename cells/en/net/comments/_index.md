---
title: Insert comments in Excel via .NET
url: /net/comments/
description: C# source codes that how to insert comment into Microsoft Excel files using .NET Library. 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel comments insertion via .NET" h2="Create Excel documents and insert comments using server-side APIs in .NET-based applications." >}}
{{% blocks/products/pf/feature-page-summary %}}

You can add comments to cells. When a cell has a comment, an indicator appears in the corner of the cell. Comments appear when you hover your cursor over a cell.These comments can be used for discussion, special instructions, or markup of document content.The [.NET Excel Library](/cells/net/) supports inserting comments in Excel files.For this, the API provides a [Comment](https://apireference.aspose.com/cells/net/aspose.cells/comment) class for comments building block.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Insert comments in Excel File" %}}

Insertting comments using Excel API is simple. Process is, Create [Workbook class](https://apireference.aspose.com/cells/net/aspose.cells/workbook) object and select the first worksheet or the relevant sheet by providing its index. Insert the required cells data using [PutValue method](https://apireference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index). Add comment to the worksheet by using [CommentCollection](https://apireference.aspose.com/cells/net/aspose.cells/commentcollection)’s [Add method](https://apireference.aspose.com/cells/net/aspose.cells.commentcollection/add/methods/1).

{{% blocks/products/pf/feature-page-code h3="C# Code to Insert Comment in Excel" %}}

{{< gist "aspose-cells-gists" "59a1901d62ea9ceb08456a818431a898" "InsertCommentIntoWorksheet.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
