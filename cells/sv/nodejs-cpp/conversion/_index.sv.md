---
title: Microsoft Excel-filkonvertering med Node.js via C++
description: Aspose.Cells for Node.js via C++-biblioteket. Konvertera EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL och fler format med bara några rader Node.js via C++-kod.
keywords: [Node.js via C++ Aspose.Cells., excel to pdf., json to excel., excel to json., csv to json., json to html., xml to excel and Convert files between various formats in Node.js via C++]
---
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Konvertering av Excel-format via Node.js via C++" h2="Importera och exportera Excel-filer som kalkylblad, webb, bild och format med fast layout" >}}

{{% blocks/products/pf/feature-page-summary %}}
Node.js via C++ Excel Library snabbar upp kalkylprogramsprogrammering och konverteringsprocesser samtidigt som det stöder populära format inklusive XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Det gör det också möjligt att exportera Excel-filer till PDF, XPS, HTML, MHTML, vanlig text och populära bildformat som TIFF, JPG, PNG, BMP och SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Konvertera Excel till XLSX, ODS, SXC och FODS med Node.js via C++" %}}
 Interkonvertering av kalkylarksformat kräver bara att ett kalkylblad laddas med en instans av[Arbetsbok](https://reference.aspose.com/cells/nodejs-cpp/workbook/) och spara tillbaka i önskat format samtidigt som du väljer lämpligt värde från[Sparaformat](https://reference.aspose.com/cells/nodejs-cpp/saveformat/) uppräkning.
{{% blocks/products/pf/feature-page-code h3="Node.js via C++-kod för konvertering av Excel-filformat" %}}

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


{{% blocks/products/pf/feature-page-section h2="Konvertera Excel till PDF, XPS, HTML och MD med Node.js via C++" %}}
 Specialiserade klasser finns tillgängliga för att styra konverteringsprocessen för specifika utdataformat som t.ex[PDFSparaAlternativ](https://reference.aspose.com/cells/nodejs-cpp/pdfsaveoptions/)för att exportera Excel-filer som PDF,[XpsSaveAlternativ](https://reference.aspose.com/cells/nodejs-cpp/xpssaveoptions/) för Excel till XPS konvertering,[HtmlSparaalternativ](https://reference.aspose.com/cells/nodejs-cpp/htmlsaveoptions/) för att återge Excel som HTML och[Sparalternativ för nedsättning](https://reference.aspose.com/cells/nodejs-cpp/markdownsaveoptions/) för konvertering från Excel till Markdown.
{{% blocks/products/pf/feature-page-code h3="Node.js via C++ Kod för Excel till PDF och webbformat" %}}

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

{{% blocks/products/pf/feature-page-section h2="Konvertera JSON till Excel och Excel till JSON med Node.js via C++" %}}
Node.js-utvecklare kan enkelt ladda och konvertera JSON-filer till Excel med bara några få rader kod. På samma sätt kan Excel-data exporteras till JSON-data.
{{% blocks/products/pf/feature-page-code h3="Node.js via C++-kod för konvertering från JSON till Excel" %}}

```js
const AsposeCells = require("aspose.cells.node");

// Load your source json file
var workbook = new AsposeCells.Workbook("Data.json");

//save file to xlsx format
workbook.save("output.xlsx");

```

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Node.js via C++-kod för konvertering från Excel till JSON" %}}

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

{{% blocks/products/pf/feature-page-section h2="Konvertera Excel-kalkylblad till JPG, BMP, PNG och GIF med Node.js via C++" %}}
 Varje kalkylblad i en Excel-fil kan konverteras till olika bildformat, ring[BildEllerUtskriftsalternativ](https://reference.aspose.com/cells/nodejs-cpp/imageorprintoptions/) .setImageFormat för att ställa in bildformatet.
{{% blocks/products/pf/feature-page-code h3="Node.js via C++-kod för konvertering från Excel till bild" %}}

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

{{% blocks/products/pf/feature-page-section h2="Konvertera Excel till Word och PowerPoint med Node.js via C++" %}}
Det är möjligt att ladda vilket kalkylblad som helst och konvertera det till Word DOCX- och PowerPoint PPTX-filer medan du använder[DocxSaveAlternativ](https://reference.aspose.com/cells/nodejs-cpp/docxsaveoptions/) & [PptxSparaalternativ](https://reference.aspose.com/cells/nodejs-cpp/pptxsaveoptions/) klasser som visas nedan.
{{% blocks/products/pf/feature-page-code h3="PHP-kod för Excel till Word & PowerPoint konvertering" %}}
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
