---
title: Microsoft Konwersja plików Excel przy użyciu Node.js za pośrednictwem C++
description: Aspose.Cells for Node.js za pomocą biblioteki C++. Konwertuj formaty EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL i inne za pomocą zaledwie kilku linijek kodu Node.js za pomocą biblioteki C++.
keywords: [Node.js via C++ Aspose.Cells., excel to pdf., json to excel., excel to json., csv to json., json to html., xml to excel and Convert files between various formats in Node.js via C++]
---
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Konwersja formatu Excela za pośrednictwem Node.js za pośrednictwem C++" h2="Importuj i eksportuj pliki Excel w formacie arkusza kalkulacyjnego, Internetu, obrazu i formatu o stałym układzie" >}}

{{% blocks/products/pf/feature-page-summary %}}
Node.js za pośrednictwem biblioteki Excel C++ przyspiesza programowanie arkuszy kalkulacyjnych i procesy konwersji, obsługując jednocześnie popularne formaty, w tym XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Umożliwia również eksportowanie plików Excel do PDF, XPS, HTML, MHTML, zwykłego tekstu i popularnych formatów obrazów, takich jak TIFF, JPG, PNG, BMP i SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Konwertuj Excela do XLSX, ODS, SXC i FODS za pomocą Node.js przez C++" %}}
 Wzajemna konwersja formatu arkusza kalkulacyjnego wymaga jedynie załadowania arkusza kalkulacyjnego z instancją[zeszyt ćwiczeń](https://reference.aspose.com/cells/nodejs-cpp/workbook/) i zapisz ponownie w żądanym formacie, wybierając odpowiednią wartość z[ZapiszFormat](https://reference.aspose.com/cells/nodejs-cpp/saveformat/) wyliczenie.
{{% blocks/products/pf/feature-page-code h3="Node.js przez C++ Kod do konwersji formatu pliku Excel" %}}

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


{{% blocks/products/pf/feature-page-section h2="Konwertuj Excela do PDF, XPS, HTML i MD za pomocą Node.js przez C++" %}}
 Dostępne są wyspecjalizowane klasy kontrolujące proces konwersji dla określonych formatów wyjściowych, takich jak[Opcje zapisywania PDF](https://reference.aspose.com/cells/nodejs-cpp/pdfsaveoptions/)aby wyeksportować pliki Excel pod numerem PDF,[Opcje XpsSave](https://reference.aspose.com/cells/nodejs-cpp/xpssaveoptions/) dla konwersji Excela na XPS,[Opcje HTMLSave](https://reference.aspose.com/cells/nodejs-cpp/htmlsaveoptions/) aby renderować Excel jako HTML i[Opcje zapisywania Markdown](https://reference.aspose.com/cells/nodejs-cpp/markdownsaveoptions/) do konwersji Excela na Markdown.
{{% blocks/products/pf/feature-page-code h3="Node.js przez C++ Kod dla Excela do PDF i formaty internetowe" %}}

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

{{% blocks/products/pf/feature-page-section h2="Konwertuj JSON do Excela i z Excela do JSON za pomocą Node.js przez C++" %}}
Programiści Node.js mogą łatwo wczytać i przekonwertować pliki JSON do Excela za pomocą zaledwie kilku linijek kodu. Analogicznie, dane z Excela można wyeksportować do danych JSON.
{{% blocks/products/pf/feature-page-code h3="Node.js przez C++ Kod do konwersji JSON do Excela" %}}

```js
const AsposeCells = require("aspose.cells.node");

// Load your source json file
var workbook = new AsposeCells.Workbook("Data.json");

//save file to xlsx format
workbook.save("output.xlsx");

```

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Node.js za pośrednictwem kodu C++ dla programu Excel do konwersji JSON" %}}

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

{{% blocks/products/pf/feature-page-section h2="Konwertuj arkusze kalkulacyjne programu Excel do formatów JPG, BMP, PNG i GIF za pomocą Node.js za pośrednictwem C++" %}}
 Każdy arkusz pliku Excel można przekonwertować na różne formaty obrazów, zadzwoń[Opcje obrazu lub wydruku](https://reference.aspose.com/cells/nodejs-cpp/imageorprintoptions/) .setImageFormat, aby ustawić format obrazu.
{{% blocks/products/pf/feature-page-code h3="Node.js przez C++ Kod do konwersji Excela na obraz" %}}

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

{{% blocks/products/pf/feature-page-section h2="Konwertuj Excela do Worda i PowerPoint za pomocą Node.js przez C++" %}}
Możliwe jest załadowanie dowolnego arkusza kalkulacyjnego i konwersja go do plików Word DOCX i PowerPoint PPTX podczas korzystania[Opcje DocxSave](https://reference.aspose.com/cells/nodejs-cpp/docxsaveoptions/) & [Opcje PptxSave](https://reference.aspose.com/cells/nodejs-cpp/pptxsaveoptions/) klas, jak pokazano poniżej.
{{% blocks/products/pf/feature-page-code h3="Kod PHP dla Excela do Worda i konwersji PowerPoint" %}}
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
