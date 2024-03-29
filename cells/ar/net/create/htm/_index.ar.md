---
title: إنشاء HTM - إنشاء ملف HTM في C#
description:  Aspose اكسل. C# قم بإنشاء ملف HTM بسرعة وسهولة باستخدام Aspose.Cells. قم بإنشاء ملف HTM باستخدام C#. قم بإنشاء HTM في C#. C# HTM Creator.
keywords: [Aspose Excel., C# Aspose.Cells., C# Create HTM file., Generate HTM file in C#., Create HTM file using C#., Write data to HTM file via C#., Create a HTM file in C#., C# Generate a HTM file., C# HTM Creater]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="قم بإنشاء ملف HTM في C#" h2="مكتبة C# عالية السرعة لإنشاء HTM. يعد هذا حلاً برمجيًا احترافيًا لاستيراد وتصدير XLSX وPDF والعديد من التنسيقات الأخرى على الأنظمة الأساسية .NET Framework أو .NET Core أو Mono." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="HTM" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://releases.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="إنشاء ملف HTM باستخدام C#" %}}
 كيفية إنشاء ملف HTM؟ باستخدام مكتبة Aspose.Cells for .NET، يمكنك بسهولة إنشاء ملف HTM برمجيًا باستخدام بضعة أسطر من التعليمات البرمجية.[Aspose.Cells for .NET](https://products.aspose.com/cells/net)قادر على إنشاء تطبيقات مشتركة بين الأنظمة الأساسية مع القدرة على إنشاء جميع ملفات Excel وتعديلها وتحويلها وعرضها وطباعتها. .NET Excel API لا يقوم فقط بالتحويل بين تنسيقات جداول البيانات، بل يمكنه أيضًا عرض ملفات Excel كصور، وPDF, HTML, ODS, CSV, SVG, JSON, WORD, PPT والمزيد، مما يجعله خيارًا مثاليًا لتبادل المستندات بتنسيقات متوافقة مع معايير الصناعة. يفتح[NuGet](https://www.nuget.org/packages/aspose.cells) مدير الحزم، ابحث عن Aspose.Cells وقم بتثبيته. يمكنك أيضًا استخدام الأمر التالي من وحدة تحكم إدارة الحزم.

{{% blocks/products/pf/agp/code-block title="أمر وحدة تحكم إدارة الحزم" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}
 
{{% /blocks/products/pf/agp/content %}}


{{% blocks/products/pf/agp/content h2="كيفية إنشاء HTM في C#" %}}

{{% blocks/products/pf/agp/text %}}

 من السهل على المطورين إنشاء ملفات HTM وتحميلها وتعديلها وتحويلها من خلال تشغيل تطبيقات تقارير مختلفة لمعالجة البيانات في بضعة أسطر فقط من التعليمات البرمجية.

{{% /blocks/products/pf/agp/text %}}

1.  قم بتضمين مساحة الاسم في ملف الفصل الدراسي الخاص بك
1.  إنشاء مثيل فئة المصنف.
1.  الوصول إلى ورقة العمل الأولى من المصنف.
1.  احصل على الخلية (الخلايا) المطلوبة من ورقة العمل وأدخل القيمة في الخلية (الخلايا).
1.  استخدم أسلوب الحفظ لحفظ المصنف كملف HTM.

{{% blocks/products/pf/agp/code-block title="يوضح نموذج التعليمات البرمجية كيفية إنشاء ملف HTM في C#." offSpacer="" %}}

```cs

// Create Workbook class instance.
Workbook wkb = new Workbook();

// Access the first worksheet of the workbook.
Worksheet sht = wkb.Worksheets[0];

// Get the desired cell(s) of the worksheet.
Cell c00 = sht.Cells["A1"];
Cell c01 = sht.Cells["B1"];
Cell c10 = sht.Cells["A2"];
Cell c11 = sht.Cells["B2"];

// input the value into the cell(s).
c00.PutValue("ColumnA");
c01.PutValue("ColumnB");
c10.PutValue("ValueA");
c11.PutValue("ValueB");

// Save the Workbook as .htm file.
wkb.Save("created_one.htm");

```

{{% /blocks/products/pf/agp/code-block %}}
{{% /blocks/products/pf/agp/content %}}


{{% blocks/products/pf/agp/content h2="مكتبة C# لإنشاء ملف HTM" %}}

{{% blocks/products/pf/agp/text %}}

هناك خياران بديلان لتثبيت "Aspose.Cells for .NET" على نظامك. يرجى اختيار ما يناسب احتياجاتك واتباع التعليمات خطوة بخطوة:

{{% /blocks/products/pf/agp/text %}}

1.  تثبيت أ[NuGet باقة](https://www.nuget.org/packages/Aspose.Cells/) . يرى[توثيق](https://docs.aspose.com/cells/net/installation/#install-asposecells-for-net-through-nuget)
1.  تثبيت المكتبة باستخدام[وحدة تحكم إدارة الحزم](https://docs.aspose.com/cells/net/installation/#install-asposecells-using-the-package-manager-console) داخل Visual Studio IDE

{{% /blocks/products/pf/agp/content %}}


{{% blocks/products/pf/agp/content h2="متطلبات النظام" %}}

{{% blocks/products/pf/agp/text %}}

 قبل تشغيل رمز مثال التحويل .NET، تأكد من أن لديك المتطلبات الأساسية التالية.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows أو نظام تشغيل متوافق مع الأنظمة الأساسية .NET أو .NET Core أو Windows Azure أو Mono.
-  بيئة التطوير مثل Microsoft Visual Studio.
-  أضف مرجعًا إلى Aspose.Cells for .NET DLL في مشروعك.

{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->
    {{< blocks/products/pf/agp/about-file-section >}}
        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="HTM" readMoreLink="https://docs.fileformat.com/web/htm/" >}}تمثل الملفات ذات الامتداد .htm لغة توصيف النص التشعبي لإنشاء صفحات ويب لعرضها في متصفحات الويب مثل Google Chrome وInternet Explorer وFirefox وعدد من المتصفحات الأخرى. وهو يحدد علامات إنشاء الصفحات الثابتة التي سيتم نشرها على شبكة الويب العالمية (WWW) ليتمكن الآخرون من الوصول إليها. تخبر هذه العلامات المتصفحات بكيفية عرض محتويات صفحة الويب. يمكن أن تحتوي هذه الصفحات على نص عادي وصور وارتباطات تشعبية لصفحات ومقاطع فيديو ومعلومات وسائط أخرى أخرى. عندما يتم نشر صفحة ويب، يمكنك إلقاء نظرة على رمز الترميز الموجود خلفها من خلال عرض مصدر الصفحة الخاص بها. تسمح المتصفحات الحديثة بفحص كل قسم من صفحة الويب حيث يتم تفصيل كل قسم فرعي أو عنصر ترميزي في مصدر HTM.{{< /blocks/products/pf/agp/i18n/about-file-text >}}
    {{< /blocks/products/pf/agp/about-file-section >}}
<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="إنشاء جداول البيانات المدعومة الأخرى" subTitle="يمكنك أيضًا إنشاء تنسيقات Excel Microsoft أخرى بما في ذلك بعض التنسيقات المدرجة أدناه." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/xls/" name="XLS" description="Microsoft جدول بيانات Excel (قديم)" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/xlsx/" name="XLSX" description="افتح مصنف XML" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/xlsb/" name="XLSB" description="مصنف Excel الثنائي" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/xlsm/" name="XLSM" description="جدول بيانات مزود بتقنية الماكرو" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/xlt/" name="XLT" description="قالب إكسل 97 - 2003" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/xltx/" name="XLTX" description="قالب اكسل" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/xltm/" name="XLTM" description="قالب Excel مزود بماكرو" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/csv/" name="CSV" description="قيم مفصولة بفواصل" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/tsv/" name="TSV" description="قيم مفصولة بعلامات التبويب" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/ods/" name="ODS" description="فتح جدول بيانات المستند" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/pdf/" name="PDF" description="نموذج المستندات المحمولة" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/html/" name="HTML" description="لغة ترميز النصوص التشعبية" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
