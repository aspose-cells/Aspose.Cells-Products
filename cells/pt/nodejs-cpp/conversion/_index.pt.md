---
title: Microsoft Conversão de Arquivos Excel usando Node.js via C++
description: Aspose.Cells for Node.js via biblioteca C++. Converta arquivos EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL e outros formatos com apenas algumas linhas de código Node.js via código C++.
keywords: [Node.js via C++ Aspose.Cells., excel to pdf., json to excel., excel to json., csv to json., json to html., xml to excel and Convert files between various formats in Node.js via C++]
---
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Conversão de formato Excel via Node.js via C++" h2="Importe e exporte arquivos Excel como planilha, web, imagem e formatos de layout fixo" >}}

{{% blocks/products/pf/feature-page-summary %}}
A biblioteca Node.js via Excel acelera a programação e os processos de conversão de planilhas, oferecendo suporte a formatos populares como XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML e ODS. Ela também permite exportar arquivos do Excel para os formatos PDF, XPS, HTML, MHTML, Texto Simples e formatos de imagem populares como TIFF, JPG, PNG, BMP e SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Converter Excel para XLSX, ODS, SXC e FODS usando Node.js via C++" %}}
 A interconversão do formato de planilha requer apenas o carregamento de uma planilha com uma instância de[Pasta de trabalho](https://reference.aspose.com/cells/nodejs-cpp/workbook/) e salvando de volta no formato desejado enquanto seleciona o valor apropriado em[Salvar formato](https://reference.aspose.com/cells/nodejs-cpp/saveformat/) enumeração.
{{% blocks/products/pf/feature-page-code h3="Node.js via C++ Código para Conversão de Formato de Arquivo Excel" %}}

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


{{% blocks/products/pf/feature-page-section h2="Converter Excel para PDF, XPS, HTML e MD usando Node.js via C++" %}}
 Classes especializadas estão disponíveis para controlar o processo de conversão para formatos de saída específicos, como[Opções de salvamento de PDF](https://reference.aspose.com/cells/nodejs-cpp/pdfsaveoptions/)para exportar arquivos Excel como PDF,[Opções XpsSave](https://reference.aspose.com/cells/nodejs-cpp/xpssaveoptions/) para conversão de Excel para XPS,[Opções de salvamento em HTML](https://reference.aspose.com/cells/nodejs-cpp/htmlsaveoptions/) para renderizar o Excel como HTML e[Opções de salvamento do Markdown](https://reference.aspose.com/cells/nodejs-cpp/markdownsaveoptions/) para conversão de Excel para Markdown.
{{% blocks/products/pf/feature-page-code h3="Node.js via C++ Código para Excel para PDF e formatos da Web" %}}

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

{{% blocks/products/pf/feature-page-section h2="Converter JSON para Excel e de Excel para JSON usando Node.js via C++" %}}
Os desenvolvedores de Node.js podem facilmente carregar e converter arquivos JSON para o Excel com apenas algumas linhas de código. Da mesma forma, os dados do Excel podem ser exportados para o formato JSON.
{{% blocks/products/pf/feature-page-code h3="Node.js via código C++ para conversão de JSON para Excel" %}}

```js
const AsposeCells = require("aspose.cells.node");

// Load your source json file
var workbook = new AsposeCells.Workbook("Data.json");

//save file to xlsx format
workbook.save("output.xlsx");

```

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Conversão de código Node.js via C++ para Excel para JSON" %}}

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

{{% blocks/products/pf/feature-page-section h2="Converter planilhas do Excel para JPG, BMP, PNG e GIF usando Node.js via C++" %}}
 Cada planilha de um arquivo Excel pode ser convertida para diferentes formatos de imagem, ligue[Opções de imagem ou impressão](https://reference.aspose.com/cells/nodejs-cpp/imageorprintoptions/) .setImageFormat para definir o formato da imagem.
{{% blocks/products/pf/feature-page-code h3="Node.js via C++ Código para conversão de Excel em imagem" %}}

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

{{% blocks/products/pf/feature-page-section h2="Converter Excel para Word e PowerPoint usando Node.js via C++" %}}
É possível carregar qualquer planilha e convertê-la para arquivos Word DOCX e PowerPoint PPTX enquanto estiver usando[Opções de salvamento do Docx](https://reference.aspose.com/cells/nodejs-cpp/docxsaveoptions/) & [Opções PptxSave](https://reference.aspose.com/cells/nodejs-cpp/pptxsaveoptions/) aulas conforme demonstrado abaixo.
{{% blocks/products/pf/feature-page-code h3="Código PHP para Excel para Word e conversão PowerPoint" %}}
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
