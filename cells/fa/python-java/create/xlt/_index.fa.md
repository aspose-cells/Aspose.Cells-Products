---
title: ایجاد XLT - ایجاد فایل XLT در Python
description: Aspose اکسل. Python اکسل. Python فایل XLT را به سرعت و به راحتی با Aspose.Cells ایجاد کنید. فایل XLT را با استفاده از کتابخانه اکسل Python ایجاد کنید. XLT را در کتابخانه اکسل Python ایجاد کنید. Python XLT سازنده.
keywords: [Aspose Python Excel., Python Aspose.Cells., Python Create XLT file., Generate XLT file in Python Excel Library., Create XLT file using Python Excel Library., Write data to XLT file via Python Excel Library., Create a XLT file in Python Excel Library., Python Generate a XLT file., Python XLT Creater]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="فایل XLT را در کتابخانه اکسل Python ایجاد کنید" h2="کتابخانه اکسل پرسرعت Python برای ایجاد فایل XLT. این یک راه حل نرم افزاری حرفه ای برای واردات و صادرات XLSX، PDF و بسیاری از فرمت های دیگر با استفاده از Python است." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-python-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLT" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Python" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-python-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/pythonjava" installationsDocsLink="https://docs.aspose.com/cells/pythonjava" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://releases.aspose.com/cells/python-java/" learnAsLink="https://docs.aspose.com/cells/pythonjava" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="ایجاد فایل XLT با استفاده از کتابخانه اکسل Python" %}}

 چگونه فایل XLT ایجاد کنیم؟ با کتابخانه اکسل Aspose.Cells for Python via Java به راحتی می توانید فایل XLT را به صورت برنامه نویسی با چند خط کد ایجاد کنید.[Aspose.Cells for Python](https://pypi.org/project/aspose-cells)قادر به ساخت برنامه های چند پلتفرمی با قابلیت تولید، تغییر، تبدیل، رندر و چاپ تمام فایل های اکسل است. Python اکسل API نه تنها بین فرمت های صفحه گسترده تبدیل می شود، بلکه می تواند فایل های اکسل را به صورت تصویر، PDF, HTML, ODS, CSV, SVG, JSON, WORD, PPT و موارد دیگر ارائه دهد، بنابراین آن را به گزینه ای عالی برای تبادل اسناد در قالب های استاندارد صنعتی تبدیل می کند.

{{% /blocks/products/pf/agp/content %}}



{{% blocks/products/pf/agp/content h2="نحوه ایجاد XLT در کتابخانه اکسل Python" %}}

{{% blocks/products/pf/agp/text %}}

 ایجاد، بارگیری، تغییر و تبدیل فایل‌های XLT در برنامه‌های مختلف گزارش‌دهی برای پردازش داده‌ها، تنها در چند خط کد برای توسعه‌دهندگان آسان است.

{{% /blocks/products/pf/agp/text %}}

1.  asposecells را در فایل کد خود وارد کنید.
1.  نمونه کلاس Workbook را ایجاد کنید.
1.  به اولین کاربرگ کتاب کار دسترسی پیدا کنید.
1. سلول(های) مورد نظر کاربرگ را دریافت کرده و مقدار را در سلول(ها) وارد کنید.
1.  از روش Save برای ذخیره کتاب کار به عنوان فایل XLT استفاده کنید.

{{% blocks/products/pf/agp/code-block title="کد نمونه نحوه ایجاد فایل XLT در کتابخانه اکسل Python را نشان می دهد." offSpacer="" %}}

```cs

import jpype
import asposecells
jpype.startJVM()
from asposecells.api import Workbook, FileFormatType

# Create Workbook object.
workbook = Workbook(FileFormatType.XLT)

# Access the first worksheet of the workbook.
worksheet = workbook.getWorksheets().get(0)

# Get the desired cell(s) of the worksheet and input the value into the cell(s).
worksheet.getCells().get("A1").putValue("ColumnA")
worksheet.getCells().get("B1").putValue("ColumnB")
worksheet.getCells().get("A2").putValue("ValueA")
worksheet.getCells().get("B2").putValue("ValueB")

# Save the workbook as XLT file.
workbook.save("output.xlt")

jpype.shutdownJVM()

```

{{% /blocks/products/pf/agp/code-block %}}
{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="Python کتابخانه اکسل برای ایجاد فایل XLT" %}}

