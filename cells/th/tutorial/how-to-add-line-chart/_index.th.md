---
title: วิธีเพิ่มกราฟเส้นผ่าน Aspose.Cells
weight: 7700
limit:
description: เรียนรู้วิธีเพิ่มแผนภูมิเส้น
keywords: [Add line chart., how to add line chart in Aspose.Cells., how to add line chart using Aspose.Cells]
url: /th/tutorial/add-line-chart-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="เรียนรู้วิธีเพิ่มแผนภูมิเส้นกับ Aspose.Cells" >}}

<p>
ในบทช่วยสอนนี้ เราจะเพิ่มแผนภูมิเส้นในไฟล์ excel
</p>

<p>
 เราจะเริ่มต้นด้วยการสร้างสมุดงานใหม่โดยใช้<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells ห้องสมุด</a> และเพิ่มแผนภูมิเส้น
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: โปรดตรวจสอบโค้ดต่อไปนี้เพื่อดูวิธีเพิ่มแผนภูมิเส้น
//ExStepSummary:0: โค้ดต่อไปนี้แสดงวิธีเพิ่มแผนภูมิเส้น ตั้งค่าช่วงข้อมูลชุดข้อมูล และตั้งค่าช่วงข้อมูลหมวดหมู่
//ExStepImage:0:step-1.png
//ExStepSummary:1: รหัสต่อไปนี้แสดงวิธีการย้ายคำอธิบายแผนภูมิไปที่ด้านล่างและตั้งค่าสีแบบอักษรของคำอธิบายแผนภูมิ
//ExStepImage:1:step-2.png
//ExStepSummary:2: รหัสต่อไปนี้แสดงวิธีการเข้าถึงป้ายข้อมูล เปิดชื่อหมวดหมู่ และกำหนดตำแหน่ง
//ExStepImage:2:step-3.png
// เอ็กซ์สตาร์ท
//ExStep:0-
โดยใช้ Aspose.Cells;
โดยใช้ Aspose.Cells.Drawing;

สมุดงานสมุดงาน = สมุดงานใหม่ ();
แผ่นงาน = workbook.Worksheets[0];
sheet.Name = "แผ่นงานแผนภูมิ";
Cells เซลล์ = sheet.Cells;
เซลล์["A1"].Value = "ผลไม้";
เซลล์ ["A2"].Value = "แอปเปิ้ล";
เซลล์ ["A3"].Value = "ส้ม";
เซลล์ ["A4"].Value = "บลูเบอร์รี่";
เซลล์ ["A5"].Value = "กีวี";

เซลล์["B1"].Value = "ราคา";
เซลล์["B2"].Value = 10;
เซลล์["B3"].Value = 5;
เซลล์["B4"].Value = 20;
เซลล์["B5"].Value = 8;

sheet.PageSetup.PrintGridlines = จริง;
sheet.PageSetup.PrintArea = "A1:F20";

แผนภูมิ ChartCollection = sheet.Charts;

//เพิ่มแผนภูมิเส้น ตั้งค่าช่วงข้อมูลชุดข้อมูล และตั้งค่าช่วงข้อมูลหมวดหมู่
ดัชนี int = sheet.Charts.Add (ChartType.Line, 6, 0, 19, 5);
แผนภูมิ แผนภูมิ = sheet.Charts[ดัชนี];
chart.NSeries.Add("B2:B5", จริง);
chart.NSeries.CategoryData = "A2:A5";

//ExStep:1-
// ย้ายคำอธิบายแผนภูมิไปที่ด้านล่างและตั้งค่าสีตัวอักษรของคำอธิบายแผนภูมิ
chart.Legend.Font.Color = Color.Blue;
chart.Legend.Position = LegendPositionType.Bottom;

//ExStep:2-
// เข้าถึงป้ายชื่อข้อมูล เปิดใช้ชื่อหมวดหมู่ และกำหนดตำแหน่ง
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
        <li class="link-item"><a href="https://docs.aspose.com/cells/net/installation/">งานติดตั้งAspose.Cells</a></li>
        <li class="link-item"><a href="https://products.aspose.app/cells/editor/">Aspose.Cells บรรณาธิการ</a></li>
    </ul>
</div>

{{< /blocks/products/pf/feature-page-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}