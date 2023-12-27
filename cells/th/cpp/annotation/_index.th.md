---
title: เพิ่มหรือลบคำอธิบายประกอบไฟล์ Excel ผ่านทาง C++
description: เพิ่มหรือลบความคิดเห็นคำอธิบายประกอบข้อมูลของสเปรดชีต Excel และ OpenOffice ด้วยไลบรารี C++
keywords: [C++ Aspose.Cells., add excel annotation., insert excel annotation., access excel annotation., remove excel annotation., delete excel annotation., add annotation in excel., insert annotation in excel., access annotation in excel., remove annotation in excel., delete annotation in excel]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="จัดการ Microsoft<sup>&reg;</sup> คำอธิบายประกอบไฟล์ Excel ผ่านทาง C++" h2="เพิ่มหรือลบบันทึกย่อแบบง่ายสำหรับคำอธิบายประกอบหรือความคิดเห็นภายในแอปพลิเคชันที่ใช้ C++" >}}
{{% blocks/products/pf/feature-page-summary %}}
[C++ เอกเซล API](/cells/th/cpp/) ให้การสนับสนุนในการจัดการคำอธิบายประกอบในระดับเซลล์โดยการเพิ่ม การเข้าถึง และการลบความคิดเห็น APIจัดให้[ความคิดเห็น](https://reference.aspose.com/cells/cpp/aspose.cells/comment/) และ[ความคิดเห็นคอลเลกชัน](https://reference.aspose.com/cells/cpp/aspose.cells/commentcollection/) เช่นเดียวกับ[GetComments()](https://reference.aspose.com/cells/cpp/aspose.cells/worksheet/getcomments/)เพื่อรับฟังความคิดเห็นในทุกด้าน รูปแบบ Excel ที่รองรับ ได้แก่ ODS, XLS, XLSX, XLSB และ XLSM
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="คำอธิบายประกอบข้อมูลไฟล์ Excel" %}}
 การจัดการความคิดเห็นในแผ่นงาน - ไม่จำกัดจำนวนความคิดเห็นในแผ่นงานใน MS Excel สามารถแทรกได้มากเท่าที่ต้องการ ขั้นตอนการใส่ความคิดเห็นคือการสร้าง[สมุดงาน](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) วัตถุคลาสเพื่อโหลดไฟล์ที่มีอยู่และเลือกแผ่นงานที่คุณต้องการเพิ่มความคิดเห็น รับความคิดเห็นทั้งหมดโดยใช้ getComments() เพิ่มความคิดเห็นโดยใช้[เพิ่ม(const char16_t* ชื่อเซลล์)](https://reference.aspose.com/cells/cpp/aspose.cells/commentcollection/add/) วิธี. รับดัชนีเซลล์และใช้งาน[เซ็ตโน้ต](https://reference.aspose.com/cells/cpp/aspose.cells/comment/setnote/) สำหรับการใส่ความคิดเห็น นอกจากนี้ API ยังสามารถลบความคิดเห็นทั้งหมดได้ มีวิธีการไม่กี่วิธี[ClearComments()](https://reference.aspose.com/cells/cpp/aspose.cells/worksheet/clearcomments/) เพื่อล้างความคิดเห็นทั้งหมดในสเปรดชีตของนักออกแบบ นอกจากนี้,***ลบที่*** วิธีการลบองค์ประกอบที่ดัชนีที่ระบุหรือด้วยชื่อที่ระบุ

{{% blocks/products/pf/feature-page-code h3="C++ โค้ดสำหรับเพิ่มความคิดเห็นภายในไฟล์ Excel" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "add-comment-in-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}
