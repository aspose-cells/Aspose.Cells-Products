---
title: قسّم جدول بيانات Excel إلى أوراق عمل في Java
description: Java أكواد المصدر التي توضح كيفية تقسيم Microsoft ملفات Excel إلى مستندات متعددة باستخدام مكتبة Excel Java
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft <sup> & reg؛ </sup> تقسيم ملف Excel via Java" h2="قسّم جدول بيانات Excel إلى أوراق عمل ضمن تطبيقات تستند إلى Java" >}}
{{% blocks/products/pf/feature-page-summary %}}
 هناك مجموعة متنوعة من السيناريوهات ، عندما تكون هناك حاجة لتقسيم ملفات Excel مثل جدول بيانات يحتوي على بيانات الطلاب مع تخصيص ورقة واحدة لكل طالب. وهناك حاجة لتقسيم كل ورقة بحكمة الطالب كملف منفصل. لأتمتة تطبيق via Java ،[Java إكسل API](/cells/ar/java/) هناك لتقسيم وثيقة إكسل ورقة. تتضمن التنسيقات المدعومة XLS ، XLSX ، XLSB ، XLSM ، ODS.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="قم بتقسيم مستند Excel إلى ملفات متعددة" %}}

إن أبسط طريقة لتقسيم ملف Excel إلى ورقة هي ، الوصول إلى جميع الأوراق ، والتكرار خلال كل ورقة وحفظ واحدة تلو الأخرى بالتنسيق المطلوب. لتحميل ورقة العمل ، يوفر API[دفتر العمل](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) فصل.[getWorksheets (). getCount ()](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#Count) طريقة الحصول على العدد الإجمالي للأوراق. كرر خلال كل ورقة واستخدمها[getWorksheets (). get (sheetindex)](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#get) للوصول إلى ورقة محددة. انقل بيانات الورقة المحددة إلى كائن فئة مصنف تم إنشاؤه حديثًا باستخدام[طريقة النسخ](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#copy(com.aspose.cells.Workbook)). أخيرًا احفظه بالتنسيق المطلوب.

{{% blocks/products/pf/feature-page-code h3="Java كود لتقسيم ملفات Excel" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-xls-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="قسّم ورقة عمل Excel إلى أجزاء" %}}

يوفر API أيضًا وظيفة تقسيم ورقة عمل Excel إلى أجزاء مختلفة. العملية هي تحميل الملف باستخدام فئة المصنف. حدد ورقة العمل الأولى أو أي ورقة مطلوبة من خلال توفير الفهرس الخاص بها. قم باستدعاء setActiveCell الذي يحتوي على فهرس الخلية ذي الصلة كمعامل. وأخيراً قسّم نافذة ورقة العمل إلى أجزاء مختلفة عن طريق استدعاء طريقة Split ().

{{% blocks/products/pf/feature-page-code h3="Java كود لتقسيم ورقة إكسل إلى طريقة عرض جزئية" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-excel-spreadsheet-into-panes.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
