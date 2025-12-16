---
title: مدیریت متادیتای فایل اکسل با Go از طریق C++
description: مشاهده، اضافه کردن، ویرایش، حذف یا استخراج فراداده‌های فایل‌های اکسل با استفاده از Go از طریق کتابخانه C++
keywords: [Go via C++ Aspose.Cells., Go via C++ view excel metadata., Go via C++ add excel metadata., Go via C++ insert excel metadata., Go via C++ edit excel metadata., Go via C++ remove excel metadata., Go via C++ extract excel metadata., Go via C++ modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="مدیریت فراداده‌های سند اکسل با شناسه Microsoft از طریق Go و با شناسه C++" h2="مشاهده، درج، به‌روزرسانی، حذف یا استخراج ویژگی‌های سند اکسل سفارشی و داخلی در برنامه‌های C++." >}}
{{% blocks/products/pf/feature-page-summary %}}
 فراداده در اکسل - نحوه مشاهده، درج و حذف فراداده‌های فایل اکسل.[از طریق C++ به کتابخانه اکسل بروید](/cells/fa/go-cpp/)faclitates با پشتیبانی از ویژگی‌های داخلی/تعریف‌شده توسط سیستم مانند نام نویسنده، عنوان، آمار سند و غیره که گاهی اوقات برای بررسی آخرین تغییر یا ذخیره فایل به همراه ویژگی‌های سفارشی/تعریف‌شده توسط کاربر در قالب جفت‌های نام/مقدار مورد نیاز هستند، به روشی آسان عمل می‌کند. برای خودکارسازی این فرآیند، کتابخانه از ایجاد و نگهداری فایل‌های اکسل فراداده بزرگ پشتیبانی می‌کند.[کتاب کار](https://reference.aspose.com/cells/go-cpp/workbook/) کلاس یک فایل اکسل را بر اساس مسیر، جریان و نوع فایل خاص باز می‌کند. بنابراین فایل را با متد مناسب برای پردازش بیشتر بارگذاری می‌کند. تعداد کمی از امکانات ذکر شده در زیر وجود دارد و توسعه‌دهندگان می‌توانند به راحتی کد خود را مطابق با نیاز برنامه بهبود بخشند.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="خواندن و به‌روزرسانی ویژگی‌های داخلی" %}}

 برای خودکارسازی ویژگی‌های داخلی، API ارائه می‌دهد.[GetBuiltInDocumentProperties()](https://reference.aspose.com/cells/go-cpp/workbook/getbuiltindocumentproperties/)متدی که مجموعه‌ای از DocumentProperties را برمی‌گرداند که نشان‌دهنده‌ی تمام ویژگی‌های سند داخلی صفحه‌گسترده است. پس از دسترسی به تمام ویژگی‌های داخلی، با استفاده از متدهای مربوطه مانند GetTitle()، GetSubject() و غیره به ویژگی‌های مربوطه دسترسی پیدا کنید. برای به‌روزرسانی ویژگی‌ها، API متدهایی مانند SetTitle، SetSubject، SetAuthor، SetComments و غیره را ارائه می‌دهد. مشاهده کنید[مجموعه املاک سند داخلی](https://reference.aspose.com/cells/go-cpp/workbook/getbuiltindocumentproperties/) برای عملکرد مورد نیاز.

{{% blocks/products/pf/feature-page-code h3="برای خواندن ویژگی‌های تعریف‌شده توسط سیستم، از طریق کد C++ اقدام کنید." %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "read-system-defined-properties.go" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="برای به‌روزرسانی ویژگی‌های داخلی، از طریق کد C++ اقدام کنید." %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "update-built-in-properties.go" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="مشاهده و اضافه کردن ویژگی‌های تعریف‌شده‌ی سفارشی" %}}

 برای مدیریت املاک سفارشی، API ارائه می‌دهد[کتاب کار::ویژگی‌های سند سفارشی را دریافت کنید](https://reference.aspose.com/cells/go-cpp/workbook/getcustomdocumentproperties/)که تمام مجموعه ویژگی‌های سند سفارشی صفحه گسترده را برمی‌گرداند. ابتدا با دسترسی به ویژگی‌های سفارشی از طریق این متد، توسعه‌دهندگان می‌توانند از متدهای مربوطه برای اضافه کردن ویژگی‌هایی مانند AddIDocumentProperty، AddLinkToContentProperty استفاده کنند و به طور مشابه از UpdateLinkedPropertyValue، UpdateLinkedRange برای به‌روزرسانی مقدار ویژگی سند سفارشی که به ترتیب به محتوا و محدوده پیوند داده شده پیوند دارد، استفاده کنند. توسعه‌دهندگان می‌توانند از متد مربوطه از[مجموعه‌ای از ویژگی‌های سند سفارشی](https://reference.aspose.com/cells/go-cpp/workbook/getcustomdocumentproperties/).

{{% blocks/products/pf/feature-page-code h3="برای مشاهده املاک سفارشی از طریق کد C++ اقدام کنید" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "view-custom-properties.go" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="برای افزودن فراداده در فایل اکسل، از طریق کد C++ اقدام کنید." %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "add-custom-property.go" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< /blocks/products/pf/feature-page-wrap >}}