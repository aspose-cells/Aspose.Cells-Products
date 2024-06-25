---
title: Microsoft Konversi File Excel Menggunakan PHP via Java
description: Aspose.Cells for PHP via Java perpustakaan. Konversi EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL dan format lainnya hanya dengan beberapa baris kode PHP.
keywords: [PHP Aspose.Cells., excel to pdf., json to excel., excel to json., csv to json., json to html., xml to excel and Convert files between various formats in PHP]
---
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header-php-java h1="Microsoft<sup>&reg;</sup> Konversi Format Excel melalui PHP" h2="Impor & ekspor file Excel sebagai format spreadsheet, web, gambar, dan tata letak tetap" >}}

{{% blocks/products/pf/feature-page-summary %}}
Perpustakaan PHP Excel mempercepat pemrograman spreadsheet dan proses konversi sambil mendukung format populer termasuk XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Ini juga memungkinkan untuk mengekspor file Excel ke PDF, XPS, HTML, MHTML, Biasa Teks dan format gambar populer seperti TIFF, JPG, PNG, BMP dan SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Konversi Excel ke XLSX, ODS, SXC & FODS Menggunakan PHP" %}}
 Antar-konversi format spreadsheet hanya memerlukan pemuatan spreadsheet dengan sebuah instance[Buku Kerja](https://reference.aspose.com/cells/php/aspose.cells/Workbook) dan menyimpan kembali dalam format yang diinginkan sambil memilih nilai yang sesuai[SimpanFormat](https://reference.aspose.com/cells/php/aspose.cells/SaveFormat) pencacahan.
{{% blocks/products/pf/feature-page-code h3="Kode PHP untuk Konversi Format File Excel" %}}

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


{{% blocks/products/pf/feature-page-section h2="Konversi Excel ke PDF, XPS, HTML & MD Menggunakan PHP" %}}
 Kelas khusus tersedia untuk mengontrol proses konversi untuk format keluaran tertentu seperti[OpsiSimpan Pdf](https://reference.aspose.com/cells/php/aspose.cells/PdfSaveOptions/)untuk mengekspor file Excel sebagai PDF,[XpsSaveOptions](https://reference.aspose.com/cells/php/aspose.cells/XpsSaveOptions/) untuk konversi Excel ke XPS,[HtmlSimpanOpsi](https://reference.aspose.com/cells/php/aspose.cells/HtmlSaveOptions/) untuk merender Excel sebagai HTML dan[Penurunan HargaSimpanOpsi](https://reference.aspose.com/cells/php/aspose.cells/MarkdownSaveOptions/) untuk konversi Excel ke Penurunan Harga.
{{% blocks/products/pf/feature-page-code h3="Kode PHP untuk Excel ke PDF dan Format Web" %}}

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

{{% blocks/products/pf/feature-page-section h2="Ubah JSON menjadi Excel & Excel menjadi JSON Menggunakan PHP" %}}
Pengembang PHP dapat dengan mudah memuat & mengonversi file JSON ke Excel hanya dalam beberapa baris kode. Demikian pula, data Excel dapat diekspor ke data JSON.
{{% blocks/products/pf/feature-page-code h3="Kode PHP untuk Konversi JSON ke Excel" %}}

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

{{% blocks/products/pf/feature-page-code h3="Kode PHP untuk Konversi Excel ke JSON" %}}

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

{{% blocks/products/pf/feature-page-section h2="Konversi Lembar Kerja Excel ke JPG, BMP, PNG & GIF Menggunakan PHP" %}}
 Setiap lembar kerja file Excel dapat dikonversi ke format gambar yang berbeda, sebut saja[Opsi GambarAtauCetak](https://reference.aspose.com/cells/php/aspose.cells/ImageOrPrintOptions/) .setImageFormat untuk mengatur format gambar.
{{% blocks/products/pf/feature-page-code h3="Kode PHP untuk Konversi Excel ke Gambar" %}}

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

{{% blocks/products/pf/feature-page-section h2="Konversi Excel ke Word & PowerPoint Menggunakan PHP" %}}
Dimungkinkan untuk memuat spreadsheet apa pun dan mengonversinya menjadi file Word DOCX & PowerPoint PPTX saat menggunakan[Opsi DocxSave](https://reference.aspose.com/cells/php/aspose.cells/DocxSaveOptions/) & [PptxSimpanOpsi](https://reference.aspose.com/cells/php/aspose.cells/PptxSaveOptions/) kelas seperti yang ditunjukkan di bawah ini.
{{% blocks/products/pf/feature-page-code h3="Kode PHP untuk Konversi Excel ke Word & PowerPoint" %}}
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
