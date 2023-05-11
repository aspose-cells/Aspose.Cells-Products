---
title: أدخل التعليقات في Excel via .NET
description:  C# أكواد المصدر التي كيفية إدراج التعليق في Microsoft ملفات Excel باستخدام .NET Library.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft <sup> & reg؛ </sup> إدراج تعليقات Excel via .NET" h2="قم بإنشاء مستندات Excel وأدخل التعليقات باستخدام واجهات برمجة التطبيقات من جانب الخادم في التطبيقات المستندة إلى .NET." >}}
{{% blocks/products/pf/feature-page-summary %}}

 يمكنك إضافة تعليقات إلى الخلايا. عندما تحتوي الخلية على تعليق ، يظهر مؤشر في زاوية الخلية. تظهر التعليقات عند تحريك المؤشر فوق إحدى الخلايا ، ويمكن استخدام هذه التعليقات للمناقشة أو للحصول على إرشادات خاصة أو لتمييز محتوى المستند.[.NET مكتبة Excel](/cells/ar/net/)يدعم إدراج التعليقات في ملفات Excel. لهذا ، يوفر API ملف[تعليق](https://reference.aspose.com/cells/net/aspose.cells/comment) فئة لبناء التعليقات.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="أدخل التعليقات في ملف Excel" %}}

 يعد إدخال التعليقات باستخدام Excel API أمرًا بسيطًا. العملية هي إنشاء[فئة المصنف](https://reference.aspose.com/cells/net/aspose.cells/workbook) الكائن وحدد ورقة العمل الأولى أو الورقة ذات الصلة من خلال توفير فهرسها. أدخل بيانات الخلايا المطلوبة باستخدام[طريقة PutValue](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index) . أضف تعليقًا إلى ورقة العمل باستخدام[جمع التعليقات](https://reference.aspose.com/cells/net/aspose.cells/commentcollection) 'س[طريقة الإضافة](https://reference.aspose.com/cells/net/aspose.cells.commentcollection/add/methods/1).

{{% blocks/products/pf/feature-page-code h3="C# كود لإدراج تعليق في Excel" %}}

{{< gist "aspose-cells-gists" "59a1901d62ea9ceb08456a818431a898" "InsertCommentIntoWorksheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
