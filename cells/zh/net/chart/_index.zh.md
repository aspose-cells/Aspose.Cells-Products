---
title: Excel 图表创建和转换为图像 via .NET
description:  C# 使用 .NET 库在 Microsoft Excel 中绘制和转换图表或图表的源代码。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel 文件图表创建和转换 via .NET" h2="在基于 .NET 的应用程序中使用服务器端 API 创建 Excel 文档图表并转换为图像。" >}}
{{% blocks/products/pf/feature-page-summary %}}
绘制图表是一种以图形方式显示数据以便于分析的艺术。[.NET Excel 库](/cells/zh/net/)支持在 Excel 文件中绘制图表。 API 支持中列出的不同图表创建[ChartType 枚举](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype)包括饼图、金字塔图、折线图和气泡图。此外，它还将图表转换为图像。 API提供了[图表类](https://reference.aspose.com/cells/net/aspose.cells.charts)用于图表构建块。

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="在 Excel 文件中创建图表" %}}

使用 Excel API 创建图表很简单。过程是，创建[练习册类](https://reference.aspose.com/cells/net/aspose.cells/workbook)对象并通过提供其索引来选择第一个工作表或相关工作表。使用插入所需的单元格数据[PutValue 方法](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index).使用 Charts 集合的将图表添加到工作表[添加方法](https://reference.aspose.com/cells/net/aspose.cells.charts/chartcollection/methods/add).指定[图表类型](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype)来自 ChartType 枚举。
{{% blocks/products/pf/feature-page-code h3="C# 创建 Excel 图表的代码" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "create-excel-chart.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section h2="将 Excel 图表转换为图像" %}}

图表转图片的过程是，使用Workbook类加载Excel文件，选择包含图表的相关工作集，调用[ToImage 方法](https://reference.aspose.com/cells/net/aspose.cells.charts.chart/toimage/methods/7)进行转换。

{{% blocks/products/pf/feature-page-code h3="C# 将 Excel 图表转换为图像的代码" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "convert-xlsx-file-chart-to-images.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}
