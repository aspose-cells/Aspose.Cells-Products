---
title: จัดการข้อมูลเมตาไฟล์ Excel via Java
description: ดู เพิ่ม แก้ไข ลบ หรือแยกข้อมูลเมตาของไฟล์ Excel ด้วยโค้ด Java เพียงไม่กี่บรรทัด
keywords: [Java Aspose.Cells., Java view excel metadata., Java add excel metadata., Java insert excel metadata., Java edit excel metadata., Java remove excel metadata., Java extract excel metadata., Java modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="จัดการ Microsoft<sup>&reg;</sup> ข้อมูลเมตาของไฟล์ Excel via Java" h2="ดู เพิ่ม อัปเดต ลบ หรือแยกคุณสมบัติไฟล์ Excel แบบกำหนดเองและในตัวโดยใช้ API ฝั่งเซิร์ฟเวอร์ Java" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java เอกเซล API](/cells/th/java/) รองรับการจัดการคุณสมบัติในตัว (กำหนดโดยระบบ) เช่น ชื่อเรื่อง ชื่อผู้แต่ง สถิติเอกสาร ฯลฯ รวมถึงคุณสมบัติที่กำหนดเอง (กำหนดโดยผู้ใช้) ในรูปแบบของคู่ชื่อ/ค่า มี[ชั้นเรียนสมุดงาน](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) เพื่อโหลดไฟล์และ[แผ่นงานคอลเลกชัน](https://reference.aspose.com/cells/java/com.aspose.cells/WorksheetCollection) เกี่ยวข้องกับการรวบรวมแผ่นงานเช่นกัน[ชั้นเรียนแผ่นงาน](https://reference.aspose.com/cells/java/com.aspose.cells/Worksheet) สำหรับแสดงแผ่นงานเดี่ยว สำหรับการเข้าถึงคุณสมบัติบิวด์อินและคุณสมบัติแบบกำหนดเอง BuiltInDocumentProperties, CustomDocumentProperties ทำให้กระบวนการสำหรับการจัดการเมตาดาต้าเป็นเรื่องง่าย
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="การจัดการคุณสมบัติที่กำหนดโดยระบบ" %}}

 รับจัดการทรัพย์สินบิวท์อิน APIจัดให้[คุณสมบัติเอกสารในตัว](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#BuiltInDocumentProperties)และโปรแกรมเมอร์สามารถเข้าถึงคุณสมบัติในตัวและอัปเดตค่าของมันได้อย่างง่ายดาย ขึ้นอยู่กับข้อกำหนดของแอปพลิเคชัน นักพัฒนาสามารถใช้ดัชนีหรือชื่อคุณสมบัติจาก[DocumentPropertyCollection](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentPropertyCollection). 

{{% blocks/products/pf/feature-page-code h3="รหัส Java เพื่อจัดการคุณสมบัติที่กำหนดโดยระบบ" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "update-system-defined-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="เพิ่มและลบข้อมูลเมตาที่กำหนดแบบกำหนดเอง" %}}

สำหรับการจัดการคุณสมบัติที่กำหนดเอง API จัดให้[คุณสมบัติเอกสารแบบกำหนดเอง](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#CustomDocumentProperties) และนักพัฒนาสามารถเข้าถึงคุณสมบัติที่มีอยู่ได้อย่างง่ายดายรวมถึงเพิ่มคุณสมบัติใหม่โดยใช้[เพิ่มวิธีการ](https://reference.aspose.com/cells/java/com.aspose.cells/customdocumentpropertycollection#add(java.lang.String,%20boolean) ) ของ[CustomDocumentPropertyCollection](https://reference.aspose.com/cells/java/com.aspose.cells/CustomDocumentPropertyCollection) คลาสเพิ่มคุณสมบัติและส่งกลับการอ้างอิงสำหรับคุณสมบัติใหม่เป็น[Properties.DocumentProperty](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentProperty) วัตถุ. คลาส DocumentProperty ใช้เพื่อดึงชื่อ ค่า และประเภทของคุณสมบัติเอกสารเป็น[DocumentProperty.ชื่อ](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Name), [DocumentProperty.Value](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Value),  [DocumentProperty.Type](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Type) ที่ส่งกลับค่าใดค่าหนึ่ง[ประเภทอสังหาริมทรัพย์](https://reference.aspose.com/cells/java/com.aspose.cells/PropertyType) ค่าแจงนับ
 
{{% blocks/products/pf/feature-page-code h3="Java โค้ดสำหรับเพิ่ม Metadata ในไฟล์ Excel" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "add-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="Java รหัสเพื่อลบคุณสมบัติแบบกำหนดเองในไฟล์ Excel" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "remove-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
