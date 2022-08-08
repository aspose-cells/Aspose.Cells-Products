---
title: Unisci diversi file Excel in uno solo in Java
url: /it/java/merger/
description: Unisci i file Excel utilizzando Java in più fogli o in un unico foglio. Unisci, combina o concatena documenti Excel anche in PDF, immagini e HTML.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Unione di file Microsoft<sup>&reg;</sup> Excel tramite Java" h2="Combina due o più file Excel in un unico foglio di lavoro utilizzando il codice Java" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Libreria di Excel](/cells/java/) fornisce diversi modi per combinare cartelle di lavoro con vari tipi di contenuto come formule, immagini, dati, grafici, ecc. in un unico foglio di calcolo. I formati di file supportati includono XLS, XLSX, XLSB, XLT, XLTX, XLTM, ODS, CSV, TSV e altri.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Combina file Excel con immagini e grafici" %}}
Il modo più semplice per combinare due file Excel con immagini e grafici è chiamare il file [Cartella di lavoro.combina](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#combine(com.aspose.cells.Workbook)) metodo. Consente di unire file Excel di tipo simile in un unico foglio di calcolo.
{{% blocks/products/pf/feature-page-code h3="Java Codice per combinare file Excel" %}}

```cs
// carica il primo file Excel
var book1 = new Workbook("with-charts.xlsx");
// carica il secondo file Excel in un'istanza separata
var book2 = new Workbook("with-images.xlsx");

// unire due cartelle di lavoro
book1.combine(book2);
// salvare la cartella di lavoro di destinazione 
book1.save("combined.xlsx");

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Unisci più file Excel" %}}
[CellsHelper.mergeFiles](https://reference.aspose.com/cells/java/com.aspose.cells/cellshelper#mergeFiles) il metodo supporta l'unione di dati, stile e formule di un file Excel in un nuovo foglio di calcolo dello stesso formato. È un modo efficiente per unire più file durante l'utilizzo della memorizzazione nella cache. 
{{% blocks/products/pf/feature-page-code h3="Java Codice per unire più file Excel" %}}

```cs
// crea un array (lunghezza=2)
String[] files = new String[2];
// specificare i percorsi dei file da unire
files[0] = "Book1.xls";
files[1] = "Book2.xls";
// unisci i file per salvare il risultato
CellsHelper.mergeFiles(files, "cache", "merged.xls");


```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Unisci file Excel copiando fogli di lavoro" %}}
[Foglio di lavoro.copia](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet#copy(com.aspose.cells.Worksheet)può essere utilizzato per copiare dati e formattazione da un foglio di lavoro di origine a un altro foglio di lavoro all'interno o tra cartelle di lavoro. Il metodo accetta l'oggetto del foglio di lavoro di origine come parametro.
{{% blocks/products/pf/feature-page-code h3="Java Codice per copiare fogli di lavoro tra cartelle di lavoro" %}}

```cs
// Crea una cartella di lavoro.
Workbook excelWorkbook0 = new Workbook(dataDir + "book1.xls");

// Crea un'altra cartella di lavoro.
Workbook excelWorkbook1 = new Workbook();

// Copia il primo foglio del primo libro nel secondo libro.
excelWorkbook1.getWorksheets().get(0).copy(excelWorkbook0.getWorksheets().get(0));

// Salva il file.
excelWorkbook1.save(dataDir + "out.xls", FileFormatType.EXCEL_97_TO_2003);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Merger" >}}