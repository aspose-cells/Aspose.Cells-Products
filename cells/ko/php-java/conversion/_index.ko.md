---
title: Microsoft PHP를 사용한 Excel 파일 변환 via Java
description: Aspose.Cells for PHP via Java 도서관. 단 몇 줄의 PHP 코드만으로 EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL 및 기타 형식을 변환할 수 있습니다.
keywords: [PHP Aspose.Cells., excel to pdf., json to excel., excel to json., csv to json., json to html., xml to excel and Convert files between various formats in PHP]
---
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header-php-java h1="Microsoft<sup>&reg;</sup> PHP를 통한 Excel 형식 변환" h2="스프레드시트, 웹, 이미지 및 고정 레이아웃 형식으로 Excel 파일 가져오기 및 내보내기" >}}

{{% blocks/products/pf/feature-page-summary %}}
PHP Excel 라이브러리는 XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS 등 널리 사용되는 형식을 지원하면서 스프레드시트 프로그래밍 및 변환 프로세스 속도를 높입니다. PDF, XPS, HTML, MHTML, 일반 TIFF, JPG, PNG, BMP 및 SVG과 같은 텍스트 및 널리 사용되는 이미지 형식입니다.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="PHP를 사용하여 Excel을 XLSX, ODS, SXC 및 FODS로 변환" %}}
 스프레드시트 형식의 상호 변환은 다음 인스턴스가 있는 스프레드시트를 로드하기만 하면 됩니다.[학습장](https://reference.aspose.com/cells/php/aspose.cells/Workbook) 다음에서 적절한 값을 선택하면서 원하는 형식으로 다시 저장합니다.[형식 저장](https://reference.aspose.com/cells/php/aspose.cells/SaveFormat) 열거.
{{% blocks/products/pf/feature-page-code h3="Excel 파일 형식 변환을 위한 PHP 코드" %}}

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


{{% blocks/products/pf/feature-page-section h2="PHP를 사용하여 Excel을 PDF, XPS, HTML 및 MD로 변환" %}}
 다음과 같은 특정 출력 형식에 대한 변환 프로세스를 제어하기 위해 특수 클래스를 사용할 수 있습니다.[PDF저장옵션](https://reference.aspose.com/cells/php/aspose.cells/PdfSaveOptions/)Excel 파일을 PDF로 내보내려면,[XpsSave옵션](https://reference.aspose.com/cells/php/aspose.cells/XpsSaveOptions/) Excel에서 XPS로 변환,[HtmlSave옵션](https://reference.aspose.com/cells/php/aspose.cells/HtmlSaveOptions/) Excel을 HTML로 렌더링하고[마크다운저장옵션](https://reference.aspose.com/cells/php/aspose.cells/MarkdownSaveOptions/) Excel에서 Markdown으로의 변환을 위해.
{{% blocks/products/pf/feature-page-code h3="Excel에서 PDF까지의 PHP 코드 및 웹 형식" %}}

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

{{% blocks/products/pf/feature-page-section h2="PHP를 사용하여 JSON을 Excel로 & Excel을 JSON로 변환" %}}
PHP 개발자는 단 몇 줄의 코드만으로 JSON 파일을 Excel로 쉽게 로드하고 변환할 수 있습니다. 마찬가지로 Excel 데이터를 JSON 데이터로 내보낼 수 있습니다.
{{% blocks/products/pf/feature-page-code h3="JSON을 Excel로 변환하는 PHP 코드" %}}

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

{{% blocks/products/pf/feature-page-code h3="Excel용 PHP 코드를 JSON로 변환" %}}

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

{{% blocks/products/pf/feature-page-section h2="PHP를 사용하여 Excel 워크시트를 JPG, BMP, PNG 및 GIF로 변환" %}}
 Excel 파일의 각 워크시트를 다른 이미지 형식으로 변환할 수 있습니다.[이미지또는인쇄옵션](https://reference.aspose.com/cells/php/aspose.cells/ImageOrPrintOptions/) .setImageFormat은 이미지 형식을 설정합니다.
{{% blocks/products/pf/feature-page-code h3="Excel에서 이미지로 변환하는 PHP 코드" %}}

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

{{% blocks/products/pf/feature-page-section h2="PHP를 사용하여 Excel을 Word 및 PowerPoint로 변환" %}}
사용하는 동안 스프레드시트를 로드하고 Word DOCX 및 PowerPoint PPTX 파일로 변환할 수 있습니다.[DocxSave옵션](https://reference.aspose.com/cells/php/aspose.cells/DocxSaveOptions/) & [PptxSave옵션](https://reference.aspose.com/cells/php/aspose.cells/PptxSaveOptions/) 아래에 설명된 대로 수업을 진행합니다.
{{% blocks/products/pf/feature-page-code h3="Excel에서 Word로의 PHP 코드 및 PowerPoint 변환" %}}
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
