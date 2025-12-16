---
title: Microsoft Konverze souborů Excel pomocí Node.js přes C++
description: Aspose.Cells for Node.js přes knihovnu C++. Převeďte EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL a další formáty pomocí několika řádků kódu Node.js pomocí knihovny C++.
keywords: [Node.js via C++ Aspose.Cells., excel to pdf., json to excel., excel to json., csv to json., json to html., xml to excel and Convert files between various formats in Node.js via C++]
---
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Konverze formátu Excelu pomocí Node.js přes C++" h2="Importujte a exportujte soubory Excel jako tabulkový procesor, web, obrázky a formáty s pevným rozložením" >}}

{{% blocks/products/pf/feature-page-summary %}}
Node.js přes knihovnu Excelu C++ zrychluje programování a konverze tabulek a zároveň podporuje populární formáty včetně XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Umožňuje také exportovat soubory Excelu do formátů PDF, XPS, HTML, MHTML, prostého textu a oblíbených obrazových formátů, jako například TIFF, JPG, PNG, BMP a SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Převod Excelu na XLSX, ODS, SXC a FODS pomocí Node.js přes C++" %}}
 Vzájemná konverze formátu tabulky vyžaduje pouze načtení tabulky s instancí[pracovní sešit](https://reference.aspose.com/cells/nodejs-cpp/workbook/) a uložení zpět v požadovaném formátu při výběru vhodné hodnoty z[UložitFormát](https://reference.aspose.com/cells/nodejs-cpp/saveformat/) výčet.
{{% blocks/products/pf/feature-page-code h3="Node.js přes kód C++ pro převod formátu souboru Excel" %}}

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


{{% blocks/products/pf/feature-page-section h2="Převeďte Excel na PDF, XPS, HTML a MD pomocí Node.js přes C++" %}}
 K dispozici jsou specializované třídy pro řízení procesu převodu pro konkrétní výstupní formáty, jako je např[Možnosti PdfSave](https://reference.aspose.com/cells/nodejs-cpp/pdfsaveoptions/)exportovat soubory Excel jako PDF,[Možnosti ukládání Xps](https://reference.aspose.com/cells/nodejs-cpp/xpssaveoptions/) pro převod Excel na XPS,[Možnosti uložení HTML](https://reference.aspose.com/cells/nodejs-cpp/htmlsaveoptions/) vykreslit Excel jako HTML a[Možnosti ukládání Markdownu](https://reference.aspose.com/cells/nodejs-cpp/markdownsaveoptions/) pro převod Excel na Markdown.
{{% blocks/products/pf/feature-page-code h3="Node.js přes C++ Kód pro Excel na PDF a webové formáty" %}}

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

{{% blocks/products/pf/feature-page-section h2="Převod JSON do Excelu a Excelu na JSON pomocí Node.js přes C++" %}}
Vývojáři Node.js mohou snadno načíst a převést soubory JSON do Excelu pomocí několika řádků kódu. Podobně lze data z Excelu exportovat do formátu JSON.
{{% blocks/products/pf/feature-page-code h3="Node.js přes kód C++ pro konverzi JSON do Excelu" %}}

```js
const AsposeCells = require("aspose.cells.node");

// Load your source json file
var workbook = new AsposeCells.Workbook("Data.json");

//save file to xlsx format
workbook.save("output.xlsx");

```

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Node.js přes kód C++ pro konverzi Excelu na JSON" %}}

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

{{% blocks/products/pf/feature-page-section h2="Převod excelových listů do formátu JPG, BMP, PNG a GIF pomocí Node.js přes C++" %}}
 Každý list souboru aplikace Excel lze převést do různých formátů obrázků, volejte[MožnostiObrázkuNeboTisk](https://reference.aspose.com/cells/nodejs-cpp/imageorprintoptions/) .setImageFormat pro nastavení formátu obrázku.
{{% blocks/products/pf/feature-page-code h3="Node.js přes C++ Kód pro převod Excelu do obrázku" %}}

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

{{% blocks/products/pf/feature-page-section h2="Převod Excelu do Wordu a PowerPoint pomocí Node.js přes C++" %}}
Je možné načíst jakoukoli tabulku a převést ji na soubory Word DOCX a PowerPoint PPTX při používání[Možnosti ukládání docxu](https://reference.aspose.com/cells/nodejs-cpp/docxsaveoptions/) & [Možnosti PptxSave](https://reference.aspose.com/cells/nodejs-cpp/pptxsaveoptions/) třídy, jak je ukázáno níže.
{{% blocks/products/pf/feature-page-code h3="PHP kód pro Excel do Wordu a převod PowerPoint" %}}
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
