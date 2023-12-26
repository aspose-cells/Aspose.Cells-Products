---
title: إدارة البيانات الوصفية لملف Excel via .NET C#
description: عرض البيانات الوصفية لملفات Excel أو إضافتها أو تحريرها أو إزالتها أو استخراجها باستخدام بضعة أسطر فقط من الكود C#
keywords: [C# Aspose.Cells., c# view excel metadata., c# add excel metadata., c# insert excel metadata., c# edit excel metadata., c# remove excel metadata., c# extract excel metadata., c# modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="إدارة Microsoft<sup>&reg;</sup> بيانات تعريف ملف Excel via .NET" h2="عرض أو إضافة أو تحديث أو إزالة أو استخراج خصائص ملف Excel المضمنة والمخصصة باستخدام واجهات برمجة التطبيقات .NET من جانب الخادم." >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET اكسل API](/cells/ar/net/) يدعم إدارة الخصائص المحددة من قبل النظام (المدمجة) مثل العنوان واسم المؤلف وإحصائيات المستند وما إلى ذلك بالإضافة إلى الخصائص المحددة من قبل المستخدم (المخصصة) في شكل زوج من الاسم والقيمة. هنالك[فئة المصنف](https://reference.aspose.com/cells/net/aspose.cells/workbook) لتحميل الملفات، و[مجموعة أوراق العمل](https://reference.aspose.com/cells/net/aspose.cells/worksheetcollection) يتعامل مع مجموعة من أوراق العمل كذلك[فئة ورقة العمل](https://reference.aspose.com/cells/net/aspose.cells/worksheet) لتمثيل ورقة عمل واحدة. جنبا إلى جنب مع هذه الفئات، BuildInDocumentProperties، CustomDocumentProperties تجعل العملية بسيطة لإدارة بيانات التعريف.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="إدارة الخصائص المضمنة" %}}

 لإدارة الخصائص المحددة من قبل النظام، يوفر API[بنيتInDocumentProperties](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/builtindocumentproperties)ويمكن للمبرمجين الوصول بسهولة إلى خاصية مدمجة وتحديث قيمتها. اعتمادًا على متطلبات التطبيق، يمكن للمطورين استخدام الفهرس أو اسم الخاصية من ملف[DocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/documentpropertycollection). 

{{% blocks/products/pf/feature-page-code h3="C# كود لإدارة العقارات المبنية" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "manage-system-defined-excel-file-metadata.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="إدارة الخصائص المحددة المخصصة" %}}

 لإدارة الخصائص المحددة من قبل المستخدم، يوفر API[خصائص المستند المخصص](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/customdocumentproperties) ويمكن للمطورين الوصول بسهولة إلى الخصائص المضافة بالفعل بالإضافة إلى إضافة خصائص جديدة. ولإضافة خصائص مخصصة،[أضف طريقة](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection/methods/add/index) ل[CustomDocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection) تضيف الفئة الخاصية وترجع مرجعًا للخاصية الجديدة باعتبارها[خصائص.DocumentProperty](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty) هدف. يتم استخدام فئة DocumentProperty لاسترداد اسم وقيمة ونوع خاصية المستند كـ[DocumentProperty.Name](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/name), [DocumentProperty.Value](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/value),  [DocumentProperty.Type](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/type) التي ترجع واحدة من[نوع الملكية](https://reference.aspose.com/cells/net/aspose.cells.properties/propertytype) قيم التعداد.
 
{{% blocks/products/pf/feature-page-code h3="C# كود اضافة البيانات الوصفية في ملف الاكسل" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "add-metadata-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="C# كود إزالة الخاصية المخصصة في ملف إكسل" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "remove-custom-properties-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
