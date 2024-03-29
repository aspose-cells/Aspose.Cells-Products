---
title:  مشاهده TSV فرمت های فایل via .NET
weight: 3090
description: کد منبع C# برای بارگیری، رندر و نمایش اسناد TSV در .NET Framework، .NET Core، Mono یا Xamarin Platforms.
keywords: [C# Aspose.Cells., c# view TSV files., c# how to render TSV document., c# load and display TSV files., TSV File Viewer using C#]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="TSV نمایشگر فایل for .NET" h2="صفحات گسترده Excel و OpenOffice مانند TSV را بدون نیاز به Microsoft Excel یا Office Automation مشاهده کنید." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="TSV" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="TSV" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="نحوه مشاهده فایل TSV با استفاده از C#" %}}

 برای مشاهده فایل TSV استفاده می کنیم
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API که دارای ویژگی های غنی، قدرتمند و آسان برای استفاده است API برای پلت فرم C# برای استفاده با هر Viewer. باز کن
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 مدیر بسته، جستجو کنید
 **Aspose.Cells** 
 و نصب کنید. همچنین می توانید از دستور زیر در کنسول Package Manager استفاده کنید.

{{% blocks/products/pf/agp/code-block title="فرمان کنسول Package Manager" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="مراحل مشاهده TSV از طریق C#" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells مشاهده فایل TSV را برای توسعه دهندگان با تنها چند خط کد آسان می کند.

{{% /blocks/products/pf/agp/text %}}

1.  فایل TSV را در یک نمونه از Workbook بارگیری کنید
1.  یک نمونه از HtmlSaveOptions ایجاد کنید و ویژگی ExportHeadings را روی true تنظیم کنید
1. فایل TSV را با فرمت HTML با استفاده از روش Workbook ذخیره کنید.
1.  HTML حاصل را در مرورگر پیش فرض با Process.Start بارگیری کنید

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="سیستم مورد نیاز" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for .NET در تمام سیستم عامل های اصلی پشتیبانی می شود. فقط مطمئن شوید که پیش نیازهای زیر را دارید.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows یا یک سیستم عامل سازگار با .NET Framework، .NET Core، Mono یا Xamarin Platforms
-  محیط توسعه مانند Microsoft Visual Studio
-  در پروژه خود به DLL Aspose.Cells for .NET ارجاع دهید

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# نمونه کد برای مشاهده فایل TSV" offSpacer="" %}}

```cs

string output = System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".html";

// load the TSV file in an instance of Workbook
var book = new Aspose.Cells.Workbook("template.tsv");
// create an instance of HtmlSaveOptions & set ExportHeadings property to true
var options = new Aspose.Cells.HtmlSaveOptions();
options.ExportHeadings = true;

// save the TSV file in HTML format
book.Save(output, options);
// load resultant HTML in default browser
System.Diagnostics.Process.Start(output);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="درباره Aspose.Cells for .NET API" %}}

 Aspose.Cells API می تواند برای ایجاد، ویرایش، تبدیل و رندر فرمت های اکسل Microsoft به فرمت های مختلف استفاده شود. علاوه بر این، می توان از آن برای نمودارهای جامع، گزارش مقیاس پذیر و محاسبات قابل اعتماد در برنامه های نرم افزاری استفاده کرد. Aspose.Cells یک API مستقل است و به هیچ نرم افزاری مانند Microsoft یا OpenOffice نیاز ندارد.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="برنامه رایگان برای مشاهده TSV" sectionDescription=" دموی زنده ما را بررسی کنید[مشاهده TSV](https://products.aspose.app/cells/viewer/tsv) با مزایای زیر" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" نیازی به دانلود یا تنظیم چیزی نیست" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" نیازی به نوشتن یا کامپایل کد نیست" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" کافیست فایل TSV را آپلود کنید و دکمه \"View\" را بزنید" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" در صورت نیاز فایل TSV را از لینک دانلود کنید" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="TSV" readMoreLink="https://docs.fileformat.com/spreadsheet/tsv/" >}}
فرمت فایل مقادیر جدا شده از تب (TSV) داده‌های جدا شده با برگه‌ها را در قالب متن ساده نشان می‌دهد. فرمت فایل مشابه CSV برای سازماندهی داده ها به صورت ساختاریافته به منظور واردات و صادرات بین برنامه های مختلف استفاده می شود. این فرمت در درجه اول برای واردات/صادرات و تبادل داده در برنامه های کاربردی صفحه گسترده و پایگاه داده استفاده می شود. هر رکورد در یک فایل TSV در یک خط از فایل متنی موجود است که در آن هر مقدار فیلد با یک کاراکتر تب جدا می شود. نوع رسانه برای فرمت فایل TSV text/tab-separated-values است.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="سایر فرمت های نمایشگر پشتیبانی شده" subTitle="با استفاده از C#، می توان بسیاری از فرمت های فایل دیگر از جمله." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/csv/" name="CSV" description="مقادیر جدا شده با کاما" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/ods/" name="ODS" description="فایل صفحه گسترده OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/txt/" name="TXT" description="سند متنی" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xls/" name="XLS" description="فرمت باینری اکسل" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xlsb/" name="XLSB" description="فایل باینری کتاب کار اکسل" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xlsm/" name="XLSM" description="فایل صفحه گسترده" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xlsx/" name="XLSX" description="فایل OOXML اکسل" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xlt/" name="XLT" description="Microsoft قالب اکسل" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xltm/" name="XLTM" description="قالب ماکرو فعال اکسل" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xltx/" name="XLTX" description="قالب Office OpenXML Excel" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
