---
title: Microsoft 使用 PHP 进行 Excel 文件转换 via Java
description: Aspose.Cells for PHP via Java 库。只需几行 PHP 代码即可转换 EXCEL、JSON、PDF、XML、HTML、TXT、TSV、CSV、SQL 等格式。
keywords: [PHP Aspose.Cells., excel to pdf., json to excel., excel to json., csv to json., json to html., xml to excel and Convert files between various formats in PHP]
---
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header-php-java h1="Microsoft<sup>&reg;</sup> 通过 PHP 进行 Excel 格式转换" h2="将 Excel 文件导入和导出为电子表格、网页、图像和固定布局格式" >}}

{{% blocks/products/pf/feature-page-summary %}}
PHP Excel 库加快了电子表格编程和转换过程，同时支持流行格式，包括 XLS、XLSX、XLSM、XLSB、XLTX、XLTM、CSV、SpreadsheetML、ODS。它还允许将 Excel 文件导出为 PDF、XPS、HTML、MHTML、纯文本和流行图像格式，如 TIFF、JPG、PNG、BMP 和 SVG。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="使用 PHP 将 Excel 转换为 XLSX、ODS、SXC 和 FODS" %}}
电子表格格式的相互转换只需要加载一个带有[工作簿](https://reference.aspose.com/cells/php/aspose.cells/Workbook)并以所需格式保存，同时从中选择适当的值[保存格式](https://reference.aspose.com/cells/php/aspose.cells/SaveFormat)枚举。
{{% blocks/products/pf/feature-page-code h3="Excel文件格式转换的PHP代码" %}}

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


{{% blocks/products/pf/feature-page-section h2="使用 PHP 将 Excel 转换为 PDF、XPS、HTML 和 MD" %}}
有专门的类可以控制特定输出格式的转换过程，例如[Pdf保存选项](https://reference.aspose.com/cells/php/aspose.cells/PdfSaveOptions/)将 Excel 文件导出为 PDF，[Xps保存选项](https://reference.aspose.com/cells/php/aspose.cells/XpsSaveOptions/)用于 Excel 到 XPS 的转换，[Html保存选项](https://reference.aspose.com/cells/php/aspose.cells/HtmlSaveOptions/)将 Excel 呈现为 HTML 和[Markdown保存选项](https://reference.aspose.com/cells/php/aspose.cells/MarkdownSaveOptions/)用于 Excel 到 Markdown 的转换。
{{% blocks/products/pf/feature-page-code h3="Excel 的 PHP 代码为 PDF 和 Web 格式" %}}

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

{{% blocks/products/pf/feature-page-section h2="使用 PHP 将 JSON 转换为 Excel 并将 Excel 转换为 JSON" %}}
PHP 开发人员只需几行代码即可轻松加载和转换 JSON 文件到 Excel。同样，Excel 数据可以导出到 JSON 数据。
{{% blocks/products/pf/feature-page-code h3="JSON 到 Excel 转换的 PHP 代码" %}}

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

{{% blocks/products/pf/feature-page-code h3="Excel 到 JSON 转换的 PHP 代码" %}}

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

{{% blocks/products/pf/feature-page-section h2="使用 PHP 将 Excel 工作表转换为 JPG、BMP、PNG 和 GIF" %}}
 Excel 文件的每个工作表都可以转换为不同的图像格式，调用[图像或打印选项](https://reference.aspose.com/cells/php/aspose.cells/ImageOrPrintOptions/).setImageFormat 设置图像格式。
{{% blocks/products/pf/feature-page-code h3="Excel 到图像转换的 PHP 代码" %}}

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

{{% blocks/products/pf/feature-page-section h2="使用 PHP 将 Excel 转换为 Word 和 PowerPoint" %}}
可以加载任何电子表格并将其转换为 Word DOCX & PowerPoint PPTX 文件，同时使用[Docx保存选项](https://reference.aspose.com/cells/php/aspose.cells/DocxSaveOptions/) & [Pptx保存选项](https://reference.aspose.com/cells/php/aspose.cells/PptxSaveOptions/)如下所示的类。
{{% blocks/products/pf/feature-page-code h3="Excel 到 Word 及 PowerPoint 转换的 PHP 代码" %}}
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
