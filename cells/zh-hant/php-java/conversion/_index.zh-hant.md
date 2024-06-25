---
title: Microsoft 使用 PHP 轉換 Excel 檔案 via Java
description: Aspose.Cells for PHP via Java 圖書館。只需幾行 PHP 程式碼即可轉換 EXCEL、JSON、PDF、XML、HTML、TXT、TSV、CSV、SQL 等格式。
keywords: [PHP Aspose.Cells., excel to pdf., json to excel., excel to json., csv to json., json to html., xml to excel and Convert files between various formats in PHP]
---
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header-php-java h1="Microsoft<sup>&reg;</sup> 透過 PHP 轉換 Excel 格式" h2="將 Excel 檔案匯入和匯出為電子表格、Web、圖像和固定佈局格式" >}}

{{% blocks/products/pf/feature-page-summary %}}
PHP Excel 函式庫加快了電子表格程式設計和轉換過程，同時支援流行的格式，包括XLS、XLSX、XLSM、XLSB、XLTX、XLTM、CSV43481、XLTM、CSV017676176176767617617676176176767617632176176376722/76176376372。 93481、XPS、HTML 、MHTML、普通文字和流行的圖像格式，例如 TIFF、JPG、PNG、BMP 和 SVG。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="使用 PHP 將 Excel 轉換為 XLSX、ODS、SXC 和 FODS" %}}
電子表格格式的相互轉換只需要載入帶有實例的電子表格[練習冊](https://reference.aspose.com/cells/php/aspose.cells/Workbook)並以所需的格式儲存，同時從中選擇適當的值[儲存格式](https://reference.aspose.com/cells/php/aspose.cells/SaveFormat)枚舉。
{{% blocks/products/pf/feature-page-code h3="Excel 檔案格式轉換的 PHP 程式碼" %}}

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


{{% blocks/products/pf/feature-page-section h2="使用 PHP 將 Excel 轉換為 PDF、XPS、HTML 和 MD" %}}
專門的類別可用於控制特定輸出格式的轉換過程，例如[Pdf保存選項](https://reference.aspose.com/cells/php/aspose.cells/PdfSaveOptions/)將 Excel 檔案匯出為 PDF，[Xps儲存選項](https://reference.aspose.com/cells/php/aspose.cells/XpsSaveOptions/)對於 Excel 到 XPS 的轉換，[Html保存選項](https://reference.aspose.com/cells/php/aspose.cells/HtmlSaveOptions/)將 Excel 呈現為 HTML 和[Markdown儲存選項](https://reference.aspose.com/cells/php/aspose.cells/MarkdownSaveOptions/)用於 Excel 到 Markdown 的轉換。
{{% blocks/products/pf/feature-page-code h3="Excel 到 PDF 和 Web 格式的 PHP 程式碼" %}}

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

{{% blocks/products/pf/feature-page-section h2="使用 PHP 將 JSON 轉換為 Excel 並將 Excel 轉換為 JSON" %}}
PHP 開發人員只需幾行程式碼即可輕鬆載入 JSON 檔案並將其轉換為 Excel。同樣，Excel資料可以匯出為JSON資料。
{{% blocks/products/pf/feature-page-code h3="用於 JSON 到 Excel 轉換的 PHP 程式碼" %}}

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

{{% blocks/products/pf/feature-page-code h3="Excel 到 JSON 轉換的 PHP 程式碼" %}}

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

{{% blocks/products/pf/feature-page-section h2="使用 PHP 將 Excel 工作表轉換為 JPG、BMP、PNG 和 GIF" %}}
 Excel檔案的每個工作表都可以轉換為不同的影像格式，調用[影像或列印選項](https://reference.aspose.com/cells/php/aspose.cells/ImageOrPrintOptions/).setImageFormat 設定影像格式。
{{% blocks/products/pf/feature-page-code h3="用於 Excel 到影像轉換的 PHP 程式碼" %}}

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

{{% blocks/products/pf/feature-page-section h2="使用 PHP 將 Excel 轉換為 Word & PowerPoint" %}}
使用時可以載入任何電子表格並將其轉換為 Word DOCX 和 PowerPoint PPTX 文件[Docx保存選項](https://reference.aspose.com/cells/php/aspose.cells/DocxSaveOptions/) & [Pptx保存選項](https://reference.aspose.com/cells/php/aspose.cells/PptxSaveOptions/)類別如下所示。
{{% blocks/products/pf/feature-page-code h3="用於 Excel 到 Word 和 PowerPoint 轉換的 PHP 程式碼" %}}
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
