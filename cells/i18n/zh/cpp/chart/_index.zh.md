---
title: 通过 C++ 创建 Excel 图表并转换为图像
url: /zh/cpp/chart/
description: C++ 使用 C++ 库在 Microsoft Excel 中绘制和转换图表或图表的源代码
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="创建 Microsoft<sup>&reg;</sup> Excel 图表并通过 C++ 转换为图像" h2="将 Excel 文档图表转换为图像，并在基于 C++ 的应用程序中创建图表，包括饼图、金字塔图、折线图和气泡图。" >}}

{{% blocks/products/pf/feature-page-summary %}}

使用 Excel 图表，您可以了解全局并轻松分析数据以做出正确决策。 [C++ Excel 库](/cells/cpp/) 支持创建不同的图表 [枚举 Aspose::Cells::Charts::ChartType
](https://apireference.aspose.com/cells/cpp/namespace/aspose.cells.charts#a2f17e69bcefc754569019185d0621b70) 包括面积图、条形图、饼图、金字塔图、折线图和气泡图。此外，为了将图表转换为图像，API 提供了一个 [图像方法](https://apireference.aspose.com/cells/cpp/class/aspose.cells.charts.i_sparkline#a28d76dd585c48366e1657f2982722ddb) 成所需的图像格式。

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="创建 Excel 图表" %}}

创建Excel图表的过程是，创建一个实例 [IWorkbook 类](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) 并选择所需的 [工作表](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet_collection#a5574d624796043233420d0e0459ccc43).使用添加图表 [添加方法](https://apireference.aspose.com/cells/cpp/class/aspose.cells.charts.i_chart_collection#ab7e8cce835c251a4682605299a6aa068) 带有相关参数，包括图表类型。通过索引访问图表和 [添加](https://apireference.aspose.com/cells/cpp/class/aspose.cells.charts.i_series_collection#a8f4dc4d883f32f65b1fb673e2aa7862f) 图表的数据源。

{{% blocks/products/pf/feature-page-code h3="C++ 创建 Excel 图表的代码" %}}

{{< gist "aspose-com-gists" "da2fd423617bf9013a7673870c81d708" "create-excel-chart.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="将图表转换为图像" %}}


对于转换图表的过程，首先使用上述代码创建相关类型的图表或从相关工作表访问它。定义图片的输出保存路径，使用ToImage方法进行转换。

 
{{% blocks/products/pf/feature-page-code h3="C++ 转换 Excel 图表的代码" %}}

{{< gist "aspose-com-gists" "da2fd423617bf9013a7673870c81d708" "convert-excel-chart-to-image.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}