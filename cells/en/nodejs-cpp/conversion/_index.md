---
title: Microsoft Excel File Conversion Using Node.js via C++

description: Aspose.Cells for Node.js via C++ library. Convert EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL and more formats with just few lines of Node.js via C++ code.
keywords: [Node.js via C++ Aspose.Cells., excel to pdf., json to excel., excel to json., csv to json., json to html., xml to excel and Convert files between various formats in Node.js via C++]
---

{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel Format Conversion via Node.js via C++" h2="Import & export Excel files as spreadsheet, web, image and fixed-layout formats" >}}

{{% blocks/products/pf/feature-page-summary %}}
Node.js via C++ Excel Library speeds up spreadsheet programming and conversion processes while supporting popular formats including XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. It also allows to export Excel files to PDF, XPS, HTML, MHTML, Plain Text and popular image formats such as TIFF, JPG, PNG, BMP and SVG.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Convert Excel to XLSX, ODS, SXC & FODS Using Node.js via C++" %}}
Inter-conversion of spreadsheet format only requires loading a spreadsheet with an instance of [Workbook](https://reference.aspose.com/cells/nodejs-cpp/workbook/) and saving back in the desired format while selecting appropriate value from [SaveFormat](https://reference.aspose.com/cells/nodejs-cpp/saveformat/) enumeration.
{{% blocks/products/pf/feature-page-code h3="Node.js via C++ Code for Excel File Format Conversion" %}}

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
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section  h2="Convert Excel to PDF, XPS, HTML & MD Using Node.js via C++" %}}
Specialized classes are available to control the conversion process for specific output formats such as [PdfSaveOptions](https://reference.aspose.com/cells/nodejs-cpp/pdfsaveoptions/) to export Excel files as PDF, [XpsSaveOptions](https://reference.aspose.com/cells/nodejs-cpp/xpssaveoptions/) for Excel to XPS conversion, [HtmlSaveOptions](https://reference.aspose.com/cells/nodejs-cpp/htmlsaveoptions/) to render Excel as HTML and [MarkdownSaveOptions](https://reference.aspose.com/cells/nodejs-cpp/markdownsaveoptions/) for Excel to Markdown conversion. 
{{% blocks/products/pf/feature-page-code h3="Node.js via C++ Code for Excel to PDF and Web Formats" %}}

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
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert">}}

{{% blocks/products/pf/feature-page-section  h2="Convert JSON to Excel & Excel to JSON Using Node.js via C++" %}}
Node.js developers can easily load & convert JSON files to Excel in just a few lines of code. Similarly, Excel data can be exported to JSON data.
{{% blocks/products/pf/feature-page-code h3="Node.js via C++ Code for JSON to Excel Conversion" %}}

```js
const AsposeCells = require("aspose.cells.node");

// Load your source json file
var workbook = new AsposeCells.Workbook("Data.json");

//save file to xlsx format
workbook.save("output.xlsx");

```

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Node.js via C++ Code for Excel to JSON Conversion" %}}

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

{{% blocks/products/pf/feature-page-section  h2="Convert Excel Worksheets to JPG, BMP, PNG & GIF Using Node.js via C++" %}}
Each worksheet of an Excel file can be converted to different image formats, call [ImageOrPrintOptions](https://reference.aspose.com/cells/nodejs-cpp/imageorprintoptions/).setImageFormat to set the image format. 
{{% blocks/products/pf/feature-page-code h3="Node.js via C++ Code for Excel to Image Conversion" %}}

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

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering">}}

{{% blocks/products/pf/feature-page-section  h2="Convert Excel to Word & PowerPoint Using Node.js via C++" %}}
It is possible to load any spreadsheet and convert it to Word DOCX & PowerPoint PPTX files while using [DocxSaveOptions](https://reference.aspose.com/cells/nodejs-cpp/docxsaveoptions/) & [PptxSaveOptions](https://reference.aspose.com/cells/nodejs-cpp/pptxsaveoptions/) classes as demonstrated below.
{{% blocks/products/pf/feature-page-code h3="PHP Code for Excel to Word & PowerPoint Conversion" %}}
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
