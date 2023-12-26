---
title: قم بتقسيم جدول بيانات Excel إلى أوراق عمل في Java
description: Java كود مصدري يشرح كيفية تقسيم ملفات Microsoft Excel إلى مستندات متعددة باستخدام مكتبة Java Excel
keywords: [Java Aspose.Cells., Java split excel files., Java how to split excel files into multiple files., Java excel splitter., Java split Cell., Cell splitter using Java]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> تقسيم ملفات اكسيل via Java" h2="قم بتقسيم جدول بيانات Excel إلى أوراق عمل ضمن التطبيقات المستندة إلى Java" >}}
{{% blocks/products/pf/feature-page-summary %}}
هناك مجموعة متنوعة من السيناريوهات، عندما تكون هناك حاجة لتقسيم ملفات Excel مثل جدول بيانات يحتوي على بيانات الطلاب مع تخصيص ورقة واحدة لكل طالب. وهناك حاجة لتقسيم كل ورقة للطالب كملف منفصل. لأتمتة ذلك تطبيق via Java،[Java اكسل API](/cells/ar/java/) هناك لتقسيم مستند Excel على الورق. تشمل التنسيقات المدعومة XLS، XLSX، XLSB، XLSM، ODS.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="تقسيم مستند Excel إلى ملفات متعددة" %}}

 إن أبسط طريقة لتقسيم ملف Excel إلى ورقة هي الوصول إلى جميع الأوراق والتكرار خلال كل ورقة وحفظها واحدة تلو الأخرى بالتنسيق المطلوب. لتحميل ورقة العمل يوفر API[دفتر العمل](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) فصل.[getWorksheets().getCount()](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#Count) الطريقة تحصل على العدد الإجمالي للأوراق. كرر من خلال كل ورقة واستخدمها[getWorksheets().get(sheetindex)](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#get) للوصول إلى ورقة محددة. انقل بيانات الورقة المحددة إلى كائن فئة المصنف الذي تم إنشاؤه حديثًا باستخدام[طريقة النسخ](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#copy(com.aspose.cells.Workbook)). وأخيراً احفظه بالتنسيق المطلوب.

{{% blocks/products/pf/feature-page-code h3="Java كود لتقسيم ملفات الاكسل" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-xls-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="تقسيم ورقة عمل Excel إلى أجزاء" %}}

API يوفر أيضًا وظيفة تقسيم ورقة عمل Excel إلى أجزاء مختلفة. العملية هي تحميل الملف باستخدام فئة المصنف. قم باختيار ورقة العمل الأولى أو أي ورقة مطلوبة من خلال توفير الفهرس الخاص بها. اتصل بـ setActiveCell الذي يحتوي على فهرس الخلايا ذي الصلة كمعلمة. وأخيرًا، قم بتقسيم نافذة ورقة العمل إلى أجزاء مختلفة عن طريق استدعاء طريقة Split().

{{% blocks/products/pf/feature-page-code h3="Java كود لتقسيم ورقة Excel إلى عرض جزء" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-excel-spreadsheet-into-panes.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
