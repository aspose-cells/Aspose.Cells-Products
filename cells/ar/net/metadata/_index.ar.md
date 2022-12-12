---
title: إدارة البيانات الوصفية لملف Excel عبر .NET C#

description: اعرض البيانات الوصفية لملفات Excel أو أضفها أو عدلها أو أزلها أو استخرجها باستخدام سطور قليلة فقط من التعليمات البرمجية C#
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="إدارة Microsoft <sup> & reg؛ </sup> البيانات الوصفية لملف Excel عبر .NET" h2="عرض أو إضافة أو تحديث أو إزالة أو استخراج خصائص ملف Excel المضمنة والمخصصة باستخدام واجهات برمجة التطبيقات .NET من جانب الخادم." >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Excel API](/cells/net/) يدعم إدارة الخصائص المحددة من قبل النظام (المضمنة) مثل العنوان واسم المؤلف وإحصائيات المستند وما إلى ذلك بالإضافة إلى الخصائص المحددة من قبل المستخدم (المخصصة) في شكل زوج الاسم والقيمة. هنالك [فئة المصنف](https://reference.aspose.com/cells/net/aspose.cells/workbook) لتحميل الملفات و [ورقة العمل](https://reference.aspose.com/cells/net/aspose.cells/worksheetcollection) يتعامل مع مجموعة أوراق العمل كذلك [فئة ورقة العمل](https://reference.aspose.com/cells/net/aspose.cells/worksheet) لتمثيل ورقة عمل واحدة. إلى جانب هذه الفئات ، تجعل BuiltInDocumentProperties و CustomDocumentProperties العملية بسيطة لإدارة البيانات الوصفية. 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="إدارة الخصائص المضمنة" %}}

لإدارة الخصائص التي يحددها النظام ، يوفر API [العقارات المبنية](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/builtindocumentproperties)، ويمكن للمبرمجين الوصول بسهولة إلى خاصية مدمجة وتحديث قيمتها. اعتمادًا على متطلبات التطبيق ، يمكن للمطورين استخدام اسم الفهرس أو الخاصية من [DocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/documentpropertycollection). 

{{% blocks/products/pf/feature-page-code h3="C# رمز لإدارة الخصائص المضمنة" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "manage-system-defined-excel-file-metadata.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="إدارة الخصائص المعرفة المخصصة" %}}

لإدارة الخصائص المعرفة من قبل المستخدم ، يوفر API [CustomDocumentProperties](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/customdocumentproperties)، ويمكن للمطورين الوصول بسهولة إلى الخصائص المضافة بالفعل بالإضافة إلى إضافة خصائص جديدة. من أجل إضافة خصائص مخصصة ، [طريقة الإضافة](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection/methods/add/index) من [CustomDocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection) يضيف class الخاصية ويعيد مرجعًا للخاصية الجديدة كملف [الخصائص](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty) هدف. تُستخدم فئة DocumentProperty لاسترداد اسم وقيمة ونوع خاصية المستند [DocumentProperty.Name](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/name)و [الوثيقة القيمة](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/value)و  [DocumentProperty.Type](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/type) هذا يعيد أحد [نوع الملكية](https://reference.aspose.com/cells/net/aspose.cells.properties/propertytype) قيم التعداد. 
 
{{% blocks/products/pf/feature-page-code h3="C# رمز لإضافة البيانات الوصفية في ملف Excel" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "add-metadata-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="C# رمز لإزالة الخاصية المخصصة في ملف Excel" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "remove-custom-properties-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
