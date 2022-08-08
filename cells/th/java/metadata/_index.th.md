---
title: จัดการข้อมูลเมตาของไฟล์ Excel ผ่าน Java
url: /th/java/metadata/
description: ดู เพิ่ม แก้ไข ลบหรือแยกข้อมูลเมตาของไฟล์ Excel ด้วย Java code . เพียงไม่กี่บรรทัด
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="จัดการ Microsoft<sup>&reg;</sup> ข้อมูลเมตาของไฟล์ Excel ผ่าน Java" h2="ดู เพิ่ม อัปเดต ลบ หรือแยกคุณสมบัติไฟล์ Excel แบบกำหนดเองและในตัวโดยใช้ Java API ฝั่งเซิร์ฟเวอร์" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java เอ็กเซล API](/cells/java/) รองรับการจัดการคุณสมบัติในตัว (กำหนดโดยระบบ) เช่น ชื่อเรื่อง ชื่อผู้เขียน สถิติเอกสาร ฯลฯ รวมถึงคุณสมบัติที่กำหนดเอง (กำหนดโดยผู้ใช้) ในรูปแบบของคู่ชื่อ/ค่า มี [คลาสเวิร์กบุค](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) เพื่อโหลดไฟล์และ [WorksheetCollection](https://reference.aspose.com/cells/java/com.aspose.cells/WorksheetCollection) เกี่ยวกับคอลเลกชันของแผ่นงานเช่นเดียวกับ [ใบงาน](https://reference.aspose.com/cells/java/com.aspose.cells/Worksheet) สำหรับเป็นตัวแทนของแผ่นงานเดียว สำหรับการเข้าถึงคุณสมบัติในตัวและแบบกำหนดเอง BuiltInDocumentProperties, CustomDocumentProperties ทำให้กระบวนการนี้ง่ายขึ้นสำหรับการจัดการข้อมูลเมตา 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="การจัดการคุณสมบัติที่กำหนดโดยระบบ" %}}

สำหรับการจัดการคุณสมบัติในตัว API จัดเตรียม [BuiltInDocumentProperties](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#BuiltInDocumentProperties)และโปรแกรมเมอร์สามารถเข้าถึงคุณสมบัติในตัวและอัปเดตค่าได้อย่างง่ายดาย ขึ้นอยู่กับข้อกำหนดของแอปพลิเคชัน นักพัฒนาสามารถใช้ดัชนีหรือชื่อคุณสมบัติจาก [DocumentPropertyCollection](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentPropertyCollection). 

{{% blocks/products/pf/feature-page-code h3="Java รหัสสำหรับจัดการคุณสมบัติที่กำหนดโดยระบบ" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "update-system-defined-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="เพิ่มและลบข้อมูลเมตาที่กำหนดแบบกำหนดเอง" %}}

สำหรับการจัดการคุณสมบัติที่กำหนดเอง APIให้ [CustomDocumentProperties](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#CustomDocumentProperties)และนักพัฒนาสามารถเข้าถึงคุณสมบัติที่มีอยู่ได้อย่างง่ายดายรวมถึงเพิ่มคุณสมบัติใหม่โดยใช้ [เพิ่มวิธีการ](https://reference.aspose.com/cells/java/com.aspose.cells/customdocumentpropertycollection#add(java.lang.String,%20boolean)) ของ [CustomDocumentPropertyCollection](https://reference.aspose.com/cells/java/com.aspose.cells/CustomDocumentPropertyCollection) class เพิ่มคุณสมบัติและส่งกลับการอ้างอิงสำหรับคุณสมบัติใหม่เป็น an [Properties.DocumentProperty](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentProperty) วัตถุ. คลาส DocumentProperty ใช้เพื่อดึงชื่อ ค่า และประเภทของคุณสมบัติเอกสารเป็น [DocumentProperty.Name](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Name), [DocumentProperty.Value](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Value),  [DocumentProperty.Type](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Type) ที่ส่งคืนหนึ่งใน [ประเภทอสังหาริมทรัพย์](https://reference.aspose.com/cells/java/com.aspose.cells/PropertyType) ค่าการแจงนับ 
 
{{% blocks/products/pf/feature-page-code h3="Java รหัสสำหรับเพิ่มข้อมูลเมตาในไฟล์ Excel" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "add-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="Java รหัสสำหรับลบคุณสมบัติที่กำหนดเองในไฟล์ Excel" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "remove-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
