---
title: วิธีเพิ่มรูปทรง โดย Aspose.Cells
weight: 7700
limit:
description: เรียนรู้วิธีเพิ่มรูปร่าง
keywords: [add shapes., how to add shapes in Aspose.Cells., how to add shapes using Aspose.Cells]
url: /th/tutorial/add-shapes-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="เรียนรู้การเพิ่มรูปทรงด้วย Aspose.Cells" >}}

<p>
ในบทช่วยสอนนี้ เราจะเพิ่มรูปร่างในไฟล์ excel
</p>

<p>
 เราจะเริ่มต้นด้วยการสร้างสมุดงานใหม่โดยใช้<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells ห้องสมุด</a> และเพิ่มรูปร่าง
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: โปรดตรวจสอบโค้ดต่อไปนี้เพื่อดูวิธีเพิ่มรูปร่าง
//ExStepSummary:0: รหัสต่อไปนี้แสดงวิธีการเพิ่มรูปร่างสี่เหลี่ยมผืนผ้า
//ExStepImage:0:step-1.png
//ExStepSummary:1: รหัสต่อไปนี้แสดงวิธีการเพิ่มรูปร่างบรรทัด
//ExStepImage:1:step-2.png
//ExStepSummary:2: รหัสต่อไปนี้แสดงวิธีการเพิ่มรูปไข่
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

// เพิ่มรูปทรงสี่เหลี่ยมผืนผ้า
รูปร่าง AddRectangle(1, 0, 1, 0, 100, 150);

//ExStep:1-
// เพิ่มรูปร่างของเส้น
รูปร่าง AddLine (8, 0, 1, 0, 100, 150);

//ExStep:2-
// เพิ่มรูปวงรี
รูปร่าง AddOval (13, 0, 1, 0, 100, 150);

//ExStep:0-
สมุดงาน
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