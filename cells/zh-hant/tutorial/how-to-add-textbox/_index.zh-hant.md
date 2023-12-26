---
title: 如何透過Aspose.Cells新增文字框
weight: 7700
limit:
description: 了解如何新增文字方塊。
keywords: [Add TextBox., how to add TextBox in Aspose.Cells., how to add TextBox using Aspose.Cells]
url: /zh-hant/tutorial/add-textbox-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="了解如何使用 Aspose.Cells 新增文字框" >}}

<p>
在本教程中，我們將在 Excel 檔案中新增 TextBox。
</p>

<p>
我們將首先使用以下命令建立新工作簿<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells 圖書館</a>並添加文字框。
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: 請檢查以下程式碼以了解如何新增 TextBox。
//ExStepSummary:0: 下面的程式碼展示如何新增TextBox並設定文字。
//ExStepImage:0:step-1.png
//ExStepSummary:1: 以下程式碼顯示如何變更文字顏色。
//ExStepImage:1:step-2.png
//ExStepSummary:2: 下面的程式碼展示如何改變TextBox的旋轉角度。
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

//新增文字方塊並設定文字
TextBox textBox = Shapes.AddTextBox(1, 0, 1, 0, 200, 200);
textBox.Text = "Aspose.Cells for .NET 是一個程式設計類別庫，允許軟體開發人員在自己的應用程式中操作和處理電子表格檔案。";

//ExStep:1-
//改變文字顏色
textBox.Font.Color = Color.Blue;

//ExStep:2-
//改變TextBox的旋轉角度
文字框.RotationAngle = 90;

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