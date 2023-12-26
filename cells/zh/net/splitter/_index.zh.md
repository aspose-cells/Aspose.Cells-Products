---
title: 在 C# 中按工作表拆分 Excel 工作表
description: C# 源代码，解释如何在 Visual C#.NET 应用程序中将 Microsoft Excel 文件拆分为多个文件
keywords: [C# Aspose.Cells., C# split excel files., C# how to split excel files into multiple files., C# excel splitter., C# split Cell., Cell splitter using C#]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel 文件分割 via .NET" h2="在基于 .NET 的应用程序中使用 C# 代码将单个 Excel 文档拆分为不同的文件" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Excel 库](/cells/zh/net/)能够在基于 .NET 的应用程序中将 Excel 文档拆分为多个电子表格。支持的文件格式包括 XLS、XLSX、XLSB、XLSM、ODS。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="将 Excel 文档拆分为多个文件" %}}
按工作表拆分 Excel 文件的最简单方法是，通过访问所有工作表[工作表](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/worksheets)，迭代每个工作表并调用[复制](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy)方法。最后保存到指定路径即可。

 + 使用完整路径加载 Excel 文件[作业本类](https://reference.aspose.com/cells/net/aspose.cells/workbook).
+ 迭代每个工作表
创建一个新的 Workbook 类对象
 复制表格通过[复制方法](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy)
调用 Save() 方法并传递具有相关 SaveFormat 的文件名（完整路径）。

{{% blocks/products/pf/feature-page-code h3="C# 分割Excel文件的代码" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="将 Excel 工作表拆分为多个窗格" %}}

为了将工作表窗口拆分为多个窗格，API 提供了[分割法](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/split)工作表类，提供工作表的分割视图。删除分割视图 API 提供[删除分割方法](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/removesplit)。最后保存到指定路径即可。

{{% blocks/products/pf/feature-page-code h3="C# 拆分Excel工作表窗口的代码" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet-into-pane.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C# 删除分割平移视图的代码" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "remove-splitted-spreadsheet-pane-view.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
