---
title: كيفية إضافة TextBox عبر Aspose.Cells
weight: 7700
limit:
description: تعرف على كيفية إضافة TextBox.
keywords: [Add TextBox., how to add TextBox in Aspose.Cells., how to add TextBox using Aspose.Cells]
url: /ar/tutorial/add-textbox-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="تعرف على كيفية إضافة TextBox مع Aspose.Cells" >}}

<p>
في هذا البرنامج التعليمي، سنقوم بإضافة TextBox في ملف Excel.
</p>

<p>
 سنبدأ بإنشاء مصنف جديد باستخدام<a href="https://www.nuget.org/packages/Aspose.Cells">مكتبة Aspose.Cells</a> وأضف TextBox.
</p>

<br />
{{< app/cells/tutorial >}}
// ExSummary: يرجى التحقق من الكود التالي لمعرفة كيفية إضافة TextBox.
//ExStepSummary:0: يوضح الكود التالي كيفية إضافة TextBox وتعيين النص.
//ExStepImage:0:step-1.png
//ExStepSummary:1: يوضح الكود التالي كيفية تغيير لون النص.
//ExStepImage:1:step-2.png
//ExStepSummary:2: يوضح الكود التالي كيفية تغيير زاوية دوران TextBox.
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

// أضف TextBox وقم بتعيين النص
TextBox textBox = Shapes.AddTextBox(1, 0, 1, 0, 200, 200);
textBox.Text = "Aspose.Cells for .NET هي مكتبة فئة برمجة تسمح لمطوري البرامج بمعالجة ملفات جداول البيانات ومعالجتها داخل تطبيقاتهم الخاصة.";

//الخطوة السابقة:1-
// تغيير لون النص
textBox.Font.Color = Color.Blue;

// اكسستيب:2-
// تغيير زاوية دوران TextBox
textBox.RotationAngle = 90;

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