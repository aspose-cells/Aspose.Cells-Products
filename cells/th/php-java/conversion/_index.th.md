---
title: Microsoft การแปลงไฟล์ Excel โดยใช้ PHP via Java
description: Aspose.Cells for PHP via Java ห้องสมุด. แปลง EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL และรูปแบบอื่นๆ ด้วยโค้ด PHP เพียงไม่กี่บรรทัด
keywords: [PHP Aspose.Cells., excel to pdf., json to excel., excel to json., csv to json., json to html., xml to excel and Convert files between various formats in PHP]
---
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header-php-java h1="Microsoft<sup>&reg;</sup> การแปลงรูปแบบ Excel ผ่าน PHP" h2="นำเข้าและส่งออกไฟล์ Excel เป็นสเปรดชีต เว็บ รูปภาพ และรูปแบบคงที่" >}}

{{% blocks/products/pf/feature-page-summary %}}
PHP Excel Library เร่งความเร็วการเขียนโปรแกรมสเปรดชีตและกระบวนการแปลงในขณะที่รองรับรูปแบบยอดนิยม ได้แก่ XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS นอกจากนี้ยังอนุญาตให้ส่งออกไฟล์ Excel ได้อีกด้วย ถึง PDF, XPS, HTML, MHTML, ธรรมดา รูปแบบข้อความและรูปภาพยอดนิยม เช่น TIFF, JPG, PNG, BMP และ SVG
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="แปลง Excel เป็น XLSX, ODS, SXC และ FODS โดยใช้ PHP" %}}
 การแปลงรูปแบบสเปรดชีตระหว่างกันต้องโหลดสเปรดชีตที่มีอินสแตนซ์เท่านั้น[สมุดงาน](https://reference.aspose.com/cells/php/aspose.cells/Workbook) และบันทึกกลับในรูปแบบที่ต้องการพร้อมเลือกค่าที่เหมาะสมจาก[บันทึกรูปแบบ](https://reference.aspose.com/cells/php/aspose.cells/SaveFormat) การแจงนับ
{{% blocks/products/pf/feature-page-code h3="รหัส PHP สำหรับการแปลงรูปแบบไฟล์ Excel" %}}

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


{{% blocks/products/pf/feature-page-section h2="แปลง Excel เป็น PDF, XPS, HTML & MD โดยใช้ PHP" %}}
 มีคลาสเฉพาะทางเพื่อควบคุมกระบวนการแปลงสำหรับรูปแบบเอาต์พุตเฉพาะเช่น[ตัวเลือก PdfSave](https://reference.aspose.com/cells/php/aspose.cells/PdfSaveOptions/)เพื่อส่งออกไฟล์ Excel เป็น PDF,[XpsSaveOptions](https://reference.aspose.com/cells/php/aspose.cells/XpsSaveOptions/) สำหรับการแปลง Excel เป็น XPS[HtmlSaveตัวเลือก](https://reference.aspose.com/cells/php/aspose.cells/HtmlSaveOptions/) เพื่อเรนเดอร์ Excel เป็น HTML และ[MarkdownSaveOptions](https://reference.aspose.com/cells/php/aspose.cells/MarkdownSaveOptions/) สำหรับการแปลง Excel เป็น Markdown
{{% blocks/products/pf/feature-page-code h3="รหัส PHP สำหรับ Excel ถึง PDF และรูปแบบเว็บ" %}}

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

{{% blocks/products/pf/feature-page-section h2="แปลง JSON เป็น Excel และ Excel เป็น JSON โดยใช้ PHP" %}}
นักพัฒนา PHP สามารถโหลดและแปลงไฟล์ JSON เป็น Excel ได้อย่างง่ายดายโดยใช้โค้ดเพียงไม่กี่บรรทัด ในทำนองเดียวกัน ข้อมูล Excel สามารถส่งออกไปยังข้อมูล JSON ได้
{{% blocks/products/pf/feature-page-code h3="รหัส PHP สำหรับ JSON เป็นการแปลง Excel" %}}

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

{{% blocks/products/pf/feature-page-code h3="รหัส PHP สำหรับ Excel เป็น JSON การแปลง" %}}

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

{{% blocks/products/pf/feature-page-section h2="แปลงแผ่นงาน Excel เป็น JPG, BMP, PNG & GIF โดยใช้ PHP" %}}
 แต่ละแผ่นงานของไฟล์ Excel สามารถแปลงเป็นรูปแบบรูปภาพที่แตกต่างกันได้ โทร[รูปภาพหรือตัวเลือกการพิมพ์](https://reference.aspose.com/cells/php/aspose.cells/ImageOrPrintOptions/) .setImageFormat เพื่อกำหนดรูปแบบภาพ
{{% blocks/products/pf/feature-page-code h3="รหัส PHP สำหรับ Excel เป็นการแปลงรูปภาพ" %}}

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

{{% blocks/products/pf/feature-page-section h2="แปลง Excel เป็น Word & PowerPoint โดยใช้ PHP" %}}
คุณสามารถโหลดสเปรดชีตใดก็ได้และแปลงเป็นไฟล์ Word DOCX & PowerPoint PPTX ในขณะที่ใช้งาน[DocxSaveOptions](https://reference.aspose.com/cells/php/aspose.cells/DocxSaveOptions/) & [PptxSaveOptions](https://reference.aspose.com/cells/php/aspose.cells/PptxSaveOptions/) ชั้นเรียนตามที่แสดงด้านล่าง
{{% blocks/products/pf/feature-page-code h3="รหัส PHP สำหรับ Excel เป็น Word และการแปลง PowerPoint" %}}
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
