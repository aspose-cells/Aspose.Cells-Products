---
title: تحويل XLT إلى PDF عبر تطبيق C++ 
url: /ar/cpp/conversion/xlt-to-pdf/ 
description: نموذج C++ رمز التحويل لمستند XLT إلى تنسيق PDF. يمكن للمبرمجين استخدام كود المصدر هذا لتحويل XLT إلى PDF دفعة داخل أي تطبيق C++.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="تحويل XLT إلى PDF عبر C++" h2="تحويل XLT إلى PDF عالي الأداء باستخدام مكتبة C++ دون الحاجة إلى تثبيت Microsoft Excel أو OpenOffice أو Adobe Acrobat." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PDF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="كيفية تحويل XLT إلى PDF باستخدام C++" %}}

 من أجل تحويل XLT إلى PDF ، سنستخدم ملفات
 [Aspose.Cells لـ C++](https://products.aspose.com/cells/cpp) 
 API وهو نظام غني بالميزات وقوي وسهل الاستخدام لمعالجة المستندات وتحويلها API لـ C++ النظام الأساسي. يمكنك تنزيل أحدث إصدار مباشرة ، فقط افتح
 [نوجيت](https://www.nuget.org/packages/aspose.cells) 
 مدير الحزم ، ابحث عن
 Aspose.Cells .cpp 
 وتثبيت. يمكنك أيضًا استخدام الأمر التالي من Package Manager Console.

{{% blocks/products/pf/agp/code-block title="أمر" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="خطوات تحويل XLT إلى PDF عبر C++" %}}

{{% blocks/products/pf/agp/text %}}

 C++ يستطيع مطورو البرامج بسهولة تحويل ملف XLT إلى PDF في بضعة أسطر من التعليمات البرمجية.

{{% /blocks/products/pf/agp/text %}}

1. قم بتحميل ملف XLT باستخدام Factory :: CreateIWorkbook.1. قم باستدعاء طريقة Save ().1. قم بتمرير مسار ملف الإخراج بامتداد ملف (PDF).1. سيتم حفظ ملف PDF في المسار المحدد.1. افتح ملف PDF في برنامج متوافق.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات النظام" %}}

{{% blocks/products/pf/agp/text %}}

 قبل تشغيل نموذج شفرة التحويل C++ ، تأكد من توفر المتطلبات الأساسية التالية لديك.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows أو نظام تشغيل متوافق مع C++ Runtime Environment لأنظمة التشغيل Windows 32 بت و Windows 64 بت و Linux 64 بت.- Aspose.Cells لـ C++ DLL المشار إليها في مشروعك.
- Microsoft Windows أو نظام تشغيل متوافق مع C++ Runtime Environment لأنظمة التشغيل Windows 32 بت و Windows 64 بت و Linux 64 بت.- Aspose.Cells لـ C++ DLL المشار إليها في مشروعك.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XLT إلى PDF C++ شفرة مصدر التحويل" offSpacer="" %}}

```cs
// قم بتحميل XLT.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.xlt");

// حفظ بتنسيق PDF.
wkb->Save(u"convertedFile.pdf", SaveFormat_Pdf);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="عروض توضيحية مباشرة لتحويل XLT إلى PDF" sectionDescription="[تحويل XLT إلى PDF](https://products.aspose.app/cells/conversion/xlt-to-pdf) الآن من خلال زيارة موقع Live Demos الخاص بنا ، حيث يتمتع العرض التوضيحي المباشر بالمزايا التالية" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" لا حاجة لتنزيل Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" لا حاجة لكتابة أي كود." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" ما عليك سوى تحميل ملف XLT الخاص بك ، وسيتم تحويله على الفور إلى PDF." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" سوف تحصل على رابط التحميل." >}}

    {{% blocks/products/pf/agp/content h2="C++ مكتبة معالجة ملفات Excel" %}}

 يمكن استخدام Excel API لإنشاء تنسيقات Microsoft Excel وتحريرها وتحويلها وعرضها بتنسيقات مختلفة. علاوة على ذلك ، يمكن استخدامه لرسم بياني شامل ، وإعداد تقارير قابلة للتطوير وحسابات موثوقة داخل تطبيقات البرامج. Aspose.Cells هو برنامج مستقل API ولا يتطلب أي برامج مثل Microsoft أو OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLT" readMoreLink="https://docs.fileformat.com/spreadsheet/xlt/" >}}

الملفات ذات الامتداد. XLT هي ملفات قوالب تم إنشاؤها باستخدام Microsoft Excel وهو تطبيق جداول بيانات يأتي كجزء من مجموعة Microsoft Office. دعم Microsoft Office 97-2003 إنشاء ملفات XLT جديدة بالإضافة إلى فتحها. لا يزال أحدث إصدار من Excel قادرًا على فتح ملفات قوالب التنسيق القديمة هذه. يتم استخدام ملف القالب هذا لإنشاء ملفات Excel جديدة بسرعة مع البيانات والإعدادات الافتراضية مثل تنسيق الصفحة وحجم الخط والهوامش والمخططات وما إلى ذلك والتي يمكن حفظها كملفات XLS جديدة.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PDF" readMoreLink="https://docs.fileformat.com/view/pdf/" >}}

تنسيق المستندات المحمولة (PDF) هو نوع من المستندات التي أنشأتها Adobe في التسعينيات. كان الغرض من تنسيق الملف هذا هو تقديم معيار لتمثيل المستندات والمواد المرجعية الأخرى بتنسيق مستقل عن برامج التطبيقات والأجهزة وكذلك نظام التشغيل. يمكن فتح ملفات PDF في Adobe Acrobat Reader / Writer وكذلك في معظم المتصفحات الحديثة مثل Chrome و Safari و Firefox عبر الإضافات / المكونات الإضافية. تقدم معظم مجموعات البرامج المتاحة تجاريًا أيضًا تحويل مستنداتها إلى تنسيق ملف PDF دون الحاجة إلى أي مكون برمجي إضافي. وبالتالي ، فإن تنسيق ملف PDF لديه القدرة الكاملة على احتواء معلومات مثل النصوص والصور والارتباطات التشعبية وحقول النموذج والوسائط الغنية والتوقيعات الرقمية والمرفقات والبيانات الوصفية والميزات الجغرافية المكانية والكائنات ثلاثية الأبعاد الموجودة فيه والتي يمكن أن تصبح جزءًا من المستند المصدر.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}