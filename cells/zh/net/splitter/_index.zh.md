---
title: 在 C# 中拆分 Excel 工作表

description: C# 源代码，说明如何在 Visual C#.NET 应用程序中将 Microsoft Excel 文件拆分为多个文件
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> 通过 .NET 拆分 Excel 文件" h2="使用基于 .NET 的应用程序中的 C# 代码将单个 Excel 文档拆分为不同的文件" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Excel 库](/cells/net/) 能够在基于 .NET 的应用程序中将 Excel 文档拆分为多个电子表格。支持的文件格式包括 XLS、XLSX、XLSB、XLSM、ODS。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="将 Excel 文档拆分为多个文件" %}}
明智地拆分 Excel 文件的最简单方法是通过以下方式访问所有工作表 [工作表](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/worksheets), 遍历每个工作表并调用 [复制](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy) 方法。最后保存到指定路径。 

+ 使用完整路径加载 Excel 文件 [工作簿类](https://reference.aspose.com/cells/net/aspose.cells/workbook).
+遍历每张纸
+ 创建一个新的工作簿类对象
+通过复制工作表 [复制方法](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy)
+ 调用 Save() 方法并传递具有相关 SaveFormat 的文件名（完整路径）。

{{% blocks/products/pf/feature-page-code h3="C# 拆分 Excel 文件的代码" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="将 Excel 工作表拆分为窗格" %}}

要将工作表窗口拆分为多个窗格，API 提供 [拆分方法](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/split) 工作表类，提供工作表的拆分视图。要删除拆分视图 API 提供 [RemoveSplit 方法](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/removesplit).最后保存到指定路径。 

{{% blocks/products/pf/feature-page-code h3="C# 拆分 Excel 工作表窗口的代码" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet-into-pane.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C# 删除分割平移视图的代码" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "remove-splitted-spreadsheet-pane-view.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
