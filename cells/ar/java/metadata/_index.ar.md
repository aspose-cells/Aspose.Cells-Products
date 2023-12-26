---
title: إدارة البيانات الوصفية لملف Excel via Java
description: عرض البيانات الوصفية لملفات Excel أو إضافتها أو تحريرها أو إزالتها أو استخراجها باستخدام بضعة أسطر فقط من الكود Java
keywords: [Java Aspose.Cells., Java view excel metadata., Java add excel metadata., Java insert excel metadata., Java edit excel metadata., Java remove excel metadata., Java extract excel metadata., Java modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="إدارة Microsoft<sup>&reg;</sup> بيانات تعريف ملف Excel via Java" h2="عرض أو إضافة أو تحديث أو حذف أو استخراج خصائص ملف Excel المخصصة والمضمنة باستخدام واجهات برمجة التطبيقات Java من جانب الخادم." >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java اكسل API](/cells/ar/java/) يدعم إدارة الخصائص المضمنة (المحددة من قبل النظام) مثل العنوان واسم المؤلف وإحصائيات المستند وما إلى ذلك بالإضافة إلى الخصائص المخصصة (المحددة من قبل المستخدم) في شكل زوج الاسم/القيمة. هنالك[فئة المصنف](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) لتحميل الملفات، و[مجموعة أوراق العمل](https://reference.aspose.com/cells/java/com.aspose.cells/WorksheetCollection) يتعامل مع مجموعة من أوراق العمل كذلك[فئة ورقة العمل](https://reference.aspose.com/cells/java/com.aspose.cells/Worksheet) لتمثيل ورقة عمل واحدة. للوصول إلى الخصائص المضمنة والمخصصة، BuildInDocumentProperties، CustomDocumentProperties تجعل العملية بسيطة لإدارة بيانات التعريف.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="إدارة الخصائص المحددة للنظام" %}}

 لإدارة العقارات المدمجة، يوفر API[بنيتInDocumentProperties](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#BuiltInDocumentProperties)ويمكن للمبرمجين الوصول بسهولة إلى خاصية مدمجة وتحديث قيمتها. اعتمادًا على متطلبات التطبيق، يمكن للمطورين استخدام الفهرس أو اسم الخاصية من ملف[DocumentPropertyCollection](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentPropertyCollection). 

{{% blocks/products/pf/feature-page-code h3="Java كود لإدارة خصائص النظام المحددة" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "update-system-defined-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="إضافة وإزالة البيانات التعريفية المحددة المخصصة" %}}

للتعامل مع الخصائص المخصصة، يوفر API[خصائص المستند المخصص](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#CustomDocumentProperties) ويمكن للمطورين الوصول بسهولة إلى العقارات الموجودة بالإضافة إلى إضافة خصائص جديدة باستخدام[إضافة طريقة](https://reference.aspose.com/cells/java/com.aspose.cells/customdocumentpropertycollection#add(java.lang.String,%20boolean) ) ل[CustomDocumentPropertyCollection](https://reference.aspose.com/cells/java/com.aspose.cells/CustomDocumentPropertyCollection) تضيف الفئة الخاصية وترجع مرجعًا للخاصية الجديدة باعتبارها[خصائص.DocumentProperty](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentProperty) هدف. يتم استخدام فئة DocumentProperty لاسترداد اسم وقيمة ونوع خاصية المستند كـ[DocumentProperty.Name](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Name), [DocumentProperty.Value](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Value),  [DocumentProperty.Type](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Type) التي ترجع واحدة من[نوع الملكية](https://reference.aspose.com/cells/java/com.aspose.cells/PropertyType) قيم التعداد.
 
{{% blocks/products/pf/feature-page-code h3="Java كود اضافة البيانات الوصفية في ملف الاكسل" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "add-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="Java كود حذف خاصية مخصصة في ملف إكسل" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "remove-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
