---
title: إنشاء مخططات Excel وتحويلها إلى صور via .NET
description:  C# الكود المصدري لرسم وتحويل الرسم البياني أو الرسم التخطيطي في Microsoft Excel باستخدام مكتبة .NET.
keywords: [C# Aspose.Cells., c# Convert chart to image., c# Save chart to image., c# chart to image., create charts in c#., insert charts in c#., manage charts in c#]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> إنشاء وتحويل مخططات ملفات Excel via .NET" h2="قم بإنشاء مخططات مستندات Excel وتحويلها إلى صور باستخدام واجهات برمجة التطبيقات من جانب الخادم ضمن التطبيقات المستندة إلى .NET." >}}
{{% blocks/products/pf/feature-page-summary %}}
 يعد رسم المخططات فنًا لعرض البيانات بيانيًا لتسهيل تحليلها.[.NET مكتبة اكسيل](/cells/ar/net/) يدعم رسم المخططات داخل ملفات Excel. API يدعم إنشاء المخططات المختلفة المدرجة في[تعداد نوع الرسم البياني](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype) بما في ذلك المخططات الدائرية والهرمية والخطية والفقاعية. علاوة على ذلك، فهو يقوم أيضًا بتحويل المخططات إلى صور. API يوفر أ[فئة الرسوم البيانية](https://reference.aspose.com/cells/net/aspose.cells.charts) لبنات بناء الرسم البياني.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="إنشاء الرسوم البيانية داخل ملف Excel" %}}

 يعد إنشاء المخططات باستخدام Excel API أمرًا بسيطًا. العملية هي إنشاء[فئة المصنف](https://reference.aspose.com/cells/net/aspose.cells/workbook)كائن وحدد ورقة العمل الأولى أو الورقة ذات الصلة من خلال توفير الفهرس الخاص بها. أدخل بيانات الخلايا المطلوبة باستخدام[طريقة وضع القيمة](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index) . أضف مخططًا إلى ورقة العمل باستخدام مجموعة المخططات[أضف طريقة](https://reference.aspose.com/cells/net/aspose.cells.charts/chartcollection/methods/add) . حدد ال[نوع التخطيط](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype) من تعداد ChartType.
{{% blocks/products/pf/feature-page-code h3="C# كود لإنشاء مخططات Excel" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "create-excel-chart.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section h2="تحويل مخططات Excel إلى صور" %}}

 عملية تحويل المخططات إلى صور هي استخدام فئة المصنف لتحميل ملف Excel، وتحديد ورقة العمل ذات الصلة التي تحتوي على المخططات واستدعاء[طريقة ToImage](https://reference.aspose.com/cells/net/aspose.cells.charts.chart/toimage/methods/7) للتحويل.

{{% blocks/products/pf/feature-page-code h3="C# كود تحويل مخطط Excel إلى صورة" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "convert-xlsx-file-chart-to-images.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}
