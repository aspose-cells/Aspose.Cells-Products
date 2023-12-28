---
title: Crea grafici Excel e converti in immagini via Java
description:  Codice sorgente Java per disegnare e convertire un grafico o un diagramma in Excel Microsoft utilizzando la Libreria Java.
keywords: [Java Aspose.Cells., Java Convert chart to image., Java Save chart to image., Java chart to image., create charts in Java., insert charts in Java., manage charts in Java]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Conversione e creazione grafici file Excel via Java" h2="Converti grafici di documenti Excel in immagini e crea vari grafici utilizzando API lato server all\'interno di applicazioni basate su Java." >}}


{{% blocks/products/pf/feature-page-summary %}}

 L'analisi dei dati tramite grafici mostra il quadro più ampio ed è facile prendere decisioni più informate con informazioni più chiare.[Java Libreria Excel](/cells/it/java/) supporta il disegno di diverse creazioni di grafici elencate per[ChartType](https://reference.aspose.com/cells/java/com.aspose.cells/ChartType) inclusi grafici a torta, a piramide, a linee e a bolle. Inoltre, converte anche i grafici in immagini. API fornisce a[Lezione di grafici](https://reference.aspose.com/cells/java/com.aspose.cells/Chart) per rappresentare un singolo grafico Excel.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Converti grafici Excel in immagini" %}}

 Il processo di conversione dei grafici in immagini tra cui JPG, PNG, TIFF, BMP ecc. è utilizzare il[Cartella di lavoro](https://reference.aspose.com/java/cells/com.aspose.cells/workbook) class per caricare il file Excel, selezionare il file pertinente[workset](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet) contenente i grafici o scorrere ciascun grafico in ogni foglio di lavoro. Definire[OpzioniImmagineOrStampa](https://reference.aspose.com/cells/java/com.aspose.cells/ImageOrPrintOptions) ed eseguire il rendering dell'immagine di output del grafico utilizzando[Chart.toImage](https://reference.aspose.com/cells/java/com.aspose.cells/chart#toImage(java.io.OutputStream,%20com.aspose.cells.ImageOrPrintOptions)).


{{% blocks/products/pf/feature-page-code h3="Java Codice per convertire grafico Excel in immagine" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "render-excel-chart-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}


{{% blocks/products/pf/feature-page-section h2="Crea grafici all\'interno di file Excel" %}}

Creare grafici utilizzando Excel API è semplice, poiché API fornisce una serie di classi diverse come Axis, Chart, ChartArea, ChartDataTable, ChartFrame, ChartPoint, ChartPointCollection, ChartCollection ecc. per diversi tipi di grafici. Il processo è creare un oggetto classe cartella di lavoro e selezionare il primo foglio di lavoro o il foglio pertinente fornendo il relativo indice. Per l'origine dati del grafico, inserire i valori nelle celle del foglio di lavoro utilizzando[valore impostato](https://reference.aspose.com/cells/java/com.aspose.cells/cell#Value) metodo. Utilizza la raccolta ChartCollection[aggiungi metodo](https://reference.aspose.com/cells/java/com.aspose.cells/chartcollection#add(int,%20int,%20int,%20int,%20int) ) per aggiungere il grafico, definire il tipo di grafico con l'enumerazione ChartType. Accedi al nuovo oggetto Chart dalla raccolta ChartCollection passandone l'indice. Usa il[SerieCollezione](https://reference.aspose.com/cells/java/com.aspose.cells/SeriesCollection) oggetto grafico per specificare l'origine dati del grafico.

{{% blocks/products/pf/feature-page-code h3="Java Codice per Creare Grafici Excel" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "create-excel-chart-pyramid.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
