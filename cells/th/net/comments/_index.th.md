---
title: แทรกความคิดเห็นใน Excel via .NET
description:  ซอร์สโค้ด C# ที่จะใส่ความคิดเห็นลงในไฟล์ Excel Microsoft โดยใช้ .NET Library
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> การแทรกความคิดเห็นของ Excel via .NET" h2="สร้างเอกสาร Excel และแทรกความคิดเห็นโดยใช้ API ฝั่งเซิร์ฟเวอร์ในแอปพลิเคชันที่ใช้ .NET" >}}
{{% blocks/products/pf/feature-page-summary %}}

 คุณสามารถเพิ่มความคิดเห็นลงในเซลล์ได้ เมื่อเซลล์มีความคิดเห็น ตัวบ่งชี้จะปรากฏที่มุมของเซลล์ ความคิดเห็นจะปรากฏขึ้นเมื่อคุณวางเคอร์เซอร์ไว้เหนือเซลล์ ความคิดเห็นเหล่านี้สามารถใช้สำหรับการสนทนา คำแนะนำพิเศษ หรือมาร์กอัปของเนื้อหาเอกสาร[.NET คลังเอ็กเซล](/cells/th/net/)รองรับการแทรกความคิดเห็นในไฟล์ Excel สำหรับสิ่งนี้ API มี[ความคิดเห็น](https://reference.aspose.com/cells/net/aspose.cells/comment) คลาสสำหรับกลุ่มการสร้างความคิดเห็น

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="แทรกความคิดเห็นในไฟล์ Excel" %}}

 การแทรกความคิดเห็นโดยใช้ Excel API ทำได้ง่าย กระบวนการคือสร้าง[คลาสสมุดงาน](https://reference.aspose.com/cells/net/aspose.cells/workbook) คัดค้านและเลือกแผ่นงานแรกหรือแผ่นงานที่เกี่ยวข้องโดยระบุดัชนี แทรกข้อมูลเซลล์ที่ต้องการโดยใช้[วิธี PutValue](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index) . เพิ่มความคิดเห็นลงในแผ่นงานโดยใช้[คอลเลกชันความคิดเห็น](https://reference.aspose.com/cells/net/aspose.cells/commentcollection) 's[เพิ่มวิธีการ](https://reference.aspose.com/cells/net/aspose.cells.commentcollection/add/methods/1).

{{% blocks/products/pf/feature-page-code h3="C# รหัสเพื่อแทรกความคิดเห็นใน Excel" %}}

{{< gist "aspose-cells-gists" "59a1901d62ea9ceb08456a818431a898" "InsertCommentIntoWorksheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
