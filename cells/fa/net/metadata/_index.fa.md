---
title: مدیریت فراداده فایل اکسل via .NET C#
description: مشاهده، افزودن، ویرایش، حذف یا استخراج ابرداده فایل های Excel تنها با چند خط کد C#
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="مدیریت Microsoft<sup>&reg;</sup> فراداده فایل Excel via .NET" h2="مشاهده، افزودن، به روز رسانی، حذف یا استخراج ویژگی های داخلی و سفارشی فایل اکسل با استفاده از API های سمت سرور .NET." >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET اکسل API](/cells/fa/net/) از مدیریت ویژگی های تعریف شده (ساخته شده) سیستم مانند عنوان، نام نویسنده، آمار سند و غیره و همچنین ویژگی های تعریف شده توسط کاربر (سفارشی) در قالب جفت نام-مقدار پشتیبانی می کند. وجود دارد[کلاس کتاب کار](https://reference.aspose.com/cells/net/aspose.cells/workbook) برای بارگذاری فایل ها و[Worksheet Collection](https://reference.aspose.com/cells/net/aspose.cells/worksheetcollection)به مجموعه ای از کاربرگ ها و همچنین[کلاس کاربرگ](https://reference.aspose.com/cells/net/aspose.cells/worksheet) برای نمایش کاربرگ واحد همراه با این کلاس ها، BuiltInDocumentProperties، CustomDocumentProperties فرآیند را برای مدیریت ابرداده ساده می کند.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="مدیریت ویژگی های داخلی" %}}

 برای مدیریت ویژگی های تعریف شده توسط سیستم، API فراهم می کند[BuiltInDocumentProperties](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/builtindocumentproperties) ، و برنامه نویسان می توانند به راحتی به یک ویژگی داخلی دسترسی پیدا کرده و مقدار آن را به روز کنند. بسته به نیاز برنامه، توسعه دهندگان می توانند از ایندکس یا نام دارایی استفاده کنند[DocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/documentpropertycollection). 

{{% blocks/products/pf/feature-page-code h3="C# کد برای مدیریت ویژگی های ساخته شده" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "manage-system-defined-excel-file-metadata.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="مدیریت ویژگی های تعریف شده سفارشی" %}}

 برای مدیریت ویژگی های تعریف شده توسط کاربر، API فراهم می کند[CustomDocumentProperties](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/customdocumentproperties) ، و توسعه دهندگان می توانند به راحتی به ویژگی های اضافه شده قبلی و همچنین اضافه کردن ویژگی های جدید دسترسی داشته باشند. به منظور افزودن خواص سفارشی،[روش اضافه کنید](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection/methods/add/index) از[CustomDocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection) کلاس ویژگی را اضافه می کند و یک مرجع برای ویژگی جدید به عنوان an برمی گرداند[Properties.DocumentProperty](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty)هدف - شی. کلاس DocumentProperty برای بازیابی نام، مقدار و نوع خاصیت سند as استفاده می شود[DocumentProperty.Name](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/name), [DocumentProperty.Value](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/value),  [DocumentProperty.Type](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/type) که یکی از آن ها را برمی گرداند[PropertyType](https://reference.aspose.com/cells/net/aspose.cells.properties/propertytype) مقادیر شمارش
 
{{% blocks/products/pf/feature-page-code h3="C# کد اضافه کردن متادیتا در فایل اکسل" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "add-metadata-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="C# کد حذف ویژگی های سفارشی در فایل اکسل" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "remove-custom-properties-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
