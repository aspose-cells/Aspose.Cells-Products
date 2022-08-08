---
title: Excel 文件合并 API .NET C#
url: /zh/net/merger/
description: 只需几行 C# 代码即可连接 Excel 和 OpenOffice 电子表格文件。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> 通过 .NET 合并 Excel 文件" h2="使用 C# 代码将 2 个或更多 Excel 文件合并到一个电子表格中" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Excel 库](/cells/net/) 提供多种方式将工作簿与各种类型的内容（如公式、数据、图像、图表等）组合到单个电子表格文件中。支持的文件格式包括 XLS、XLSX、XLSB、XLT、XLTX、XLTM、ODS、CSV、TSV 等。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="将 Excel 文件与图像和图表相结合" %}}
组合 2 个具有图像和图表的 Excel 文件的最简单方法是调用 [工作簿.组合](https://reference.aspose.com/cells/net/aspose.cells/workbook/methods/combine) 方法。它允许将类似类型的 Excel 文件合并到一个电子表格中。
{{% blocks/products/pf/feature-page-code h3="C# 合并 Excel 文件的代码" %}}

{{< gist "aspose-com-gists" "d7c757e7471bd38006ac0d35d221b2e2" "combine-two-workbooks.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="合并多个 Excel 文件" %}}
[CellsHelper.MergeFiles](https://reference.aspose.com/cells/net/aspose.cells/cellshelper/methods/mergefiles) 方法支持将 Excel 文件的数据、样式和公式合并到相同格式的新电子表格中。这是在使用缓存时合并多个文件的有效方法。 
{{% blocks/products/pf/feature-page-code h3="C# 合并多个 Excel 文件的代码" %}}

{{< gist "aspose-com-gists" "d7c757e7471bd38006ac0d35d221b2e2" "merge-several-excel-files.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="通过复制工作表合并 Excel 文件" %}}
[工作表.复制](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy/index) 可用于将数据和格式从源工作表复制到工作簿内或工作簿之间的另一个工作表。该方法将源工作表对象作为参数。
{{% blocks/products/pf/feature-page-code h3="C# 跨 Excel 文件复制工作表的代码" %}}

{{< gist "aspose-com-gists" "d7c757e7471bd38006ac0d35d221b2e2" "copy-worksheets-across-excel-files.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Merger" >}}