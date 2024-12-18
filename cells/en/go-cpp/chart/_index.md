---
title: Create Excel Charts and Convert to Images with Go via C++

description: Go via C++ source code to draw and convert chart or diagram in Microsoft Excel using Go via C++ Library
keywords: [Go via C++ Aspose.Cells., Go via C++ Convert chart to image., Go via C++ Save chart to image., Go via C++ chart to image., create charts in Go via C++., insert charts in Go via C++., manage charts in Go via C++]
---


{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Create Microsoft<sup>&reg;</sup> Excel Charts and Convert to Images with Go via C++" h2="Convert Excel document charts to images as well as create charts including Pie, Pyramid, Line and Bubble charts within Go via C++ based applications." >}}

{{% blocks/products/pf/feature-page-summary %}}

Using Excel charts, one can get the bigger picture and analyse data easily for taking right decisions. [Go via C++ Excel Library](/cells/go-cpp/) supports creating different charts listed by [enum Aspose::Cells::Charts::ChartType
](https://reference.aspose.com/cells/go-cpp/aspose.cells.charts/charttype/) including area, bar, pie, pyramid, line and bubble charts. Moreover, For conversion of charts to images, API provides a [ToImage](https://reference.aspose.com/cells/go-cpp/aspose.cells.charts/chart/toimage/) mehtod into required image format.

{{% /blocks/products/pf/feature-page-summary  %}}
{{% blocks/products/pf/feature-page-section  h2="Create Excel Charts" %}}

Process of creating Excel chart is, create an instance of the [Workbook class](https://reference.aspose.com/cells/go-cpp/aspose.cells/workbook/) and select the desired [Worksheet](https://reference.aspose.com/cells/go-cpp/aspose.cells/worksheet/). Add the chart using [Add method](https://reference.aspose.com/cells/go-cpp/aspose.cells.charts/chartcollection/add/) with relevant parameters including chart type. Access the chart via index and [Add](https://reference.aspose.com/cells/go-cpp/aspose.cells.charts/seriescollection/add/) the data source for chart.

{{% blocks/products/pf/feature-page-code h3="Go via C++ Code to Create Excel Charts" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "create-excel-chart.go" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert Charts to Images" %}}


For converting charts process is, first create chart as of relevant type using above code or access it from relevant sheet. Define the output saving path for image and use the ToImage method for conversion.


{{% blocks/products/pf/feature-page-code h3="Go via C++ Code to Convert Excel Charts" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "convert-excel-chart-to-image.go" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion">}}


{{< /blocks/products/pf/feature-page-wrap >}}