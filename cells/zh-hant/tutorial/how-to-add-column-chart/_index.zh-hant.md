---
title: 如何通過Aspose.Cells添加柱形圖
weight: 7700
limit:
description: 了解如何添加柱形圖。
keywords: [Add column chart., how to add column chart in Aspose.Cells., how to add column chart using Aspose.Cells]
url: /zh-hant/tutorial/add-column-chart-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="了解如何使用 Aspose.Cells 添加柱形圖" >}}

<p>
在本教程中，我們將在 Excel 文件中添加柱形圖。
</p>

<p>
我們將首先使用以下命令創建一個新工作簿<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells 圖書館</a>並添加柱形圖。
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: 請檢查以下代碼以了解如何添加柱形圖。
//ExStepSummary:0: 下面的代碼展示瞭如何添加柱形圖。
//ExStepImage:0:step-1.png
//ExStepSummary:1: 下面的代碼展示瞭如何將圖例向左移動並設置圖例的字體顏色。
//ExStepImage:1:step-2.png
//ExStepSummary:2: 以下代碼演示如何設置圖表標題並將字體顏色更改為藍色。
//ExStepImage:2:step-3.png
//Ex開始
//ExStep:0-
使用Aspose.Cells；
使用Aspose.Cells.繪圖；

工作簿 工作簿 = new Workbook();
工作表sheet = workbook.Worksheets[0];
sheet.Name = "ChartSheet";
Cells單元格=工作表.Cells;
cells["A1"].Value = "水果";
cells["A2"].Value = "蘋果";
cells["A3"].Value = "橙色";
cells["A4"].Value = "藍莓";
cells["A5"].Value = "kiwi";

cells["B1"].Value = "價格";
單元格[“B2”]。值= 10；
單元格[“B3”]。值= 5；
單元格[“B4”]。值= 20；
單元格[“B5”]。值= 8；

sheet.PageSetup.PrintGridlines = true;
sheet.PageSetup.PrintArea = "A1:F20";

ChartCollection圖表=sheet.Charts;

//添加柱形圖
int index = Charts.Add(ChartType.Column, "=ChartSheet!A1:B5", false, 6, 0, 19, 5);
圖表圖表=圖表[指數]；

//ExStep:1-
//將圖例向左移動並設置圖例的字體顏色
圖表.圖例.字體.顏色=顏色.藍色;
Chart.Legend.Position = LegendPositionType.Left;

//ExStep:2-
//設置圖表標題並將字體顏色更改為藍色
Chart.Title.Text = "水果價格柱形圖";
圖表.標題.字體.顏色 = 顏色.藍色;

//ExStep:0-

//結束
{{< /app/cells/tutorial >}}
<br />

<br />
<br />
<div class="code-sample">
    <ul class="link-list">
        <li class="link-item"><a href="https://docs.aspose.com/cells/net/installation/">安裝Aspose.Cells</a></li>
        <li class="link-item"><a href="https://products.aspose.app/cells/editor/">Aspose.Cells編輯</a></li>
    </ul>
</div>

{{< /blocks/products/pf/feature-page-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}