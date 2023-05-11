---
title:  Microsoft Excel-Dateikonvertierung über C#
description: Convert Excel XLS, XLSX, ODS, CSV to PDF, XPS, HTML, JPEG, HTML and many other popular formats with just few lines of C# code.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel-Formatkonvertierung via .NET" h2="Importieren und exportieren Sie Excel-Dateien als Tabellenkalkulations-, Web-, Bild- und feste Layoutformate" >}}

{{% blocks/products/pf/feature-page-summary %}}
.NET Die Excel-Bibliothek beschleunigt die Programmierung und Konvertierung von Tabellenkalkulationen und unterstützt gleichzeitig gängige Formate wie XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, 0761934 81. Es ermöglicht auch den Export von Excel-Dateien nach PDF, XPS, HTML, MHTML, Plain Text- und gängige Bildformate wie TIFF, JPG, PNG, BMP und SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Konvertieren Sie Excel in XLSX, ODS, SXC und FODS" %}}
 Für die gegenseitige Konvertierung des Tabellenformats ist lediglich das Laden einer Tabelle mit einer Instanz von erforderlich[Arbeitsmappe](https://reference.aspose.com/cells/net/aspose.cells/workbook) und Speichern im gewünschten Format zurück, während Sie den entsprechenden Wert aus auswählen[SaveFormat](https://reference.aspose.com/cells/net/aspose.cells/saveformat) Aufzählung.
{{% blocks/products/pf/feature-page-code h3="C# Code für die Konvertierung des Excel-Dateiformats" %}}

```cs
// load the template file
var workbook = new Aspose.Cells.Workbook("template.xls");
// save as XLSX, ODS, SXC & FODS formats
workbook.Save("output.xlsx", Aspose.Cells.SaveFormat.Xlsx);
workbook.Save("output.ods", Aspose.Cells.SaveFormat.Ods);
workbook.Save("output.scx", Aspose.Cells.SaveFormat.Sxc);
workbook.Save("output.fods", Aspose.Cells.SaveFormat.Fods);
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Konvertieren Sie Excel in PDF, XPS, HTML und MD" %}}
 Es stehen spezielle Klassen zur Verfügung, um den Konvertierungsprozess für bestimmte Ausgabeformate zu steuern, z[PDFSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/pdfsaveoptions) um Excel-Dateien als PDF zu exportieren,[XpsSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/xpssaveoptions) für die Konvertierung von Excel in XPS,[HtmlSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/htmlsaveoptions) um Excel als HTML darzustellen und[MarkdownSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/markdownsaveoptions) für die Konvertierung von Excel in Markdown.
{{% blocks/products/pf/feature-page-code h3="C# Code für Excel bis PDF und Webformate" %}}

```cs
// load template Excel file from disc
var book = new Aspose.Cells.Workbook("template.xlsx");
// save Excel in PDF/A-1a format
book.Save("output.pdf", new Aspose.Cells.PdfSaveOptions() { Compliance = PdfComplianceVersion.PdfA1a });
// save Excel in XPS with 1 page per worksheet
book.Save("output.xps", new Aspose.Cells.XpsSaveOptions() { OnePagePerSheet = true });
// save Excel in HTML with images as Base64
book.Save("output.html", new Aspose.Cells.HtmlSaveOptions() { ExportImagesAsBase64 = true });
// save Excel in Markdown (MD) while retaining cell formatting
book.Save("output.md", new Aspose.Cells.MarkdownSaveOptions() { FormatStrategy = Cells.CellValueFormatStrategy.CellStyle });
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="Konvertieren Sie JSON in Excel und Excel in JSON" %}}
 JSON Daten können in eine Instanz von importiert werden[Cells](https://reference.aspose.com/cells/net/aspose.cells/cells) Klasse mit Hilfe von[JsonUtility.ImportData](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/importdata) zur weiteren Verarbeitung oder einfachen Konvertierung in eines der unterstützten Formate. Ähnlich,[Arbeitsblatt](https://reference.aspose.com/cells/net/aspose.cells/worksheet) Daten können als JSON exportiert werden, indem eine erstellt wird[Bereich](https://reference.aspose.com/cells/net/aspose.cells/range) oder Zellen und das Aufrufen der[JsonUtility.ExportRangeToJson](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/exportrangetojson) Methode.
{{% blocks/products/pf/feature-page-code h3="C# Code für die Konvertierung von JSON in Excel" %}}
```cs
// create a Workbook object
var workbook = new Cells.Workbook();
var worksheet = workbook.Worksheets[0];
// read JSON data from file
string jsonInput = File.ReadAllText("Data.json");
// set JsonLayoutOptions to treat Arrays as Table
var options = new Cells.Utility.JsonLayoutOptions();
options.ArrayAsTable = true;
// import JSON data to worksheet starting at cell A1
Cells.Utility.JsonUtility.ImportData(jsonInput, worksheet.Cells, 0, 0, options);
// save resultant file in XLSX format
workbook.Save("output.xlsx", Cells.SaveFormat.Auto); 
```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C#-Code für Excel in JSON-Konvertierung" %}}
```cs
// load XLSX file with an instance of Workbook
var workbook = new Workbook("template.xlsx", new LoadOptions(Cells.LoadFormat.Auto));
// access CellsCollection of the worksheet containing data to be converted
var cells = workbook.Worksheets[0].Cells;
// create & set ExportRangeToJsonOptions for advanced options
var exportOptions = new Utility.ExportRangeToJsonOptions();
// create a range of cells containing data to be exported
var range = cells.CreateRange(0, 0, cells.LastCell.Row + 1, cells.LastCell.Column + 1);
// export range as JSON data
string jsonData = Cells.Utility.JsonUtility.ExportRangeToJson(range, exportOptions);
// write data file to disc in JSON format
System.IO.File.WriteAllText("output.json", jsonData); 
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Konvertieren Sie Excel-Arbeitsblätter in JPG, BMP, PNG und GIF" %}}
 Jedes Arbeitsblatt einer Excel-Datei kann in verschiedene, von der Datei festgelegte Bildformate konvertiert werden[ImageOrPrintOptions.ImageType](https://reference.aspose.com/cells/net/aspose.cells.rendering/imageorprintoptions/properties/imagetype) Eigentum. Der Standardwert ist `ImageFormat.Bmp`.
{{% blocks/products/pf/feature-page-code h3="C# Code für die Konvertierung von Excel in Bilder" %}}
```cs
// load template spreadsheet
var workbook = new Aspose.Cells.Workbook("template.xlsx");
// create & set an instance of ImageOrPrintOptions
var options = new Aspose.Cells.Rendering.ImageOrPrintOptions();
options.OnePagePerSheet = true;
// set output image format
options.ImageType = Aspose.Cells.Drawing.ImageType.Jpeg;
// create SheetRender for first worksheet in the collection
var render = new Aspose.Cells.Rendering.SheetRender(workbook.Worksheets[0], options);
// render worksheet to image
render.ToImage(0, "output.jpg");
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Konvertieren Sie Excel in Word & PowerPoint" %}}
 Es ist möglich, jede Tabellenkalkulation zu laden und sie während der Verwendung in Word-Dateien DOCX und PowerPoint PPTX zu konvertieren[DocxSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/docxsaveoptions) & [PptxSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/pptxsaveoptions) Klassen wie unten gezeigt.
{{% blocks/products/pf/feature-page-code h3="C#-Code für Excel in Word und PowerPoint-Konvertierung" %}}
```cs
// load the template file
var workbook = new Aspose.Cells.Workbook("template.xlsx");
// save spreadsheet as DOCX
workbook.Save("output.docx", new Aspose.Cells.DocxSaveOptions());
// save spreadsheet as PPTX
workbook.Save("output.pptx", new Aspose.Cells.PptxSaveOptions());
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