{{% blocks/products/pf/agp/text %}}

سه گزینه برای نصب "Aspose.Cells for Python via Java" بر روی سیستم شما وجود دارد. لطفاً یکی را انتخاب کنید که شبیه نیاز شما باشد و دستورالعمل های گام به گام را دنبال کنید:

{{% /blocks/products/pf/agp/text %}}

1.  Aspose.Cells for Python via Java را در Windows نصب کنید.[مستندات](https://docs.aspose.com/cells/python-java/getting-started/#windows)
1.  Aspose.Cells for Python via Java را در لینوکس نصب کنید. دیدن[مستندات](https://docs.aspose.com/cells/python-java/getting-started/#linux)
1.  Aspose.Cells for Python via Java را در macOS نصب کنید. دیدن[مستندات](https://docs.aspose.com/cells/python-java/getting-started/#macos)

{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="سیستم مورد نیاز" %}}

{{% blocks/products/pf/agp/text %}}

Aspose.Cells for Python via Java مستقل از پلتفرم API است و می تواند بر روی هر پلتفرمی (Windows، لینوکس و MacOS) استفاده شود، فقط مطمئن شوید که سیستم دارای Java 1.8 یا بالاتر است،[Python](https://www.python.org/downloads/) 3.5 یا بالاتر

{{% /blocks/products/pf/agp/text %}}

-  Java را نصب کنید و آن را به متغیر محیطی PATH اضافه کنید، به عنوان مثال:<code>PATH=C:\Program Files\Java\jdk1.8.0_131;</code>.
-  نصب Aspose.Cells for Python via Java از<a href="https://pypi.org/project/aspose-cells/">pypi</a> ، از دستور به صورت زیر استفاده کنید:<code>$ pip install aspose-cells</code>.

{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->
    {{< blocks/products/pf/agp/about-file-section >}}
        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLT" readMoreLink="https://docs.fileformat.com/spreadsheet/xlt/" >}}فایل‌های با پسوند xlt. فایل‌های قالبی هستند که با Microsoft Excel ایجاد شده‌اند که یک برنامه صفحه‌گسترده است که به عنوان بخشی از مجموعه آفیس Microsoft ارائه می‌شود. Microsoft Office 97-2003 از ایجاد فایل های جدید XLT و همچنین باز کردن آنها پشتیبانی می کند. آخرین نسخه اکسل همچنان قادر به باز کردن این فایل های قالب قدیمی است. چنین فایل قالبی برای ایجاد سریع فایل‌های اکسل جدید با داده‌ها و تنظیمات پیش‌فرض مانند قالب‌بندی صفحه، اندازه فونت، حاشیه‌ها، نمودارها و غیره استفاده می‌شود که می‌توانند بیشتر به عنوان فایل‌های xls. جدید ذخیره شوند.{{< /blocks/products/pf/agp/i18n/about-file-text >}}
    {{< /blocks/products/pf/agp/about-file-section >}}
<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="دیگر تولید صفحه گسترده پشتیبانی شده" subTitle="شما همچنین می توانید سایر فرمت های اکسل Microsoft از جمله تعداد کمی از آنها را ایجاد کنید." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xls/" name="XLS" description="Microsoft صفحه گسترده اکسل (قدیمی)" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xlsx/" name="XLSX" description="XML Workbook را باز کنید" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xlsb/" name="XLSB" description="کتاب کار باینری اکسل" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xlsm/" name="XLSM" description="صفحه گسترده ماکرو فعال" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xlt/" name="XLT" description="قالب اکسل 97 - 2003" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xltx/" name="XLTX" description="قالب اکسل" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xltm/" name="XLTM" description="قالب ماکرو فعال اکسل" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/csv/" name="CSV" description="مقادیر جدا شده با کاما" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/tsv/" name="TSV" description="مقادیر جدا شده از برگه ها" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/ods/" name="ODS" description="صفحه گسترده OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/pdf/" name="PDF" description="فرمت سند قابل حمل" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/html/" name="HTML" description="زبان نشانه گذاری فرا متنی" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
