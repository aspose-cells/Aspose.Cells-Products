---
title: วิธีเพิ่ม TextBox ผ่าน Aspose.Cells
weight: 7700
limit:
description: เรียนรู้วิธีเพิ่มกล่องข้อความ
keywords: [Add TextBox., how to add TextBox in Aspose.Cells., how to add TextBox using Aspose.Cells]
url: /th/tutorial/add-textbox-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="เรียนรู้การเพิ่ม TextBox ด้วย Aspose.Cells" >}}

<p>
ในบทช่วยสอนนี้ เราจะเพิ่ม TextBox ในไฟล์ excel
</p>

<p>
 เราจะเริ่มต้นด้วยการสร้างสมุดงานใหม่โดยใช้<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells ห้องสมุด</a> และเพิ่ม TextBox
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: โปรดตรวจสอบโค้ดต่อไปนี้เพื่อดูวิธีการเพิ่ม TextBox
//ExStepSummary:0: โค้ดต่อไปนี้แสดงวิธีการเพิ่ม TextBox และตั้งค่าข้อความ
//ExStepImage:0:step-1.png
//ExStepSummary:1: รหัสต่อไปนี้แสดงวิธีการเปลี่ยนสีของข้อความ
//ExStepImage:1:step-2.png
//ExStepSummary:2: รหัสต่อไปนี้แสดงวิธีการเปลี่ยนมุมการหมุนของ TextBox
//ExStepImage:2:step-3.png
// เอ็กซ์สตาร์ท
//ExStep:0-
โดยใช้ Aspose.Cells;
โดยใช้ Aspose.Cells.Drawing;

สมุดงานสมุดงาน = สมุดงานใหม่ ();
แผ่นงาน = workbook.Worksheets[0];
sheet.PageSetup.PrintGridlines = จริง;
sheet.PageSetup.PrintArea = "A1:F20";

ShapeCollection รูปร่าง = sheet.Shapes;

// เพิ่ม TextBox และตั้งค่าข้อความ
กล่องข้อความ textBox = รูปร่าง AddTextBox(1, 0, 1, 0, 200, 200);
textBox.Text = "Aspose.Cells for .NET เป็นไลบรารีคลาสการเขียนโปรแกรมที่ช่วยให้นักพัฒนาซอฟต์แวร์จัดการและประมวลผลไฟล์สเปรดชีตภายในแอปพลิเคชันของตนเอง";

//ExStep:1-
//เปลี่ยนสีข้อความ
textBox.Font.Color = Color.Blue;

//ExStep:2-
// เปลี่ยนมุมการหมุนของ TextBox
textBox.RotationAngle = 90;

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