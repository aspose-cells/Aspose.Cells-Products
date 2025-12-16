---
title: تبدیل فایل اکسل با استفاده از Node.js از طریق C++
description: Aspose.Cells for Node.js از طریق کتابخانه C++. تبدیل فرمت‌های EXCEL، JSON، PDF، XML، HTML، TXT، TSV، CSV، SQL و فرمت‌های دیگر تنها با چند خط کد Node.js از طریق کد C++.
keywords: [Node.js via C++ Aspose.Cells., excel to pdf., json to excel., excel to json., csv to json., json to html., xml to excel and Convert files between various formats in Node.js via C++]
---
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/i18n/feature-page-header h1="‎Microsoft تبدیل فرمت اکسل از طریق Node.js از طریق ‎C++‎" h2="فایل‌های اکسل را به‌صورت صفحه‌گسترده، وب، تصویر و قالب‌بندی ثابت وارد و صادر کنید" >}}

{{% blocks/products/pf/feature-page-summary %}}
کتابخانه اکسل Node.js از طریق C++، برنامه‌نویسی صفحات گسترده و فرآیندهای تبدیل را سرعت می‌بخشد و در عین حال از فرمت‌های محبوبی از جمله XLS، XLSX، XLSM، XLSB، XLTX، XLTM، CSV، SpreadsheetML، ODS پشتیبانی می‌کند. همچنین امکان خروجی گرفتن از فایل‌های اکسل به فرمت‌های PDF، XPS، HTML، MHTML، متن ساده و فرمت‌های تصویری محبوب مانند TIFF، JPG، PNG، BMP و SVG را فراهم می‌کند.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="تبدیل اکسل به XLSX، ODS، SXC و FODS با استفاده از Node.js از طریق C++" %}}
 تبدیل فرمت صفحه گسترده فقط به بارگیری یک صفحه گسترده با یک نمونه از نیاز دارد[کتاب کار](https://reference.aspose.com/cells/nodejs-cpp/workbook/) و همزمان با انتخاب مقدار مناسب، در قالب مورد نظر ذخیره کنید[ذخیره قالب](https://reference.aspose.com/cells/nodejs-cpp/saveformat/) شمارش
{{% blocks/products/pf/feature-page-code h3="Node.js از طریق کد C++ برای تبدیل فرمت فایل اکسل" %}}

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


{{% blocks/products/pf/feature-page-section h2="تبدیل اکسل به PDF، XPS، HTML و MD با استفاده از Node.js از طریق C++" %}}
 کلاس های تخصصی برای کنترل فرآیند تبدیل برای فرمت های خروجی خاص مانند[گزینه‌های ذخیره پی‌دی‌اف](https://reference.aspose.com/cells/nodejs-cpp/pdfsaveoptions/)برای صادرات فایل های اکسل به عنوان PDF،[گزینه‌های ذخیره Xps](https://reference.aspose.com/cells/nodejs-cpp/xpssaveoptions/) برای تبدیل اکسل به XPS،[گزینه‌های ذخیره Html](https://reference.aspose.com/cells/nodejs-cpp/htmlsaveoptions/) برای رندر اکسل به صورت HTML و[گزینه‌های ذخیره و علامت‌گذاری](https://reference.aspose.com/cells/nodejs-cpp/markdownsaveoptions/) برای تبدیل Excel به Markdown
{{% blocks/products/pf/feature-page-code h3="Node.js از طریق کد C++ برای اکسل به PDF و قالب‌های وب" %}}

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

{{% blocks/products/pf/feature-page-section h2="تبدیل JSON به اکسل و اکسل به JSON با استفاده از Node.js از طریق C++" %}}
توسعه‌دهندگان Node.js می‌توانند به راحتی فایل‌های JSON را تنها با چند خط کد به اکسل بارگذاری و تبدیل کنند. به طور مشابه، داده‌های اکسل را می‌توان به داده‌های JSON تبدیل کرد.
{{% blocks/products/pf/feature-page-code h3="Node.js از طریق کد C++ برای تبدیل JSON به اکسل" %}}

```js
const AsposeCells = require("aspose.cells.node");

// Load your source json file
var workbook = new AsposeCells.Workbook("Data.json");

//save file to xlsx format
workbook.save("output.xlsx");

```

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Node.js از طریق کد C++ برای تبدیل اکسل به JSON" %}}

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

{{% blocks/products/pf/feature-page-section h2="تبدیل صفحات کاری اکسل به JPG، BMP، PNG و GIF با استفاده از Node.js از طریق C++" %}}
 هر کاربرگ یک فایل اکسل را می توان به فرمت های مختلف تصویر تبدیل کرد، تماس بگیرید[گزینه‌های تصویر یا چاپ](https://reference.aspose.com/cells/nodejs-cpp/imageorprintoptions/) برای تنظیم فرمت تصویر، setImageFormat.
{{% blocks/products/pf/feature-page-code h3="کد Node.js از طریق C++ برای تبدیل اکسل به تصویر" %}}

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

{{% blocks/products/pf/feature-page-section h2="تبدیل اکسل به ورد و PowerPoint با استفاده از Node.js از طریق C++" %}}
امکان بارگذاری هر صفحه گسترده و تبدیل آن به فایل های Word DOCX و PowerPoint PPTX در حین استفاده وجود دارد.[گزینه‌های ذخیره سند](https://reference.aspose.com/cells/nodejs-cpp/docxsaveoptions/) & [گزینه‌های ذخیره پاورپوینت](https://reference.aspose.com/cells/nodejs-cpp/pptxsaveoptions/) کلاس هایی که در زیر نشان داده شده است.
{{% blocks/products/pf/feature-page-code h3="کد پی اچ پی برای تبدیل اکسل به ورد و PowerPoint" %}}
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
