---
title: Microsoft Chuyển đổi tập tin Excel bằng Node.js qua C++
description: Aspose.Cells for Node.js thông qua thư viện C++. Chuyển đổi EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL và nhiều định dạng khác chỉ với vài dòng mã Node.js thông qua thư viện C++.
keywords: [Node.js via C++ Aspose.Cells., excel to pdf., json to excel., excel to json., csv to json., json to html., xml to excel and Convert files between various formats in Node.js via C++]
---
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Chuyển đổi định dạng Excel thông qua Node.js qua C++" h2="Nhập và xuất các tệp Excel dưới dạng bảng tính, web, hình ảnh và bố cục cố định" >}}

{{% blocks/products/pf/feature-page-summary %}}
Node.js thông qua thư viện Excel C++ giúp tăng tốc quá trình lập trình và chuyển đổi bảng tính, đồng thời hỗ trợ các định dạng phổ biến bao gồm XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Nó cũng cho phép xuất các tệp Excel sang các định dạng PDF, XPS, HTML, MHTML, văn bản thuần túy và các định dạng hình ảnh phổ biến như TIFF, JPG, PNG, BMP và SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Chuyển đổi Excel sang mã XLSX, ODS, SXC & FODS bằng Node.js thông qua C++" %}}
 Việc chuyển đổi giữa các định dạng bảng tính chỉ yêu cầu tải một bảng tính có phiên bản của[Sách bài tập](https://reference.aspose.com/cells/nodejs-cpp/workbook/) và lưu lại ở định dạng mong muốn trong khi chọn giá trị thích hợp từ[Lưu định dạng](https://reference.aspose.com/cells/nodejs-cpp/saveformat/) sự liệt kê.
{{% blocks/products/pf/feature-page-code h3="Mã Node.js thông qua C++ để chuyển đổi định dạng tệp Excel" %}}

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


{{% blocks/products/pf/feature-page-section h2="Chuyển đổi Excel sang định dạng PDF, XPS, HTML & MD bằng Node.js thông qua C++" %}}
 Các lớp chuyên biệt có sẵn để kiểm soát quá trình chuyển đổi cho các định dạng đầu ra cụ thể như[Tùy chọn lưu Pdf](https://reference.aspose.com/cells/nodejs-cpp/pdfsaveoptions/)để xuất tệp Excel dưới dạng PDF,[Tùy chọn XpsSave](https://reference.aspose.com/cells/nodejs-cpp/xpssaveoptions/) để chuyển đổi Excel sang XPS,[Tùy chọn lưu Html](https://reference.aspose.com/cells/nodejs-cpp/htmlsaveoptions/) để hiển thị Excel dưới dạng HTML và[Tùy chọn lưu Markdown](https://reference.aspose.com/cells/nodejs-cpp/markdownsaveoptions/) để chuyển đổi Excel sang Markdown.
{{% blocks/products/pf/feature-page-code h3="Node.js thông qua mã C++ để chuyển đổi Excel sang định dạng PDF và định dạng web." %}}

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

{{% blocks/products/pf/feature-page-section h2="Chuyển đổi JSON sang Excel và từ Excel sang JSON bằng Node.js thông qua C++" %}}
Các nhà phát triển Node.js có thể dễ dàng tải và chuyển đổi các tệp JSON sang Excel chỉ với một vài dòng mã. Tương tự, dữ liệu Excel cũng có thể được xuất sang dữ liệu JSON.
{{% blocks/products/pf/feature-page-code h3="Node.js thông qua mã C++ để chuyển đổi mã JSON sang Excel." %}}

```js
const AsposeCells = require("aspose.cells.node");

// Load your source json file
var workbook = new AsposeCells.Workbook("Data.json");

//save file to xlsx format
workbook.save("output.xlsx");

```

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Sử dụng Node.js thông qua mã C++ để chuyển đổi dữ liệu từ Excel sang JSON." %}}

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

{{% blocks/products/pf/feature-page-section h2="Chuyển đổi bảng tính Excel sang JPG, BMP, PNG & GIF bằng Node.js thông qua C++" %}}
 Mỗi bảng tính của một tệp Excel có thể được chuyển đổi sang các định dạng hình ảnh khác nhau, hãy gọi[Tùy chọn Hình ảnh Hoặc In](https://reference.aspose.com/cells/nodejs-cpp/imageorprintoptions/) .setImageFormat để đặt định dạng hình ảnh.
{{% blocks/products/pf/feature-page-code h3="Mã Node.js (mã nguồn C++) để chuyển đổi Excel sang hình ảnh" %}}

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

{{% blocks/products/pf/feature-page-section h2="Chuyển đổi Excel sang Word & PowerPoint Sử dụng Node.js qua C++" %}}
Có thể tải bất kỳ bảng tính nào và chuyển đổi nó thành tệp Word DOCX & PowerPoint PPTX trong khi sử dụng[Tùy chọn lưu Docx](https://reference.aspose.com/cells/nodejs-cpp/docxsaveoptions/) & [Tùy chọn lưu Pptx](https://reference.aspose.com/cells/nodejs-cpp/pptxsaveoptions/) các lớp như được minh họa dưới đây.
{{% blocks/products/pf/feature-page-code h3="Mã PHP cho Excel sang Word & chuyển đổi PowerPoint" %}}
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
