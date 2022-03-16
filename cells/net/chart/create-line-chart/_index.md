---
title: How to create line chart to Excel via .NET
url: /net/chart/create-line-chart
description: C# source code to create line charts to Excel and image using .NET Library. 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Create Line Chart via .NET" h2="Create and customize line chart using server-side APIs within .NET based applications." >}}
{{% blocks/products/pf/feature-page-summary %}}
Line charts make use of lines to display information. These charts are very useful to show a temporal trend over time and are often used to show variations in the value of more than one item over time.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Create Line Chart within Excel File" %}}

In the above example, simply changing the ChartType to Line creates a line chart. The complete source is provided below. when the code is executed, a line chart is added to the worksheet.
{{% blocks/products/pf/feature-page-code h3="C# Code to Create Line Charts" %}}

{{< gist "aspose-cells-gists" "88c9872508ec3150c552eb5155edf06e" "Examples-CSharp-Charts-ManipulateChart-HowToCreateLineChart-1.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section  h2="Convert Excel Charts to Images" %}}

Process of converting charts to images is, Use the Workbook class to load the Excel file, select the relevant workseet containing the charts and call the [ToImage method](https://apireference.aspose.com/cells/net/aspose.cells.charts.chart/toimage/methods/7) for conversion.

{{% blocks/products/pf/feature-page-code h3="C# Code to Convert Excel Chart to Image" %}}

{{< gist "aspose-cells-gists" "88c9872508ec3150c552eb5155edf06e" "Examples-CSharp-Charts-ManipulateChart-HowToCreatePyramidChart-1.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion">}}