---
title: การสร้างแผนภูมิ Excel และการแปลงเป็นรูปภาพผ่าน .NET

description: C# ซอร์สโค้ดสำหรับวาดและแปลงแผนภูมิหรือไดอะแกรมใน Microsoft Excel โดยใช้ .NET Library 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> การสร้างและการแปลงไฟล์ Excel ผ่าน .NET" h2="สร้างแผนภูมิเอกสาร Excel และแปลงเป็นรูปภาพโดยใช้ API ฝั่งเซิร์ฟเวอร์ภายในแอปพลิเคชันที่ใช้ .NET" >}}
{{% blocks/products/pf/feature-page-summary %}}
การวาดแผนภูมิเป็นศิลปะในการแสดงข้อมูลแบบกราฟิกเพื่อการวิเคราะห์ที่ง่ายดาย [.NET ไลบรารี Excel](/cells/net/) รองรับการวาดแผนภูมิภายในไฟล์ Excel API รองรับการสร้างแผนภูมิที่แตกต่างกันใน [ChartType การแจงนับ](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype) รวมถึงแผนภูมิวงกลม พีระมิด เส้น และฟองสบู่ นอกจากนี้ยังแปลงแผนภูมิเป็นรูปภาพ API ให้ a [คลาสชาร์ต](https://reference.aspose.com/cells/net/aspose.cells.charts) สำหรับหน่วยการสร้างแผนภูมิ

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="สร้างแผนภูมิภายในไฟล์ Excel" %}}

การสร้างแผนภูมิโดยใช้ Excel API เป็นเรื่องง่าย กระบวนการคือ สร้าง [คลาสเวิร์กบุค](https://reference.aspose.com/cells/net/aspose.cells/workbook) และเลือกแผ่นงานแรกหรือแผ่นงานที่เกี่ยวข้องโดยระบุดัชนี แทรกข้อมูลเซลล์ที่ต้องการโดยใช้ [วิธี PutValue](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index). เพิ่มแผนภูมิลงในแผ่นงานโดยใช้คอลเลกชันแผนภูมิ [เพิ่มวิธีการ](https://reference.aspose.com/cells/net/aspose.cells.charts/chartcollection/methods/add). ระบุ [ประเภทแผนภูมิ](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype) จากการแจงนับ ChartType
{{% blocks/products/pf/feature-page-code h3="C# รหัสสำหรับสร้างแผนภูมิ Excel" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "create-excel-chart.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section h2="แปลงแผนภูมิ Excel เป็นรูปภาพ" %}}

ขั้นตอนการแปลงแผนภูมิเป็นรูปภาพ ใช้คลาสเวิร์กบุ๊กเพื่อโหลดไฟล์ Excel เลือกเวิร์กชีตที่เกี่ยวข้องซึ่งมีแผนภูมิและเรียก [วิธีการอิมเมจ](https://reference.aspose.com/cells/net/aspose.cells.charts.chart/toimage/methods/7) สำหรับการแปลง

{{% blocks/products/pf/feature-page-code h3="C# โค้ดสำหรับแปลงแผนภูมิ Excel เป็นรูปภาพ" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "convert-xlsx-file-chart-to-images.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}
