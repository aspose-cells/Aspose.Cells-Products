---
title: จัดการข้อมูลเมตาของไฟล์ Excel ผ่าน C++
url: /th/cpp/metadata/
description: ดู เพิ่ม แก้ไข ลบ หรือแยกข้อมูลเมตาของไฟล์ Excel โดยใช้ C++ library
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="จัดการข้อมูลเมตาของเอกสาร Microsoft<sup>&reg;</sup> ผ่าน C++" h2="ดู แทรก อัปเดต ลบหรือแยกคุณสมบัติเอกสาร Excel แบบกำหนดเองและในตัวภายใน C++ แอปพลิเคชัน" >}}
{{% blocks/products/pf/feature-page-summary %}}
ข้อมูลเมตาใน Excel - วิธีดู แทรก และลบข้อมูลเมตาของไฟล์ excel [C++ ไลบรารี Excel](/cells/cpp/) อำนวยความสะดวกเป็นเรื่องง่ายโดยรองรับคุณสมบัติในตัว / ที่กำหนดโดยระบบเช่นชื่อผู้แต่ง, ชื่อเรื่อง, สถิติเอกสาร ฯลฯ ที่จำเป็นในบางครั้งเช่นการตรวจสอบเมื่อไฟล์สุดท้ายถูกแก้ไขหรือบันทึกพร้อมกับคุณสมบัติกำหนดเอง / ที่ผู้ใช้กำหนดในรูปแบบของ คู่ชื่อ/ค่า เพื่อให้กระบวนการเป็นไปโดยอัตโนมัติ ไลบรารีสนับสนุนการสร้างและดูแลไฟล์ Excel ข้อมูลเมตาขนาดใหญ่ [วิธีการ CreateIWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8) ของ [ชั้นโรงงาน](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory) เปิดสมุดงานตามเส้นทาง โดยสตรีม และโดย FileFormatType พิเศษ ดังนั้นให้โหลดไฟล์ด้วยวิธีที่เหมาะสมสำหรับการประมวลผลต่อไป มีความเป็นไปได้สองสามอย่างตามรายการด้านล่าง และนักพัฒนาสามารถปรับปรุงโค้ดได้อย่างง่ายดายตามข้อกำหนดของแอปพลิเคชัน 
 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="อ่านและอัปเดตคุณสมบัติในตัว" %}}

สำหรับการทำให้คุณสมบัติในตัวเป็นอัตโนมัติ API จัดเตรียม [GetIBuiltInDocumentProperties()](https://reference.aspose.com/cells/cpp/class/aspose.cells.metadata.i_workbook_metadata) เมธอดที่ส่งคืนคอลเล็กชัน DocumentProperties ที่แสดงคุณสมบัติเอกสารในตัวทั้งหมดของสเปรดชีต หลังจากเข้าถึงคุณสมบัติในตัวทั้งหมดแล้ว ให้เข้าถึงคุณสมบัติที่เกี่ยวข้องโดยใช้วิธีการที่เกี่ยวข้อง เช่น GetTitle(), GetSubject() เป็นต้น ในการอัปเดตคุณสมบัติ API จะจัดเตรียมวิธีการ เช่น SetTitle, SetSubject, SetAuthor, SetComments เป็นต้น ดู [การรวบรวมคุณสมบัติเอกสารในตัว](https://reference.aspose.com/cells/cpp/class/aspose.cells.properties.i_built_in_document_property_collection) สำหรับฟังก์ชั่นที่จำเป็น

{{% blocks/products/pf/feature-page-code h3="C++ รหัสสำหรับอ่านคุณสมบัติที่กำหนดโดยระบบ" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "read-system-defined-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C++ รหัสสำหรับอัปเดตคุณสมบัติในตัว" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "update-built-in-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="ดูและเพิ่มคุณสมบัติที่กำหนดขึ้นเอง" %}}

สำหรับการจัดการคุณสมบัติที่กำหนดเอง APIให้ [IWorkbookMetadata::GetICustomDocumentProperties](https://reference.aspose.com/cells/cpp/class/aspose.cells.metadata.i_workbook_metadata#a69f0226813ce18c03ebc13b8ca691e79) ที่ส่งคืนคอลเลกชันคุณสมบัติเอกสารที่กำหนดเองทั้งหมดของสเปรดชีต ประการแรก การเข้าถึงคุณสมบัติที่กำหนดเองผ่านวิธีนี้ นักพัฒนาสามารถใช้วิธีการที่เกี่ยวข้องเพื่อเพิ่มคุณสมบัติเช่น AddIDocumentProperty, AddLinkToContentProperty และใช้ UpdateLinkedPropertyValue, UpdateLinkedRange ในทำนองเดียวกันเพื่ออัปเดตค่าคุณสมบัติเอกสารที่กำหนดเองซึ่งเชื่อมโยงไปยังเนื้อหาและช่วงที่เชื่อมโยงตามลำดับ นักพัฒนาสามารถใช้วิธีการที่เกี่ยวข้องจาก [คอลเลกชันของคุณสมบัติเอกสารที่กำหนดเอง](https://reference.aspose.com/cells/cpp/class/aspose.cells.properties.i_custom_document_property_collection).

{{% blocks/products/pf/feature-page-code h3="C++ รหัสเพื่อดูคุณสมบัติที่กำหนดเอง" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "view-custom-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C++ รหัสสำหรับเพิ่มข้อมูลเมตาในไฟล์ Excel" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "add-custom-property.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}