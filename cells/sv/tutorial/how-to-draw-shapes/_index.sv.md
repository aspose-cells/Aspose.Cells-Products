---
title: Hur man lägger till former via Aspose.Cells
weight: 7700
limit:
description: Lär dig hur du lägger till former.
keywords: [add shapes., how to add shapes in Aspose.Cells., how to add shapes using Aspose.Cells]
url: /sv/tutorial/add-shapes-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Lär dig hur du lägger till former med Aspose.Cells" >}}

<p>
I den här handledningen lägger vi till former i en excel-fil.
</p>

<p>
 Vi börjar med att skapa en ny arbetsbok med hjälp av<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells bibliotek</a> och lägg till former.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: Kontrollera följande kod för att ta reda på hur du lägger till former.
//ExStepSummary:0: Följande kod visar hur man lägger till rektangelform.
//ExStepImage:0:step-1.png
//ExStepSummary:1: Följande kod visar hur man lägger till linjeform.
//ExStepImage:1:step-2.png
//ExStepSummary:2: Följande kod visar hur man lägger till oval form.
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
använder Aspose.Cells;
med Aspose.Cells. Ritning;





Arbetsbok arbetsbok = ny arbetsbok();
Arbetsblad = arbetsbok. Arbetsblad[0];
sheet.PageSetup.PrintGridlines = sant;
sheet.PageSetup.PrintArea = "A1:F20";

ShapeCollection former = ark.Shapes;

//Lägg till rektangelform
shapes.AddRectangle(1, 0, 1, 0, 100, 150);

//ExStep:1-
//Lägg till linjeform
shapes.AddLine(8, 0, 1, 0, 100, 150);

//ExStep:2-
//Lägg till oval form
shapes.AddOval(13, 0, 1, 0, 100, 150);

//ExStep:0-
arbetsbok
//ExEnd
{{< /app/cells/tutorial >}}
<br />

<br />
<br />
<div class="code-sample">
    <ul class="link-list">
        <li class="link-item"><a href="https://docs.aspose.com/cells/net/installation/">Installation av Aspose.Cells</a></li>
        <li class="link-item"><a href="https://products.aspose.app/cells/editor/">Aspose.Cells Redaktör</a></li>
    </ul>
</div>

{{< /blocks/products/pf/feature-page-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}