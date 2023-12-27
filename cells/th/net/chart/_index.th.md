---
title: การสร้างแผนภูมิ Excel และการแปลงเป็นรูปภาพ via .NET
description:  C# ซอร์สโค้ดสำหรับวาดและแปลงแผนภูมิหรือไดอะแกรมใน Microsoft Excel โดยใช้ .NET Library
keywords: [C# Aspose.Cells., c# Convert chart to image., c# Save chart to image., c# chart to image., create charts in c#., insert charts in c#., manage charts in c#]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> การสร้างแผนภูมิไฟล์ Excel และการแปลง via .NET" h2="สร้างแผนภูมิเอกสาร Excel และแปลงเป็นรูปภาพโดยใช้ API ฝั่งเซิร์ฟเวอร์ภายในแอปพลิเคชันที่ใช้ .NET" >}}
{{% blocks/products/pf/feature-page-summary %}}
 การวาดแผนภูมิเป็นศิลปะในการแสดงข้อมูลแบบกราฟิกเพื่อการวิเคราะห์ที่ง่ายดาย[.NET เอ็กเซล ไลบรารี่](/cells/th/net/) รองรับแผนภูมิการวาดภายในไฟล์ Excel API รองรับการสร้างแผนภูมิต่างๆ ที่แสดงอยู่ในรายการ[การแจงนับประเภทแผนภูมิ](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype) รวมถึงแผนภูมิวงกลม พีระมิด เส้น และฟองสบู่ นอกจากนี้ยังแปลงแผนภูมิเป็นรูปภาพอีกด้วย APIจัดให้[ชั้นเรียนแผนภูมิ](https://reference.aspose.com/cells/net/aspose.cells.charts) สำหรับบล็อคการสร้างแผนภูมิ

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="สร้างแผนภูมิภายในไฟล์ Excel" %}}

 การสร้างแผนภูมิโดยใช้ Excel API เป็นเรื่องง่าย กระบวนการคือ สร้าง[ชั้นเรียนสมุดงาน](https://reference.aspose.com/cells/net/aspose.cells/workbook)object และเลือกแผ่นงานแรกหรือแผ่นงานที่เกี่ยวข้องโดยจัดทำดัชนี แทรกข้อมูลเซลล์ที่ต้องการโดยใช้[วิธีการใส่ค่า](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index) . เพิ่มแผนภูมิลงในแผ่นงานโดยใช้คอลเลกชันแผนภูมิ[เพิ่มวิธีการ](https://reference.aspose.com/cells/net/aspose.cells.charts/chartcollection/methods/add) . ระบุ[ChartType](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype) จากการแจงนับ ChartType
{{% blocks/products/pf/feature-page-code h3="C# โค้ดสร้างแผนภูมิ Excel" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "create-excel-chart.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section h2="แปลงแผนภูมิ Excel เป็นรูปภาพ" %}}

 กระบวนการแปลงแผนภูมิเป็นรูปภาพคือ ใช้คลาสสมุดงานเพื่อโหลดไฟล์ Excel เลือกชุดงานที่เกี่ยวข้องซึ่งมีแผนภูมิแล้วเรียก[วิธี ToImage](https://reference.aspose.com/cells/net/aspose.cells.charts.chart/toimage/methods/7) สำหรับการแปลง

{{% blocks/products/pf/feature-page-code h3="C# รหัสแปลงแผนภูมิ Excel เป็นรูปภาพ" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "convert-xlsx-file-chart-to-images.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}
