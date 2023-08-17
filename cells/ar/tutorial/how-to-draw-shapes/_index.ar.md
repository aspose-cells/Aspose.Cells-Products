---
title: طريقة اضافة الأشكال عن طريق Aspose.Cells
weight: 7700
limit:
description: تعرف على كيفية إضافة الأشكال.
keywords: [add shapes., how to add shapes in Aspose.Cells., how to add shapes using Aspose.Cells]
url: /ar/tutorial/add-shapes-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="تعرف على كيفية إضافة الأشكال باستخدام Aspose.Cells" >}}

<p>
في هذا البرنامج التعليمي ، سنضيف أشكالًا في ملف Excel.
</p>

<p>
 سنبدأ بإنشاء مصنف جديد باستخدام ملف<a href="https://www.nuget.org/packages/Aspose.Cells">مكتبة Aspose.Cells</a> وأضف الأشكال.
</p>

<br />
{{< app/cells/tutorial >}}
// ExSummary: الرجاء التحقق من الكود التالي لمعرفة كيفية إضافة الأشكال.
// ExStepSummary: 0: يوضح الكود التالي كيفية إضافة شكل مستطيل.
//ExStepImage:0:step-1.png
// ExStepSummary: 1: يوضح الكود التالي كيفية إضافة شكل الخط.
//ExStepImage:1:step-2.png
// ExStepSummary: 2: يوضح الكود التالي كيفية إضافة شكل بيضاوي.
//ExStepImage:2:step-3.png
// ExStart
// ExStep: 0-
باستخدام Aspose.Cells ؛
باستخدام Aspose.Cells. الرسم ؛





مصنف المصنف = مصنف جديد () ؛
ورقة العمل = workbook.Worksheets [0] ؛
sheet.PageSetup.PrintGridlines = صحيح ،
sheet.PageSetup.PrintArea = "A1: F20" ؛

أشكال ShapeCollection = sheet.Shapes ؛

// أضف شكل مستطيل
الأشكال إضافة مستطيل (1 ، 0 ، 1 ، 0 ، 100 ، 150) ؛

// ExStep: 1-
// أضف شكل الخط
الأشكال الإضافية (8 ، 0 ، 1 ، 0 ، 100 ، 150) ؛

// ExStep: 2-
// أضف شكل بيضاوي
الأشكال. AddOval (13 ، 0 ، 1 ، 0 ، 100 ، 150) ؛

// ExStep: 0-
دفتر العمل
// ExEnd
{{< /app/cells/tutorial >}}
<br />

<br />
<br />
<div class="code-sample">
    <ul class="link-list">
        <li class="link-item"><a href="https://docs.aspose.com/cells/net/installation/">تركيب Aspose.Cells</a></li>
        <li class="link-item"><a href="https://products.aspose.app/cells/editor/">Aspose.Cells المحرر</a></li>
    </ul>
</div>

{{< /blocks/products/pf/feature-page-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}