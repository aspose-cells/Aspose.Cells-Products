---
title: การแปลงไฟล์ Microsoft Excel ผ่าน Java 
url: /th/java/conversion/
description: แปลง Excel XLS, XLSX, ODS, CSV เป็น PDF, XPS, HTML, JPEG, HTML และรูปแบบยอดนิยมอื่นๆ ด้วยโค้ด Java เพียงไม่กี่บรรทัด
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> การแปลงไฟล์ Excel ผ่าน Java" h2="บันทึกเอกสาร Microsoft Excel เป็นสเปรดชีต เว็บ รูปภาพ และรูปแบบเค้าโครงคงที่" >}}

{{% blocks/products/pf/feature-page-summary %}}
สำหรับแอปพลิเคชันหรือโซลูชัน **โปรแกรมแปลงไฟล์ Excel** Java ไลบรารีของ Excel ช่วยเพิ่มความเร็วในการเขียนโปรแกรมสเปรดชีตและกระบวนการแปลงในขณะที่จัดการรูปแบบต่างๆ เช่น XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS นอกจากนี้ยังช่วยให้ **แปลงไฟล์ Excel เป็น PDF**, XPS, HTML, MHTML, ข้อความธรรมดา และรูปแบบรูปภาพยอดนิยม เช่น TIFF, JPG, PNG, BMP และ SVG
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="การแปลงระหว่างรูปแบบ Microsoft Excel" %}}
การแปลงรูปแบบสเปรดชีตระหว่างกัน จำเป็นต้องโหลดสเปรดชีตที่มีอินสแตนซ์ของ . เท่านั้น [สมุดงาน](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) และบันทึกในรูปแบบที่ต้องการในขณะที่เลือกค่าที่เหมาะสมจาก [บันทึกรูปแบบ](https://reference.aspose.com/cells/java/com.aspose.cells/SaveFormat) การแจงนับ
{{% blocks/products/pf/feature-page-code h3="Java ตัวอย่างโค้ดสำหรับการแปลงรูปแบบไฟล์ Excel" %}}

```cs
// โหลดไฟล์ต้นฉบับ
var wkb = new Workbook("sourceFile.xls");
// บันทึกเป็นรูปแบบ XLSX, ODS, SXC & FODS
wkb.save("xlsx-output.xlsx", SaveFormat.XLSX);
wkb.save("ods-output.ods", SaveFormat.ODS);
wkb.save("scx-output.scx", SaveFormat.SXC);
wkb.save("fods-output.fods", SaveFormat.FODS);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-json xlsx-to-pdf xlsx-to-html xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="แปลง Excel เป็น PDF, XPS, HTML & MD" %}}
มีคลาสเฉพาะเพื่อควบคุมกระบวนการแปลงสำหรับรูปแบบเอาต์พุตเฉพาะเช่น [PdfSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/PdfSaveOptions) เพื่อแปลงไฟล์ Excel เป็น PDF [XpsSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/XpsSaveOptions) เพื่อส่งออก Excel เป็น XPS [HtmlSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/HtmlSaveOptions) เพื่อแสดง Excel เป็น HTML และ [MarkdownSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/MarkdownSaveOptions) สำหรับการแปลง Excel เป็น Markdown 
{{% blocks/products/pf/feature-page-code h3="Java ตัวอย่างโค้ดสำหรับ Excel เป็น PDF และรูปแบบเว็บ" %}}

```cs
// โหลดเทมเพลตไฟล์ Excel จาก disc
var bk = new Workbook("source-file.xlsx");

// แปลง Excel เป็น PDF โดยใช้ Java
// สร้างตัวเลือก PDF
PdfSaveOptions options = new PdfSaveOptions();
options.setCompliance(PdfCompliance.PDF_A_1_A);

bk.save("excel-to-pdf.pdf", options);
// บันทึก Excel ใน XPS
bk.save("output.xps", new XpsSaveOptions());
// บันทึก Excel ใน HTML
bk.save("output.html", new HtmlSaveOptions());
// บันทึก Excel ใน Markdown (MD)
bk.save("output.md", new MarkdownSaveOptions());

// สามารถตั้งค่าตัวเลือกการบันทึกที่เกี่ยวข้องได้ตามต้องการก่อนที่จะบันทึกลงในรูปแบบที่เกี่ยวข้อง

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="แปลง JSON เป็น Excel และ Excel เป็น JSON" %}}
ข้อมูล JSON สามารถนำเข้าสู่อินสแตนซ์ของคลาส Workbook ด้วยความช่วยเหลือของ [JSONUtility.importData](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility#importData) สำหรับการประมวลผลเพิ่มเติมหรือการแปลงอย่างง่ายเป็นรูปแบบที่รองรับ ในทำนองเดียวกัน ข้อมูลเวิร์กชีตสามารถส่งออกเป็น JSON ได้โดยการสร้าง a [พิสัย](https://reference.aspose.com/cells/java/com.aspose.cells/range) หรือเซลล์แล้วเรียก [exportRangeToJson](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility) กระบวนการ.
{{% blocks/products/pf/feature-page-code h3="Java โค้ดสำหรับการแปลง JSON เป็น Excel" %}}
```cs
Workbook workbook = new Workbook(path + "source-file.xlsx");
Worksheet wks = workbook.getWorksheets().get(0);
		
// อ่านไฟล์
File file = new File(path + "source-data.json");
BufferedReader bufferedReader = new BufferedReader(new FileReader(file));
String jsonInput = "";
String tempString;
while ((tempString = bufferedReader.readLine()) != null) {
	jsonInput = jsonInput + tempString; 
}
bufferedReader.close();
							
// ตั้งค่า JsonLayoutOptions
JsonLayoutOptions options = new JsonLayoutOptions();
options.setIgnoreArrayTitle(true);
options.setArrayAsTable(true);

// นำเข้าข้อมูล JSON
JSONUtility.importData(jsonInput, wks.getCells(), 0, 0, options);

// บันทึกไฟล์ Excel
workbook.save(path + "excel-to-json.out.xlsx");

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Java ซอร์สโค้ดสำหรับการแปลง Excel เป็น JSON" %}}
```cs
// โหลดไฟล์ XLSX ด้วยอินสแตนซ์ของ Workbook
Workbook workbook = new Workbook("sourceFile.xlsx");
// เข้าถึง CellsCollection ของเวิร์กชีตที่มีข้อมูลที่จะแปลง
Cells cells = workbook.getWorksheets().get(0).getCells();
// สร้างและตั้งค่า ExportRangeToJsonOptions สำหรับตัวเลือกขั้นสูง
ExportRangeToJsonOptions exportOptions = new ExportRangeToJsonOptions();
// สร้างช่วงของเซลล์ที่มีข้อมูลที่จะส่งออก
Range range = cells.createRange(0, 0, cells.getLastCell().getRow() + 1, cells.getLastCell().getColumn() + 1);
// ช่วงการส่งออกเป็นข้อมูล JSON
String jsonData = JsonUtility.exportRangeToJson(range, exportOptions);
// เขียนข้อมูลลงแผ่นดิสก์ในรูปแบบ JSON
BufferedWriter writer = new BufferedWriter(new FileWriter("output.json"));
writer.write(jsonData);
writer.close();    

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="บันทึกแผ่นงาน Excel ไปยังรูปภาพ" %}}
แผ่นงานแต่ละแผ่นสามารถแปลงเป็นรูปแบบภาพต่างๆ ได้ รวมทั้ง JPG, BMP, PNG และ GIF ที่กำหนดโดยคุณสมบัติ ImageType สำหรับกรณี **แปลง Excel เป็นรูปภาพ** ให้เลือกกรณีที่เกี่ยวข้องจากลิงก์
{{% blocks/products/pf/feature-page-code h3="Java โค้ดสำหรับ Excel เป็นการแปลงรูปภาพ" %}}
```cs
// โหลดสเปรดชีตเทมเพลต
var wkb = new Workbook("template.xlsx");

// สร้างวัตถุสำหรับ ImageOptions
ImageOrPrintOptions imgOptions = new ImageOrPrintOptions();

// ตั้งค่าประเภทภาพ
imgOptions.setImageType(ImageType.PNG);

// รับใบงานแรก
Worksheet sheet = wkb.getWorksheets().get(0);

// สร้างวัตถุ SheetRender สำหรับแผ่นงานเป้าหมาย
SheetRender sr = new SheetRender(sheet, imgOptions);
for (int j = 0; j < sr.getPageCount(); j++) {
	// สร้างภาพสำหรับเวิร์กชีต
	sr.toImage(j, dataDir + "WToImage-out" + j + ".png");
}

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="แปลง Microsoft Excel เป็น Word และ PowerPoint" %}}
สามารถโหลดสเปรดชีตใดก็ได้และแปลงเป็นไฟล์ Word DOCX และ PowerPoint PPTX ขณะใช้งาน [DocxSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/DocxSaveOptions) & [PptxSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/PptxSaveOptions) ชั้นเรียนดังที่แสดงด้านล่าง
{{% blocks/products/pf/feature-page-code h3="Java โค้ดสำหรับการแปลง Excel เป็น Word & PowerPoint" %}}
```cs
// โหลดไฟล์เทมเพลต
var wkb = new Workbook("template.xlsx");
// บันทึกสเปรดชีตเป็น DOCX
wkb.save("output.docx", new DocxSaveOptions());
// บันทึกสเปรดชีตเป็น PPTX
wkb.save("output.pptx", new PptxSaveOptions());

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}