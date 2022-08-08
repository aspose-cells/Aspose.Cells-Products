---
title: Führen Sie verschiedene Excel-Dateien in Java zu einer einzigen zusammen
url: /de/java/merger/
description: Führen Sie Excel-Dateien mit Java in mehrere Blätter oder ein einzelnes Blatt zusammen. Zusammenführen, Kombinieren oder Verketten von Excel-Dokumenten zu PDF, Bildern und HTML.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Zusammenführen von Microsoft<sup>&reg;</sup> Excel-Dateien über Java" h2="Kombinieren Sie zwei oder mehr Excel-Dateien in einer einzigen Tabelle mit Java-Code" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Excel-Bibliothek](/cells/java/) bietet mehrere Möglichkeiten, Arbeitsmappen mit verschiedenen Arten von Inhalten wie Formeln, Bildern, Daten, Diagrammen usw. in einem einzigen Tabellenkalkulationsdokument zu kombinieren. Zu den unterstützten Dateiformaten gehören XLS, XLSX, XLSB, XLT, XLTX, XLTM, ODS, CSV, TSV und mehr.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Kombinieren Sie Excel-Dateien mit Bildern und Diagrammen" %}}
Der einfachste Weg, zwei Excel-Dateien mit Bildern und Diagrammen zu kombinieren, ist der Aufruf der [Arbeitsbuch.combine](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#combine(com.aspose.cells.Workbook)) Methode. Es ermöglicht das Zusammenführen von Excel-Dateien ähnlichen Typs in einer einzigen Tabelle.
{{% blocks/products/pf/feature-page-code h3="Java Code zum Kombinieren von Excel-Dateien" %}}

```cs
// Laden Sie die erste Excel-Datei
var book1 = new Workbook("with-charts.xlsx");
// Laden Sie die zweite Excel-Datei in eine separate Instanz
var book2 = new Workbook("with-images.xlsx");

// zwei Arbeitsmappen zusammenführen
book1.combine(book2);
// Speichern Sie die Zielarbeitsmappe 
book1.save("combined.xlsx");

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Mehrere Excel-Dateien zusammenführen" %}}
[CellsHelper.mergeFiles](https://reference.aspose.com/cells/java/com.aspose.cells/cellshelper#mergeFiles) -Methode unterstützt das Zusammenführen von Daten, Stil und Formeln einer Excel-Datei mit einer neuen Tabelle im gleichen Format. Es ist eine effiziente Möglichkeit, mehrere Dateien zusammenzuführen, während Caching verwendet wird. 
{{% blocks/products/pf/feature-page-code h3="Java Code zum Zusammenführen mehrerer Excel-Dateien" %}}

```cs
// Erstellen Sie ein Array (Länge = 2)
String[] files = new String[2];
// Geben Sie Dateipfade an, die zusammengeführt werden sollen
files[0] = "Book1.xls";
files[1] = "Book2.xls";
// führen Sie die Dateien zusammen, um das Ergebnis zu speichern
CellsHelper.mergeFiles(files, "cache", "merged.xls");


```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Excel-Dateien durch Kopieren von Arbeitsblättern zusammenführen" %}}
[Arbeitsblatt.kopieren](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet#copy(com.aspose.cells.Worksheet)kann verwendet werden, um Daten und Formatierungen von einem Quellarbeitsblatt in ein anderes Arbeitsblatt innerhalb oder zwischen Arbeitsmappen zu kopieren. Die Methode nimmt das Quellarbeitsblattobjekt als Parameter.
{{% blocks/products/pf/feature-page-code h3="Java Code zum Kopieren von Arbeitsblättern zwischen Arbeitsmappen" %}}

```cs
// Erstellen Sie eine Arbeitsmappe.
Workbook excelWorkbook0 = new Workbook(dataDir + "book1.xls");

// Erstellen Sie eine weitere Arbeitsmappe.
Workbook excelWorkbook1 = new Workbook();

// Kopieren Sie das erste Blatt des ersten Buches in das zweite Buch.
excelWorkbook1.getWorksheets().get(0).copy(excelWorkbook0.getWorksheets().get(0));

// Speicher die Datei.
excelWorkbook1.save(dataDir + "out.xls", FileFormatType.EXCEL_97_TO_2003);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Merger" >}}