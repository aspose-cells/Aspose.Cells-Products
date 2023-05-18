---
title: ایجاد و تبدیل نمودارهای اکسل به تصاویر via .NET
description:  کد منبع C# برای رسم و تبدیل نمودار یا نمودار در اکسل Microsoft با استفاده از کتابخانه .NET.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> ایجاد و تبدیل نمودارهای فایل اکسل via .NET" h2="نمودارهای سند اکسل را ایجاد کنید و با استفاده از API های سمت سرور در برنامه های مبتنی بر .NET به تصاویر تبدیل کنید." >}}
{{% blocks/products/pf/feature-page-summary %}}
 رسم نمودارها هنری برای نمایش داده ها به صورت گرافیکی برای تجزیه و تحلیل آسان است.[.NET کتابخانه اکسل](/cells/fa/net/) از ترسیم نمودارها در فایل های اکسل پشتیبانی می کند. API از ایجاد نمودارهای مختلف لیست شده در پشتیبانی می کند[ChartType Enumeration](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype) از جمله نمودارهای پای، هرم، خط و حباب. علاوه بر این، نمودارها را نیز به تصاویر تبدیل می کند. API ارائه می دهد[کلاس نمودارها](https://reference.aspose.com/cells/net/aspose.cells.charts) برای بلوک های ساختمان نمودار

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="ایجاد نمودار در فایل اکسل" %}}

 ایجاد نمودار با استفاده از اکسل API ساده است. فرآیند، ایجاد است[کلاس کتاب کار](https://reference.aspose.com/cells/net/aspose.cells/workbook) شی و اولین کاربرگ یا شیت مربوطه را با ارائه نمایه آن انتخاب کنید. با استفاده از داده های سلولی مورد نیاز را وارد کنید[روش PutValue](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index) . با استفاده از مجموعه نمودارها نمودار را به کاربرگ اضافه کنید[روش اضافه کنید](https://reference.aspose.com/cells/net/aspose.cells.charts/chartcollection/methods/add) . را مشخص کنید[ChartType](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype)از ChartType enumeration.
{{% blocks/products/pf/feature-page-code h3="C# کد ایجاد نمودار اکسل" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "create-excel-chart.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section h2="تبدیل نمودارهای اکسل به تصاویر" %}}

 فرآیند تبدیل نمودارها به تصویر به این صورت است که از کلاس Workbook برای بارگذاری فایل اکسل استفاده کنید، صفحه کاری مربوطه حاوی نمودارها را انتخاب کنید و[روش ToImage](https://reference.aspose.com/cells/net/aspose.cells.charts.chart/toimage/methods/7) برای تبدیل

{{% blocks/products/pf/feature-page-code h3="C# کد برای تبدیل نمودار اکسل به تصویر" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "convert-xlsx-file-chart-to-images.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}
