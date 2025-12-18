---
title: จัดการเมตาเดต้าไฟล์ Excel ด้วย Go ผ่านหมายเลข C++
description: ดู เพิ่ม แก้ไข ลบ หรือดึงข้อมูลเมตาของไฟล์ Excel โดยใช้ภาษา Go ผ่านไลบรารีหมายเลข C++
keywords: [Go via C++ Aspose.Cells., Go via C++ view excel metadata., Go via C++ add excel metadata., Go via C++ insert excel metadata., Go via C++ edit excel metadata., Go via C++ remove excel metadata., Go via C++ extract excel metadata., Go via C++ modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="จัดการข้อมูลเมตาของเอกสาร Excel หมายเลข Microsoft ผ่าน Go โดยใช้หมายเลข C++" h2="ดู แทรก อัปเดต ลบ หรือดึงข้อมูลคุณสมบัติเอกสาร Excel แบบกำหนดเองและแบบสำเร็จรูปภายในแอปพลิเคชัน C++" >}}
{{% blocks/products/pf/feature-page-summary %}}
 ข้อมูลเมตาในไฟล์ Excel - วิธีดู แทรก และลบข้อมูลเมตาของไฟล์ Excel[ไปที่หมายเลข C++ ในไลบรารี Excel](/cells/th/go-cpp/)ระบบอำนวยความสะดวกนี้ทำได้ง่ายโดยการสนับสนุนคุณสมบัติในตัว/ที่กำหนดโดยระบบ เช่น ชื่อผู้เขียน ชื่อเรื่อง สถิติเอกสาร ฯลฯ ซึ่งบางครั้งจำเป็น เช่น เพื่อตรวจสอบว่าไฟล์ได้รับการแก้ไขหรือบันทึกครั้งล่าสุดเมื่อใด พร้อมด้วยคุณสมบัติที่กำหนดเอง/ที่ผู้ใช้กำหนดในรูปแบบคู่ชื่อ/ค่า เพื่อให้กระบวนการเป็นไปโดยอัตโนมัติ ไลบรารีนี้รองรับการสร้างและบำรุงรักษาไฟล์ Excel เมตาเดตาขนาดใหญ่[สมุดงาน](https://reference.aspose.com/cells/go-cpp/workbook/) คลาสนี้เปิดเวิร์กบุ๊กโดยใช้พาธ สตรีม และประเภทไฟล์พิเศษ ดังนั้นจึงโหลดไฟล์ด้วยวิธีการที่เหมาะสมสำหรับการประมวลผลต่อไป ตัวอย่างบางส่วนแสดงไว้ด้านล่าง และนักพัฒนาสามารถปรับปรุงโค้ดของตนเองได้อย่างง่ายดายตามความต้องการของแอปพลิเคชัน

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="อ่านและอัปเดตคุณสมบัติในตัว" %}}

 สำหรับการตั้งค่าคุณสมบัติในตัวโดยอัตโนมัติ รหัส API มีไว้สำหรับ...[GetBuiltInDocumentProperties()](https://reference.aspose.com/cells/go-cpp/workbook/getbuiltindocumentproperties/)เมธอดนี้จะส่งคืนคอลเลกชัน DocumentProperties ซึ่งแสดงถึงคุณสมบัติเอกสารในตัวทั้งหมดของสเปรดชีต หลังจากเข้าถึงคุณสมบัติในตัวทั้งหมดแล้ว ให้เข้าถึงคุณสมบัติที่เกี่ยวข้องโดยใช้เมธอดที่เกี่ยวข้อง เช่น GetTitle(), GetSubject() เป็นต้น สำหรับการอัปเดตคุณสมบัติ โค้ด API มีเมธอดต่างๆ เช่น SetTitle, SetSubject, SetAuthor, SetComments เป็นต้น ดูรายละเอียดเพิ่มเติมได้ที่นี่[การรวบรวมคุณสมบัติเอกสารในตัว](https://reference.aspose.com/cells/go-cpp/workbook/getbuiltindocumentproperties/) เพื่อการทำงานที่จำเป็น

{{% blocks/products/pf/feature-page-code h3="ไปที่รหัส C++ เพื่ออ่านคุณสมบัติที่กำหนดโดยระบบ" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "read-system-defined-properties.go" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="ไปที่รหัส C++ เพื่ออัปเดตคุณสมบัติในตัว" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "update-built-in-properties.go" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="ดูและเพิ่มคุณสมบัติที่กำหนดเอง" %}}

 สำหรับการจัดการคุณสมบัติที่กำหนดเอง รหัส API ให้บริการ[เวิร์กบุ๊ก::รับคุณสมบัติเอกสารแบบกำหนดเอง](https://reference.aspose.com/cells/go-cpp/workbook/getcustomdocumentproperties/)เมธอดนี้จะส่งคืนคอลเลกชันคุณสมบัติเอกสารแบบกำหนดเองทั้งหมดของสเปรดชีต โดยการเข้าถึงคุณสมบัติแบบกำหนดเองผ่านเมธอดนี้ นักพัฒนาสามารถใช้เมธอดที่เกี่ยวข้องเพื่อเพิ่มคุณสมบัติ เช่น AddIDocumentProperty, AddLinkToContentProperty และในทำนองเดียวกัน ใช้ UpdateLinkedPropertyValue, UpdateLinkedRange เพื่ออัปเดตค่าคุณสมบัติเอกสารแบบกำหนดเองที่เชื่อมโยงกับเนื้อหาและช่วงที่เชื่อมโยงตามลำดับ นักพัฒนาสามารถใช้เมธอดที่เกี่ยวข้องจาก[ชุดคุณสมบัติเอกสารที่กำหนดเอง](https://reference.aspose.com/cells/go-cpp/workbook/getcustomdocumentproperties/).

{{% blocks/products/pf/feature-page-code h3="เข้าไปดูรายละเอียดคุณสมบัติที่กำหนดเองได้โดยใช้รหัส C++" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "view-custom-properties.go" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="ใช้รหัส C++ เพื่อเพิ่มข้อมูลเมตาในไฟล์ Excel" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "add-custom-property.go" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< /blocks/products/pf/feature-page-wrap >}}