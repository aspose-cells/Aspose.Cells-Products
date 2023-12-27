---
title: วิธีเพิ่มกราฟเส้นทาง Aspose.Cells
weight: 7700
limit:
description: เรียนรู้วิธีเพิ่มแผนภูมิเส้น
keywords: [Add line chart., how to add line chart in Aspose.Cells., how to add line chart using Aspose.Cells]
url: /th/tutorial/add-line-chart-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="เรียนรู้การเพิ่มแผนภูมิเส้นกับ Aspose.Cells" >}}

<p>
ในบทช่วยสอนนี้ เราจะเพิ่มแผนภูมิเส้นในไฟล์ Excel
</p>

<p>
 เราจะเริ่มต้นด้วยการสร้างสมุดงานใหม่โดยใช้<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells ห้องสมุด</a> และเพิ่มแผนภูมิเส้น
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: โปรดตรวจสอบโค้ดต่อไปนี้เพื่อดูวิธีเพิ่มแผนภูมิเส้น
//ExStepSummary:0: รหัสต่อไปนี้แสดงวิธีการเพิ่มแผนภูมิเส้น ตั้งค่าช่วงข้อมูลชุด และตั้งค่าช่วงข้อมูลหมวดหมู่
//ExStepImage:0:step-1.png
//ExStepSummary:1: รหัสต่อไปนี้แสดงวิธีการย้ายคำอธิบายแผนภูมิไปที่ด้านล่างและตั้งค่าสีแบบอักษรของคำอธิบายแผนภูมิ
//ExStepImage:1:step-2.png
//ExStepSummary:2: รหัสต่อไปนี้แสดงวิธีการเข้าถึงป้ายกำกับข้อมูล เปิดชื่อหมวดหมู่ และกำหนดตำแหน่ง
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
ใช้ Aspose.Cells;
ใช้ Aspose.Cells.วาดรูป;

สมุดงานสมุดงาน = สมุดงานใหม่ ();
แผ่นงาน = สมุดงาน แผ่นงาน[0];
sheet.Name = "แผนภูมิชีต";
Cells เซลล์ = แผ่น Cells;
เซลล์["A1"].Value = "ผลไม้";
เซลล์["A2"].Value = "แอปเปิ้ล";
เซลล์["A3"].Value = "สีส้ม";
เซลล์["A4"].Value = "บลูเบอร์รี่";
เซลล์["A5"].Value = "กีวี";

เซลล์["B1"].Value = "ราคา";
เซลล์["B2"].ค่า = 10;
เซลล์["B3"].ค่า = 5;
เซลล์["B4"].ค่า = 20;
เซลล์["B5"].ค่า = 8;

sheet.PageSetup.PrintGridlines = จริง;
sheet.PageSetup.PrintArea = "A1:F20";

แผนภูมิ ChartCollection = sheet.Charts;

//เพิ่มแผนภูมิเส้น กำหนดช่วงข้อมูลอนุกรม และกำหนดช่วงข้อมูลหมวดหมู่
ดัชนี int = sheet.Charts.Add(ChartType.Line, 6, 0, 19, 5);
แผนภูมิแผนภูมิ = sheet.Charts[ดัชนี];
chart.NSeries.Add("B2:B5", จริง);
chart.NSeries.CategoryData = "A2:A5";

//ExStep:1-
//ย้ายคำอธิบายไปด้านล่างและตั้งค่าสีตัวอักษรของคำอธิบายแผนภูมิ
chart.Legend.Font.Color = Color.Blue;
chart.Legend.Position = LegendPositionType.Bottom;

//ExStep:2-
//เข้าถึงป้ายกำกับข้อมูล เปิดชื่อหมวดหมู่ และกำหนดตำแหน่ง
DataLabels dataLabels = chart.NSeries[0].DataLabels;
dataLabels.ShowCategoryName = จริง;
dataLabels.Position = LabelPositionType.Center;

//ExStep:0-

//ExEnd
{{< /app/cells/tutorial >}}
<br />

<br />
<br />
<div class="code-sample">
    <ul class="link-list">
        <li class="link-item"><a href="https://docs.aspose.com/cells/net/installation/">ติดตั้งAspose.Cells</a></li>
        <li class="link-item"><a href="https://products.aspose.app/cells/editor/">Aspose.Cells บรรณาธิการ</a></li>
    </ul>
</div>

{{< /blocks/products/pf/feature-page-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}