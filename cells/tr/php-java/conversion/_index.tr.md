---
title: Microsoft PHP Kullanarak Excel Dosyası Dönüştürme via Java
description: Aspose.Cells for PHP via Java kütüphane. Sadece birkaç satır PHP koduyla EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL ve daha birçok formatı dönüştürün.
keywords: [PHP Aspose.Cells., excel to pdf., json to excel., excel to json., csv to json., json to html., xml to excel and Convert files between various formats in PHP]
---
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header-php-java h1="Microsoft<sup>&reg;</sup> PHP aracılığıyla Excel Format Dönüştürme" h2="Excel dosyalarını elektronik tablo, web, resim ve sabit düzen formatlarında içe ve dışa aktarın" >}}

{{% blocks/products/pf/feature-page-summary %}}
PHP Excel Kütüphanesi, XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS gibi popüler formatları desteklerken elektronik tablo programlama ve dönüştürme süreçlerini hızlandırır. Ayrıca Excel dosyalarının dışa aktarılmasına da olanak tanır PDF, XPS, HTML, MHTML, Düz TIFF, JPG, PNG, BMP ve SVG gibi metin ve popüler resim formatları.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="PHP kullanarak Excel\'i XLSX, ODS, SXC ve FODS\'e dönüştürün" %}}
 Elektronik tablo formatının karşılıklı dönüştürülmesi yalnızca aşağıdaki örneğin bulunduğu bir elektronik tablonun yüklenmesini gerektirir:[Çalışma kitabı](https://reference.aspose.com/cells/php/aspose.cells/Workbook) ve uygun değeri seçerken istenilen formatta tekrar kaydetme[Formatı Kaydet](https://reference.aspose.com/cells/php/aspose.cells/SaveFormat) numaralandırma.
{{% blocks/products/pf/feature-page-code h3="Excel Dosya Formatı Dönüşümü için PHP Kodu" %}}

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


{{% blocks/products/pf/feature-page-section h2="PHP Kullanarak Excel\'i PDF, XPS, HTML ve MD\'ye Dönüştürme" %}}
 Belirli çıktı formatları için dönüştürme sürecini kontrol etmek amacıyla özel sınıflar mevcuttur:[PdfKaydetmeSeçenekleri](https://reference.aspose.com/cells/php/aspose.cells/PdfSaveOptions/)Excel dosyalarını PDF olarak dışa aktarmak için,[XpsSaveOptions](https://reference.aspose.com/cells/php/aspose.cells/XpsSaveOptions/) Excel'den XPS'e dönüşüm için,[HtmlSaveOptions](https://reference.aspose.com/cells/php/aspose.cells/HtmlSaveOptions/) Excel'i HTML olarak işlemek ve[İşaretlemeKaydetSeçenekleri](https://reference.aspose.com/cells/php/aspose.cells/MarkdownSaveOptions/) Excel'den Markdown'a dönüşüm için.
{{% blocks/products/pf/feature-page-code h3="Excel için PHP Kodu PDF ve Web Formatları" %}}

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

{{% blocks/products/pf/feature-page-section h2="PHP kullanarak JSON\'i Excel\'e ve Excel\'i JSON\'e dönüştürün" %}}
PHP geliştiricileri JSON dosyalarını yalnızca birkaç satır kodla kolayca yükleyebilir ve Excel'e dönüştürebilir. Benzer şekilde Excel verileri JSON verisine aktarılabilir.
{{% blocks/products/pf/feature-page-code h3="JSON\'in Excel\'e Dönüştürülmesi için PHP Kodu" %}}

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

{{% blocks/products/pf/feature-page-code h3="Excel için PHP Kodunu JSON\'e Dönüştürme" %}}

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

{{% blocks/products/pf/feature-page-section h2="PHP Kullanarak Excel Çalışma Sayfalarını JPG, BMP, PNG ve GIF\'e Dönüştürme" %}}
 Bir Excel dosyasının her çalışma sayfası farklı görüntü formatlarına dönüştürülebilir.[Görüntü Veya Yazdırma Seçenekleri](https://reference.aspose.com/cells/php/aspose.cells/ImageOrPrintOptions/) .setImageFormat görüntü formatını ayarlamak için.
{{% blocks/products/pf/feature-page-code h3="Excel\'den Görüntüye Dönüştürme için PHP Kodu" %}}

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

{{% blocks/products/pf/feature-page-section h2="PHP Kullanarak Excel\'i Word\'e ve PowerPoint\'e Dönüştürme" %}}
Kullanırken herhangi bir elektronik tabloyu yükleyip Word DOCX & PowerPoint PPTX dosyalarına dönüştürmek mümkündür.[DocxSaveOptions](https://reference.aspose.com/cells/php/aspose.cells/DocxSaveOptions/) & [PptxSaveOptions](https://reference.aspose.com/cells/php/aspose.cells/PptxSaveOptions/) Aşağıda gösterildiği gibi sınıflar.
{{% blocks/products/pf/feature-page-code h3="Excel\'den Word\'e ve PowerPoint Dönüşümü için PHP Kodu" %}}
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
