---
title: Create Excel Charts and Convert to Images via C++

description: C++ source code to draw and convert chart or diagram in Microsoft Excel using C++ Library
keywords: [C++ Aspose.Cells., C++ Convert chart to image., C++ Save chart to image., C++ chart to image., create charts in C++., insert charts in C++., manage charts in C++]
---


{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Create Microsoft<sup>&reg;</sup> Excel Charts and Convert to Images via C++" h2="Convert Excel document charts to images as well as create charts including Pie, Pyramid, Line and Bubble charts within C++ based applications." >}}

{{% blocks/products/pf/feature-page-summary %}}

Using Excel charts, one can get the bigger picture and analyse data easily for taking right decisions. [C++ Excel Library](/cells/cpp/) supports creating different charts listed by [enum Aspose::Cells::Charts::ChartType
](https://reference.aspose.com/cells/cpp/aspose.cells.charts/charttype/) including area, bar, pie, pyramid, line and bubble charts. Moreover, For conversion of charts to images, API provides a [ToImage](https://reference.aspose.com/cells/cpp/aspose.cells.charts/chart/toimage/) mehtod into required image format.

{{% /blocks/products/pf/feature-page-summary  %}}
{{% blocks/products/pf/feature-page-section  h2="Create Excel Charts" %}}

Process of creating Excel chart is, create an instance of the [Workbook class](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) and select the desired [Worksheet](https://reference.aspose.com/cells/cpp/aspose.cells/worksheet/). Add the chart using [Add method](https://reference.aspose.com/cells/cpp/aspose.cells.charts/chartcollection/add/) with relevant parameters including chart type. Access the chart via index and [Add](https://reference.aspose.com/cells/cpp/aspose.cells.charts/seriescollection/add/) the data source for chart.

{{% blocks/products/pf/feature-page-code h3="C++ Code to Create Excel Charts" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "create-excel-chart.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert Charts to Images" %}}


For converting charts process is, first create chart as of relevant type using above code or access it from relevant sheet. Define the output saving path for image and use the ToImage method for conversion.

 
{{% blocks/products/pf/feature-page-code h3="C++ Code to Convert Excel Charts" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "convert-excel-chart-to-image.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion">}}
