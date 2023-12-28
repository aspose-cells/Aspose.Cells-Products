---
title: Unisci diversi file Excel in uno unico in Java
description: Unisci file Excel utilizzando Java in più fogli o foglio singolo. Unisci, combina o concatena documenti Excel anche a PDF, Immagini e HTML.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Unione file Excel via Java" h2="Combina due o più file Excel in un unico foglio di calcolo utilizzando il codice Java" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Libreria Excel](/cells/it/java/)fornisce diversi modi per combinare cartelle di lavoro con vari tipi di contenuti come formule, immagini, dati, grafici ecc. in un unico foglio di calcolo. I formati di file supportati includono XLS, XLSX, XLSB, XLT, XLTX, XLTM, ODS, CSV, TSV e altri.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Combina file Excel con immagini e grafici" %}}
 Il modo più semplice per combinare due file Excel con immagini e grafici è chiamare il file[Cartella di lavoro.combine](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#combine(com.aspose.cells.Workbook)) metodo. Permette di unire file Excel di tipo simile in un unico foglio di calcolo.
{{% blocks/products/pf/feature-page-code h3="Java Codice per unire file Excel" %}}

```cs
// load first Excel file
var book1 = new Workbook("with-charts.xlsx");
// load second Excel file into a separate instance
var book2 = new Workbook("with-images.xlsx");

// merge two workbooks
book1.combine(book2);
// save the target workbook 
book1.save("combined.xlsx");
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Unisci più file Excel" %}}
[CellsHelper.mergeFiles](https://reference.aspose.com/cells/java/com.aspose.cells/cellshelper#mergeFiles) Il metodo supporta l'unione di dati, stile e formule di un file Excel in un nuovo foglio di calcolo dello stesso formato. È un modo efficace per unire più file durante l'utilizzo della memorizzazione nella cache.
{{% blocks/products/pf/feature-page-code h3="Java Codice per unire più file Excel" %}}

```cs
// create an Array (length=2)
String[] files = new String[2];
// specify file paths to be merged
files[0] = "Book1.xls";
files[1] = "Book2.xls";
// merge the files to save the result
CellsHelper.mergeFiles(files, "cache", "merged.xls");

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Unisci file Excel copiando fogli di lavoro" %}}
[Foglio di lavoro.copia](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet#copy(com.aspose.cells.Worksheet)può essere utilizzato per copiare dati e formattazione da un foglio di lavoro di origine a un altro foglio di lavoro all'interno o tra cartelle di lavoro. Il metodo accetta l'oggetto del foglio di lavoro di origine come parametro.
{{% blocks/products/pf/feature-page-code h3="Java Codice per copiare fogli di lavoro tra cartelle di lavoro" %}}

```cs
// Create a Workbook.
Workbook excelWorkbook0 = new Workbook(dataDir + "book1.xls");

// Create another Workbook.
Workbook excelWorkbook1 = new Workbook();

// Copy the first sheet of the first book into second book.
excelWorkbook1.getWorksheets().get(0).copy(excelWorkbook0.getWorksheets().get(0));

// Save the file.
excelWorkbook1.save(dataDir + "out.xls", FileFormatType.EXCEL_97_TO_2003);
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/other-supported-section title="Altri formati di unione supportati" subTitle="Utilizzando Java, è possibile anche unire molti altri formati di file, inclusi..." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/csv/" name="CSV" description="valori separati da virgola" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/html/" name="HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/mhtml/" name="MHTML" description="Formato di archivio delle pagine Web" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/ods/" name="ODS" description="File di foglio di calcolo OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/tsv/" name="TSV" description="Valori separati da tabulazioni" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/txt/" name="TXT" description="Documento di testo" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xls/" name="XLS" description="Formato binario Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsb/" name="XLSB" description="File binario della cartella di lavoro Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsm/" name="XLSM" description="File di foglio di calcolo" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsx/" name="XLSX" description="File Excel OOXML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlt/" name="XLT" description="Microsoft Modello Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xltm/" name="XLTM" description="Modello con attivazione macro di Excel" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}
