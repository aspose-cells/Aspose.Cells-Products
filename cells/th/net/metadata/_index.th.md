---
title: จัดการข้อมูลเมตาของไฟล์ Excel via .NET C#
description: ดู เพิ่ม แก้ไข ลบ หรือแยกข้อมูลเมตาของไฟล์ Excel ด้วยโค้ด C# เพียงไม่กี่บรรทัด
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="จัดการ Microsoft<sup>&reg;</sup> ข้อมูลเมตาของไฟล์ Excel via .NET" h2="ดู เพิ่ม อัปเดต ลบ หรือแยกคุณสมบัติไฟล์ Excel ในตัวและแบบกำหนดเองโดยใช้ API ฝั่งเซิร์ฟเวอร์ .NET" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET เอ็กเซล API](/cells/th/net/) รองรับการจัดการคุณสมบัติที่ระบบกำหนด (ในตัว) เช่น ชื่อเรื่อง ชื่อผู้เขียน สถิติเอกสาร ฯลฯ เช่นเดียวกับคุณสมบัติที่ผู้ใช้กำหนด (กำหนดเอง) ในรูปแบบของคู่ชื่อ-ค่า มี[คลาสสมุดงาน](https://reference.aspose.com/cells/net/aspose.cells/workbook) เพื่อโหลดไฟล์และ[คอลเลกชันแผ่นงาน](https://reference.aspose.com/cells/net/aspose.cells/worksheetcollection) เกี่ยวข้องกับการรวบรวมแผ่นงานเช่นเดียวกับ[คลาสใบงาน](https://reference.aspose.com/cells/net/aspose.cells/worksheet) สำหรับแสดงแผ่นงานเดียว ร่วมกับคลาสเหล่านี้ BuiltInDocumentProperties, CustomDocumentProperties ทำให้กระบวนการง่ายสำหรับการจัดการข้อมูลเมตา
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="การจัดการคุณสมบัติในตัว" %}}

 สำหรับการจัดการคุณสมบัติที่ระบบกำหนด API ให้[BuiltInDocumentProperties](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/builtindocumentproperties) และโปรแกรมเมอร์สามารถเข้าถึงคุณสมบัติในตัวและอัปเดตค่าของมันได้อย่างง่ายดาย นักพัฒนาสามารถใช้ดัชนีหรือชื่อคุณสมบัติจาก[DocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/documentpropertycollection). 

{{% blocks/products/pf/feature-page-code h3="รหัส C# เพื่อจัดการคุณสมบัติในตัว" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "manage-system-defined-excel-file-metadata.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="การจัดการคุณสมบัติที่กำหนดขึ้นเอง" %}}

 สำหรับการจัดการคุณสมบัติที่ผู้ใช้กำหนด API ให้[CustomDocumentProperties](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/customdocumentproperties) และนักพัฒนาสามารถเข้าถึงพร็อพเพอร์ตี้ที่เพิ่มไว้แล้ว รวมทั้งเพิ่มพร็อพเพอร์ตี้ใหม่ได้อย่างง่ายดาย ในการเพิ่มคุณสมบัติที่กำหนดเอง[เพิ่มวิธีการ](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection/methods/add/index) ของ[CustomDocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection) class เพิ่มคุณสมบัติและส่งกลับการอ้างอิงสำหรับคุณสมบัติใหม่เป็น an[Properties.DocumentProperty](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty) วัตถุ. คลาส DocumentProperty ใช้เพื่อดึงชื่อ ค่า และประเภทของคุณสมบัติเอกสารเป็น[DocumentProperty.Name](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/name), [DocumentProperty.Value](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/value),  [DocumentProperty.Type](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/type) ที่คืนค่าหนึ่งใน[ประเภทอสังหาริมทรัพย์](https://reference.aspose.com/cells/net/aspose.cells.properties/propertytype) ค่าการแจงนับ
 
{{% blocks/products/pf/feature-page-code h3="C# รหัสเพื่อเพิ่มข้อมูลเมตาในไฟล์ Excel" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "add-metadata-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="รหัส C# เพื่อลบคุณสมบัติที่กำหนดเองในไฟล์ Excel" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "remove-custom-properties-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
