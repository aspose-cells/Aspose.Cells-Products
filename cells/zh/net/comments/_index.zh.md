---
title: 在 Excel 中插入注释 via .NET
description:  C# 源代码，说明如何使用 .NET 库将注释插入 Microsoft Excel 文件。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel 注释插入 via .NET" h2="在基于 .NET 的应用程序中使用服务器端 API 创建 Excel 文档并插入注释。" >}}
{{% blocks/products/pf/feature-page-summary %}}

您可以向单元格添加注释。当单元格有评论时，单元格的一角会出现一个指示符。将光标悬停在单元格上时会出现注释。这些注释可用于讨论、特殊说明或文档内容的标记。[.NET Excel 库](/cells/zh/net/)支持在Excel文件中插入注释。为此，API提供了一个[评论](https://reference.aspose.com/cells/net/aspose.cells/comment)评论构建块的类。

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="在 Excel 文件中插入注释" %}}

使用 Excel API 插入评论很简单。过程是，创建[练习册类](https://reference.aspose.com/cells/net/aspose.cells/workbook)对象并通过提供其索引来选择第一个工作表或相关工作表。使用插入所需的单元格数据[PutValue 方法](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index).通过使用向工作表添加评论[评论集](https://reference.aspose.com/cells/net/aspose.cells/commentcollection)的[添加方法](https://reference.aspose.com/cells/net/aspose.cells.commentcollection/add/methods/1).

{{% blocks/products/pf/feature-page-code h3="C# 在 Excel 中插入注释的代码" %}}

{{< gist "aspose-cells-gists" "59a1901d62ea9ceb08456a818431a898" "InsertCommentIntoWorksheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
