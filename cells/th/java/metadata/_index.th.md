---
title: จัดการข้อมูลเมตาของไฟล์ Excel via Java
description: ดู เพิ่ม แก้ไข ลบ หรือแยกข้อมูลเมตาของไฟล์ Excel ด้วยโค้ด Java เพียงไม่กี่บรรทัด
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="จัดการ Microsoft<sup>&reg;</sup> ข้อมูลเมตาของไฟล์ Excel via Java" h2="ดู เพิ่ม อัปเดต ลบ หรือแยกคุณสมบัติไฟล์ Excel แบบกำหนดเองและในตัวโดยใช้ API ฝั่งเซิร์ฟเวอร์ Java" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java เอ็กเซล API](/cells/th/java/) รองรับการจัดการคุณสมบัติในตัว (กำหนดโดยระบบ) เช่น ชื่อเรื่อง ชื่อผู้เขียน สถิติเอกสาร ฯลฯ เช่นเดียวกับคุณสมบัติกำหนดเอง (ผู้ใช้กำหนด) ในรูปแบบของคู่ชื่อ/ค่า มี[คลาสสมุดงาน](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) เพื่อโหลดไฟล์และ[คอลเลกชันแผ่นงาน](https://reference.aspose.com/cells/java/com.aspose.cells/WorksheetCollection)เกี่ยวข้องกับการรวบรวมแผ่นงานเช่นเดียวกับ[คลาสใบงาน](https://reference.aspose.com/cells/java/com.aspose.cells/Worksheet) สำหรับแสดงแผ่นงานเดียว สำหรับการเข้าถึงในตัวและคุณสมบัติที่กำหนดเอง BuiltInDocumentProperties, CustomDocumentProperties ทำให้กระบวนการง่ายสำหรับการจัดการข้อมูลเมตา
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="การจัดการคุณสมบัติที่กำหนดโดยระบบ" %}}

 สำหรับการจัดการคุณสมบัติในตัว API จัดให้[BuiltInDocumentProperties](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#BuiltInDocumentProperties) และโปรแกรมเมอร์สามารถเข้าถึงคุณสมบัติในตัวและอัปเดตค่าของมันได้อย่างง่ายดาย นักพัฒนาสามารถใช้ดัชนีหรือชื่อคุณสมบัติจาก[DocumentPropertyCollection](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentPropertyCollection). 

{{% blocks/products/pf/feature-page-code h3="รหัส Java เพื่อจัดการคุณสมบัติที่กำหนดโดยระบบ" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "update-system-defined-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="เพิ่มและลบข้อมูลเมตาที่กำหนดขึ้นเอง" %}}

สำหรับการจัดการคุณสมบัติที่กำหนดเอง API ให้[CustomDocumentProperties](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#CustomDocumentProperties) และนักพัฒนาสามารถเข้าถึงพร็อพเพอร์ตี้ที่มีอยู่ได้อย่างง่ายดาย รวมทั้งเพิ่มพร็อพเพอร์ตี้ใหม่โดยใช้[เพิ่มวิธีการ](https://reference.aspose.com/cells/java/com.aspose.cells/customdocumentpropertycollection#add(java.lang.String,%20boolean) ) ของ[CustomDocumentPropertyCollection](https://reference.aspose.com/cells/java/com.aspose.cells/CustomDocumentPropertyCollection) class เพิ่มคุณสมบัติและส่งกลับการอ้างอิงสำหรับคุณสมบัติใหม่เป็น an[Properties.DocumentProperty](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentProperty)วัตถุ. คลาส DocumentProperty ใช้เพื่อดึงชื่อ ค่า และประเภทของคุณสมบัติเอกสารเป็น[DocumentProperty.Name](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Name), [DocumentProperty.Value](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Value),  [DocumentProperty.Type](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Type) ที่คืนค่าหนึ่งใน[ประเภทอสังหาริมทรัพย์](https://reference.aspose.com/cells/java/com.aspose.cells/PropertyType) ค่าการแจงนับ
 
{{% blocks/products/pf/feature-page-code h3="Java รหัสเพื่อเพิ่มข้อมูลเมตาในไฟล์ Excel" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "add-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="รหัส Java เพื่อลบคุณสมบัติที่กำหนดเองในไฟล์ Excel" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "remove-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
