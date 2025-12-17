---
title: Microsoft Excel fájlkonverzió Node.js használatával via C++
description: Aspose.Cells for Node.js a C++ könyvtáron keresztül. EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL és további formátumok konvertálása mindössze néhány sor Node.js-sel a C++ kódon keresztül.
keywords: [Node.js via C++ Aspose.Cells., excel to pdf., json to excel., excel to json., csv to json., json to html., xml to excel and Convert files between various formats in Node.js via C++]
---
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel formátum konvertálása Node.js-en keresztül C++-en keresztül" h2="Excel-fájlok importálása és exportálása táblázat-, web-, kép- és rögzített elrendezésű formátumokba" >}}

{{% blocks/products/pf/feature-page-summary %}}
A Node.js a C++ Excel Library-n keresztül felgyorsítja a táblázatkezelő programozási és konvertálási folyamatokat, miközben támogatja a népszerű formátumokat, beleértve a XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS-et. Lehetővé teszi Excel fájlok exportálását PDF, XPS, HTML, MHTML, sima szöveg formátumba, valamint népszerű képformátumokba, például TIFF, JPG, PNG, BMP és SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel konvertálása XLSX, ODS, SXC és FODS formátumúra Node.js használatával C++-en keresztül" %}}
 A táblázatos formátumok közötti konvertáláshoz csak egy példányt tartalmazó táblázatot kell betölteni[Munkafüzet](https://reference.aspose.com/cells/nodejs-cpp/workbook/) és visszamenti a kívánt formátumba, miközben kiválasztja a megfelelő értéket[Mentési formátum](https://reference.aspose.com/cells/nodejs-cpp/saveformat/) felsorolás.
{{% blocks/products/pf/feature-page-code h3="Node.js a C++ kódon keresztül az Excel fájlformátum-konverzióhoz" %}}

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


{{% blocks/products/pf/feature-page-section h2="Excel konvertálása PDF, XPS, HTML és MD formátumúra Node.js használatával C++-en keresztül" %}}
 Speciális osztályok állnak rendelkezésre az átalakítási folyamat vezérlésére meghatározott kimeneti formátumokhoz, mint pl[PDF mentési beállításai](https://reference.aspose.com/cells/nodejs-cpp/pdfsaveoptions/)Excel-fájlok exportálásához PDF-es számként,[XPS mentési beállítások](https://reference.aspose.com/cells/nodejs-cpp/xpssaveoptions/) az Excelből XPS-re való átalakításhoz,[HTML mentési beállítások](https://reference.aspose.com/cells/nodejs-cpp/htmlsaveoptions/) hogy az Excel HTML-ként jelenjen meg, és[MarkdownMentésiBeállítások](https://reference.aspose.com/cells/nodejs-cpp/markdownsaveoptions/) az Excelből Markdown konvertáláshoz.
{{% blocks/products/pf/feature-page-code h3="Node.js a C++ kódon keresztül Excelhez PDF-re és webes formátumokhoz" %}}

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

{{% blocks/products/pf/feature-page-section h2="JSON konvertálása Excelbe és Excelből JSON-be Node.js használatával C++-en keresztül" %}}
A Node.js fejlesztők könnyedén betölthetnek és konvertálhatnak JSON fájlokat Excelbe mindössze néhány sor kóddal. Hasonlóképpen, az Excel adatok exportálhatók JSON adatokká.
{{% blocks/products/pf/feature-page-code h3="Node.js a C++ kódon keresztül a JSON Excelbe konvertálásához" %}}

```js
const AsposeCells = require("aspose.cells.node");

// Load your source json file
var workbook = new AsposeCells.Workbook("Data.json");

//save file to xlsx format
workbook.save("output.xlsx");

```

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Node.js a C++ kódon keresztül az Excel JSON-re konvertálásához" %}}

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

{{% blocks/products/pf/feature-page-section h2="Excel munkalapok konvertálása JPG, BMP, PNG és GIF formátumba Node.js használatával a C++-en keresztül" %}}
 Egy Excel-fájl minden munkalapja konvertálható különböző képformátumokba, hívja[Kép- vagy nyomtatási beállítások](https://reference.aspose.com/cells/nodejs-cpp/imageorprintoptions/) .setImageFormat a képformátum beállításához.
{{% blocks/products/pf/feature-page-code h3="Node.js kód a C++-es számon Excelből képfájlokká konvertálásához" %}}

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

{{% blocks/products/pf/feature-page-section h2="Excel konvertálása Wordbe és PowerPoint Node.js használatával a C++-es címen keresztül" %}}
Lehetőség van bármilyen táblázat betöltésére és Word DOCX és PowerPoint PPTX fájlokká konvertálására használat közben.[DocxSaveOptions](https://reference.aspose.com/cells/nodejs-cpp/docxsaveoptions/) & [PptxMentésiBeállítások](https://reference.aspose.com/cells/nodejs-cpp/pptxsaveoptions/) osztályok alább látható módon.
{{% blocks/products/pf/feature-page-code h3="PHP kód az Excel Wordbe és a PowerPoint konvertáláshoz" %}}
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
