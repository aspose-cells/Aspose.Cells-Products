---
title: إدارة البيانات الوصفية لملف Excel عبر Java

description: اعرض البيانات الوصفية لملفات Excel أو أضفها أو عدلها أو أزلها أو استخرجها باستخدام سطور قليلة فقط من التعليمات البرمجية Java
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="إدارة Microsoft <sup> & reg؛ </sup> البيانات الوصفية لملف Excel عبر Java" h2="عرض أو إضافة أو تحديث أو حذف أو استخراج خصائص ملف Excel المخصصة والمضمنة باستخدام واجهات برمجة التطبيقات Java من جانب الخادم." >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Excel API](/cells/java/) يدعم إدارة الخصائص المضمنة (التي يحددها النظام) مثل العنوان واسم المؤلف وإحصائيات المستند وما إلى ذلك بالإضافة إلى الخصائص المخصصة (المعرفة من قبل المستخدم) في شكل زوج الاسم / القيمة. هنالك [فئة المصنف](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) لتحميل الملفات و [ورقة العمل](https://reference.aspose.com/cells/java/com.aspose.cells/WorksheetCollection) يتعامل مع مجموعة أوراق العمل كذلك [فئة ورقة العمل](https://reference.aspose.com/cells/java/com.aspose.cells/Worksheet) لتمثيل ورقة عمل واحدة. للوصول إلى الخصائص المضمنة والمخصصة ، تجعل BuiltInDocumentProperties و CustomDocumentProperties العملية بسيطة لإدارة البيانات الوصفية. 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="إدارة الخصائص المعرفة من قبل النظام" %}}

لإدارة الخصائص المضمنة ، يوفر API [العقارات المبنية](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#BuiltInDocumentProperties)، ويمكن للمبرمجين الوصول بسهولة إلى خاصية مدمجة وتحديث قيمتها. اعتمادًا على متطلبات التطبيق ، يمكن للمطورين استخدام اسم الفهرس أو الخاصية من [DocumentPropertyCollection](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentPropertyCollection). 

{{% blocks/products/pf/feature-page-code h3="Java رمز لإدارة الخصائص المحددة من قبل النظام" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "update-system-defined-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="إضافة وإزالة البيانات الأولية المعرفة المخصصة" %}}

للتعامل مع الخصائص المخصصة ، يوفر API [CustomDocumentProperties](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#CustomDocumentProperties)، ويمكن للمطورين الوصول بسهولة إلى الخصائص الموجودة بالإضافة إلى إضافة خصائص جديدة باستخدام [طريقة الإضافة](https://reference.aspose.com/cells/java/com.aspose.cells/customdocumentpropertycollection#add(java.lang.String,%20boolean)) من [CustomDocumentPropertyCollection](https://reference.aspose.com/cells/java/com.aspose.cells/CustomDocumentPropertyCollection) يضيف class الخاصية ويعيد مرجعًا للخاصية الجديدة كملف [الخصائص](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentProperty) هدف. تُستخدم فئة DocumentProperty لاسترداد اسم وقيمة ونوع خاصية المستند [DocumentProperty.Name](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Name)و [الوثيقة القيمة](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Value)و  [DocumentProperty.Type](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Type) هذا يعيد أحد [نوع الملكية](https://reference.aspose.com/cells/java/com.aspose.cells/PropertyType) قيم التعداد. 
 
{{% blocks/products/pf/feature-page-code h3="Java رمز لإضافة البيانات الوصفية في ملف Excel" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "add-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="Java رمز لحذف خاصية مخصصة في ملف Excel" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "remove-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
