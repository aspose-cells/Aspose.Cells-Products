---
title:  Microsoft การแปลงไฟล์ Excel ผ่าน C#
description: แปลง Excel XLS, XLSX, ODS, CSV เป็น PDF, XPS, HTML, JPEG, HTML และรูปแบบยอดนิยมอื่น ๆ อีกมากมายด้วยรหัส C# เพียงไม่กี่บรรทัด .
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> การแปลงรูปแบบ Excel via .NET" h2="นำเข้าและส่งออกไฟล์ Excel เป็นรูปแบบสเปรดชีต เว็บ รูปภาพ และเค้าโครงคงที่" >}}

{{% blocks/products/pf/feature-page-summary %}}
.NET Excel Library เร่งความเร็วการเขียนโปรแกรมสเปรดชีตและกระบวนการแปลงในขณะที่รองรับรูปแบบยอดนิยม ได้แก่ XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, 076193 481 นอกจากนี้ยังอนุญาตให้ส่งออกไฟล์ Excel ไปที่ PDF, XPS, HTML, MHTML, Plain รูปแบบข้อความและรูปภาพยอดนิยม เช่น TIFF, JPG, PNG, BMP และ SVG
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="แปลง Excel เป็น XLSX, ODS, SXC & FODS" %}}
 การแปลงรูปแบบสเปรดชีตระหว่างกันจำเป็นต้องโหลดสเปรดชีตที่มีอินสแตนซ์ของ[สมุดงาน](https://reference.aspose.com/cells/net/aspose.cells/workbook) และบันทึกกลับในรูปแบบที่ต้องการพร้อมเลือกค่าที่เหมาะสมจาก[บันทึกรูปแบบ](https://reference.aspose.com/cells/net/aspose.cells/saveformat) การแจงนับ
{{% blocks/products/pf/feature-page-code h3="C# รหัสสำหรับการแปลงรูปแบบไฟล์ Excel" %}}

```cs
// load the template file
var workbook = new Aspose.Cells.Workbook("template.xls");
// save as XLSX, ODS, SXC & FODS formats
workbook.Save("output.xlsx", Aspose.Cells.SaveFormat.Xlsx);
workbook.Save("output.ods", Aspose.Cells.SaveFormat.Ods);
workbook.Save("output.scx", Aspose.Cells.SaveFormat.Sxc);
workbook.Save("output.fods", Aspose.Cells.SaveFormat.Fods);
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="แปลง Excel เป็น PDF, XPS, HTML & MD" %}}
 มีคลาสเฉพาะสำหรับควบคุมกระบวนการแปลงสำหรับรูปแบบเอาต์พุตเฉพาะ เช่น[PdfSaveตัวเลือก](https://reference.aspose.com/cells/net/aspose.cells/pdfsaveoptions) เพื่อส่งออกไฟล์ Excel เป็น PDF[ตัวเลือก XpsSave](https://reference.aspose.com/cells/net/aspose.cells/xpssaveoptions) สำหรับการแปลง Excel เป็น XPS[ตัวเลือก HtmlSave](https://reference.aspose.com/cells/net/aspose.cells/htmlsaveoptions) เพื่อแสดง Excel เป็น HTML และ[MarkdownSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/markdownsaveoptions) สำหรับการแปลง Excel เป็น Markdown
{{% blocks/products/pf/feature-page-code h3="C# รหัสสำหรับ Excel ถึง PDF และรูปแบบเว็บ" %}}

```cs
// load template Excel file from disc
var book = new Aspose.Cells.Workbook("template.xlsx");
// save Excel in PDF/A-1a format
book.Save("output.pdf", new Aspose.Cells.PdfSaveOptions() { Compliance = PdfComplianceVersion.PdfA1a });
// save Excel in XPS with 1 page per worksheet
book.Save("output.xps", new Aspose.Cells.XpsSaveOptions() { OnePagePerSheet = true });
// save Excel in HTML with images as Base64
book.Save("output.html", new Aspose.Cells.HtmlSaveOptions() { ExportImagesAsBase64 = true });
// save Excel in Markdown (MD) while retaining cell formatting
book.Save("output.md", new Aspose.Cells.MarkdownSaveOptions() { FormatStrategy = Cells.CellValueFormatStrategy.CellStyle });
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="แปลง JSON เป็น Excel และ Excel เป็น JSON" %}}
 ข้อมูล JSON สามารถนำเข้าอินสแตนซ์ของ[Cells](https://reference.aspose.com/cells/net/aspose.cells/cells) ชั้นด้วยความช่วยเหลือของ[JsonUtility.ImportData](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/importdata)สำหรับการประมวลผลเพิ่มเติมหรือการแปลงอย่างง่ายเป็นรูปแบบที่รองรับ ในทำนองเดียวกัน[ใบงาน](https://reference.aspose.com/cells/net/aspose.cells/worksheet) ข้อมูลสามารถส่งออกเป็น JSON โดยสร้างไฟล์[พิสัย](https://reference.aspose.com/cells/net/aspose.cells/range) หรือเซลล์และโทร[JsonUtility.ExportRangeToJson](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/exportrangetojson) วิธี.
{{% blocks/products/pf/feature-page-code h3="รหัส C# สำหรับการแปลง JSON เป็น Excel" %}}
```cs
// create a Workbook object
var workbook = new Cells.Workbook();
var worksheet = workbook.Worksheets[0];
// read JSON data from file
string jsonInput = File.ReadAllText("Data.json");
// set JsonLayoutOptions to treat Arrays as Table
var options = new Cells.Utility.JsonLayoutOptions();
options.ArrayAsTable = true;
// import JSON data to worksheet starting at cell A1
Cells.Utility.JsonUtility.ImportData(jsonInput, worksheet.Cells, 0, 0, options);
// save resultant file in XLSX format
workbook.Save("output.xlsx", Cells.SaveFormat.Auto); 
```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# รหัสสำหรับการแปลง Excel เป็น JSON" %}}
```cs
// load XLSX file with an instance of Workbook
var workbook = new Workbook("template.xlsx", new LoadOptions(Cells.LoadFormat.Auto));
// access CellsCollection of the worksheet containing data to be converted
var cells = workbook.Worksheets[0].Cells;
// create & set ExportRangeToJsonOptions for advanced options
var exportOptions = new Utility.ExportRangeToJsonOptions();
// create a range of cells containing data to be exported
var range = cells.CreateRange(0, 0, cells.LastCell.Row + 1, cells.LastCell.Column + 1);
// export range as JSON data
string jsonData = Cells.Utility.JsonUtility.ExportRangeToJson(range, exportOptions);
// write data file to disc in JSON format
System.IO.File.WriteAllText("output.json", jsonData); 
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="แปลงแผ่นงาน Excel เป็น JPG, BMP, PNG & GIF" %}}
 แผ่นงานแต่ละไฟล์ของไฟล์ Excel สามารถแปลงเป็นรูปแบบภาพต่างๆ ที่กำหนดโดย[ImageOrPrintOptions.ImageType](https://reference.aspose.com/cells/net/aspose.cells.rendering/imageorprintoptions/properties/imagetype) คุณสมบัติ. ค่าเริ่มต้นคือ `ImageFormat.Bmp`
{{% blocks/products/pf/feature-page-code h3="C# รหัสสำหรับการแปลง Excel เป็นรูปภาพ" %}}
```cs
// load template spreadsheet
var workbook = new Aspose.Cells.Workbook("template.xlsx");
// create & set an instance of ImageOrPrintOptions
var options = new Aspose.Cells.Rendering.ImageOrPrintOptions();
options.OnePagePerSheet = true;
// set output image format
options.ImageType = Aspose.Cells.Drawing.ImageType.Jpeg;
// create SheetRender for first worksheet in the collection
var render = new Aspose.Cells.Rendering.SheetRender(workbook.Worksheets[0], options);
// render worksheet to image
render.ToImage(0, "output.jpg");
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="แปลง Excel เป็น Word & PowerPoint" %}}
 เป็นไปได้ที่จะโหลดสเปรดชีตและแปลงเป็นไฟล์ Word DOCX & PowerPoint PPTX ขณะใช้งาน[ตัวเลือก DocxSave](https://reference.aspose.com/cells/net/aspose.cells/docxsaveoptions) & [ตัวเลือก PptxSave](https://reference.aspose.com/cells/net/aspose.cells/pptxsaveoptions)ชั้นเรียนที่แสดงด้านล่าง
{{% blocks/products/pf/feature-page-code h3="รหัส C# สำหรับการแปลง Excel เป็น Word & PowerPoint" %}}
```cs
// load the template file
var workbook = new Aspose.Cells.Workbook("template.xlsx");
// save spreadsheet as DOCX
workbook.Save("output.docx", new Aspose.Cells.DocxSaveOptions());
// save spreadsheet as PPTX
workbook.Save("output.pptx", new Aspose.Cells.PptxSaveOptions());
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
