---
title: แยกแผ่นงาน Excel อย่างชาญฉลาดใน C#
description: ซอร์สโค้ด C# ที่อธิบายวิธีการแยกไฟล์ Excel Microsoft ออกเป็นหลายไฟล์ในแอปพลิเคชัน Visual C#.NET
keywords: [C# Aspose.Cells., C# split excel files., C# how to split excel files into multiple files., C# excel splitter., C# split Cell., Cell splitter using C#]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> การแยกไฟล์ Excel via .NET" h2="แยกเอกสาร Excel เดี่ยวออกเป็นไฟล์ต่างๆ โดยใช้รหัส C# ภายในแอปพลิเคชันที่ใช้ .NET" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET เอ็กเซล ไลบรารี่](/cells/th/net/) สามารถแยกเอกสาร Excel ออกเป็นหลายสเปรดชีตภายในแอปพลิเคชันที่ใช้ .NET รูปแบบไฟล์ที่รองรับได้แก่ XLS, XLSX, XLSB, XLSM, ODS
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="แยกเอกสาร Excel ออกเป็นหลายไฟล์" %}}
วิธีที่ง่ายที่สุดในการแบ่งแผ่นงานไฟล์ Excel อย่างชาญฉลาดคือการเข้าถึงแผ่นงานทั้งหมดผ่านทาง[ใบงาน](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/worksheets) , วนซ้ำแต่ละชีตแล้วเรียก[สำเนา](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy) วิธี. ในที่สุดก็บันทึกลงในเส้นทางที่ระบุ

 + โหลดไฟล์ Excel ด้วยเส้นทางแบบเต็มโดยใช้[ชั้นเรียนสมุดงาน](https://reference.aspose.com/cells/net/aspose.cells/workbook).
+ วนซ้ำแต่ละแผ่น
+ สร้างวัตถุคลาสสมุดงานใหม่
 + คัดลอกแผ่นงานผ่าน[วิธีการคัดลอก](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy)
+ เรียกใช้เมธอด Save() และส่งชื่อไฟล์ (เส้นทางแบบเต็ม) ที่มี SaveFormat ที่เกี่ยวข้อง

{{% blocks/products/pf/feature-page-code h3="C# โค้ดแยกไฟล์ Excel" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="แยกแผ่นงาน Excel ออกเป็นบานหน้าต่าง" %}}

 หากต้องการแยกหน้าต่างเวิร์กชีตออกเป็นบานหน้าต่าง API จัดให้[วิธีการแยก](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/split) ของคลาสเวิร์กชีตที่ให้มุมมองแบบแยกของเวิร์กชีต หากต้องการลบแยกมุมมอง API จัดให้[วิธีการ RemoveSplit](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/removesplit) . ในที่สุดก็บันทึกลงในเส้นทางที่ระบุ

{{% blocks/products/pf/feature-page-code h3="C# รหัสสำหรับแยกหน้าต่างแผ่นงาน Excel" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet-into-pane.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C# โค้ดลบมุมมอง Pan แบบแยกส่วน" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "remove-splitted-spreadsheet-pane-view.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
