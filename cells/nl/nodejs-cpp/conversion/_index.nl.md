---
title: Microsoft Excel-bestandconversie met Node.js via C++
description: Converteer EXCEL, XML, SQL en andere formaten met slechts een paar regels Node.js-code via de bibliotheek met behulp van ...
keywords: [Node.js via C++ Aspose.Cells., excel to pdf., json to excel., excel to json., csv to json., json to html., xml to excel and Convert files between various formats in Node.js via C++]
---
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel-formaatconversie via Node.js via C++" h2="Importeer en exporteer Excel-bestanden als spreadsheet-, web-, afbeeldings- en vaste lay-outformaten" >}}

{{% blocks/products/pf/feature-page-summary %}}
De Node.js-bibliotheek C++ versnelt het programmeren en converteren van spreadsheets en ondersteunt populaire formaten zoals XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML en ODS. Het is ook mogelijk om Excel-bestanden te exporteren naar PDF, XPS, HTML, MHTML, platte tekst en populaire afbeeldingsformaten zoals TIFF, JPG, PNG en BMP. SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Converteer Excel naar XLSX, ODS, SXC en FODS met behulp van Node.js via C++" %}}
 Voor de onderlinge conversie van het spreadsheetformaat is alleen het laden van een spreadsheet nodig met een exemplaar van[Werkboek](https://reference.aspose.com/cells/nodejs-cpp/workbook/) en weer opslaan in het gewenste formaat terwijl u de juiste waarde selecteert[Formaat opslaan](https://reference.aspose.com/cells/nodejs-cpp/saveformat/) opsomming.
{{% blocks/products/pf/feature-page-code h3="Node.js via C++ Code voor conversie van Excel-bestandsindeling" %}}

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


{{% blocks/products/pf/feature-page-section h2="Converteer Excel naar PDF, XPS, HTML en MD met behulp van Node.js via C++" %}}
 Er zijn gespecialiseerde klassen beschikbaar om het conversieproces voor specifieke uitvoerformaten zoals[PdfSaveOpties](https://reference.aspose.com/cells/nodejs-cpp/pdfsaveoptions/)om Excel-bestanden te exporteren als PDF,[XpsSaveOpties](https://reference.aspose.com/cells/nodejs-cpp/xpssaveoptions/) voor conversie van Excel naar XPS,[HtmlSaveOptions](https://reference.aspose.com/cells/nodejs-cpp/htmlsaveoptions/) om Excel weer te geven als HTML en[MarkdownSaveOpties](https://reference.aspose.com/cells/nodejs-cpp/markdownsaveoptions/) voor conversie van Excel naar Markdown.
{{% blocks/products/pf/feature-page-code h3="Node.js via C++ Code voor Excel naar PDF en webformaten" %}}

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

{{% blocks/products/pf/feature-page-section h2="Converteer JSON naar Excel en Excel naar JSON met behulp van Node.js via C++" %}}
Node.js-ontwikkelaars kunnen eenvoudig JSON-bestanden laden en converteren naar Excel met slechts een paar regels code. Op dezelfde manier kunnen Excel-gegevens worden geëxporteerd naar JSON-gegevens.
{{% blocks/products/pf/feature-page-code h3="Node.js via C++ Code voor JSON naar Excel-conversie" %}}

```js
const AsposeCells = require("aspose.cells.node");

// Load your source json file
var workbook = new AsposeCells.Workbook("Data.json");

//save file to xlsx format
workbook.save("output.xlsx");

```

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Node.js via C++ Code voor Excel naar JSON conversie" %}}

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

{{% blocks/products/pf/feature-page-section h2="Excel-werkbladen converteren naar JPG, BMP, PNG & GIF met Node.js via C++" %}}
 Elk werkblad van een Excel-bestand kan worden omgezet naar verschillende afbeeldingsformaten, bel[AfbeeldingOfAfdrukopties](https://reference.aspose.com/cells/nodejs-cpp/imageorprintoptions/) .setImageFormat om het afbeeldingsformaat in te stellen.
{{% blocks/products/pf/feature-page-code h3="Node.js-code via C++ voor het converteren van Excel-bestanden naar afbeeldingen." %}}

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

{{% blocks/products/pf/feature-page-section h2="Excel converteren naar Word & PowerPoint met Node.js via C++" %}}
Het is mogelijk om elk spreadsheet te laden en te converteren naar Word DOCX & PowerPoint PPTX bestanden tijdens het gebruik[DocxSaveOptions](https://reference.aspose.com/cells/nodejs-cpp/docxsaveoptions/) & [PptxSaveOpties](https://reference.aspose.com/cells/nodejs-cpp/pptxsaveoptions/) klassen zoals hieronder gedemonstreerd.
{{% blocks/products/pf/feature-page-code h3="PHP-code voor Excel naar Word en PowerPoint-conversie" %}}
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
