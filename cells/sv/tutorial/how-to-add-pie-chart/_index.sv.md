---
title: Hur man lägger till cirkeldiagram via Aspose.Cells
weight: 7700
limit:
description: Lär dig hur du lägger till ett cirkeldiagram.
keywords: [Add pie chart., how to add pie chart in Aspose.Cells., how to add pie chart using Aspose.Cells]
url: /sv/tutorial/add-pie-chart-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Lär dig hur du lägger till ett cirkeldiagram med Aspose.Cells" >}}

<p>
I den här handledningen lägger vi till cirkeldiagram i en excel-fil.
</p>

<p>
 Vi börjar med att skapa en ny arbetsbok med hjälp av<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells bibliotek</a> och lägg till cirkeldiagram.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: Kontrollera följande kod för att ta reda på hur du lägger till cirkeldiagram.
//ExStepSummary:0: Följande kod visar hur man lägger till cirkeldiagram, ställer in seriedataintervall och ställer in kategoridataintervall.
//ExStepImage:0:step-1.png
//ExStepSummary:1: Följande kod visar hur man stänger av legend.
//ExStepImage:1:step-2.png
//ExStepSummary:2: Följande kod visar hur du kommer åt dataetiketter, aktiverar kategorinamn, aktiverar procentformat och ställer in position.
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

//Lägg till cirkeldiagram, ställ in seriedataintervall och ställ in kategoridataintervall
int index = sheet.Charts.Add(ChartType.Pie, 6, 0, 19, 5);
Diagramdiagram = ark.Charts[index];
chart.NSeries.Add("B2:B5", true);
chart.NSeries.CategoryData = "A2:A5";

//ExStep:1-
//Stäng av legend
chart.ShowLegend = false;

//ExStep:2-
//Åtkomst till dataetiketter, aktivera kategorinamn, aktivera procentformat och ange position
DataLabels dataLabels = diagram.NSeries[0].DataLabels;
dataLabels.ShowCategoryName = true;
dataLabels.ShowPercentage = sant;
dataLabels.Position = LabelPositionType.OutsideEnd;

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