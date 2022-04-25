---
title: أدخل التعليقات في Excel عبر .NET
url: /ar/net/comment/
description: C# رموز المصدر التي توضح كيفية إدراج تعليق في ملفات Microsoft Excel باستخدام .NET المكتبة. 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="إدراج تعليقات Microsoft <sup> & reg؛ </sup> Excel عبر .NET" h2="أنشئ مستندات Excel وأدخل التعليقات باستخدام واجهات برمجة التطبيقات من جانب الخادم في التطبيقات المستندة إلى .NET." >}}
{{% blocks/products/pf/feature-page-summary %}}

يمكنك إضافة تعليقات إلى الخلايا. عندما تحتوي الخلية على تعليق ، يظهر مؤشر في زاوية الخلية. تظهر التعليقات عندما تقوم بتمرير المؤشر فوق إحدى الخلايا ، ويمكن استخدام هذه التعليقات للمناقشة أو للحصول على إرشادات خاصة أو لتمييز محتوى المستند. [.NET مكتبة Excel](/cells/net/) يدعم إدراج التعليقات في ملفات Excel. لهذا ، يوفر API ملف [تعليق](https://apireference.aspose.com/cells/net/aspose.cells/comment) فئة لبناء التعليقات.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="أدخل التعليقات في ملف Excel" %}}

يعد إدراج التعليقات باستخدام Excel API أمرًا بسيطًا. العملية هي إنشاء [فئة المصنف](https://apireference.aspose.com/cells/net/aspose.cells/workbook) الكائن وحدد ورقة العمل الأولى أو الورقة ذات الصلة من خلال توفير فهرسها. أدخل بيانات الخلايا المطلوبة باستخدام [طريقة PutValue](https://apireference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index). أضف تعليقًا إلى ورقة العمل باستخدام [جمع التعليقات](https://apireference.aspose.com/cells/net/aspose.cells/commentcollection)'س [طريقة الإضافة](https://apireference.aspose.com/cells/net/aspose.cells.commentcollection/add/methods/1).

{{% blocks/products/pf/feature-page-code h3="C# رمز لإدراج تعليق في Excel" %}}

{{< gist "aspose-cells-gists" "88c9872508ec3150c552eb5155edf06e" "InsertCommentIntoWorksheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
