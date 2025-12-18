---
title: Microsoft 使用 Node.js 進行 Excel 檔案轉換（透過 C++）
description: 透過 C++ 函式庫，轉換 EXCEL、JSON、PDF、XML、HTML、TXT、TSV、CSV、SQLSQL 等多種格式，幾行 Node.
keywords: [Node.js via C++ Aspose.Cells., excel to pdf., json to excel., excel to json., csv to json., json to html., xml to excel and Convert files between various formats in Node.js via C++]
---
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/i18n/feature-page-header h1="透過 Node.js 進行 Excel 格式轉換，使用 C++" h2="將 Excel 檔案匯入和匯出為電子表格、Web、圖像和固定佈局格式" >}}

{{% blocks/products/pf/feature-page-summary %}}
幫助ODS 在內的常用格式。它還允許將 Excel 檔案匯出為 PDF、XPS、HTML、MHTML、純文字以及 TIFF、JPG、PNG、BMP、JPG、PNG、BMP、JPG、PNG、076116381 和常用圖像。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="使用 Node.js 透過 C++ 將 Excel 轉換為 XLSX、ODS、SXC 和 FODS 格式" %}}
電子表格格式的相互轉換只需要載入帶有實例的電子表格[練習冊](https://reference.aspose.com/cells/nodejs-cpp/workbook/)並以所需的格式儲存，同時從中選擇適當的值[儲存格式](https://reference.aspose.com/cells/nodejs-cpp/saveformat/)枚舉。
{{% blocks/products/pf/feature-page-code h3="Node.js（代碼編號：C++）用於Excel檔案格式轉換" %}}

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


{{% blocks/products/pf/feature-page-section h2="使用 Node.js 透過 C++ 將 Excel 轉換為 PDF、XPS、HTML 和 MD 格式" %}}
專門的類別可用於控制特定輸出格式的轉換過程，例如[Pdf保存選項](https://reference.aspose.com/cells/nodejs-cpp/pdfsaveoptions/)將 Excel 檔案匯出為 PDF，[Xps儲存選項](https://reference.aspose.com/cells/nodejs-cpp/xpssaveoptions/)對於 Excel 到 XPS 的轉換，[Html保存選項](https://reference.aspose.com/cells/nodejs-cpp/htmlsaveoptions/)將 Excel 呈現為 HTML 和[Markdown儲存選項](https://reference.aspose.com/cells/nodejs-cpp/markdownsaveoptions/)用於 Excel 到 Markdown 的轉換。
{{% blocks/products/pf/feature-page-code h3="Node.js 透過 C++ 程式碼將 Excel 轉換為 PDF 和 Web 格式" %}}

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

{{% blocks/products/pf/feature-page-section h2="使用 Node.js 透過 C++ 將 JSON 轉換為 Excel，並將 Excel 轉換為 JSON" %}}
Node.js 開發人員只需幾行程式碼即可輕鬆載入 JSON 檔案並將其轉換為 Excel 檔案。同樣，Excel 資料也可以匯出為 JSON 格式。
{{% blocks/products/pf/feature-page-code h3="Node.js 透過 C++ 程式碼將 JSON 轉換為 Excel" %}}

```js
const AsposeCells = require("aspose.cells.node");

// Load your source json file
var workbook = new AsposeCells.Workbook("Data.json");

//save file to xlsx format
workbook.save("output.xlsx");

```

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Node.js 透過 C++ 程式碼將 Excel 轉換為 JSON" %}}

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

{{% blocks/products/pf/feature-page-section h2="使用 Node.js 將 Excel 工作表轉換為 JPG 格式，參考碼：BMP、PNG 和 GIF（參考碼：C++）。" %}}
 Excel檔案的每個工作表都可以轉換為不同的影像格式，調用[影像或列印選項](https://reference.aspose.com/cells/nodejs-cpp/imageorprintoptions/).setImageFormat 設定影像格式。
{{% blocks/products/pf/feature-page-code h3="Node.js（代碼編號：C++）用於Excel轉圖像轉換" %}}

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

{{% blocks/products/pf/feature-page-section h2="將 Excel 轉換為 Word 文件 & PowerPoint 使用 Node.js 透過 C++" %}}
使用時可以載入任何電子表格並將其轉換為 Word DOCX 和 PowerPoint PPTX 文件[Docx保存選項](https://reference.aspose.com/cells/nodejs-cpp/docxsaveoptions/) & [Pptx保存選項](https://reference.aspose.com/cells/nodejs-cpp/pptxsaveoptions/)類別如下所示。
{{% blocks/products/pf/feature-page-code h3="用於 Excel 到 Word 和 PowerPoint 轉換的 PHP 程式碼" %}}
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
