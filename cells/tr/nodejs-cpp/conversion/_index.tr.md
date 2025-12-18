---
title: Microsoft Node.js Kullanarak Excel Dosyası Dönüştürme (C++ aracılığıyla)
description: Aspose.Cells for Node.js, C++ kütüphanesi aracılığıyla. EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL ve daha birçok formatı, C++ koduyla sadece birkaç satır Node.js kodu kullanarak dönüştürün.
keywords: [Node.js via C++ Aspose.Cells., excel to pdf., json to excel., excel to json., csv to json., json to html., xml to excel and Convert files between various formats in Node.js via C++]
---
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Node.js aracılığıyla Excel Format Dönüştürme (C++ üzerinden)" h2="Excel dosyalarını elektronik tablo, web, resim ve sabit düzen formatlarında içe ve dışa aktarın" >}}

{{% blocks/products/pf/feature-page-summary %}}
C++ Excel Kütüphanesi aracılığıyla Node.js, XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS gibi popüler formatları desteklerken, elektronik tablo programlama ve dönüştürme süreçlerini hızlandırır. Ayrıca Excel dosyalarını PDF, XPS, HTML, MHTML, Düz Metin ve TIFF, JPG, PNG, BMP gibi popüler resim formatlarına dışa aktarmaya olanak tanır. SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel dosyasını XLSX, ODS, SXC ve FODS numaralarına Node.js kullanarak C++ aracılığıyla dönüştürün." %}}
 Elektronik tablo formatının karşılıklı dönüştürülmesi yalnızca aşağıdaki örneğin bulunduğu bir elektronik tablonun yüklenmesini gerektirir:[Çalışma kitabı](https://reference.aspose.com/cells/nodejs-cpp/workbook/) ve uygun değeri seçerken istenilen formatta tekrar kaydetme[Formatı Kaydet](https://reference.aspose.com/cells/nodejs-cpp/saveformat/) numaralandırma.
{{% blocks/products/pf/feature-page-code h3="Node.js aracılığıyla C++ numaralı kod ile Excel Dosya Formatı Dönüştürme" %}}

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


{{% blocks/products/pf/feature-page-section h2="Excel dosyasını PDF, XPS, HTML ve MD\'ye Node.js kullanarak C++ aracılığıyla dönüştürün." %}}
 Belirli çıktı formatları için dönüştürme sürecini kontrol etmek amacıyla özel sınıflar mevcuttur:[PdfKaydetmeSeçenekleri](https://reference.aspose.com/cells/nodejs-cpp/pdfsaveoptions/)Excel dosyalarını PDF olarak dışa aktarmak için,[XpsKaydetSeçenekleri](https://reference.aspose.com/cells/nodejs-cpp/xpssaveoptions/) Excel'den XPS'e dönüşüm için,[HtmlKaydetSeçenekleri](https://reference.aspose.com/cells/nodejs-cpp/htmlsaveoptions/) Excel'i HTML olarak işlemek ve[İşaretlemeKaydetSeçenekleri](https://reference.aspose.com/cells/nodejs-cpp/markdownsaveoptions/) Excel'den Markdown'a dönüşüm için.
{{% blocks/products/pf/feature-page-code h3="Node.js, C++ aracılığıyla Excel için PDF ve Web Formatları için Kod" %}}

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

{{% blocks/products/pf/feature-page-section h2="JSON\'i Excel\'e ve Excel\'i JSON\'e Node.js kullanarak C++ üzerinden dönüştürün." %}}
Node.js geliştiricileri, JSON dosyalarını birkaç satır kodla kolayca yükleyip Excel'e dönüştürebilirler. Benzer şekilde, Excel verileri de JSON verilerine aktarılabilir.
{{% blocks/products/pf/feature-page-code h3="JSON kodunun Excel\'e dönüştürülmesi için Node.js aracılığıyla C++" %}}

```js
const AsposeCells = require("aspose.cells.node");

// Load your source json file
var workbook = new AsposeCells.Workbook("Data.json");

//save file to xlsx format
workbook.save("output.xlsx");

```

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Node.js aracılığıyla C++ Kodundan Excel\'den JSON Koduna Dönüştürme" %}}

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

{{% blocks/products/pf/feature-page-section h2="Excel çalışma sayfalarını Node.js kullanarak JPG\'ye dönüştürme, BMP, PNG ve GIF (C++ aracılığıyla)." %}}
 Bir Excel dosyasının her çalışma sayfası farklı görüntü formatlarına dönüştürülebilir.[Görüntü Veya Yazdırma Seçenekleri](https://reference.aspose.com/cells/nodejs-cpp/imageorprintoptions/) .setImageFormat görüntü formatını ayarlamak için.
{{% blocks/products/pf/feature-page-code h3="Node.js aracılığıyla C++ numaralı kod ile Excel\'den Görüntüye Dönüştürme" %}}

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

{{% blocks/products/pf/feature-page-section h2="Excel\'i Word\'e Dönüştürme ve PowerPoint Node.js Kullanarak C++" %}}
Kullanırken herhangi bir elektronik tabloyu yükleyip Word DOCX & PowerPoint PPTX dosyalarına dönüştürmek mümkündür.[DocxKaydetSeçenekleri](https://reference.aspose.com/cells/nodejs-cpp/docxsaveoptions/) & [PptxKaydetSeçenekleri](https://reference.aspose.com/cells/nodejs-cpp/pptxsaveoptions/) Aşağıda gösterildiği gibi sınıflar.
{{% blocks/products/pf/feature-page-code h3="Excel\'den Word\'e ve PowerPoint Dönüşümü için PHP Kodu" %}}
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
