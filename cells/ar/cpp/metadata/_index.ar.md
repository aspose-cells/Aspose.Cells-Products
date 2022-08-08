---
title: إدارة البيانات الوصفية لملف Excel عبر C++
url: /ar/cpp/metadata/
description: عرض أو إضافة أو تعديل أو إزالة أو استخراج البيانات الوصفية لملفات Excel باستخدام مكتبة C++
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="إدارة Microsoft <sup> & reg؛ </sup> البيانات الوصفية لمستند Excel عبر C++" h2="عرض أو إدراج أو تحديث أو إزالة أو استخراج خصائص مستندات Excel المخصصة والمضمنة داخل C++ تطبيقات." >}}
{{% blocks/products/pf/feature-page-summary %}}
البيانات الوصفية في Excel - كيفية عرض وإدراج وإزالة البيانات الوصفية لملف Excel. [C++ مكتبة Excel](/cells/cpp/) يعد faclitates طريقة سهلة من خلال دعم الخصائص المضمنة / المحددة من قبل النظام مثل اسم المؤلف والعنوان وإحصائيات المستند وما إلى ذلك المطلوبة في وقت ما مثل التحقق من تعديل الملف الأخير أو حفظه جنبًا إلى جنب مع الخصائص المخصصة / المعرفة في شكل أزواج الاسم / القيمة. لأتمتة العملية ، تدعم المكتبة إنشاء ملفات Excel للبيانات الوصفية الكبيرة والحفاظ عليها. [طريقة CreateIWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8) من [فئة المصنع](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory) افتح مصنفًا حسب المسار والدفق وبواسطة FileFormatType الخاص. لذلك قم بتحميل الملف بطريقة التقريب لمزيد من المعالجة. قليل من الاحتمالات المدرجة أدناه ويمكن للمطورين تحسين الكود الخاص بهم بسهولة وفقًا لمتطلبات التطبيق. 
 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="قراءة وتحديث الخصائص المضمنة" %}}

لأتمتة الخصائص المضمنة ، يوفر API [GetIBuiltInDocumentProperties ()](https://reference.aspose.com/cells/cpp/class/aspose.cells.metadata.i_workbook_metadata) تقوم بإرجاع مجموعة DocumentProperties التي تمثل جميع خصائص المستند المضمنة في جدول البيانات. بعد الوصول إلى جميع الخصائص المضمنة ، قم بالوصول إلى الخصائص ذات الصلة باستخدام الطريقة ذات الصلة مثل GetTitle () و GetSubject () وما إلى ذلك. لتحديث الخصائص ، يوفر API طريقة مثل SetTitle و SetSubject و SetAuthor و SetComments وما إلى ذلك. [مجموعة ممتلكات وثيقة مضمنة](https://reference.aspose.com/cells/cpp/class/aspose.cells.properties.i_built_in_document_property_collection) للوظيفة المطلوبة.

{{% blocks/products/pf/feature-page-code h3="C++ رمز لقراءة الخصائص المحددة من قبل النظام" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "read-system-defined-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C++ رمز لتحديث الخصائص المضمنة" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "update-built-in-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="عرض وإضافة الخصائص المعرفة المخصصة" %}}

للتعامل مع الخصائص المخصصة ، يوفر API [IWorkbookMetadata :: GetICustomDocumentProperties](https://reference.aspose.com/cells/cpp/class/aspose.cells.metadata.i_workbook_metadata#a69f0226813ce18c03ebc13b8ca691e79) يقوم بإرجاع كل مجموعة خصائص المستند المخصصة لجدول البيانات. أولاً ، عند الوصول إلى الخصائص المخصصة عبر هذه الطريقة ، يمكن للمطورين استخدام الأساليب ذات الصلة لإضافة خصائص مثل AddIDocumentProperty و AddLinkToContentProperty وبالمثل استخدام UpdateLinkedPropertyValue و UpdateLinkedRange لتحديث قيمة خاصية المستند المخصصة التي ترتبط بالمحتوى والنطاق المرتبط على التوالي. يمكن للمطورين استخدام الطريقة ذات الصلة من [مجموعة من خصائص الوثيقة المخصصة](https://reference.aspose.com/cells/cpp/class/aspose.cells.properties.i_custom_document_property_collection).

{{% blocks/products/pf/feature-page-code h3="C++ رمز لعرض الخصائص المخصصة" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "view-custom-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C++ رمز لإضافة البيانات الوصفية في ملف Excel" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "add-custom-property.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}