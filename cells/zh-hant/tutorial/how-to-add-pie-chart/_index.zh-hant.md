---
title: 如何透過Aspose.Cells添加餅圖
weight: 7700
limit:
description: 了解如何新增圓餅圖。
keywords: [Add pie chart., how to add pie chart in Aspose.Cells., how to add pie chart using Aspose.Cells]
url: /zh-hant/tutorial/add-pie-chart-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="了解如何使用 Aspose.Cells 新增圓餅圖" >}}

<p>
在本教學中，我們將在 Excel 檔案中新增圓餅圖。
</p>

<p>
我們將首先使用以下命令建立新工作簿<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells 圖書館</a>並添加餅圖。
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: 請檢查以下程式碼以了解如何新增圓餅圖。
//ExStepSummary:0: 下面的程式碼展示如何新增圓餅圖、設定係列資料範圍和設定類別資料範圍。
//ExStepImage:0:step-1.png
//ExStepSummary:1: 以下程式碼顯示如何關閉圖例。
//ExStepImage:1:step-2.png
//ExStepSummary:2: 以下程式碼顯示如何存取資料標籤、開啟類別名稱、開啟百分比格式和設定位置。
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
cells["A3"].Value = "橘色";
cells["A4"].Value = "藍莓";
cells["A5"].Value = "kiwi";

cells["B1"].Value = "價格";
單元格[“B2”]。值= 10；
儲存格[“B3”]。值= 5；
儲存格[“B4”]。值= 20；
儲存格[“B5”]。值= 8；

sheet.PageSetup.PrintGridlines = true;
sheet.PageSetup.PrintArea = "A1:F20";

ChartCollection圖表=sheet.Charts;

//新增圓餅圖，設定係列資料範圍和設定類別資料範圍
int索引=sheet.Charts.Add(ChartType.Pie,6,0,19,5);
圖表圖表=sheet.Charts[index];
Chart.NSeries.Add("B2:B5", true);
Chart.NSeries.CategoryData = "A2:A5";

//ExStep:1-
//關閉圖例
圖表.ShowLegend = false;

//ExStep:2-
//存取資料標籤，開啟類別名稱，開啟百分比格式並設定位置
DataLabels dataLabels = Chart.NSeries[0].DataLabels;
dataLabels.ShowCategoryName = true;
dataLabels.ShowPercentage = true;
dataLabels.Position = LabelPositionType.OutsideEnd;

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