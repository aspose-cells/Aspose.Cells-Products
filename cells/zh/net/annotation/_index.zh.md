---
title: Excel 文件注释 NET C#
description: 只需几行 C# 代码即可添加或删除 Excel 和 OpenOffice 电子表格的数据注释。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="删除 Microsoft<sup>&reg;</sup> Excel 文件注释 via .NET" h2="在基于 .NET 的应用程序中使用 C# 代码添加或删除 Excel 文件注释。" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Excel 库](/cells/zh/net/)通过添加、访问和删除注释来支持在单元格级别管理注释。使用单元格级别的评论，可以为最终用户存储相关信息。支持的文件格式包括 ODS、XLS、XLSX、XLSB 和 XLSM。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel 文件数据注释" %}}
管理工作表中的评论 - 在 MS Excel 中，一张工作表的评论数量没有任何限制。一个人可以添加尽可能多的应用程序需求。我们将使用[评论类](https://reference.aspose.com/cells/net/aspose.cells/comment)对于所有这些功能。

+ 使用工作簿类对象加载 Excel 文件
访问相关的工作表及其相关的 Cell 索引
+ 使用 Cell Id 调用 RemoveAt 将其删除
 使用[备注属性](https://reference.aspose.com/cells/net/aspose.cells/comment/properties/note)用于添加评论内容
调用 RemoveAt 方法比较前后保存工作簿

{{% blocks/products/pf/feature-page-code h3="C# 访问、插入和删除 Excel 文件的代码 Cell 评论" %}}


{{< gist "aspose-com-gists" "e3dcb9c341b81d4db3a404ca7cd6e4cf" "access-insert-and-delete-excel-files-cell-comments.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}
