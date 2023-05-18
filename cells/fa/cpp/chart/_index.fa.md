---
title: نمودارهای اکسل ایجاد کنید و از طریق C++ به تصاویر تبدیل کنید
description: کد منبع C++ برای ترسیم و تبدیل نمودار یا نمودار در اکسل Microsoft با استفاده از کتابخانه C++
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="نمودارهای اکسل Microsoft<sup>&reg;</sup> ایجاد کنید و از طریق C++ به تصاویر تبدیل کنید" h2="نمودارهای اسناد اکسل را به تصاویر تبدیل کنید و همچنین نمودارهایی از جمله نمودارهای Pie، Pyramid، Line و Bubble را در برنامه های مبتنی بر C++ ایجاد کنید." >}}

{{% blocks/products/pf/feature-page-summary %}}

 با استفاده از نمودارهای اکسل، می توان تصویر بزرگتر را به دست آورد و داده ها را به راحتی برای تصمیم گیری درست تجزیه و تحلیل کرد.[C++ کتابخانه اکسل](/cells/fa/cpp/) پشتیبانی از ایجاد نمودارهای مختلف فهرست شده توسط[enum Aspose::Cells::نمودارها::ChartType
](https://reference.aspose.com/cells/cpp/namespace/aspose.cells.charts#a2f17e69bcefc754569019185d0621b70) از جمله نمودارهای مساحت، میله، پای، هرم، خط و حباب. همچنین برای تبدیل نمودارها به تصویر شماره API یک[روش ToImage](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_sparkline#a28d76dd585c48366e1657f2982722ddb) به فرمت تصویر مورد نیاز

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="نمودارهای اکسل ایجاد کنید" %}}

 فرآیند ایجاد نمودار اکسل، ایجاد یک نمونه از آن است[کلاس IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) و مورد نظر را انتخاب کنید[کاربرگ](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet_collection#a5574d624796043233420d0e0459ccc43) . نمودار را با استفاده از آن اضافه کنید[روش اضافه کنید](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_chart_collection#ab7e8cce835c251a4682605299a6aa068)با پارامترهای مربوطه از جمله نوع نمودار. دسترسی به نمودار از طریق فهرست و[اضافه کردن](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_series_collection#a8f4dc4d883f32f65b1fb673e2aa7862f) منبع داده برای نمودار

{{% blocks/products/pf/feature-page-code h3="C++ کد ایجاد نمودار اکسل" %}}

{{< gist "aspose-com-gists" "da2fd423617bf9013a7673870c81d708" "create-excel-chart.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="تبدیل نمودارها به تصاویر" %}}


برای تبدیل نمودارها، ابتدا نمودار را با استفاده از کد بالا از نوع مربوطه ایجاد کنید یا از برگه مربوطه به آن دسترسی داشته باشید. مسیر ذخیره خروجی را برای تصویر تعریف کنید و از روش ToImage برای تبدیل استفاده کنید.

 
{{% blocks/products/pf/feature-page-code h3="C++ کد برای تبدیل نمودار اکسل" %}}

{{< gist "aspose-com-gists" "da2fd423617bf9013a7673870c81d708" "convert-excel-chart-to-image.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}
