---
title: คำอธิบายประกอบไฟล์ Excel NET C#
description: เพิ่มหรือลบคำอธิบายประกอบข้อมูลของสเปรดชีต Excel และ OpenOffice ด้วยโค้ด C# เพียงไม่กี่บรรทัด
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="ลบ Microsoft<sup>&reg;</sup> คำอธิบายประกอบไฟล์ Excel via .NET" h2="เพิ่มหรือลบคำอธิบายประกอบไฟล์ Excel โดยใช้รหัส C# ภายในแอปพลิเคชันที่ใช้ .NET" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET คลังเอ็กเซล](/cells/th/net/) ให้การสนับสนุนในการจัดการคำอธิบายประกอบที่ระดับเซลล์โดยการเพิ่ม เข้าถึง และลบความคิดเห็น เมื่อใช้ความคิดเห็นที่ระดับเซลล์ ข้อมูลที่เกี่ยวข้องจะถูกเก็บไว้สำหรับผู้ใช้ปลายทาง รูปแบบไฟล์ที่รองรับ ได้แก่ ODS, XLS, XLSX, XLSB และ XLSM
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="คำอธิบายประกอบข้อมูลไฟล์ Excel" %}}
 การจัดการความคิดเห็นในแผ่นงาน - ไม่มีการจำกัดจำนวนความคิดเห็นในแผ่นงานใน MS Excel หนึ่งสามารถเพิ่มได้มากตามความต้องการของการสมัคร เราจะใช้[ชั้นแสดงความคิดเห็น](https://reference.aspose.com/cells/net/aspose.cells/comment)สำหรับฟังก์ชันทั้งหมดนี้

+ โหลดไฟล์ Excel โดยใช้วัตถุคลาสสมุดงาน
+ เข้าถึงแผ่นงานที่เกี่ยวข้องและดัชนี Cell ที่เกี่ยวข้อง
+ โทร RemoveAt ด้วยรหัส Cell เพื่อลบออก
 + ใช้[คุณสมบัติหมายเหตุ](https://reference.aspose.com/cells/net/aspose.cells/comment/properties/note) สำหรับการเพิ่มเนื้อหาความคิดเห็น
+ บันทึกสมุดงานก่อน & หลังเรียกวิธี RemoveAt เพื่อเปรียบเทียบ

{{% blocks/products/pf/feature-page-code h3="C# รหัสการเข้าถึง แทรก และลบไฟล์ Excel Cell ความคิดเห็น" %}}


{{< gist "aspose-com-gists" "e3dcb9c341b81d4db3a404ca7cd6e4cf" "access-insert-and-delete-excel-files-cell-comments.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}
