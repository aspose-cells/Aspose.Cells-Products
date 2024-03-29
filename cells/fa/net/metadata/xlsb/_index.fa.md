---
title:  مشاهده یا ویرایش XLSB فایل های فراداده via .NET
weight: 7890
description: کد منبع C# برای ویرایش یا مشاهده فراداده با فرمت XLSB در .NET Framework، .NET Core، Mono یا Xamarin Platforms.
keywords: [C# Aspose.Cells., c# view xlsb metadata., c# add xlsb metadata., c# insert xlsb metadata., c# edit xlsb metadata., c# remove xlsb metadata., c# extract xlsb metadata., c# modify xlsb metadata]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Extract XLSB Metadata via .NET" h2="برنامه های .NET خود را بسازید تا با استفاده از API های سمت سرور، متادیتا را از فایل های XLSB اضافه، ویرایش، حذف یا استخراج کنید." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSB" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="نحوه استخراج فراداده XLSB با استفاده از C#" %}}

به منظور استخراج فراداده XLSB، از آن استفاده می کنیم
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API که یک ابرداده سند با ویژگی های غنی، قدرتمند و آسان برای استفاده است API برای پلت فرم C#. باز کن
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 مدیر بسته، جستجو کنید
 **Aspose.Cells** 
 و نصب کنید. همچنین می توانید از دستور زیر در کنسول Package Manager استفاده کنید.

{{% blocks/products/pf/agp/code-block title="فرمان" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="مراحل استخراج فراداده XLSB از طریق C#" %}}

{{% blocks/products/pf/agp/text %}}

 به اطلاعات مفید ذخیره شده در فایل XLSB از جمله زمان دریافت فایل XLSB، پردازش، زمان بندی و غیره دسترسی داشته باشید.

{{% /blocks/products/pf/agp/text %}}

+ XLSB را با یک نمونه از Workbook بارگیری کنید
+ مجموعه BuiltInDocumentProperties شی Workbook را دریافت کنید
+ تکرار روی مجموعه
+ نمایش نام، نوع و مقدار دارایی

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="سیستم مورد نیاز" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for .NET در تمام سیستم عامل های اصلی پشتیبانی می شود. فقط مطمئن شوید که پیش نیازهای زیر را دارید.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows یا یک سیستم عامل سازگار با .NET Framework، .NET Core، Mono یا Xamarin Platforms.
-  محیط توسعه مانند Microsoft Visual Studio.
-  در پروژه خود به DLL Aspose.Cells for .NET اشاره کنید.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="استخراج فراداده XLSB - C#" offSpacer="" %}}

```cs

// load the XLSB with an instance of Workbook
var book = new Aspose.Cells.Workbook("template.xlsb");
// iterate over the BuiltInDocumentProperties collection
foreach (Aspose.Cells.Properties.DocumentProperty property in book.Worksheets.BuiltInDocumentProperties)
{
    Console.WriteLine($"\tType:\t{property.Type}");

    // Some properties may store multiple values
    if (property.Value is Array)
    {
        foreach (object value in property.Value as Array)
            Console.WriteLine($"\tValue:\t\"{value}\"");
    }
    else
    {
        Console.WriteLine($"\tValue:\t\"{property.Value}\"");
    }
}  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="درباره Aspose.Cells for .NET API" %}}

 Aspose.Cells API می تواند برای ایجاد، ویرایش، تبدیل و رندر فرمت های اکسل Microsoft به فرمت های مختلف استفاده شود. علاوه بر این، می توان از آن برای نمودارهای جامع، گزارش مقیاس پذیر و محاسبات قابل اعتماد در برنامه های نرم افزاری استفاده کرد. Aspose.Cells یک API مستقل است و به هیچ نرم افزاری مانند Microsoft یا OpenOffice نیاز ندارد.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="فراداده XLSB را از طریق برنامه آنلاین استخراج کنید" sectionDescription=" مشاهده و ویرایش فراداده به اسناد XLSB با استفاده از ما[دموهای زنده](https://products.aspose.app/cells/metadata) با مزایای زیر" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" نیازی به دانلود یا تنظیم چیزی نیست" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" نیازی به نوشتن هیچ کدی نیست" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" فقط فایل XLSB خود را آپلود کنید و ویژگی های سند را ویرایش کنید" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" بلافاصله لینک دانلود فایل حاصل را دریافت کنید" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSB" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsb/" >}}
فرمت فایل XLSB فرمت فایل باینری اکسل را مشخص می کند که مجموعه ای از رکوردها و ساختارهایی است که محتوای کتاب کار اکسل را مشخص می کند. محتوا می تواند شامل جداول بدون ساختار یا نیمه ساختاریافته اعداد، متن یا هر دو اعداد و متن، فرمول ها، اتصالات داده خارجی، نمودارها و تصاویر باشد. برخلاف XLSX (که بر اساس فرمت فایل Open XML است)، XLSB فایل باینری کتاب کار اکسل را نشان می دهد. فایل های XLSB را می توان سریعتر خواند و نوشت که آنها را برای کار با فایل های حجیم مفید می کند. XLSB به ندرت برای ذخیره کتاب‌های کار استفاده می‌شود، زیرا XLSX (و قبلاً XLS) رایج‌ترین فرمت‌های فایل انتخابی کاربر برای ذخیره کتاب‌های کار هستند. با شماره Microsoft Office 2007 به بالا قابل باز شدن است.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="سایر فرمت های فراداده پشتیبانی شده" subTitle="با استفاده از C#، می توان ابرداده های بسیاری از فرمت های دیگر از جمله را نیز دستکاری کرد." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/metadata/ods/" name="ODS" description="فایل صفحه گسترده OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/metadata/xls/" name="XLS" description="فرمت باینری اکسل" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/metadata/xlsm/" name="XLSM" description="فایل صفحه گسترده" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/metadata/xlsx/" name="XLSX" description="فایل OOXML اکسل" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
