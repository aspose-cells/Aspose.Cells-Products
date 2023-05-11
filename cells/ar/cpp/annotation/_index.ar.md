---
title: شروح ملف Excel عبر C++
description: قم بإضافة تعليقات توضيحية للبيانات أو إزالتها من جداول بيانات Excel و OpenOffice باستخدام مكتبة C++.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="إدارة Microsoft <sup> & reg؛ </sup> تعليقات ملف Excel التوضيحية عبر C++" h2="إضافة أو إزالة ملاحظات بسيطة للتعليق أو التعليقات داخل C++ التطبيقات القائمة." >}}
{{% blocks/products/pf/feature-page-summary %}}
[C++ إكسل API](/cells/ar/cpp/) يوفر الدعم لإدارة التعليقات التوضيحية على مستوى الخلية عن طريق إضافة التعليقات والوصول إليها وإزالتها. يوفر API[IComment](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment) و[ICommentCollection](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection) إلى جانب[GetIComments()](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ae7cce5f85b7b25a1e5c58df1b613ca5a)للتعامل مع التعليقات في جميع الجوانب. تتضمن تنسيقات Excel المدعومة ODS و XLS و XLSX و XLSB و XLSM.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="شروح بيانات ملفات Excel" %}}
 معالجة التعليقات في أوراق العمل - لا يقتصر الأمر على عدد التعليقات الموجودة على الورقة في MS Excel. يمكن للمرء أن يدرج قدر ما يحتاجه التطبيق. عملية إدراج التعليقات هي إنشاء[IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) كائن فئة لتحميل ملف موجود وتحديد ورقة العمل حيث تريد إضافة التعليق. احصل على جميع تعليقاته باستخدام getComments (). أضف التعليق باستخدام[يضيف](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection#a3f014415e292fa15c6220e9727dad384) (intrusive_ptr< Aspose::Cells::Systems::String > cellName). احصل على فهرس الخلية واستخدمه[تعيين](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment#a791b9d4e9bf3975709a7f93b5db09580) لإدخال التعليقات. علاوة على ذلك ، API قادر على إزالة كافة التعليقات. قليل من الأساليب[ClearComments()](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ad4e0ea291ae60fc1b5d815e520edc6c3) لمسح جميع التعليقات في جدول بيانات المصمم. علاوة على ذلك،[RemoveAt](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet_collection#addabcc7d7d76874694018fb3ba37b72c)(intrusive_ptr< Aspose::Cells::Systems::String > name) لإزالة العنصر في فهرس محدد أو باسم محدد.

{{% blocks/products/pf/feature-page-code h3="C++ كود لإضافة تعليقات داخل ملف إكسيل" %}}

{{< gist "aspose-com-gists" "e144512d2c395c3336f12ce960424686" "add-comment-in-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}
