---
title: 如何通过 Aspose.Cells 添加形状
weight: 7700
limit:
description: 了解如何添加形状。
keywords: [add shapes., how to add shapes in Aspose.Cells., how to add shapes using Aspose.Cells]
url: /zh/tutorial/add-shapes-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="了解如何使用 Aspose.Cells 添加形状" >}}

<p>
在本教程中，我们将在 Excel 文件中添加形状。
</p>

<p>
我们将首先使用以下命令创建一个新工作簿<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells 图书馆</a>并添加形状。
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: 请检查以下代码以了解如何添加形状。
//ExStepSummary:0: 以下代码显示如何添加矩形形状。
//ExStepImage:0:step-1.png
//ExStepSummary:1: 以下代码展示了如何添加线条形状。
//ExStepImage:1:step-2.png
//ExStepSummary:2: 以下代码显示如何添加椭圆形。
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

//添加矩形形状
形状.AddRectangle(1, 0, 1, 0, 100, 150);

//ExStep:1-
//添加线条形状
形状.AddLine(8, 0, 1, 0, 100, 150);

//ExStep:2-
//添加椭圆形
形状.AddOval(13, 0, 1, 0, 100, 150);

//ExStep:0-
作业簿
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