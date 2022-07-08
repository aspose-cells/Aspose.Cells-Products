---
title: Create Excel Charts and Convert to Images via C++
url: /cpp/chart/
description: C++ source code to draw and convert chart or diagram in Microsoft Excel using C++ Library
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Create Microsoft<sup>&reg;</sup> Excel Charts and Convert to Images via C++" h2="Convert Excel document charts to images as well as create charts including Pie, Pyramid, Line and Bubble charts within C++ based applications." >}}

{{% blocks/products/pf/feature-page-summary %}}

Using Excel charts, one can get the bigger picture and analyse data easily for taking right decisions. [C++ Excel Library](/cells/cpp/) supports creating different charts listed by [enum Aspose::Cells::Charts::ChartType
](https://reference.aspose.com/cells/cpp/namespace/aspose.cells.charts#a2f17e69bcefc754569019185d0621b70) including area, bar, pie, pyramid, line and bubble charts. Moreover, For conversion of charts to images, API provides a [ToImage mehtod](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_sparkline#a28d76dd585c48366e1657f2982722ddb) into required image format.

{{% /blocks/products/pf/feature-page-summary  %}}
{{% blocks/products/pf/feature-page-section  h2="Create Excel Charts" %}}

Process of creating Excel chart is, create an instance of the [IWorkbook class](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) and select the desired [Worksheet](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet_collection#a5574d624796043233420d0e0459ccc43). Add the chart using [Add method](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_chart_collection#ab7e8cce835c251a4682605299a6aa068) with relevant parameters including chart type. Access the chart via index and [Add](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_series_collection#a8f4dc4d883f32f65b1fb673e2aa7862f) the data source for chart.

{{% blocks/products/pf/feature-page-code h3="C++ Code to Create Excel Charts" %}}

{{< gist "aspose-com-gists" "da2fd423617bf9013a7673870c81d708" "create-excel-chart.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert Charts to Images" %}}


For converting charts process is, first create chart as of relevant type using above code or access it from relevant sheet. Define the output saving path for image and use the ToImage method for conversion.

 
{{% blocks/products/pf/feature-page-code h3="C++ Code to Convert Excel Charts" %}}

{{< gist "aspose-com-gists" "da2fd423617bf9013a7673870c81d708" "convert-excel-chart-to-image.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion">}}