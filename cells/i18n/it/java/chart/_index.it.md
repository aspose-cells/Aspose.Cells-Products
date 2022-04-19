---
title: Crea grafici Excel e converti in immagini tramite Java
url: /it/java/chart/
description: Java codice sorgente per disegnare e convertire grafici o diagrammi in Microsoft Excel utilizzando Java Libreria. 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Conversione e creazione di grafici di file Excel di Microsoft<sup>&reg;</sup> tramite Java" h2="Converti i grafici dei documenti Excel in immagini e crea vari grafici utilizzando le API lato server all\'interno di applicazioni basate su Java." >}}


{{% blocks/products/pf/feature-page-summary %}}

L'analisi dei dati tramite grafici mostra il quadro più ampio ed è facile prendere decisioni più informate con informazioni più chiare. [Java Libreria di Excel](/cells/java/) supporta il disegno di diverse creazione di grafici elencati da [Tipo di grafico](https://apireference.aspose.com/cells/java/com.aspose.cells/ChartType) inclusi grafici a torta, piramidali, a linee e a bolle. Inoltre, converte anche i grafici in immagini. API fornisce a [Classe di grafici](https://apireference.aspose.com/cells/java/com.aspose.cells/Chart) per rappresentare un singolo grafico Excel.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Converti grafici Excel in immagini" %}}

Il processo di conversione dei grafici in immagini inclusi JPG, PNG, TIFF, BMP ecc. È utilizzare il [Cartella di lavoro](https://apireference.aspose.com/java/cells/com.aspose.cells/workbook) class per caricare il file Excel, selezionare il relativo [posto di lavoro](https://apireference.aspose.com/cells/java/com.aspose.cells/worksheet) contenente i grafici o scorrere ogni grafico in ogni foglio di lavoro. Definire [Opzioni immagine o stampa](https://apireference.aspose.com/cells/java/com.aspose.cells/ImageOrPrintOptions) e renderizza l'immagine di output del grafico usando [Grafico.a Immagine](https://apireference.aspose.com/cells/java/com.aspose.cells/chart#toImage(java.io.OutputStream,%20com.aspose.cells.ImageOrPrintOptions)).


{{% blocks/products/pf/feature-page-code h3="Java Codice per convertire il grafico Excel in immagine" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "render-excel-chart-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}


{{% blocks/products/pf/feature-page-section h2="Crea grafici all\'interno di un file Excel" %}}

La creazione di grafici utilizzando Excel API è semplice, poiché API fornisce un insieme di classi diverse come Axis, Chart, ChartArea, ChartDataTable, ChartFrame, ChartPoint, ChartPointCollection, ChartCollection ecc. per diversi tipi di grafici. Il processo è Crea oggetto classe cartella di lavoro e seleziona il primo foglio di lavoro o il foglio pertinente fornendo il suo indice. Per l'origine dati del grafico, inserisci i valori nelle celle del foglio di lavoro utilizzando [valore impostato](https://apireference.aspose.com/cells/java/com.aspose.cells/cell#Value) metodo. Usa le raccolte di ChartCollection [aggiungi metodo](https://apireference.aspose.com/cells/java/com.aspose.cells/chartcollection#add(int,%20int,%20int,%20int,%20int)) per aggiungere il grafico, definire il tipo di grafico con l'enumerazione ChartType. Accedi al nuovo oggetto Chart dalla raccolta ChartCollection passandone l'indice. Usa il [Collezione di serie](https://apireference.aspose.com/cells/java/com.aspose.cells/SeriesCollection) oggetto grafico per specificare l'origine dati del grafico.

{{% blocks/products/pf/feature-page-code h3="Java Codice per creare grafici Excel" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "create-excel-chart-pyramid.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}