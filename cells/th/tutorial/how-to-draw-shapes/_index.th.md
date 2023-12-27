---
title: วิธีเพิ่มรูปทรงทางAspose.Cells
weight: 7700
limit:
description: เรียนรู้วิธีการเพิ่มรูปร่าง
keywords: [add shapes., how to add shapes in Aspose.Cells., how to add shapes using Aspose.Cells]
url: /th/tutorial/add-shapes-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="เรียนเพิ่มรูปทรงกับ Aspose.Cells" >}}

<p>
ในบทช่วยสอนนี้ เราจะเพิ่มรูปร่างในไฟล์ Excel
</p>

<p>
 เราจะเริ่มต้นด้วยการสร้างสมุดงานใหม่โดยใช้<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells ห้องสมุด</a> และเพิ่มรูปทรง
</p>

<br />
{{< app/cells/tutorial >}}
//ตัวอย่างสรุป: โปรดตรวจสอบโค้ดต่อไปนี้เพื่อดูวิธีเพิ่มรูปร่าง
//ExStepSummary:0: รหัสต่อไปนี้แสดงวิธีการเพิ่มรูปร่างสี่เหลี่ยมผืนผ้า
//ExStepImage:0:step-1.png
//ExStepSummary:1: รหัสต่อไปนี้แสดงวิธีการเพิ่มรูปร่างเส้น
//ExStepImage:1:step-2.png
//ExStepSummary:2: รหัสต่อไปนี้แสดงวิธีการเพิ่มรูปร่างวงรี
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

//เพิ่มรูปทรงสี่เหลี่ยม
รูปร่างเพิ่มสี่เหลี่ยมผืนผ้า (1, 0, 1, 0, 100, 150);

//ExStep:1-
//เพิ่มรูปทรงเส้น
รูปร่างAddLine(8, 0, 1, 0, 100, 150);

//ExStep:2-
//เพิ่มรูปทรงวงรี
รูปร่างAddOval(13, 0, 1, 0, 100, 150);

//ExStep:0-
สมุดงาน
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