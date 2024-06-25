---
title: Microsoft Conversion de fichiers Excel à l'aide de PHP via Java
description: Aspose.Cells for PHP via Java bibliothèque. Convertissez EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL et d'autres formats avec seulement quelques lignes de code PHP.
keywords: [PHP Aspose.Cells., excel to pdf., json to excel., excel to json., csv to json., json to html., xml to excel and Convert files between various formats in PHP]
---
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header-php-java h1="Microsoft<sup>&reg;</sup> Conversion du format Excel via PHP" h2="Importez et exportez des fichiers Excel aux formats tableur, Web, image et mise en page fixe" >}}

{{% blocks/products/pf/feature-page-summary %}}
La bibliothèque PHP Excel accélère les processus de programmation et de conversion des feuilles de calcul tout en prenant en charge les formats populaires, notamment XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Elle permet également d'exporter des fichiers Excel. au PDF, XPS, HTML, MHTML, Plaine Formats de texte et d’image populaires tels que TIFF, JPG, PNG, BMP et SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Convertir Excel en XLSX, ODS, SXC et FODS à l\'aide de PHP" %}}
 L'interconversion du format de feuille de calcul nécessite uniquement le chargement d'une feuille de calcul avec une instance de[Cahier d'exercices](https://reference.aspose.com/cells/php/aspose.cells/Workbook) et sauvegarder dans le format souhaité tout en sélectionnant la valeur appropriée dans[EnregistrerFormat](https://reference.aspose.com/cells/php/aspose.cells/SaveFormat) énumération.
{{% blocks/products/pf/feature-page-code h3="Code PHP pour la conversion du format de fichier Excel" %}}

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


{{% blocks/products/pf/feature-page-section h2="Convertir Excel en PDF, XPS, HTML et MD à l\'aide de PHP" %}}
 Des cours spécialisés sont disponibles pour contrôler le processus de conversion pour des formats de sortie spécifiques tels que[Options d'enregistrement PDF](https://reference.aspose.com/cells/php/aspose.cells/PdfSaveOptions/)pour exporter des fichiers Excel sous le numéro PDF,[XpsSaveOptions](https://reference.aspose.com/cells/php/aspose.cells/XpsSaveOptions/) pour la conversion Excel en XPS,[HtmlSaveOptions](https://reference.aspose.com/cells/php/aspose.cells/HtmlSaveOptions/) pour afficher Excel sous la forme HTML et[MarkdownSaveOptions](https://reference.aspose.com/cells/php/aspose.cells/MarkdownSaveOptions/) pour la conversion Excel vers Markdown.
{{% blocks/products/pf/feature-page-code h3="Code PHP pour Excel jusqu\'au PDF et formats Web" %}}

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

{{% blocks/products/pf/feature-page-section h2="Convertir JSON en Excel et Excel en JSON en utilisant PHP" %}}
Les développeurs PHP peuvent facilement charger et convertir des fichiers JSON en Excel en quelques lignes de code seulement. De même, les données Excel peuvent être exportées vers les données JSON.
{{% blocks/products/pf/feature-page-code h3="Code PHP pour la conversion JSON en Excel" %}}

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

{{% blocks/products/pf/feature-page-code h3="Code PHP pour la conversion Excel en JSON" %}}

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

{{% blocks/products/pf/feature-page-section h2="Convertir des feuilles de calcul Excel en JPG, BMP, PNG et GIF à l\'aide de PHP" %}}
 Chaque feuille de calcul d'un fichier Excel peut être convertie en différents formats d'image, appelez[OptionsImageOuImpression](https://reference.aspose.com/cells/php/aspose.cells/ImageOrPrintOptions/) .setImageFormat pour définir le format de l'image.
{{% blocks/products/pf/feature-page-code h3="Code PHP pour la conversion d\'Excel en image" %}}

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

{{% blocks/products/pf/feature-page-section h2="Convertir Excel en Word et PowerPoint en utilisant PHP" %}}
Il est possible de charger n'importe quelle feuille de calcul et de la convertir en fichiers Word DOCX et PowerPoint PPTX tout en utilisant[DocxSaveOptions](https://reference.aspose.com/cells/php/aspose.cells/DocxSaveOptions/) & [PptxSaveOptions](https://reference.aspose.com/cells/php/aspose.cells/PptxSaveOptions/) cours comme démontré ci-dessous.
{{% blocks/products/pf/feature-page-code h3="Code PHP pour la conversion Excel vers Word et PowerPoint" %}}
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
