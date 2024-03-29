---
title:  محافظت و قفل XLSB سند via .NET
weight: 5920
description: کد منبع C# برای قفل کردن فایل XLSB با استفاده از رمز عبور در .NET Framework، .NET Core، Mono یا Xamarin Platforms.
keywords: [C# Aspose.Cells., c# Lock XLSB files., c# How to Protect and lock XLSB document., c# Protect XLSB files., Encrypt XLSB Files using C#]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="فایل های XLSB را از طریق C# رمزگذاری کنید" h2="از صفحات گسترده اکسل با فرمت XLSB با استفاده از کتابخانه .NET محافظت کنید." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSB" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSB" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="نحوه محافظت از فایل XLSB با استفاده از C#" %}}

 به منظور حفاظت از فایل XLSB، ما استفاده خواهیم کرد
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API که دارای ویژگی های غنی، قدرتمند و آسان برای حفاظت از اسناد API برای پلت فرم C# است. باز کن
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 مدیر بسته، جستجو کنید
 **Aspose.Cells** 
 و نصب کنید. همچنین می توانید از دستور زیر در کنسول Package Manager استفاده کنید.

{{% blocks/products/pf/agp/code-block title="Aspose.Cells" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="XLSB را از طریق C# محافظت کنید" %}}

{{% blocks/products/pf/agp/text %}}

 تو نیاز داری
 [aspose.cells.dll](https://downloads.aspose.com/cells/net) 
 در پروژه شما برای اجرای گردش کار زیر ارجاع داده شده است.

{{% /blocks/products/pf/agp/text %}}

1.  کلاس Workbook Instantiate با مسیر فایل XLSB
1.  برای افزودن حفاظت، کاربرگ پیش‌فرض یا هر کاربرگ را دریافت کنید
1.  Protect Worksheet با روش Worksheet.Protect
1.  Protect Workbook با Workbook.روش Protect
1.  نتیجه را در قالب XLSB ذخیره کنید

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="سیستم مورد نیاز" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for .NET در تمام سیستم عامل های اصلی پشتیبانی می شود. فقط مطمئن شوید که پیش نیازهای زیر را دارید.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows یا یک سیستم عامل سازگار با .NET Framework، .NET Core، Mono یا Xamarin Platforms
-  محیط توسعه مانند Microsoft Visual Studio
-  در پروژه خود به DLL Aspose.Cells for .NET ارجاع دهید

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="فرمان" offSpacer="" %}}

```cs

// load the XLSB Excel file 
var book = new Aspose.Cells.Workbook("unlocked.xlsb");

// access the first worksheet
var worksheet = book.Worksheets[0];

// protect the worksheet with password
worksheet.Protect(Aspose.Cells.ProtectionType.All, "password", null);

// protect the whole workbook with password
book.Protect(Aspose.Cells.ProtectionType.All, "password");

// save the modified file in default format
book.Save("protected.xlsb");

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="درباره Aspose.Cells for .NET API" %}}

 Aspose.Cells API می تواند برای ایجاد، ویرایش، تبدیل و رندر فرمت های اکسل Microsoft به فرمت های مختلف استفاده شود. علاوه بر این، می توان از آن برای نمودارهای جامع، گزارش مقیاس پذیر و محاسبات قابل اعتماد در برنامه های نرم افزاری استفاده کرد. Aspose.Cells یک API مستقل است و به هیچ نرم افزاری مانند Microsoft یا OpenOffice نیاز ندارد.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="برنامه رایگان برای محافظت از XLSB" sectionDescription=" دموی زنده ما را بررسی کنید[فایل های XLSB را رمزگذاری کنید](https://products.aspose.app/cells/protect/xlsb) با مزایای زیر" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" نیازی به دانلود یا تنظیم چیزی نیست" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" نیازی به نوشتن یا کامپایل کد نیست" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" فقط فایل XLSB را آپلود کرده و دکمه \"باز کردن\" را فشار دهید" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" فایل XLSB حاصل را از لینک دانلود کنید" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSB" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsb/" >}}
فرمت فایل XLSB فرمت فایل باینری اکسل را مشخص می کند که مجموعه ای از رکوردها و ساختارهایی است که محتوای کتاب کار اکسل را مشخص می کند. محتوا می تواند شامل جداول بدون ساختار یا نیمه ساختاریافته اعداد، متن یا هر دو اعداد و متن، فرمول ها، اتصالات داده خارجی، نمودارها و تصاویر باشد. برخلاف XLSX (که بر اساس فرمت فایل Open XML است)، XLSB فایل باینری کتاب کار اکسل را نشان می دهد. فایل های XLSB را می توان سریعتر خواند و نوشت که آنها را برای کار با فایل های حجیم مفید می کند. XLSB به ندرت برای ذخیره کتاب‌های کار استفاده می‌شود، زیرا XLSX (و قبلاً XLS) رایج‌ترین فرمت‌های فایل انتخابی کاربر برای ذخیره کتاب‌های کار هستند. با شماره Microsoft Office 2007 به بالا قابل باز شدن است.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="سایر فرمت های حفاظتی پشتیبانی شده" subTitle="با استفاده از C# می توان به راحتی از فرمت های دیگر از جمله محافظت کرد." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/ods/" name="ODS" description="فایل صفحه گسترده OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/xls/" name="XLS" description="فرمت باینری اکسل" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/xlsm/" name="XLSM" description="فایل صفحه گسترده" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/xlsx/" name="XLSX" description="فایل OOXML اکسل" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
