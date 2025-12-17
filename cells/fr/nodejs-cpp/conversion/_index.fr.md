---
title: Conversion de fichiers Excel (Microsoft) avec Node.js (via C++)
description: Aspose.Cells for Node.js via la bibliothèque C++. Convertissez des fichiers EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL et bien d'autres formats en quelques lignes de code Node.js via C++.
keywords: [Node.js via C++ Aspose.Cells., excel to pdf., json to excel., excel to json., csv to json., json to html., xml to excel and Convert files between various formats in Node.js via C++]
---
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/i18n/feature-page-header h1="Conversion de format Excel via Node.js (Microsoft)" h2="Importez et exportez des fichiers Excel aux formats tableur, Web, image et mise en page fixe" >}}

{{% blocks/products/pf/feature-page-summary %}}
La bibliothèque Excel Node.js (code C++) accélère la programmation et la conversion de feuilles de calcul, tout en prenant en charge les formats courants suivants : Excel (XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS). Elle permet également d'exporter des fichiers Excel aux formats suivants : texte brut (PDF, XPS, HTML, MHTML) et images (TIFF, JPG, PNG, BMP, SVG).
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Convertir des fichiers Excel aux formats XLSX, ODS, SXC et FODS à l\'aide de Node.js (code C++)." %}}
 L'interconversion du format de feuille de calcul nécessite uniquement le chargement d'une feuille de calcul avec une instance de[Cahier d'exercices](https://reference.aspose.com/cells/nodejs-cpp/workbook/) et sauvegarder dans le format souhaité tout en sélectionnant la valeur appropriée dans[EnregistrerFormat](https://reference.aspose.com/cells/nodejs-cpp/saveformat/) énumération.
{{% blocks/products/pf/feature-page-code h3="Code Node.js via C++ pour la conversion du format de fichier Excel" %}}

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


{{% blocks/products/pf/feature-page-section h2="Conversion de fichiers Excel aux formats PDF, XPS, HTML et MD via Node.js (code C++)." %}}
 Des cours spécialisés sont disponibles pour contrôler le processus de conversion pour des formats de sortie spécifiques tels que[Options d'enregistrement PDF](https://reference.aspose.com/cells/nodejs-cpp/pdfsaveoptions/)pour exporter des fichiers Excel sous le numéro PDF,[Options de sauvegarde XPS](https://reference.aspose.com/cells/nodejs-cpp/xpssaveoptions/) pour la conversion Excel en XPS,[Options d'enregistrement HTML](https://reference.aspose.com/cells/nodejs-cpp/htmlsaveoptions/) pour afficher Excel sous la forme HTML et[Options d'enregistrement Markdown](https://reference.aspose.com/cells/nodejs-cpp/markdownsaveoptions/) pour la conversion Excel vers Markdown.
{{% blocks/products/pf/feature-page-code h3="Code Node.js via C++ pour Excel et formats Web" %}}

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

{{% blocks/products/pf/feature-page-section h2="Convertir JSON en Excel et Excel en JSON à l\'aide de Node.js via C++" %}}
Les développeurs Node.js peuvent facilement charger et convertir des fichiers JSON en Excel en quelques lignes de code seulement. De même, les données Excel peuvent être exportées au format JSON.
{{% blocks/products/pf/feature-page-code h3="Code Node.js via C++ pour la conversion de JSON en Excel" %}}

```js
const AsposeCells = require("aspose.cells.node");

// Load your source json file
var workbook = new AsposeCells.Workbook("Data.json");

//save file to xlsx format
workbook.save("output.xlsx");

```

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Conversion de code Node.js via C++ pour Excel vers JSON" %}}

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

{{% blocks/products/pf/feature-page-section h2="Conversion de feuilles de calcul Excel en JPG, BMP, PNG et GIF à l\'aide de Node.js (via C++)" %}}
 Chaque feuille de calcul d'un fichier Excel peut être convertie en différents formats d'image, appelez[OptionsImageOuImpression](https://reference.aspose.com/cells/nodejs-cpp/imageorprintoptions/) .setImageFormat pour définir le format de l'image.
{{% blocks/products/pf/feature-page-code h3="Code Node.js via C++ pour la conversion d\'Excel en image" %}}

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

{{% blocks/products/pf/feature-page-section h2="Conversion d\'Excel en Word & PowerPoint avec Node.js via C++" %}}
Il est possible de charger n'importe quelle feuille de calcul et de la convertir en fichiers Word DOCX et PowerPoint PPTX tout en utilisant[Options d'enregistrement Docx](https://reference.aspose.com/cells/nodejs-cpp/docxsaveoptions/) & [Options d'enregistrement Pptx](https://reference.aspose.com/cells/nodejs-cpp/pptxsaveoptions/) cours comme démontré ci-dessous.
{{% blocks/products/pf/feature-page-code h3="Code PHP pour la conversion Excel vers Word et PowerPoint" %}}
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
