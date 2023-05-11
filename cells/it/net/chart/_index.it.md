---
title: Creazione di grafici Excel e conversione in immagini via .NET
description:  C# codice sorgente per disegnare e convertire grafici o diagrammi in Microsoft Excel utilizzando la libreria .NET.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Creazione e conversione di grafici di file Excel via .NET" h2="Crea grafici di documenti Excel e converti in immagini utilizzando le API lato server all\'interno di applicazioni basate su .NET." >}}
{{% blocks/products/pf/feature-page-summary %}}
 Disegnare grafici è un'arte per visualizzare i dati graficamente per una facile analisi.[.NET Libreria Excel](/cells/it/net/) supporta il disegno di grafici all'interno di file Excel. API supporta la creazione di diversi grafici elencati in[Enumerazione ChartType](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype) inclusi grafici a torta, a piramide, a linee ea bolle. Inoltre, converte anche i grafici in immagini. API fornisce a[Classe Grafici](https://reference.aspose.com/cells/net/aspose.cells.charts) per i blocchi di costruzione del grafico.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Crea grafici all\'interno del file Excel" %}}

 La creazione di grafici utilizzando Excel API è semplice. Il processo è, Crea[Classe di cartella di lavoro](https://reference.aspose.com/cells/net/aspose.cells/workbook) oggetto e selezionare il primo foglio di lavoro o il relativo foglio fornendone l'indice. Inserisci i dati delle celle richieste utilizzando[Metodo PutValue](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index) . Aggiungi grafico al foglio di lavoro utilizzando la raccolta di grafici[Aggiungi metodo](https://reference.aspose.com/cells/net/aspose.cells.charts/chartcollection/methods/add) . Specificare la[Tipo di grafico](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype)dall'enumerazione ChartType.
{{% blocks/products/pf/feature-page-code h3="C# Codice per creare grafici Excel" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "create-excel-chart.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section h2="Converti grafici Excel in immagini" %}}

 Il processo di conversione dei grafici in immagini è, Usa la classe Cartella di lavoro per caricare il file Excel, seleziona il foglio di lavoro pertinente contenente i grafici e chiama il[Metodo ToImage](https://reference.aspose.com/cells/net/aspose.cells.charts.chart/toimage/methods/7) per la conversione.

{{% blocks/products/pf/feature-page-code h3="C# Codice per convertire il grafico di Excel in immagine" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "convert-xlsx-file-chart-to-images.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}
