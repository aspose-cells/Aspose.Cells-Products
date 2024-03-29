---
title:  تبدیل XLT به آرایه بایتی از طریق C#
weight: 7690
description: C# نمونه کد تبدیل XLT به آرایه بایت. از این کد برای تبدیل اکسل XLT به آرایه بایت در VB.NET، Asp.NET یا هر برنامه مبتنی بر .NET استفاده کنید.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="تبدیل XLT به آرایه بایتی از طریق C#" h2="تبدیل بومی و با کارایی بالا Microsoft Excel XLT به آرایه بایت یا برعکس برای پردازش داده های صفحات گسترده با استفاده از API های سمت سرور .NET." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PDF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="" %}}

 آرایه بایت برای پردازش یا ذخیره داده ها مفید است. شما می توانید فایل XLT را به آرایه بایت و همچنین یک**آرایه بایت به XLT** سند با استفاده از زبان C#. برای تبدیل XLT به آرایه بایتی، از آن استفاده می کنیم
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API که ویژگی های مختلفی را برای دستکاری و تبدیل اسناد با استفاده از پلت فرم .NET ارائه می دهد.
{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="نحوه تبدیل XLT به آرایه بایتی از طریق C#" %}}

{{% blocks/products/pf/agp/text %}}

 برای توسعه دهندگان آسان است که فایل های XLT را به آرایه بایتی برای کارهای دستکاری بیشتر تنها در چند خط کد بارگذاری و تبدیل کنند.

{{% /blocks/products/pf/agp/text %}}

1.  فضای نام را در فایل کلاس خود قرار دهید
1.  فایل ورودی XLT را با استفاده از Workbook بارگیری کنید
1.  شی MemoryStream را مقداردهی کنید
1.  تبدیل داده های جریان به آرایه بایت
1.  داده ها را طبق نیاز خود پردازش کنید

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="سیستم مورد نیاز" %}}

{{% blocks/products/pf/agp/text %}}

فقط مطمئن شوید که سیستم دارای Microsoft Windows یا یک سیستم عامل سازگار با .NET Framework، .NET Core، Windows Azure، Mono یا Xamarin پلتفرم های 876 استودیو 3076 و همچنین محیط های توسعه است.

{{% /blocks/products/pf/agp/text %}}

-  از خط فرمان به عنوان نصب کنید<code>nuget install Aspose.Cells</code> یا از طریق کنسول Package Manager ویژوال استودیو با<code>Install-Package Aspose.Cells</code>.
-  متناوبا، نصب کننده آفلاین MSI یا همه DLL های موجود در یک فایل ZIP را از آن دریافت کنید<a href="https://downloads.aspose.com/cells/net">دانلودها</a>

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="این کد نمونه XLT به آرایه بایت C# تبدیل را نشان می دهد" offSpacer="" %}}

```cs
Workbook workbook = new Workbook("sourceFile.xlt");

//Save the workbook in memory stream
MemoryStream ms = new MemoryStream();

workbook.Save(ms, SaveFormat.Xlt);

//Read bytes from memory stream
byte[] byte_array = new byte[ms.Length];
ms.Read(byte_array, 0, byte_array.Length);

// Process the memory stream byte array data as of your requirement 

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<!-- aboutfile Starts -->
      
     {{% blocks/products/pf/agp/content h2="" %}}

یک کتابخانه برنامه نویسی صفحه گسترده اکسل که قادر به ساخت برنامه های کاربردی چند پلتفرمی با توانایی تولید، تغییر، تبدیل، رندر و چاپ همه فایل های اکسل است. .NET اکسل API نه تنها بین فرمت های صفحه گسترده تبدیل می شود، بلکه می تواند فایل های اکسل شامل XLT را به صورت تصویر، PDF، HTML، ODS، ODS و موارد دیگر را رندر کند، در نتیجه آن را به یک فرمت استاندارد برای تبادل اسناد تبدیل می کند.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLT" readMoreLink="https://docs.fileformat.com/spreadsheet/xlt/" >}}
فایل‌های با پسوند xlt. فایل‌های قالبی هستند که با Microsoft Excel ایجاد شده‌اند که یک برنامه صفحه‌گسترده است که به عنوان بخشی از مجموعه آفیس Microsoft ارائه می‌شود. Microsoft Office 97-2003 از ایجاد فایل های جدید XLT و همچنین باز کردن آنها پشتیبانی می کند. آخرین نسخه اکسل همچنان قادر به باز کردن این فایل های قالب قدیمی است. چنین فایل قالبی برای ایجاد سریع فایل‌های اکسل جدید با داده‌ها و تنظیمات پیش‌فرض مانند قالب‌بندی صفحه، اندازه فونت، حاشیه‌ها، نمودارها و غیره استفاده می‌شود که می‌توانند بیشتر به عنوان فایل‌های xls. جدید ذخیره شوند.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

           {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="سایر تبدیل های پشتیبانی شده" subTitle="همچنین می‌توانید فرمت‌های فایل دیگر را به آرایه بایتی یا برعکس تبدیل کنید، از جمله تعدادی که در زیر ذکر شده‌اند." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xls-to-byte-array/" name="XLS به آرایه بایت" description="Microsoft صفحه گسترده اکسل (قدیمی)" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlsx-to-byte-array/" name="XLSX به آرایه بایت" description="XML Workbook را باز کنید" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlsb-to-byte-array/" name="XLSB به آرایه بایت" description="کتاب کار باینری اکسل" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlsm-to-byte-array/" name="XLSM به آرایه بایت" description="صفحه گسترده ماکرو فعال" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlt-to-byte-array/" name="XLT به آرایه بایت" description="قالب اکسل 97 - 2003" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xltx-to-byte-array/" name="XLTX به آرایه بایت" description="قالب اکسل" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xltm-to-byte-array/" name="XLTM به آرایه بایت" description="قالب ماکرو فعال اکسل" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/csv-to-byte-array/" name="CSV به آرایه بایت" description="مقادیر جدا شده با کاما" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/tsv-to-byte-array/" name="TSV به آرایه بایت" description="Tab Seperated Values" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/ods-to-byte-array/" name="ODS به آرایه بایت" description="صفحه گسترده OpenDocument" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xls-to-pdf/" name="XLS الی PDF" description="فرمت سند قابل حمل" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xls-to-html/" name="XLS الی HTML" description="زبان نشانه گذاری فرا متنی" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlsx-to-pdf/" name="XLSX الی XPS" description="Microsoft اکسل OOXML فایل اکسل" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlsx-to-html/" name="XLSX الی HTML" description="فایل OOXML اکسل" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlsx-to-svg/" name="XLSX الی SVG" description="گرافیک برداری مقیاس پذیر" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xls-to-jpeg/" name="XLS الی JPEG" description="JPEG تصویر" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
