---
title: Microsoft Node.js を使用した Excel ファイル変換 (C++ 経由)
description: C++ライブラリ経由でAspose.Cells、for Node.jsに変換します。C++コード経由で、わずか数行のNode.jsコードで、EXCEL、JSON、PDF、XML、HTML、TXT、TSV、CSV、SQLなどのフォーマットに変換します。
keywords: [Node.js via C++ Aspose.Cells., excel to pdf., json to excel., excel to json., csv to json., json to html., xml to excel and Convert files between various formats in Node.js via C++]
---
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Node.js 経由の Excel 形式変換 (C++ 経由)" h2="Excel ファイルをスプレッドシート、Web、画像、固定レイアウト形式でインポートおよびエクスポートします。" >}}

{{% blocks/products/pf/feature-page-summary %}}
C++ Excelライブラリ経由のNode.jsは、XLS、XLSX、XLSM、XLSB、XLTX、XLTM、CSV、SpreadsheetML、ODSなどの一般的な形式をサポートしながら、スプレッドシートのプログラミングと変換プロセスを高速化します。また、ExcelファイルをPDF、XPS、HTML、MHTML、プレーンテキスト、およびTIFF、JPG、PNG、BMPなどの一般的な画像形式にエクスポートすることもできます。 SVG。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Node.js を使って C++ 経由で Excel を XLSX、ODS、SXC、FODS に変換する" %}}
スプレッドシート形式の相互変換には、次のインスタンスを含むスプレッドシートを読み込むだけで済みます。[ワークブック](https://reference.aspose.com/cells/nodejs-cpp/workbook/)適切な値を選択しながら、希望の形式で保存します。[保存形式](https://reference.aspose.com/cells/nodejs-cpp/saveformat/)列挙。
{{% blocks/products/pf/feature-page-code h3="Node.js 経由 C++ Excel ファイル形式変換コード" %}}

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


{{% blocks/products/pf/feature-page-section h2="Node.js を使用して C++ 経由で Excel を PDF、XPS、HTML、および MD に変換する" %}}
特定の出力形式の変換プロセスを制御するための専用クラスが用意されています。[Pdf保存オプション](https://reference.aspose.com/cells/nodejs-cpp/pdfsaveoptions/)ExcelファイルをPDFとしてエクスポートするには、[Xps保存オプション](https://reference.aspose.com/cells/nodejs-cpp/xpssaveoptions/)ExcelからXPSへの変換、[HTML保存オプション](https://reference.aspose.com/cells/nodejs-cpp/htmlsaveoptions/)ExcelをHTMLと表示し、[マークダウン保存オプション](https://reference.aspose.com/cells/nodejs-cpp/markdownsaveoptions/)Excel から Markdown への変換用。
{{% blocks/products/pf/feature-page-code h3="Node.js経由のC++ ExcelコードからPDFおよびWeb形式" %}}

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

{{% blocks/products/pf/feature-page-section h2="Node.js を使用して C++ 経由で JSON を Excel に変換し、Excel を JSON に変換する" %}}
Node.js開発者は、わずか数行のコードでJSONファイルをExcelに簡単に読み込み、変換できます。同様に、ExcelデータをJSONデータにエクスポートすることもできます。
{{% blocks/products/pf/feature-page-code h3="Node.js 経由 C++ コード JSON を Excel に変換する" %}}

```js
const AsposeCells = require("aspose.cells.node");

// Load your source json file
var workbook = new AsposeCells.Workbook("Data.json");

//save file to xlsx format
workbook.save("output.xlsx");

```

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Node.js 経由の C++ コードによる Excel から JSON への変換" %}}

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

{{% blocks/products/pf/feature-page-section h2="Node.js を使用して C++ 経由で Excel ワークシートを JPG、BMP、PNG、GIF に変換する" %}}
Excelファイルの各ワークシートは、異なる画像形式に変換することができます。[画像または印刷オプション](https://reference.aspose.com/cells/nodejs-cpp/imageorprintoptions/).setImageFormat を使用して画像形式を設定します。
{{% blocks/products/pf/feature-page-code h3="Node.js 経由 C++ Excel から画像への変換コード" %}}

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

{{% blocks/products/pf/feature-page-section h2="C++ 経由で Node.js を使用して Excel を Word に変換します。" %}}
任意のスプレッドシートを読み込み、使用中にWord DOCX & PowerPoint PPTXファイルに変換することが可能です。[Docx保存オプション](https://reference.aspose.com/cells/nodejs-cpp/docxsaveoptions/) & [Pptx保存オプション](https://reference.aspose.com/cells/nodejs-cpp/pptxsaveoptions/)以下に示すようにクラスがあります。
{{% blocks/products/pf/feature-page-code h3="Excel から Word への変換と PowerPoint への変換のための PHP コード" %}}
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
