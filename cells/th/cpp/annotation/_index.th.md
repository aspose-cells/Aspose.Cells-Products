---
title: คำอธิบายประกอบไฟล์ Excel ผ่าน C++
description: เพิ่มหรือลบความคิดเห็นคำอธิบายประกอบข้อมูลของสเปรดชีต Excel และ OpenOffice ด้วยไลบรารี C++
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="จัดการ Microsoft<sup>&reg;</sup> คำอธิบายประกอบไฟล์ Excel ผ่าน C++" h2="เพิ่มหรือลบบันทึกง่ายๆ สำหรับคำอธิบายประกอบหรือความคิดเห็นภายในแอปพลิเคชันที่ใช้ C++" >}}
{{% blocks/products/pf/feature-page-summary %}}
[C++ เอ็กเซล API](/cells/th/cpp/) ให้การสนับสนุนในการจัดการคำอธิบายประกอบที่ระดับเซลล์โดยการเพิ่ม เข้าถึง และลบความคิดเห็น APIจัดให้[ไอคอมเมนท์](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment) และ[ICommentCollection](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection) เช่นเดียวกับ[GetIComments()](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ae7cce5f85b7b25a1e5c58df1b613ca5a)สำหรับการจัดการความคิดเห็นในทุกด้าน รูปแบบ Excel ที่รองรับ ได้แก่ ODS, XLS, XLSX, XLSB และ XLSM
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="คำอธิบายประกอบข้อมูลไฟล์ Excel" %}}
 การจัดการความคิดเห็นในแผ่นงาน - ไม่จำกัดจำนวนความคิดเห็นในแผ่นงานใน MS Excel ใส่ได้มากเท่าที่ต้องการ ขั้นตอนการแทรกความคิดเห็นคือสร้าง[ไอเวิร์กบุ๊ก](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) วัตถุคลาสเพื่อโหลดไฟล์ที่มีอยู่และเลือกแผ่นงานที่คุณต้องการเพิ่มความคิดเห็น รับความคิดเห็นทั้งหมดโดยใช้ getComments() เพิ่มความคิดเห็นโดยใช้[เพิ่ม](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection#a3f014415e292fa15c6220e9727dad384) (intrusive_ptr< Aspose::Cells::Systems::String > ชื่อเซลล์) เมธอด รับดัชนีเซลล์และใช้[ตั้งหมายเหตุ](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment#a791b9d4e9bf3975709a7f93b5db09580) สำหรับการแทรกความคิดเห็น นอกจากนี้ API สามารถลบความคิดเห็นทั้งหมดได้ มีไม่กี่วิธี[ClearComments()](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ad4e0ea291ae60fc1b5d815e520edc6c3) เพื่อล้างความคิดเห็นทั้งหมดในสเปรดชีตของนักออกแบบ นอกจากนี้,[ลบที่](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet_collection#addabcc7d7d76874694018fb3ba37b72c)(intrusive_ptr< Aspose::Cells::Systems::String > ชื่อ) วิธีลบองค์ประกอบที่ดัชนีที่ระบุหรือด้วยชื่อที่ระบุ

{{% blocks/products/pf/feature-page-code h3="C++ รหัสเพื่อเพิ่มความคิดเห็นภายในไฟล์ Excel" %}}

{{< gist "aspose-com-gists" "e144512d2c395c3336f12ce960424686" "add-comment-in-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}
