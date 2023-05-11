---
title: คำอธิบายประกอบไฟล์ Excel via Java
description: เพิ่มหรือลบคำอธิบายประกอบข้อมูลของสเปรดชีต Excel และ OpenOffice ด้วยไลบรารี Java
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="จัดการ Microsoft<sup>&reg;</sup> คำอธิบายประกอบไฟล์ Excel via Java" h2="แทรกบันทึกย่ออย่างง่ายสำหรับคำอธิบายประกอบหรือลบความคิดเห็นระดับเซลล์สเปรดชีต Excel ภายในแอปพลิเคชันที่ใช้ Java" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java เอ็กเซล API](/cells/th/java/) ให้การสนับสนุนในการจัดการคำอธิบายประกอบที่ระดับเซลล์โดยการเพิ่ม เข้าถึง และลบความคิดเห็น APIจัดให้[ความคิดเห็น](https://reference.aspose.com/cells/java/com.aspose.cells/Comment), [คอลเลกชันความคิดเห็น](https://reference.aspose.com/cells/java/com.aspose.cells/CommentCollection), [เธรดความคิดเห็น](https://reference.aspose.com/cells/java/com.aspose.cells/ThreadedComment) และ[ThreadedCommentCollection](https://reference.aspose.com/cells/java/com.aspose.cells/ThreadedCommentCollection) สำหรับการจัดการความคิดเห็นในทุกด้าน
รูปแบบไฟล์ที่รองรับ ได้แก่ ODS, XLS, XLSX, XLSB และ XLSM
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="คำอธิบายประกอบข้อมูลไฟล์ Excel" %}}
 การจัดการความคิดเห็นในแผ่นงาน - ไม่มีการจำกัดจำนวนความคิดเห็นในแผ่นงานใน MS Excel หนึ่งสามารถเพิ่มได้มากตามความต้องการของการสมัคร ขั้นตอนการเพิ่มความคิดเห็นคือสร้าง[สมุดงาน](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)วัตถุคลาสหรือโหลดไฟล์ที่มีอยู่โดยใช้คลาสสมุดงาน เข้าถึงความคิดเห็นทั้งหมดโดยใช้ getComments() รับดัชนีเซลล์และใช้[ตั้งหมายเหตุ](https://reference.aspose.com/cells/java/com.aspose.cells/comment#Note) สำหรับการแทรกความคิดเห็น นอกจากนี้ API สามารถลบความคิดเห็นทั้งหมดได้

{{% blocks/products/pf/feature-page-code h3="Java รหัสเพื่อเพิ่มความคิดเห็นภายในไฟล์ Excel" %}}

{{< gist "aspose-com-gists" "1b223bbd23b1c5b3fb5c96614e5584c6" "add-comments-excel-file.java" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Java รหัสเพื่อลบความคิดเห็นภายในไฟล์ Excel" %}}

{{< gist "aspose-com-gists" "1b223bbd23b1c5b3fb5c96614e5584c6" "remove-annotation-in-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}
