---
title:  تحرير أو عرض ODS بيانات تعريف الوثيقة عبر C++
weight: 1000
description: رمز مثال C++ لتحرير أو عرض بيانات تعريف الملف ODS على C++ بيئة التشغيل لـ Windows 32 بت وWindows 64 بت ولينكس 64 بت.
keywords: [C++ Aspose.Cells., C++ view ods metadata., C++ add ods metadata., C++ insert ods metadata., C++ edit ods metadata., C++ remove ods metadata., C++ extract ods metadata., C++ modify ods metadata]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="استخراج البيانات الوصفية ODS عبر C++" h2="أنشئ تطبيقات C++ الخاصة بك لإضافة البيانات التعريفية أو تحريرها أو إزالتها أو استخراجها من ملفات ODS باستخدام واجهات برمجة التطبيقات من جانب الخادم." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODS" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="كيفية الحصول على البيانات الوصفية ODS باستخدام C++" %}}

من أجل استخراج البيانات الوصفية ODS، سنستخدم
 [Aspose.Cells for C++](https://products.aspose.com/cells/cpp) 
 API وهي منصة غنية بالميزات وقوية وسهلة الاستخدام لاستخراج البيانات الوصفية للمستندات API for C++. يمكنك تنزيل أحدث إصدار له مباشرة، فقط قم بفتحه
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 مدير الحزم، ابحث عن
 **Aspose.Cells.Cpp** 
 وتثبيت. يمكنك أيضًا استخدام الأمر التالي من وحدة تحكم إدارة الحزم.

{{% blocks/products/pf/agp/code-block title="يأمر" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="خطوات استخراج البيانات الوصفية لـ ODS عبر C++" %}}

{{% blocks/products/pf/agp/text %}}

 الوصول إلى المعلومات المفيدة المخزنة في الملف ODS بما في ذلك وقت استلام الملف ODS ومعالجته وختمه بالوقت وما إلى ذلك.

{{% /blocks/products/pf/agp/text %}}

+ إنشاء خيارات باستخدام MetadataOptions
+ تحميل ملف ODS باستخدام WorkbookMetadata
+ إضافة خصائص جديدة عن طريق GetCustomDocumentProperties () وإضافة
+ حفظ ODS وثيقة

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات النظام" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for C++ يدعم جميع المنصات وأنظمة التشغيل الرئيسية. يرجى التأكد من أن لديك المتطلبات الأساسية التالية.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows أو نظام تشغيل متوافق مع C++ Runtime Environment لـ Windows 32 بت وWindows 64 بت وLinux 64 بت.
-  أضف مرجعًا إلى Aspose.Cells for C++ DLL في مشروعك.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="استخراج البيانات الوصفية لـ ODS - C++" offSpacer="" %}}

```cs

Aspose::Cells::Startup();

//Load the sample excel file
MetadataOptions options(MetadataType::Document_Properties);
WorkbookMetadata meta(u"c:\\book1.ods", options);
//Add a new custom property
meta.GetCustomDocumentProperties().Add(u"test", u"test");
//Save the output excel file
meta.Save(u"c:\\book2.ods");

Aspose::Cells::Cleanup();

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="حول Aspose.Cells for C++ API" %}}

 Aspose.Cells API يمكن استخدامه لإنشاء وتحرير وتحويل وتقديم Microsoft تنسيقات Excel إلى تنسيقات مختلفة. علاوة على ذلك، يمكن استخدامه للرسوم البيانية الشاملة وإعداد التقارير القابلة للتطوير والحسابات الموثوقة داخل تطبيقات البرامج. Aspose.Cells هو API مستقل ولا يتطلب أي برامج مثل Microsoft أو OpenOffice.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="استخراج البيانات الوصفية لـ ODS عبر التطبيق عبر الإنترنت" sectionDescription=" عرض وتحرير البيانات الوصفية إلى مستندات ODS باستخدام[العروض الحية](https://products.aspose.app/cells/metadata) مع الفوائد التالية." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" لا حاجة لتنزيل أو إعداد أي شيء" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" لا حاجة لكتابة أي رمز" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" ما عليك سوى تحميل ملف ODS وتحرير خصائص المستند" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" احصل على رابط التنزيل للملف الناتج على الفور" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODS" readMoreLink="https://docs.fileformat.com/spreadsheet/ods/" >}}
تمثل الملفات ذات الامتداد ODS تنسيق مستند جدول بيانات OpenDocument الذي يمكن للمستخدم تحريره. يتم تخزين البيانات داخل ملف ODF في صفوف وأعمدة. وهو تنسيق يستند إلى XML وهو أحد الأنواع الفرعية المتعددة في عائلة تنسيقات المستندات المفتوحة (ODF). تم تحديد التنسيق كجزء من مواصفات ODF 1.2 المنشورة والتي تحتفظ بها OASIS. يمكن لعدد من التطبيقات الموجودة على Windows بالإضافة إلى أنظمة التشغيل الأخرى فتح ملفات ODS للتحرير والمعالجة بما في ذلك Microsoft Excel وNeoOffice وLibreOffice. يمكن أيضًا تحويل ملفات ODS إلى تنسيقات جداول بيانات أخرى مثل XLS وXLSX وغيرها بواسطة تطبيقات مختلفة.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="تنسيقات بيانات التعريف المدعومة الأخرى" subTitle="باستخدام C++، يمكن للمرء أيضًا معالجة البيانات الوصفية للعديد من التنسيقات الأخرى بما في ذلك" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/metadata/xls/" name="XLS" description="تنسيق ثنائي إكسل" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/metadata/xlsb/" name="XLSB" description="ملف مصنف Excel الثنائي" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/metadata/xlsm/" name="XLSM" description="ملف جدول البيانات" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/metadata/xlsx/" name="XLSX" description="ملف اكسيل OOXML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
