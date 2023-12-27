---
title:  Microsoft การแปลงไฟล์ Excel via Java
description: Aspose.Cells for Java ห้องสมุด. แปลง EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL, JPG, PNG และรูปแบบอื่นๆ ด้วยโค้ด Java เพียงไม่กี่บรรทัด
keywords: [Java Aspose.Cells., excel to pdf., excel to json., html to xps., csv to json., json to pdf., xml to excel and Convert files between various formats in Java]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> การแปลงไฟล์ Excel via Java" h2="บันทึก Microsoft เอกสาร Excel เป็นสเปรดชีต เว็บ รูปภาพ และรูปแบบคงที่" >}}

{{% blocks/products/pf/feature-page-summary %}}
 สำหรับอย่างใดอย่างหนึ่ง**ตัวแปลง Excel** แอปพลิเคชันหรือโซลูชัน Java Excel Library เร่งความเร็วการเขียนโปรแกรมสเปรดชีตและกระบวนการแปลงในขณะที่จัดการหลายรูปแบบรวมถึง XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, 07619 3481 นอกจากนี้ยังอนุญาตให้ *แปลงไฟล์ Excel เป็น PDF**, XPS, HTML, MHTML, Plain Text และรูปแบบรูปภาพยอดนิยม เช่น TIFF, JPG, PNG, BMP และ SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="การแปลงรูปแบบ Excel Microsoft ระหว่างกัน" %}}
 การแปลงรูปแบบสเปรดชีตระหว่างกันต้องโหลดสเปรดชีตที่มีอินสแตนซ์เท่านั้น[สมุดงาน](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) และบันทึกกลับในรูปแบบที่ต้องการพร้อมเลือกค่าที่เหมาะสมจาก[บันทึกรูปแบบ](https://reference.aspose.com/cells/java/com.aspose.cells/SaveFormat) การแจงนับ
{{% blocks/products/pf/feature-page-code h3="Java ตัวอย่างโค้ดสำหรับการแปลงรูปแบบไฟล์ Excel" %}}

```cs
// load the source file
var wkb = new Workbook("sourceFile.xls");
// save as XLSX, ODS, SXC & FODS formats
wkb.save("xlsx-output.xlsx", SaveFormat.XLSX);
wkb.save("ods-output.ods", SaveFormat.ODS);
wkb.save("scx-output.scx", SaveFormat.SXC);
wkb.save("fods-output.fods", SaveFormat.FODS);
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-json xlsx-to-pdf xlsx-to-html xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="แปลง Excel เป็น PDF, XPS, HTML และ MD" %}}
 มีคลาสเฉพาะทางเพื่อควบคุมกระบวนการแปลงสำหรับรูปแบบเอาต์พุตเฉพาะเช่น[ตัวเลือก PdfSave](https://reference.aspose.com/cells/java/com.aspose.cells/PdfSaveOptions) เพื่อแปลงไฟล์ Excel เป็น PDF,[XpsSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/XpsSaveOptions) เพื่อส่งออก Excel เป็น XPS,[HtmlSaveตัวเลือก](https://reference.aspose.com/cells/java/com.aspose.cells/HtmlSaveOptions) เพื่อเรนเดอร์ Excel เป็น HTML และ[MarkdownSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/MarkdownSaveOptions) สำหรับการแปลง Excel เป็น Markdown
{{% blocks/products/pf/feature-page-code h3="Java โค้ดตัวอย่างสำหรับ Excel ถึง PDF และรูปแบบเว็บ" %}}

```cs
// load template Excel file from disc
var bk = new Workbook("source-file.xlsx");

// convert Excel to PDF using Java
// Create PDF options
PdfSaveOptions options = new PdfSaveOptions();
options.setCompliance(PdfCompliance.PDF_A_1_A);

bk.save("excel-to-pdf.pdf", options);
// save Excel in XPS
bk.save("output.xps", new XpsSaveOptions());
// save Excel in HTML
bk.save("output.html", new HtmlSaveOptions());
// save Excel in Markdown (MD)
bk.save("output.md", new MarkdownSaveOptions());

// one can set relevant save options as of his choice before saving into relevant format
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="แปลง JSON เป็น Excel และ Excel เป็น JSON" %}}
 ข้อมูล JSON สามารถนำเข้าไปยังอินสแตนซ์ของคลาส Workbook ได้โดยใช้[JSONUtility.importData](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility#importData) สำหรับการประมวลผลเพิ่มเติมหรือการแปลงเป็นรูปแบบที่รองรับอย่างง่าย ในทำนองเดียวกัน ข้อมูลในเวิร์กชีตสามารถส่งออกเป็น JSON ได้ด้วยการสร้าง[พิสัย](https://reference.aspose.com/cells/java/com.aspose.cells/range) หรือเซลล์และเรียก[ส่งออก RangeToJson](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility) วิธี.
{{% blocks/products/pf/feature-page-code h3="รหัส Java สำหรับการแปลง JSON เป็น Excel" %}}
```cs
Workbook workbook = new Workbook(path + "source-file.xlsx");
Worksheet wks = workbook.getWorksheets().get(0);
		
// Read File
File file = new File(path + "source-data.json");
BufferedReader bufferedReader = new BufferedReader(new FileReader(file));
String jsonInput = "";
String tempString;
while ((tempString = bufferedReader.readLine()) != null) {
	jsonInput = jsonInput + tempString; 
}
bufferedReader.close();
							
// Set JsonLayoutOptions
JsonLayoutOptions options = new JsonLayoutOptions();
options.setIgnoreArrayTitle(true);
options.setArrayAsTable(true);

// Import JSON Data
JSONUtility.importData(jsonInput, wks.getCells(), 0, 0, options);

// Save Excel file
workbook.save(path + "excel-to-json.out.xlsx");
```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Java ซอร์สโค้ดสำหรับ Excel เป็น JSON การแปลง" %}}
```cs
// load XLSX file with an instance of Workbook
Workbook workbook = new Workbook("sourceFile.xlsx");
// access CellsCollection of the worksheet containing data to be converted
Cells cells = workbook.getWorksheets().get(0).getCells();
// create & set ExportRangeToJsonOptions for advanced options
ExportRangeToJsonOptions exportOptions = new ExportRangeToJsonOptions();
// create a range of cells containing data to be exported
Range range = cells.createRange(0, 0, cells.getLastCell().getRow() + 1, cells.getLastCell().getColumn() + 1);
// export range as JSON data
String jsonData = JsonUtility.exportRangeToJson(range, exportOptions);
// write data to disc in JSON format
BufferedWriter writer = new BufferedWriter(new FileWriter("output.json"));
writer.write(jsonData);
writer.close();    
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="บันทึกแผ่นงาน Excel ลงในรูปภาพ" %}}
 แต่ละแผ่นงานสามารถแปลงเป็นรูปแบบภาพที่แตกต่างกันได้ รวมถึง JPG, BMP, PNG และ GIF กำหนดโดยคุณสมบัติ ImageType สำหรับอย่างใดอย่างหนึ่ง**แปลง Excel เป็นรูปภาพ** กรณี ให้เลือกกรณีที่เกี่ยวข้องจากลิงก์
{{% blocks/products/pf/feature-page-code h3="Java รหัสสำหรับการแปลง Excel เป็นรูปภาพ" %}}
```cs
// load template spreadsheet
var wkb = new Workbook("template.xlsx");

// Create an object for ImageOptions
ImageOrPrintOptions imgOptions = new ImageOrPrintOptions();

// Set the image type
imgOptions.setImageType(ImageType.PNG);

// Get the first worksheet.
Worksheet sheet = wkb.getWorksheets().get(0);

// Create a SheetRender object for the target sheet
SheetRender sr = new SheetRender(sheet, imgOptions);
for (int j = 0; j < sr.getPageCount(); j++) {
	// Generate an image for the worksheet
	sr.toImage(j, dataDir + "WToImage-out" + j + ".png");
}
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="แปลง Microsoft Excel เป็น Word และ PowerPoint" %}}
คุณสามารถโหลดสเปรดชีตใดก็ได้และแปลงเป็นไฟล์ Word DOCX & PowerPoint PPTX ในขณะที่ใช้งาน[DocxSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/DocxSaveOptions) & [PptxSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/PptxSaveOptions) ชั้นเรียนตามที่แสดงด้านล่าง
{{% blocks/products/pf/feature-page-code h3="Java รหัสสำหรับ Excel เป็น Word และ PowerPoint การแปลง" %}}
```cs
// load the template file
var wkb = new Workbook("template.xlsx");
// save spreadsheet as DOCX
wkb.save("output.docx", new DocxSaveOptions());
// save spreadsheet as PPTX
wkb.save("output.pptx", new PptxSaveOptions());
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
