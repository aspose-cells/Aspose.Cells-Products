---
title: Dividi foglio di calcolo Excel in fogli di lavoro in Java
description: Java codici sorgente che spiega come dividere i file Excel Microsoft in più documenti utilizzando la libreria Excel Java
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Divisione file Excel via Java" h2="Dividi il foglio di calcolo Excel in fogli di lavoro all\'interno di applicazioni basate su Java" >}}
{{% blocks/products/pf/feature-page-summary %}}
 Esistono vari scenari, quando è necessario dividere i file Excel come un foglio di calcolo contenente i dati degli studenti con l'assegnazione di un singolo foglio per ogni studente. E c'è bisogno di dividere ogni foglio in modo saggio come un file separato. Per automatizzare l'applicazione via Java,[Java Excel API](/cells/it/java/) è lì per dividere il documento Excel a fogli. I formati supportati includono XLS, XLSX, XLSB, XLSM, ODS.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Dividi documento Excel in più file" %}}

 Il modo più semplice per dividere il file Excel in un foglio è accedere a tutti i fogli, scorrere ogni foglio e salvarli uno per uno nel formato desiderato. Per caricare il foglio di lavoro, API fornisce[Cartella di lavoro](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) classe.[getWorksheets().getCount()](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#Count) metodo ottiene il numero totale di fogli. Scorri ogni foglio e usa[getWorksheets().get(indicefoglio)](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#get)per l'accesso al foglio specifico. Sposta i dati del foglio selezionato nell'oggetto della classe Workbook appena creato utilizzando[Metodo di copia](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#copy(com.aspose.cells.Workbook)). Infine salvalo nel formato richiesto.

{{% blocks/products/pf/feature-page-code h3="Java Codice per dividere file Excel" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-xls-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="Dividi il foglio di lavoro Excel in riquadri" %}}

API fornisce anche la funzionalità di suddividere il foglio di lavoro di Excel in diversi riquadri. Il processo è, Carica il file usando la classe Workbook. Seleziona il primo foglio di lavoro o qualsiasi foglio richiesto fornendo il suo indice. Chiama setActiveCell con l'indice di cella pertinente come parametro. E infine dividere la finestra del foglio di lavoro in riquadri diversi chiamando il metodo split().

{{% blocks/products/pf/feature-page-code h3="Java Codice per dividere il foglio Excel nella visualizzazione del riquadro" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-excel-spreadsheet-into-panes.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
