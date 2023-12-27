---
title: So fügen Sie ein Kreisdiagramm über Aspose.Cells hinzu
weight: 7700
limit:
description: Erfahren Sie, wie Sie ein Kreisdiagramm hinzufügen.
keywords: [Add pie chart., how to add pie chart in Aspose.Cells., how to add pie chart using Aspose.Cells]
url: /de/tutorial/add-pie-chart-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Erfahren Sie, wie Sie mit Aspose.Cells ein Kreisdiagramm hinzufügen" >}}

<p>
In diesem Tutorial fügen wir ein Kreisdiagramm in eine Excel-Datei ein.
</p>

<p>
 Wir beginnen mit der Erstellung einer neuen Arbeitsmappe mithilfe von<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells Bibliothek</a> und Kreisdiagramm hinzufügen.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: Bitte überprüfen Sie den folgenden Code, um herauszufinden, wie Sie ein Kreisdiagramm hinzufügen.
//ExStepSummary:0: Der folgende Code zeigt, wie man ein Kreisdiagramm hinzufügt, den Seriendatenbereich festlegt und den Kategoriedatenbereich festlegt.
//ExStepImage:0:step-1.png
//ExStepSummary:1: Der folgende Code zeigt, wie die Legende deaktiviert wird.
//ExStepImage:1:step-2.png
//ExStepSummary:2: Der folgende Code zeigt, wie man auf Datenbeschriftungen zugreift, Kategorienamen aktiviert, das Prozentformat aktiviert und die Position festlegt.
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
unter Aspose.Cells;
mit Aspose.Cells.Zeichnung;

Arbeitsmappe Arbeitsmappe = new Workbook();
Arbeitsblatt sheet = workbook.Worksheets[0];
sheet.Name = "ChartSheet";
Cells Zellen = Blatt.Cells;
Zellen["A1"].Value = "Fruit";
Zellen["A2"].Value = "Apfel";
Zellen["A3"].Value = "orange";
Zellen["A4"].Value = "Blaubeere";
Zellen["A5"].Value = "kiwi";

Zellen["B1"].Value = "Preis";
Zellen["B2"].Wert = 10;
Zellen["B3"].Wert = 5;
Zellen["B4"].Wert = 20;
Zellen["B5"].Wert = 8;

sheet.PageSetup.PrintGridlines = true;
sheet.PageSetup.PrintArea = "A1:F20";

ChartCollection charts = sheet.Charts;

//Kreisdiagramm hinzufügen, Seriendatenbereich festlegen und Kategoriedatenbereich festlegen
int index = sheet.Charts.Add(ChartType.Pie, 6, 0, 19, 5);
Diagramm chart = sheet.Charts[index];
chart.NSeries.Add("B2:B5", true);
chart.NSeries.CategoryData = "A2:A5";

//ExStep:1-
//Legende ausschalten
chart.ShowLegend = false;

//ExStep:2-
//Auf Datenbeschriftungen zugreifen, Kategorienamen aktivieren, Prozentformat aktivieren und Position festlegen
DataLabels dataLabels = chart.NSeries[0].DataLabels;
dataLabels.ShowCategoryName = true;
dataLabels.ShowPercentage = true;
dataLabels.Position = LabelPositionType.OutsideEnd;

//ExStep:0-

//ExEnd
{{< /app/cells/tutorial >}}
<br />

<br />
<br />
<div class="code-sample">
    <ul class="link-list">
        <li class="link-item"><a href="https://docs.aspose.com/cells/net/installation/">Installation von Aspose.Cells</a></li>
        <li class="link-item"><a href="https://products.aspose.app/cells/editor/">Aspose.Cells Herausgeber</a></li>
    </ul>
</div>

{{< /blocks/products/pf/feature-page-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}