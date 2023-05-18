---
title: ورق کاربرگ اکسل را به شماره C# تقسیم کنید
description: کدهای منبع C# که نحوه تقسیم فایل های اکسل Microsoft را به چندین فایل در برنامه های Visual C#.NET توضیح می دهد.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> تقسیم فایل اکسل via .NET" h2="تقسیم یک سند اکسل به فایل های مختلف با استفاده از کد C# در برنامه های مبتنی بر .NET" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET کتابخانه اکسل](/cells/fa/net/) قادر به تقسیم سند اکسل به صفحات گسترده چندگانه در برنامه های مبتنی بر .NET است. فرمت های فایل پشتیبانی شده عبارتند از XLS، XLSX، XLSB، XLSM، ODS.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="سند اکسل را به چندین فایل تقسیم کنید" %}}
 ساده ترین راه برای تقسیم بندی فایل های اکسل به صورت عاقلانه، دسترسی به همه برگه ها از طریق آن است[کاربرگ ها](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/worksheets) ، تکرار از طریق هر برگه و فراخوانی[کپی 🀄](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy) روش. در نهایت آن را در یک مسیر مشخص ذخیره کنید.

 + فایل اکسل را با استفاده از مسیر کامل بارگذاری کنید[کلاس کتاب کار](https://reference.aspose.com/cells/net/aspose.cells/workbook).
+ در هر برگه تکرار کنید
+ یک شی کلاس Workbook جدید ایجاد کنید
 + برگه را از طریق کپی کنید[روش کپی](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy)
+ متد Save() را فراخوانی کنید و نام فایل (مسیر کامل) را با SaveFormat مربوطه ارسال کنید.

{{% blocks/products/pf/feature-page-code h3="C# کد برای تقسیم فایل های اکسل" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="کاربرگ اکسل را به صفحات تقسیم کنید" %}}

 برای تقسیم پنجره کاربرگ به پنجره ها، API فراهم می کند[روش تقسیم](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/split) از کلاس کاربرگ، که نمای تقسیم شده از کاربرگ را ارائه می دهد. برای حذف نمای تقسیم شده API فراهم می کند[روش RemoveSplit](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/removesplit) . در نهایت آن را در یک مسیر مشخص ذخیره کنید.

{{% blocks/products/pf/feature-page-code h3="C# کد برای تقسیم پنجره کاربرگ اکسل" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet-into-pane.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C# کد حذف نمای پانل تقسیم شده" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "remove-splitted-spreadsheet-pane-view.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
