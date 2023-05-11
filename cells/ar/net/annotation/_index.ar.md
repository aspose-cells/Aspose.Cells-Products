---
title: شروح ملف Excel NET C#
description: قم بإضافة تعليق توضيحي للبيانات أو إزالته من جداول بيانات Excel و OpenOffice باستخدام سطور قليلة فقط من كود C#.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="إزالة Microsoft <sup> & reg؛ </sup> تعليقات ملف Excel التوضيحية via .NET" h2="قم بإضافة أو حذف التعليقات التوضيحية لملفات Excel باستخدام كود C# ضمن التطبيقات القائمة على .NET." >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET مكتبة Excel](/cells/ar/net/) يوفر الدعم لإدارة التعليقات التوضيحية على مستوى الخلية عن طريق إضافة التعليقات والوصول إليها وإزالتها. باستخدام التعليقات على مستوى الخلية ، يمكن تخزين المعلومات ذات الصلة للمستخدمين النهائيين. تتضمن تنسيقات الملفات المدعومة ODS و XLS و XLSX و XLSB و XLSM.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="شروح بيانات ملفات Excel" %}}
 إدارة التعليقات في أوراق العمل - لا يوجد حد لعدد التعليقات الموجودة على الورقة في MS Excel. يمكن للمرء أن يضيف الكثير من متطلبات التطبيق. سوف نستخدم ملف[فئة التعليق](https://reference.aspose.com/cells/net/aspose.cells/comment)لكل هذه الوظائف.

+ تحميل ملف Excel باستخدام كائن فئة المصنف
+ احصل على ورقة العمل ذات الصلة وفهرس Cell ذي الصلة
+ استدعاء RemoveAt مع Cell معرف لإزالته
 + استخدم[خاصية الملاحظة](https://reference.aspose.com/cells/net/aspose.cells/comment/properties/note) لإضافة محتوى التعليقات
+ احفظ المصنف قبل وبعد استدعاء طريقة RemoveAt للمقارنة

{{% blocks/products/pf/feature-page-code h3="C# رمز للوصول إلى ملفات Excel وإدراجها وحذفها Cell التعليقات" %}}


{{< gist "aspose-com-gists" "e3dcb9c341b81d4db3a404ca7cd6e4cf" "access-insert-and-delete-excel-files-cell-comments.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}
