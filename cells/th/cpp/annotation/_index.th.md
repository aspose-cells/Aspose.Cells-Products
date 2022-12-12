---
title: คำอธิบายประกอบไฟล์ Excel ผ่าน C++

description: เพิ่มหรือลบความคิดเห็นเกี่ยวกับคำอธิบายประกอบข้อมูลของ Excel และสเปรดชีต OpenOffice ด้วยไลบรารี C++
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="จัดการ Microsoft<sup>&reg;</sup> Excel File Annotation ผ่าน C++" h2="เพิ่มหรือลบบันทึกย่อสำหรับคำอธิบายประกอบหรือความคิดเห็นภายในแอปพลิเคชันที่ใช้ C++" >}}
{{% blocks/products/pf/feature-page-summary %}}
[C++ เอ็กเซล API](/cells/cpp/) ให้การสนับสนุนในการจัดการคำอธิบายประกอบในระดับเซลล์โดยการเพิ่ม เข้าถึง และลบความคิดเห็น API ให้ [ไอความคิดเห็น](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment) และ [ICommentCollection](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection) เช่นกัน [GetIComments()](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ae7cce5f85b7b25a1e5c58df1b613ca5a) เพื่อจัดการกับความคิดเห็นในทุกด้าน รูปแบบ Excel ที่รองรับ ได้แก่ ODS, XLS, XLSX, XLSB และ XLSM
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="คำอธิบายประกอบข้อมูลไฟล์ Excel" %}}
การจัดการความคิดเห็นในเวิร์กชีต - ไม่จำกัดจำนวนความคิดเห็นในแผ่นงานใน MS Excel สามารถแทรกได้มากเท่าที่ต้องการของแอปพลิเคชัน ขั้นตอนการใส่ความคิดเห็นคือ create [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) class object เพื่อโหลดไฟล์ที่มีอยู่และเลือกเวิร์กชีตที่คุณต้องการเพิ่มความคิดเห็น รับความคิดเห็นทั้งหมดโดยใช้ getComments() เพิ่มความคิดเห็นโดยใช้ [เพิ่ม](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection#a3f014415e292fa15c6220e9727dad384)(ล่วงล้ำ_ptr < Aspose::Cells::Systems::String > cellName) วิธีการ รับดัชนีเซลล์และใช้ [setNote](https://reference.aspose.com/cells/cpp/com.aspose.cells/comment#Note) สำหรับการใส่ความคิดเห็น นอกจากนี้ API สามารถลบความคิดเห็นทั้งหมดได้ ไม่กี่วิธีคือ [เคลียร์คอมเมนต์()](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ad4e0ea291ae60fc1b5d815e520edc6c3) เพื่อล้างความคิดเห็นทั้งหมดในสเปรดชีตของนักออกแบบ นอกจากนี้, [RemoveAt](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet_collection#addabcc7d7d76874694018fb3ba37b72c)(ล่วงล้ำ_ptr< Aspose::Cells::Systems::String > ชื่อ) วิธีการลบองค์ประกอบที่ดัชนีที่ระบุหรือด้วยชื่อที่ระบุ

{{% blocks/products/pf/feature-page-code h3="C++ รหัสสำหรับเพิ่มความคิดเห็นภายในไฟล์ Excel" %}}

{{< gist "aspose-com-gists" "e144512d2c395c3336f12ce960424686" "add-comment-in-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}
