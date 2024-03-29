---
title:  حماية وقفل XLSM مستند via .NET
weight: 7530
description: كود المصدر C# لقفل ملف XLSM باستخدام كلمة المرور على .NET Framework أو .NET Core أو Mono أو Xamarin Platforms.
keywords: [C# Aspose.Cells., c# Lock XLSM files., c# How to Protect and lock XLSM document., c# Protect XLSM files., Encrypt XLSM Files using C#]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="تشفير الملفات XLSM عبر C#" h2="جداول بيانات Excel محمية بكلمة مرور، بما في ذلك تنسيق XLSM باستخدام مكتبة .NET." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSM" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="كيفية حماية ملف XLSM باستخدام C#" %}}

 من أجل حماية ملف XLSM، سنستخدم
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API وهي منصة غنية بالميزات وقوية وسهلة الاستخدام لحماية المستندات API لمنصة C#. يفتح
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 مدير الحزم، ابحث عن
 **Aspose.Cells** 
 وتثبيت. يمكنك أيضًا استخدام الأمر التالي من وحدة تحكم إدارة الحزم.

{{% blocks/products/pf/agp/code-block title="Aspose.Cells" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="حماية XLSM عبر C#" %}}

{{% blocks/products/pf/agp/text %}}

 انت تحتاج
 [aspose.cells.dll](https://downloads.aspose.com/cells/net) 
 المشار إليها في المشروع الخاص بك لتنفيذ سير العمل التالي.

{{% /blocks/products/pf/agp/text %}}

1.  إنشاء مثيل لفئة المصنف مع المسار إلى الملف XLSM
1.  احصل على ورقة العمل الافتراضية أو أي ورقة عمل لإضافة الحماية
1.  حماية ورقة العمل باستخدام طريقة Worksheet.Protect
1.  حماية المصنف باستخدام طريقة Workbook.Protect
1.  حفظ النتيجة بتنسيق XLSM

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات النظام" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for .NET مدعوم على جميع أنظمة التشغيل الرئيسية. فقط تأكد من أن لديك المتطلبات الأساسية التالية.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows أو نظام تشغيل متوافق مع .NET Framework أو .NET Core أو Mono أو Xamarin Platforms
-  بيئة التطوير مثل Microsoft Visual Studio
-  أضف إشارة إلى Aspose.Cells for .NET DLL في مشروعك

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="يأمر" offSpacer="" %}}

```cs

// load the XLSM Excel file 
var book = new Aspose.Cells.Workbook("unlocked.xlsm");

// access the first worksheet
var worksheet = book.Worksheets[0];

// protect the worksheet with password
worksheet.Protect(Aspose.Cells.ProtectionType.All, "password", null);

// protect the whole workbook with password
book.Protect(Aspose.Cells.ProtectionType.All, "password");

// save the modified file in default format
book.Save("protected.xlsm");

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="حول Aspose.Cells for .NET API" %}}

 Aspose.Cells API يمكن استخدامه لإنشاء وتحرير وتحويل وتقديم Microsoft تنسيقات Excel إلى تنسيقات مختلفة. علاوة على ذلك، يمكن استخدامه للرسوم البيانية الشاملة وإعداد التقارير القابلة للتطوير والحسابات الموثوقة داخل تطبيقات البرامج. Aspose.Cells هو API مستقل ولا يتطلب أي برامج مثل Microsoft أو OpenOffice.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="تطبيق مجاني للحماية XLSM" sectionDescription=" تحقق من العروض التوضيحية الحية لدينا[تشفير XLSM الملفات](https://products.aspose.app/cells/protect/xlsm) مع الفوائد التالية." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" لا حاجة لتنزيل أو إعداد أي شيء" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" لا حاجة لكتابة أو ترجمة التعليمات البرمجية" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" ما عليك سوى تحميل ملف XLSM والضغط على زر \"فتح\"." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" قم بتنزيل الملف XLSM الناتج من الرابط" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSM" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsm/" >}}
الملفات ذات الامتداد XLSM هي نوع من ملفات جداول البيانات التي تدعم وحدات الماكرو. من وجهة نظر التطبيق، الماكرو عبارة عن مجموعة من التعليمات التي يتم استخدامها لأتمتة العمليات. يتم استخدام الماكرو لتسجيل الخطوات التي يتم تنفيذها بشكل متكرر وتسهيل تنفيذ الإجراءات عن طريق تشغيل الماكرو مرة أخرى. تتم برمجة وحدات الماكرو باستخدام Visual Basic for Applications (VBA) الخاص بـ Microsoft من داخل مصنف Excel باستخدام محرر Visual Basic ويمكن تشغيلها/تصحيح الأخطاء مباشرة من هناك.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="تنسيقات الحماية المدعومة الأخرى" subTitle="باستخدام C#، يمكن للمرء بسهولة حماية التنسيقات الأخرى بما في ذلك." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/ods/" name="ODS" description="ملف جدول بيانات OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/xls/" name="XLS" description="تنسيق ثنائي إكسل" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/xlsb/" name="XLSB" description="ملف مصنف Excel الثنائي" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/xlsx/" name="XLSX" description="ملف اكسيل OOXML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
