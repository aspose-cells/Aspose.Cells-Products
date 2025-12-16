---
title: Microsoft Excel-Dateikonvertierung mit Node.js über C++
description: Aspose.Cells for Node.js via C++ library. Convert EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL and more formats with only few lines of Node.js via C++ code.
keywords: [Node.js via C++ Aspose.Cells., excel to pdf., json to excel., excel to json., csv to json., json to html., xml to excel and Convert files between various formats in Node.js via C++]
---
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel-Formatkonvertierung via Node.js via C++" h2="Importieren und exportieren Sie Excel-Dateien als Tabellenkalkulations-, Web-, Bild- und Festlayoutformate." >}}

{{% blocks/products/pf/feature-page-summary %}}
Node.js beschleunigt mit der Excel-Bibliothek C++ die Tabellenkalkulations-Programmierung und Konvertierungsprozesse und unterstützt gängige Formate wie XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML und ODS. Zudem ermöglicht sie den Export von Excel-Dateien in die Formate PDF, XPS, HTML, MHTML, Klartext sowie in gängige Bildformate wie TIFF, JPG, PNG, BMP und SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel-Konvertierung in XLSX, ODS, SXC & FODS mit Node.js über C++" %}}
 Die Konvertierung des Tabellenformats erfordert lediglich das Laden einer Tabelle mit einer Instanz von[Arbeitsmappe](https://reference.aspose.com/cells/nodejs-cpp/workbook/) und speichern Sie es im gewünschten Format zurück, während Sie den entsprechenden Wert auswählen aus[Format speichern](https://reference.aspose.com/cells/nodejs-cpp/saveformat/) Aufzählung.
{{% blocks/products/pf/feature-page-code h3="Node.js-Code (C++) zur Konvertierung des Excel-Dateiformats" %}}

```js
const AsposeCells = require("aspose.cells.node");

// load the template file
var workbook = new AsposeCells.Workbook("input.xlsx");

// save as XLSX, ODS, SXC & FODS formats
workbook.save("output.xlsx", AsposeCells.SaveFormat.Xlsx);
workbook.save("output.ods", AsposeCells.SaveFormat.Ods);
workbook.save("output.sxc", AsposeCells.SaveFormat.Sxc);
workbook.save("output.fods", AsposeCells.SaveFormat.Fods);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Excel-Konvertierung in PDF, XPS, HTML & MD mit Node.js über C++" %}}
 Es stehen spezielle Klassen zur Verfügung, um den Konvertierungsprozess für bestimmte Ausgabeformate zu steuern, wie beispielsweise[PdfSpeichernOptionen](https://reference.aspose.com/cells/nodejs-cpp/pdfsaveoptions/)um Excel-Dateien als PDF zu exportieren,[XP-Speicheroptionen](https://reference.aspose.com/cells/nodejs-cpp/xpssaveoptions/) für die Konvertierung von Excel nach XPS,[HTML-Speicheroptionen](https://reference.aspose.com/cells/nodejs-cpp/htmlsaveoptions/) Excel als HTML darzustellen und[MarkdownSpeichernOptionen](https://reference.aspose.com/cells/nodejs-cpp/markdownsaveoptions/) für die Konvertierung von Excel in Markdown.
{{% blocks/products/pf/feature-page-code h3="Node.js-Code für Excel (C++) und Webformate (PDF)" %}}

```js
const AsposeCells = require("aspose.cells.node");

// load the template file
var workbook = new AsposeCells.Workbook("input.xlsx");

// save Excel in PDF_A_1_B format
var pdfOptions = new AsposeCells.PdfSaveOptions();
pdfOptions.setCompliance(AsposeCells.PdfCompliance.PdfA1b);
workbook.save("output.pdf", pdfOptions);

// save Excel in XPS with 1 page per worksheet
var xpsOptions = new AsposeCells.XpsSaveOptions();
xpsOptions.setOnePagePerSheet(true);
workbook.save("output.xps", xpsOptions);

// save Excel in HTML with images as Base64
var htmlOptions = new AsposeCells.HtmlSaveOptions();
htmlOptions.setExportImagesAsBase64(true);
workbook.save("output.html", htmlOptions);

// save Excel in Markdown (MD) while retaining cell formatting
var mdOptions = new AsposeCells.MarkdownSaveOptions();
mdOptions.setFormatStrategy(AsposeCells.CellValueFormatStrategy.CellStyle);
workbook.save("output.md", mdOptions);
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="JSON in Excel und Excel in JSON konvertieren mit Node.js über C++" %}}
Node.js-Entwickler können JSON-Dateien mit nur wenigen Codezeilen problemlos in Excel laden und konvertieren. Umgekehrt lassen sich Excel-Daten auch in das Format JSON exportieren.
{{% blocks/products/pf/feature-page-code h3="Node.js-Code für die Konvertierung von C++ in Excel (JSON)" %}}

