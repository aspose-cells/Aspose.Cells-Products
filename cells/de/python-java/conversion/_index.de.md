---
title: Microsoft Excel-Dateikonvertierung über Python 
url: /de/python/conversion/
description: Konvertieren Sie Excel XLS, XLSX, ODS, CSV in PDF, XPS, HTML, JPEG, HTML und viele andere gängige Formate mit nur wenigen Zeilen Python-Code.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel-Formatkonvertierung über Python" h2="Importieren und exportieren Sie Excel-Dateien als Tabellenkalkulations-, Web-, Bild- und feste Layoutformate" >}}

{{% blocks/products/pf/feature-page-summary %}}
Python Die Excel-Bibliothek beschleunigt die Programmierung und Konvertierung von Tabellenkalkulationen und unterstützt gleichzeitig gängige Formate wie XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML und ODS. Es ermöglicht auch den Export von Excel-Dateien in PDF, XPS, HTML, MHTML, Plain Text und gängige Bildformate wie TIFF, JPG, PNG, BMP und SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Konvertieren Sie Excel in XLSX, ODS, SXC und FODS" %}}
Die Konvertierung des Tabellenkalkulationsformats erfordert nur das Laden einer Tabellenkalkulation mit einer Instanz von [Arbeitsmappe](https://reference.aspose.com/cells/python/asposecells.api/Workbook) und im gewünschten Format zurückspeichern, während Sie den entsprechenden Wert auswählen [Format speichern](https://reference.aspose.com/cells/python/asposecells.api/saveformat) Aufzählung.
{{% blocks/products/pf/feature-page-code h3="Python Code für die Konvertierung des Excel-Dateiformats" %}}

```cs
// Laden Sie die Vorlagendatei
workbook = Workbook("Book1.xls")
  
// als XLSX-, ODS-, SXC- und FODS-Formate speichern
workbook.save("output.xlsx", SaveFormat.XLSX);
workbook.save("output.ods", SaveFormat.ODS);
workbook.save("output.scx", SaveFormat.SXC);
workbook.save("output.fods", SaveFormat.FODS);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Konvertieren Sie Excel in PDF, XPS, HTML und MD" %}}
Es sind spezialisierte Klassen verfügbar, um den Konvertierungsprozess für bestimmte Ausgabeformate wie z [PdfSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/PdfSaveOptions) Excel-Dateien als PDF exportieren, [XpsSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/XpsSaveOptions) für die Konvertierung von Excel in XPS, [HtmlSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/HtmlSaveOptions) um Excel als HTML zu rendern und [MarkdownSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/MarkdownSaveOptions) für die Excel-zu-Markdown-Konvertierung. 
{{% blocks/products/pf/feature-page-code h3="Python Code für Excel in PDF- und Webformate" %}}

```cs
// Laden Sie die Excel-Vorlagendatei von der Disc
book = Workbook("template.xlsx")

// Speichern Sie Excel im Format PDF_A_1_B
pdfOptions = PdfSaveOptions()
pdfOptions.setCompliance(PdfCompliance.PDF_A_1_B)
book.save("output.pdf", pdfOptions);

// Speichern Sie Excel in XPS mit 1 Seite pro Arbeitsblatt
xpsOptions = XpsSaveOptions()
xpsOptions.setOnePagePerSheet(True)
book.save("output.xps", xpsOptions);

// Speichern Sie Excel in HTML mit Bildern als Base64
htmlOptions = HtmlSaveOptions()
htmlOptions.setExportImagesAsBase64(True)
book.save("output.html", htmlOptions);

// Excel in Markdown (MD) speichern und dabei die Zellformatierung beibehalten
mdOptions = MarkdownSaveOptions()
mdOptions.setFormatStrategy(CellValueFormatStrategy.CELL_STYLE)
book.save("output.md", mdOptions);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="Konvertieren Sie JSON in Excel und Excel in JSON" %}}
Python-Entwickler können JSON-Dateien in nur wenigen Codezeilen einfach laden und in Excel konvertieren. Ebenso können Excel-Daten in JSON-Daten exportiert werden.
{{% blocks/products/pf/feature-page-code h3="Python Code für JSON-zu-Excel-Konvertierung" %}}
```cs
//Laden Sie Ihre JSON-Quelldatei
workbook = Workbook("Data.json")
//Datei im xlsx-Format speichern
workbook.save("output.xlsx")

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python Code für Excel-zu-JSON-Konvertierung" %}}
```cs
//Laden Sie Ihre xlsx-Quelldatei
workbook = Workbook("input.xlsx")
//Datei im json-Format speichern
workbook.save("Data.json")

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Konvertieren Sie Excel-Arbeitsblätter in JPG, BMP, PNG und GIF" %}}
Jedes Arbeitsblatt einer Excel-Datei kann in verschiedene Bildformate konvertiert werden, aufrufen [ImageOrPrintOptions](https://reference.aspose.com/cells/python/asposecells.api/ImageOrPrintOptions).setImageFormat, um das Bildformat festzulegen. 
{{% blocks/products/pf/feature-page-code h3="Python Code für Excel-zu-Bild-Konvertierung" %}}
```cs
// Vorlagetabelle laden
workbook = Workbook("template.xlsx")
// Erstellen und setzen Sie eine Instanz von ImageOrPrintOptions
options = ImageOrPrintOptions()
// Ausgabebildformat einstellen
options.setImageFormat(ImageFormat.getPng())
// Erstellen Sie SheetRender für das erste Arbeitsblatt in der Sammlung
sheet = workbook.getWorksheets().get(0)
sr = SheetRender(sheet, options)
// Arbeitsblatt in Bild rendern
sr.toImage(0, "output.jpg")

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Konvertieren Sie Excel in Word und PowerPoint" %}}
Es ist möglich, jede Tabelle zu laden und sie während der Verwendung in Word DOCX- und PowerPoint PPTX-Dateien zu konvertieren [DocxSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/DocxSaveOptions) & [PptxSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/PptxSaveOptions) Klassen wie unten gezeigt.
{{% blocks/products/pf/feature-page-code h3="Python-Code für die Umwandlung von Excel in Word und PowerPoint" %}}
```cs
// Laden Sie die Vorlagendatei
workbook = Workbook("template.xlsx")

// Tabelle als DOCX speichern
docxOptions = DocxSaveOptions()
workbook.save("output.docx", docxOptions)

// Tabelle als PPTX speichern
pptxOptions = PptxSaveOptions()
workbook.save("output.pptx", pptxOptions)

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}