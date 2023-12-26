---
title: إنشاء مخططات Excel وتحويلها إلى صور via Java
description:  Java الكود المصدري لرسم وتحويل الرسم البياني أو الرسم التخطيطي في Microsoft Excel باستخدام مكتبة Java.
keywords: [Java Aspose.Cells., Java Convert chart to image., Java Save chart to image., Java chart to image., create charts in Java., insert charts in Java., manage charts in Java]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> تحويل وإنشاء مخططات ملفات Excel via Java" h2="قم بتحويل مخططات مستندات Excel إلى صور بالإضافة إلى إنشاء مخططات متنوعة باستخدام واجهات برمجة التطبيقات من جانب الخادم ضمن التطبيقات المستندة إلى Java." >}}


{{% blocks/products/pf/feature-page-summary %}}

 يُظهر تحليل البيانات عبر الرسوم البيانية الصورة الأكبر ومن السهل اتخاذ قرارات أكثر استنارة مع رؤى أكثر وضوحًا.[Java مكتبة اكسيل](/cells/ar/java/) يدعم رسم إنشاء مخططات مختلفة مدرجة بواسطة[نوع التخطيط](https://reference.aspose.com/cells/java/com.aspose.cells/ChartType) بما في ذلك المخططات الدائرية والهرمية والخطية والفقاعية. علاوة على ذلك، فهو يقوم أيضًا بتحويل المخططات إلى صور. API يوفر أ[فئة الرسوم البيانية](https://reference.aspose.com/cells/java/com.aspose.cells/Chart) لتمثيل مخطط Excel واحد.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="تحويل مخططات Excel إلى صور" %}}

 عملية تحويل المخططات إلى صور بما في ذلك JPG، PNG، TIFF، BMP الخ، استخدم[دفتر العمل](https://reference.aspose.com/java/cells/com.aspose.cells/workbook) فئة لتحميل ملف Excel، حدد ذات الصلة[com.workset](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet) تحتوي على المخططات أو قم بالتكرار خلال كل مخطط في كل ورقة عمل. يُعرِّف[خيارات الصورة أو الطباعة](https://reference.aspose.com/cells/java/com.aspose.cells/ImageOrPrintOptions) وتقديم صورة الإخراج للمخطط باستخدام[Chart.toImage](https://reference.aspose.com/cells/java/com.aspose.cells/chart#toImage(java.io.OutputStream,%20com.aspose.cells.ImageOrPrintOptions)).


{{% blocks/products/pf/feature-page-code h3="Java كود تحويل مخطط Excel إلى صورة" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "render-excel-chart-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}


{{% blocks/products/pf/feature-page-section h2="إنشاء الرسوم البيانية داخل ملف Excel" %}}

يعد إنشاء المخططات باستخدام Excel API أمرًا بسيطًا، حيث يوفر API مجموعة من الفئات المختلفة مثل Axis وChart وChartArea وChartDataTable وChartFrame وChartPoint وChartPointCollection وChartCollection وما إلى ذلك لأنواع مختلفة من المخططات. العملية هي إنشاء كائن فئة المصنف وتحديد ورقة العمل الأولى أو الورقة ذات الصلة من خلال توفير الفهرس الخاص بها. بالنسبة لمصدر بيانات المخطط، قم بإدراج القيم في خلايا ورقة العمل باستخدام[setValue](https://reference.aspose.com/cells/java/com.aspose.cells/cell#Value) طريقة. استخدم مجموعة ChartCollection[إضافة طريقة](https://reference.aspose.com/cells/java/com.aspose.cells/chartcollection#add(int,%20int,%20int,%20int,%20int) ) لإضافة المخطط، حدد نوع المخطط باستخدام تعداد ChartType. قم بالوصول إلى كائن المخطط الجديد من مجموعة ChartCollection عن طريق تمرير الفهرس الخاص به. استخدم ال[مجموعة السلسلة](https://reference.aspose.com/cells/java/com.aspose.cells/SeriesCollection) كائن التخطيط لتحديد مصدر بيانات المخطط.

{{% blocks/products/pf/feature-page-code h3="Java كود لإنشاء مخططات Excel" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "create-excel-chart-pyramid.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
