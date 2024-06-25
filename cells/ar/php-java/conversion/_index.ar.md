---
title: Microsoft تحويل ملفات Excel باستخدام PHP via Java
description: Aspose.Cells for PHP via Java مكتبة. تحويل EXCEL، JSON، PDF، XML، HTML، TXT، TSV، CSV، SQL والمزيد من التنسيقات مع بضعة أسطر فقط من كود PHP.
keywords: [PHP Aspose.Cells., excel to pdf., json to excel., excel to json., csv to json., json to html., xml to excel and Convert files between various formats in PHP]
---
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header-php-java h1="Microsoft<sup>&reg;</sup> تحويل تنسيق Excel عبر PHP" h2="استيراد وتصدير ملفات Excel بتنسيقات جداول البيانات والويب والصور والتخطيطات الثابتة" >}}

{{% blocks/products/pf/feature-page-summary %}}
تعمل مكتبة PHP Excel على تسريع برمجة جداول البيانات وعمليات التحويل مع دعم التنسيقات الشائعة بما في ذلك XLS، XLSX، XLSB، XLTX، XLTM، CSV، SpreadsheetML، ODS. كما أنها تسمح بتصدير Excel الملفات إلى PDF، XPS، HTML، MHTML، عادي تنسيقات النصوص والصور الشائعة مثل TIFF وJPG وPNG وBMP وSVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="تحويل Excel إلى XLSX وODS وSXC وFODS باستخدام PHP" %}}
 يتطلب التحويل البيني لتنسيق جدول البيانات فقط تحميل جدول بيانات بمثيل[دفتر العمل](https://reference.aspose.com/cells/php/aspose.cells/Workbook) والحفظ مرة أخرى بالتنسيق المطلوب أثناء تحديد القيمة المناسبة من[حفظ التنسيق](https://reference.aspose.com/cells/php/aspose.cells/SaveFormat) تعداد.
{{% blocks/products/pf/feature-page-code h3="كود PHP لتحويل تنسيق ملف Excel" %}}

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


{{% blocks/products/pf/feature-page-section h2="تحويل Excel إلى PDF وXPS وHTML وMD باستخدام PHP" %}}
 تتوفر فئات متخصصة للتحكم في عملية التحويل لتنسيقات إخراج محددة مثل[خيارات حفظ PDF](https://reference.aspose.com/cells/php/aspose.cells/PdfSaveOptions/)لتصدير ملفات Excel كـ PDF،[خيارات XpsSave](https://reference.aspose.com/cells/php/aspose.cells/XpsSaveOptions/) لتحويل Excel إلى XPS ،[هتملسافيوبتيونس](https://reference.aspose.com/cells/php/aspose.cells/HtmlSaveOptions/) لتقديم Excel كـ HTML و[خيارات تخفيض السعر](https://reference.aspose.com/cells/php/aspose.cells/MarkdownSaveOptions/) لتحويل Excel إلى Markdown.
{{% blocks/products/pf/feature-page-code h3="كود PHP لبرنامج Excel إلى PDF وتنسيقات الويب" %}}

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

{{% blocks/products/pf/feature-page-section h2="تحويل JSON إلى Excel و Excel إلى JSON باستخدام PHP" %}}
يمكن لمطوري PHP تحميل ملفات JSON وتحويلها بسهولة إلى Excel في بضعة أسطر فقط من التعليمات البرمجية. وبالمثل، يمكن تصدير بيانات Excel إلى بيانات JSON.
{{% blocks/products/pf/feature-page-code h3="كود PHP لتحويل JSON إلى Excel" %}}

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

{{% blocks/products/pf/feature-page-code h3="كود PHP لتحويل Excel إلى JSON" %}}

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

{{% blocks/products/pf/feature-page-section h2="تحويل أوراق عمل Excel إلى JPG، BMP، PNG وGIF باستخدام PHP" %}}
 يمكن تحويل كل ورقة عمل من ملف Excel إلى تنسيقات صور مختلفة[خيارات الصورة أو الطباعة](https://reference.aspose.com/cells/php/aspose.cells/ImageOrPrintOptions/) .setImageFormat لتعيين تنسيق الصورة.
{{% blocks/products/pf/feature-page-code h3="كود PHP لبرنامج Excel لتحويل الصور" %}}

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

{{% blocks/products/pf/feature-page-section h2="تحويل Excel إلى Word وPowerPoint باستخدام PHP" %}}
من الممكن تحميل أي جدول بيانات وتحويله إلى ملفات Word DOCX & PowerPoint PPTX أثناء الاستخدام[DocxSaveOptions](https://reference.aspose.com/cells/php/aspose.cells/DocxSaveOptions/) & [خيارات PptxSave](https://reference.aspose.com/cells/php/aspose.cells/PptxSaveOptions/) الطبقات كما هو موضح أدناه.
{{% blocks/products/pf/feature-page-code h3="كود PHP لتحويل Excel إلى Word وPowerPoint" %}}
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
