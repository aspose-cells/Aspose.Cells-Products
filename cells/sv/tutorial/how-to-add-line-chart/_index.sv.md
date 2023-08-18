---
title: Hur man lägger till linjediagram via Aspose.Cells
weight: 7700
limit:
description: Lär dig hur du lägger till linjediagram.
keywords: [Add line chart., how to add line chart in Aspose.Cells., how to add line chart using Aspose.Cells]
url: /sv/tutorial/add-line-chart-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Lär dig hur du lägger till linjediagram med Aspose.Cells" >}}

<p>
I den här handledningen lägger vi till linjediagram i en excel-fil.
</p>

<p>
 Vi börjar med att skapa en ny arbetsbok med hjälp av<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells bibliotek</a> och lägg till linjediagram.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: Kontrollera följande kod för att ta reda på hur du lägger till linjediagram.
//ExStepSummary:0: Följande kod visar hur man lägger till linjediagram, ställer in seriedataintervall och ställer in kategoridataintervall.
//ExStepImage:0:step-1.png
//ExStepSummary:1: Följande kod visar hur man flyttar förklaringen till botten och ställer in teckensnittsfärg för förklaringen.
//ExStepImage:1:step-2.png
//ExStepSummary:2: Följande kod visar hur du kommer åt dataetiketter, aktiverar kategorinamn och ställer in position.
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

//Lägg till linjediagram, ställ in seriedataintervall och ställ in kategoridataintervall
int index = sheet.Charts.Add(ChartType.Line, 6, 0, 19, 5);
Diagramdiagram = ark.Charts[index];
chart.NSeries.Add("B2:B5", true);
chart.NSeries.CategoryData = "A2:A5";

//ExStep:1-
//Flytta förklaringen till botten och ställ in teckensnittsfärg för förklaringen
chart.Legend.Font.Color = Color.Blue;
chart.Legend.Position = LegendPositionType.Bottom;

//ExStep:2-
//Åtkomst till dataetiketter, aktivera kategorinamn och ange position
DataLabels dataLabels = diagram.NSeries[0].DataLabels;
dataLabels.ShowCategoryName = true;
dataLabels.Position = LabelPositionType.Center;

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