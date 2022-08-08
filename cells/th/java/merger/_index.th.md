---
title: รวมไฟล์ Excel ต่างๆ ให้เป็นไฟล์เดียวใน Java
url: /th/java/merger/
description: รวมไฟล์ Excel โดยใช้ Java ลงในแผ่นงานหลายแผ่นหรือแผ่นเดียว ผสาน รวม หรือเชื่อมเอกสาร Excel เป็น PDF, รูปภาพ และ HTML เช่นกัน
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> การรวมไฟล์ Excel ผ่าน Java" h2="รวมไฟล์ Excel สองไฟล์ขึ้นไปในสเปรดชีตเดียวโดยใช้ Java code" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java ไลบรารี Excel](/cells/java/) มีหลายวิธีในการรวมเวิร์กบุ๊กกับเนื้อหาประเภทต่างๆ เช่น สูตร รูปภาพ ข้อมูล แผนภูมิ ฯลฯ ไว้ในเอกสารสเปรดชีตเดียว รูปแบบไฟล์ที่รองรับ ได้แก่ XLS, XLSX, XLSB, XLT, XLTX, XLTM, ODS, CSV, TSV และอื่นๆ
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="รวมไฟล์ Excel กับรูปภาพและแผนภูมิ" %}}
วิธีที่ง่ายที่สุดในการรวมไฟล์ Excel สองไฟล์ที่มีรูปภาพและแผนภูมิคือการเรียก [Workbook.combine](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#combine(com.aspose.cells.Workbook)) กระบวนการ. อนุญาตให้รวมไฟล์ Excel ประเภทเดียวกันลงในสเปรดชีตเดียว
{{% blocks/products/pf/feature-page-code h3="Java โค้ดสำหรับรวมไฟล์ Excel" %}}

```cs
// โหลดไฟล์ Excel แรก
var book1 = new Workbook("with-charts.xlsx");
// โหลดไฟล์ Excel ที่สองลงในอินสแตนซ์ที่แยกจากกัน
var book2 = new Workbook("with-images.xlsx");

// รวมสมุดงานสองเล่ม
book1.combine(book2);
// บันทึกสมุดงานเป้าหมาย 
book1.save("combined.xlsx");

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="รวมไฟล์ Excel หลายไฟล์" %}}
[CellsHelper.mergeFiles](https://reference.aspose.com/cells/java/com.aspose.cells/cellshelper#mergeFiles) method รองรับการผสานข้อมูล รูปแบบ และสูตรของไฟล์ Excel เข้ากับสเปรดชีตใหม่ที่มีรูปแบบเดียวกัน เป็นวิธีที่มีประสิทธิภาพในการรวมหลายไฟล์ในขณะที่ใช้แคช 
{{% blocks/products/pf/feature-page-code h3="Java รหัสเพื่อรวมไฟล์ Excel หลายไฟล์" %}}

```cs
// สร้าง Array (ความยาว=2)
String[] files = new String[2];
// ระบุเส้นทางของไฟล์ที่จะรวม
files[0] = "Book1.xls";
files[1] = "Book2.xls";
// ผสานไฟล์เพื่อบันทึกผลลัพธ์
CellsHelper.mergeFiles(files, "cache", "merged.xls");


```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="รวมไฟล์ Excel โดยการคัดลอกแผ่นงาน" %}}
[ใบงาน.copy](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet#copy(com.aspose.cells.Worksheet)สามารถใช้เพื่อคัดลอกข้อมูลและการจัดรูปแบบจากเวิร์กชีตต้นทางไปยังเวิร์กชีตอื่นภายในหรือระหว่างเวิร์กบุ๊ก เมธอดนี้ใช้ออบเจ็กต์เวิร์กชีตต้นทางเป็นพารามิเตอร์
{{% blocks/products/pf/feature-page-code h3="Java รหัสสำหรับคัดลอกแผ่นงานระหว่างสมุดงาน" %}}

```cs
// สร้างสมุดงาน
Workbook excelWorkbook0 = new Workbook(dataDir + "book1.xls");

// สร้างสมุดงานอื่น
Workbook excelWorkbook1 = new Workbook();

// คัดลอกแผ่นแรกของหนังสือเล่มแรกไปยังหนังสือเล่มที่สอง
excelWorkbook1.getWorksheets().get(0).copy(excelWorkbook0.getWorksheets().get(0));

// บันทึกไฟล์.
excelWorkbook1.save(dataDir + "out.xls", FileFormatType.EXCEL_97_TO_2003);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Merger" >}}