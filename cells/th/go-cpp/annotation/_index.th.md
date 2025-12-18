---
title: เพิ่มหรือลบคำอธิบายประกอบไฟล์ Excel ด้วย Go ผ่านหมายเลข C++
description: เพิ่มหรือลบคำอธิบายประกอบข้อมูลในสเปรดชีต Excel และ OpenOffice ด้วยภาษา Go ผ่านไลบรารีหมายเลข C++
keywords: [Go via C++ Aspose.Cells., add excel annotation., insert excel annotation., access excel annotation., remove excel annotation., delete excel annotation., add annotation in excel., insert annotation in excel., access annotation in excel., remove annotation in excel., delete annotation in excel]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=" จัดการคำอธิบายประกอบไฟล์ Excel หมายเลข Microsoft<sup>&reg;</sup> ด้วย Go ผ่าน C++" h2="เพิ่มหรือลบโน้ตง่ายๆ สำหรับคำอธิบายประกอบหรือความคิดเห็นภายใน Go ผ่านแอปพลิเคชันที่ใช้หมายเลข C++" >}}
{{% blocks/products/pf/feature-page-summary %}}
[ติดต่อผ่านหมายเลข C++ หรือ Excel API](/cells/th/go-cpp/) ให้การสนับสนุนในการจัดการคำอธิบายประกอบในระดับเซลล์โดยการเพิ่ม เข้าถึง และลบความคิดเห็น รหัส API ให้การสนับสนุน[ความคิดเห็น](https://reference.aspose.com/cells/go-cpp/aspose.cells/comment/) และ[คอลเลกชันความคิดเห็น](https://reference.aspose.com/cells/go-cpp/aspose.cells/commentcollection/)รวมถึง[GetComments()](https://reference.aspose.com/cells/go-cpp/aspose.cells/worksheet/getcomments/) สำหรับการจัดการความคิดเห็นในทุกด้าน รูปแบบไฟล์ Excel ที่รองรับ ได้แก่ ODS, XLS, XLSX, XLSB และ XLSM
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="คำอธิบายประกอบข้อมูลในไฟล์ Excel" %}}
 การจัดการความคิดเห็นในเวิร์กชีต - ไม่มีข้อจำกัดว่าเวิร์กชีตใน MS Excel จะมีความคิดเห็นได้กี่รายการ สามารถใส่ความคิดเห็นได้มากเท่าที่แอปพลิเคชันต้องการ ขั้นตอนการใส่ความคิดเห็นคือ การสร้างความคิดเห็น[สมุดงาน](https://reference.aspose.com/cells/go-cpp/aspose.cells/workbook/) สร้างอ็อบเจ็กต์คลาสเพื่อโหลดไฟล์ที่มีอยู่แล้วและเลือกเวิร์กชีตที่คุณต้องการเพิ่มความคิดเห็น ดึงความคิดเห็นทั้งหมดโดยใช้ getComments() เพิ่มความคิดเห็นโดยใช้[Add(const char16_t* cellName)](https://reference.aspose.com/cells/go-cpp/aspose.cells/commentcollection/add/) วิธีการ รับดัชนีเซลล์และนำไปใช้[ตั้งค่าหมายเหตุ](https://reference.aspose.com/cells/go-cpp/aspose.cells/comment/setnote/) สำหรับการแทรกความคิดเห็น นอกจากนี้ รหัส API ยังสามารถลบความคิดเห็นทั้งหมดได้อีกด้วย วิธีการบางส่วนมีดังนี้[ClearComments()](https://reference.aspose.com/cells/go-cpp/aspose.cells/worksheet/clearcomments/) เพื่อล้างความคิดเห็นทั้งหมดในสเปรดชีตของนักออกแบบ นอกจากนี้***ลบออกที่*** วิธีการลบองค์ประกอบที่ดัชนีที่ระบุหรือที่มีชื่อที่ระบุ

{{% blocks/products/pf/feature-page-code h3="ใช้รหัส C++ เพื่อเพิ่มความคิดเห็นภายในไฟล์ Excel" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "add-comment-in-excel.go" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}

{{< /blocks/products/pf/feature-page-wrap >}}
