---
title: مدیریت فراداده فایل اکسل از طریق C++
description: مشاهده، افزودن، ویرایش، حذف یا استخراج فراداده فایل های Excel با استفاده از کتابخانه C++
keywords: [C++ Aspose.Cells., C++ view excel metadata., C++ add excel metadata., C++ insert excel metadata., C++ edit excel metadata., C++ remove excel metadata., C++ extract excel metadata., C++ modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="مدیریت Microsoft<sup>&reg;</sup> فراداده سند اکسل از طریق C++" h2="مشاهده، درج، به روز رسانی، حذف یا استخراج ویژگی های سند اکسل سفارشی و داخلی در برنامه های C++." >}}
{{% blocks/products/pf/feature-page-summary %}}
 ابرداده در اکسل - نحوه مشاهده، درج و حذف ابرداده فایل اکسل.[C++ کتابخانه اکسل](/cells/fa/cpp/) faclitates با پشتیبانی از ویژگی های داخلی/تعریف شده توسط سیستم مانند نام نویسنده، عنوان، آمار سند و غیره به روشی آسان انجام می شود، مانند بررسی اینکه آیا آخرین فایل تغییر یا ذخیره شده است به همراه ویژگی های سفارشی / تعریف شده توسط کاربر در قالب جفت نام/مقدار برای خودکارسازی فرآیند، کتابخانه از ایجاد و نگهداری فایل‌های اکسل ابرداده بزرگ پشتیبانی می‌کند.[کتاب کار](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/)class یک کتاب کار را بر اساس مسیر، جریان و توسط FileFormatType خاص باز می کند. بنابراین فایل را با روش مناسب برای پردازش بیشتر بارگذاری کنید. تعداد کمی از امکانات ذکر شده در زیر و توسعه دهندگان می توانند به راحتی کد خود را با توجه به نیاز برنامه افزایش دهند.
 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="ویژگی های ساخته شده را بخوانید و به روز کنید" %}}

 برای خودکارسازی خواص داخلی، API فراهم می کند[GetBuiltInDocumentProperties()](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/getbuiltindocumentproperties/) روشی که یک مجموعه DocumentProperties را باز می گرداند که نشان دهنده تمام ویژگی های سند داخلی صفحه گسترده است. پس از دسترسی به تمام ویژگی های داخلی، با استفاده از متدهای مرتبط مانند GetTitle()، GetSubject() و غیره به ویژگی های مربوطه دسترسی پیدا کنید.[مجموعه اموال سند داخلی](https://reference.aspose.com/cells/cpp/aspose.cells.properties/builtindocumentpropertycollection/) برای عملکرد مورد نیاز

{{% blocks/products/pf/feature-page-code h3="C++ کد برای خواندن ویژگی های تعریف شده سیستم" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "read-system-defined-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C++ کد به روز رسانی Builtin Properties" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "update-built-in-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="مشاهده و افزودن ویژگی های تعریف شده سفارشی" %}}

برای رسیدگی به خواص سفارشی، API فراهم می کند[کتاب کار::GetCustomDocumentProperties](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/getcustomdocumentproperties/) که تمام مجموعه ویژگی های سند سفارشی صفحه گسترده را برمی گرداند. ابتدا با دسترسی به ویژگی‌های سفارشی از طریق این روش، توسعه‌دهندگان می‌توانند از روش‌های مربوطه برای افزودن ویژگی‌هایی مانند AddIDocumentProperty، AddLinkToContentProperty و به طور مشابه از UpdateLinkedPropertyValue، UpdateLinkedRange برای به‌روزرسانی ارزش ویژگی سند سفارشی استفاده کنند که به ترتیب به محتوا و محدوده پیوندی پیوند می‌خورد. توسعه دهندگان می توانند از روش مربوطه استفاده کنند[مجموعه ای از ویژگی های سند سفارشی](https://reference.aspose.com/cells/cpp/aspose.cells.properties/customdocumentpropertycollection/).

{{% blocks/products/pf/feature-page-code h3="C++ کد برای مشاهده ویژگی های سفارشی" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "view-custom-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C++ کد اضافه کردن متادیتا در فایل اکسل" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "add-custom-property.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
