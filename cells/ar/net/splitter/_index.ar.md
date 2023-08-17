---
title: قم بتقسيم ورقة عمل Excel بحكمة في C#
description: C# أكواد المصدر التي تشرح كيفية تقسيم Microsoft ملفات Excel إلى ملفات متعددة في تطبيقات المرئية C#.NET
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft <sup> & reg؛ </sup> تقسيم ملف Excel via .NET" h2="قم بتقسيم مستند Excel الفردي إلى ملفات مختلفة باستخدام كود C# ضمن التطبيقات القائمة على .NET" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET مكتبة Excel](/cells/ar/net/) قادر على تقسيم مستند Excel إلى جداول بيانات متعددة ضمن تطبيقات تستند إلى .NET. تتضمن تنسيقات الملفات المدعومة XLS ، XLSX ، XLSB ، XLSM ، ODS.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="قم بتقسيم مستند Excel إلى ملفات متعددة" %}}
 إن أبسط طريقة لتقسيم ورقة ملفات Excel هي الوصول إلى جميع الأوراق عبر[أوراق عمل](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/worksheets) ، التكرار خلال كل ورقة واستدعاء[ينسخ](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy) طريقة. أخيرًا حفظه في مسار محدد.

 + قم بتحميل ملف Excel بالمسار الكامل باستخدام[فئة المصنف](https://reference.aspose.com/cells/net/aspose.cells/workbook).
+ كرر من خلال كل ورقة
+ إنشاء كائن فئة مصنف جديد
 + انسخ الورقة عبر[طريقة النسخ](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy)
+ استدعاء طريقة Save () ومرر اسم الملف (المسار الكامل) مع SaveFormat ذات الصلة.

{{% blocks/products/pf/feature-page-code h3="C# كود لتقسيم ملفات Excel" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="قسّم ورقة عمل Excel إلى أجزاء" %}}

 لتقسيم نافذة ورقة العمل إلى أجزاء ، يوفر API[طريقة التقسيم](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/split)فئة ورقة العمل ، التي توفر طريقة عرض مقسمة لورقة العمل. لإزالة عرض منقسم يوفر API[طريقة RemoveSplit](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/removesplit) . أخيرًا احفظه في مسار محدد.

{{% blocks/products/pf/feature-page-code h3="C# كود لتقسيم نافذة ورقة عمل Excel" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet-into-pane.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C# كود لإزالة تقسيم عرض عموم" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "remove-splitted-spreadsheet-pane-view.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
