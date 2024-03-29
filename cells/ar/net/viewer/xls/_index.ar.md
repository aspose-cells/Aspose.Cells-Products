---
title:  عرض XLS تنسيقات الملفات via .NET
weight: 1260
description: كود المصدر C# لتحميل وعرض وعرض XLS مستندًا على .NET Framework أو .NET Core أو Mono أو Xamarin Platforms.
keywords: [C# Aspose.Cells., c# view XLS files., c# how to render XLS document., c# load and display XLS files., XLS File Viewer using C#]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="XLS عارض الملفات for .NET" h2="عرض جداول بيانات Excel وOpenOffice مثل XLS دون الحاجة إلى Microsoft Excel أو Office Automation." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLS" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="كيفية عرض ملف XLS باستخدام C#" %}}

 لعرض ملف XLS، سنستخدم
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API وهي منصة غنية بالميزات وقوية وسهلة الاستخدام API لمنصة C# لاستخدامها مع أي مشاهد. يفتح
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 مدير الحزم، ابحث عن
 **Aspose.Cells** 
 وتثبيت. يمكنك أيضًا استخدام الأمر التالي من وحدة تحكم إدارة الحزم.

{{% blocks/products/pf/agp/code-block title="أمر وحدة تحكم إدارة الحزم" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="خطوات المشاهدة XLS عبر C#" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells يجعل من السهل على المطورين عرض ملف XLS مع بضعة أسطر فقط من التعليمات البرمجية.

{{% /blocks/products/pf/agp/text %}}

1.  قم بتحميل الملف XLS في مثيل المصنف
1.  قم بإنشاء مثيل لـ HtmlSaveOptions وقم بتعيين خاصية ExportHeadings على true
1. احفظ الملف XLS بتنسيق HTML باستخدام طريقة Workbook.Save
1.  قم بتحميل HTML الناتج في المتصفح الافتراضي باستخدام Process.Start

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات النظام" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for .NET مدعوم على جميع أنظمة التشغيل الرئيسية. فقط تأكد من أن لديك المتطلبات الأساسية التالية.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows أو نظام تشغيل متوافق مع .NET Framework أو .NET Core أو Mono أو Xamarin Platforms
-  بيئة التطوير مثل Microsoft Visual Studio
-  أضف إشارة إلى Aspose.Cells for .NET DLL في مشروعك

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# رمز المثال لعرض ملف XLS" offSpacer="" %}}

```cs

string output = System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".html";

// load the XLS file in an instance of Workbook
var book = new Aspose.Cells.Workbook("template.xls");
// create an instance of HtmlSaveOptions & set ExportHeadings property to true
var options = new Aspose.Cells.HtmlSaveOptions();
options.ExportHeadings = true;

// save the XLS file in HTML format
book.Save(output, options);
// load resultant HTML in default browser
System.Diagnostics.Process.Start(output);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="حول Aspose.Cells for .NET API" %}}

 Aspose.Cells API يمكن استخدامه لإنشاء وتحرير وتحويل وتقديم Microsoft تنسيقات Excel إلى تنسيقات مختلفة. علاوة على ذلك، يمكن استخدامه للرسوم البيانية الشاملة وإعداد التقارير القابلة للتطوير والحسابات الموثوقة داخل تطبيقات البرامج. Aspose.Cells هو API مستقل ولا يتطلب أي برامج مثل Microsoft أو OpenOffice.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="تطبيق مجاني للعرض XLS" sectionDescription=" تحقق من العروض التوضيحية الحية لدينا[عرض XLS](https://products.aspose.app/cells/viewer/xls) مع الفوائد التالية." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" لا حاجة لتنزيل أو إعداد أي شيء" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" لا حاجة لكتابة أو ترجمة التعليمات البرمجية" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" ما عليك سوى تحميل ملف XLS والضغط على زر \"عرض\"." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" قم بتنزيل ملف XLS من الرابط إذا لزم الأمر" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}
تمثل الملفات ذات الامتداد XLS تنسيق ملف Excel الثنائي. يمكن إنشاء مثل هذه الملفات بواسطة Microsoft Excel بالإضافة إلى برامج جداول البيانات المماثلة الأخرى مثل OpenOffice Calc أو Apple Numbers. يُعرف الملف المحفوظ بواسطة Excel باسم Workbook حيث يمكن أن يحتوي كل مصنف على ورقة عمل واحدة أو أكثر. يتم تخزين البيانات وعرضها للمستخدمين بتنسيق جدول في ورقة العمل ويمكن أن تشمل القيم الرقمية والبيانات النصية والصيغ واتصالات البيانات الخارجية والصور والمخططات. تتيح لك تطبيقات مثل Microsoft Excel تصدير بيانات المصنف إلى عدة تنسيقات مختلفة بما في ذلك PDF وCSV وXLSX وTXT وHTML وXPS والعديد من التنسيقات الأخرى. تم استبدال تنسيق الملف XLS بتنسيق أكثر انفتاحًا وتنظيمًا، XLSX، مع إصدار Microsoft Excel 2007. ولا تزال أحدث الإصدارات توفر دعمًا لإنشاء وقراءة ملفات XLS، على الرغم من أن XLSX هو الخيار الأول للاستخدام الآن.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="تنسيقات العارض المدعومة الأخرى" subTitle="باستخدام C#، يمكن للمرء أيضًا عرض العديد من تنسيقات الملفات الأخرى بما في ذلك." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/csv/" name="CSV" description="قيم مفصولة بفواصل" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/ods/" name="ODS" description="ملف جدول بيانات OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/tsv/" name="TSV" description="قيم مفصولة بعلامات جدولة" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/txt/" name="TXT" description="وثيقة نصية" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xlsb/" name="XLSB" description="ملف مصنف Excel الثنائي" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xlsm/" name="XLSM" description="ملف جدول البيانات" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xlsx/" name="XLSX" description="ملف اكسيل OOXML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xlt/" name="XLT" description="Microsoft قالب إكسل" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xltm/" name="XLTM" description="قالب Excel مزود بماكرو" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xltx/" name="XLTX" description="قالب Excel لمكتب OpenXML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
