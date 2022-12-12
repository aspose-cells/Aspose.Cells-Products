---
title: Excel Charts Creation and Conversion to Images via .NET

description: C# source code to draw and convert chart or diagram in Microsoft Excel using .NET Library. 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel File Charts Creation and Conversion via .NET" h2="Create Excel document charts and convert to images using server-side APIs within .NET based applications." >}}
{{% blocks/products/pf/feature-page-summary %}}
Drawing charts is an art to display data graphically for easy analysis. [.NET Excel Library](/cells/net/) supports drawing charts within Excel files. API supports different chart creation listed in [ChartType Enumeration](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype) including pie, pyramid, line and bubble charts. Moreover, it also converts charts to images. API provides a [Charts class](https://reference.aspose.com/cells/net/aspose.cells.charts) for chart building blocks.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Create Charts within Excel File" %}}

Creating charts using Excel API is simple. Process is, Create [Workbook class](https://reference.aspose.com/cells/net/aspose.cells/workbook) object and select the first worksheet or the relevant sheet by providing its index. Insert the required cells data using [PutValue method](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index). Add chart to the worksheet by using Charts collection’s [Add method](https://reference.aspose.com/cells/net/aspose.cells.charts/chartcollection/methods/add). Specify the [ChartType](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype) from  ChartType enumeration.
{{% blocks/products/pf/feature-page-code h3="C# Code to Create Excel Charts" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "create-excel-chart.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section  h2="Convert Excel Charts to Images" %}}

Process of converting charts to images is, Use the Workbook class to load the Excel file, select the relevant workseet containing the charts and call the [ToImage method](https://reference.aspose.com/cells/net/aspose.cells.charts.chart/toimage/methods/7) for conversion.

{{% blocks/products/pf/feature-page-code h3="C# Code to Convert Excel Chart to Image" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "convert-xlsx-file-chart-to-images.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion">}}
