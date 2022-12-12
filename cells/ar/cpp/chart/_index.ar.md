---
title: إنشاء مخططات Excel وتحويلها إلى صور عبر C++

description: C++ شفرة المصدر لرسم وتحويل مخطط أو رسم تخطيطي في Microsoft Excel باستخدام C++ Library
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="قم بإنشاء Microsoft <sup> & reg؛ </sup> مخططات Excel وتحويلها إلى صور عبر C++" h2="قم بتحويل مخططات مستندات Excel إلى صور بالإضافة إلى إنشاء مخططات بما في ذلك المخططات الدائرية والهرمية والخطية والفقاعية داخل التطبيقات المستندة إلى C++." >}}

{{% blocks/products/pf/feature-page-summary %}}

باستخدام مخططات Excel ، يمكن للمرء الحصول على صورة أكبر وتحليل البيانات بسهولة لاتخاذ القرارات الصحيحة. [C++ مكتبة Excel](/cells/cpp/) يدعم إنشاء مخططات مختلفة مدرجة بواسطة [تعداد Aspose :: Cells :: Charts :: ChartType
](https://reference.aspose.com/cells/cpp/namespace/aspose.cells.charts#a2f17e69bcefc754569019185d0621b70) بما في ذلك المخططات المساحية والشريطية والدائرية والهرمية والخطية والفقاعية. علاوة على ذلك ، لتحويل المخططات إلى صور ، يوفر API تنسيق [ToImage mehtod](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_sparkline#a28d76dd585c48366e1657f2982722ddb) في تنسيق الصورة المطلوب.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="إنشاء مخططات Excel" %}}

عملية إنشاء مخطط Excel هي إنشاء مثيل لـ [فئة IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) وحدد الملف المطلوب [ورقة عمل](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet_collection#a5574d624796043233420d0e0459ccc43). أضف الرسم البياني باستخدام [طريقة الإضافة](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_chart_collection#ab7e8cce835c251a4682605299a6aa068) مع المعلمات ذات الصلة بما في ذلك نوع الرسم البياني. الوصول إلى الرسم البياني عبر الفهرس و [يضيف](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_series_collection#a8f4dc4d883f32f65b1fb673e2aa7862f) مصدر البيانات للرسم البياني.

{{% blocks/products/pf/feature-page-code h3="C++ رمز لإنشاء مخططات Excel" %}}

{{< gist "aspose-com-gists" "da2fd423617bf9013a7673870c81d708" "create-excel-chart.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="تحويل المخططات إلى صور" %}}


لتحويل عملية الرسوم البيانية ، قم أولاً بإنشاء مخطط من النوع ذي الصلة باستخدام الكود أعلاه أو الوصول إليه من الورقة ذات الصلة. حدد مسار حفظ الإخراج للصورة واستخدم طريقة ToImage للتحويل.

 
{{% blocks/products/pf/feature-page-code h3="C++ رمز لتحويل مخططات Excel" %}}

{{< gist "aspose-com-gists" "da2fd423617bf9013a7673870c81d708" "convert-excel-chart-to-image.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}
