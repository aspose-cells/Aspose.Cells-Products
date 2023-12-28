---
title: Dividi il foglio di calcolo Excel in fogli di lavoro in Java
description: Java codici sorgente che spiegano come dividere i file Excel Microsoft in più documenti utilizzando la libreria Excel Java
keywords: [Java Aspose.Cells., Java split excel files., Java how to split excel files into multiple files., Java excel splitter., Java split Cell., Cell splitter using Java]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Suddivisione file Excel via Java" h2="Dividi il foglio di calcolo Excel in fogli di lavoro all\'interno di applicazioni basate su Java" >}}
{{% blocks/products/pf/feature-page-summary %}}
Esistono diversi scenari in cui è necessario dividere file Excel come un foglio di calcolo contenente i dati degli studenti con assegnazione di un singolo foglio per ogni studente. Ed è necessario dividere ogni foglio dal punto di vista dello studente come un file separato. Per automatizzarla applicazione via Java,[Java Excel API](/cells/it/java/) è lì per dividere il documento Excel in fogli. I formati supportati includono XLS, XLSX, XLSB, XLSM, ODS.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Dividi il documento Excel in più file" %}}

 Il modo più semplice per dividere il file Excel in fogli è accedere a tutti i fogli, scorrere ciascun foglio e salvarlo uno per uno nel formato desiderato. Per il caricamento del foglio di lavoro fornisce lo API[Cartella di lavoro](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) classe.[getWorksheets().getCount()](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#Count) il metodo ottiene il numero totale di fogli. Scorrere ogni foglio e utilizzarlo[getWorksheets().get(sheetindex)](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#get) per accedere alla scheda specifica. Spostare i dati del foglio selezionato nell'oggetto della classe cartella di lavoro appena creato utilizzando[Metodo di copia](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#copy(com.aspose.cells.Workbook)). Infine salvalo nel formato richiesto.

{{% blocks/products/pf/feature-page-code h3="Java Codice per dividere file Excel" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-xls-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="Dividi il foglio di lavoro Excel in riquadri" %}}

API fornisce anche la funzionalità di suddivisione del foglio di lavoro Excel in diversi riquadri. Il processo è caricare il file utilizzando la classe Workbook. Seleziona il primo foglio di lavoro o qualsiasi foglio richiesto fornendo il relativo indice. Chiama setActiveCell con l'indice di cella pertinente come parametro. E infine dividi la finestra del foglio di lavoro in diversi riquadri chiamando il metodo split().

{{% blocks/products/pf/feature-page-code h3="Java Codice per dividere il foglio Excel nel riquadro Visualizza" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-excel-spreadsheet-into-panes.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
