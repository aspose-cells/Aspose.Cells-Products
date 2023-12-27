---
title: แยกสเปรดชีต Excel ออกเป็นแผ่นงานใน Java
description: ซอร์สโค้ด Java ที่อธิบายวิธีแยกไฟล์ Excel Microsoft ออกเป็นหลายเอกสารโดยใช้ไลบรารี Excel Java
keywords: [Java Aspose.Cells., Java split excel files., Java how to split excel files into multiple files., Java excel splitter., Java split Cell., Cell splitter using Java]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> การแยกไฟล์ Excel via Java" h2="แยกสเปรดชีต Excel ออกเป็นแผ่นงานภายในแอปพลิเคชันที่ใช้ Java" >}}
{{% blocks/products/pf/feature-page-summary %}}
มีหลายสถานการณ์ เมื่อจำเป็นต้องแยกไฟล์ Excel เช่น สเปรดชีตที่มีข้อมูลนักเรียน โดยมีการจัดสรรชีตเดียวสำหรับนักเรียนแต่ละคน และจำเป็นต้องแยกนักเรียนแต่ละชีตออกเป็นไฟล์แยกกัน หากต้องการทำให้แอปพลิเคชัน via Java เป็นแบบอัตโนมัติ[Java เอกเซล API](/cells/th/java/) มีไว้เพื่อแยกเอกสาร Excel ตามแผ่นงาน รูปแบบที่รองรับ ได้แก่ XLS, XLSX, XLSB, XLSM, ODS
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="แยกเอกสาร Excel ออกเป็นหลายไฟล์" %}}

 วิธีที่ง่ายที่สุดในการแบ่งไฟล์ Excel ออกเป็นชีตคือ เข้าถึงชีตทั้งหมด วนซ้ำแต่ละชีต และบันทึกทีละชีตในรูปแบบที่ต้องการ หากต้องการโหลดใบงาน API จัดให้[สมุดงาน](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) ระดับ.[getWorksheets().getCount()](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#Count) วิธีรับจำนวนแผ่นงานทั้งหมด วนซ้ำแต่ละแผ่นและใช้งาน[getWorksheets().get(sheetindex)](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#get) สำหรับการเข้าถึงแผ่นงานเฉพาะ ย้ายข้อมูลแผ่นงานที่เลือกไปยังวัตถุคลาสสมุดงานที่สร้างขึ้นใหม่โดยใช้[วิธีการคัดลอก](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#copy(com.aspose.cells.Workbook)). ในที่สุดก็บันทึกเป็นรูปแบบที่ต้องการ

{{% blocks/products/pf/feature-page-code h3="Java โค้ดแยกไฟล์ Excel" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-xls-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="แยกแผ่นงาน Excel ออกเป็นบานหน้าต่าง" %}}

API ยังมีฟังก์ชันการแบ่งแผ่นงาน Excel ออกเป็นบานหน้าต่างต่างๆ กระบวนการคือโหลดไฟล์โดยใช้คลาสสมุดงาน เลือกแผ่นงานแรกหรือแผ่นงานที่จำเป็นโดยระบุดัชนี เรียก setActiveCell ที่มีดัชนีเซลล์ที่เกี่ยวข้องเป็นพารามิเตอร์ และสุดท้ายก็แบ่งหน้าต่างเวิร์กชีตออกเป็นบานหน้าต่างต่างๆ โดยเรียกเมธอด split()

{{% blocks/products/pf/feature-page-code h3="Java รหัสสำหรับแยกแผ่นงาน Excel ลงในมุมมองบานหน้าต่าง" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-excel-spreadsheet-into-panes.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
