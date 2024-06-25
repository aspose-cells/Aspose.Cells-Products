---
title: Microsoft Chuyển đổi tệp Excel bằng PHP via Java
description: Aspose.Cells for PHP via Java thư viện. Chuyển đổi EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL và nhiều định dạng khác chỉ với vài dòng mã PHP.
keywords: [PHP Aspose.Cells., excel to pdf., json to excel., excel to json., csv to json., json to html., xml to excel and Convert files between various formats in PHP]
---
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header-php-java h1="Microsoft<sup>&reg;</sup> Chuyển đổi định dạng Excel qua PHP" h2="Nhập và xuất các tệp Excel dưới dạng bảng tính, web, hình ảnh và bố cục cố định" >}}

{{% blocks/products/pf/feature-page-summary %}}
Thư viện PHP Excel tăng tốc quá trình lập trình và chuyển đổi bảng tính đồng thời hỗ trợ các định dạng phổ biến bao gồm XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Nó cũng cho phép xuất các tệp Excel sang PDF, XPS, HTML, MHTML, Trơn Các định dạng văn bản và hình ảnh phổ biến như TIFF, JPG, PNG, BMP và SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Chuyển đổi Excel thành XLSX, ODS, SXC & FODS bằng PHP" %}}
 Việc chuyển đổi giữa các định dạng bảng tính chỉ yêu cầu tải một bảng tính có phiên bản của[Sách bài tập](https://reference.aspose.com/cells/php/aspose.cells/Workbook) và lưu lại ở định dạng mong muốn trong khi chọn giá trị thích hợp từ[Lưu định dạng](https://reference.aspose.com/cells/php/aspose.cells/SaveFormat) sự liệt kê.
{{% blocks/products/pf/feature-page-code h3="Mã PHP để chuyển đổi định dạng tệp Excel" %}}

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


{{% blocks/products/pf/feature-page-section h2="Chuyển đổi Excel thành PDF, XPS, HTML & MD bằng PHP" %}}
 Các lớp chuyên biệt có sẵn để kiểm soát quá trình chuyển đổi cho các định dạng đầu ra cụ thể như[Tùy chọn lưu Pdf](https://reference.aspose.com/cells/php/aspose.cells/PdfSaveOptions/)để xuất tệp Excel dưới dạng PDF,[Tùy chọn XpsSave](https://reference.aspose.com/cells/php/aspose.cells/XpsSaveOptions/) để chuyển đổi Excel sang XPS,[Tùy chọn lưu Html](https://reference.aspose.com/cells/php/aspose.cells/HtmlSaveOptions/) để hiển thị Excel dưới dạng HTML và[MarkdownSaveOptions](https://reference.aspose.com/cells/php/aspose.cells/MarkdownSaveOptions/) để chuyển đổi Excel sang Markdown.
{{% blocks/products/pf/feature-page-code h3="Mã PHP cho Excel tới PDF và Định dạng Web" %}}

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

{{% blocks/products/pf/feature-page-section h2="Chuyển đổi JSON sang Excel & Excel thành JSON Sử dụng PHP" %}}
Các nhà phát triển PHP có thể dễ dàng tải và chuyển đổi tệp JSON sang Excel chỉ bằng vài dòng mã. Tương tự, dữ liệu Excel có thể xuất sang dữ liệu JSON.
{{% blocks/products/pf/feature-page-code h3="Mã PHP cho chuyển đổi JSON sang Excel" %}}

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

{{% blocks/products/pf/feature-page-code h3="Mã PHP cho Excel chuyển đổi sang JSON" %}}

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

{{% blocks/products/pf/feature-page-section h2="Chuyển đổi bảng tính Excel sang JPG, BMP, PNG & GIF bằng PHP" %}}
 Mỗi bảng tính của một tệp Excel có thể được chuyển đổi sang các định dạng hình ảnh khác nhau, hãy gọi[Tùy chọn Hình ảnh Hoặc In](https://reference.aspose.com/cells/php/aspose.cells/ImageOrPrintOptions/) .setImageFormat để đặt định dạng hình ảnh.
{{% blocks/products/pf/feature-page-code h3="Mã PHP để chuyển đổi Excel sang hình ảnh" %}}

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

{{% blocks/products/pf/feature-page-section h2="Chuyển Excel sang Word & PowerPoint Sử dụng PHP" %}}
Có thể tải bất kỳ bảng tính nào và chuyển đổi nó thành tệp Word DOCX & PowerPoint PPTX trong khi sử dụng[Tùy chọn lưu Docx](https://reference.aspose.com/cells/php/aspose.cells/DocxSaveOptions/) & [Tùy chọn lưu Pptx](https://reference.aspose.com/cells/php/aspose.cells/PptxSaveOptions/) các lớp như được minh họa dưới đây.
{{% blocks/products/pf/feature-page-code h3="Mã PHP cho Excel sang Word & chuyển đổi PowerPoint" %}}
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
