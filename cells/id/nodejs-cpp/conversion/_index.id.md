---
title: Microsoft Konversi File Excel Menggunakan Node.js melalui C++
description: Aspose.Cells for Node.js melalui pustaka C++. Konversi EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL dan format lainnya hanya dengan beberapa baris kode Node.js melalui kode C++.
keywords: [Node.js via C++ Aspose.Cells., excel to pdf., json to excel., excel to json., csv to json., json to html., xml to excel and Convert files between various formats in Node.js via C++]
---
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/i18n/feature-page-header h1="Konversi Format Excel melalui Node.js via C++" h2="Impor & ekspor file Excel sebagai format spreadsheet, web, gambar, dan tata letak tetap" >}}

{{% blocks/products/pf/feature-page-summary %}}
Node.js melalui pustaka Excel C++ mempercepat proses pemrograman dan konversi spreadsheet sambil mendukung format populer termasuk XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Pustaka ini juga memungkinkan ekspor file Excel ke PDF, XPS, HTML, MHTML, Teks Biasa, dan format gambar populer seperti TIFF, JPG, PNG, BMP, dan SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Konversi Excel ke XLSX, ODS, SXC & FODS Menggunakan Node.js melalui C++" %}}
 Antar-konversi format spreadsheet hanya memerlukan pemuatan spreadsheet dengan sebuah instance[Buku Kerja](https://reference.aspose.com/cells/nodejs-cpp/workbook/) dan menyimpan kembali dalam format yang diinginkan sambil memilih nilai yang sesuai[SimpanFormat](https://reference.aspose.com/cells/nodejs-cpp/saveformat/) pencacahan.
{{% blocks/products/pf/feature-page-code h3="Node.js melalui Kode C++ untuk Konversi Format File Excel" %}}

```js
const AsposeCells = require("aspose.cells.node");

// load the template file
var workbook = new AsposeCells.Workbook("input.xlsx");

// save as XLSX, ODS, SXC & FODS formats
workbook.save("output.xlsx", AsposeCells.SaveFormat.Xlsx);
workbook.save("output.ods", AsposeCells.SaveFormat.Ods);
workbook.save("output.sxc", AsposeCells.SaveFormat.Sxc);
workbook.save("output.fods", AsposeCells.SaveFormat.Fods);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Konversi Excel ke PDF, XPS, HTML & MD Menggunakan Node.js melalui C++" %}}
 Kelas khusus tersedia untuk mengontrol proses konversi untuk format keluaran tertentu seperti[OpsiSimpan Pdf](https://reference.aspose.com/cells/nodejs-cpp/pdfsaveoptions/)untuk mengekspor file Excel sebagai PDF,[Opsi Simpan XPS](https://reference.aspose.com/cells/nodejs-cpp/xpssaveoptions/) untuk konversi Excel ke XPS,[HtmlSimpanOpsi](https://reference.aspose.com/cells/nodejs-cpp/htmlsaveoptions/) untuk merender Excel sebagai HTML dan[Penurunan HargaSimpanOpsi](https://reference.aspose.com/cells/nodejs-cpp/markdownsaveoptions/) untuk konversi Excel ke Penurunan Harga.
{{% blocks/products/pf/feature-page-code h3="Node.js melalui C++ Kode untuk Excel ke PDF dan Format Web" %}}

```js
const AsposeCells = require("aspose.cells.node");

// load the template file
var workbook = new AsposeCells.Workbook("input.xlsx");

// save Excel in PDF_A_1_B format
var pdfOptions = new AsposeCells.PdfSaveOptions();
pdfOptions.setCompliance(AsposeCells.PdfCompliance.PdfA1b);
workbook.save("output.pdf", pdfOptions);

// save Excel in XPS with 1 page per worksheet
var xpsOptions = new AsposeCells.XpsSaveOptions();
xpsOptions.setOnePagePerSheet(true);
workbook.save("output.xps", xpsOptions);

// save Excel in HTML with images as Base64
var htmlOptions = new AsposeCells.HtmlSaveOptions();
htmlOptions.setExportImagesAsBase64(true);
workbook.save("output.html", htmlOptions);

// save Excel in Markdown (MD) while retaining cell formatting
var mdOptions = new AsposeCells.MarkdownSaveOptions();
mdOptions.setFormatStrategy(AsposeCells.CellValueFormatStrategy.CellStyle);
workbook.save("output.md", mdOptions);
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="Konversi JSON ke Excel & Excel ke JSON Menggunakan Node.js melalui C++" %}}
Pengembang Node.js dapat dengan mudah memuat & mengkonversi file JSON ke Excel hanya dengan beberapa baris kode. Demikian pula, data Excel dapat diekspor ke data JSON.
{{% blocks/products/pf/feature-page-code h3="Node.js melalui Kode C++ untuk Konversi JSON ke Excel" %}}

