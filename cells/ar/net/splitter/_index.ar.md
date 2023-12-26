---
title: تقسيم ورقة عمل Excel في C#
description: C# الكود المصدري الذي يشرح كيفية تقسيم Microsoft ملفات Excel إلى ملفات متعددة في تطبيقات Visual C#.NET
keywords: [C# Aspose.Cells., C# split excel files., C# how to split excel files into multiple files., C# excel splitter., C# split Cell., Cell splitter using C#]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> تقسيم ملفات اكسيل via .NET" h2="قم بتقسيم مستند Excel واحد إلى ملفات مختلفة باستخدام رمز C# ضمن التطبيقات المستندة إلى .NET" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET مكتبة اكسيل](/cells/ar/net/) قادر على تقسيم مستند Excel إلى جداول بيانات متعددة ضمن التطبيقات المستندة إلى .NET. تشمل تنسيقات الملفات المدعومة XLS، XLSX، XLSB، XLSM، ODS.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="تقسيم مستند Excel إلى ملفات متعددة" %}}
إن أبسط طريقة لتقسيم ورقة ملفات Excel هي الوصول إلى جميع الأوراق عبر[أوراق عمل](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/worksheets) ، التكرار من خلال كل ورقة واستدعاء[ينسخ](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy) طريقة. وأخيرا حفظه في المسار المحدد.

 + قم بتحميل ملف Excel بالمسار الكامل باستخدام[فئة المصنف](https://reference.aspose.com/cells/net/aspose.cells/workbook).
+ كرر من خلال كل ورقة
+ إنشاء كائن فئة مصنف جديد
 + انسخ الورقة عبر[طريقة النسخ](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy)
+ استدعاء طريقة Save () وتمرير اسم الملف (المسار الكامل) الذي يحتوي على SaveFormat ذي الصلة.

{{% blocks/products/pf/feature-page-code h3="C# كود لتقسيم ملفات الاكسل" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="تقسيم ورقة عمل Excel إلى أجزاء" %}}

 لتقسيم نافذة ورقة العمل إلى أجزاء، يوفر API[طريقة التقسيم](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/split) لفئة ورقة العمل، التي توفر طريقة عرض مقسمة لورقة العمل. لإزالة العرض المقسم يوفر API[طريقة إزالة سبليت](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/removesplit) . وأخيراً احفظه في المسار المحدد.

{{% blocks/products/pf/feature-page-code h3="C# كود لتقسيم نافذة ورقة عمل Excel" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet-into-pane.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C# كود لإزالة العرض المقسم" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "remove-splitted-spreadsheet-pane-view.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
