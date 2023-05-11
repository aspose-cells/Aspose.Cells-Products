---
title: แยกสเปรดชีต Excel ออกเป็นแผ่นงานใน Java
description: ซอร์สโค้ด Java ที่อธิบายวิธีแยกไฟล์ Excel Microsoft ออกเป็นหลายเอกสารโดยใช้ไลบรารี Java Excel
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> การแยกไฟล์ Excel via Java" h2="แยกสเปรดชีต Excel ออกเป็นแผ่นงานภายในแอปพลิเคชันที่ใช้ Java" >}}
{{% blocks/products/pf/feature-page-summary %}}
 มีสถานการณ์ที่หลากหลาย เมื่อจำเป็นต้องแยกไฟล์ Excel เช่น สเปรดชีตที่มีข้อมูลนักเรียนพร้อมจัดสรรชีตเดียวสำหรับนักเรียนแต่ละคน และจำเป็นต้องแบ่งชีตนักเรียนแต่ละคนเป็นไฟล์แยกต่างหาก เพื่อทำให้เป็นอัตโนมัติ via Java แอปพลิเคชัน[Java เอ็กเซล API](/cells/th/java/) มีไว้เพื่อแยกเอกสาร Excel ตามแผ่น รูปแบบที่รองรับ ได้แก่ XLS, XLSX, XLSB, XLSM, ODS
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="แยกเอกสาร Excel ออกเป็นหลายไฟล์" %}}

 วิธีที่ง่ายที่สุดในการแยกไฟล์ Excel ออกเป็นชีตคือ เข้าถึงชีตทั้งหมด วนซ้ำแต่ละชีต และบันทึกทีละชีตในรูปแบบที่ต้องการ สำหรับโหลดใบงาน API จัดให้ครับ[สมุดงาน](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) ระดับ.[getWorksheets().getCount()](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#Count) วิธีรับจำนวนแผ่นงานทั้งหมด ทำซ้ำในแต่ละแผ่นและใช้[getWorksheets().get(sheetindex)](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#get)เพื่อเข้าใช้งานเฉพาะแผ่น ย้ายข้อมูลแผ่นงานที่เลือกไปยังวัตถุคลาสสมุดงานที่สร้างขึ้นใหม่โดยใช้[วิธีการคัดลอก](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#copy(com.aspose.cells.Workbook)). สุดท้ายให้บันทึกลงในรูปแบบที่ต้องการ

{{% blocks/products/pf/feature-page-code h3="Java รหัสแยกไฟล์ Excel" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-xls-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="แยกแผ่นงาน Excel ออกเป็นบานหน้าต่าง" %}}

API ยังมีฟังก์ชันการแยกแผ่นงาน Excel ออกเป็นบานหน้าต่างต่างๆ ขั้นตอนคือโหลดไฟล์โดยใช้คลาสสมุดงาน เลือกแผ่นงานแรกหรือแผ่นงานที่ต้องการโดยระบุดัชนี เรียก setActiveCell ที่มีดัชนีเซลล์ที่เกี่ยวข้องเป็นพารามิเตอร์ และในที่สุดก็แบ่งหน้าต่างแผ่นงานออกเป็นบานหน้าต่างต่างๆ โดยเรียกวิธีการ split()

{{% blocks/products/pf/feature-page-code h3="Java รหัสเพื่อแยกแผ่นงาน Excel ออกเป็นมุมมองบานหน้าต่าง" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-excel-spreadsheet-into-panes.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
