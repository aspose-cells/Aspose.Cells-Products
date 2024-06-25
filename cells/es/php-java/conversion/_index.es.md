---
title: Microsoft Conversión de archivos de Excel usando PHP via Java
description: Aspose.Cells for PHP via Java biblioteca. Convierta EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL y más formatos con solo unas pocas líneas de código PHP.
keywords: [PHP Aspose.Cells., excel to pdf., json to excel., excel to json., csv to json., json to html., xml to excel and Convert files between various formats in PHP]
---
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header-php-java h1="Microsoft<sup>&reg;</sup> Conversión de formato Excel mediante PHP" h2="Importe y exporte archivos de Excel como formatos de hoja de cálculo, web, imágenes y diseño fijo" >}}

{{% blocks/products/pf/feature-page-summary %}}
La biblioteca PHP Excel acelera los procesos de conversión y programación de hojas de cálculo y admite formatos populares, incluidos XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. También permite exportar Excel archivos a PDF, XPS, HTML, MHTML, normal Formatos de texto e imágenes populares como TIFF, JPG, PNG, BMP y SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Convierta Excel a XLSX, ODS, SXC y FODS usando PHP" %}}
 La interconversión de formato de hoja de cálculo solo requiere cargar una hoja de cálculo con una instancia de[Libro de trabajo](https://reference.aspose.com/cells/php/aspose.cells/Workbook) y guardarlo nuevamente en el formato deseado mientras selecciona el valor apropiado de[Guardar formato](https://reference.aspose.com/cells/php/aspose.cells/SaveFormat) enumeración.
{{% blocks/products/pf/feature-page-code h3="Código PHP para conversión de formato de archivo de Excel" %}}

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


{{% blocks/products/pf/feature-page-section h2="Convierta Excel a PDF, XPS, HTML y MD usando PHP" %}}
 Hay clases especializadas disponibles para controlar el proceso de conversión para formatos de salida específicos, como[Opciones de guardar PDF](https://reference.aspose.com/cells/php/aspose.cells/PdfSaveOptions/)para exportar archivos de Excel como PDF,[XpsGuardarOpciones](https://reference.aspose.com/cells/php/aspose.cells/XpsSaveOptions/) para conversión de Excel a XPS,[HtmlSaveOptions](https://reference.aspose.com/cells/php/aspose.cells/HtmlSaveOptions/) para representar Excel como HTML y[Opciones de ahorro de rebajas](https://reference.aspose.com/cells/php/aspose.cells/MarkdownSaveOptions/) para la conversión de Excel a Markdown.
{{% blocks/products/pf/feature-page-code h3="Código PHP para Excel a PDF y Formatos Web" %}}

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

{{% blocks/products/pf/feature-page-section h2="Convierta JSON a Excel y Excel a JSON usando PHP" %}}
Los desarrolladores de PHP pueden cargar y convertir fácilmente archivos JSON a Excel en tan solo unas pocas líneas de código. De manera similar, los datos de Excel se pueden exportar a datos JSON.
{{% blocks/products/pf/feature-page-code h3="Código PHP para conversión de JSON a Excel" %}}

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

{{% blocks/products/pf/feature-page-code h3="Código PHP para conversión de Excel a JSON" %}}

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

{{% blocks/products/pf/feature-page-section h2="Convierta hojas de cálculo de Excel a JPG, BMP, PNG y GIF usando PHP" %}}
 Cada hoja de cálculo de un archivo Excel se puede convertir a diferentes formatos de imagen, llame[Opciones de imagen o impresión](https://reference.aspose.com/cells/php/aspose.cells/ImageOrPrintOptions/) .setImageFormat para establecer el formato de la imagen.
{{% blocks/products/pf/feature-page-code h3="Código PHP para conversión de Excel a imagen" %}}

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

{{% blocks/products/pf/feature-page-section h2="Convierta Excel a Word y PowerPoint usando PHP" %}}
Es posible cargar cualquier hoja de cálculo y convertirla a archivos Word DOCX y PowerPoint PPTX mientras se usa[Opciones de DocxSave](https://reference.aspose.com/cells/php/aspose.cells/DocxSaveOptions/) & [PptxGuardarOpciones](https://reference.aspose.com/cells/php/aspose.cells/PptxSaveOptions/) clases como se demuestra a continuación.
{{% blocks/products/pf/feature-page-code h3="Código PHP para conversión de Excel a Word y PowerPoint" %}}
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
