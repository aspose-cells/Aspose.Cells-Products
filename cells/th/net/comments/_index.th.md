---
title: แทรกความคิดเห็นใน Excel ผ่าน .NET

description: C# ซอร์สโค้ดที่จะแทรกความคิดเห็นลงในไฟล์ Microsoft Excel โดยใช้ .NET Library 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> การแทรกความคิดเห็นของ Excel ผ่าน .NET" h2="สร้างเอกสาร Excel และแทรกความคิดเห็นโดยใช้ API ฝั่งเซิร์ฟเวอร์ในแอปพลิเคชันที่ใช้ .NET" >}}
{{% blocks/products/pf/feature-page-summary %}}

คุณสามารถเพิ่มความคิดเห็นลงในเซลล์ได้ เมื่อเซลล์มีความคิดเห็น ตัวบ่งชี้จะปรากฏขึ้นที่มุมของเซลล์ ความคิดเห็นจะปรากฏขึ้นเมื่อคุณวางเคอร์เซอร์ไว้เหนือเซลล์ ความคิดเห็นเหล่านี้สามารถใช้สำหรับการอภิปราย คำแนะนำพิเศษ หรือมาร์กอัปเนื้อหาในเอกสาร [.NET ไลบรารี Excel](/cells/net/) รองรับการแทรกความคิดเห็นในไฟล์ Excel สำหรับสิ่งนี้ API ให้a [ความคิดเห็น](https://reference.aspose.com/cells/net/aspose.cells/comment) ชั้นเรียนสำหรับการสร้างความคิดเห็น

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="แทรกความคิดเห็นในไฟล์ Excel" %}}

การแทรกความคิดเห็นโดยใช้ Excel API เป็นเรื่องง่าย กระบวนการคือ สร้าง [คลาสเวิร์กบุค](https://reference.aspose.com/cells/net/aspose.cells/workbook) และเลือกแผ่นงานแรกหรือแผ่นงานที่เกี่ยวข้องโดยระบุดัชนี แทรกข้อมูลเซลล์ที่ต้องการโดยใช้ [วิธี PutValue](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index). เพิ่มความคิดเห็นในแผ่นงานโดยใช้ [ความคิดเห็นคอลเลกชั่น](https://reference.aspose.com/cells/net/aspose.cells/commentcollection)ของ [เพิ่มวิธีการ](https://reference.aspose.com/cells/net/aspose.cells.commentcollection/add/methods/1).

{{% blocks/products/pf/feature-page-code h3="C# รหัสสำหรับใส่ความคิดเห็นใน Excel" %}}

{{< gist "aspose-cells-gists" "88c9872508ec3150c552eb5155edf06e" "InsertCommentIntoWorksheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
