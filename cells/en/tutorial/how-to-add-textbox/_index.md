---
title: How to add TextBox via Aspose.Cells
weight: 7700
limit: 
description: Learn how to add TextBox.
keywords: [Add TextBox., how to add TextBox in Aspose.Cells., how to add TextBox using Aspose.Cells]
url: /tutorial/add-textbox-in-excel
---

{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Learn how to add TextBox with Aspose.Cells" >}}

<p>
In this tutorial, we'll add TextBox in a excel file.
</p>

<p>
We'll start by creating a new workbook using the <a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells library</a> and add TextBox.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: Please check the following code to find out how to add TextBox.
//ExStepSummary:0: The following code shows how to add TextBox and set text.
//ExStepImage:0:step-1.png
//ExStepSummary:1: The following code shows how to change the color of text.
//ExStepImage:1:step-2.png
//ExStepSummary:2: The following code shows how to change the rotation angle of TextBox.
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
using Aspose.Cells;
using Aspose.Cells.Drawing;

Workbook workbook = new Workbook();
Worksheet sheet = workbook.Worksheets[0];
sheet.PageSetup.PrintGridlines = true;
sheet.PageSetup.PrintArea = "A1:F20";

ShapeCollection shapes = sheet.Shapes;

//Add TextBox and set text
TextBox textBox =  shapes.AddTextBox(1, 0, 1, 0, 200, 200);
textBox.Text = "Aspose.Cells for .NET is a programming class library that allows software developers to manipulate and process spreadsheet files within their own applications.";

//ExStep:1-
//Change the color of text
textBox.Font.Color = Color.Blue;

//ExStep:2-
//Change the rotation angle of TextBox
textBox.RotationAngle = 90;

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