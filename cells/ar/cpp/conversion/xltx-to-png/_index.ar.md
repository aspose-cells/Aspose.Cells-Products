---
title: قم بتحويل XLTX إلى PNG عبر تطبيق C++ 
url: /ar/cpp/conversion/xltx-to-png/ 
description: نموذج C++ كود التحويل لمستند XLTX إلى تنسيق PNG. يمكن للمبرمجين استخدام كود المصدر هذا لتحويل XLTX إلى PNG دفعة داخل أي تطبيق C++.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="تحويل XLTX إلى PNG عبر C++" h2="تحويل XLTX إلى PNG عالي الأداء باستخدام مكتبة C++ دون الحاجة إلى تثبيت Microsoft Excel أو OpenOffice أو Adobe Acrobat." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PNG" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLTX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="كيفية تحويل XLTX إلى PNG باستخدام C++" %}}

 من أجل تحويل XLTX إلى PNG ، سنستخدم ملفات
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

{{% blocks/products/pf/agp/feature-section-col title="خطوات تحويل XLTX إلى PNG عبر C++" %}}

{{% blocks/products/pf/agp/text %}}

 يمكن لمطوّري برامج C++ بسهولة تحويل ملف XLTX إلى PNG في بضعة أسطر من التعليمات البرمجية.

{{% /blocks/products/pf/agp/text %}}

1. قم بتحميل ملف XLTX باستخدام Factory :: CreateIWorkbook.1. حدد ورقة العمل الأولى.1. اضبط خيارات (PNG).1. كرر خلال كل صفحة من الورقة وعرضها.1. افتح ملف PNG في برنامج متوافق.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات النظام" %}}

{{% blocks/products/pf/agp/text %}}

 قبل تشغيل نموذج شفرة التحويل C++ ، تأكد من توفر المتطلبات الأساسية التالية لديك.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows أو نظام تشغيل متوافق مع C++ Runtime Environment لأنظمة التشغيل Windows 32 بت و Windows 64 بت و Linux 64 بت.- Aspose.Cells لـ C++ DLL المشار إليها في مشروعك.
- Microsoft Windows أو نظام تشغيل متوافق مع C++ Runtime Environment لأنظمة التشغيل Windows 32 بت و Windows 64 بت و Linux 64 بت.- Aspose.Cells لـ C++ DLL المشار إليها في مشروعك.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XLTX إلى PNG C++ شفرة مصدر التحويل" offSpacer="" %}}

```cs
// مسار دليل الإخراج.
StringPtr outDir = new String("OutputDirectoryPath");

// قم بتحميل ملف XLTX.
intrusive_ptr<Aspose::Cells::IWorkbook> workbook = Factory::CreateIWorkbook(u"sourceFile.xltx");

// الوصول إلى ورقة العمل الأولى.
intrusive_ptr<Aspose::Cells::IWorksheet> worksheet = workbook->GetIWorksheets()->GetObjectByIndex(0);

// إنشاء صورة أو كائن خيارات الطباعة.
intrusive_ptr<Aspose::Cells::Rendering::IImageOrPrintOptions> imgOptions = Factory::CreateIImageOrPrintOptions();

// حدد تنسيق الصورة.
imgOptions->SetImageFormat(Aspose::Cells::Systems::Drawing::Imaging::ImageFormat::GetPng());

// حدد الدقة الأفقية والعمودية
imgOptions->SetHorizontalResolution(200);
imgOptions->SetVerticalResolution(200);

// تجسيد الورقة فيما يتعلق بالصورة المحددة أو خيارات الطباعة.
intrusive_ptr<Aspose::Cells::Rendering::ISheetRender> sr = Factory::CreateISheetRender(worksheet, imgOptions);

// احصل على عدد الصفحات.
Aspose::Cells::Systems::Int32 pageCount = sr->GetPageCount();

// إنشاء كائن منشئ السلسلة لسلسلة السلاسل.
intrusive_ptr<Aspose::Cells::Systems::Text::StringBuilder> sb = new Aspose::Cells::Systems::Text::StringBuilder();

// جعل كل صفحة إلى صورة png واحدة تلو الأخرى.
for (int i = 0; i Clear();
	sb->Append(outDir);
	sb->Append((StringPtr)new String("outputConvertingWorksheetToImagePNG_"));
	sb->Append(i);
	sb->Append((StringPtr)new String(".png"));

	// احصل على مسار الصورة الناتجة.
	StringPtr outputPNG = sb->ToString();

	// تحويل ورقة العمل إلى صورة بابوا نيو غينيا.
	sr->ToImage(i, outputPNG);
}


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="عروض توضيحية مباشرة لتحويل XLTX إلى PNG" sectionDescription="[تحويل XLTX إلى PNG](https://products.aspose.app/cells/conversion/xltx-to-png) الآن من خلال زيارة موقع Live Demos الخاص بنا ، حيث يتمتع العرض التوضيحي المباشر بالمزايا التالية" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" لا حاجة لتنزيل Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" لا حاجة لكتابة أي كود." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" ما عليك سوى تحميل ملف XLTX الخاص بك ، وسيتم تحويله على الفور إلى PNG." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" سوف تحصل على رابط التحميل." >}}

    {{% blocks/products/pf/agp/content h2="C++ مكتبة معالجة ملفات Excel" %}}

 يمكن استخدام Excel API لإنشاء تنسيقات Microsoft Excel وتحريرها وتحويلها وعرضها بتنسيقات مختلفة. علاوة على ذلك ، يمكن استخدامه لرسم بياني شامل ، وإعداد تقارير قابلة للتطوير وحسابات موثوقة داخل تطبيقات البرامج. Aspose.Cells هو برنامج مستقل API ولا يتطلب أي برامج مثل Microsoft أو OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLTX" readMoreLink="https://docs.fileformat.com/spreadsheet/xltx/" >}}

تمثل الملفات ذات الملحق XLTX ملفات قالب Microsoft Excel التي تستند إلى مواصفات تنسيق ملف Office OpenXML. يتم استخدامه لإنشاء ملف قالب قياسي يمكن استخدامه لإنشاء ملفات XLSX التي تعرض نفس الإعدادات المحددة في ملف XLTX.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PNG" readMoreLink="https://docs.fileformat.com/image/png/" >}}

يشير PNG ، Portable Network Graphics ، إلى نوع من تنسيق ملف الصور النقطية الذي يستخدم ضغطًا بلا فقدان. تم إنشاء تنسيق الملف هذا كبديل لتنسيق تبادل الرسومات (GIF) وليس له قيود على حقوق النشر. ومع ذلك ، لا يدعم تنسيق ملف PNG الرسوم المتحركة. يدعم تنسيق ملف PNG ضغط الصور بدون فقدان مما يجعله شائعًا بين مستخدميه. مع مرور الوقت ، تطورت PNG كواحدة من أكثر تنسيقات ملفات الصور استخدامًا. تدعم جميع أنظمة التشغيل تقريبًا فتح ملفات PNG. على سبيل المثال ، يمتلك عارض Microsoft Windows القدرة على فتح ملفات PNG لأن نظام التشغيل لديه افتراضيًا الدعم المتاح كجزء من التثبيت.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}