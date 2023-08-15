---
title: Excel文件合并 API .NET C#
description: 只需几行 C# 代码即可连接 Excel 和 OpenOffice 电子表格文件。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel 文件合并 via .NET" h2="使用 C# 代码将 2 个或多个 Excel 文件合并到一个电子表格中" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Excel 库](/cells/zh/net/)提供多种方式将工作簿与各种类型的内容（如公式、数据、图像、图表等）组合到单个电子表格文件中。支持的文件格式包括 XLS、XLSX、XLSB、XLT、XLTX、XLTM、ODS、CSV、TSV 等。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="将 Excel 文件与图像和图表合并" %}}
组合 2 个包含图像和图表的 Excel 文件的最简单方法是调用[工作簿.合并](https://reference.aspose.com/cells/net/aspose.cells/workbook/methods/combine)方法。它允许将类似类型的 Excel 文件合并到单个电子表格中。
{{% blocks/products/pf/feature-page-code h3="C# 合并Excel文件的代码" %}}

{{< gist "aspose-com-gists" "d7c757e7471bd38006ac0d35d221b2e2" "combine-two-workbooks.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="合并多个 Excel 文件" %}}
[CellsHelper.MergeFiles](https://reference.aspose.com/cells/net/aspose.cells/cellshelper/methods/mergefiles)方法支持将Excel文件的数据、样式和公式合并到相同格式的新电子表格中。这是使用缓存合并多个文件的有效方法。
{{% blocks/products/pf/feature-page-code h3="C# 合并多个Excel文件的代码" %}}

{{< gist "aspose-com-gists" "d7c757e7471bd38006ac0d35d221b2e2" "merge-several-excel-files.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="通过复制工作表合并 Excel 文件" %}}
[工作表.副本](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy/index)可用于将数据和格式从源工作表复制到工作簿内或工作簿之间的另一个工作表。该方法将源工作表对象作为参数。
{{% blocks/products/pf/feature-page-code h3="C# 跨 Excel 文件复制工作表的代码" %}}

{{< gist "aspose-com-gists" "d7c757e7471bd38006ac0d35d221b2e2" "copy-worksheets-across-excel-files.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/other-supported-section title="其他支持的合并格式" subTitle="使用 C#，还可以合并许多其他文件格式，包括。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/csv/" name="CSV" description="逗号分隔值" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/html/" name="HTML" description="超文本标记语言" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/mhtml/" name="MHTML" description="网页存档格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/ods/" name="ODS" description="OpenDocument 电子表格文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/tsv/" name="TSV" description="制表符分隔值" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/txt/" name="TXT" description="文本文档" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/xls/" name="XLS" description="Excel 二进制格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/xlsb/" name="XLSB" description="二进制 Excel 工作簿文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/xlsm/" name="XLSM" description="电子表格文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/xlsx/" name="XLSX" description="OOXML Excel 文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/xlt/" name="XLT" description="Microsoft Excel 模板" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/xltm/" name="XLTM" description="Excel 宏启用模板" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}
