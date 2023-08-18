---
title: Hur man lägger till kolumndiagram via Aspose.Cells
weight: 7700
limit:
description: Lär dig hur du lägger till kolumndiagram.
keywords: [Add column chart., how to add column chart in Aspose.Cells., how to add column chart using Aspose.Cells]
url: /sv/tutorial/add-column-chart-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Lär dig hur du lägger till kolumndiagram med Aspose.Cells" >}}

<p>
I den här handledningen lägger vi till kolumndiagram i en excel-fil.
</p>

<p>
 Vi börjar med att skapa en ny arbetsbok med hjälp av<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells bibliotek</a> och lägg till kolumndiagram.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: Kontrollera följande kod för att ta reda på hur du lägger till kolumndiagram.
//ExStepSummary:0: Följande kod visar hur man lägger till kolumndiagram.
//ExStepImage:0:step-1.png
//ExStepSummary:1: Följande kod visar hur man flyttar förklaringen till vänster och ställer in teckensnittsfärg för förklaringen.
//ExStepImage:1:step-2.png
//ExStepSummary:2: Följande kod visar hur man ställer in titeln på ett diagram och ändrar teckensnittsfärgen till blå.
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
använder Aspose.Cells;
med Aspose.Cells. Ritning;

Arbetsbok arbetsbok = ny arbetsbok();
Arbetsblad = arbetsbok. Arbetsblad[0];
sheet.Name = "ChartSheet";
Cells celler = ark.Cells;
celler["A1"].Value = "Frukt";
celler["A2"].Value = "äpple";
celler["A3"].Value = "orange";
celler["A4"].Value = "blåbär";
celler["A5"].Value = "kiwi";

celler["B1"].Value = "Pris";
celler["B2"].Värde = 10;
celler["B3"].Värde = 5;
celler["B4"].Värde = 20;
celler["B5"].Värde = 8;

sheet.PageSetup.PrintGridlines = sant;
sheet.PageSetup.PrintArea = "A1:F20";

ChartCollection diagram = sheet.Charts;

//Lägg till kolumndiagram
int index = charts.Add(ChartType.Column, "=ChartSheet!A1:B5", false, 6, 0, 19, 5);
Diagramdiagram = diagram[index];

//ExStep:1-
//Flytta förklaringen till vänster och ställ in teckensnittsfärgen för förklaringen
chart.Legend.Font.Color = Color.Blue;
chart.Legend.Position = LegendPositionType.Left;

//ExStep:2-
//Ange titeln på ett diagram och ändra teckensnittsfärgen till blått
chart.Title.Text = "Kolumndiagram för fruktpriser";
chart.Title.Font.Color = Color.Blue;

//ExStep:0-

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