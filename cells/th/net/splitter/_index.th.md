---
title: แยกแผ่นงาน Excel อย่างชาญฉลาดใน C#
description: ซอร์สโค้ด C# ที่อธิบายวิธีแยกไฟล์ Excel Microsoft ออกเป็นหลายไฟล์ในแอปพลิเคชัน Visual C#.NET
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> การแยกไฟล์ Excel via .NET" h2="แยกเอกสาร Excel เดี่ยวออกเป็นไฟล์ต่างๆ โดยใช้รหัส C# ภายในแอปพลิเคชันที่ใช้ .NET" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET คลังเอ็กเซล](/cells/th/net/) สามารถแยกเอกสาร Excel ออกเป็นหลายสเปรดชีตภายในแอปพลิเคชันที่ใช้ .NET รูปแบบไฟล์ที่รองรับ ได้แก่ XLS, XLSX, XLSB, XLSM, ODS
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="แยกเอกสาร Excel ออกเป็นหลายไฟล์" %}}
 วิธีที่ง่ายที่สุดในการแยกแผ่นงานไฟล์ Excel คือการเข้าถึงแผ่นงานทั้งหมดผ่าน[แผ่นงาน](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/worksheets) ,วนซ้ำไปทีละแผ่นและเรียก[สำเนา](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy) วิธี. ในที่สุดก็บันทึกลงในเส้นทางที่กำหนด

 + โหลดไฟล์ Excel ด้วยเส้นทางแบบเต็มโดยใช้[คลาสสมุดงาน](https://reference.aspose.com/cells/net/aspose.cells/workbook).
+ วนซ้ำแต่ละแผ่น
+ สร้างวัตถุคลาสสมุดงานใหม่
 + คัดลอกชีทผ่าน[วิธีการคัดลอก](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy)
+ เรียกใช้เมธอด Save() และส่งชื่อไฟล์ (พาธเต็ม) ที่มี SaveFormat ที่เกี่ยวข้อง

{{% blocks/products/pf/feature-page-code h3="C# รหัสแยกไฟล์ Excel" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="แยกแผ่นงาน Excel ออกเป็นบานหน้าต่าง" %}}

 สำหรับการแบ่งหน้าต่างแผ่นงานออกเป็นบานหน้าต่าง API จัดเตรียมไว้ให้[วิธีการแยก](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/split)ของคลาสแผ่นงาน ที่ให้มุมมองแยกของแผ่นงาน หากต้องการลบมุมมองแยก API จัดให้[วิธี RemoveSplit](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/removesplit) . สุดท้ายบันทึกลงในเส้นทางที่ระบุ

{{% blocks/products/pf/feature-page-code h3="C# รหัสเพื่อแยกหน้าต่างแผ่นงาน Excel" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet-into-pane.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C# รหัสเพื่อลบมุมมองแพนแยก" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "remove-splitted-spreadsheet-pane-view.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
