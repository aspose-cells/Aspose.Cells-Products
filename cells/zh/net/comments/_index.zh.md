---
title: 通过 .NET 在 Excel 中插入注释
url: /zh/net/comment/
description: C# 源代码，说明如何使用 .NET 库将注释插入 Microsoft Excel 文件。 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> 通过 .NET 插入 Excel 评论" h2="在基于 .NET 的应用程序中使用服务器端 API 创建 Excel 文档并插入注释。" >}}
{{% blocks/products/pf/feature-page-summary %}}

您可以向单元格添加注释。当单元格有注释时，单元格的角落会出现一个指示符。将光标悬停在单元格上时会出现注释。这些注释可用于讨论、特殊说明或文档内容的标记。 [.NET Excel 库](/cells/net/) 支持在 Excel 文件中插入注释。为此，API 提供了一个 [评论](https://apireference.aspose.com/cells/net/aspose.cells/comment) 评论构建块的类。

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="在 Excel 文件中插入注释" %}}

使用 Excel API 插入注释很简单。过程是，创造 [工作簿类](https://apireference.aspose.com/cells/net/aspose.cells/workbook) 对象并通过提供其索引来选择第一个工作表或相关工作表。使用插入所需的单元格数据 [PutValue 方法](https://apireference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index).使用向工作表添加注释 [评论集合](https://apireference.aspose.com/cells/net/aspose.cells/commentcollection)的 [添加方法](https://apireference.aspose.com/cells/net/aspose.cells.commentcollection/add/methods/1).

{{% blocks/products/pf/feature-page-code h3="C# 在 Excel 中插入注释的代码" %}}

{{< gist "aspose-cells-gists" "88c9872508ec3150c552eb5155edf06e" "InsertCommentIntoWorksheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
