---
title: 如何通过Aspose.Cells添加饼图
weight: 7700
limit:
description: 了解如何添加饼图。
keywords: [Add pie chart., how to add pie chart in Aspose.Cells., how to add pie chart using Aspose.Cells]
url: /zh/tutorial/add-pie-chart-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="了解如何使用 Aspose.Cells 添加饼图" >}}

<p>
在本教程中，我们将在 Excel 文件中添加饼图。
</p>

<p>
我们将首先使用以下命令创建一个新工作簿<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells 图书馆</a>并添加饼图。
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: 请检查以下代码以了解如何添加饼图。
//ExStepSummary:0: 下面的代码展示了如何添加饼图、设置系列数据范围和设置类别数据范围。
//ExStepImage:0:step-1.png
//ExStepSummary:1: 以下代码显示如何关闭图例。
//ExStepImage:1:step-2.png
//ExStepSummary:2: 以下代码显示如何访问数据标签、打开类别名称、打开百分比格式和设置位置。
//ExStepImage:2:step-3.png
//Ex开始
//ExStep:0-
使用Aspose.Cells；
使用Aspose.Cells.绘图；

工作簿 工作簿 = new Workbook();
工作表sheet = workbook.Worksheets[0];
sheet.Name = "ChartSheet";
Cells单元格=工作表.Cells;
cells["A1"].Value = "水果";
cells["A2"].Value = "苹果";
cells["A3"].Value = "橙色";
cells["A4"].Value = "蓝莓";
cells["A5"].Value = "kiwi";

cells["B1"].Value = "价格";
单元格[“B2”]。值= 10；
单元格[“B3”]。值= 5；
单元格[“B4”]。值= 20；
单元格[“B5”]。值= 8；

sheet.PageSetup.PrintGridlines = true;
sheet.PageSetup.PrintArea = "A1:F20";

ChartCollection图表=sheet.Charts;

//添加饼图，设置系列数据范围和设置类别数据范围
int索引=sheet.Charts.Add(ChartType.Pie,6,0,19,5);
图表图表=sheet.Charts[index];
Chart.NSeries.Add("B2:B5", true);
Chart.NSeries.CategoryData = "A2:A5";

//ExStep:1-
//关闭图例
图表.ShowLegend = false;

//ExStep:2-
//访问数据标签，打开类别名称，打开百分比格式并设置位置
DataLabels dataLabels = Chart.NSeries[0].DataLabels;
dataLabels.ShowCategoryName = true;
dataLabels.ShowPercentage = true;
dataLabels.Position = LabelPositionType.OutsideEnd;

//ExStep:0-

//结束
{{< /app/cells/tutorial >}}
<br />

<br />
<br />
<div class="code-sample">
    <ul class="link-list">
        <li class="link-item"><a href="https://docs.aspose.com/cells/net/installation/">安装Aspose.Cells</a></li>
        <li class="link-item"><a href="https://products.aspose.app/cells/editor/">Aspose.Cells编辑</a></li>
    </ul>
</div>

{{< /blocks/products/pf/feature-page-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}