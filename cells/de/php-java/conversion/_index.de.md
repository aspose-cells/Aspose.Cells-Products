---
title: Microsoft Excel-Dateikonvertierung mit PHP via Java
description: Aspose.Cells for PHP via Java Bibliothek. Konvertieren Sie EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL und weitere Formate mit nur wenigen Zeilen PHP-Code.
keywords: [PHP Aspose.Cells., excel to pdf., json to excel., excel to json., csv to json., json to html., xml to excel and Convert files between various formats in PHP]
---
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header-php-java h1="Microsoft<sup>&reg;</sup> Excel-Formatkonvertierung über PHP" h2="Importieren und exportieren Sie Excel-Dateien als Tabellenkalkulations-, Web-, Bild- und Festlayoutformate." >}}

{{% blocks/products/pf/feature-page-summary %}}
Die PHP Excel Library beschleunigt die Tabellenkalkulationsprogrammierung und Konvertierungsprozesse und unterstützt gängige Formate, darunter XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Sie ermöglicht auch den Export von Excel-Dateien in die Formate PDF, XPS, HTML, MHTML, Nur-Text und gängige Bildformate wie TIFF, JPG, PNG, BMP und SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Konvertieren Sie Excel mit PHP in XLSX, ODS, SXC und FODS" %}}
 Die Konvertierung des Tabellenformats erfordert lediglich das Laden einer Tabelle mit einer Instanz von[Arbeitsmappe](https://reference.aspose.com/cells/php/aspose.cells/Workbook) und speichern Sie es im gewünschten Format zurück, während Sie den entsprechenden Wert auswählen aus[Format speichern](https://reference.aspose.com/cells/php/aspose.cells/SaveFormat) Aufzählung.
{{% blocks/products/pf/feature-page-code h3="PHP-Code zur Konvertierung des Excel-Dateiformats" %}}

```php
require_once("Java.inc"); 
require_once("lib/aspose.cells.php"); 
use aspose\cells;
use aspose\cells\Workbook; 

// load the template file
$workbook = new Workbook("input.xlsx");

// save as XLSX, ODS, SXC & FODS formats
$workbook->save("output.xlsx", SaveFormat::Xlsx);
$workbook->save("output.ods", SaveFormat::Ods);
$workbook->save("output.scx", SaveFormat::Sxc);
$workbook->save("output.fods", SaveFormat::Fods);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Konvertieren Sie Excel mit PHP in PDF, XPS, HTML und MD" %}}
 Es stehen spezielle Klassen zur Verfügung, um den Konvertierungsprozess für bestimmte Ausgabeformate zu steuern, wie beispielsweise[PdfSpeichernOptionen](https://reference.aspose.com/cells/php/aspose.cells/PdfSaveOptions/)um Excel-Dateien als PDF zu exportieren,[XpsSaveOptions](https://reference.aspose.com/cells/php/aspose.cells/XpsSaveOptions/) für die Konvertierung von Excel nach XPS,[HtmlSaveOptions](https://reference.aspose.com/cells/php/aspose.cells/HtmlSaveOptions/) Excel als HTML darzustellen und[MarkdownSpeichernOptionen](https://reference.aspose.com/cells/php/aspose.cells/MarkdownSaveOptions/) für die Konvertierung von Excel in Markdown.
{{% blocks/products/pf/feature-page-code h3="PHP-Code für Excel bis PDF und Webformate" %}}

```php
require_once("Java.inc"); 
require_once("lib/aspose.cells.php"); 
use aspose\cells;
use aspose\cells\Workbook; 

// load the template file
$workbook = new Workbook("input.xlsx");


// save Excel in PDF_A_1_B format
$pdfOptions = new PdfSaveOptions();
$pdfOptions->setCompliance(PdfCompliance::PDF_A_1_B);
$workbook->save("output.pdf", pdfOptions);

// save Excel in XPS with 1 page per worksheet
$xpsOptions = new XpsSaveOptions();
$xpsOptions->setOnePagePerSheet(true);
$workbook->save("output.xps", xpsOptions);

// save Excel in HTML with images as Base64
$htmlOptions = new HtmlSaveOptions();
$htmlOptions->setExportImagesAsBase64(true);
$workbook->save("output.html", htmlOptions);

// save Excel in Markdown (MD) while retaining cell formatting
$mdOptions = new MarkdownSaveOptions();
$mdOptions->setFormatStrategy(CellValueFormatStrategy::CELL_STYLE);
$workbook->save("output.md", mdOptions);
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="Konvertieren Sie JSON in Excel und Excel in JSON mit PHP" %}}
PHP-Entwickler können JSON-Dateien mit nur wenigen Codezeilen problemlos in Excel laden und konvertieren. Ebenso können Excel-Daten in JSON-Daten exportiert werden.
{{% blocks/products/pf/feature-page-code h3="PHP-Code für die Konvertierung von JSON in Excel" %}}

