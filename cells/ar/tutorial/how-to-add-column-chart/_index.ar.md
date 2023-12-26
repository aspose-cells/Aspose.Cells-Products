---
title: كيفية إضافة مخطط عمودي عبر Aspose.Cells
weight: 7700
limit:
description: تعرف على كيفية إضافة مخطط عمودي.
keywords: [Add column chart., how to add column chart in Aspose.Cells., how to add column chart using Aspose.Cells]
url: /ar/tutorial/add-column-chart-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="تعرف على كيفية إضافة مخطط عمودي مع Aspose.Cells" >}}

<p>
في هذا البرنامج التعليمي، سنقوم بإضافة مخطط عمودي في ملف Excel.
</p>

<p>
 سنبدأ بإنشاء مصنف جديد باستخدام<a href="https://www.nuget.org/packages/Aspose.Cells">مكتبة Aspose.Cells</a> وإضافة مخطط عمودي.
</p>

<br />
{{< app/cells/tutorial >}}
// ExSummary: يرجى التحقق من الكود التالي لمعرفة كيفية إضافة مخطط عمودي.
//ExStepSummary:0: يوضح الكود التالي كيفية إضافة مخطط عمودي.
//ExStepImage:0:step-1.png
//ExStepSummary:1: يوضح الكود التالي كيفية نقل وسيلة الإيضاح إلى اليسار وتعيين لون خط وسيلة الإيضاح.
//ExStepImage:1:step-2.png
//ExStepSummary:2: يوضح الكود التالي كيفية تعيين عنوان المخطط وتغيير لون الخط إلى اللون الأزرق.
//ExStepImage:2:step-3.png
//ExStart
// اكسستيب:0-
باستخدام Aspose.Cells؛
باستخدام Aspose.Cells.الرسم؛

مصنف المصنف = مصنف جديد ()؛
ورقة عمل = Workbook.Worksheets[0];
Sheet.Name = "ChartSheet";
Cells خلية = ورقة.Cells؛
الخلايا ["A1"].Value = "الفاكهة"؛
الخلايا["A2"].Value = "apple";
الخلايا ["A3"].Value = "orange"؛
الخلايا ["A4"].Value = "عنبية"؛
الخلايا["A5"].Value = "kiwi";

الخلايا ["B1"].Value = "السعر"؛
الخلايا ["B2"].Value = 10؛
الخلايا ["B3"].Value = 5؛
الخلايا ["B4"].Value = 20؛
الخلايا ["B5"].Value = 8؛

Sheet.PageSetup.PrintGridlines = true;
Sheet.PageSetup.PrintArea = "A1:F20";

ChartCollection Charts =sheet.Charts;

// إضافة مخطط عمودي
int Index = Charts.Add(ChartType.Column, "=ChartSheet!A1:B5", false, 6, 0, 19, 5);
مخطط الرسم البياني = الرسوم البيانية [الفهرس]؛

//الخطوة السابقة:1-
// انقل وسيلة الإيضاح إلى اليسار واضبط لون خط وسيلة الإيضاح
Chart.Legend.Font.Color = Color.Blue;
Chart.Legend.Position = LegendPositionType.Left;

// اكسستيب:2-
// قم بتعيين عنوان المخطط وتغيير لون الخط إلى اللون الأزرق
Chart.Title.Text = "المخطط العمودي لأسعار الفاكهة";
Chart.Title.Font.Color = Color.Blue;

// اكسستيب:0-

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