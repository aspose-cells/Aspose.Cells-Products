---
title: تقسیم صفحه گسترده اکسل به کاربرگ در Java
description: کدهای منبع Java که نحوه تقسیم فایل های Microsoft اکسل را به چندین سند با استفاده از کتابخانه اکسل Java توضیح می دهد.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> تقسیم فایل اکسل via Java" h2="صفحه‌گسترده اکسل را به کاربرگ‌هایی در برنامه‌های مبتنی بر Java تقسیم کنید" >}}
{{% blocks/products/pf/feature-page-summary %}}
 سناریوهای مختلفی وجود دارد، زمانی که نیاز به تقسیم فایل‌های اکسل مانند صفحه‌گسترده حاوی داده‌های دانش‌آموز با تخصیص یک برگه برای هر دانش‌آموز وجود دارد. و نیاز به تقسیم هر برگه دانش آموز به عنوان یک فایل جداگانه وجود دارد. برای خودکارسازی برنامه via Java،[Java اکسل API](/cells/fa/java/) برای تقسیم سند اکسل به صورت ورق وجود دارد. فرمت های پشتیبانی شده عبارتند از XLS، XLSX، XLSB، XLSM، ODS.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="سند اکسل را به چندین فایل تقسیم کنید" %}}

ساده ترین راه برای تقسیم فایل اکسل به شیت این است که به همه برگه ها دسترسی داشته باشید، هر برگه را تکرار کنید و یک به یک در قالب دلخواه ذخیره کنید. برای بارگذاری کاربرگ API ارائه می دهد[کتاب کار](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) کلاس[getWorksheets().getCount()](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#Count) روش تعداد کل برگه ها را بدست می آورد. در هر برگه تکرار کنید و استفاده کنید[getWorksheets().get(sheetindex)](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#get) برای دسترسی به برگه خاص داده های برگه انتخاب شده را با استفاده از آن به شی کلاس Workbook جدید ایجاد شده منتقل کنید[روش کپی](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#copy(com.aspose.cells.Workbook)). در نهایت آن را در فرمت مورد نیاز ذخیره کنید.

{{% blocks/products/pf/feature-page-code h3="Java کد برای تقسیم فایل های اکسل" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-xls-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="کاربرگ اکسل را به صفحات تقسیم کنید" %}}

API همچنین قابلیت تقسیم کاربرگ اکسل به صفحات مختلف را فراهم می کند. فرآیند به این صورت است که فایل را با استفاده از کلاس Workbook بارگیری کنید. کاربرگ اول یا هر برگه مورد نیاز را با ارائه فهرست آن انتخاب کنید. setActiveCell را که شاخص سلول مربوطه را به عنوان پارامتر دارد، فراخوانی کنید. و در نهایت با فراخوانی متد split() پنجره کاربرگ را به پنجره های مختلف تقسیم کنید.

{{% blocks/products/pf/feature-page-code h3="Java کد برای تقسیم برگه اکسل به نمای پانل" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-excel-spreadsheet-into-panes.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
