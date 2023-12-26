---
title: إدارة بيانات تعريف ملف Excel عبر C++
description: عرض أو إضافة أو تعديل أو إزالة أو استخراج البيانات التعريفية لملفات Excel باستخدام مكتبة C++
keywords: [C++ Aspose.Cells., C++ view excel metadata., C++ add excel metadata., C++ insert excel metadata., C++ edit excel metadata., C++ remove excel metadata., C++ extract excel metadata., C++ modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="إدارة Microsoft<sup>&reg;</sup> بيانات تعريف مستند Excel عبر C++" h2="عرض أو إدراج أو تحديث أو إزالة أو استخراج خصائص مستند Excel المخصصة والمدمجة ضمن تطبيقات C++." >}}
{{% blocks/products/pf/feature-page-summary %}}
 البيانات التعريفية في Excel - كيفية عرض البيانات التعريفية لملف Excel وإدراجها وإزالتها.[C++ مكتبة اكسيل](/cells/ar/cpp/) يتم التسهيل بطريقة سهلة من خلال دعم الخصائص المضمنة / المحددة بواسطة النظام مثل اسم المؤلف والعنوان وإحصائيات المستند وما إلى ذلك اللازمة في وقت ما مثل التحقق من تعديل الملف أو حفظه أخيرًا مع الخصائص المخصصة / المحددة من قبل المستخدم في شكل أزواج الاسم/القيمة. لأتمتة العملية، تدعم المكتبة إنشاء وصيانة ملفات Excel كبيرة الحجم لبيانات التعريف.[دفتر العمل](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/)فئة يفتح مصنفًا حسب المسار والدفق وFileFormatType الخاص. لذا قم بتحميل الملف بالطريقة المناسبة لمزيد من المعالجة. قليل من الإمكانيات المذكورة أدناه ويمكن للمطورين تحسين التعليمات البرمجية الخاصة بهم بسهولة وفقًا لمتطلبات التطبيق.
 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="قراءة وتحديث الخصائص المضمنة" %}}

 لأتمتة الخصائص المضمنة، يوفر API[GetBuiltInDocumentProperties()](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/getbuiltindocumentproperties/) الطريقة التي تُرجع مجموعة DocumentProperties التي تمثل جميع خصائص المستند المضمنة في جدول البيانات. بعد الوصول إلى جميع الخصائص المضمنة، يمكنك الوصول إلى الخصائص ذات الصلة باستخدام الطريقة ذات الصلة مثل GetTitle() وGetSubject() وما إلى ذلك. لتحديث الخصائص، يوفر API طريقة مثل SetTitle وSetSubject وSetAuthor وSetComments وما إلى ذلك.[مجموعة خصائص الوثيقة المضمنة](https://reference.aspose.com/cells/cpp/aspose.cells.properties/builtindocumentpropertycollection/) للوظيفة المطلوبة.

{{% blocks/products/pf/feature-page-code h3="C++ كود لقراءة الخصائص المحددة للنظام" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "read-system-defined-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C++ كود لتحديث خصائص البناء" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "update-built-in-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="عرض وإضافة الخصائص المحددة المخصصة" %}}

للتعامل مع الخصائص المخصصة، يوفر API[المصنف::GetCustomDocumentProperties](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/getcustomdocumentproperties/) يقوم بإرجاع كافة مجموعة خصائص المستند المخصصة لجدول البيانات. أولاً، عند الوصول إلى الخصائص المخصصة عبر هذه الطريقة، يمكن للمطورين استخدام الطرق ذات الصلة لإضافة خصائص مثل AddIDocumentProperty وAddLinkToContentProperty وبالمثل استخدام UpdateLinkedPropertyValue وUpdateLinkedRange لتحديث قيمة خاصية المستند المخصص التي ترتبط بالمحتوى والنطاق المرتبط على التوالي. يمكن للمطورين استخدام الطريقة ذات الصلة من[مجموعة من خصائص الوثيقة المخصصة](https://reference.aspose.com/cells/cpp/aspose.cells.properties/customdocumentpropertycollection/).

{{% blocks/products/pf/feature-page-code h3="C++ كود لعرض الخصائص المخصصة" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "view-custom-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C++ كود اضافة البيانات الوصفية في ملف الاكسل" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "add-custom-property.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
