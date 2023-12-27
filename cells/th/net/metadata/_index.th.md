---
title: จัดการข้อมูลเมตาไฟล์ Excel via .NET C#
description: ดู เพิ่ม แก้ไข ลบ หรือแยกข้อมูลเมตาของไฟล์ Excel ด้วยโค้ด C# เพียงไม่กี่บรรทัด
keywords: [C# Aspose.Cells., c# view excel metadata., c# add excel metadata., c# insert excel metadata., c# edit excel metadata., c# remove excel metadata., c# extract excel metadata., c# modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="จัดการ Microsoft<sup>&reg;</sup> ข้อมูลเมตาของไฟล์ Excel via .NET" h2="ดู เพิ่ม อัปเดต ลบ หรือแยกคุณสมบัติไฟล์ Excel ในตัวและแบบกำหนดเองโดยใช้ API ฝั่งเซิร์ฟเวอร์ .NET" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET เอกเซล API](/cells/th/net/) รองรับการจัดการคุณสมบัติที่ระบบกำหนด (ในตัว) เช่น ชื่อเรื่อง ชื่อผู้แต่ง สถิติเอกสาร ฯลฯ รวมถึงคุณสมบัติที่ผู้ใช้กำหนด (กำหนดเอง) ในรูปแบบของคู่ชื่อ-ค่า มี[ชั้นเรียนสมุดงาน](https://reference.aspose.com/cells/net/aspose.cells/workbook) เพื่อโหลดไฟล์และ[แผ่นงานคอลเลกชัน](https://reference.aspose.com/cells/net/aspose.cells/worksheetcollection) เกี่ยวข้องกับการรวบรวมแผ่นงานเช่นกัน[ชั้นเรียนแผ่นงาน](https://reference.aspose.com/cells/net/aspose.cells/worksheet) สำหรับแสดงแผ่นงานเดี่ยว นอกจากคลาสเหล่านี้แล้ว BuiltInDocumentProperties แล้ว CustomDocumentProperties ยังทำให้กระบวนการสำหรับการจัดการข้อมูลเมตาเป็นเรื่องง่าย
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="การจัดการคุณสมบัติบิวท์อิน" %}}

 สำหรับการจัดการคุณสมบัติที่ระบบกำหนด API จัดให้[คุณสมบัติเอกสารในตัว](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/builtindocumentproperties)และโปรแกรมเมอร์สามารถเข้าถึงคุณสมบัติในตัวและอัปเดตค่าของมันได้อย่างง่ายดาย ขึ้นอยู่กับข้อกำหนดของแอปพลิเคชัน นักพัฒนาสามารถใช้ดัชนีหรือชื่อคุณสมบัติจาก[DocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/documentpropertycollection). 

{{% blocks/products/pf/feature-page-code h3="C# รหัสเพื่อจัดการคุณสมบัติบิวท์อิน" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "manage-system-defined-excel-file-metadata.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="การจัดการคุณสมบัติที่กำหนดแบบกำหนดเอง" %}}

 สำหรับการจัดการคุณสมบัติที่ผู้ใช้กำหนด API จัดให้[คุณสมบัติเอกสารแบบกำหนดเอง](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/customdocumentproperties) และนักพัฒนาสามารถเข้าถึงคุณสมบัติที่เพิ่มไว้แล้วรวมทั้งเพิ่มคุณสมบัติใหม่ได้อย่างง่ายดาย ในการเพิ่มคุณสมบัติที่กำหนดเอง[เพิ่มวิธีการ](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection/methods/add/index) ของ[CustomDocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection) คลาสเพิ่มคุณสมบัติและส่งกลับการอ้างอิงสำหรับคุณสมบัติใหม่เป็น[Properties.DocumentProperty](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty) วัตถุ. คลาส DocumentProperty ใช้เพื่อดึงชื่อ ค่า และประเภทของคุณสมบัติเอกสารเป็น[DocumentProperty.ชื่อ](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/name), [DocumentProperty.Value](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/value),  [DocumentProperty.Type](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/type) ที่ส่งกลับค่าใดค่าหนึ่ง[ประเภทอสังหาริมทรัพย์](https://reference.aspose.com/cells/net/aspose.cells.properties/propertytype) ค่าแจงนับ
 
{{% blocks/products/pf/feature-page-code h3="C# โค้ดสำหรับเพิ่ม Metadata ในไฟล์ Excel" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "add-metadata-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="C# รหัสเพื่อลบคุณสมบัติที่กำหนดเองในไฟล์ Excel" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "remove-custom-properties-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
