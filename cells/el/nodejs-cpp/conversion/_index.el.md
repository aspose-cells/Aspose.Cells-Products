---
title: Microsoft Μετατροπή αρχείου Excel χρησιμοποιώντας Node.js μέσω C++
description: Aspose.Cells for Node.js μέσω της βιβλιοθήκης C++. Μετατρέψτε EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL και άλλες μορφές με λίγες μόνο γραμμές Node.js μέσω κώδικα C++.
keywords: [Node.js via C++ Aspose.Cells., excel to pdf., json to excel., excel to json., csv to json., json to html., xml to excel and Convert files between various formats in Node.js via C++]
---
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Μετατροπή μορφής Excel μέσω Node.js μέσω C++" h2="Εισαγωγή και εξαγωγή αρχείων Excel ως υπολογιστικού φύλλου, ιστού, εικόνας και μορφής σταθερής διάταξης" >}}

{{% blocks/products/pf/feature-page-summary %}}
Το Node.js μέσω της βιβλιοθήκης Excel C++ επιταχύνει τον προγραμματισμό υπολογιστικών φύλλων και τις διαδικασίες μετατροπής, ενώ παράλληλα υποστηρίζει δημοφιλείς μορφές, όπως XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Επιτρέπει επίσης την εξαγωγή αρχείων Excel σε PDF, XPS, HTML, MHTML, Απλό Κείμενο και δημοφιλείς μορφές εικόνας όπως TIFF, JPG, PNG, BMP και SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Μετατροπή Excel σε XLSX, ODS, SXC και FODS χρησιμοποιώντας το Node.js μέσω του C++" %}}
 Η αλληλομετατροπή της μορφής υπολογιστικού φύλλου απαιτεί μόνο τη φόρτωση ενός υπολογιστικού φύλλου με μια παρουσία του[ΤΕΤΡΑΔΙΟ ΕΡΓΑΣΙΩΝ](https://reference.aspose.com/cells/nodejs-cpp/workbook/) και αποθηκεύστε ξανά στην επιθυμητή μορφή ενώ επιλέγετε την κατάλληλη τιμή από[ΑποθήκευσηΜορφής](https://reference.aspose.com/cells/nodejs-cpp/saveformat/) απαρίθμηση.
{{% blocks/products/pf/feature-page-code h3="Node.js μέσω C++ Κώδικας για Μετατροπή Μορφής Αρχείου Excel" %}}

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


{{% blocks/products/pf/feature-page-section h2="Μετατροπή Excel σε PDF, XPS, HTML & MD χρησιμοποιώντας Node.js μέσω C++" %}}
 Διατίθενται εξειδικευμένες κλάσεις για τον έλεγχο της διαδικασίας μετατροπής για συγκεκριμένες μορφές εξόδου, όπως π.χ[Επιλογές Αποθήκευσης Pdf](https://reference.aspose.com/cells/nodejs-cpp/pdfsaveoptions/)για εξαγωγή αρχείων Excel ως PDF,[Επιλογές Αποθήκευσης Xps](https://reference.aspose.com/cells/nodejs-cpp/xpssaveoptions/) για μετατροπή Excel σε XPS,[Επιλογές Αποθήκευσης Html](https://reference.aspose.com/cells/nodejs-cpp/htmlsaveoptions/) για απόδοση του Excel ως HTML και[Επιλογές Αποθήκευσης Markdown](https://reference.aspose.com/cells/nodejs-cpp/markdownsaveoptions/) για τη μετατροπή Excel σε Markdown.
{{% blocks/products/pf/feature-page-code h3="Node.js μέσω C++ Κώδικας για Excel σε PDF και Μορφές Web" %}}

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

{{% blocks/products/pf/feature-page-section h2="Μετατροπή JSON σε Excel & Excel σε JSON χρησιμοποιώντας Node.js μέσω C++" %}}
Οι προγραμματιστές του Node.js μπορούν εύκολα να φορτώσουν και να μετατρέψουν αρχεία JSON σε Excel σε λίγες μόνο γραμμές κώδικα. Ομοίως, τα δεδομένα του Excel μπορούν να εξαχθούν σε δεδομένα JSON.
{{% blocks/products/pf/feature-page-code h3="Node.js μέσω C++ Κωδικός για μετατροπή JSON σε Excel" %}}

```js
const AsposeCells = require("aspose.cells.node");

// Load your source json file
var workbook = new AsposeCells.Workbook("Data.json");

//save file to xlsx format
workbook.save("output.xlsx");

```

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Node.js μέσω κώδικα C++ για μετατροπή από Excel σε JSON" %}}

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

{{% blocks/products/pf/feature-page-section h2="Μετατροπή φύλλων εργασίας Excel σε JPG, BMP, PNG και GIF χρησιμοποιώντας το Node.js μέσω του C++" %}}
 Κάθε φύλλο εργασίας ενός αρχείου Excel μπορεί να μετατραπεί σε διαφορετικές μορφές εικόνας, καλέστε[Επιλογές εικόνας ή εκτύπωσης](https://reference.aspose.com/cells/nodejs-cpp/imageorprintoptions/) .setImageFormat για να ορίσετε τη μορφή εικόνας.
{{% blocks/products/pf/feature-page-code h3="Node.js μέσω C++ Κώδικας για μετατροπή Excel σε εικόνα" %}}

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

{{% blocks/products/pf/feature-page-section h2="Μετατροπή Excel σε Word & PowerPoint χρησιμοποιώντας Node.js μέσω C++" %}}
Είναι δυνατή η φόρτωση οποιουδήποτε υπολογιστικού φύλλου και η μετατροπή του σε αρχεία Word DOCX & PowerPoint PPTX κατά τη χρήση[Επιλογές Αποθήκευσης Docx](https://reference.aspose.com/cells/nodejs-cpp/docxsaveoptions/) & [Επιλογές Αποθήκευσης Pptx](https://reference.aspose.com/cells/nodejs-cpp/pptxsaveoptions/) τάξεις όπως παρουσιάζεται παρακάτω.
{{% blocks/products/pf/feature-page-code h3="Κώδικας PHP για Excel σε Word & Μετατροπή PowerPoint" %}}
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