```js
const AsposeCells = require("aspose.cells.node");

// Load your source json file
var workbook = new AsposeCells.Workbook("Data.json");

//save file to xlsx format
workbook.save("output.xlsx");

```

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Node.js-Code für Excel (C++) zur Konvertierung in JSON" %}}

```js
const AsposeCells = require("aspose.cells.node");

// Load your source xlsx file
var workbook = new AsposeCells.Workbook("input.xlsx");

// save file to json format
workbook.save("Data.json");
```

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Excel-Arbeitsblätter mit Node.js in JPG konvertieren (BMP, PNG & GIF)" %}}
 Jedes Arbeitsblatt einer Excel-Datei kann in verschiedene Bildformate konvertiert werden, rufen Sie[Bild-oder-Druckoptionen](https://reference.aspose.com/cells/nodejs-cpp/imageorprintoptions/) .setImageFormat zum Festlegen des Bildformats.
{{% blocks/products/pf/feature-page-code h3="Node.js-Code (C++) zur Excel-zu-Bild-Konvertierung" %}}

```js
const AsposeCells = require("aspose.cells.node");

// load template spreadsheet
var workbook = new AsposeCells.Workbook("template.xlsx");

// create & set an instance of ImageOrPrintOptions
var options = new AsposeCells.ImageOrPrintOptions();
// set output image type
options.setImageType(AsposeCells.ImageType.Png);
// create SheetRender for first worksheet in the collection
var sheet = workbook.getWorksheets().get(0);
var sr = new AsposeCells.SheetRender(sheet, options);
// render worksheet to image
sr.toImage(0, "output.jpg");
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Excel in Word konvertieren & PowerPoint mit Node.js über C++" %}}
Es ist möglich, jede Tabelle zu laden und sie in Word DOCX & PowerPoint PPTX Dateien zu konvertieren, während[DocxSaveOptions](https://reference.aspose.com/cells/nodejs-cpp/docxsaveoptions/) & [PptxSpeichernOptionen](https://reference.aspose.com/cells/nodejs-cpp/pptxsaveoptions/) Klassen, wie unten gezeigt.
{{% blocks/products/pf/feature-page-code h3="PHP-Code für die Konvertierung von Excel in Word und PowerPoint" %}}
```js
const AsposeCells = require("aspose.cells.node");

// load template spreadsheet
var workbook = new AsposeCells.Workbook("template.xlsx");

// save spreadsheet as DOCX
var docxOptions = new AsposeCells.DocxSaveOptions();
workbook.save("output.docx", docxOptions);

// save spreadsheet as PPTX
var pptxOptions = new AsposeCells.PptxSaveOptions();
workbook.save("output.pptx", pptxOptions)
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xls-to-docx xlsx-to-docx xlsb-to-docx xlsm-to-docx html-to-docx mhtml-to-docx ods-to-docx tsv-to-docx csv-to-docx json-to-docx numbers-to-docx prn-to-docx xlt-to-docx xltx-to-docx xltm-to-docx ots-to-docx sxc-to-docx png-to-docx jpg-to-docx txt-to-docx xls-to-pptx xlsx-to-pptx xlsb-to-pptx xlsm-to-pptx html-to-pptx mhtml-to-pptx ods-to-pptx tsv-to-pptx csv-to-pptx json-to-pptx numbers-to-pptx prn-to-pptx xlt-to-pptx xltx-to-pptx xltm-to-pptx ots-to-pptx sxc-to-pptx png-to-pptx jpg-to-pptx txt-to-pptx" >}}
