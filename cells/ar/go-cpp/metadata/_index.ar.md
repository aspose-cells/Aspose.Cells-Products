---
title: إدارة بيانات تعريف ملفات Excel باستخدام Go عبر الرقم C++
description: يمكنك عرض بيانات تعريف ملفات Excel وإضافتها وتعديلها وإزالتها واستخراجها باستخدام مكتبة Go عبر C++
keywords: [Go via C++ Aspose.Cells., Go via C++ view excel metadata., Go via C++ add excel metadata., Go via C++ insert excel metadata., Go via C++ edit excel metadata., Go via C++ remove excel metadata., Go via C++ extract excel metadata., Go via C++ modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="إدارة بيانات تعريف مستند Excel عبر Go من خلال C++" h2="عرض أو إدراج أو تحديث أو إزالة أو استخراج خصائص مستندات Excel المخصصة والمدمجة ضمن تطبيقات C++." >}}
{{% blocks/products/pf/feature-page-summary %}}
 البيانات الوصفية في برنامج Excel - كيفية عرض وإدراج وإزالة البيانات الوصفية لملفات Excel.[انتقل إلى مكتبة إكسل عبر الرقم C++](/cells/ar/go-cpp/)يُسهّل برنامج faclitates العملية من خلال دعم الخصائص المدمجة/المُعرّفة من قِبل النظام، مثل اسم المؤلف، والعنوان، وإحصائيات المستند، وغيرها من الخصائص التي قد تكون ضرورية أحيانًا للتحقق من تاريخ آخر تعديل أو حفظ للملف، بالإضافة إلى الخصائص المُخصصة/المُعرّفة من قِبل المستخدم على شكل أزواج اسم/قيمة. ولأتمتة العملية، تدعم المكتبة إنشاء ملفات بيانات وصفية كبيرة الحجم في Excel وصيانتها.[دفتر العمل](https://reference.aspose.com/cells/go-cpp/workbook/) يفتح هذا الصنف مصنفًا باستخدام المسار، أو التدفق، أو نوع تنسيق الملف المحدد. لذا، حمّل الملف بالطريقة المناسبة لمزيد من المعالجة. بعض الاحتمالات مذكورة أدناه، ويمكن للمطورين بسهولة تحسين التعليمات البرمجية الخاصة بهم وفقًا لمتطلبات التطبيق.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="قراءة وتحديث الخصائص المدمجة" %}}

 لأتمتة الخصائص المدمجة، يوفر الرقم API[GetBuiltInDocumentProperties()](https://reference.aspose.com/cells/go-cpp/workbook/getbuiltindocumentproperties/)دالة تُعيد مجموعة DocumentProperties التي تُمثل جميع خصائص المستند المُضمنة في جدول البيانات. بعد الوصول إلى جميع الخصائص المُضمنة، يُمكن الوصول إلى الخصائص ذات الصلة باستخدام الدوال المُناسبة مثل GetTitle() وGetSubject()، إلخ. لتحديث الخصائص، تُوفر الدالة API دوالًا مثل SetTitle وSetSubject وSetAuthor وSetComments، إلخ.[مجموعة خصائص المستندات المدمجة](https://reference.aspose.com/cells/go-cpp/workbook/getbuiltindocumentproperties/) للوظيفة المطلوبة.

{{% blocks/products/pf/feature-page-code h3="استخدم الرمز C++ لقراءة خصائص النظام المعرفة" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "read-system-defined-properties.go" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="استخدم الرمز C++ لتحديث الخصائص المدمجة" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "update-built-in-properties.go" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="عرض وإضافة خصائص مُعرَّفة حسب الطلب" %}}

 فيما يتعلق بمعالجة الخصائص المخصصة، يوفر الرقم API[Workbook::GetCustomDocumentProperties](https://reference.aspose.com/cells/go-cpp/workbook/getcustomdocumentproperties/)تُعيد هذه الدالة جميع خصائص المستند المخصصة لجدول البيانات. عند الوصول إلى هذه الخصائص، يمكن للمطورين استخدام الدوال المناسبة لإضافة خصائص، مثل AddIDocumentProperty وAddLinkToContentProperty، وبالمثل، يمكن استخدام UpdateLinkedPropertyValue وUpdateLinkedRange لتحديث قيمة خاصية المستند المخصصة التي ترتبط بالمحتوى والنطاق المرتبط على التوالي. يمكن للمطورين استخدام الدوال المناسبة من[مجموعة من خصائص المستندات المخصصة](https://reference.aspose.com/cells/go-cpp/workbook/getcustomdocumentproperties/).

{{% blocks/products/pf/feature-page-code h3="استخدم الرمز C++ لعرض الخصائص المخصصة" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "view-custom-properties.go" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="استخدم الرمز C++ لإضافة البيانات الوصفية في ملف إكسل" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "add-custom-property.go" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< /blocks/products/pf/feature-page-wrap >}}