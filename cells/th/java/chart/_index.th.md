---
title: สร้างแผนภูมิ Excel และแปลงเป็นรูปภาพ via Java
description:  ซอร์สโค้ด Java เพื่อวาดและแปลงแผนภูมิหรือไดอะแกรมใน Microsoft Excel โดยใช้ Java Library
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> การแปลงและสร้างแผนภูมิไฟล์ Excel via Java" h2="แปลงแผนภูมิเอกสาร Excel เป็นรูปภาพ รวมทั้งสร้างแผนภูมิต่างๆ โดยใช้ API ฝั่งเซิร์ฟเวอร์ภายในแอปพลิเคชันที่ใช้ Java" >}}


{{% blocks/products/pf/feature-page-summary %}}

 การวิเคราะห์ข้อมูลผ่านแผนภูมิจะแสดงให้เห็นภาพรวมที่ใหญ่ขึ้น และง่ายต่อการตัดสินใจโดยมีข้อมูลมากขึ้นด้วยข้อมูลเชิงลึกที่ชัดเจนยิ่งขึ้น[Java คลังเอ็กเซล](/cells/th/java/) รองรับการวาดการสร้างแผนภูมิต่าง ๆ ที่แสดงรายการโดย[ประเภทแผนภูมิ](https://reference.aspose.com/cells/java/com.aspose.cells/ChartType) รวมถึงแผนภูมิวงกลม พีระมิด เส้น และฟอง นอกจากนี้ยังแปลงแผนภูมิเป็นภาพ API ให้บริการ[คลาสแผนภูมิ](https://reference.aspose.com/cells/java/com.aspose.cells/Chart)สำหรับการแสดงแผนภูมิ Excel เดียว

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="แปลงแผนภูมิ Excel เป็นรูปภาพ" %}}

 ขั้นตอนการแปลงแผนภูมิเป็นภาพ ได้แก่ JPG, PNG, TIFF, BMP เป็นต้น คือ ใช้[สมุดงาน](https://reference.aspose.com/java/cells/com.aspose.cells/workbook) class เพื่อโหลดไฟล์ Excel เลือกที่เกี่ยวข้อง[ชุดงาน](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet) ที่มีแผนภูมิหรือวนซ้ำในแต่ละแผนภูมิในแต่ละแผ่นงาน กำหนด[ImageOrPrintOptions](https://reference.aspose.com/cells/java/com.aspose.cells/ImageOrPrintOptions) และแสดงภาพเอาต์พุตของแผนภูมิโดยใช้[Chart.toImage](https://reference.aspose.com/cells/java/com.aspose.cells/chart#toImage(java.io.OutputStream,%20com.aspose.cells.ImageOrPrintOptions)).


{{% blocks/products/pf/feature-page-code h3="Java รหัสสำหรับแปลงแผนภูมิ Excel เป็นรูปภาพ" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "render-excel-chart-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}


{{% blocks/products/pf/feature-page-section h2="สร้างแผนภูมิภายในไฟล์ Excel" %}}

 การสร้างแผนภูมิโดยใช้ Excel API เป็นเรื่องง่าย เนื่องจาก API มีชุดของคลาสต่างๆ เช่น Axis, Chart, ChartArea, ChartDataTable, ChartFrame, ChartPoint, ChartPointCollection, ChartCollection เป็นต้น สำหรับแผนภูมิประเภทต่างๆ กระบวนการคือสร้างวัตถุคลาสสมุดงานและเลือกแผ่นงานแรกหรือแผ่นงานที่เกี่ยวข้องโดยระบุดัชนี สำหรับแหล่งข้อมูลของแผนภูมิ ให้แทรกค่าลงในเซลล์แผ่นงานโดยใช้[ตั้งค่า](https://reference.aspose.com/cells/java/com.aspose.cells/cell#Value)วิธี. ใช้คอลเลกชันของ ChartCollection[เพิ่มวิธีการ](https://reference.aspose.com/cells/java/com.aspose.cells/chartcollection#add(int,%20int,%20int,%20int,%20int) ) เพื่อเพิ่มแผนภูมิ กำหนดประเภทของแผนภูมิด้วยการแจงนับ ChartType เข้าถึงวัตถุแผนภูมิใหม่จากคอลเลกชัน ChartCollection โดยผ่านดัชนี ใช้[ชุดสะสม](https://reference.aspose.com/cells/java/com.aspose.cells/SeriesCollection) การสร้างแผนภูมิเพื่อระบุแหล่งข้อมูลของแผนภูมิ

{{% blocks/products/pf/feature-page-code h3="Java รหัสเพื่อสร้างแผนภูมิ Excel" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "create-excel-chart-pyramid.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
