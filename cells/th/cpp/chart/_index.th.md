---
title: สร้างแผนภูมิ Excel และแปลงเป็นรูปภาพผ่าน C++

description: C++ ซอร์สโค้ดสำหรับวาดและแปลงแผนภูมิหรือไดอะแกรมใน Microsoft Excel โดยใช้ C++ Library
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="สร้าง Microsoft<sup>&reg;</sup> แผนภูมิ Excel และแปลงเป็นรูปภาพผ่าน C++" h2="แปลงแผนภูมิเอกสาร Excel เป็นรูปภาพ รวมทั้งสร้างแผนภูมิรวมถึงแผนภูมิวงกลม พีระมิด เส้น และฟองภายในแอปพลิเคชันที่ใช้ C++" >}}

{{% blocks/products/pf/feature-page-summary %}}

การใช้แผนภูมิ Excel จะทำให้ได้ภาพที่ใหญ่ขึ้นและวิเคราะห์ข้อมูลเพื่อการตัดสินใจที่ถูกต้องได้อย่างง่ายดาย [C++ ไลบรารี Excel](/cells/cpp/) รองรับการสร้างแผนภูมิที่แตกต่างกันโดย [enum Aspose::Cells::Charts::ChartType
](https://reference.aspose.com/cells/cpp/namespace/aspose.cells.charts#a2f17e69bcefc754569019185d0621b70) รวมถึงแผนภูมิพื้นที่ แท่ง พาย พีระมิด เส้น และฟองอากาศ นอกจากนี้ สำหรับการแปลงแผนภูมิเป็นรูปภาพ API ให้ a [ToImage mehtod](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_sparkline#a28d76dd585c48366e1657f2982722ddb) ในรูปแบบภาพที่ต้องการ

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="สร้างแผนภูมิ Excel" %}}

ขั้นตอนการสร้างแผนภูมิ Excel คือ สร้างอินสแตนซ์ของ [คลาส IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) และเลือกแบบที่ต้องการ [ใบงาน](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet_collection#a5574d624796043233420d0e0459ccc43). เพิ่มแผนภูมิโดยใช้ [เพิ่มวิธีการ](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_chart_collection#ab7e8cce835c251a4682605299a6aa068) ด้วยพารามิเตอร์ที่เกี่ยวข้องรวมถึงประเภทแผนภูมิ เข้าถึงแผนภูมิผ่านดัชนีและ [เพิ่ม](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_series_collection#a8f4dc4d883f32f65b1fb673e2aa7862f) แหล่งข้อมูลสำหรับแผนภูมิ

{{% blocks/products/pf/feature-page-code h3="C++ รหัสสำหรับสร้างแผนภูมิ Excel" %}}

{{< gist "aspose-com-gists" "da2fd423617bf9013a7673870c81d708" "create-excel-chart.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="แปลงแผนภูมิเป็นรูปภาพ" %}}


สำหรับขั้นตอนการแปลงแผนภูมิ ขั้นแรกให้สร้างแผนภูมิตามประเภทที่เกี่ยวข้องโดยใช้โค้ดด้านบนหรือเข้าถึงจากชีตที่เกี่ยวข้อง กำหนดเส้นทางการบันทึกเอาต์พุตสำหรับรูปภาพและใช้วิธี ToImage สำหรับการแปลง

 
{{% blocks/products/pf/feature-page-code h3="C++ โค้ดสำหรับแปลงแผนภูมิ Excel" %}}

{{< gist "aspose-com-gists" "da2fd423617bf9013a7673870c81d708" "convert-excel-chart-to-image.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}
