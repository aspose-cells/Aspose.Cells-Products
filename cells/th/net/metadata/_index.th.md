---
title: จัดการข้อมูลเมตาของไฟล์ Excel ผ่าน .NET C#
url: /th/net/metadata/
description: ดู เพิ่ม แก้ไข ลบหรือแยกข้อมูลเมตาของไฟล์ Excel ด้วย C# code . เพียงไม่กี่บรรทัด
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="จัดการ Microsoft<sup>&reg;</sup> ข้อมูลเมตาของไฟล์ Excel ผ่าน .NET" h2="ดู เพิ่ม อัปเดต ลบหรือแยกคุณสมบัติไฟล์ Excel ที่มีอยู่แล้วภายในและกำหนดเองโดยใช้ .NET API ฝั่งเซิร์ฟเวอร์" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET เอ็กเซล API](/cells/net/) รองรับการจัดการคุณสมบัติที่กำหนดโดยระบบ (ในตัว) เช่น ชื่อเรื่อง ชื่อผู้เขียน สถิติเอกสาร ฯลฯ รวมถึงคุณสมบัติที่ผู้ใช้กำหนดเอง (กำหนดเอง) ในรูปแบบของคู่ชื่อ-ค่า มี [คลาสเวิร์กบุค](https://reference.aspose.com/cells/net/aspose.cells/workbook) เพื่อโหลดไฟล์และ [WorksheetCollection](https://reference.aspose.com/cells/net/aspose.cells/worksheetcollection) เกี่ยวกับคอลเลกชันของแผ่นงานเช่นเดียวกับ [ใบงาน](https://reference.aspose.com/cells/net/aspose.cells/worksheet) สำหรับเป็นตัวแทนของแผ่นงานเดียว พร้อมด้วยคลาสเหล่านี้ BuiltInDocumentProperties, CustomDocumentProperties ทำให้กระบวนการง่ายสำหรับการจัดการข้อมูลเมตา 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="การจัดการคุณสมบัติในตัว" %}}

สำหรับการจัดการคุณสมบัติที่กำหนดโดยระบบ API จัดเตรียม [BuiltInDocumentProperties](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/builtindocumentproperties)และโปรแกรมเมอร์สามารถเข้าถึงคุณสมบัติในตัวและอัปเดตค่าได้อย่างง่ายดาย ขึ้นอยู่กับข้อกำหนดของแอปพลิเคชัน นักพัฒนาสามารถใช้ดัชนีหรือชื่อคุณสมบัติจาก [DocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/documentpropertycollection). 

{{% blocks/products/pf/feature-page-code h3="C# รหัสสำหรับจัดการคุณสมบัติในตัว" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "manage-system-defined-excel-file-metadata.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="การจัดการคุณสมบัติที่กำหนดขึ้นเอง" %}}

สำหรับการจัดการคุณสมบัติที่ผู้ใช้กำหนด API จัดเตรียม [CustomDocumentProperties](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/customdocumentproperties)และนักพัฒนาสามารถเข้าถึงคุณสมบัติที่เพิ่มไว้แล้วและเพิ่มคุณสมบัติใหม่ได้อย่างง่ายดาย เพื่อเพิ่มคุณสมบัติที่กำหนดเอง [เพิ่มวิธีการ](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection/methods/add/index) ของ [CustomDocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection) class เพิ่มคุณสมบัติและส่งกลับการอ้างอิงสำหรับคุณสมบัติใหม่เป็น an [Properties.DocumentProperty](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty) วัตถุ. คลาส DocumentProperty ใช้เพื่อดึงชื่อ ค่า และประเภทของคุณสมบัติเอกสารเป็น [DocumentProperty.Name](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/name), [DocumentProperty.Value](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/value),  [DocumentProperty.Type](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/type) ที่ส่งคืนหนึ่งใน [ประเภทอสังหาริมทรัพย์](https://reference.aspose.com/cells/net/aspose.cells.properties/propertytype) ค่าการแจงนับ 
 
{{% blocks/products/pf/feature-page-code h3="C# รหัสสำหรับเพิ่มข้อมูลเมตาในไฟล์ Excel" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "add-metadata-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="C# รหัสสำหรับลบคุณสมบัติที่กำหนดเองในไฟล์ Excel" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "remove-custom-properties-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
