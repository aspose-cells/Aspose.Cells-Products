---
title: Microsoft การแปลงไฟล์ Excel โดยใช้ Node.js ผ่าน C++
description: Aspose.Cells for Node.js ผ่านไลบรารี C++ แปลงไฟล์ EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL และรูปแบบอื่นๆ อีกมากมายด้วยโค้ด Node.js เพียงไม่กี่บรรทัด ผ่านโค้ด C++
keywords: [Node.js via C++ Aspose.Cells., excel to pdf., json to excel., excel to json., csv to json., json to html., xml to excel and Convert files between various formats in Node.js via C++]
---
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> การแปลงรูปแบบ Excel ผ่าน Node.js โดย C++" h2="นำเข้าและส่งออกไฟล์ Excel เป็นสเปรดชีต เว็บ รูปภาพ และรูปแบบคงที่" >}}

{{% blocks/products/pf/feature-page-summary %}}
Node.js ผ่านไลบรารี Excel C++ ช่วยเร่งความเร็วในการเขียนโปรแกรมและแปลงไฟล์สเปรดชีต พร้อมรองรับรูปแบบยอดนิยมต่างๆ เช่น XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML และ ODS นอกจากนี้ยังอนุญาตให้ส่งออกไฟล์ Excel ไปยัง PDF, XPS, HTML, MHTML, ข้อความธรรมดา และรูปแบบภาพยอดนิยม เช่น TIFF, PNG และ BMP SVG
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="แปลงไฟล์ Excel เป็นรหัส XLSX, ODS, SXC และ FODS โดยใช้ Node.js ผ่านรหัส C++" %}}
 การแปลงรูปแบบสเปรดชีตระหว่างกันต้องโหลดสเปรดชีตที่มีอินสแตนซ์เท่านั้น[สมุดงาน](https://reference.aspose.com/cells/nodejs-cpp/workbook/) และบันทึกกลับในรูปแบบที่ต้องการพร้อมเลือกค่าที่เหมาะสมจาก[บันทึกรูปแบบ](https://reference.aspose.com/cells/nodejs-cpp/saveformat/) การแจงนับ
{{% blocks/products/pf/feature-page-code h3="โค้ด Node.js หมายเลข C++ สำหรับการแปลงรูปแบบไฟล์ Excel" %}}

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


{{% blocks/products/pf/feature-page-section h2="แปลงไฟล์ Excel เป็นรหัส PDF, XPS, HTML และ MD โดยใช้ Node.js ผ่านรหัส C++" %}}
 มีคลาสเฉพาะทางเพื่อควบคุมกระบวนการแปลงสำหรับรูปแบบเอาต์พุตเฉพาะเช่น[ตัวเลือก PdfSave](https://reference.aspose.com/cells/nodejs-cpp/pdfsaveoptions/)เพื่อส่งออกไฟล์ Excel เป็น PDF,[XpsSaveOptions](https://reference.aspose.com/cells/nodejs-cpp/xpssaveoptions/) สำหรับการแปลง Excel เป็น XPS[HtmlSaveตัวเลือก](https://reference.aspose.com/cells/nodejs-cpp/htmlsaveoptions/) เพื่อเรนเดอร์ Excel เป็น HTML และ[ตัวเลือกการบันทึกมาร์คดาวน์](https://reference.aspose.com/cells/nodejs-cpp/markdownsaveoptions/) สำหรับการแปลง Excel เป็น Markdown
{{% blocks/products/pf/feature-page-code h3="Node.js ผ่านรหัส C++ สำหรับ Excel และรูปแบบเว็บ" %}}

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

{{% blocks/products/pf/feature-page-section h2="แปลง JSON เป็น Excel และ Excel เป็น JSON โดยใช้ Node.js ผ่าน C++" %}}
นักพัฒนา Node.js สามารถโหลดและแปลงไฟล์ JSON เป็น Excel ได้อย่างง่ายดายด้วยโค้ดเพียงไม่กี่บรรทัด ในทำนองเดียวกัน ข้อมูลจาก Excel ก็สามารถส่งออกไปยังข้อมูล JSON ได้เช่นกัน
{{% blocks/products/pf/feature-page-code h3="Node.js ผ่านรหัส C++ สำหรับการแปลง JSON เป็น Excel" %}}

```js
const AsposeCells = require("aspose.cells.node");

// Load your source json file
var workbook = new AsposeCells.Workbook("Data.json");

//save file to xlsx format
workbook.save("output.xlsx");

```

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="โค้ด Node.js หมายเลข C++ สำหรับการแปลง Excel เป็น JSON" %}}

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

{{% blocks/products/pf/feature-page-section h2="แปลงเวิร์กชีต Excel เป็น JPG, BMP, PNG และ GIF โดยใช้ Node.js ผ่าน C++" %}}
 แต่ละแผ่นงานของไฟล์ Excel สามารถแปลงเป็นรูปแบบรูปภาพที่แตกต่างกันได้ โทร[รูปภาพหรือตัวเลือกการพิมพ์](https://reference.aspose.com/cells/nodejs-cpp/imageorprintoptions/) .setImageFormat เพื่อกำหนดรูปแบบภาพ
{{% blocks/products/pf/feature-page-code h3="โค้ด Node.js หมายเลข C++ สำหรับแปลงไฟล์ Excel เป็นรูปภาพ" %}}

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

{{% blocks/products/pf/feature-page-section h2="แปลงไฟล์ Excel เป็น Word โดยใช้ Node.js (รหัส PowerPoint) (รหัส C++)" %}}
คุณสามารถโหลดสเปรดชีตใดก็ได้และแปลงเป็นไฟล์ Word DOCX & PowerPoint PPTX ในขณะที่ใช้งาน[ตัวเลือกการบันทึกเอกสาร](https://reference.aspose.com/cells/nodejs-cpp/docxsaveoptions/) & [ตัวเลือกการบันทึก Pptx](https://reference.aspose.com/cells/nodejs-cpp/pptxsaveoptions/) ชั้นเรียนตามที่แสดงด้านล่าง
{{% blocks/products/pf/feature-page-code h3="รหัส PHP สำหรับ Excel เป็น Word และการแปลง PowerPoint" %}}
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
