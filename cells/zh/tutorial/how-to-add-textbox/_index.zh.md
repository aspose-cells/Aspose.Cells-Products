---
title: 如何通过Aspose.Cells添加文本框
weight: 7700
limit:
description: 了解如何添加文本框。
keywords: [Add TextBox., how to add TextBox in Aspose.Cells., how to add TextBox using Aspose.Cells]
url: /zh/tutorial/add-textbox-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="了解如何使用 Aspose.Cells 添加文本框" >}}

<p>
在本教程中，我们将在 Excel 文件中添加 TextBox。
</p>

<p>
我们将首先使用以下命令创建一个新工作簿<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells 图书馆</a>并添加文本框。
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: 请检查以下代码以了解如何添加 TextBox。
//ExStepSummary:0: 下面的代码展示了如何添加TextBox并设置文本。
//ExStepImage:0:step-1.png
//ExStepSummary:1: 以下代码显示如何更改文本颜色。
//ExStepImage:1:step-2.png
//ExStepSummary:2: 下面的代码展示了如何改变TextBox的旋转角度。
//ExStepImage:2:step-3.png
//Ex开始
//ExStep:0-
使用Aspose.Cells；
使用Aspose.Cells.绘图；

工作簿 工作簿 = new Workbook();
工作表sheet = workbook.Worksheets[0];
sheet.PageSetup.PrintGridlines = true;
sheet.PageSetup.PrintArea = "A1:F20";

ShapeCollection 形状 =sheet.Shapes;

//添加文本框并设置文本
TextBox textBox = Shapes.AddTextBox(1, 0, 1, 0, 200, 200);
textBox.Text = "Aspose.Cells for .NET 是一个编程类库，允许软件开发人员在自己的应用程序中操作和处理电子表格文件。";

//ExStep:1-
//改变文本颜色
textBox.Font.Color = Color.Blue;

//ExStep:2-
//改变TextBox的旋转角度
文本框.RotationAngle = 90;

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