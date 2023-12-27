---
title: สร้างแผนภูมิ Excel และแปลงเป็นรูปภาพ via Java
description:  Java ซอร์สโค้ดสำหรับวาดและแปลงแผนภูมิหรือไดอะแกรมใน Microsoft Excel โดยใช้ Java Library
keywords: [Java Aspose.Cells., Java Convert chart to image., Java Save chart to image., Java chart to image., create charts in Java., insert charts in Java., manage charts in Java]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> การแปลงและสร้างแผนภูมิไฟล์ Excel via Java" h2="แปลงแผนภูมิเอกสาร Excel เป็นรูปภาพ รวมถึงสร้างแผนภูมิต่างๆ โดยใช้ API ฝั่งเซิร์ฟเวอร์ภายในแอปพลิเคชันที่ใช้ Java" >}}


{{% blocks/products/pf/feature-page-summary %}}

 การวิเคราะห์ข้อมูลผ่านแผนภูมิจะแสดงภาพที่ใหญ่ขึ้น และง่ายต่อการตัดสินใจโดยใช้ข้อมูลประกอบมากขึ้นด้วยข้อมูลเชิงลึกที่ชัดเจนยิ่งขึ้น[Java เอ็กเซล ไลบรารี่](/cells/th/java/) รองรับการวาดการสร้างแผนภูมิที่แตกต่างกันตามรายการ[ChartType](https://reference.aspose.com/cells/java/com.aspose.cells/ChartType) รวมถึงแผนภูมิวงกลม พีระมิด เส้น และฟองสบู่ นอกจากนี้ยังแปลงแผนภูมิเป็นรูปภาพอีกด้วย APIจัดให้[ชั้นเรียนแผนภูมิ](https://reference.aspose.com/cells/java/com.aspose.cells/Chart) สำหรับการแสดงแผนภูมิ Excel เดียว

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="แปลงแผนภูมิ Excel เป็นรูปภาพ" %}}

 กระบวนการแปลงแผนภูมิเป็นรูปภาพ ได้แก่ JPG, PNG, TIFF, BMP ฯลฯ คือ ใช้[สมุดงาน](https://reference.aspose.com/java/cells/com.aspose.cells/workbook) คลาสที่จะโหลดไฟล์ Excel ให้เลือกคลาสที่เกี่ยวข้อง[ชุดทำงาน](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet) ที่มีแผนภูมิหรือวนซ้ำแต่ละแผนภูมิในแต่ละแผ่นงาน กำหนด[รูปภาพหรือตัวเลือกการพิมพ์](https://reference.aspose.com/cells/java/com.aspose.cells/ImageOrPrintOptions) และแสดงภาพเอาต์พุตของแผนภูมิโดยใช้[Chart.toImage](https://reference.aspose.com/cells/java/com.aspose.cells/chart#toImage(java.io.OutputStream,%20com.aspose.cells.ImageOrPrintOptions)).


{{% blocks/products/pf/feature-page-code h3="Java รหัสแปลงแผนภูมิ Excel เป็นรูปภาพ" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "render-excel-chart-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}


{{% blocks/products/pf/feature-page-section h2="สร้างแผนภูมิภายในไฟล์ Excel" %}}

การสร้างแผนภูมิโดยใช้ Excel API นั้นง่ายดาย เนื่องจาก API มีชุดของคลาสที่แตกต่างกัน เช่น Axis, Chart, ChartArea, ChartDataTable, ChartFrame, ChartPoint, ChartPointCollection, ChartCollection ฯลฯ สำหรับแผนภูมิประเภทต่างๆ กระบวนการคือ สร้างวัตถุคลาสสมุดงาน และเลือกแผ่นงานแรกหรือแผ่นงานที่เกี่ยวข้องโดยจัดทำดัชนี สำหรับแหล่งข้อมูลของแผนภูมิ ให้แทรกค่าลงในเซลล์แผ่นงานโดยใช้[ตั้งค่า](https://reference.aspose.com/cells/java/com.aspose.cells/cell#Value) วิธี. ใช้คอลเลกชัน ChartCollection[เพิ่มวิธีการ](https://reference.aspose.com/cells/java/com.aspose.cells/chartcollection#add(int,%20int,%20int,%20int,%20int) ) เพื่อเพิ่มแผนภูมิ ให้กำหนดประเภทของแผนภูมิด้วยการแจงนับ ChartType เข้าถึงวัตถุแผนภูมิใหม่จากคอลเลกชัน ChartCollection โดยส่งดัชนี ใช้[ซีรีส์คอลเลกชัน](https://reference.aspose.com/cells/java/com.aspose.cells/SeriesCollection) การสร้างแผนภูมิวัตถุเพื่อระบุแหล่งข้อมูลของแผนภูมิ

{{% blocks/products/pf/feature-page-code h3="Java โค้ดสร้างแผนภูมิ Excel" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "create-excel-chart-pyramid.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
