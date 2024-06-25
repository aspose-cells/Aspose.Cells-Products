---
title: Microsoft PHP का उपयोग करके Excel फ़ाइल रूपांतरण via Java
description: Aspose.Cells for PHP via Java लाइब्रेरी। PHP कोड की कुछ ही पंक्तियों के साथ EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL और अधिक प्रारूपों को परिवर्तित करें।
keywords: [PHP Aspose.Cells., excel to pdf., json to excel., excel to json., csv to json., json to html., xml to excel and Convert files between various formats in PHP]
---
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header-php-java h1="Microsoft<sup>&reg;</sup> PHP के माध्यम से एक्सेल प्रारूप रूपांतरण" h2="एक्सेल फ़ाइलों को स्प्रेडशीट, वेब, छवि और निश्चित-लेआउट प्रारूपों में आयात और निर्यात करें" >}}

{{% blocks/products/pf/feature-page-summary %}}
PHP एक्सेल लाइब्रेरी XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS सहित लोकप्रिय प्रारूपों का समर्थन करते हुए स्प्रेडशीट प्रोग्रामिंग और रूपांतरण प्रक्रियाओं को गति देती है। यह एक्सेल फ़ाइलों को PDF, XPS, HTML, MHTML, प्लेन टेक्स्ट और लोकप्रिय छवि प्रारूपों जैसे TIFF, JPG, PNG, BMP और SVG में निर्यात करने की भी अनुमति देता है।
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="PHP का उपयोग करके Excel को XLSX, ODS, SXC और FODS में बदलें" %}}
 स्प्रेडशीट प्रारूप के अंतर-रूपांतरण के लिए केवल एक उदाहरण के साथ स्प्रेडशीट लोड करना आवश्यक है[वर्कबुक](https://reference.aspose.com/cells/php/aspose.cells/Workbook) और उचित मूल्य का चयन करते हुए वांछित प्रारूप में वापस सहेजना[सहेजेंप्रारूप](https://reference.aspose.com/cells/php/aspose.cells/SaveFormat) गणना.
{{% blocks/products/pf/feature-page-code h3="एक्सेल फ़ाइल प्रारूप रूपांतरण के लिए PHP कोड" %}}

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


{{% blocks/products/pf/feature-page-section h2="PHP का उपयोग करके Excel को PDF, XPS, HTML और MD में बदलें" %}}
 विशिष्ट आउटपुट प्रारूपों के लिए रूपांतरण प्रक्रिया को नियंत्रित करने के लिए विशेष कक्षाएं उपलब्ध हैं जैसे[पीडीएफसहेजेंविकल्प](https://reference.aspose.com/cells/php/aspose.cells/PdfSaveOptions/)एक्सेल फ़ाइलों को PDF के रूप में निर्यात करने के लिए,[Xpsसेवविकल्प](https://reference.aspose.com/cells/php/aspose.cells/XpsSaveOptions/) एक्सेल से XPS रूपांतरण के लिए,[Htmlसहेजेंविकल्प](https://reference.aspose.com/cells/php/aspose.cells/HtmlSaveOptions/) एक्सेल को HTML के रूप में प्रस्तुत करने के लिए और[मार्कडाउनसहेजेंविकल्प](https://reference.aspose.com/cells/php/aspose.cells/MarkdownSaveOptions/) एक्सेल से मार्कडाउन रूपांतरण के लिए.
{{% blocks/products/pf/feature-page-code h3="एक्सेल के लिए PHP कोड PDF और वेब प्रारूप" %}}

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

{{% blocks/products/pf/feature-page-section h2="PHP का उपयोग करके JSON को Excel में और Excel को JSON में बदलें" %}}
PHP डेवलपर्स आसानी से JSON फ़ाइलों को कोड की कुछ ही पंक्तियों में एक्सेल में लोड और कन्वर्ट कर सकते हैं। इसी तरह, एक्सेल डेटा को JSON डेटा में एक्सपोर्ट किया जा सकता है।
{{% blocks/products/pf/feature-page-code h3="JSON से Excel रूपांतरण के लिए PHP कोड" %}}

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

{{% blocks/products/pf/feature-page-code h3="एक्सेल से JSON रूपांतरण के लिए PHP कोड" %}}

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

{{% blocks/products/pf/feature-page-section h2="PHP का उपयोग करके Excel वर्कशीट को JPG, BMP, PNG और GIF में बदलें" %}}
 एक्सेल फ़ाइल की प्रत्येक वर्कशीट को विभिन्न छवि प्रारूपों में परिवर्तित किया जा सकता है, जिन्हें कहा जाता है[छवियाप्रिंटविकल्प](https://reference.aspose.com/cells/php/aspose.cells/ImageOrPrintOptions/) छवि प्रारूप सेट करने के लिए .setImageFormat.
{{% blocks/products/pf/feature-page-code h3="एक्सेल से छवि रूपांतरण के लिए PHP कोड" %}}

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

{{% blocks/products/pf/feature-page-section h2="PHP का उपयोग करके Excel को Word में बदलें & PowerPoint" %}}
किसी भी स्प्रेडशीट को लोड करना और इसे वर्ड DOCX और PowerPoint PPTX फ़ाइलों में परिवर्तित करना संभव है[DocxSaveविकल्प](https://reference.aspose.com/cells/php/aspose.cells/DocxSaveOptions/) & [पीपीटीएक्ससेवऑप्शन](https://reference.aspose.com/cells/php/aspose.cells/PptxSaveOptions/) जैसा कि नीचे दर्शाया गया है, कक्षाएं।
{{% blocks/products/pf/feature-page-code h3="एक्सेल से वर्ड और PowerPoint रूपांतरण के लिए PHP कोड" %}}
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
