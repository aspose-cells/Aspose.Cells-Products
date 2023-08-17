---
title: كيفية إضافة مخطط دائري عبر Aspose.Cells
weight: 7700
limit:
description: تعرف على كيفية إضافة مخطط دائري.
keywords: [Add pie chart., how to add pie chart in Aspose.Cells., how to add pie chart using Aspose.Cells]
url: /ar/tutorial/add-pie-chart-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="تعرف على كيفية إضافة الرسم البياني الدائري مع Aspose.Cells" >}}

<p>
في هذا البرنامج التعليمي ، سنضيف مخطط دائري في ملف Excel.
</p>

<p>
 سنبدأ بإنشاء مصنف جديد باستخدام ملف<a href="https://www.nuget.org/packages/Aspose.Cells">مكتبة Aspose.Cells</a> وأضف مخطط دائري.
</p>

<br />
{{< app/cells/tutorial >}}
// ExSummary: يرجى التحقق من الكود التالي لمعرفة كيفية إضافة مخطط دائري.
// ExStepSummary: 0: يوضح الكود التالي كيفية إضافة مخطط دائري وتعيين نطاق بيانات السلسلة وتعيين نطاق بيانات الفئة.
//ExStepImage:0:step-1.png
// ExStepSummary: 1: يوضح الكود التالي كيفية إيقاف تشغيل وسيلة الإيضاح.
//ExStepImage:1:step-2.png
// ExStepSummary: 2: يوضح الكود التالي كيفية الوصول إلى تسميات البيانات وتشغيل أسماء الفئات وتشغيل تنسيق النسبة المئوية وتعيين الموضع.
//ExStepImage:2:step-3.png
// ExStart
// ExStep: 0-
باستخدام Aspose.Cells ؛
باستخدام Aspose.Cells. الرسم ؛

مصنف المصنف = مصنف جديد () ؛
ورقة العمل = workbook.Worksheets [0] ؛
sheet.Name = "ChartSheet" ؛
Cells خلايا = ورقة .Cells ؛
الخلايا ["A1"]. القيمة = "الفاكهة" ؛
الخلايا ["A2"]. القيمة = "تفاحة" ؛
الخلايا ["A3"]. القيمة = "برتقالي" ؛
الخلايا ["A4"]. القيمة = "عنبية" ؛
خلايا ["A5"]. القيمة = "كيوي" ؛

الخلايا ["B1"]. القيمة = "السعر" ؛
الخلايا ["B2"]. القيمة = 10 ؛
خلايا ["B3"]. القيمة = 5 ؛
خلايا ["B4"]. القيمة = 20 ؛
خلايا ["B5"]. القيمة = 8 ؛

sheet.PageSetup.PrintGridlines = صحيح ،
sheet.PageSetup.PrintArea = "A1: F20" ؛

مخططات المجموعة = sheet.Charts ؛

// إضافة مخطط دائري ، وتعيين نطاق بيانات السلسلة وتعيين نطاق بيانات الفئة
فهرس int = sheet.Charts.Add (ChartType.Pie، 6، 0، 19، 5) ؛
مخطط الرسم البياني = sheet.Charts [index] ؛
chart.NSeries.Add ("B2: B5" ، صحيح) ؛
chart.NSeries.CategoryData = "A2: A5" ؛

// ExStep: 1-
// إيقاف الأسطورة
chart.ShowLegend = خطأ ؛

// ExStep: 2-
// الوصول إلى تسميات البيانات وتشغيل أسماء الفئات وتشغيل تنسيق النسبة المئوية وتعيين الموضع
DataLabels dataLabels = chart.NSeries [0] .DataLabels؛
dataLabels.ShowCategoryName = صحيح ؛
dataLabels.ShowPercentage = صحيح ،
dataLabels.Position = LabelPositionType.OutsideEnd ؛

// ExStep: 0-

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