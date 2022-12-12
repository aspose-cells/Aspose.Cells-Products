---
title: Dividi foglio di lavoro Excel in fogli di lavoro in Java

description: Java codici sorgente che spiegano come dividere i file di Microsoft Excel in più documenti utilizzando la Java libreria di Excel
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Divisione file Microsoft<sup>&reg;</sup> Excel tramite Java" h2="Dividi foglio di lavoro Excel in fogli di lavoro all\'interno di applicazioni basate su Java" >}}
{{% blocks/products/pf/feature-page-summary %}}
Ci sono una varietà di scenari, quando è necessario dividere file Excel come un foglio di calcolo contenente i dati degli studenti con l'assegnazione di un singolo foglio per ogni studente. E c'è bisogno di dividere ogni foglio per studente come un file separato. Per automatizzarlo tramite l'applicazione Java, [Java Excel API](/cells/java/) c'è per dividere il documento Excel in modo foglio. I formati supportati includono XLS, XLSX, XLSB, XLSM, ODS. 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Dividi il documento Excel in più file" %}}

Il modo più semplice per dividere il file Excel in un foglio è accedere a tutti i fogli, scorrere ogni foglio e salvarlo uno per uno nel formato desiderato. Per caricare il foglio di lavoro, API fornisce [Cartella di lavoro](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) classe. [getWorksheets().getCount()](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#Count) il metodo ottiene il numero totale di fogli. Scorri ogni foglio e usa [getWorksheets().get(sheetindex)](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#get) per l'accesso alla scheda specifica. Sposta i dati del foglio selezionato nell'oggetto classe Cartella di lavoro appena creato utilizzando [Metodo di copia](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#copy(com.aspose.cells.Workbook)). Infine salvalo nel formato richiesto.

{{% blocks/products/pf/feature-page-code h3="Java Codice per dividere i file Excel" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-xls-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="Dividi il foglio di lavoro di Excel in riquadri" %}}

API fornisce anche la funzionalità di suddivisione del foglio di lavoro di Excel in diversi riquadri. Il processo è Caricare il file utilizzando la classe Cartella di lavoro. Seleziona il primo foglio di lavoro o qualsiasi foglio richiesto fornendo il suo indice. Chiama il setActiveCell con l'indice di cella rilevante come parametro. E infine dividere la finestra del foglio di lavoro in diversi riquadri chiamando il metodo split().

{{% blocks/products/pf/feature-page-code h3="Java Codice per dividere il foglio Excel in visualizzazione riquadro" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-excel-spreadsheet-into-panes.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
