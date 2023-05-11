---
title: Führen Sie in Java verschiedene Excel-Dateien zu einer einzigen zusammen
description: Führen Sie Excel-Dateien mit Java in mehreren Blättern oder einem einzelnen Blatt zusammen. Führen Sie Excel-Dokumente zu PDF, Bildern und HTML zusammen, kombinieren oder verketten Sie sie.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Zusammenführen von Excel-Dateien via Java" h2="Kombinieren Sie zwei oder mehr Excel-Dateien in einer einzigen Tabelle mit dem Code Java" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Excel-Bibliothek](/cells/de/java/) bietet mehrere Möglichkeiten, Arbeitsmappen mit verschiedenen Inhaltstypen wie Formeln, Bildern, Daten, Diagrammen usw. in einem einzigen Tabellenkalkulationsdokument zu kombinieren. Zu den unterstützten Dateiformaten gehören XLS, XLSX, XLSB, XLT, XLTX, XLTM, ODS, CSV, TSV und mehr.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Kombinieren Sie Excel-Dateien mit Bildern und Diagrammen" %}}
 Der einfachste Weg, zwei Excel-Dateien mit Bildern und Diagrammen zu kombinieren, ist der Aufruf von[Arbeitsmappe.kombinieren](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#combine(com.aspose.cells.Workbook)) Methode. Es ermöglicht das Zusammenführen von Excel-Dateien ähnlichen Typs in einer einzigen Tabelle.
{{% blocks/products/pf/feature-page-code h3="Java Code zum Kombinieren von Excel-Dateien" %}}

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

{{% blocks/products/pf/feature-page-section h2="Mehrere Excel-Dateien zusammenführen" %}}
[CellsHelper.mergeFiles](https://reference.aspose.com/cells/java/com.aspose.cells/cellshelper#mergeFiles) Die Methode unterstützt das Zusammenführen von Daten, Stilen und Formeln einer Excel-Datei in einer neuen Tabelle mit demselben Format. Dies ist eine effiziente Möglichkeit, mehrere Dateien zusammenzuführen und gleichzeitig Caching zu verwenden.
{{% blocks/products/pf/feature-page-code h3="Java Code zum Zusammenführen mehrerer Excel-Dateien" %}}

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

{{% blocks/products/pf/feature-page-section h2="Führen Sie Excel-Dateien durch Kopieren von Arbeitsblättern zusammen" %}}
[Arbeitsblatt.kopie](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet#copy(com.aspose.cells.Worksheet)) kann zum Kopieren von Daten und Formatierungen von einem Quellarbeitsblatt in ein anderes Arbeitsblatt innerhalb oder zwischen Arbeitsmappen verwendet werden. Die Methode verwendet das Quellarbeitsblattobjekt als Parameter.
{{% blocks/products/pf/feature-page-code h3="Java Code zum Kopieren von Arbeitsblättern zwischen Arbeitsmappen" %}}

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

{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Zusammenführungsformate" subTitle="Mit Java kann man auch viele andere Dateiformate zusammenführen, darunter." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/csv/" name="CSV" description="Komma-getrennte Werte" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/html/" name="HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/mhtml/" name="MHTML" description="Webseitenarchivformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/ods/" name="ODS" description="OpenDocument-Tabellenkalkulationsdatei" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/tsv/" name="TSV" description="Durch Tabulatoren getrennte Werte" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/txt/" name="TXT" description="Text dokument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xls/" name="XLS" description="Excel-Binärformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsb/" name="XLSB" description="Binäre Excel-Arbeitsmappendatei" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsm/" name="XLSM" description="Tabellenkalkulationsdatei" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsx/" name="XLSX" description="OOXML-Excel-Datei" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlt/" name="XLT" description="Microsoft Excel-Vorlage" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xltm/" name="XLTM" description="Excel-Makro-fähige Vorlage" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}
