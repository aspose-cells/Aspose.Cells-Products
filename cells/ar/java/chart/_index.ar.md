---
title: إنشاء مخططات Excel وتحويلها إلى صور عبر Java

description: Java شفرة المصدر لرسم وتحويل مخطط أو رسم تخطيطي في Microsoft Excel باستخدام Java Library. 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft <sup> & reg؛ </sup> تحويل وإنشاء مخططات ملف Excel عبر Java" h2="قم بتحويل مخططات مستندات Excel إلى صور بالإضافة إلى إنشاء مخططات متنوعة باستخدام واجهات برمجة التطبيقات من جانب الخادم داخل التطبيقات المستندة إلى Java." >}}


{{% blocks/products/pf/feature-page-summary %}}

يُظهر تحليل البيانات عبر الرسوم البيانية الصورة الأكبر ومن السهل اتخاذ قرارات أكثر استنارة برؤى أوضح. [Java مكتبة Excel](/cells/java/) يدعم رسم إنشاء مخطط مختلف مدرج بواسطة [نوع التخطيط](https://reference.aspose.com/cells/java/com.aspose.cells/ChartType) بما في ذلك المخططات الدائرية والهرمية والخطية والفقاعية. علاوة على ذلك ، فإنه يحول المخططات إلى صور. API يوفر ملف [فئة الرسوم البيانية](https://reference.aspose.com/cells/java/com.aspose.cells/Chart) لتمثيل مخطط Excel واحد.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="تحويل مخططات Excel إلى صور" %}}

عملية تحويل المخططات إلى صور بما في ذلك JPG و PNG و TIFF و BMP وما إلى ذلك هي استخدام [دفتر العمل](https://reference.aspose.com/java/cells/com.aspose.cells/workbook) فئة لتحميل ملف Excel ، حدد ملف [مجموعة العمل](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet) تحتوي على المخططات أو تكرارها من خلال كل مخطط في كل ورقة عمل. حدد [خيارات ImageOrPrintOptions](https://reference.aspose.com/cells/java/com.aspose.cells/ImageOrPrintOptions) وتقديم صورة الإخراج للمخطط باستخدام [Chart.toImage](https://reference.aspose.com/cells/java/com.aspose.cells/chart#toImage(java.io.OutputStream,%20com.aspose.cells.ImageOrPrintOptions)).


{{% blocks/products/pf/feature-page-code h3="Java رمز لتحويل مخطط Excel إلى صورة" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "render-excel-chart-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}


{{% blocks/products/pf/feature-page-section h2="قم بإنشاء مخططات داخل ملف Excel" %}}

يعد إنشاء المخططات باستخدام Excel API أمرًا بسيطًا ، حيث يوفر API مجموعة من الفئات المختلفة مثل Axis و Chart و ChartArea و ChartDataTable و ChartFrame و ChartPoint و ChartPointCollection و ChartCollection وما إلى ذلك لأنواع مختلفة من المخططات. العملية هي ، إنشاء كائن فئة مصنف وحدد ورقة العمل الأولى أو الورقة ذات الصلة من خلال توفير الفهرس الخاص بها. لمصدر بيانات المخطط ، قم بإدراج القيم في خلايا ورقة العمل باستخدام [setValue](https://reference.aspose.com/cells/java/com.aspose.cells/cell#Value) طريقة. استخدم مجموعة ChartCollection [طريقة الإضافة](https://reference.aspose.com/cells/java/com.aspose.cells/chartcollection#add(int,%20int,%20int,%20int,%20int)) لإضافة المخطط ، حدد نوع المخطط باستخدام تعداد ChartType. قم بالوصول إلى كائن المخطط الجديد من مجموعة ChartCollection بتمرير الفهرس الخاص به. استخدم ال [السلسلة](https://reference.aspose.com/cells/java/com.aspose.cells/SeriesCollection) رسم بياني لتحديد مصدر بيانات المخطط.

{{% blocks/products/pf/feature-page-code h3="Java رمز لإنشاء مخططات Excel" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "create-excel-chart-pyramid.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
