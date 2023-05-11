---
title: การสร้างแผนภูมิ Excel และการแปลงเป็นรูปภาพ via .NET
description:  ซอร์สโค้ด C# เพื่อวาดและแปลงแผนภูมิหรือไดอะแกรมใน Microsoft Excel โดยใช้ .NET Library
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> การสร้างแผนภูมิไฟล์ Excel และการแปลง via .NET" h2="สร้างแผนภูมิเอกสาร Excel และแปลงเป็นรูปภาพโดยใช้ API ฝั่งเซิร์ฟเวอร์ภายในแอปพลิเคชันที่ใช้ .NET" >}}
{{% blocks/products/pf/feature-page-summary %}}
 การวาดแผนภูมิเป็นศิลปะในการแสดงข้อมูลแบบกราฟิกเพื่อการวิเคราะห์ที่ง่ายดาย[.NET คลังเอ็กเซล](/cells/th/net/) รองรับการวาดแผนภูมิภายในไฟล์ Excel API รองรับการสร้างแผนภูมิต่างๆ ที่ระบุไว้ใน[การแจงนับประเภทแผนภูมิ](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype) รวมถึงแผนภูมิวงกลม พีระมิด เส้น และฟอง นอกจากนี้ยังแปลงแผนภูมิเป็นภาพ API ให้บริการ[คลาสแผนภูมิ](https://reference.aspose.com/cells/net/aspose.cells.charts) สำหรับบล็อกการสร้างแผนภูมิ

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="สร้างแผนภูมิภายในไฟล์ Excel" %}}

 การสร้างแผนภูมิโดยใช้ Excel API นั้นง่ายมาก กระบวนการคือสร้าง[คลาสสมุดงาน](https://reference.aspose.com/cells/net/aspose.cells/workbook) คัดค้านและเลือกแผ่นงานแรกหรือแผ่นงานที่เกี่ยวข้องโดยระบุดัชนี แทรกข้อมูลเซลล์ที่ต้องการโดยใช้[วิธี PutValue](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index) . เพิ่มแผนภูมิลงในเวิร์กชีตโดยใช้คอลเลกชันของแผนภูมิ[เพิ่มวิธีการ](https://reference.aspose.com/cells/net/aspose.cells.charts/chartcollection/methods/add) . ระบุ[ประเภทแผนภูมิ](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype)จากการแจงนับ ChartType
{{% blocks/products/pf/feature-page-code h3="C# รหัสเพื่อสร้างแผนภูมิ Excel" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "create-excel-chart.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section h2="แปลงแผนภูมิ Excel เป็นรูปภาพ" %}}

 ขั้นตอนการแปลงแผนภูมิเป็นรูปภาพ ใช้คลาสสมุดงานเพื่อโหลดไฟล์ Excel เลือกเวิร์กชีตที่เกี่ยวข้องที่มีแผนภูมิ และเรียกใช้[วิธี ToImage](https://reference.aspose.com/cells/net/aspose.cells.charts.chart/toimage/methods/7) สำหรับการแปลง

{{% blocks/products/pf/feature-page-code h3="C# รหัสสำหรับแปลงแผนภูมิ Excel เป็นรูปภาพ" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "convert-xlsx-file-chart-to-images.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}
