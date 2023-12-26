---
title: 如何透過 Aspose.Cells 新增形狀
weight: 7700
limit:
description: 了解如何新增形狀。
keywords: [add shapes., how to add shapes in Aspose.Cells., how to add shapes using Aspose.Cells]
url: /zh-hant/tutorial/add-shapes-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="了解如何使用 Aspose.Cells 新增形狀" >}}

<p>
在本教程中，我們將在 Excel 檔案中新增形狀。
</p>

<p>
我們將首先使用以下命令建立新工作簿<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells 圖書館</a>並添加形狀。
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: 請檢查以下程式碼以了解如何新增形狀。
//ExStepSummary:0: 以下程式碼顯示如何新增矩形形狀。
//ExStepImage:0:step-1.png
//ExStepSummary:1: 以下程式碼展示如何新增線條形狀。
//ExStepImage:1:step-2.png
//ExStepSummary:2: 以下程式碼顯示如何新增橢圓形。
//ExStepImage:2:step-3.png
//Ex開始
//ExStep:0-
使用Aspose.Cells；
使用Aspose.Cells.繪圖；





工作簿 工作簿 = new Workbook();
工作表sheet = workbook.Worksheets[0];
sheet.PageSetup.PrintGridlines = true;
sheet.PageSetup.PrintArea = "A1:F20";

ShapeCollection 形狀 =sheet.Shapes;

//新增矩形形狀
形狀.AddRectangle(1, 0, 1, 0, 100, 150);

//ExStep:1-
//新增線條形狀
形狀.AddLine(8, 0, 1, 0, 100, 150);

//ExStep:2-
//新增橢圓形
形狀.AddOval(13, 0, 1, 0, 100, 150);

//ExStep:0-
作業簿
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