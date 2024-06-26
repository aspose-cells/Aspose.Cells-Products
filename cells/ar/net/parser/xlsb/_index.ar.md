---
title:  استخراج النص والصور من XLSB وثيقة via .NET
weight: 2200
description: C# الكود المصدري لاستخراج النصوص والصور من ملف XLSB على .NET Framework أو .NET Core أو Mono أو Xamarin Platforms.
keywords: [C# Aspose.Cells., c# Extract text and images from XLSB file., c# How to Parse XLSB File., c# Extract text from XLSB file., Extract images from XLSB file using C#]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="تحليل XLSB التنسيقات في C#" h2="تحليل مستند XLSB أصلي وعالي الأداء باستخدام واجهات برمجة التطبيقات Aspose.Cells for .NET من جانب الخادم، دون استخدام أي برنامج مثل Microsoft أو Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLSB" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="كيفية تحليل ملف XLSB باستخدام C#" %}}

 من أجل تحليل الملف XLSB، سنستخدم[Aspose.Cells for .NET](https://products.aspose.com/cells/net) API وهي منصة غنية بالميزات وقوية وسهلة الاستخدام لمعالجة المستندات API لمنصة C#. يفتح[NuGet](https://www.nuget.org/packages/aspose.cells) مدير الحزم، ابحث عن**Aspose.Cells** وتثبيت. يمكنك أيضًا استخدام الأمر التالي من وحدة تحكم إدارة الحزم.

{{% blocks/products/pf/agp/code-block title="يأمر" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="خطوات تحليل XLSB الملفات في C#" %}}

{{% blocks/products/pf/agp/text %}}

 تحليل الوثيقة الأساسية مع[Aspose.Cells for .NET](https://products.aspose.com/cells/net)يمكن إنشاء واجهات برمجة التطبيقات باستخدام بضعة أسطر من التعليمات البرمجية. تحليل النصوص والصور من Microsoft ملفات Excel XLS وXLSX وXLSM وXLSB وOpenDocument ODS.

{{% /blocks/products/pf/agp/text %}}

+ تحميل مستند XLSB.
+ حدد الورقة.
+ احصل على الصورة ونوع الصورة.
+ احفظ الصورة.
+ حفظ الوثيقة

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات النظام" %}}

{{% blocks/products/pf/agp/text %}}

 يتم دعم واجهات برمجة التطبيقات الخاصة بنا على جميع المنصات وأنظمة التشغيل الرئيسية. قبل تنفيذ التعليمات البرمجية أدناه، يرجى التأكد من توفر المتطلبات الأساسية التالية على نظامك.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows أو نظام تشغيل متوافق مع .NET Framework أو .NET Core أو Mono أو Xamarin Platforms
-  بيئة التطوير مثل Microsoft Visual Studio
-  أضف إشارة إلى Aspose.Cells for .NET DLL في مشروعك - قم بالتثبيت من NuGet باستخدام زر التنزيل أعلاه

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="تحليل XLSB الملفات - C#" offSpacer="" %}}

```cs
    // extract images from Worksheets 
    // open a template Excel file
    Workbook workbook = new Workbook("sampleExtractImagesFromWorksheets.xlsb");
    
    // get the first worksheet
    Worksheet worksheet = workbook.Worksheets[0];
    
    // get the first Picture in the first worksheet
    Aspose.Cells.Drawing.Picture pic = worksheet.Pictures[0];
    
    // set the output image file path
    string picformat = pic.ImageType.ToString();
                
    // Note: you may evaluate the image format before specifying the image path
    // define ImageOrPrintOptions
    Aspose.Cells.Rendering.ImageOrPrintOptions printoption = new  Aspose.Cells.Rendering.ImageOrPrintOptions();
    
    // specify the image format
    printoption.ImageType =  Aspose.Cells.Drawing.ImageType.Jpeg;
                
    // save the image
    pic.ToImage("outputExtractImagesFromWorksheets.jpg", printoption);  

    

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="حول Aspose.Cells for .NET API" %}}

 Aspose.Cells API يمكن استخدامه لإنشاء وتحرير وتحويل وتقديم Microsoft تنسيقات Excel إلى تنسيقات مختلفة. علاوة على ذلك، يمكن استخدامه للرسوم البيانية الشاملة وإعداد التقارير القابلة للتطوير والحسابات الموثوقة داخل تطبيقات البرامج. Aspose.Cells هو API مستقل ولا يتطلب أي برامج مثل Microsoft أو OpenOffice.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="العروض التوضيحية المباشرة للمحلل عبر الإنترنت XLSB" sectionDescription="قم باستخراج النصوص والصور من مستندات XLSB الآن من خلال زيارة موقعنا[موقع العروض الحية](https://products.aspose.app/cells/parser). يتمتع العرض التجريبي المباشر بالمزايا التالية" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" لا داعي للتحميل Aspose API." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" لا حاجة لكتابة أي رمز." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" فقط قم بتحميل ملفات XLSB الخاصة بك." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" سيتم تحليله على الفور." >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSB" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsb/" >}}
يحدد تنسيق الملف XLSB تنسيق ملف Excel الثنائي، وهو عبارة عن مجموعة من السجلات والهياكل التي تحدد محتوى مصنف Excel. يمكن أن يشتمل المحتوى على جداول أرقام غير منظمة أو شبه منظمة، أو نصوص، أو كل من الأرقام والنصوص، والصيغ، واتصالات البيانات الخارجية، والمخططات والصور. على عكس XLSX (الذي يعتمد على تنسيق ملف XML المفتوح)، يمثل XLSB ملف مصنف Excel الثنائي. يمكن قراءة وكتابة ملفات XLSB بشكل أسرع مما يجعلها مفيدة للعمل مع الملفات الكبيرة. نادرًا ما يتم استخدام XLSB لتخزين المصنفات حيث أن XLSX (وسابقًا XLS) هي تنسيقات الملفات المحددة الأكثر شيوعًا من قبل المستخدم لحفظ المصنفات. يمكن فتحه بواسطة Microsoft Office 2007 وما فوق.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="تنسيقات التحليل المدعومة الأخرى" subTitle="باستخدام C#، يمكن للمرء بسهولة تحليل التنسيقات الأخرى بما في ذلك." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/parser/ods/" name="ODS" description="ملف جدول بيانات OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/parser/xls/" name="XLS" description="تنسيق ثنائي إكسل" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/parser/xlsm/" name="XLSM" description="ملف جدول البيانات" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/parser/xlsx/" name="XLSX" description="ملف اكسيل OOXML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