```php
require_once("Java.inc"); 
require_once("lib/aspose.cells.php"); 
use aspose\cells;
use aspose\cells\Workbook; 

// Load your source json file
$workbook = new Workbook("Data.json");

//save file to xlsx format
$workbook->save("output.xlsx");
```

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="PHP-Code für die Konvertierung von Excel in JSON" %}}

```php
require_once("Java.inc"); 
require_once("lib/aspose.cells.php"); 
use aspose\cells;
use aspose\cells\Workbook; 

// Load your source xlsx file
$workbook = new Workbook("input.xlsx");

// save file to json format
$workbook->save("Data.json");
```

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Konvertieren Sie Excel-Arbeitsblätter mit PHP in JPG, BMP, PNG und GIF" %}}
 Jedes Arbeitsblatt einer Excel-Datei kann in verschiedene Bildformate konvertiert werden, rufen Sie[Bild-oder-Druckoptionen](https://reference.aspose.com/cells/php/aspose.cells/ImageOrPrintOptions/) .setImageFormat zum Festlegen des Bildformats.
{{% blocks/products/pf/feature-page-code h3="PHP-Code zur Konvertierung von Excel in Bilder" %}}

```php
require_once("Java.inc"); 
require_once("lib/aspose.cells.php"); 
use aspose\cells;
use aspose\cells\Workbook; 

// load template spreadsheet
$workbook = new Workbook("template.xlsx");

// create & set an instance of ImageOrPrintOptions
$options = new ImageOrPrintOptions();
// set output image type
$options->setImageType(ImageType::PNG);
// create SheetRender for first worksheet in the collection
$sheet = $workbook->getWorksheets()->get(0);
$sr = new SheetRender(sheet, options);
// render worksheet to image
$sr->toImage(0, "output.jpg")
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Konvertieren Sie Excel in Word und PowerPoint mit PHP" %}}
Es ist möglich, jede Tabelle zu laden und sie in Word DOCX & PowerPoint PPTX Dateien zu konvertieren, während[DocxSaveOptions](https://reference.aspose.com/cells/php/aspose.cells/DocxSaveOptions/) & [PptxSpeichernOptionen](https://reference.aspose.com/cells/php/aspose.cells/PptxSaveOptions/) Klassen, wie unten gezeigt.
{{% blocks/products/pf/feature-page-code h3="PHP-Code für die Konvertierung von Excel in Word und PowerPoint" %}}
```php
require_once("Java.inc"); 
require_once("lib/aspose.cells.php"); 
use aspose\cells;
use aspose\cells\Workbook; 

// load template spreadsheet
$workbook = new Workbook("template.xlsx");

// save spreadsheet as DOCX
$docxOptions = new DocxSaveOptions();
$workbook->save("output.docx", docxOptions);

// save spreadsheet as PPTX
$pptxOptions = new PptxSaveOptions();
$workbook->save("output.pptx", pptxOptions)
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xls-to-docx xlsx-to-docx xlsb-to-docx xlsm-to-docx html-to-docx mhtml-to-docx ods-to-docx tsv-to-docx csv-to-docx json-to-docx numbers-to-docx prn-to-docx xlt-to-docx xltx-to-docx xltm-to-docx ots-to-docx sxc-to-docx png-to-docx jpg-to-docx txt-to-docx xls-to-pptx xlsx-to-pptx xlsb-to-pptx xlsm-to-pptx html-to-pptx mhtml-to-pptx ods-to-pptx tsv-to-pptx csv-to-pptx json-to-pptx numbers-to-pptx prn-to-pptx xlt-to-pptx xltx-to-pptx xltm-to-pptx ots-to-pptx sxc-to-pptx png-to-pptx jpg-to-pptx txt-to-pptx" >}}
