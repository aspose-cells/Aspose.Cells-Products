---
title: Kolomdiagram toevoegen via Aspose.Cells
weight: 7700
limit:
description: Meer informatie over het toevoegen van een kolomdiagram.
keywords: [Add column chart., how to add column chart in Aspose.Cells., how to add column chart using Aspose.Cells]
url: /nl/tutorial/add-column-chart-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Leer hoe u een kolomdiagram kunt toevoegen met Aspose.Cells" >}}

<p>
In deze zelfstudie voegen we een kolomdiagram toe aan een Excel-bestand.
</p>

<p>
 We beginnen met het maken van een nieuwe werkmap met behulp van de<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells bibliotheek</a> en kolomdiagram toevoegen.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: controleer de volgende code om erachter te komen hoe u een kolomdiagram kunt toevoegen.
//ExStepSummary:0: de volgende code laat zien hoe u een kolomdiagram toevoegt.
//ExStepImage:0:stap-1.png
//ExStepSummary:1: De volgende code laat zien hoe u de legenda naar links verplaatst en de lettertypekleur van de legenda instelt.
//ExStepImage:1:step-2.png
//ExStepSummary:2: De volgende code laat zien hoe u de titel van een diagram instelt en de lettertypekleur in blauw wijzigt.
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
met behulp van Aspose.Cells;
met behulp van Aspose.Cells.Tekening;

Werkmap werkmap = nieuwe werkmap();
Werkblad = werkboek. Werkbladen [0];
blad.Naam = "Kaartblad";
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

blad.PageSetup.PrintGridlines = waar;
blad.PageSetup.PrintArea = "A1:F20";

ChartCollection charts = blad.Diagrammen;

//Kolomdiagram toevoegen
int index = charts.Add(ChartType.Column, "=ChartSheet!A1:B5", false, 6, 0, 19, 5);
Grafiekgrafiek = grafieken[index];

//ExStap:1-
// Verplaats de legenda naar links en stel de letterkleur van de legenda in
chart.Legend.Font.Color = Kleur.Blauw;
chart.Legend.Position = LegendPositionType.Left;

//ExStep:2-
// Stel de titel van een diagram in en wijzig de letterkleur in blauw
chart.Title.Text = "Fruitprijskolomgrafiek";
chart.Title.Font.Color = Color.Blue;

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