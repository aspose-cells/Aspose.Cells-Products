---
title: Microsoft Převod souborů aplikace Excel pomocí PHP via Java
description: Aspose.Cells for PHP via Java knihovna. Převeďte formáty EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL a další formáty pomocí několika řádků kódu PHP.
keywords: [PHP Aspose.Cells., excel to pdf., json to excel., excel to json., csv to json., json to html., xml to excel and Convert files between various formats in PHP]
---
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header-php-java h1="Microsoft<sup>&reg;</sup> Převod formátu Excel přes PHP" h2="Importujte a exportujte soubory Excel jako tabulkový procesor, web, obrázky a formáty s pevným rozložením" >}}

{{% blocks/products/pf/feature-page-summary %}}
Knihovna PHP Excel urychluje programování tabulek a procesy převodu a zároveň podporuje oblíbené formáty včetně XLS, XLSX, XLSM, XLSB, XLTX, XLTM, 0761637183, 0761637183, 0761676183, Excel soubory na PDF, XPS, HTML, MHTML, Prostý Textové a oblíbené formáty obrázků, jako jsou TIFF, JPG, PNG, BMP a SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Převeďte Excel na XLSX, ODS, SXC a FODS pomocí PHP" %}}
 Vzájemná konverze formátu tabulky vyžaduje pouze načtení tabulky s instancí[pracovní sešit](https://reference.aspose.com/cells/php/aspose.cells/Workbook) a uložení zpět v požadovaném formátu při výběru vhodné hodnoty z[UložitFormát](https://reference.aspose.com/cells/php/aspose.cells/SaveFormat) výčet.
{{% blocks/products/pf/feature-page-code h3="PHP kód pro převod formátu souboru Excel" %}}

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


{{% blocks/products/pf/feature-page-section h2="Převeďte Excel na PDF, XPS, HTML a MD pomocí PHP" %}}
 K dispozici jsou specializované třídy pro řízení procesu převodu pro konkrétní výstupní formáty, jako je např[Možnosti PdfSave](https://reference.aspose.com/cells/php/aspose.cells/PdfSaveOptions/)exportovat soubory Excel jako PDF,[XpsSaveOptions](https://reference.aspose.com/cells/php/aspose.cells/XpsSaveOptions/) pro převod Excel na XPS,[HtmlSaveOptions](https://reference.aspose.com/cells/php/aspose.cells/HtmlSaveOptions/) vykreslit Excel jako HTML a[MarkdownSaveOptions](https://reference.aspose.com/cells/php/aspose.cells/MarkdownSaveOptions/) pro převod Excel na Markdown.
{{% blocks/products/pf/feature-page-code h3="PHP kód pro Excel na PDF a webové formáty" %}}

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

{{% blocks/products/pf/feature-page-section h2="Převést JSON na Excel a Excel na JSON pomocí PHP" %}}
Vývojáři PHP mohou snadno načíst a převést JSON soubory do Excelu v několika řádcích kódu. Podobně lze data aplikace Excel exportovat do dat JSON.
{{% blocks/products/pf/feature-page-code h3="PHP kód pro převod JSON na Excel" %}}

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

{{% blocks/products/pf/feature-page-code h3="Převod PHP kódu pro Excel na JSON" %}}

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

{{% blocks/products/pf/feature-page-section h2="Převod pracovních listů aplikace Excel do formátu JPG, BMP, PNG a GIF pomocí PHP" %}}
 Každý list souboru aplikace Excel lze převést do různých formátů obrázků, volejte[ImageOrPrintOptions](https://reference.aspose.com/cells/php/aspose.cells/ImageOrPrintOptions/) .setImageFormat pro nastavení formátu obrázku.
{{% blocks/products/pf/feature-page-code h3="PHP kód pro převod Excel na obrázek" %}}

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

{{% blocks/products/pf/feature-page-section h2="Převeďte Excel do Wordu a PowerPoint pomocí PHP" %}}
Je možné načíst jakoukoli tabulku a převést ji na soubory Word DOCX a PowerPoint PPTX při používání[DocxSaveOptions](https://reference.aspose.com/cells/php/aspose.cells/DocxSaveOptions/) & [Možnosti PptxSave](https://reference.aspose.com/cells/php/aspose.cells/PptxSaveOptions/) třídy, jak je ukázáno níže.
{{% blocks/products/pf/feature-page-code h3="PHP kód pro Excel do Wordu a převod PowerPoint" %}}
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
