---
title: Come aggiungere un grafico a torta tramite Aspose.Cells
weight: 7700
limit:
description: Scopri come aggiungere un grafico a torta.
keywords: [Add pie chart., how to add pie chart in Aspose.Cells., how to add pie chart using Aspose.Cells]
url: /it/tutorial/add-pie-chart-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Scopri come aggiungere un grafico a torta con Aspose.Cells" >}}

<p>
In questo tutorial, aggiungeremo un grafico a torta in un file excel.
</p>

<p>
 Inizieremo creando una nuova cartella di lavoro utilizzando il file<a href="https://www.nuget.org/packages/Aspose.Cells">biblioteca Aspose.Cells</a> e aggiungi il grafico a torta.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: controllare il codice seguente per scoprire come aggiungere un grafico a torta.
//ExStepSummary:0: il codice seguente mostra come aggiungere un grafico a torta, impostare l'intervallo di dati della serie e impostare l'intervallo di dati della categoria.
//ExStepImage:0:step-1.png
//ExStepSummary:1: il codice seguente mostra come disattivare la legenda.
//ExStepImage:1:step-2.png
//ExStepSummary:2: il codice seguente mostra come accedere alle etichette dei dati, attivare i nomi delle categorie, attivare il formato percentuale e impostare la posizione.
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

//Aggiungi un grafico a torta, imposta l'intervallo di dati della serie e imposta l'intervallo di dati della categoria
int index = sheet.Charts.Add(ChartType.Pie, 6, 0, 19, 5);
Grafico grafico = foglio.Grafici[indice];
chart.NSeries.Add("B2:B5", vero);
chart.NSeries.CategoryData = "A2:A5";

//ExStep:1-
//Disattiva legenda
chart.ShowLegend = falso;

//ExStep:2-
//Accedi alle etichette dei dati, attiva i nomi delle categorie, attiva il formato percentuale e imposta la posizione
DataLabels dataLabels = chart.NSeries[0].DataLabels;
dataLabels.ShowCategoryName = vero;
dataLabels.ShowPercentage = vero;
dataLabels.Position = LabelPositionType.OutsideEnd;

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