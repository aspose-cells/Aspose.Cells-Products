---
title: วิธีเพิ่มแผนภูมิคอลัมน์ทาง Aspose.Cells
weight: 7700
limit:
description: เรียนรู้วิธีเพิ่มแผนภูมิคอลัมน์
keywords: [Add column chart., how to add column chart in Aspose.Cells., how to add column chart using Aspose.Cells]
url: /th/tutorial/add-column-chart-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="เรียนรู้วิธีเพิ่มแผนภูมิคอลัมน์ด้วย Aspose.Cells" >}}

<p>
ในบทช่วยสอนนี้ เราจะเพิ่มแผนภูมิคอลัมน์ในไฟล์ Excel
</p>

<p>
 เราจะเริ่มต้นด้วยการสร้างสมุดงานใหม่โดยใช้<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells ห้องสมุด</a> และเพิ่มแผนภูมิคอลัมน์
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: โปรดตรวจสอบโค้ดต่อไปนี้เพื่อดูวิธีเพิ่มแผนภูมิคอลัมน์
//ExStepSummary:0: รหัสต่อไปนี้แสดงวิธีการเพิ่มแผนภูมิคอลัมน์
//ExStepImage:0:step-1.png
//ExStepSummary:1: รหัสต่อไปนี้แสดงวิธีการย้ายคำอธิบายไปทางซ้ายและตั้งค่าสีแบบอักษรของคำอธิบายแผนภูมิ
//ExStepImage:1:step-2.png
//ExStepSummary:2: รหัสต่อไปนี้แสดงวิธีตั้งชื่อแผนภูมิและเปลี่ยนสีแบบอักษรเป็นสีน้ำเงิน
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

//เพิ่มแผนภูมิคอลัมน์
int index = charts.Add(ChartType.Column, "=ChartSheet!A1:B5", false, 6, 0, 19, 5);
แผนภูมิแผนภูมิ = แผนภูมิ [ดัชนี];

//ExStep:1-
//เลื่อนคำอธิบายไปทางซ้ายและตั้งค่าสีตัวอักษรของคำอธิบายแผนภูมิ
chart.Legend.Font.Color = Color.Blue;
chart.Legend.Position = LegendPositionType.ซ้าย;

//ExStep:2-
//ตั้งชื่อแผนภูมิและเปลี่ยนสีตัวอักษรเป็นสีน้ำเงิน
chart.Title.Text = "แผนภูมิคอลัมน์ราคาผลไม้";
chart.Title.Font.Color = Color.Blue;

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