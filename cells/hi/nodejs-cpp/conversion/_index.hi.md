---
title: Microsoft Node.js का इस्तेमाल करके Excel फ़ाइल कन्वर्ज़न C++ के ज़रिए
description: Aspose.Cells for Node.js C++ लाइब्रेरी के ज़रिए। C++ कोड के ज़रिए Node.js की कुछ लाइनों से EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL और दूसरे फ़ॉर्मैट कन्वर्ट करें।
keywords: [Node.js via C++ Aspose.Cells., excel to pdf., json to excel., excel to json., csv to json., json to html., xml to excel and Convert files between various formats in Node.js via C++]
---
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Node.js के ज़रिए Excel फ़ॉर्मेट कन्वर्ज़न C++ के ज़रिए" h2="एक्सेल फ़ाइलों को स्प्रेडशीट, वेब, छवि और निश्चित-लेआउट प्रारूपों में आयात और निर्यात करें" >}}

{{% blocks/products/pf/feature-page-summary %}}
C++ एक्सेल लाइब्रेरी के माध्यम से Node.js स्प्रेडशीट प्रोग्रामिंग और रूपांतरण प्रक्रियाओं को गति देता है जबकि XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS सहित लोकप्रिय प्रारूपों का समर्थन करता है। यह एक्सेल फ़ाइलों को PDF, XPS, HTML, MHTML, सादा पाठ और लोकप्रिय छवि प्रारूपों जैसे TIFF, JPG, PNG, BMP और SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Node.js का इस्तेमाल करके C++ के ज़रिए Excel को XLSX, ODS, SXC और FODS में बदलें" %}}
 स्प्रेडशीट प्रारूप के अंतर-रूपांतरण के लिए केवल एक उदाहरण के साथ स्प्रेडशीट लोड करना आवश्यक है[वर्कबुक](https://reference.aspose.com/cells/nodejs-cpp/workbook/) और उचित मूल्य का चयन करते हुए वांछित प्रारूप में वापस सहेजना[सहेजेंप्रारूप](https://reference.aspose.com/cells/nodejs-cpp/saveformat/) गणना.
{{% blocks/products/pf/feature-page-code h3="Node.js वाया C++ एक्सेल फ़ाइल फ़ॉर्मेट कन्वर्ज़न के लिए कोड" %}}

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


{{% blocks/products/pf/feature-page-section h2="Node.js का इस्तेमाल करके C++ के ज़रिए Excel को PDF, XPS, HTML और MD में बदलें" %}}
 विशिष्ट आउटपुट प्रारूपों के लिए रूपांतरण प्रक्रिया को नियंत्रित करने के लिए विशेष कक्षाएं उपलब्ध हैं जैसे[पीडीएफसहेजेंविकल्प](https://reference.aspose.com/cells/nodejs-cpp/pdfsaveoptions/)एक्सेल फ़ाइलों को PDF के रूप में निर्यात करने के लिए,[Xpsसेवविकल्प](https://reference.aspose.com/cells/nodejs-cpp/xpssaveoptions/) एक्सेल से XPS रूपांतरण के लिए,[Htmlसहेजेंविकल्प](https://reference.aspose.com/cells/nodejs-cpp/htmlsaveoptions/) एक्सेल को HTML के रूप में प्रस्तुत करने के लिए और[मार्कडाउनसहेजेंविकल्प](https://reference.aspose.com/cells/nodejs-cpp/markdownsaveoptions/) एक्सेल से मार्कडाउन रूपांतरण के लिए.
{{% blocks/products/pf/feature-page-code h3="Node.js वाया C++ कोड फॉर एक्सेल टू PDF और वेब फॉर्मेट" %}}

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

{{% blocks/products/pf/feature-page-section h2="Node.js का इस्तेमाल करके JSON को Excel में और Excel को JSON में बदलें C++ के ज़रिए" %}}
Node.js डेवलपर्स कुछ ही लाइन के कोड में JSON फ़ाइलों को आसानी से लोड और Excel में कन्वर्ट कर सकते हैं। इसी तरह, Excel डेटा को JSON डेटा में एक्सपोर्ट किया जा सकता है।
{{% blocks/products/pf/feature-page-code h3="Node.js के ज़रिए C++ कोड JSON से Excel में बदलने के लिए" %}}

```js
const AsposeCells = require("aspose.cells.node");

// Load your source json file
var workbook = new AsposeCells.Workbook("Data.json");

//save file to xlsx format
workbook.save("output.xlsx");

```

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Node.js से C++ कोड फॉर एक्सेल से JSON कन्वर्ज़न" %}}

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

{{% blocks/products/pf/feature-page-section h2="Node.js का इस्तेमाल करके Excel वर्कशीट को JPG, BMP, PNG और GIF में बदलें C++" %}}
 एक्सेल फ़ाइल की प्रत्येक वर्कशीट को विभिन्न छवि प्रारूपों में परिवर्तित किया जा सकता है, जिन्हें कहा जाता है[छवियाप्रिंटविकल्प](https://reference.aspose.com/cells/nodejs-cpp/imageorprintoptions/) छवि प्रारूप सेट करने के लिए .setImageFormat.
{{% blocks/products/pf/feature-page-code h3="Node.js वाया C++ एक्सेल से इमेज कन्वर्ज़न के लिए कोड" %}}

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

{{% blocks/products/pf/feature-page-section h2="Node.js का इस्तेमाल करके C++ से Excel को Word में बदलें" %}}
किसी भी स्प्रेडशीट को लोड करना और इसे वर्ड DOCX और PowerPoint PPTX फ़ाइलों में परिवर्तित करना संभव है[DocxSaveविकल्प](https://reference.aspose.com/cells/nodejs-cpp/docxsaveoptions/) & [पीपीटीएक्ससेवऑप्शन](https://reference.aspose.com/cells/nodejs-cpp/pptxsaveoptions/) जैसा कि नीचे दर्शाया गया है, कक्षाएं।
{{% blocks/products/pf/feature-page-code h3="एक्सेल से वर्ड और PowerPoint रूपांतरण के लिए PHP कोड" %}}
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
