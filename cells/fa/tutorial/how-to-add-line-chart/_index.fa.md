---
title: نحوه اضافه کردن نمودار خطی از طریق Aspose.Cells
weight: 7700
limit:
description: نحوه اضافه کردن نمودار خطی را بیاموزید.
keywords: [Add line chart., how to add line chart in Aspose.Cells., how to add line chart using Aspose.Cells]
url: /fa/tutorial/add-line-chart-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="نحوه اضافه کردن نمودار خطی با Aspose.Cells را بیاموزید" >}}

<p>
در این آموزش، نمودار خطی را در یک فایل اکسل اضافه می کنیم.
</p>

<p>
 ما با ایجاد یک کتاب کار جدید با استفاده از<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells کتابخانه</a> و نمودار خطی را اضافه کنید.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: لطفاً کد زیر را بررسی کنید تا نحوه اضافه کردن نمودار خطی را بیابید.
//ExStepSummary:0: کد زیر نحوه اضافه کردن نمودار خط، تنظیم محدوده داده سری و تنظیم محدوده داده دسته بندی را نشان می دهد.
//ExStepImage:0:step-1.png
//ExStepSummary:1: کد زیر نحوه انتقال افسانه به پایین و تنظیم رنگ فونت افسانه را نشان می دهد.
//ExStepImage:1:step-2.png
//ExStepSummary:2: کد زیر نحوه دسترسی به برچسب های داده، روشن کردن نام دسته ها و تنظیم موقعیت را نشان می دهد.
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
با استفاده از Aspose.Cells;
با استفاده از Aspose.Cells.Drawing;

Workbook workbook = new Workbook();
برگه کار = کتاب کار.کاربرگ[0];
sheet.Name = "ChartSheet";
Cells سلول = sheet.Cells;
cell["A1"].Value = "میوه";
سلول["A2"].Value = "apple";
سلول["A3"].Value = "نارنجی";
سلول["A4"].Value = "زغال اخته";
سلول["A5"].Value = "کیوی";

سلول["B1"].Value = "Price";
سلول["B2"].Value = 10;
سلول["B3"].Value = 5;
سلول["B4"].Value = 20;
سلول["B5"].Value = 8;

sheet.PageSetup.PrintGridlines = true;
sheet.PageSetup.PrintArea = "A1:F20";

ChartCollection charts = sheet.Charts;

//افزودن نمودار خط، تنظیم محدوده داده سری و تنظیم محدوده داده دسته
int index = sheet.Charts.Add(ChartType.Line, 6, 0, 19, 5);
نمودار نمودار = sheet.Charts[index];
chart.NSeries.Add("B2:B5"، true);
chart.NSeries.CategoryData = "A2:A5";

//ExStep:1-
// افسانه را به پایین منتقل کنید و رنگ فونت افسانه را تنظیم کنید
نمودار.Legend.Font.Color = رنگ.آبی;
chart.Legend.Position = LegendPositionType.Bottom;

//ExStep:2-
//به برچسب های داده ها دسترسی داشته باشید، نام دسته ها را روشن کنید و موقعیت را تنظیم کنید
DataLabels dataLabels = نمودار.NSeries[0].DataLabels;
dataLabels.ShowCategoryName = true;
dataLabels.Position = LabelPositionType.Center;

//ExStep:0-

//ExEnd
{{< /app/cells/tutorial >}}
<br />

<br />
<br />
<div class="code-sample">
    <ul class="link-list">
        <li class="link-item"><a href="https://docs.aspose.com/cells/net/installation/">نصب Aspose.Cells</a></li>
        <li class="link-item"><a href="https://products.aspose.app/cells/editor/">Aspose.Cells ویرایشگر</a></li>
    </ul>
</div>

{{< /blocks/products/pf/feature-page-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}