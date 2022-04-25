---
title: แยกแผ่นงาน Excel อย่างชาญฉลาดใน C#
url: /th/net/splitter/
description: C# ซอร์สโค้ดที่อธิบายวิธีแยกไฟล์ Microsoft Excel ออกเป็นหลายไฟล์ในแอปพลิเคชัน Visual C#.NET
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> การแยกไฟล์ Excel ผ่าน .NET" h2="แยกเอกสาร Excel เดียวออกเป็นไฟล์ต่างๆ โดยใช้รหัส C# ภายในแอปพลิเคชันที่ใช้ .NET" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET ไลบรารี Excel](/cells/net/) สามารถแบ่งเอกสาร Excel ออกเป็นหลายสเปรดชีตภายในแอปพลิเคชันที่ใช้ .NET รูปแบบไฟล์ที่รองรับ ได้แก่ XLS, XLSX, XLSB, XLSM, ODS
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="แยกเอกสาร Excel ออกเป็นหลายไฟล์" %}}
วิธีที่ง่ายที่สุดในการแยกไฟล์ Excel แผ่นงานอย่างชาญฉลาดคือ การเข้าถึงแผ่นงานทั้งหมดผ่าน [ใบงาน](https://apireference.aspose.com/cells/net/aspose.cells/workbook/properties/worksheets), วนซ้ำในแต่ละแผ่นและเรียก [สำเนา](https://apireference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy) กระบวนการ. ในที่สุดก็บันทึกลงในเส้นทางที่ระบุ 

+ โหลดไฟล์ Excel พร้อมพาธแบบเต็มโดยใช้ [คลาสเวิร์กบุค](https://apireference.aspose.com/cells/net/aspose.cells/workbook).
+ วนซ้ำในแต่ละแผ่น
+ สร้างวัตถุคลาสสมุดงานใหม่
+ คัดลอกแผ่นงานผ่าน [วิธีการคัดลอก](https://apireference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy)
+ เรียกเมธอด Save() และส่งชื่อไฟล์ (เส้นทางแบบเต็ม) ที่มี SaveFormat ที่เกี่ยวข้อง

{{% blocks/products/pf/feature-page-code h3="C# รหัสสำหรับแยกไฟล์ Excel" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="แยกแผ่นงาน Excel ออกเป็นบานหน้าต่าง" %}}

สำหรับการแบ่งหน้าต่างเวิร์กชีตเป็นบานหน้าต่าง APIให้ [วิธีแยก](https://apireference.aspose.com/cells/net/aspose.cells/worksheet/methods/split) ของคลาสเวิร์กชีต ที่ให้มุมมองแบบแยกของเวิร์กชีต ในการลบมุมมองที่แยกออก API จัดเตรียม [วิธีการ RemoveSplit](https://apireference.aspose.com/cells/net/aspose.cells/worksheet/methods/removesplit). สุดท้ายบันทึกลงในเส้นทางที่ระบุ 

{{% blocks/products/pf/feature-page-code h3="C# รหัสเพื่อแยกหน้าต่างแผ่นงาน Excel" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet-into-pane.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C# รหัสสำหรับลบ Pan View แบบแยกส่วน" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "remove-splitted-spreadsheet-pane-view.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
