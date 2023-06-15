---
title: How to add shapes via Aspose.Cells
weight: 7700
limit: 
description: Learn how to add shapes.
keywords: [add shapes, how to add shapes in Aspose.Cells, how to add shapes using Aspose.Cells]
url: /tutorial/add-shapes-in-excel
---

{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Learn how to add shapes with Aspose.Cells" >}}

<p>
In this tutorial, we'll add shapes in a excel file.
</p>

<p>
We'll start by creating a new workbook using the <a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells library</a> and add shapes.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: Please check the following code to find out how to add shapes, you can modify the code and run it directly in your browser.
//ExStepSummary:0: The following code shows how to add rectangle shape.
//ExStepImage:0:step-1.png
//ExStepSummary:1: The following code shows how to add line shape.
//ExStepImage:1:step-2.png
//ExStepSummary:2: The following code shows how to add oval shape.
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
using Aspose.Cells;
using Aspose.Cells.Drawing;

Workbook workbook = new Workbook();
Worksheet sheet = workbook.Worksheets[0];
ShapeCollection shapes = sheet.Shapes;
//Add rectangle shape
shapes.AddRectangle(1, 0, 1, 0, 50, 100);

//ExStep:1-
//Add line shape
shapes.AddLine(5, 0, 1, 0, 50, 100);

//ExStep:2-
//Add oval shape
shapes.AddOval(10,0,1,0, 50, 100);

//ExStep:0-
workbook
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