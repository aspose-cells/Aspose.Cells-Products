---
title: تحويل XLSX إلى JPG عبر تطبيق C++ 
url: /ar/cpp/conversion/xlsx-to-jpg/ 
description: نموذج رمز تحويل C++ لمستند XLSX إلى تنسيق JPG. يمكن للمبرمجين استخدام كود المصدر هذا لتحويل XLSX دفعة واحدة إلى JPG داخل أي تطبيق C++.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="تحويل XLSX إلى JPG عبر C++" h2="تحويل XLSX إلى JPG عالي الأداء باستخدام مكتبة C++ دون الحاجة إلى تثبيت Microsoft Excel أو OpenOffice أو Adobe Acrobat." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="JPG" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="كيفية تحويل XLSX إلى JPG باستخدام C++" %}}

 من أجل تحويل XLSX إلى JPG ، سنستخدم ملفات
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

{{% blocks/products/pf/agp/feature-section-col title="خطوات تحويل XLSX إلى JPG عبر C++" %}}

{{% blocks/products/pf/agp/text %}}

 يمكن لمطوّري برامج C++ تحويل ملف XLSX إلى JPG بسهولة في بضعة أسطر من التعليمات البرمجية.

{{% /blocks/products/pf/agp/text %}}

1. قم بتحميل ملف XLSX باستخدام Factory :: CreateIWorkbook.1. قم باستدعاء طريقة Save ().1. قم بتمرير مسار ملف الإخراج بامتداد ملف (JPG).1. سيتم حفظ ملف JPG في المسار المحدد.1. افتح ملف JPG في برنامج متوافق.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات النظام" %}}

{{% blocks/products/pf/agp/text %}}

 قبل تشغيل نموذج شفرة التحويل C++ ، تأكد من توفر المتطلبات الأساسية التالية لديك.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows أو نظام تشغيل متوافق مع C++ Runtime Environment لأنظمة التشغيل Windows 32 بت و Windows 64 بت و Linux 64 بت.- Aspose.Cells لـ C++ DLL المشار إليها في مشروعك.
- Microsoft Windows أو نظام تشغيل متوافق مع C++ Runtime Environment لأنظمة التشغيل Windows 32 بت و Windows 64 بت و Linux 64 بت.- Aspose.Cells لـ C++ DLL المشار إليها في مشروعك.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XLSX إلى JPG C++ شفرة مصدر التحويل" offSpacer="" %}}

```cs
// قم بتحميل ملف XLSX.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.xlsx");

// حفظ بتنسيق JPG.
wkb->Save(u"convertedFile.jpg", SaveFormat_Jpg);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="عروض توضيحية مباشرة لتحويل XLSX إلى JPG" sectionDescription="[تحويل XLSX إلى JPG](https://products.aspose.app/cells/conversion/xlsx-to-jpg) الآن من خلال زيارة موقع Live Demos الخاص بنا ، حيث يتمتع العرض التوضيحي المباشر بالمزايا التالية" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" لا حاجة لتنزيل Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" لا حاجة لكتابة أي كود." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" ما عليك سوى تحميل ملف XLSX الخاص بك ، وسيتم تحويله على الفور إلى JPG." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" سوف تحصل على رابط التحميل." >}}

    {{% blocks/products/pf/agp/content h2="C++ مكتبة معالجة ملفات Excel" %}}

 يمكن استخدام Excel API لإنشاء تنسيقات Microsoft Excel وتحريرها وتحويلها وعرضها بتنسيقات مختلفة. علاوة على ذلك ، يمكن استخدامه لرسم بياني شامل ، وإعداد تقارير قابلة للتطوير وحسابات موثوقة داخل تطبيقات البرامج. Aspose.Cells هو برنامج مستقل API ولا يتطلب أي برامج مثل Microsoft أو OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSX" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsx/" >}}

XLSX هو تنسيق معروف لمستندات Microsoft Excel تم تقديمه بواسطة Microsoft مع إصدار Microsoft Office 2007. استنادًا إلى الهيكل المنظم وفقًا لاتفاقيات التغليف المفتوح كما هو موضح في الجزء 2 من معيار OOXML ECMA-376 ، يكون التنسيق الجديد هو حزمة مضغوطة تحتوي على عدد من ملفات XML. يمكن فحص البنية والملفات الأساسية ببساطة عن طريق فك ضغط ملف .xlsx.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="JPG" readMoreLink="https://docs.fileformat.com/image/jpeg/" >}}

JPEG هو نوع من تنسيق الصور يتم حفظه باستخدام طريقة الضغط مع فقدان البيانات. الصورة الناتجة ، كنتيجة للضغط ، هي مقايضة بين حجم التخزين وجودة الصورة. يمكن للمستخدمين ضبط مستوى الضغط لتحقيق مستوى الجودة المطلوب مع تقليل حجم التخزين في نفس الوقت. تتأثر جودة الصورة بشكل ضئيل إذا تم تطبيق ضغط بنسبة 10: 1 على الصورة. كلما زادت قيمة الضغط ، زاد تدهور جودة الصورة.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="التحويلات المدعومة الأخرى" subTitle="يمكنك أيضًا تحويل XLSX إلى العديد من تنسيقات الملفات الأخرى بما في ذلك بعض التنسيقات المدرجة أدناه." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-bmp/" name="XLSX إلى BMP" description="سيب" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-csv/" name="XLSX إلى CSV" description="قيم مفصولة بفواصل" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-dif/" name="XLSX إلى DIF" description="تنسيق تبادل البيانات" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-emf/" name="XLSX إلى EMF" description="تنسيق ملف التعريف المحسن" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-gif/" name="من XLSX إلى GIF" description="تنسيق التبادل الرسومي" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-html/" name="XLSX إلى HTML" description="لغة ترميز النصوص التشعبية" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-jpeg/" name="XLSX إلى JPEG" description="صورة JPEG" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-mhtml/" name="XLSX إلى MHTML" description="تنسيق أرشيف صفحة الويب" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-ods/" name="XLSX إلى ODS" description="ملف جدول بيانات OpenDocument" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-pdf/" name="XLSX إلى PDF" description="نموذج المستندات المحمولة" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-png/" name="XLSX إلى PNG" description="رسومات الشبكة المحمولة" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-svg/" name="XLSX إلى SVG" description="الرسومات المتجهات قابلة لل" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-tiff/" name="XLSX إلى TIFF" description="تنسيق الصورة الموسومة" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-tsv/" name="XLSX إلى TSV" description="قيم مفصولة بعلامات جدولة" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-xls/" name="XLSX إلى XLS" description="تنسيق Excel الثنائي" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-xlsb/" name="XLSX إلى XLSB" description="ملف مصنف Excel ثنائي" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-xlsm/" name="XLSX إلى XLSM" description="ملف Spreasheet" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-xltm/" name="XLSX إلى XLTM" description="قالب Excel ممكّن بماكرو" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-xltx/" name="XLSX إلى XLTX" description="قالب Office OpenXML Excel" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-xps/" name="XLSX إلى XPS" description="مواصفات ورق XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}