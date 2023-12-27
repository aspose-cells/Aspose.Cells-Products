---
title: วิธีเพิ่มกล่องข้อความทาง Aspose.Cells
weight: 7700
limit:
description: เรียนรู้วิธีเพิ่มกล่องข้อความ
keywords: [Add TextBox., how to add TextBox in Aspose.Cells., how to add TextBox using Aspose.Cells]
url: /th/tutorial/add-textbox-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="เรียนรู้วิธีเพิ่มกล่องข้อความด้วย Aspose.Cells" >}}

<p>
ในบทช่วยสอนนี้ เราจะเพิ่มกล่องข้อความในไฟล์ Excel
</p>

<p>
 เราจะเริ่มต้นด้วยการสร้างสมุดงานใหม่โดยใช้<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells ห้องสมุด</a> และเพิ่มกล่องข้อความ
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: โปรดตรวจสอบโค้ดต่อไปนี้เพื่อดูวิธีเพิ่มกล่องข้อความ
//ExStepSummary:0: รหัสต่อไปนี้แสดงวิธีการเพิ่มกล่องข้อความและตั้งค่าข้อความ
//ExStepImage:0:step-1.png
//ExStepSummary:1: รหัสต่อไปนี้แสดงวิธีการเปลี่ยนสีของข้อความ
//ExStepImage:1:step-2.png
//ExStepSummary:2: รหัสต่อไปนี้แสดงวิธีการเปลี่ยนมุมการหมุนของกล่องข้อความ
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
ใช้ Aspose.Cells;
ใช้ Aspose.Cells.วาดรูป;

สมุดงานสมุดงาน = สมุดงานใหม่ ();
แผ่นงาน = สมุดงาน แผ่นงาน[0];
sheet.PageSetup.PrintGridlines = จริง;
sheet.PageSetup.PrintArea = "A1:F20";

รูปร่าง ShapeCollection = แผ่น รูปร่าง;

//เพิ่มกล่องข้อความและตั้งค่าข้อความ
กล่องข้อความ textBox = รูปร่าง AddTextBox(1, 0, 1, 0, 200, 200);
textBox.Text = "Aspose.Cells for .NET เป็นไลบรารีคลาสการเขียนโปรแกรมที่ช่วยให้นักพัฒนาซอฟต์แวร์จัดการและประมวลผลไฟล์สเปรดชีตภายในแอปพลิเคชันของตนเอง";

//ExStep:1-
//เปลี่ยนสีข้อความ
textBox.Font.Color = Color.Blue;

//ExStep:2-
//เปลี่ยนมุมการหมุนของกล่องข้อความ
กล่องข้อความ RotationAngle = 90;

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