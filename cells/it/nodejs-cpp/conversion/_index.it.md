---
title: Microsoft Conversione di file Excel tramite Node.js tramite C++
description: Aspose.Cells for Node.js tramite la libreria C++. Converti EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL e altri formati con poche righe di Node.js tramite il codice C++.
keywords: [Node.js via C++ Aspose.Cells., excel to pdf., json to excel., excel to json., csv to json., json to html., xml to excel and Convert files between various formats in Node.js via C++]
---
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Conversione del formato Excel tramite Node.js tramite C++" h2="Importa ed esporta file Excel come formati di fogli di calcolo, Web, immagini e layout fisso" >}}

{{% blocks/products/pf/feature-page-summary %}}
Node.js tramite la libreria Excel C++ velocizza la programmazione dei fogli di calcolo e i processi di conversione supportando formati popolari tra cui XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Consente inoltre di esportare file Excel in PDF, XPS, HTML, MHTML, testo normale e formati di immagine popolari come TIFF, JPG, PNG, BMP e SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Converti Excel in XLSX, ODS, SXC e FODS utilizzando Node.js tramite C++" %}}
 L'interconversione del formato del foglio di calcolo richiede solo il caricamento di un foglio di calcolo con un'istanza di[Cartella di lavoro](https://reference.aspose.com/cells/nodejs-cpp/workbook/) e salvare nuovamente nel formato desiderato selezionando il valore appropriato da[Salva formato](https://reference.aspose.com/cells/nodejs-cpp/saveformat/) enumerazione.
{{% blocks/products/pf/feature-page-code h3="Node.js tramite codice C++ per la conversione del formato file Excel" %}}

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


{{% blocks/products/pf/feature-page-section h2="Converti Excel in PDF, XPS, HTML e MD utilizzando Node.js tramite C++" %}}
 Sono disponibili classi specializzate per controllare il processo di conversione per formati di output specifici come[Opzioni di salvataggio PDF](https://reference.aspose.com/cells/nodejs-cpp/pdfsaveoptions/)per esportare file Excel come PDF,[Opzioni di salvataggio Xps](https://reference.aspose.com/cells/nodejs-cpp/xpssaveoptions/) per la conversione da Excel a XPS,[Opzioni di salvataggio HTML](https://reference.aspose.com/cells/nodejs-cpp/htmlsaveoptions/) per rendere Excel come HTML e[MarkdownSaveOptions](https://reference.aspose.com/cells/nodejs-cpp/markdownsaveoptions/) per la conversione da Excel a Markdown.
{{% blocks/products/pf/feature-page-code h3="Node.js tramite codice C++ per Excel a PDF e formati Web" %}}

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

{{% blocks/products/pf/feature-page-section h2="Converti JSON in Excel e Excel in JSON utilizzando Node.js tramite C++" %}}
Gli sviluppatori Node.js possono caricare e convertire facilmente i file JSON in Excel in poche righe di codice. Allo stesso modo, i dati Excel possono essere esportati in formato JSON.
{{% blocks/products/pf/feature-page-code h3="Node.js tramite codice C++ per la conversione da JSON a Excel" %}}

```js
const AsposeCells = require("aspose.cells.node");

// Load your source json file
var workbook = new AsposeCells.Workbook("Data.json");

//save file to xlsx format
workbook.save("output.xlsx");

```

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Node.js tramite codice C++ per la conversione da Excel a JSON" %}}

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

{{% blocks/products/pf/feature-page-section h2="Convertire fogli di lavoro Excel in JPG, BMP, PNG e GIF utilizzando Node.js tramite C++" %}}
 Ogni foglio di lavoro di un file Excel può essere convertito in diversi formati di immagine, call[OpzioniImmagineOrStampa](https://reference.aspose.com/cells/nodejs-cpp/imageorprintoptions/) .setImageFormat per impostare il formato dell'immagine.
{{% blocks/products/pf/feature-page-code h3="Node.js tramite codice C++ per la conversione da Excel a immagine" %}}

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

{{% blocks/products/pf/feature-page-section h2="Converti Excel in Word e PowerPoint utilizzando Node.js tramite C++" %}}
È possibile caricare qualsiasi foglio di calcolo e convertirlo nei file Word DOCX e PowerPoint PPTX durante l'utilizzo[Opzioni di salvataggio Docx](https://reference.aspose.com/cells/nodejs-cpp/docxsaveoptions/) & [Opzioni di salvataggio Pptx](https://reference.aspose.com/cells/nodejs-cpp/pptxsaveoptions/) classi come illustrato di seguito.
{{% blocks/products/pf/feature-page-code h3="Codice PHP per la conversione da Excel a Word e PowerPoint" %}}
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
