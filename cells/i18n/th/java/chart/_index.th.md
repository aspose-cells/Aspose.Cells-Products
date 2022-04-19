---
title: สร้างแผนภูมิ Excel และแปลงเป็นรูปภาพผ่าน Java
url: /th/java/chart/
description: Java ซอร์สโค้ดสำหรับวาดและแปลงแผนภูมิหรือไดอะแกรมใน Microsoft Excel โดยใช้ Java Library 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> การแปลงและสร้างแผนภูมิไฟล์ Excel ผ่าน Java" h2="แปลงแผนภูมิเอกสาร Excel เป็นรูปภาพ และสร้างแผนภูมิต่างๆ โดยใช้ API ฝั่งเซิร์ฟเวอร์ภายในแอปพลิเคชันที่ใช้ Java" >}}


{{% blocks/products/pf/feature-page-summary %}}

การวิเคราะห์ข้อมูลผ่านแผนภูมิจะแสดงภาพที่ใหญ่ขึ้น และง่ายต่อการตัดสินใจอย่างมีข้อมูลมากขึ้นด้วยข้อมูลเชิงลึกที่ชัดเจนยิ่งขึ้น [Java ไลบรารี Excel](/cells/java/) รองรับการวาดการสร้างแผนภูมิที่แตกต่างกันตามรายการโดย [ประเภทแผนภูมิ](https://apireference.aspose.com/cells/java/com.aspose.cells/ChartType) รวมถึงแผนภูมิวงกลม พีระมิด เส้น และฟองสบู่ นอกจากนี้ยังแปลงแผนภูมิเป็นรูปภาพ API ให้ a [คลาสชาร์ต](https://apireference.aspose.com/cells/java/com.aspose.cells/Chart) สำหรับแสดงแผนภูมิ Excel เดียว

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="แปลงแผนภูมิ Excel เป็นรูปภาพ" %}}

ขั้นตอนการแปลงแผนภูมิเป็นรูปภาพรวมถึง JPG, PNG, TIFF, BMP เป็นต้นคือ ใช้ [สมุดงาน](https://apireference.aspose.com/java/cells/com.aspose.cells/workbook) คลาสที่จะโหลดไฟล์ Excel เลือกที่เกี่ยวข้อง [ชุดทำงาน](https://apireference.aspose.com/cells/java/com.aspose.cells/worksheet) มีแผนภูมิหรือวนซ้ำในแต่ละแผนภูมิในแต่ละแผ่นงาน กำหนด [ImageOrPrintOptions](https://apireference.aspose.com/cells/java/com.aspose.cells/ImageOrPrintOptions) และแสดงผลภาพที่ส่งออกของแผนภูมิโดยใช้ [Chart.toImage](https://apireference.aspose.com/cells/java/com.aspose.cells/chart#toImage(java.io.OutputStream,%20com.aspose.cells.ImageOrPrintOptions)).


{{% blocks/products/pf/feature-page-code h3="Java โค้ดสำหรับแปลงแผนภูมิ Excel เป็นรูปภาพ" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "render-excel-chart-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}


{{% blocks/products/pf/feature-page-section h2="สร้างแผนภูมิภายในไฟล์ Excel" %}}

การสร้างแผนภูมิโดยใช้ Excel API เป็นเรื่องง่าย เนื่องจาก API มีชุดของคลาสต่างๆ เช่น Axis, Chart, ChartArea, ChartDataTable, ChartFrame, ChartPoint, ChartPointCollection, ChartCollection เป็นต้น สำหรับแผนภูมิประเภทต่างๆ กระบวนการคือ สร้างวัตถุคลาสสมุดงาน และเลือกแผ่นงานแรกหรือแผ่นงานที่เกี่ยวข้องโดยระบุดัชนี สำหรับแหล่งข้อมูลของแผนภูมิ ให้แทรกค่าลงในเซลล์ของเวิร์กชีตโดยใช้ [ตั้งค่า](https://apireference.aspose.com/cells/java/com.aspose.cells/cell#Value) กระบวนการ. ใช้คอลเลกชันของ ChartCollection [เพิ่มวิธีการ](https://apireference.aspose.com/cells/java/com.aspose.cells/chartcollection#add(int,%20int,%20int,%20int,%20int)) ในการเพิ่มแผนภูมิ ให้กำหนดประเภทของแผนภูมิด้วยการแจงนับ ChartType เข้าถึงออบเจ็กต์ Chart ใหม่จากคอลเล็กชัน ChartCollection โดยส่งดัชนี ใช้ [SeriesCollection](https://apireference.aspose.com/cells/java/com.aspose.cells/SeriesCollection) การสร้างแผนภูมิวัตถุเพื่อระบุแหล่งข้อมูลของแผนภูมิ

{{% blocks/products/pf/feature-page-code h3="Java รหัสสำหรับสร้างแผนภูมิ Excel" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "create-excel-chart-pyramid.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}