---
title: كيفية إضافة مخطط خطي عبر Aspose.Cells
weight: 7700
limit:
description: تعرف على كيفية إضافة مخطط خطي.
keywords: [Add line chart., how to add line chart in Aspose.Cells., how to add line chart using Aspose.Cells]
url: /ar/tutorial/add-line-chart-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="تعرف على كيفية إضافة مخطط خطي مع Aspose.Cells" >}}

<p>
في هذا البرنامج التعليمي، سنقوم بإضافة مخطط خطي في ملف Excel.
</p>

<p>
 سنبدأ بإنشاء مصنف جديد باستخدام<a href="https://www.nuget.org/packages/Aspose.Cells">مكتبة Aspose.Cells</a> وإضافة مخطط خطي.
</p>

<br />
{{< app/cells/tutorial >}}
// ExSummary: يرجى التحقق من الكود التالي لمعرفة كيفية إضافة مخطط خطي.
//ExStepSummary:0: يوضح الكود التالي كيفية إضافة مخطط خطي وتعيين نطاق بيانات السلسلة وتعيين نطاق بيانات الفئة.
//ExStepImage:0:step-1.png
//ExStepSummary:1: يوضح الكود التالي كيفية نقل وسيلة الإيضاح إلى الأسفل وتعيين لون خط وسيلة الإيضاح.
//ExStepImage:1:step-2.png
//ExStepSummary:2: يوضح الكود التالي كيفية الوصول إلى تسميات البيانات وتشغيل أسماء الفئات وتعيين الموضع.
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

// إضافة مخطط خطي وتعيين نطاق بيانات السلسلة وتعيين نطاق بيانات الفئة
int Index =sheet.Charts.Add(ChartType.Line, 6, 0, 19, 5);
مخطط الرسم البياني = Sheet.Charts[index];
Chart.NSeries.Add("B2:B5"، صحيح)؛
Chart.NSeries.CategoryData = "A2:A5";

//الخطوة السابقة:1-
// انقل وسيلة الإيضاح إلى الأسفل وقم بتعيين لون خط وسيلة الإيضاح
Chart.Legend.Font.Color = Color.Blue;
Chart.Legend.Position = LegendPositionType.Bottom;

// اكسستيب:2-
// الوصول إلى تسميات البيانات وتشغيل أسماء الفئات وتعيين الموضع
DataLabels dataLabels = Chart.NSeries[0].DataLabels;
dataLabels.ShowCategoryName = true;
dataLabels.Position = LabelPositionType.Center;

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