---
title: Creazione di grafici Excel e conversione in immagini tramite .NET
url: /it/net/chart/
description: C# codice sorgente per disegnare e convertire grafici o diagrammi in Microsoft Excel utilizzando .NET Libreria. 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Creazione e conversione di grafici di file Excel Microsoft<sup>&reg;</sup> tramite .NET" h2="Crea grafici di documenti Excel e convertili in immagini utilizzando le API lato server all\'interno di applicazioni basate su .NET." >}}
{{% blocks/products/pf/feature-page-summary %}}
Disegnare grafici è un'arte per visualizzare i dati graficamente per una facile analisi. [.NET Libreria di Excel](/cells/net/) supporta grafici di disegno all'interno di file Excel. API supporta la creazione di grafici diversi elencati in [Enumerazione ChartType](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype) inclusi grafici a torta, piramidali, a linee e a bolle. Inoltre, converte anche i grafici in immagini. API fornisce a [Classe di grafici](https://reference.aspose.com/cells/net/aspose.cells.charts) per i blocchi di costruzione del grafico.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Crea grafici all\'interno di un file Excel" %}}

Creare grafici utilizzando Excel API è semplice. Il processo è Crea [Classe cartella di lavoro](https://reference.aspose.com/cells/net/aspose.cells/workbook) oggetto e selezionare il primo foglio di lavoro o il foglio pertinente fornendo il relativo indice. Inserisci i dati delle celle richieste utilizzando [Metodo PutValue](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index). Aggiungi un grafico al foglio di lavoro utilizzando la raccolta di grafici [Aggiungi metodo](https://reference.aspose.com/cells/net/aspose.cells.charts/chartcollection/methods/add). Specificare la [Tipo di grafico](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype) dall'enumerazione ChartType.
{{% blocks/products/pf/feature-page-code h3="C# Codice per creare grafici Excel" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "create-excel-chart.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section h2="Converti grafici Excel in immagini" %}}

Il processo di conversione dei grafici in immagini è, utilizzare la classe Workbook per caricare il file Excel, selezionare il relativo workseet contenente i grafici e chiamare il [Metodo ToImage](https://reference.aspose.com/cells/net/aspose.cells.charts.chart/toimage/methods/7) per la conversione.

{{% blocks/products/pf/feature-page-code h3="C# Codice per convertire il grafico Excel in immagine" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "convert-xlsx-file-chart-to-images.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}