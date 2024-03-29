---
title:  Callouts را در اکسل via .NET قرار دهید
weight: 360
description: C# نمونه کد برای افزودن یا درج Callouts به اکسل با استفاده از کتابخانه .NET. از این کد برای ایجاد Callouts در MS Excel در VB.NET، Asp.NET یا هر برنامه مبتنی بر .NET استفاده کنید.
keywords: [C# Aspose.Cells., c# add Callouts shape., c# insert Callouts shape., c# create Callouts shape]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Callouts را در اکسل via .NET قرار دهید" h2="Callouts را با استفاده از Aspose.Cells\' API بدون هیچ نرم افزاری مانند Microsoft یا Open Office، Adobe PDF و غیره درج کنید." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="نحوه درج Callouts در فایل اکسل با استفاده از C#" %}}

 برای درج Callouts در فایل اکسل، از آن استفاده می کنیم
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API که دارای ویژگی های غنی، قدرتمند و آسان برای دستکاری اسناد و تقسیم کننده API برای پلت فرم C# است. باز کن
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 مدیر بسته، جستجو کنید
 Aspose.Cells 
 و نصب کنید. همچنین می توانید از دستور زیر در کنسول Package Manager استفاده کنید.

{{% blocks/products/pf/agp/code-block title="فرمان" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="مراحل درج Callouts به فایل اکسل از طریق C#" %}}

{{% blocks/products/pf/agp/text %}}

شما به aspose.cells.dll نیاز دارید تا گردش کار زیر را در محیط خود امتحان کنید.

{{% /blocks/products/pf/agp/text %}}

+ نمونه سازی یک شی Workbook. (یا -> فایل XLSX را با مسیر کامل بارگیری کنید.)
+ کاربرگ را از طریق فهرست آن انتخاب کنید.
 + استفاده کنید[روش اضافه کردن](https://reference.aspose.com/cells/net/aspose.cells.drawing/shapecollection/addautoshape) برای درج Callouts در کاربرگ انتخابی
+ کتاب کار را با فرمت XLSX ذخیره کنید.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="سیستم مورد نیاز" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for .NET در تمام سیستم عامل های اصلی پشتیبانی می شود. فقط مطمئن شوید که پیش نیازهای زیر را دارید.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows یا یک سیستم عامل سازگار با .NET Framework، .NET Core، Mono یا Xamarin Platforms
-  محیط توسعه مانند Microsoft Visual Studio
-  در پروژه خود به DLL Aspose.Cells for .NET اضافه کنید - با استفاده از دکمه دانلود بالا از NuGet نصب کنید

{{% /blocks/products/pf/agp/feature-section-col %}}

کد نمونه زیر نحوه درج یک "حباب فکر: ابر" را نشان می دهد. برای انواع بیشتر، لطفاً به "نمای کلی انواع Callout" در زیر مراجعه کنید.

{{% blocks/products/pf/agp/code-block title="درج Callouts - C#" offSpacer="" %}}

{{< gist "aspose-cells-gists" "59a1901d62ea9ceb08456a818431a898" "InsertCalloutsIntoWorksheet.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

<div class="container-fluid features-section bg-gray">
 <a class="anchor" id="features" name="features">
 </a>
 <div class="row">
  <div class="container">
   <h2 class="pr-ft">
 مروری بر انواع Callout
   </h2>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-callouts-to-excel/speech_bubble_rectangle.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.RectangularCallout
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-callouts-to-excel/speech_bubble_rectangle_with_corners_rounded.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.RoundedRectangularCallout
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-callouts-to-excel/speech_bubble_oval.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.OvalCallout
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-callouts-to-excel/thought_bubble_cloud.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.CloudCallout
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-callouts-to-excel/line.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.LineCalloutWithBorder1
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-callouts-to-excel/bent_line.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
AutoShapeType.LineCalloutWithBorder2
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-callouts-to-excel/double_bent_line.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.LineCalloutWithBorder3
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-callouts-to-excel/line_with_accent_bar.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.LineCalloutWithAccentBar1
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-callouts-to-excel/bent_line_with_accent_bar.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.LineCalloutWithAccentBar2
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-callouts-to-excel/double_bent_line_with_accent_bar.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.LineCalloutWithAccentBar3
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-callouts-to-excel/line_with_no_border.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.LineCalloutNoBorder1
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-callouts-to-excel/bent_line_with_no_border.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.LineCalloutNoBorder2
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-callouts-to-excel/double_bent_line_with_no_border.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.LineCalloutNoBorder3
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-callouts-to-excel/line_with_border_and_accent_bar.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.LineCalloutWithBorderAndAccentBar1
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-callouts-to-excel/bent_line_with_border_and_accent_bar.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.LineCalloutWithBorderAndAccentBar2
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-callouts-to-excel/double_bent_line_with_border_and_accent_bar.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.LineCalloutWithBorderAndAccentBar3
    </p>
   </div>
  </div>
 </div>
</div>

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="درباره Aspose.Cells for .NET API" %}}

Aspose.Cells API می تواند برای ایجاد، ویرایش، تبدیل و رندر فرمت های اکسل Microsoft به فرمت های مختلف استفاده شود. علاوه بر این، می توان از آن برای نمودارهای جامع، گزارش مقیاس پذیر و محاسبات قابل اعتماد در برنامه های نرم افزاری استفاده کرد. Aspose.Cells یک API مستقل است و به هیچ نرم افزاری مانند Microsoft یا OpenOffice نیاز ندارد.

{{% /blocks/products/pf/agp/content %}}



<!-- aboutfile Ends -->
<!--
{{< blocks/products/pf/agp/other-supported-section title="Other Supported Splitting Formats" subTitle="Using C#, One can also split large file into chunks of many other file formats including." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/splitter/ods/" name="ODS" description="OpenDocument Spreadsheet File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/splitter/xls/" name="XLS" description="Excel Binary Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/splitter/xlsb/" name="XLSB" description="Binary Excel Workbook File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/splitter/xlsm/" name="XLSM" description="Spreadsheet File" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

-->

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
