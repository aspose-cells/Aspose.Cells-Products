---
title: 通过 C++ 创建 Excel 图表并转换为图像
description: C++ 使用 C++ 库在 Microsoft Excel 中绘制和转换图表或图表的源代码
keywords: [C++ Aspose.Cells., C++ Convert chart to image., C++ Save chart to image., C++ chart to image., create charts in C++., insert charts in C++., manage charts in C++]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="创建 Microsoft<sup>&reg;</sup> Excel 图表并通过 C++ 转换为图像" h2="将 Excel 文档图表转换为图像，并在基于 C++ 的应用程序中创建图表，包括饼图、金字塔图、折线图和气泡图。" >}}

{{% blocks/products/pf/feature-page-summary %}}

使用 Excel 图表，人们可以了解更大的情况并轻松分析数据以做出正确的决策。[C++ Excel 库](/cells/zh/cpp/)支持创建列出的不同图表[枚举Aspose::Cells::图表::图表类型
](https://reference.aspose.com/cells/cpp/aspose.cells.charts/charttype/)包括面积图、条形图、饼图、金字塔图、折线图和气泡图。此外，为了将图表转换为图像，API 提供了[印象](https://reference.aspose.com/cells/cpp/aspose.cells.charts/chart/toimage/)方法转换为所需的图像格式。

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="创建 Excel 图表" %}}

创建Excel图表的过程是，创建一个实例[作业本类](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/)并选择所需的[工作表](https://reference.aspose.com/cells/cpp/aspose.cells/worksheet/)。使用添加图表[添加方法](https://reference.aspose.com/cells/cpp/aspose.cells.charts/chartcollection/add/)以及相关参数，包括图表类型。通过索引访问图表[添加](https://reference.aspose.com/cells/cpp/aspose.cells.charts/seriescollection/add/)图表的数据源。

{{% blocks/products/pf/feature-page-code h3="C++ 创建 Excel 图表的代码" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "create-excel-chart.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="将图表转换为图像" %}}


对于转换图表的过程是，首先使用上面的代码创建相关类型的图表或从相关工作表访问它。定义图像的输出保存路径，并使用ToImage方法进行转换。

 
{{% blocks/products/pf/feature-page-code h3="C++ 转换Excel图表的代码" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "convert-excel-chart-to-image.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}
