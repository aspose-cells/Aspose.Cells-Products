---
title: Come aggiungere un istogramma tramite Aspose.Cells
weight: 7700
limit:
description: Scopri come aggiungere un istogramma.
keywords: [Add column chart., how to add column chart in Aspose.Cells., how to add column chart using Aspose.Cells]
url: /it/tutorial/add-column-chart-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Scopri come aggiungere un istogramma con Aspose.Cells" >}}

<p>
In questo tutorial, aggiungeremo un istogramma in un file excel.
</p>

<p>
 Inizieremo creando una nuova cartella di lavoro utilizzando il file<a href="https://www.nuget.org/packages/Aspose.Cells">biblioteca Aspose.Cells</a> e aggiungi un istogramma.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: controllare il codice seguente per scoprire come aggiungere un istogramma.
//ExStepSummary:0: il codice seguente mostra come aggiungere un istogramma.
//ExStepImage:0:step-1.png
//ExStepSummary:1: il codice seguente mostra come spostare la legenda a sinistra e impostare il colore del carattere della legenda.
//ExStepImage:1:step-2.png
//ExStepSummary:2: il codice seguente mostra come impostare il titolo di un grafico e modificare il colore del carattere in blu.
//ExStepImage:2:step-3.png
//ExStart
//ExPasso:0-
utilizzando il numero Aspose.Cells;
utilizzando Aspose.Cells.Drawing;

Cartella di lavoro cartella di lavoro = nuova cartella di lavoro();
Foglio di lavoro = workbook.Worksheets[0];
foglio.Name = "FoglioGrafico";
Cells celle = foglio.Cells;
cells["A1"].Value = "Frutta";
cells["A2"].Value = "mela";
celle["A3"].Valore = "arancione";
cells["A4"].Value = "mirtillo";
celle["A5"].Valore = "kiwi";

cells["B1"].Value = "Prezzo";
celle["B2"].Valore = 10;
celle["B3"].Valore = 5;
celle["B4"].Valore = 20;
celle["B5"].Valore = 8;

sheet.PageSetup.PrintGridlines = true;
sheet.PageSetup.PrintArea = "A1:F20";

Grafici ChartCollection = sheet.Charts;

//Aggiungi istogramma
int index = charts.Add(ChartType.Column, "=ChartSheet!A1:B5", false, 6, 0, 19, 5);
Grafico grafico = grafici[indice];

//ExStep:1-
//Sposta la legenda a sinistra e imposta il colore del carattere della legenda
chart.Legend.Font.Color = Color.Blue;
chart.Legend.Position = LegendPositionType.Left;

//ExStep:2-
//Imposta il titolo di un grafico e cambia il colore del carattere in blu
chart.Title.Text = "Istogramma prezzo frutta";
chart.Title.Font.Color = Color.Blue;

//ExPasso:0-

//ExFine
{{< /app/cells/tutorial >}}
<br />

<br />
<br />
<div class="code-sample">
    <ul class="link-list">
        <li class="link-item"><a href="https://docs.aspose.com/cells/net/installation/">Installazione di Aspose.Cells</a></li>
        <li class="link-item"><a href="https://products.aspose.app/cells/editor/">Aspose.Cells Editore</a></li>
    </ul>
</div>

{{< /blocks/products/pf/feature-page-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}