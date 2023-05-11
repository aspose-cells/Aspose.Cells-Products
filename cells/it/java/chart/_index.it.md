---
title: Crea grafici Excel e converti in immagini via Java
description:  Java codice sorgente per disegnare e convertire grafici o diagrammi in Microsoft Excel utilizzando la libreria Java.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Conversione e creazione di grafici di file Excel via Java" h2="Converti grafici di documenti Excel in immagini e crea vari grafici utilizzando le API lato server all\'interno di applicazioni basate su Java." >}}


{{% blocks/products/pf/feature-page-summary %}}

 L'analisi dei dati tramite grafici mostra il quadro più ampio ed è facile prendere decisioni più informate con approfondimenti più chiari.[Java Libreria Excel](/cells/it/java/) supporta il disegno di diverse creazioni di grafici elencate da[Tipo di grafico](https://reference.aspose.com/cells/java/com.aspose.cells/ChartType) inclusi grafici a torta, a piramide, a linee ea bolle. Inoltre, converte anche i grafici in immagini. API fornisce a[Classe Grafici](https://reference.aspose.com/cells/java/com.aspose.cells/Chart)per rappresentare un singolo grafico di Excel.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Converti grafici Excel in immagini" %}}

 Il processo di conversione dei grafici in immagini tra cui JPG, PNG, TIFF, BMP ecc.[Cartella di lavoro](https://reference.aspose.com/java/cells/com.aspose.cells/workbook) class per caricare il file Excel, selezionare il relativo[foglio di lavoro](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet) contenente i grafici o iterare attraverso ogni grafico in ogni foglio di lavoro. Definire[ImageOrPrintOptions](https://reference.aspose.com/cells/java/com.aspose.cells/ImageOrPrintOptions) e rendere l'immagine di output del grafico utilizzando[Chart.toImage](https://reference.aspose.com/cells/java/com.aspose.cells/chart#toImage(java.io.OutputStream,%20com.aspose.cells.ImageOrPrintOptions)).


{{% blocks/products/pf/feature-page-code h3="Java Codice per convertire il grafico di Excel in immagine" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "render-excel-chart-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}


{{% blocks/products/pf/feature-page-section h2="Crea grafici all\'interno del file Excel" %}}

 La creazione di grafici utilizzando Excel API è semplice, poiché API fornisce un insieme di classi diverse come Axis, Chart, ChartArea, ChartDataTable, ChartFrame, ChartPoint, ChartPointCollection, ChartCollection ecc. Per diversi tipi di grafici. Il processo è, Crea oggetto classe cartella di lavoro e seleziona il primo foglio di lavoro o il foglio pertinente fornendo il suo indice. Per l'origine dati del grafico, inserire i valori nelle celle del foglio di lavoro utilizzando[valore impostato](https://reference.aspose.com/cells/java/com.aspose.cells/cell#Value)metodo. Usa la raccolta di ChartCollection[aggiungere metodo](https://reference.aspose.com/cells/java/com.aspose.cells/chartcollection#add(int,%20int,%20int,%20int,%20int) ) per aggiungere il grafico, definire il tipo di grafico con l'enumerazione ChartType. Accedi al nuovo oggetto Chart dalla raccolta ChartCollection passandone l'indice. Usa il[SerieCollezione](https://reference.aspose.com/cells/java/com.aspose.cells/SeriesCollection) grafico per specificare l'origine dati del grafico.

{{% blocks/products/pf/feature-page-code h3="Java Codice per creare grafici Excel" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "create-excel-chart-pyramid.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
