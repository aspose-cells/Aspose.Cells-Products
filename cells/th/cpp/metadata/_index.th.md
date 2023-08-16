---
title: จัดการข้อมูลเมตาของไฟล์ Excel ผ่าน C++
description: ดู เพิ่ม แก้ไข ลบ หรือแยกข้อมูลเมตาของไฟล์ Excel โดยใช้ไลบรารี C++
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="จัดการ Microsoft<sup>&reg;</sup> ข้อมูลเมตาของเอกสาร Excel ผ่าน C++" h2="ดู แทรก อัปเดต ลบ หรือแยกคุณสมบัติเอกสาร Excel แบบกำหนดเองและในตัวภายในแอปพลิเคชัน C++" >}}
{{% blocks/products/pf/feature-page-summary %}}
 ข้อมูลเมตาใน Excel - วิธีดู แทรก และลบข้อมูลเมตาของไฟล์ excel[C++ คลังเอ็กเซล](/cells/th/cpp/) อำนวยความสะดวกด้วยวิธีง่าย ๆ โดยรองรับคุณสมบัติในตัว / ที่ระบบกำหนด เช่น ชื่อผู้เขียน ชื่อเรื่อง สถิติเอกสาร ฯลฯ ที่จำเป็น เช่น การตรวจสอบเมื่อไฟล์สุดท้ายถูกแก้ไขหรือบันทึกพร้อมกับคุณสมบัติที่กำหนดเอง / ที่ผู้ใช้กำหนดในรูปแบบของ คู่ชื่อ/ค่า เพื่อให้กระบวนการเป็นไปโดยอัตโนมัติ ไลบรารีรองรับการสร้างและดูแลไฟล์ Excel ข้อมูลเมตาขนาดใหญ่[เมธอด CreateIWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8) ของ[ชั้นโรงงาน](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory)เปิดสมุดงานตามเส้นทาง ตามสตรีม และตาม FileFormatType พิเศษ ดังนั้นโหลดไฟล์ด้วยวิธีที่เหมาะสมเพื่อดำเนินการต่อไป ความเป็นไปได้ไม่กี่รายการด้านล่างและนักพัฒนาซอฟต์แวร์สามารถปรับปรุงโค้ดได้อย่างง่ายดายตามความต้องการของแอปพลิเคชัน
 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="อ่านและอัปเดตคุณสมบัติในตัว" %}}

 สำหรับการทำให้คุณสมบัติในตัวเป็นไปโดยอัตโนมัติ API มีให้[GetIBuiltInDocumentProperties()](https://reference.aspose.com/cells/cpp/class/aspose.cells.metadata.i_workbook_metadata) เมธอดที่ส่งคืนคอลเล็กชัน DocumentProperties ที่แสดงคุณสมบัติเอกสารในตัวทั้งหมดของสเปรดชีต หลังจากเข้าถึงคุณสมบัติในตัวทั้งหมดแล้ว ให้เข้าถึงคุณสมบัติที่เกี่ยวข้องโดยใช้วิธีการที่เกี่ยวข้อง เช่น GetTitle(), GetSubject() เป็นต้น หากต้องการอัปเดตคุณสมบัติ API จัดเตรียมวิธีการ เช่น SetTitle, SetSubject, SetAuthor, SetComments เป็นต้น ดู[การรวบรวมคุณสมบัติเอกสารในตัว](https://reference.aspose.com/cells/cpp/class/aspose.cells.properties.i_built_in_document_property_collection) สำหรับฟังก์ชั่นที่ต้องการ

{{% blocks/products/pf/feature-page-code h3="รหัส C++ เพื่ออ่านคุณสมบัติที่กำหนดโดยระบบ" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "read-system-defined-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="รหัส C++ เพื่ออัพเดตคุณสมบัติในตัว" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "update-built-in-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="ดูและเพิ่มคุณสมบัติที่กำหนดขึ้นเอง" %}}

สำหรับการจัดการคุณสมบัติที่กำหนดเอง API ให้[IWorkbookMetadata::GetICustomDocumentProperties](https://reference.aspose.com/cells/cpp/class/aspose.cells.metadata.i_workbook_metadata#a69f0226813ce18c03ebc13b8ca691e79) ที่ส่งคืนคอลเลกชันคุณสมบัติเอกสารที่กำหนดเองทั้งหมดของสเปรดชีต ขั้นแรก การเข้าถึงคุณสมบัติแบบกำหนดเองด้วยวิธีนี้ นักพัฒนาสามารถใช้วิธีการที่เกี่ยวข้องเพื่อเพิ่มคุณสมบัติ เช่น AddIDocumentProperty, AddLinkToContentProperty และใช้ UpdateLinkedPropertyValue, UpdateLinkedRange ในทำนองเดียวกันเพื่ออัปเดตค่าคุณสมบัติเอกสารที่กำหนดเองซึ่งลิงก์ไปยังเนื้อหาและไปยังช่วงที่เชื่อมโยงตามลำดับ นักพัฒนาสามารถใช้วิธีการที่เกี่ยวข้องจาก[การรวบรวมคุณสมบัติของเอกสารแบบกำหนดเอง](https://reference.aspose.com/cells/cpp/class/aspose.cells.properties.i_custom_document_property_collection).

{{% blocks/products/pf/feature-page-code h3="รหัส C++ เพื่อดูคุณสมบัติแบบกำหนดเอง" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "view-custom-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C++ รหัสเพื่อเพิ่มข้อมูลเมตาในไฟล์ Excel" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "add-custom-property.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
