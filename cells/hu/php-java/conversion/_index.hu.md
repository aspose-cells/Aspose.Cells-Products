---
title: Microsoft Excel-fájl konvertálása PHP via Java használatával
description: Aspose.Cells for PHP via Java könyvtár. Konvertálja az EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL és további formátumokat néhány soros PHP kóddal.
keywords: [PHP Aspose.Cells., excel to pdf., json to excel., excel to json., csv to json., json to html., xml to excel and Convert files between various formats in PHP]
---
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header-php-java h1="Microsoft<sup>&reg;</sup> Excel formátum konvertálása PHP-n keresztül" h2="Excel-fájlok importálása és exportálása táblázat-, web-, kép- és rögzített elrendezésű formátumokba" >}}

{{% blocks/products/pf/feature-page-summary %}}
PHP Excel Library felgyorsítja a táblázatkezelési és átalakítási folyamatokat, miközben támogatja a népszerű formátumokat, köztük a XLS, XLSX, XLSB, XLTX, XLTM, XLTM, 07616481, 716481, 716481 lehetővé teszi az Excel fájlok exportálását is a következő címekre: PDF, XPS, HTML, MHTML, sima Szöveg- és népszerű képformátumok, például TIFF, JPG, PNG, BMP és SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Az Excel konvertálása XLSX, ODS, SXC és FODS-re PHP használatával" %}}
 A táblázatos formátumok közötti konvertáláshoz csak egy példányt tartalmazó táblázatot kell betölteni[Munkafüzet](https://reference.aspose.com/cells/php/aspose.cells/Workbook) és visszamenti a kívánt formátumba, miközben kiválasztja a megfelelő értéket[SaveFormat](https://reference.aspose.com/cells/php/aspose.cells/SaveFormat) felsorolás.
{{% blocks/products/pf/feature-page-code h3="PHP kód az Excel fájlformátum konvertálásához" %}}

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


{{% blocks/products/pf/feature-page-section h2="Az Excel konvertálása PDF, XPS, HTML és MD-re PHP használatával" %}}
 Speciális osztályok állnak rendelkezésre az átalakítási folyamat vezérlésére meghatározott kimeneti formátumokhoz, mint pl[PdfSaveOptions](https://reference.aspose.com/cells/php/aspose.cells/PdfSaveOptions/)Excel-fájlok exportálásához PDF-es számként,[XpsSaveOptions](https://reference.aspose.com/cells/php/aspose.cells/XpsSaveOptions/) az Excelből XPS-re való átalakításhoz,[HtmlSaveOptions](https://reference.aspose.com/cells/php/aspose.cells/HtmlSaveOptions/) hogy az Excel HTML-ként jelenjen meg, és[MarkdownSaveOptions](https://reference.aspose.com/cells/php/aspose.cells/MarkdownSaveOptions/) az Excelből Markdown konvertáláshoz.
{{% blocks/products/pf/feature-page-code h3="PHP-kód Excelhez PDF-ig és webes formátumokhoz" %}}

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

{{% blocks/products/pf/feature-page-section h2="Konvertálja a JSON-et Excel-re és az Excel-t JSON-re PHP segítségével" %}}
A PHP-fejlesztők egyszerűen betölthetik és néhány sornyi kóddal Excelbe konvertálhatják a JSON fájlokat. Hasonlóképpen, az Excel-adatok exportálhatók a JSON-es adatokba.
{{% blocks/products/pf/feature-page-code h3="PHP kód a JSON Excel konvertálásához" %}}

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

{{% blocks/products/pf/feature-page-code h3="PHP-kód az Excelhez JSON átalakítás" %}}

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

{{% blocks/products/pf/feature-page-section h2="Excel-munkalapok konvertálása JPG, BMP, PNG és GIF formátumba PHP segítségével" %}}
 Egy Excel-fájl minden munkalapja konvertálható különböző képformátumokba, hívja[ImageOrPrintOptions](https://reference.aspose.com/cells/php/aspose.cells/ImageOrPrintOptions/) .setImageFormat a képformátum beállításához.
{{% blocks/products/pf/feature-page-code h3="PHP kód az Excel-kép konvertáláshoz" %}}

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

{{% blocks/products/pf/feature-page-section h2="Konvertálja az Excelt Word-be és PowerPoint-be PHP használatával" %}}
Lehetőség van bármilyen táblázat betöltésére és Word DOCX és PowerPoint PPTX fájlokká konvertálására használat közben.[DocxSaveOptions](https://reference.aspose.com/cells/php/aspose.cells/DocxSaveOptions/) & [PptxSaveOptions](https://reference.aspose.com/cells/php/aspose.cells/PptxSaveOptions/) osztályok alább látható módon.
{{% blocks/products/pf/feature-page-code h3="PHP kód az Excel Wordbe és a PowerPoint konvertáláshoz" %}}
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
