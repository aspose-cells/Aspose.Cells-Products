---
title: So fügen Sie ein Säulendiagramm über Aspose.Cells hinzu
weight: 7700
limit:
description: Erfahren Sie, wie Sie ein Säulendiagramm hinzufügen.
keywords: [Add column chart., how to add column chart in Aspose.Cells., how to add column chart using Aspose.Cells]
url: /de/tutorial/add-column-chart-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Erfahren Sie, wie Sie mit Aspose.Cells ein Säulendiagramm hinzufügen" >}}

<p>
In diesem Tutorial fügen wir ein Säulendiagramm in eine Excel-Datei ein.
</p>

<p>
 Wir beginnen mit der Erstellung einer neuen Arbeitsmappe mithilfe von<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells Bibliothek</a> und Säulendiagramm hinzufügen.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: Bitte überprüfen Sie den folgenden Code, um herauszufinden, wie Sie ein Säulendiagramm hinzufügen.
//ExStepSummary:0: Der folgende Code zeigt, wie man ein Säulendiagramm hinzufügt.
//ExStepImage:0:step-1.png
//ExStepSummary:1: Der folgende Code zeigt, wie man die Legende nach links verschiebt und die Schriftfarbe der Legende festlegt.
//ExStepImage:1:step-2.png
//ExStepSummary:2: Der folgende Code zeigt, wie man den Titel eines Diagramms festlegt und die Schriftfarbe in Blau ändert.
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

//Säulendiagramm hinzufügen
int index = charts.Add(ChartType.Column, "=ChartSheet!A1:B5", false, 6, 0, 19, 5);
Diagramm chart = charts[index];

//ExStep:1-
//Verschieben Sie die Legende nach links und legen Sie die Schriftfarbe der Legende fest
chart.Legend.Font.Color = Color.Blue;
chart.Legend.Position = LegendPositionType.Left;

//ExStep:2-
//Legen Sie den Titel eines Diagramms fest und ändern Sie die Schriftfarbe in Blau
chart.Title.Text = "Fruchtpreis-Säulendiagramm";
chart.Title.Font.Color = Color.Blue;

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