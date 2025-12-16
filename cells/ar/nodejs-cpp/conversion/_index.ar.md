---
title: Microsoft تحويل ملفات إكسل باستخدام Node.js عبر C++
description: Aspose.Cells for Node.js عبر مكتبة C++. تحويل ملفات إكسل، JSON، PDF، XML، HTML، TXT، TSV، CSV، SQL، وغيرها من الصيغ باستخدام بضعة أسطر فقط من كود Node.js عبر كود C++.
keywords: [Node.js via C++ Aspose.Cells., excel to pdf., json to excel., excel to json., csv to json., json to html., xml to excel and Convert files between various formats in Node.js via C++]
---
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> تحويل تنسيق Excel عبر Node.js عبر C++" h2="استيراد وتصدير ملفات Excel بتنسيقات جداول البيانات والويب والصور والتخطيطات الثابتة" >}}

{{% blocks/products/pf/feature-page-summary %}}
تُسرّع مكتبة Node.js عبر C++ Excel عمليات برمجة جداول البيانات وتحويلها، مع دعمها للتنسيقات الشائعة بما في ذلك XLS، XLSX، XLSM، XLSB، XLTX، XLTM، CSV، SpreadsheetML، ODS. كما تتيح تصدير ملفات Excel إلى PDF، XPS، HTML، MHTML، بالإضافة إلى تنسيقات نصية عادية وتنسيقات صور شائعة مثل TIFF، JPG، PNG، BMP. SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="تحويل ملفات إكسل إلى الأرقام XLSX، ODS، SXC، وFODS باستخدام Node.js عبر الرقم C++" %}}
 يتطلب التحويل البيني لتنسيق جدول البيانات فقط تحميل جدول بيانات بمثيل[دفتر العمل](https://reference.aspose.com/cells/nodejs-cpp/workbook/) والحفظ مرة أخرى بالتنسيق المطلوب أثناء تحديد القيمة المناسبة من[حفظ التنسيق](https://reference.aspose.com/cells/nodejs-cpp/saveformat/) تعداد.
{{% blocks/products/pf/feature-page-code h3="كود Node.js عبر C++ لتحويل تنسيق ملف Excel" %}}

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


{{% blocks/products/pf/feature-page-section h2="تحويل ملفات Excel إلى صيغ PDF، XPS، HTML وMD باستخدام Node.js عبر C++" %}}
 تتوفر فئات متخصصة للتحكم في عملية التحويل لتنسيقات إخراج محددة مثل[خيارات حفظ PDF](https://reference.aspose.com/cells/nodejs-cpp/pdfsaveoptions/)لتصدير ملفات Excel كـ PDF،[خيارات XpsSave](https://reference.aspose.com/cells/nodejs-cpp/xpssaveoptions/) لتحويل Excel إلى XPS ،[هتملسافيوبتيونس](https://reference.aspose.com/cells/nodejs-cpp/htmlsaveoptions/) لتقديم Excel كـ HTML و[خيارات تخفيض السعر](https://reference.aspose.com/cells/nodejs-cpp/markdownsaveoptions/) لتحويل Excel إلى Markdown.
{{% blocks/products/pf/feature-page-code h3="Node.js عبر الرقم C++، كود Excel إلى الرقم PDF، وتنسيقات الويب" %}}

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

{{% blocks/products/pf/feature-page-section h2="حوّل الرقم JSON إلى ملف Excel، ثم حوّله إلى ملف Excel باستخدام Node.js عبر الرقم C++" %}}
يستطيع مطورو Node.js تحميل ملفات JSON وتحويلها إلى ملفات Excel بسهولة تامة باستخدام بضعة أسطر من التعليمات البرمجية. وبالمثل، يمكن تصدير بيانات Excel إلى بيانات JSON.
{{% blocks/products/pf/feature-page-code h3="كود Node.js عبر C++ لتحويل JSON إلى Excel" %}}

```js
const AsposeCells = require("aspose.cells.node");

// Load your source json file
var workbook = new AsposeCells.Workbook("Data.json");

//save file to xlsx format
workbook.save("output.xlsx");

```

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="تحويل كود Node.js من C++ إلى JSON" %}}

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

{{% blocks/products/pf/feature-page-section h2="تحويل أوراق عمل Excel إلى صور JPG، BMP، PNG وGIF باستخدام Node.js عبر C++" %}}
 يمكن تحويل كل ورقة عمل من ملف Excel إلى تنسيقات صور مختلفة[خيارات الصورة أو الطباعة](https://reference.aspose.com/cells/nodejs-cpp/imageorprintoptions/) .setImageFormat لتعيين تنسيق الصورة.
{{% blocks/products/pf/feature-page-code h3="كود Node.js (عبر C++) لتحويل ملفات Excel إلى صور" %}}

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

{{% blocks/products/pf/feature-page-section h2="تحويل ملفات إكسل إلى وورد وPowerPoint باستخدام Node.js عبر C++" %}}
من الممكن تحميل أي جدول بيانات وتحويله إلى ملفات Word DOCX & PowerPoint PPTX أثناء الاستخدام[خيارات حفظ Docx](https://reference.aspose.com/cells/nodejs-cpp/docxsaveoptions/) & [خيارات PptxSave](https://reference.aspose.com/cells/nodejs-cpp/pptxsaveoptions/) الطبقات كما هو موضح أدناه.
{{% blocks/products/pf/feature-page-code h3="كود PHP لتحويل Excel إلى Word وPowerPoint" %}}
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
