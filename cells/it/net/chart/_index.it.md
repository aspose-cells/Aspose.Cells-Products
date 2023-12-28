---
title: Creazione Grafici Excel e Conversione in Immagini via .NET
description:  Codice sorgente C# per disegnare e convertire un grafico o un diagramma in Excel Microsoft utilizzando la Libreria .NET.
keywords: [C# Aspose.Cells., c# Convert chart to image., c# Save chart to image., c# chart to image., create charts in c#., insert charts in c#., manage charts in c#]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Creazione e conversione di grafici in file Excel via .NET" h2="Crea grafici di documenti Excel e convertili in immagini utilizzando le API lato server all\'interno di applicazioni basate su .NET." >}}
{{% blocks/products/pf/feature-page-summary %}}
 Disegnare grafici è un'arte per visualizzare graficamente i dati per una facile analisi.[.NET Libreria Excel](/cells/it/net/) supporta il disegno di grafici all'interno di file Excel. API supporta la creazione di diversi grafici elencati in[Enumerazione ChartType](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype) inclusi grafici a torta, a piramide, a linee e a bolle. Inoltre, converte anche i grafici in immagini. API fornisce a[Lezione di grafici](https://reference.aspose.com/cells/net/aspose.cells.charts) per gli elementi costitutivi del grafico.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Crea grafici all\'interno di file Excel" %}}

 Creare grafici utilizzando Excel API è semplice. Il processo è creare[Classe cartella di lavoro](https://reference.aspose.com/cells/net/aspose.cells/workbook)oggetto e selezionare il primo foglio di lavoro o il foglio rilevante fornendo il relativo indice. Inserisci i dati delle celle richieste utilizzando[Metodo PutValue](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index) . Aggiungi un grafico al foglio di lavoro utilizzando la raccolta Grafici[Aggiungi metodo](https://reference.aspose.com/cells/net/aspose.cells.charts/chartcollection/methods/add) . Specificare la[ChartType](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype) dall'enumerazione ChartType.
{{% blocks/products/pf/feature-page-code h3="C# Codice per Creare Grafici Excel" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "create-excel-chart.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section h2="Converti grafici Excel in immagini" %}}

 Il processo di conversione dei grafici in immagini consiste nell'utilizzare la classe Workbook per caricare il file Excel, selezionare il workseet pertinente contenente i grafici e chiamare il comando[Metodo ToImage](https://reference.aspose.com/cells/net/aspose.cells.charts.chart/toimage/methods/7) per la conversione.

{{% blocks/products/pf/feature-page-code h3="C# Codice per convertire grafico Excel in immagine" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "convert-xlsx-file-chart-to-images.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}
