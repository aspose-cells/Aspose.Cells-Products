---
title: แยกสเปรดชีต Excel เป็นเวิร์กชีตใน Java
url: /th/java/splitter/
description: Java ซอร์สโค้ดที่อธิบายวิธีแยกไฟล์ Microsoft Excel เป็นหลายเอกสารโดยใช้ Java ไลบรารี Excel
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> การแยกไฟล์ Excel ผ่าน Java" h2="แยกสเปรดชีต Excel เป็นเวิร์กชีตภายใน Java แอปพลิเคชันที่อ้างอิงถึง" >}}
{{% blocks/products/pf/feature-page-summary %}}
มีหลายสถานการณ์ เมื่อจำเป็นต้องแยกไฟล์ Excel เช่น สเปรดชีตที่มีข้อมูลนักเรียนพร้อมการจัดสรรแผ่นงานเดียวสำหรับนักเรียนแต่ละคน และจำเป็นต้องแยกแผ่นงานของนักเรียนออกเป็นไฟล์แยกกัน ในการทำให้เป็นอัตโนมัติผ่านแอปพลิเคชัน Java [Java เอ็กเซล API](/cells/java/) มีการแยกเอกสาร Excel เป็นแผ่น รูปแบบที่รองรับ ได้แก่ XLS, XLSX, XLSB, XLSM, ODS 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="แยกเอกสาร Excel ออกเป็นหลายไฟล์" %}}

วิธีที่ง่ายที่สุดในการแบ่งไฟล์ Excel เป็นแผ่นงานคือ เข้าถึงแผ่นงานทั้งหมด วนซ้ำในแต่ละแผ่นงาน และบันทึกทีละแผ่นในรูปแบบที่ต้องการ สำหรับการโหลดเวิร์กชีต API ให้ [สมุดงาน](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) ระดับ. [getWorksheets().getCount()](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#Count) วิธีรับจำนวนแผ่นทั้งหมด ทำซ้ำผ่านแต่ละแผ่นและใช้ [getWorksheets().get(แผ่นงานดัชนี)](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#get) สำหรับการเข้าถึงแผ่นงานเฉพาะ ย้ายข้อมูลแผ่นงานที่เลือกไปยังวัตถุคลาสสมุดงานที่สร้างขึ้นใหม่โดยใช้ [วิธีการคัดลอก](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#copy(com.aspose.cells.Workbook)). สุดท้ายบันทึกลงในรูปแบบที่ต้องการ

{{% blocks/products/pf/feature-page-code h3="Java รหัสสำหรับแยกไฟล์ Excel" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-xls-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="แยกแผ่นงาน Excel ออกเป็นบานหน้าต่าง" %}}

API ยังมีฟังก์ชันของการแบ่งเวิร์กชีต Excel ออกเป็นบานหน้าต่างต่างๆ กระบวนการคือ โหลดไฟล์โดยใช้คลาสสมุดงาน เลือกแผ่นงานแรกหรือแผ่นงานที่จำเป็นโดยระบุดัชนี เรียก setActiveCell ที่มีดัชนีเซลล์ที่เกี่ยวข้องเป็นพารามิเตอร์ และสุดท้ายก็แบ่งหน้าต่างเวิร์กชีตออกเป็นบานหน้าต่างต่างๆ โดยเรียกเมธอด split()

{{% blocks/products/pf/feature-page-code h3="Java โค้ดสำหรับแยกแผ่นงาน Excel ออกเป็น Pane View" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-excel-spreadsheet-into-panes.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}