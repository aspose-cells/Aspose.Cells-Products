---
title: รวมไฟล์ Excel ที่แตกต่างกันเป็นไฟล์เดียวใน Java
description: รวมไฟล์ Excel โดยใช้ Java เป็นหลายแผ่นหรือแผ่นเดียว รวม รวม หรือเชื่อมเอกสาร Excel เป็น PDF รูปภาพ และ HTML ด้วย
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> การรวมไฟล์ Excel via Java" h2="รวมไฟล์ Excel สองไฟล์ขึ้นไปในสเปรดชีตเดียวโดยใช้รหัส Java" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java คลังเอ็กเซล](/cells/th/java/) มีหลายวิธีในการรวมสมุดงานกับเนื้อหาประเภทต่างๆ เช่น สูตร รูปภาพ ข้อมูล แผนภูมิ ฯลฯ ไว้ในเอกสารสเปรดชีตเดียว รูปแบบไฟล์ที่รองรับ ได้แก่ XLS, XLSX, XLSB, XLT, XLTX, XLTM, ODS, CSV, TSV และอื่นๆ
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="รวมไฟล์ Excel เข้ากับรูปภาพและแผนภูมิ" %}}
 วิธีที่ง่ายที่สุดในการรวมไฟล์ Excel สองไฟล์ที่มีรูปภาพและแผนภูมิคือการเรียก[Workbook.combine](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#combine(com.aspose.cells.Workbook)) วิธี. อนุญาตให้รวมไฟล์ Excel ประเภทเดียวกันไว้ในสเปรดชีตเดียว
{{% blocks/products/pf/feature-page-code h3="Java รหัสเพื่อรวมไฟล์ Excel" %}}

```cs
// load first Excel file
var book1 = new Workbook("with-charts.xlsx");
// load second Excel file into a separate instance
var book2 = new Workbook("with-images.xlsx");

// merge two workbooks
book1.combine(book2);
// save the target workbook 
book1.save("combined.xlsx");
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="รวมไฟล์ Excel หลายไฟล์" %}}
[CellsHelper.mergeFiles](https://reference.aspose.com/cells/java/com.aspose.cells/cellshelper#mergeFiles) เมธอดรองรับการรวมข้อมูล สไตล์ และสูตรของไฟล์ Excel เข้ากับสเปรดชีตใหม่ที่มีรูปแบบเดียวกัน เป็นวิธีที่มีประสิทธิภาพในการรวมไฟล์หลายไฟล์ในขณะที่ใช้การแคช
{{% blocks/products/pf/feature-page-code h3="Java รหัสเพื่อรวมไฟล์ Excel หลายไฟล์" %}}

```cs
// create an Array (length=2)
String[] files = new String[2];
// specify file paths to be merged
files[0] = "Book1.xls";
files[1] = "Book2.xls";
// merge the files to save the result
CellsHelper.mergeFiles(files, "cache", "merged.xls");

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="รวมไฟล์ Excel โดยการคัดลอกแผ่นงาน" %}}
[Worksheet.copy](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet#copy(com.aspose.cells.Worksheet)) สามารถใช้เพื่อคัดลอกข้อมูลและการจัดรูปแบบจากแผ่นงานต้นทางไปยังแผ่นงานอื่นภายในหรือระหว่างสมุดงาน วิธีการใช้วัตถุแผ่นงานต้นฉบับเป็นพารามิเตอร์
{{% blocks/products/pf/feature-page-code h3="Java รหัสเพื่อคัดลอกแผ่นงานระหว่างสมุดงาน" %}}

```cs
// Create a Workbook.
Workbook excelWorkbook0 = new Workbook(dataDir + "book1.xls");

// Create another Workbook.
Workbook excelWorkbook1 = new Workbook();

// Copy the first sheet of the first book into second book.
excelWorkbook1.getWorksheets().get(0).copy(excelWorkbook0.getWorksheets().get(0));

// Save the file.
excelWorkbook1.save(dataDir + "out.xls", FileFormatType.EXCEL_97_TO_2003);
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/other-supported-section title="รูปแบบการผสานอื่นๆ ที่รองรับ" subTitle="การใช้ Java ทำให้สามารถผสานรูปแบบไฟล์อื่นๆ ได้มากมาย รวมทั้ง.." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/csv/" name="CSV" description="ค่าที่คั่นด้วยเครื่องหมายจุลภาค" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/html/" name="HTML" description="ภาษามาร์กอัปข้อความไฮเปอร์" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/mhtml/" name="MHTML" description="รูปแบบการเก็บถาวรของหน้าเว็บ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/ods/" name="ODS" description="ไฟล์สเปรดชีต OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/tsv/" name="TSV" description="ค่าที่คั่นด้วยแท็บ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/txt/" name="TXT" description="เอกสารข้อความ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xls/" name="XLS" description="รูปแบบไบนารีของ Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsb/" name="XLSB" description="ไฟล์สมุดงานไบนารี Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsm/" name="XLSM" description="ไฟล์สเปรดชีต" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsx/" name="XLSX" description="ไฟล์ OOXML Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlt/" name="XLT" description="Microsoft เทมเพลต Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xltm/" name="XLTM" description="เทมเพลตที่เปิดใช้งานแมโครของ Excel" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}
