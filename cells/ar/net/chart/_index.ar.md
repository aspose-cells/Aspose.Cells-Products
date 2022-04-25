---
title: إنشاء مخططات Excel والتحويل إلى صور عبر .NET
url: /ar/net/chart/
description: C# شفرة المصدر لرسم وتحويل مخطط أو رسم تخطيطي في Microsoft Excel باستخدام .NET Library. 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft <sup> & reg؛ </sup> إنشاء وتحويل مخططات ملف Excel عبر .NET" h2="قم بإنشاء مخططات مستندات Excel وتحويلها إلى صور باستخدام واجهات برمجة التطبيقات من جانب الخادم داخل التطبيقات المستندة إلى .NET." >}}
{{% blocks/products/pf/feature-page-summary %}}
رسم المخططات هو فن لعرض البيانات بيانياً لتحليلها بسهولة. [.NET مكتبة Excel](/cells/net/) يدعم رسم المخططات داخل ملفات Excel. API يدعم إنشاء المخططات المختلفة المدرجة في [تعداد نوع المخطط](https://apireference.aspose.com/cells/net/aspose.cells.charts/charttype) بما في ذلك المخططات الدائرية والهرمية والخطية والفقاعية. علاوة على ذلك ، فإنه يحول المخططات إلى صور. API يوفر ملف [فئة الرسوم البيانية](https://apireference.aspose.com/cells/net/aspose.cells.charts) لبنات بناء الرسم البياني.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="قم بإنشاء مخططات داخل ملف Excel" %}}

يعد إنشاء المخططات باستخدام Excel API أمرًا بسيطًا. العملية هي إنشاء [فئة المصنف](https://apireference.aspose.com/cells/net/aspose.cells/workbook) الكائن وحدد ورقة العمل الأولى أو الورقة ذات الصلة من خلال توفير فهرسها. أدخل بيانات الخلايا المطلوبة باستخدام [طريقة PutValue](https://apireference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index). أضف مخططًا إلى ورقة العمل باستخدام مجموعة المخططات [طريقة الإضافة](https://apireference.aspose.com/cells/net/aspose.cells.charts/chartcollection/methods/add). حدد ال [نوع التخطيط](https://apireference.aspose.com/cells/net/aspose.cells.charts/charttype) من تعداد ChartType.
{{% blocks/products/pf/feature-page-code h3="C# رمز لإنشاء مخططات Excel" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "create-excel-chart.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section h2="تحويل مخططات Excel إلى صور" %}}

عملية تحويل المخططات إلى صور هي ، استخدم فئة المصنف لتحميل ملف Excel ، وحدد مجموعة العمل ذات الصلة التي تحتوي على المخططات واستدعاء [طريقة ToImage](https://apireference.aspose.com/cells/net/aspose.cells.charts.chart/toimage/methods/7) للتحويل.

{{% blocks/products/pf/feature-page-code h3="C# رمز لتحويل مخطط Excel إلى صورة" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "convert-xlsx-file-chart-to-images.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}