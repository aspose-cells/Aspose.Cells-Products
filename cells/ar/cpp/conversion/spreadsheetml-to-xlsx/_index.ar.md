---
title: تحويل SPREADSHEETML إلى XLSX عبر تطبيق C++ 
url: /ar/cpp/conversion/spreadsheetml-to-xlsx/ 
description: نموذج رمز تحويل C++ لمستند SPREADSHEETML إلى تنسيق XLSX. يمكن للمبرمجين استخدام كود المصدر هذا لتحويل SPREADSHEETML دفعة واحدة إلى XLSX داخل أي تطبيق C++.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="تحويل SPREADSHEETML إلى XLSX عبر C++" h2="SPREADSHEETML عالي الأداء لتحويل XLSX باستخدام مكتبة C++ دون الحاجة إلى تثبيت Microsoft Excel أو OpenOffice أو Adobe Acrobat." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="SPREADSHEETML" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="كيفية تحويل SPREADSHEETML إلى XLSX باستخدام C++" %}}

 من أجل تحويل SPREADSHEETML إلى XLSX ، سنستخدم
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

{{% blocks/products/pf/agp/feature-section-col title="خطوات تحويل SPREADSHEETML إلى XLSX عبر C++" %}}

{{% blocks/products/pf/agp/text %}}

 يمكن لمطوري C++ بسهولة تحويل ملف SPREADSHEETML إلى XLSX في بضعة أسطر من التعليمات البرمجية.

{{% /blocks/products/pf/agp/text %}}

1. قم بتحميل ملف SPREADSHEETML باستخدام Factory :: CreateIWorkbook.1. قم باستدعاء طريقة Save ().1. قم بتمرير مسار ملف الإخراج بامتداد الملف (XLSX).1. سيتم حفظ ملف XLSX في المسار المحدد.1. افتح ملف XLSX في برنامج متوافق.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات النظام" %}}

{{% blocks/products/pf/agp/text %}}

 قبل تشغيل نموذج شفرة التحويل C++ ، تأكد من توفر المتطلبات الأساسية التالية لديك.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows أو نظام تشغيل متوافق مع C++ Runtime Environment لأنظمة التشغيل Windows 32 بت و Windows 64 بت و Linux 64 بت.- Aspose.Cells لـ C++ DLL المشار إليها في مشروعك.
- Microsoft Windows أو نظام تشغيل متوافق مع C++ Runtime Environment لأنظمة التشغيل Windows 32 بت و Windows 64 بت و Linux 64 بت.- Aspose.Cells لـ C++ DLL المشار إليها في مشروعك.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="SPREADSHEETML إلى شفرة مصدر تحويل XLSX C++" offSpacer="" %}}

```cs
// قم بتحميل ملف SPREADSHEETML.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.spreadsheetml");

// حفظ بتنسيق XLSX.
wkb->Save(u"convertedFile.xlsx", SaveFormat_Xlsx);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="SPREADSHEETML إلى العروض التجريبية المباشرة لتحويل XLSX" sectionDescription="[تحويل SPREADSHEETML إلى XLSX](https://products.aspose.app/cells/conversion/spreadsheetml-to-xlsx) الآن من خلال زيارة موقع Live Demos الخاص بنا ، حيث يتمتع العرض التوضيحي المباشر بالمزايا التالية" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" لا حاجة لتنزيل Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" لا حاجة لكتابة أي كود." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" ما عليك سوى تحميل ملف SPREADSHEETML الخاص بك ، وسيتم تحويله على الفور إلى XLSX." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" سوف تحصل على رابط التحميل." >}}

    {{% blocks/products/pf/agp/content h2="C++ مكتبة معالجة ملفات Excel" %}}

 يمكن استخدام Excel API لإنشاء تنسيقات Microsoft Excel وتحريرها وتحويلها وعرضها بتنسيقات مختلفة. علاوة على ذلك ، يمكن استخدامه لرسم بياني شامل ، وإعداد تقارير قابلة للتطوير وحسابات موثوقة داخل تطبيقات البرامج. Aspose.Cells هو برنامج مستقل API ولا يتطلب أي برامج مثل Microsoft أو OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="SPREADSHEETML" readMoreLink="/{{spreadsheetml_url}}" >}}

{{spreadsheetml}}

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSX" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsx/" >}}

XLSX هو تنسيق معروف لمستندات Microsoft Excel تم تقديمه بواسطة Microsoft مع إصدار Microsoft Office 2007. استنادًا إلى الهيكل المنظم وفقًا لاتفاقيات التغليف المفتوح كما هو موضح في الجزء 2 من معيار OOXML ECMA-376 ، يكون التنسيق الجديد هو حزمة مضغوطة تحتوي على عدد من ملفات XML. يمكن فحص البنية والملفات الأساسية ببساطة عن طريق فك ضغط ملف .xlsx.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}