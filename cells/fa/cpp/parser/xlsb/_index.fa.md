---
title: استخراج متن و تصاویر از سند XLSB از طریق C++
weight: 3140
description: C++ کد نمونه برای استخراج متن و تصاویر از فایل XLSB در C++ Runtime Environment برای Windows 32 بیتی، Windows 64 بیتی و لینوکس 64 بیتی.
keywords: [C++ Aspose.Cells., C++ Extract text and images from XLSB file., C++ How to Parse XLSB File., C++ Extract text from XLSB file., Extract images from XLSB file using C++]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="فرمت های XLSB را در C++ تجزیه کنید" h2="تجزیه اسناد بومی و با کارایی بالا XLSB با استفاده از APIهای Aspose.Cells for C++ سمت سرور، بدون استفاده از نرم افزارهایی مانند Microsoft یا Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLSB" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="نحوه تجزیه فایل XLSB با استفاده از C++" %}}

 به منظور تجزیه فایل XLSB، از آن استفاده می کنیم[Aspose.Cells for C++](https://products.aspose.com/cells/cpp) API که یک پلتفرم تجزیه اسناد API for C++ با ویژگی های غنی، قدرتمند و آسان برای استفاده است. شما می توانید آخرین نسخه آن را مستقیما دانلود کنید، فقط باز کنید[NuGet](https://www.nuget.org/packages/aspose.cells) مدیر بسته، جستجو کنید**Aspose.Cells.Cpp** و نصب کنید. همچنین می توانید از دستور زیر در کنسول Package Manager استفاده کنید.

{{% blocks/products/pf/agp/code-block title="فرمان" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="مراحل تجزیه فایل های XLSB در C++" %}}

{{% blocks/products/pf/agp/text %}}

 تجزیه سند پایه با[Aspose.Cells for C++](https://products.aspose.com/cells/cpp)API ها را می توان تنها با چند خط کد انجام داد. متن و تصاویر را از فایل های Microsoft Excel XLS، XLSX، XLSM، XLSB و OpenDocument ODS تجزیه کنید.

{{% /blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="سیستم مورد نیاز" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for C++ در تمام سیستم عامل ها و سیستم عامل های اصلی پشتیبانی می کند. لطفا مطمئن شوید که پیش نیازهای زیر را دارید.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows یا یک سیستم عامل سازگار با C++ Runtime Environment برای Windows 32 بیتی، Windows 64 بیتی و لینوکس 64 بیتی.
-  در پروژه خود به DLL Aspose.Cells for C++ اشاره کنید.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="فایل های پارس XLSB - C++" offSpacer="" %}}

```cs

Aspose::Cells::Startup();

// extract images from Worksheets 
// open a template Excel file
Workbook workbook(u"sampleExtractImagesFromWorksheets.xlsb");

// get the first worksheet
Worksheet worksheet = workbook.GetWorksheets().Get(0);

// get the first Picture in the first worksheet
Picture pic = worksheet.GetPictures().Get(0);

// Note: you may evaluate the image format before specifying the image path
// define ImageOrPrintOptions
ImageOrPrintOptions printoption;

// specify the image format
printoption.SetImageType(ImageType::Jpeg);

// save the image
pic.ToImage(u"outputExtractImagesFromWorksheets.jpg", printoption);

Aspose::Cells::Cleanup();

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="درباره Aspose.Cells for C++ API" %}}

 Aspose.Cells API می تواند برای ایجاد، ویرایش، تبدیل و رندر فرمت های اکسل Microsoft به فرمت های مختلف استفاده شود. علاوه بر این، می توان از آن برای نمودارهای جامع، گزارش مقیاس پذیر و محاسبات قابل اعتماد در برنامه های نرم افزاری استفاده کرد. Aspose.Cells یک API مستقل است و به هیچ نرم افزاری مانند Microsoft یا OpenOffice نیاز ندارد.



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="آنلاین XLSB Parser Live Demos" sectionDescription="همین حالا با مراجعه به ما، متن و تصاویر را از اسناد XLSB استخراج کنید[وب سایت Live Demos](https://products.aspose.app/cells/parser). نسخه ی نمایشی زنده دارای مزایای زیر است" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" بدون نیاز به دانلود Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" نیازی به نوشتن هیچ کدی نیست." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" فقط فایل های XLSB خود را آپلود کنید." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" فوراً تجزیه خواهد شد." >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSB" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsb/" >}}
فرمت فایل XLSB فرمت فایل باینری اکسل را مشخص می کند که مجموعه ای از رکوردها و ساختارهایی است که محتوای کتاب کار اکسل را مشخص می کند. محتوا می تواند شامل جداول بدون ساختار یا نیمه ساختاریافته اعداد، متن یا هر دو اعداد و متن، فرمول ها، اتصالات داده خارجی، نمودارها و تصاویر باشد. برخلاف XLSX (که بر اساس فرمت فایل Open XML است)، XLSB فایل باینری کتاب کار اکسل را نشان می دهد. فایل های XLSB را می توان سریعتر خواند و نوشت که آنها را برای کار با فایل های حجیم مفید می کند. XLSB به ندرت برای ذخیره کتاب‌های کار استفاده می‌شود، زیرا XLSX (و قبلاً XLS) رایج‌ترین فرمت‌های فایل انتخابی کاربر برای ذخیره کتاب‌های کار هستند. با شماره Microsoft Office 2007 به بالا قابل باز شدن است.

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="سایر اسناد تجزیه و تحلیل پشتیبانی شده" subTitle="با استفاده از C++ می توان به راحتی فرمت های دیگر از جمله را تجزیه کرد." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/parser/ods/" name="ODS" description="فایل صفحه گسترده OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/parser/xls/" name="XLS" description="فرمت باینری اکسل" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/parser/xlsm/" name="XLSM" description="فایل صفحه گسترده" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/parser/xlsx/" name="XLSX" description="فایل OOXML اکسل" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
