---
title: Create Excel Charts and Convert to Images via Java
url: /java/chart/
description: Java source code to draw and convert chart or diagram in Microsoft Excel using Java Library. 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel File Charts Conversion and Creation via Java" h2="Convert Excel document charts to images as well as create various charts using server-side APIs within Java based applications." >}}


{{% blocks/products/pf/feature-page-summary %}}

Analysing data via charts shows the bigger picture and it is easy to make more informed decisions with clearer insights. [Java Excel Library](/cells/net/) supports drawing different chart creation listed by [ChartType](https://apireference.aspose.com/cells/java/com.aspose.cells/ChartType) including pie, pyramid, line and bubble charts. Moreover, it also converts charts to images. API provides a [Charts class](https://apireference.aspose.com/cells/java/com.aspose.cells/Chart) for representing a single Excel chart.

{{% /blocks/products/pf/feature-page-summary  %}}
{{% blocks/products/pf/feature-page-section  h2="Convert Excel Charts to Images" %}}

Process of converting charts to images including JPG, PNG, TIFF, BMP etc is, Use the [Workbook](https://apireference.aspose.com/java/cells/com.aspose.cells/workbook) class to load the Excel file, select the relevant [workseet](https://apireference.aspose.com/cells/java/com.aspose.cells/worksheet) containing the charts or iterate through each chart in each worksheet. Define [ImageOrPrintOptions](https://apireference.aspose.com/cells/java/com.aspose.cells/ImageOrPrintOptions) and render output image of the Chart using [Chart.toImage](https://apireference.aspose.com/cells/java/com.aspose.cells/chart#toImage(java.io.OutputStream,%20com.aspose.cells.ImageOrPrintOptions)).


{{% blocks/products/pf/feature-page-code h3="Java Code to Convert Excel Chart to Image" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "render-excel-chart-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion">}}


{{% blocks/products/pf/feature-page-section  h2="Create Charts within Excel File" %}}

Creating charts using Excel API is simple, as API provides set of different classes such as Axis, Chart, ChartArea, ChartDataTable, ChartFrame, ChartPoint, ChartPointCollection, ChartCollection etc for different kinds of charts. Process is, Create Workbook class object and select the first worksheet or the relevant sheet by providing its index. For data source of the chart, insert values to worksheet cells using [setValue](https://apireference.aspose.com/cells/java/com.aspose.cells/cell#Value) method. Use ChartCollection collection’s [add method](https://apireference.aspose.com/cells/java/com.aspose.cells/chartcollection#add(int,%20int,%20int,%20int,%20int)) to add the chart, define type of chart with the ChartType enumeration. Access the new Chart object from the ChartCollection collection by passing its index. Use the [SeriesCollection](https://apireference.aspose.com/cells/java/com.aspose.cells/SeriesCollection) charting object to specify the chart’s data source.

{{% blocks/products/pf/feature-page-code h3="Java Code to Create Excel Charts" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "create-excel-chart-pyramid.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}