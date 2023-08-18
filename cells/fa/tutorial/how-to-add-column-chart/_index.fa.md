---
title: نحوه اضافه کردن نمودار ستونی از طریق Aspose.Cells
weight: 7700
limit:
description: نحوه اضافه کردن نمودار ستونی را بیاموزید.
keywords: [Add column chart., how to add column chart in Aspose.Cells., how to add column chart using Aspose.Cells]
url: /fa/tutorial/add-column-chart-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="نحوه اضافه کردن نمودار ستونی با Aspose.Cells را بیاموزید" >}}

<p>
در این آموزش، نمودار ستونی را در یک فایل اکسل اضافه می کنیم.
</p>

<p>
 ما با ایجاد یک کتاب کار جدید با استفاده از<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells کتابخانه</a> و نمودار ستونی را اضافه کنید.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: لطفاً کد زیر را بررسی کنید تا نحوه اضافه کردن نمودار ستونی را بیابید.
//ExStepSummary:0: کد زیر نحوه اضافه کردن نمودار ستونی را نشان می دهد.
//ExStepImage:0:step-1.png
//ExStepSummary:1: کد زیر نحوه انتقال افسانه به چپ و تنظیم رنگ فونت افسانه را نشان می دهد.
//ExStepImage:1:step-2.png
//ExStepSummary:2: کد زیر نحوه تنظیم عنوان نمودار و تغییر رنگ فونت به آبی را نشان می دهد.
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

//افزودن نمودار ستونی
int index = charts.Add(ChartType.Column, "=ChartSheet!A1:B5", false, 6, 0, 19, 5);
نمودار نمودار = نمودارها[شاخص];

//ExStep:1-
// افسانه را به چپ منتقل کنید و رنگ فونت افسانه را تنظیم کنید
نمودار.Legend.Font.Color = رنگ.آبی;
chart.Legend.Position = LegendPositionType.Left;

//ExStep:2-
//عنوان نمودار را تنظیم کنید و رنگ فونت را به آبی تغییر دهید
chart.Title.Text = "نمودار ستونی قیمت میوه";
chart.Title.Font.Color = رنگ.آبی;

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