---
title: คำอธิบายประกอบไฟล์ Excel ผ่าน Java
url: /th/java/annotation/
description: เพิ่มหรือลบคำอธิบายประกอบข้อมูลของสเปรดชีต Excel และ OpenOffice ด้วยไลบรารี Java
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="จัดการ Microsoft<sup>&reg;</sup> Excel File Annotation ผ่าน Java" h2="แทรกบันทึกย่อสำหรับคำอธิบายประกอบหรือลบความคิดเห็นระดับเซลล์สเปรดชีต Excel ภายในแอปพลิเคชันที่ใช้ Java" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java เอ็กเซล API](/cells/java/) ให้การสนับสนุนในการจัดการคำอธิบายประกอบในระดับเซลล์โดยการเพิ่ม เข้าถึง และลบความคิดเห็น API ให้ [ความคิดเห็น](https://reference.aspose.com/cells/java/com.aspose.cells/Comment), [ความคิดเห็นคอลเลกชั่น](https://reference.aspose.com/cells/java/com.aspose.cells/CommentCollection), [ThreadedComment](https://reference.aspose.com/cells/java/com.aspose.cells/ThreadedComment) และ [ThreadedCommentCollection](https://reference.aspose.com/cells/java/com.aspose.cells/ThreadedCommentCollection) เพื่อจัดการกับความคิดเห็นในทุกด้าน
รูปแบบไฟล์ที่รองรับ ได้แก่ ODS, XLS, XLSX, XLSB และ XLSM
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="คำอธิบายประกอบข้อมูลไฟล์ Excel" %}}
การจัดการความคิดเห็นในเวิร์กชีต - ไม่มีการจำกัดจำนวนความคิดเห็นในแผ่นงานใน MS Excel สามารถเพิ่มได้มากเท่าที่ต้องการ ขั้นตอนการเพิ่มความคิดเห็นคือ create [สมุดงาน](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) class object หรือโหลดไฟล์ที่มีอยู่โดยใช้คลาส Workbook เข้าถึงความคิดเห็นทั้งหมดโดยใช้ getComments() รับดัชนีเซลล์และใช้ [setNote](https://reference.aspose.com/cells/java/com.aspose.cells/comment#Note) สำหรับการใส่ความคิดเห็น นอกจากนี้ API สามารถลบความคิดเห็นทั้งหมดได้ 

{{% blocks/products/pf/feature-page-code h3="Java รหัสสำหรับเพิ่มความคิดเห็นภายในไฟล์ Excel" %}}

{{< gist "aspose-com-gists" "1b223bbd23b1c5b3fb5c96614e5584c6" "add-comments-excel-file.java" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Java รหัสสำหรับลบความคิดเห็นภายในไฟล์ Excel" %}}

{{< gist "aspose-com-gists" "1b223bbd23b1c5b3fb5c96614e5584c6" "remove-annotation-in-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}