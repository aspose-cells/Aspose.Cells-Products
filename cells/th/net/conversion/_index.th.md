---
title: การแปลงไฟล์ Microsoft Excel ผ่าน C# 

description: แปลง Excel XLS, XLSX, ODS, CSV เป็น PDF, XPS, HTML, JPEG, HTML และรูปแบบยอดนิยมอื่นๆ ด้วยโค้ด C# เพียงไม่กี่บรรทัด
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> การแปลงรูปแบบ Excel ผ่าน .NET" h2="นำเข้าและส่งออกไฟล์ Excel เป็นสเปรดชีต เว็บ รูปภาพ และรูปแบบเค้าโครงคงที่" >}}

{{% blocks/products/pf/feature-page-summary %}}
.NET ไลบรารี Excel ช่วยเพิ่มความเร็วในการเขียนโปรแกรมสเปรดชีตและกระบวนการแปลง ในขณะที่สนับสนุนรูปแบบยอดนิยม เช่น XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS นอกจากนี้ยังอนุญาตให้ส่งออกไฟล์ Excel เป็น PDF, XPS, HTML, MHTML, ข้อความธรรมดา และรูปแบบรูปภาพยอดนิยม เช่น TIFF, JPG, PNG, BMP และ SVG
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="แปลง Excel เป็น XLSX, ODS, SXC & FODS" %}}
การแปลงรูปแบบสเปรดชีตระหว่างกัน จำเป็นต้องโหลดสเปรดชีตที่มีอินสแตนซ์ของ . เท่านั้น [สมุดงาน](https://reference.aspose.com/cells/net/aspose.cells/workbook) และบันทึกในรูปแบบที่ต้องการในขณะที่เลือกค่าที่เหมาะสมจาก [บันทึกรูปแบบ](https://reference.aspose.com/cells/net/aspose.cells/saveformat) การแจงนับ
{{% blocks/products/pf/feature-page-code h3="C# โค้ดสำหรับการแปลงรูปแบบไฟล์ Excel" %}}

```cs
// โหลดไฟล์เทมเพลต
var workbook = new Aspose.Cells.Workbook("template.xls");
// บันทึกเป็นรูปแบบ XLSX, ODS, SXC & FODS
workbook.Save("output.xlsx", Aspose.Cells.SaveFormat.Xlsx);
workbook.Save("output.ods", Aspose.Cells.SaveFormat.Ods);
workbook.Save("output.scx", Aspose.Cells.SaveFormat.Sxc);
workbook.Save("output.fods", Aspose.Cells.SaveFormat.Fods);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="แปลง Excel เป็น PDF, XPS, HTML & MD" %}}
มีคลาสเฉพาะเพื่อควบคุมกระบวนการแปลงสำหรับรูปแบบเอาต์พุตเฉพาะเช่น [PdfSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/pdfsaveoptions) เพื่อส่งออกไฟล์ Excel เป็น PDF [XpsSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/xpssaveoptions) สำหรับการแปลง Excel เป็น XPS [HtmlSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/htmlsaveoptions) เพื่อแสดง Excel เป็น HTML และ [MarkdownSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/markdownsaveoptions) สำหรับการแปลง Excel เป็น Markdown 
{{% blocks/products/pf/feature-page-code h3="C# โค้ดสำหรับ Excel เป็น PDF และรูปแบบเว็บ" %}}

```cs
// โหลดเทมเพลตไฟล์ Excel จาก disc
var book = new Aspose.Cells.Workbook("template.xlsx");
// บันทึก Excel ในรูปแบบ PDF/A-1a
book.Save("output.pdf", new Aspose.Cells.PdfSaveOptions() { Compliance = PdfComplianceVersion.PdfA1a });
// บันทึก Excel ใน XPS ด้วย 1 หน้าต่อแผ่นงาน
book.Save("output.xps", new Aspose.Cells.XpsSaveOptions() { OnePagePerSheet = true });
// บันทึก Excel เป็น HTML พร้อมรูปภาพเป็น Base64
book.Save("output.html", new Aspose.Cells.HtmlSaveOptions() { ExportImagesAsBase64 = true });
// บันทึก Excel ใน Markdown (MD) ในขณะที่ยังคงการจัดรูปแบบเซลล์ไว้
book.Save("output.md", new Aspose.Cells.MarkdownSaveOptions() { FormatStrategy = Cells.CellValueFormatStrategy.CellStyle });

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="แปลง JSON เป็น Excel & Excel เป็น JSON" %}}
ข้อมูล JSON สามารถนำเข้าสู่อินสแตนซ์ของ [Cells](https://reference.aspose.com/cells/net/aspose.cells/cells) ชั้นเรียนด้วยความช่วยเหลือของ [JsonUtility.ImportData](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/importdata) สำหรับการประมวลผลเพิ่มเติมหรือการแปลงอย่างง่ายเป็นรูปแบบที่รองรับ ในทำนองเดียวกัน [ใบงาน](https://reference.aspose.com/cells/net/aspose.cells/worksheet) ข้อมูลสามารถส่งออกเป็น JSON ได้โดยการสร้าง a [พิสัย](https://reference.aspose.com/cells/net/aspose.cells/range) หรือเซลล์แล้วเรียก [JsonUtility.ExportRangeToJson](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/exportrangetojson) กระบวนการ.
{{% blocks/products/pf/feature-page-code h3="C# โค้ดสำหรับการแปลง JSON เป็น Excel" %}}
```cs
// สร้างวัตถุสมุดงาน
var workbook = new Cells.Workbook();
var worksheet = workbook.Worksheets[0];
// อ่านข้อมูล JSON จากไฟล์
string jsonInput = File.ReadAllText("Data.json");
// ตั้งค่า JsonLayoutOptions เพื่อจัดการกับอาร์เรย์เป็น Table
var options = new Cells.Utility.JsonLayoutOptions();
options.ArrayAsTable = true;
// นำเข้าข้อมูล JSON ไปยังแผ่นงานโดยเริ่มต้นที่เซลล์ A1
Cells.Utility.JsonUtility.ImportData(jsonInput, worksheet.Cells, 0, 0, options);
// บันทึกไฟล์ผลลัพธ์ในรูปแบบ XLSX
workbook.Save("output.xlsx", Cells.SaveFormat.Auto); 

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# โค้ดสำหรับการแปลง Excel เป็น JSON" %}}
```cs
// โหลดไฟล์ XLSX ด้วยอินสแตนซ์ของ Workbook
var workbook = new Workbook("template.xlsx", new LoadOptions(Cells.LoadFormat.Auto));
// เข้าถึง CellsCollection ของเวิร์กชีตที่มีข้อมูลที่จะแปลง
var cells = workbook.Worksheets[0].Cells;
// สร้างและตั้งค่า ExportRangeToJsonOptions สำหรับตัวเลือกขั้นสูง
var exportOptions = new Utility.ExportRangeToJsonOptions();
// สร้างช่วงของเซลล์ที่มีข้อมูลที่จะส่งออก
var range = cells.CreateRange(0, 0, cells.LastCell.Row + 1, cells.LastCell.Column + 1);
// ช่วงการส่งออกเป็นข้อมูล JSON
string jsonData = Cells.Utility.JsonUtility.ExportRangeToJson(range, exportOptions);
// เขียนไฟล์ข้อมูลลงแผ่นดิสก์ในรูปแบบ JSON
System.IO.File.WriteAllText("output.json", jsonData); 

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="แปลงแผ่นงาน Excel เป็น JPG, BMP, PNG & GIF" %}}
แผ่นงานแต่ละไฟล์ของไฟล์ Excel สามารถแปลงเป็นรูปแบบภาพต่างๆ ที่กำหนดโดย [ImageOrPrintOptions.ImageType](https://reference.aspose.com/cells/net/aspose.cells.rendering/imageorprintoptions/properties/imagetype) คุณสมบัติ. ค่าเริ่มต้นคือ 'ImageFormat.Bmp'
{{% blocks/products/pf/feature-page-code h3="C# โค้ดสำหรับ Excel เป็นการแปลงรูปภาพ" %}}
```cs
// โหลดสเปรดชีตเทมเพลต
var workbook = new Aspose.Cells.Workbook("template.xlsx");
// สร้างและตั้งค่าอินสแตนซ์ของ ImageOrPrintOptions
var options = new Aspose.Cells.Rendering.ImageOrPrintOptions();
options.OnePagePerSheet = true;
// กำหนดรูปแบบภาพที่ส่งออก
options.ImageType = Aspose.Cells.Drawing.ImageType.Jpeg;
// สร้าง SheetRender สำหรับแผ่นงานแรกในคอลเล็กชัน
var render = new Aspose.Cells.Rendering.SheetRender(workbook.Worksheets[0], options);
// เรนเดอร์แผ่นงานเป็นรูปภาพ
render.ToImage(0, "output.jpg");

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="แปลง Excel เป็น Word & PowerPoint" %}}
สามารถโหลดสเปรดชีตใดก็ได้และแปลงเป็นไฟล์ Word DOCX และ PowerPoint PPTX ขณะใช้งาน [DocxSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/docxsaveoptions) & [PptxSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/pptxsaveoptions) ชั้นเรียนดังที่แสดงด้านล่าง
{{% blocks/products/pf/feature-page-code h3="โค้ด C# สำหรับการแปลง Excel เป็น Word & PowerPoint" %}}
```cs
// โหลดไฟล์เทมเพลต
var workbook = new Aspose.Cells.Workbook("template.xlsx");
// บันทึกสเปรดชีตเป็น DOCX
workbook.Save("output.docx", new Aspose.Cells.DocxSaveOptions());
// บันทึกสเปรดชีตเป็น PPTX
workbook.Save("output.pptx", new Aspose.Cells.PptxSaveOptions());

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
