---
title: بحث في مستند CSV بدون فتح عبر .NET 
weight: 7510
url: /ar/net/search/csv/ 
description: C# شفرة المصدر للبحث عن الكلمات ذات النمط في ملف CSV على .NET Framework أو .NET Core أو Mono أو أنظمة Xamarin الأساسية.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="بحث في تنسيقات CSV في C#" h2="بحث محلي وعالي الأداء في مستندات CSV باستخدام واجهات برمجة تطبيقات Aspose.Cells for .NET من جانب الخادم ، بدون استخدام أي برنامج مثل Microsoft أو Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="CSV" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="كيفية البحث في ملف CSV باستخدام C#" %}}

 من أجل البحث في ملف CSV ، سنستخدم
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API وهو بحث غني بالميزات وقوي وسهل الاستخدام في المستندات API من أجل C# النظام الأساسي. يفتح
 [نوجيت](https://www.nuget.org/packages/aspose.cells) 
 مدير الحزم ، ابحث عن
 ** Aspose.Cells ** 
 وتثبيت. يمكنك أيضًا استخدام الأمر التالي من Package Manager Console.

{{% blocks/products/pf/agp/code-block title="أمر" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="خطوات البحث في ملفات CSV في C#" %}}

{{% blocks/products/pf/agp/text %}}

 بحث أساسي في المستند باستخدام
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 يمكن عمل واجهات برمجة التطبيقات ببضعة سطور من التعليمات البرمجية.

{{% /blocks/products/pf/agp/text %}}

+ تحميل ملف CSV باستخدام فئة المصنف.
+ احصل على الخلايا في الورقة ذات الصلة.
+ أرقام البحث والتاريخ والنص باستخدام طريقة البحث

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات النظام" %}}

{{% blocks/products/pf/agp/text %}}

 يتم دعم واجهات برمجة التطبيقات الخاصة بنا على جميع الأنظمة الأساسية وأنظمة التشغيل الرئيسية. قبل تنفيذ الكود أدناه ، يرجى التأكد من أن لديك المتطلبات الأساسية التالية على نظامك.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows أو نظام تشغيل متوافق مع .NET Framework أو .NET Core أو Mono أو الأنظمة الأساسية Xamarin- بيئة التطوير مثل Microsoft Visual Studio- Aspose.Cells for .NET DLL المشار إليه في مشروعك - قم بالتثبيت من NuGet باستخدام الزر "تنزيل" أعلاه
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="بحث في ملفات CSV - C#" offSpacer="" %}}

```cs
// البحث عن الخلايا التي تحتوي على قيمة سلسلة محددة أو رقم
Workbook workbook = new Workbook("book1.csv");

// جمع الخلايا
Cells cells = workbook.Worksheets[0].Cells;

FindOptions opts = new FindOptions();
opts.LookInType = LookInType.Values;
opts.LookAtType = LookAtType.EntireContent;

// ابحث عن الخلية التي تحتوي على عدد صحيح أو مزدوج
Cell cell1 = cells.Find(205, null, opts);

if (cell1 != null){
    Console.WriteLine("Name of the cell containing the value: " + cell1.Name);
}else{
    Console.WriteLine("Record not found ");
}

// ابحث عن الخلية التي تحتوي على سلسلة الإدخال
Aspose.Cells.Cell cell2 = cells.Find("Items A", null, opts);

if (cell2 != null){
    Console.WriteLine("Name of the cell containing the value: " + cell2.Name);
}else{
    Console.WriteLine("Record not found ");
}

// ابحث عن الخلية التي تحتوي على سلسلة الإدخال
opts.LookAtType = LookAtType.Contains;
Cell cell3 = cells.Find("Data", null, opts);

if (cell3 != null){
    Console.WriteLine("Name of the cell containing the value: " + cell3.Name);
}else{
    Console.WriteLine("Record not found ");
}  


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="حول Aspose.Cells for .NET API" %}}

 يمكن استخدام Aspose.Cells API لإنشاء تنسيقات Microsoft Excel وتحريرها وتحويلها وعرضها بتنسيقات مختلفة. علاوة على ذلك ، يمكن استخدامه لرسم بياني شامل ، وإعداد تقارير قابلة للتطوير وحسابات موثوقة داخل تطبيقات البرامج. Aspose.Cells هو برنامج مستقل API ولا يتطلب أي برامج مثل Microsoft أو OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="عروض توضيحية مباشرة للبحث في CSV عبر الإنترنت" sectionDescription="ابحث عن النص والكلمات والعبارات في مستندات CSV الآن من خلال زيارة [موقع تجريبي مباشر](https://products.aspose.app/cells/search). يحتوي العرض التوضيحي المباشر على الفوائد التالية" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" لا حاجة لتنزيل Aspose API." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" لا حاجة لكتابة أي كود." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="ما عليك سوى تحميل ملفات CSV الخاصة بك." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" تظهر نتيجة البحث على الفور." >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="CSV " readMoreLink="https://docs.fileformat.com/spreadsheet/csv/" >}}
تمثل الملفات ذات امتداد CSV (قيم مفصولة بفواصل) ملفات نصية عادية تحتوي على سجلات بيانات بقيم مفصولة بفواصل. كل سطر في ملف CSV هو رقم قياسي جديد من مجموعة السجلات الموجودة في الملف. يتم إنشاء هذه الملفات عندما يكون نقل البيانات مقصودًا من نظام تخزين إلى آخر. نظرًا لأن جميع التطبيقات يمكنها التعرف على السجلات المفصولة بفاصلة ، فإن استيراد ملفات البيانات هذه إلى قاعدة البيانات يتم بشكل مريح للغاية. يمكن لجميع تطبيقات جداول البيانات تقريبًا مثل Microsoft Excel أو OpenOffice Calc استيراد ملف CSV دون بذل الكثير من الجهد. يتم ترتيب البيانات المستوردة من هذه الملفات في خلايا جدول بيانات لتمثيلها للمستخدم. 

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="تنسيقات البحث الأخرى المدعومة" subTitle="باستخدام C# ، يمكن أيضًا البحث عن تنسيقات أخرى بما في ذلك." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/search/ods/" name="المواد المستنفدة للأوزون" description="ملف جدول بيانات OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/search/tsv/" name="ملف TSV" description="قيم مفصولة بعلامات جدولة" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/search/txt/" name="رسالة قصيرة" description="مستند نصي" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/search/xls/" name="XLS" description="تنسيق Excel الثنائي" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/search/xlsb/" name="XLSB" description="ملف مصنف Excel ثنائي" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/search/xlsm/" name="XLSM" description="ملف Spreasheet" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}