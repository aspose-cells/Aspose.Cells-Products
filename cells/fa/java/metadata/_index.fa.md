---
title: مدیریت فراداده فایل اکسل via Java
description: مشاهده، افزودن، ویرایش، حذف یا استخراج ابرداده فایل های Excel تنها با چند خط کد Java
keywords: [Java Aspose.Cells., Java view excel metadata., Java add excel metadata., Java insert excel metadata., Java edit excel metadata., Java remove excel metadata., Java extract excel metadata., Java modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="مدیریت Microsoft<sup>&reg;</sup> فراداده فایل Excel via Java" h2="با استفاده از API های سمت سرور Java مشخصات فایل اکسل سفارشی و داخلی را مشاهده، اضافه کنید، به روز کنید، حذف کنید یا استخراج کنید." >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java اکسل API](/cells/fa/java/) از مدیریت ویژگی های داخلی (تعریف شده توسط سیستم) مانند عنوان، نام نویسنده، آمار سند و غیره و همچنین ویژگی های سفارشی (تعریف شده توسط کاربر) در قالب جفت نام/مقدار پشتیبانی می کند. وجود دارد[کلاس کتاب کار](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) برای بارگذاری فایل ها و[Worksheet Collection](https://reference.aspose.com/cells/java/com.aspose.cells/WorksheetCollection) به مجموعه ای از کاربرگ ها و همچنین[کلاس کاربرگ](https://reference.aspose.com/cells/java/com.aspose.cells/Worksheet) برای نمایش کاربرگ واحد برای دسترسی به ویژگی های داخلی و سفارشی، BuiltInDocumentProperties، CustomDocumentProperties این فرآیند را برای مدیریت ابرداده ساده می کند.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="مدیریت ویژگی های تعریف شده سیستم" %}}

 برای مدیریت خواص داخلی، API ارائه می دهد[BuiltInDocumentProperties](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#BuiltInDocumentProperties)، و برنامه نویسان می توانند به راحتی به یک ویژگی داخلی دسترسی پیدا کرده و مقدار آن را به روز کنند. بسته به نیاز برنامه، توسعه دهندگان می توانند از ایندکس یا نام دارایی استفاده کنند[DocumentPropertyCollection](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentPropertyCollection). 

{{% blocks/products/pf/feature-page-code h3="Java کد برای مدیریت ویژگی های تعریف شده سیستم" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "update-system-defined-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="افزودن و حذف متادیتای سفارشی تعریف شده" %}}

برای رسیدگی به خواص سفارشی، API فراهم می کند[CustomDocumentProperties](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#CustomDocumentProperties) ، و توسعه دهندگان می توانند به راحتی به ویژگی های موجود دسترسی داشته باشند و همچنین ویژگی های جدید را با استفاده از آن اضافه کنند[روش اضافه کردن](https://reference.aspose.com/cells/java/com.aspose.cells/customdocumentpropertycollection#add(java.lang.String,%20boolean) ) از[CustomDocumentPropertyCollection](https://reference.aspose.com/cells/java/com.aspose.cells/CustomDocumentPropertyCollection) کلاس ویژگی را اضافه می کند و یک مرجع برای ویژگی جدید به عنوان an برمی گرداند[Properties.DocumentProperty](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentProperty) هدف - شی. کلاس DocumentProperty برای بازیابی نام، مقدار و نوع خاصیت سند as استفاده می شود[DocumentProperty.Name](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Name), [DocumentProperty.Value](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Value),  [DocumentProperty.Type](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Type) که یکی از آن ها را برمی گرداند[PropertyType](https://reference.aspose.com/cells/java/com.aspose.cells/PropertyType) مقادیر شمارش
 
{{% blocks/products/pf/feature-page-code h3="Java کد اضافه کردن متادیتا در فایل اکسل" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "add-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="Java کد حذف ویژگی های سفارشی در فایل اکسل" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "remove-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
