---
title:  سند TXT را بدون باز کردن از طریق C++ جستجو کنید
weight: 5090
description: C++ کد مثال برای جستجوی کلمات با الگو در فایل TXT در C++ Runtime Environment برای Windows 32 بیتی، Windows 64 بیتی و لینوکس 64 بیتی.
keywords: [C++ Aspose.Cells., C++ search words with pattern in txt file., C++ find words with pattern in txt file., C++ search string with pattern in txt file., C++ find words with pattern in txt file., C++ search words in txt file., C++ find words in txt file., C++ search string in txt file., C++ find string in txt file]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="فرمت های TXT را در C++ جستجو کنید" h2="جستجوی سند بومی و با کارایی بالا TXT با استفاده از API های سمت سرور Aspose.Cells for C++، بدون استفاده از نرم افزارهایی مانند Microsoft یا Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="TXT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="نحوه جستجوی فایل TXT با استفاده از C++" %}}

 برای جستجوی فایل TXT، از
 [Aspose.Cells for C++](https://products.aspose.com/cells/cpp) 
API که یک پلتفرم جستجوی اسناد با ویژگی های غنی، قدرتمند و آسان برای استفاده است API for C++. شما می توانید آخرین نسخه آن را مستقیما دانلود کنید، فقط باز کنید
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 مدیر بسته، جستجو کنید
 **Aspose.Cells.Cpp** 
 و نصب کنید. همچنین می توانید از دستور زیر در کنسول Package Manager استفاده کنید.

{{% blocks/products/pf/agp/code-block title="فرمان" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="مراحل جستجوی فایل های TXT در C++" %}}

{{% blocks/products/pf/agp/text %}}

 جستجوی اولیه سند با استفاده از API های Aspose.Cells را می توان تنها با چند خط کد انجام داد.

{{% /blocks/products/pf/agp/text %}}

+ فایل TXT را با نمونه سازی کلاس Workbook بارگیری کنید.
+ کلاس ReplaceOptions را Instantiate کنید.
+ تنظیم الگوی مورد نیاز مانند SetCaseSensitive (مقدار bool)، SetMatchEntireCellContents (مقدار bool).
از روش Workbook::Replace(...) با گزینه های مربوطه استفاده کنید.
+ فایل TXT را با استفاده از روش Workbook::Save(...) ذخیره کنید.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="سیستم مورد نیاز" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for C++ در تمام سیستم عامل ها و سیستم عامل های اصلی پشتیبانی می کند. لطفا مطمئن شوید که پیش نیازهای زیر را دارید.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows یا یک سیستم عامل سازگار با C++ Runtime Environment برای Windows 32 بیتی، Windows 64 بیتی و لینوکس 64 بیتی.
-  در پروژه خود به DLL Aspose.Cells for C++ اشاره کنید.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="جستجوی فایل TXT - C++" offSpacer="" %}}

```cs

Aspose::Cells::Startup();

// Source directory path.
U16String srcDir(u"SourcePath\\");

// Output directory path.
U16String outDir(u"OutputPath\\");

// Load TXT file
Workbook  wkb(srcDir + u"sourceFile.txt");

// Create an instance of the IReplaceOptions class
ReplaceOptions replaceOptions;

// Set case sensitivity option
replaceOptions.SetCaseSensitive(false);

// Set text matching option
replaceOptions.SetMatchEntireCellContents(false);

// Replace text
wkb.Replace(u"Text to find", u"Text replacement", replaceOptions);

// Save as TXT file
wkb.Save(outDir + u"outputFile.txt");

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

    {{< blocks/products/pf/agp/demobox sectionTitle="آنلاین TXT جستجوی دموهای زنده" sectionDescription=" در حال حاضر با مراجعه به ما، متن، کلمات، عبارات را در اسناد TXT جستجو کنید[وب سایت Live Demos](https://products.aspose.app/cells/search). نسخه ی نمایشی زنده دارای مزایای زیر است" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" بدون نیاز به دانلود Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" نیازی به نوشتن هیچ کدی نیست." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text="فقط فایل های TXT خود را آپلود کنید." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" نتیجه جستجو فوراً ظاهر می شود." >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="TXT " readMoreLink="https://docs.fileformat.com/word-processing/txt/" >}}
یک فایل با پسوند 0.TXT یک سند متنی را نشان می دهد که حاوی متن ساده به شکل خطوط است. پاراگراف ها در یک سند متنی با بازگردانی های حمل و نقل شناسایی می شوند و برای چیدمان بهتر محتویات فایل استفاده می شوند. یک سند متنی استاندارد را می توان در هر ویرایشگر متن یا برنامه پردازش کلمه در سیستم عامل های مختلف باز کرد. تمام متن موجود در چنین فایلی در قالب قابل خواندن توسط انسان است و با ترتیب کاراکترها نشان داده می شود.

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="سایر اسناد جستجوی پشتیبانی شده" subTitle="با استفاده از C++ می توان فایل های دیگر از جمله." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/csv/" name="CSV" description="مقادیر جدا شده با کاما" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/ods/" name="ODS" description="فایل صفحه گسترده OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/tsv/" name="TSV" description="مقادیر جدا شده از تب" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/xls/" name="XLS" description="فرمت باینری اکسل" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/xlsb/" name="XLSB" description="فایل باینری کتاب کار اکسل" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/xlsm/" name="XLSM" description="فایل صفحه گسترده" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
