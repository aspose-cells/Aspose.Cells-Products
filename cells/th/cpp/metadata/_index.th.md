---
title: จัดการ Metadata ไฟล์ Excel ผ่านทาง C++
description: ดู เพิ่ม แก้ไข ลบ หรือแยกข้อมูลเมตาของไฟล์ Excel โดยใช้ไลบรารี C++
keywords: [C++ Aspose.Cells., C++ view excel metadata., C++ add excel metadata., C++ insert excel metadata., C++ edit excel metadata., C++ remove excel metadata., C++ extract excel metadata., C++ modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="จัดการ Microsoft<sup>&reg;</sup> ข้อมูลเมตาเอกสาร Excel ผ่าน C++" h2="ดู แทรก อัปเดต ลบ หรือแยกคุณสมบัติเอกสาร Excel แบบกำหนดเองและในตัวภายในแอปพลิเคชัน C++" >}}
{{% blocks/products/pf/feature-page-summary %}}
 ข้อมูลเมตาใน Excel - วิธีดู แทรก และลบข้อมูลเมตาของไฟล์ Excel[C++ เอ็กเซล ไลบรารี่](/cells/th/cpp/) อำนวยความสะดวกด้วยวิธีง่ายๆ โดยรองรับคุณสมบัติในตัว / ที่ระบบกำหนด เช่น ชื่อผู้แต่ง ชื่อเรื่อง สถิติเอกสาร ฯลฯ ที่จำเป็นบางครั้ง เช่น ตรวจสอบว่าไฟล์สุดท้ายถูกแก้ไขหรือบันทึกเมื่อใด พร้อมด้วยคุณสมบัติแบบกำหนดเอง / ที่ผู้ใช้กำหนดในรูปแบบของ คู่ชื่อ/ค่า เพื่อให้กระบวนการเป็นอัตโนมัติ ไลบรารีรองรับการสร้างและดูแลรักษาไฟล์ Excel เมตาดาต้าขนาดใหญ่[สมุดงาน](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/)คลาสเปิดสมุดงานตามเส้นทางตามกระแสและตาม FileFormatType พิเศษ ดังนั้นให้โหลดไฟล์ด้วยวิธีที่เหมาะสมเพื่อการประมวลผลต่อไป ความเป็นไปได้บางประการตามรายการด้านล่าง และนักพัฒนาสามารถปรับปรุงโค้ดของตนได้อย่างง่ายดายตามความต้องการของแอปพลิเคชัน
 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="อ่านและอัปเดตคุณสมบัติบิวท์อิน" %}}

 สำหรับคุณสมบัติในตัวอัตโนมัติ API จัดให้[GetBuiltInDocumentProperties()](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/getbuiltindocumentproperties/) วิธีการส่งคืนคอลเลกชัน DocumentProperties ที่แสดงคุณสมบัติเอกสารในตัวทั้งหมดของสเปรดชีต หลังจากเข้าถึงคุณสมบัติบิวท์อินทั้งหมดแล้ว ให้เข้าถึงคุณสมบัติที่เกี่ยวข้องโดยใช้วิธีการที่เกี่ยวข้อง เช่น GetTitle(), GetSubject() ฯลฯ หากต้องการอัปเดตคุณสมบัติ API จัดเตรียมวิธีการ เช่น SetTitle, SetSubject, SetAuthor, SetComments เป็นต้น ดู[การรวบรวมคุณสมบัติเอกสารในตัว](https://reference.aspose.com/cells/cpp/aspose.cells.properties/builtindocumentpropertycollection/) สำหรับฟังก์ชันที่ต้องการ

{{% blocks/products/pf/feature-page-code h3="C++ รหัสเพื่ออ่านคุณสมบัติที่กำหนดโดยระบบ" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "read-system-defined-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C++ รหัสเพื่ออัพเดตคุณสมบัติบิวท์อิน" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "update-built-in-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="ดูและเพิ่มคุณสมบัติที่กำหนดแบบกำหนดเอง" %}}

สำหรับการจัดการคุณสมบัติที่กำหนดเอง API จัดให้[สมุดงาน::GetCustomDocumentProperties](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/getcustomdocumentproperties/) ที่ส่งคืนคอลเลกชันคุณสมบัติเอกสารแบบกำหนดเองทั้งหมดของสเปรดชีต ประการแรก การเข้าถึงคุณสมบัติแบบกำหนดเองด้วยวิธีนี้ นักพัฒนาสามารถใช้วิธีการที่เกี่ยวข้องในการเพิ่มคุณสมบัติ เช่น AddIDocumentProperty, AddLinkToContentProperty และใช้ UpdateLinkedPropertyValue, UpdateLinkedRange ในทำนองเดียวกัน เพื่ออัปเดตค่าคุณสมบัติเอกสารแบบกำหนดเองซึ่งลิงก์ไปยังเนื้อหาและไปยังช่วงที่ลิงก์ตามลำดับ นักพัฒนาสามารถใช้วิธีการที่เกี่ยวข้องได้จาก[การรวบรวมคุณสมบัติเอกสารที่กำหนดเอง](https://reference.aspose.com/cells/cpp/aspose.cells.properties/customdocumentpropertycollection/).

{{% blocks/products/pf/feature-page-code h3="C++ รหัสเพื่อดูคุณสมบัติที่กำหนดเอง" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "view-custom-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C++ โค้ดสำหรับเพิ่ม Metadata ในไฟล์ Excel" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "add-custom-property.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
