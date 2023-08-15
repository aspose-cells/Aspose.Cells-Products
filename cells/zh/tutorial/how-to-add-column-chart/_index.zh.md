---
title: 如何通过Aspose.Cells添加柱形图
weight: 7700
limit:
description: 了解如何添加柱形图。
keywords: [Add column chart., how to add column chart in Aspose.Cells., how to add column chart using Aspose.Cells]
url: /zh/tutorial/add-column-chart-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="了解如何使用 Aspose.Cells 添加柱形图" >}}

<p>
在本教程中，我们将在 Excel 文件中添加柱形图。
</p>

<p>
我们将首先使用以下命令创建一个新工作簿<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells 图书馆</a>并添加柱形图。
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: 请检查以下代码以了解如何添加柱形图。
//ExStepSummary:0: 下面的代码展示了如何添加柱形图。
//ExStepImage:0:step-1.png
//ExStepSummary:1: 下面的代码展示了如何将图例向左移动并设置图例的字体颜色。
//ExStepImage:1:step-2.png
//ExStepSummary:2: 以下代码演示如何设置图表标题并将字体颜色更改为蓝色。
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

//添加柱形图
int index = Charts.Add(ChartType.Column, "=ChartSheet!A1:B5", false, 6, 0, 19, 5);
图表图表=图表[指数]；

//ExStep:1-
//将图例向左移动并设置图例的字体颜色
图表.图例.字体.颜色=颜色.蓝色;
Chart.Legend.Position = LegendPositionType.Left;

//ExStep:2-
//设置图表标题并将字体颜色更改为蓝色
Chart.Title.Text = "水果价格柱形图";
图表.标题.字体.颜色 = 颜色.蓝色;

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