---
title: Cirkeldiagram toevoegen via Aspose.Cells
weight: 7700
limit:
description: Leer hoe u een cirkeldiagram toevoegt.
keywords: [Add pie chart., how to add pie chart in Aspose.Cells., how to add pie chart using Aspose.Cells]
url: /nl/tutorial/add-pie-chart-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Leer hoe u een cirkeldiagram toevoegt met Aspose.Cells" >}}

<p>
In deze zelfstudie voegen we een cirkeldiagram toe aan een Excel-bestand.
</p>

<p>
 We beginnen met het maken van een nieuwe werkmap met behulp van de<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells bibliotheek</a> en voeg een cirkeldiagram toe.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: Controleer de volgende code om te zien hoe u een cirkeldiagram kunt toevoegen.
//ExStepSummary:0: De volgende code laat zien hoe u een cirkeldiagram toevoegt, het reeksgegevensbereik instelt en het categoriegegevensbereik instelt.
//ExStepImage:0:stap-1.png
//ExStepSummary:1: De volgende code laat zien hoe u de legenda uitschakelt.
//ExStepImage:1:stap-2.png
//ExStepSummary:2: De volgende code laat zien hoe u toegang krijgt tot gegevenslabels, categorienamen inschakelt, het percentageformaat inschakelt en de positie instelt.
//ExStepImage:2:stap-3.png
//ExStart
//ExStep:0-
via Aspose.Cells;
via Aspose.Cells.Tekening;

Werkmap werkmap = nieuwe werkmap();
Werkbladblad = werkmap.Werkbladen[0];
sheet.Name = "Grafiekblad";
Cells cellen = blad.Cells;
cellen["A1"].Waarde = "Fruit";
cellen["A2"].Waarde = "appel";
cellen["A3"].Waarde = "oranje";
cellen["A4"].Waarde = "bosbes";
cellen["A5"].Waarde = "kiwi";

cellen["B1"].Waarde = "Prijs";
cellen["B2"].Waarde = 10;
cellen["B3"].Waarde = 5;
cellen["B4"].Waarde = 20;
cellen["B5"].Waarde = 8;

sheet.PageSetup.PrintGridlines = waar;
sheet.PageSetup.PrintArea = "A1:F20";

ChartCollection-grafieken = blad. Grafieken;

//Voeg een cirkeldiagram toe, stel het reeksgegevensbereik in en stel het categoriegegevensbereik in
int index = blad.Charts.Add(ChartType.Pie, 6, 0, 19, 5);
Grafiekdiagram = blad. Grafieken [index];
chart.NSeries.Add("B2:B5", waar);
chart.NSeries.CategoryData = "A2:A5";

//ExStap:1-
// Schakel de legenda uit
chart.ShowLegend = false;

//ExStap:2-
// Krijg toegang tot gegevenslabels, schakel categorienamen in, schakel het percentageformaat in en stel de positie in
DataLabels dataLabels = grafiek.NSeries[0].DataLabels;
dataLabels.ShowCategoryName = waar;
dataLabels.ShowPercentage = waar;
dataLabels.Position = LabelPositionType.OutsideEnd;

//ExStep:0-

//ExEnd
{{< /app/cells/tutorial >}}
<br />

<br />
<br />
<div class="code-sample">
    <ul class="link-list">
        <li class="link-item"><a href="https://docs.aspose.com/cells/net/installation/">Installatie van Aspose.Cells</a></li>
        <li class="link-item"><a href="https://products.aspose.app/cells/editor/">Aspose.Cells Redacteur</a></li>
    </ul>
</div>

{{< /blocks/products/pf/feature-page-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}