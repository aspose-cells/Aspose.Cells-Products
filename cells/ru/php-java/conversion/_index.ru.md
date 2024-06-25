---
title: Microsoft Преобразование файлов Excel с помощью PHP via Java
description: Aspose.Cells for PHP via Java библиотека. Конвертируйте форматы EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL и другие с помощью всего лишь нескольких строк PHP-кода.
keywords: [PHP Aspose.Cells., excel to pdf., json to excel., excel to json., csv to json., json to html., xml to excel and Convert files between various formats in PHP]
---
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header-php-java h1="Microsoft<sup>&reg;</sup> Преобразование формата Excel с помощью PHP" h2="Импортируйте и экспортируйте файлы Excel в форматах электронных таблиц, Интернета, изображений и с фиксированным макетом." >}}

{{% blocks/products/pf/feature-page-summary %}}
Библиотека PHP Excel ускоряет процессы программирования и преобразования электронных таблиц, поддерживая популярные форматы, включая XLS, XLSX, XLSM, XLSB, XLTM, XLTM, CSV, SpreadsheetML, ODS. Она также позволяет экспортировать Excel. файлы на PDF, XPS, HTML, MHTML, обычный Текстовые и популярные форматы изображений, такие как TIFF, JPG, PNG, BMP и SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Преобразование Excel в XLSX, ODS, SXC и FODS с помощью PHP" %}}
 Для взаимного преобразования формата электронной таблицы требуется только загрузка электронной таблицы с экземпляром[Рабочая тетрадь](https://reference.aspose.com/cells/php/aspose.cells/Workbook) и сохранить обратно в желаемом формате, выбрав подходящее значение из[СохранитьФормат](https://reference.aspose.com/cells/php/aspose.cells/SaveFormat) перечисление.
{{% blocks/products/pf/feature-page-code h3="PHP-код для преобразования формата файла Excel" %}}

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


{{% blocks/products/pf/feature-page-section h2="Преобразование Excel в PDF, XPS, HTML и MD с помощью PHP" %}}
 Доступны специализированные классы для управления процессом преобразования для определенных выходных форматов, таких как[PDFSaveOptions](https://reference.aspose.com/cells/php/aspose.cells/PdfSaveOptions/)для экспорта файлов Excel как PDF,[XpsSaveOptions](https://reference.aspose.com/cells/php/aspose.cells/XpsSaveOptions/) для преобразования Excel в XPS,[HtmlSaveOptions](https://reference.aspose.com/cells/php/aspose.cells/HtmlSaveOptions/) для отображения Excel как HTML и[МаркдаунСохранитьПараметры](https://reference.aspose.com/cells/php/aspose.cells/MarkdownSaveOptions/) для преобразования Excel в Markdown.
{{% blocks/products/pf/feature-page-code h3="PHP-код для Excel для PDF и веб-форматов" %}}

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

{{% blocks/products/pf/feature-page-section h2="Преобразование JSON в Excel и Excel в JSON с помощью PHP" %}}
Разработчики PHP могут легко загружать и конвертировать файлы JSON в Excel всего за несколько строк кода. Аналогичным образом данные Excel можно экспортировать в данные JSON.
{{% blocks/products/pf/feature-page-code h3="PHP-код для преобразования JSON в Excel" %}}

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

{{% blocks/products/pf/feature-page-code h3="Преобразование PHP-кода Excel в JSON" %}}

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

{{% blocks/products/pf/feature-page-section h2="Конвертируйте листы Excel в JPG, BMP, PNG и GIF с помощью PHP" %}}
 Каждый лист файла Excel можно преобразовать в разные форматы изображений, позвоните[Параметры изображения или печати](https://reference.aspose.com/cells/php/aspose.cells/ImageOrPrintOptions/) .setImageFormat для установки формата изображения.
{{% blocks/products/pf/feature-page-code h3="PHP-код для преобразования Excel в изображения" %}}

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

{{% blocks/products/pf/feature-page-section h2="Преобразование Excel в Word и PowerPoint с помощью PHP" %}}
Можно загрузить любую электронную таблицу и преобразовать ее в файлы Word DOCX и PowerPoint PPTX при использовании[Параметры сохранения документа](https://reference.aspose.com/cells/php/aspose.cells/DocxSaveOptions/) & [Параметры сохранения Pptx](https://reference.aspose.com/cells/php/aspose.cells/PptxSaveOptions/) классы, как показано ниже.
{{% blocks/products/pf/feature-page-code h3="PHP-код для Excel в Word и преобразование PowerPoint" %}}
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