```js
const AsposeCells = require("aspose.cells.node");

// Load your source json file
var workbook = new AsposeCells.Workbook("Data.json");

//save file to xlsx format
workbook.save("output.xlsx");

```

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Node.js melalui Kode C++ untuk Konversi Excel ke JSON" %}}

```js
const AsposeCells = require("aspose.cells.node");

// Load your source xlsx file
var workbook = new AsposeCells.Workbook("input.xlsx");

// save file to json format
workbook.save("Data.json");
```

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Konversi Lembar Kerja Excel ke JPG, BMP, PNG & GIF Menggunakan Node.js melalui C++" %}}
 Setiap lembar kerja file Excel dapat dikonversi ke format gambar yang berbeda, sebut saja[Opsi GambarAtauCetak](https://reference.aspose.com/cells/nodejs-cpp/imageorprintoptions/) .setImageFormat untuk mengatur format gambar.
{{% blocks/products/pf/feature-page-code h3="Node.js melalui kode C++ untuk konversi Excel ke gambar." %}}

```js
const AsposeCells = require("aspose.cells.node");

// load template spreadsheet
var workbook = new AsposeCells.Workbook("template.xlsx");

// create & set an instance of ImageOrPrintOptions
var options = new AsposeCells.ImageOrPrintOptions();
// set output image type
options.setImageType(AsposeCells.ImageType.Png);
// create SheetRender for first worksheet in the collection
var sheet = workbook.getWorksheets().get(0);
var sr = new AsposeCells.SheetRender(sheet, options);
// render worksheet to image
sr.toImage(0, "output.jpg");
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Konversi Excel ke Word & PowerPoint Menggunakan Node.js melalui C++" %}}
Dimungkinkan untuk memuat spreadsheet apa pun dan mengonversinya menjadi file Word DOCX & PowerPoint PPTX saat menggunakan[Opsi DocxSave](https://reference.aspose.com/cells/nodejs-cpp/docxsaveoptions/) & [PptxSimpanOpsi](https://reference.aspose.com/cells/nodejs-cpp/pptxsaveoptions/) kelas seperti yang ditunjukkan di bawah ini.
{{% blocks/products/pf/feature-page-code h3="Kode PHP untuk Konversi Excel ke Word & PowerPoint" %}}
```js
const AsposeCells = require("aspose.cells.node");

// load template spreadsheet
var workbook = new AsposeCells.Workbook("template.xlsx");

// save spreadsheet as DOCX
var docxOptions = new AsposeCells.DocxSaveOptions();
workbook.save("output.docx", docxOptions);

// save spreadsheet as PPTX
var pptxOptions = new AsposeCells.PptxSaveOptions();
workbook.save("output.pptx", pptxOptions)
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xls-to-docx xlsx-to-docx xlsb-to-docx xlsm-to-docx html-to-docx mhtml-to-docx ods-to-docx tsv-to-docx csv-to-docx json-to-docx numbers-to-docx prn-to-docx xlt-to-docx xltx-to-docx xltm-to-docx ots-to-docx sxc-to-docx png-to-docx jpg-to-docx txt-to-docx xls-to-pptx xlsx-to-pptx xlsb-to-pptx xlsm-to-pptx html-to-pptx mhtml-to-pptx ods-to-pptx tsv-to-pptx csv-to-pptx json-to-pptx numbers-to-pptx prn-to-pptx xlt-to-pptx xltx-to-pptx xltm-to-pptx ots-to-pptx sxc-to-pptx png-to-pptx jpg-to-pptx txt-to-pptx" >}}
