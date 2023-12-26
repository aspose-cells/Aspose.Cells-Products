---
title: طريقة اضافة الاشكال عبر الرقم Aspose.Cells
weight: 7700
limit:
description: تعرف على كيفية إضافة الأشكال.
keywords: [add shapes., how to add shapes in Aspose.Cells., how to add shapes using Aspose.Cells]
url: /ar/tutorial/add-shapes-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="تعلم كيفية إضافة الأشكال مع Aspose.Cells" >}}

<p>
في هذا البرنامج التعليمي، سنقوم بإضافة الأشكال في ملف Excel.
</p>

<p>
 سنبدأ بإنشاء مصنف جديد باستخدام<a href="https://www.nuget.org/packages/Aspose.Cells">مكتبة Aspose.Cells</a> وإضافة الأشكال.
</p>

<br />
{{< app/cells/tutorial >}}
// ExSummary: يرجى التحقق من الكود التالي لمعرفة كيفية إضافة الأشكال.
//ExStepSummary:0: يوضح الكود التالي كيفية إضافة شكل مستطيل.
//ExStepImage:0:step-1.png
//ExStepSummary:1: يوضح الكود التالي كيفية إضافة شكل خط.
//ExStepImage:1:step-2.png
//ExStepSummary:2: الكود التالي يوضح كيفية إضافة شكل بيضاوي.
//ExStepImage:2:step-3.png
//ExStart
// اكسستيب:0-
باستخدام Aspose.Cells؛
باستخدام Aspose.Cells.الرسم؛





مصنف المصنف = مصنف جديد ()؛
ورقة عمل = Workbook.Worksheets[0];
Sheet.PageSetup.PrintGridlines = true;
Sheet.PageSetup.PrintArea = "A1:F20";

ShapeCollection Shapes = Sheet.Shapes;

// أضف شكل مستطيل
Shapes.AddRectangle(1, 0, 1, 0, 100, 150);

//الخطوة السابقة:1-
// أضف شكل خط
Shapes.AddLine(8, 0, 1, 0, 100, 150);

// اكسستيب:2-
// أضف شكل بيضاوي
Shapes.AddOval(13, 0, 1, 0, 100, 150);

// اكسستيب:0-
دفتر العمل
//انتهى
{{< /app/cells/tutorial >}}
<br />

<br />
<br />
<div class="code-sample">
    <ul class="link-list">
        <li class="link-item"><a href="https://docs.aspose.com/cells/net/installation/">تركيب Aspose.Cells</a></li>
        <li class="link-item"><a href="https://products.aspose.app/cells/editor/">Aspose.Cells محرر</a></li>
    </ul>
</div>

{{< /blocks/products/pf/feature-page-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}