---
title: Microsoft Преобразование файла Excel с использованием Node.js через C++
description: Aspose.Cells for Node.js через библиотеку C++. Преобразование EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL и других форматов всего несколькими строками кода Node.js через C++.
keywords: [Node.js via C++ Aspose.Cells., excel to pdf., json to excel., excel to json., csv to json., json to html., xml to excel and Convert files between various formats in Node.js via C++]
---
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Преобразование формата Excel через Node.js с помощью C++" h2="Импортируйте и экспортируйте файлы Excel в форматах электронных таблиц, Интернета, изображений и с фиксированным макетом." >}}

{{% blocks/products/pf/feature-page-summary %}}
Библиотека Excel для Node.js ускоряет программирование и преобразование электронных таблиц, поддерживая популярные форматы, включая XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Она также позволяет экспортировать файлы Excel в форматы PDF, XPS, HTML, MHTML, Plain Text и популярные форматы изображений, такие как TIFF, JPG, PNG, BMP и другие. SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Преобразование файлов Excel в форматы XLSX, ODS, SXC и FODS с использованием Node.js через C++." %}}
 Для взаимного преобразования формата электронной таблицы требуется только загрузка электронной таблицы с экземпляром[Рабочая тетрадь](https://reference.aspose.com/cells/nodejs-cpp/workbook/) и сохранить обратно в желаемом формате, выбрав подходящее значение из[СохранитьФормат](https://reference.aspose.com/cells/nodejs-cpp/saveformat/) перечисление.
{{% blocks/products/pf/feature-page-code h3="Node.js через C++ Код для преобразования формата файла Excel" %}}

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


{{% blocks/products/pf/feature-page-section h2="Преобразование Excel в форматы PDF, XPS, HTML и MD с использованием Node.js через C++" %}}
 Доступны специализированные классы для управления процессом преобразования для определенных выходных форматов, таких как[PDFSaveOptions](https://reference.aspose.com/cells/nodejs-cpp/pdfsaveoptions/)для экспорта файлов Excel как PDF,[XpsSaveOptions](https://reference.aspose.com/cells/nodejs-cpp/xpssaveoptions/) для преобразования Excel в XPS,[HtmlSaveOptions](https://reference.aspose.com/cells/nodejs-cpp/htmlsaveoptions/) для отображения Excel как HTML и[МаркдаунСохранитьПараметры](https://reference.aspose.com/cells/nodejs-cpp/markdownsaveoptions/) для преобразования Excel в Markdown.
{{% blocks/products/pf/feature-page-code h3="Node.js через C++ Код для Excel через PDF и веб-форматы" %}}

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

{{% blocks/products/pf/feature-page-section h2="Преобразование JSON в Excel и Excel в JSON с помощью Node.js через C++" %}}
Разработчики Node.js могут легко загружать и преобразовывать файлы JSON в Excel всего несколькими строками кода. Аналогичным образом, данные Excel можно экспортировать в формат JSON.
{{% blocks/products/pf/feature-page-code h3="Node.js через C++ Код для преобразования JSON в Excel" %}}

```js
const AsposeCells = require("aspose.cells.node");

// Load your source json file
var workbook = new AsposeCells.Workbook("Data.json");

//save file to xlsx format
workbook.save("output.xlsx");

```

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Node.js через C++ Код для Excel в JSON Преобразование" %}}

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

{{% blocks/products/pf/feature-page-section h2="Преобразование электронных таблиц Excel в форматы JPG (BMP, PNG и GIF) с использованием Node.js через C++." %}}
 Каждый лист файла Excel можно преобразовать в разные форматы изображений, позвоните[Параметры изображения или печати](https://reference.aspose.com/cells/nodejs-cpp/imageorprintoptions/) .setImageFormat для установки формата изображения.
{{% blocks/products/pf/feature-page-code h3="Node.js через C++ Код для преобразования файлов Excel в изображения" %}}

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

{{% blocks/products/pf/feature-page-section h2="Преобразование Excel в Word и PowerPoint с использованием Node.js через C++" %}}
Можно загрузить любую электронную таблицу и преобразовать ее в файлы Word DOCX и PowerPoint PPTX при использовании[Параметры сохранения документа](https://reference.aspose.com/cells/nodejs-cpp/docxsaveoptions/) & [Параметры сохранения Pptx](https://reference.aspose.com/cells/nodejs-cpp/pptxsaveoptions/) классы, как показано ниже.
{{% blocks/products/pf/feature-page-code h3="PHP-код для Excel в Word и преобразование PowerPoint" %}}
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
