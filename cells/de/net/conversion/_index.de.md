---
title: Microsoft Excel-Dateikonvertierung über C# 
url: /de/net/conversion/
description: Konvertieren Sie Excel XLS, XLSX, ODS, CSV in PDF, XPS, HTML, JPEG, HTML und viele andere gängige Formate mit nur wenigen Zeilen C#-Code.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel-Formatkonvertierung über .NET" h2="Importieren und exportieren Sie Excel-Dateien als Tabellenkalkulations-, Web-, Bild- und feste Layoutformate" >}}

{{% blocks/products/pf/feature-page-summary %}}
.NET Die Excel-Bibliothek beschleunigt die Programmierung und Konvertierung von Tabellenkalkulationen und unterstützt gleichzeitig gängige Formate wie XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML und ODS. Es ermöglicht auch den Export von Excel-Dateien in PDF, XPS, HTML, MHTML, Plain Text und gängige Bildformate wie TIFF, JPG, PNG, BMP und SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Konvertieren Sie Excel in XLSX, ODS, SXC und FODS" %}}
Die Konvertierung des Tabellenkalkulationsformats erfordert nur das Laden einer Tabellenkalkulation mit einer Instanz von [Arbeitsmappe](https://reference.aspose.com/cells/net/aspose.cells/workbook) und im gewünschten Format zurückspeichern, während Sie den entsprechenden Wert auswählen [Format speichern](https://reference.aspose.com/cells/net/aspose.cells/saveformat) Aufzählung.
{{% blocks/products/pf/feature-page-code h3="C# Code für die Konvertierung des Excel-Dateiformats" %}}

```cs
// Laden Sie die Vorlagendatei
var workbook = new Aspose.Cells.Workbook("template.xls");
// als XLSX-, ODS-, SXC- und FODS-Formate speichern
workbook.Save("output.xlsx", Aspose.Cells.SaveFormat.Xlsx);
workbook.Save("output.ods", Aspose.Cells.SaveFormat.Ods);
workbook.Save("output.scx", Aspose.Cells.SaveFormat.Sxc);
workbook.Save("output.fods", Aspose.Cells.SaveFormat.Fods);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Konvertieren Sie Excel in PDF, XPS, HTML und MD" %}}
Es sind spezialisierte Klassen verfügbar, um den Konvertierungsprozess für bestimmte Ausgabeformate wie z [PdfSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/pdfsaveoptions) Excel-Dateien als PDF exportieren, [XpsSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/xpssaveoptions) für die Konvertierung von Excel in XPS, [HtmlSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/htmlsaveoptions) um Excel als HTML zu rendern und [MarkdownSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/markdownsaveoptions) für die Excel-zu-Markdown-Konvertierung. 
{{% blocks/products/pf/feature-page-code h3="C# Code für Excel in PDF- und Webformate" %}}

```cs
// Laden Sie die Excel-Vorlagendatei von der Disc
var book = new Aspose.Cells.Workbook("template.xlsx");
// Excel im PDF/A-1a-Format speichern
book.Save("output.pdf", new Aspose.Cells.PdfSaveOptions() { Compliance = PdfComplianceVersion.PdfA1a });
// Speichern Sie Excel in XPS mit 1 Seite pro Arbeitsblatt
book.Save("output.xps", new Aspose.Cells.XpsSaveOptions() { OnePagePerSheet = true });
// Speichern Sie Excel in HTML mit Bildern als Base64
book.Save("output.html", new Aspose.Cells.HtmlSaveOptions() { ExportImagesAsBase64 = true });
// Excel in Markdown (MD) speichern und dabei die Zellformatierung beibehalten
book.Save("output.md", new Aspose.Cells.MarkdownSaveOptions() { FormatStrategy = Cells.CellValueFormatStrategy.CellStyle });

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="Konvertieren Sie JSON in Excel und Excel in JSON" %}}
JSON-Daten können in eine Instanz von importiert werden [Cells](https://reference.aspose.com/cells/net/aspose.cells/cells) Klasse mit Hilfe von [JsonUtility.ImportData](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/importdata) zur Weiterverarbeitung oder einfachen Konvertierung in eines der unterstützten Formate. Ähnlich, [Arbeitsblatt](https://reference.aspose.com/cells/net/aspose.cells/worksheet) Daten können als JSON exportiert werden, indem eine erstellt wird [Bereich](https://reference.aspose.com/cells/net/aspose.cells/range) oder Zellen und Aufruf der [JsonUtility.ExportRangeToJson](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/exportrangetojson) Methode.
{{% blocks/products/pf/feature-page-code h3="C# Code für JSON-zu-Excel-Konvertierung" %}}
```cs
// Erstellen Sie ein Workbook-Objekt
var workbook = new Cells.Workbook();
var worksheet = workbook.Worksheets[0];
// JSON-Daten aus Datei lesen
string jsonInput = File.ReadAllText("Data.json");
// Legen Sie JsonLayoutOptions fest, um Arrays als Tabelle zu behandeln
var options = new Cells.Utility.JsonLayoutOptions();
options.ArrayAsTable = true;
// Importieren Sie JSON-Daten in das Arbeitsblatt, beginnend bei Zelle A1
Cells.Utility.JsonUtility.ImportData(jsonInput, worksheet.Cells, 0, 0, options);
// Speichern Sie die resultierende Datei im XLSX-Format
workbook.Save("output.xlsx", Cells.SaveFormat.Auto); 

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Code für Excel-zu-JSON-Konvertierung" %}}
```cs
// XLSX-Datei mit einer Instanz von Workbook laden
var workbook = new Workbook("template.xlsx", new LoadOptions(Cells.LoadFormat.Auto));
// Greifen Sie auf die CellsCollection des Arbeitsblatts zu, das die zu konvertierenden Daten enthält
var cells = workbook.Worksheets[0].Cells;
// ExportRangeToJsonOptions für erweiterte Optionen erstellen und festlegen
var exportOptions = new Utility.ExportRangeToJsonOptions();
// Erstellen Sie einen Zellbereich mit zu exportierenden Daten
var range = cells.CreateRange(0, 0, cells.LastCell.Row + 1, cells.LastCell.Column + 1);
// Bereich als JSON-Daten exportieren
string jsonData = Cells.Utility.JsonUtility.ExportRangeToJson(range, exportOptions);
// Datendatei im JSON-Format auf Disc schreiben
System.IO.File.WriteAllText("output.json", jsonData); 

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Konvertieren Sie Excel-Arbeitsblätter in JPG, BMP, PNG und GIF" %}}
Jedes Arbeitsblatt einer Excel-Datei kann in verschiedene Bildformate konvertiert werden, die von der eingestellt werden [ImageOrPrintOptions.ImageType](https://reference.aspose.com/cells/net/aspose.cells.rendering/imageorprintoptions/properties/imagetype) Eigentum. Der Standardwert ist `ImageFormat.Bmp`.
{{% blocks/products/pf/feature-page-code h3="C# Code für Excel-zu-Bild-Konvertierung" %}}
```cs
// Vorlagetabelle laden
var workbook = new Aspose.Cells.Workbook("template.xlsx");
// Erstellen und setzen Sie eine Instanz von ImageOrPrintOptions
var options = new Aspose.Cells.Rendering.ImageOrPrintOptions();
options.OnePagePerSheet = true;
// Ausgabebildformat einstellen
options.ImageType = Aspose.Cells.Drawing.ImageType.Jpeg;
// Erstellen Sie SheetRender für das erste Arbeitsblatt in der Sammlung
var render = new Aspose.Cells.Rendering.SheetRender(workbook.Worksheets[0], options);
// Arbeitsblatt in Bild rendern
render.ToImage(0, "output.jpg");

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Konvertieren Sie Excel in Word und PowerPoint" %}}
Es ist möglich, jede Tabelle zu laden und sie während der Verwendung in Word DOCX- und PowerPoint PPTX-Dateien zu konvertieren [DocxSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/docxsaveoptions) & [PptxSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/pptxsaveoptions) Klassen wie unten gezeigt.
{{% blocks/products/pf/feature-page-code h3="C#-Code für die Umwandlung von Excel in Word und PowerPoint" %}}
```cs
// Laden Sie die Vorlagendatei
var workbook = new Aspose.Cells.Workbook("template.xlsx");
// Tabelle als DOCX speichern
workbook.Save("output.docx", new Aspose.Cells.DocxSaveOptions());
// Tabelle als PPTX speichern
workbook.Save("output.pptx", new Aspose.Cells.PptxSaveOptions());

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}