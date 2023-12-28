---
title: Come aggiungere un istogramma tramite Aspose.Cells
weight: 7700
limit:
description: Scopri come aggiungere un grafico a colonne.
keywords: [Add column chart., how to add column chart in Aspose.Cells., how to add column chart using Aspose.Cells]
url: /it/tutorial/add-column-chart-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Scopri come aggiungere un istogramma con Aspose.Cells" >}}

<p>
In questo tutorial, aggiungeremo un istogramma in un file Excel.
</p>

<p>
 Inizieremo creando una nuova cartella di lavoro utilizzando il file<a href="https://www.nuget.org/packages/Aspose.Cells">Biblioteca Aspose.Cells</a> e aggiungi un grafico a colonne.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: controlla il codice seguente per scoprire come aggiungere un grafico a colonne.
//ExStepSummary:0: il codice seguente mostra come aggiungere un istogramma.
//ExStepImage:0:step-1.png
//ExStepSummary:1: il codice seguente mostra come spostare la legenda a sinistra e impostare il colore del carattere della legenda.
//ExStepImage:1:step-2.png
//ExStepSummary:2: il codice seguente mostra come impostare il titolo di un grafico e modificare il colore del carattere in blu.
//ExStepImage:2:step-3.png
//ExStart
//PassoEx:0-
utilizzando Aspose.Cells;
utilizzando Aspose.Cells.Disegno;

Cartella di lavoro cartella di lavoro = nuova cartella di lavoro();
Foglio di lavoro = cartella di lavoro.Fogli di lavoro[0];
sheet.Name = "Foglio grafico";
Cells celle = foglio.Cells;
celle["A1"].Valore = "Frutta";
celle["A2"].Valore = "mela";
celle["A3"].Valore = "arancione";
celle["A4"].Valore = "mirtillo";
celle["A5"].Valore = "kiwi";

celle["B1"].Valore = "Prezzo";
celle["B2"].Valore = 10;
celle["B3"].Valore = 5;
celle["B4"].Valore = 20;
celle["B5"].Valore = 8;

sheet.PageSetup.PrintGridlines = true;
foglio.PageSetup.PrintArea = "A1:F20";

Grafici ChartCollection = sheet.Charts;

//Aggiungi grafico a colonne
int indice = grafici.Add(ChartType.Column, "=ChartSheet!A1:B5", false, 6, 0, 19, 5);
Grafico grafico = grafici[indice];

//ExPassaggio:1-
//Sposta la legenda a sinistra e imposta il colore del carattere della legenda
chart.Legend.Font.Color = Colore.Blu;
chart.Legend.Position = LegendPositionType.Left;

//ExPassaggio:2-
//Imposta il titolo di un grafico e cambia il colore del carattere in blu
chart.Title.Text = "Grafico a colonne dei prezzi della frutta";
grafico.Titolo.Font.Color = Colore.Blu;

//PassoEx:0-

//Exend
{{< /app/cells/tutorial >}}
<br />

<br />
<br />
<div class="code-sample">
    <ul class="link-list">
        <li class="link-item"><a href="https://docs.aspose.com/cells/net/installation/">Installazione dello Aspose.Cells</a></li>
        <li class="link-item"><a href="https://products.aspose.app/cells/editor/">Aspose.Cells Redattore</a></li>
    </ul>
</div>

{{< /blocks/products/pf/feature-page-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}