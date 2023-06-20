---
title: How to add pie chart via Aspose.Cells
weight: 7700
limit: 
description: Learn how to add pie chart.
keywords: [Add pie chart., how to add pie chart in Aspose.Cells., how to add pie chart using Aspose.Cells]
url: /tutorial/add-pie-chart-in-excel
---

{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Learn how to add pie chart with Aspose.Cells" >}}

<p>
In this tutorial, we'll add pie chart in a excel file.
</p>

<p>
We'll start by creating a new workbook using the <a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells library</a> and add pie chart.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: Please check the following code to find out how to add pie chart.
//ExStepSummary:0: The following code shows how to add pie chart, set series data range and set category data range.
//ExStepImage:0:step-1.png
//ExStepSummary:1: The following code shows how to turn off legend.
//ExStepImage:1:step-2.png
//ExStepSummary:2: The following code shows how to access data labels, turn on category names, turn on percentage format and set position.
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
using Aspose.Cells;
using Aspose.Cells.Drawing;

Workbook workbook = new Workbook();
Worksheet sheet = workbook.Worksheets[0];
sheet.Name = "ChartSheet";
Cells cells = sheet.Cells;
cells["A1"].Value = "Fruit";
cells["A2"].Value = "apple";
cells["A3"].Value = "orange";
cells["A4"].Value = "blueberry";
cells["A5"].Value = "kiwi";

cells["B1"].Value = "Price";
cells["B2"].Value = 10;
cells["B3"].Value = 5;
cells["B4"].Value = 20;
cells["B5"].Value = 8;

sheet.PageSetup.PrintGridlines = true;
sheet.PageSetup.PrintArea = "A1:F20";

ChartCollection charts = sheet.Charts;

//Add pie chart, set series data range and set category data range
int index = sheet.Charts.Add(ChartType.Pie, 6, 0, 19, 5);
Chart chart = sheet.Charts[index];
chart.NSeries.Add("B2:B5", true);
chart.NSeries.CategoryData = "A2:A5";

//ExStep:1-
//Turn off legend
chart.ShowLegend = false;

//ExStep:2-
//Access data labels, turn on category names, turn on percentage format and set position
DataLabels dataLabels = chart.NSeries[0].DataLabels;
dataLabels.ShowCategoryName = true;
dataLabels.ShowPercentage = true;
dataLabels.Position = LabelPositionType.OutsideEnd;

//ExStep:0-

//ExEnd
{{< /app/cells/tutorial >}}
<br />

<br />
<br />
<div class="code-sample">
    <ul class="link-list">
        <li class="link-item"><a href="https://docs.aspose.com/cells/net/installation/">Installation of Aspose.Cells</a></li>
        <li class="link-item"><a href="https://products.aspose.app/cells/editor/">Aspose.Cells Editor</a></li>
    </ul>
</div>

{{< /blocks/products/pf/feature-page-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}