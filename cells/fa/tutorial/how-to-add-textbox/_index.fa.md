---
title: نحوه اضافه کردن TextBox از طریق Aspose.Cells
weight: 7700
limit:
description: با نحوه افزودن TextBox آشنا شوید.
keywords: [Add TextBox., how to add TextBox in Aspose.Cells., how to add TextBox using Aspose.Cells]
url: /fa/tutorial/add-textbox-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="نحوه اضافه کردن TextBox با Aspose.Cells را بیاموزید" >}}

<p>
در این آموزش، TextBox را در یک فایل اکسل اضافه می کنیم.
</p>

<p>
 ما با ایجاد یک کتاب کار جدید با استفاده از<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells کتابخانه</a> و TextBox را اضافه کنید.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: لطفاً کد زیر را بررسی کنید تا نحوه افزودن TextBox را بیابید.
//ExStepSummary:0: کد زیر نحوه افزودن TextBox و تنظیم متن را نشان می دهد.
//ExStepImage:0:step-1.png
//ExStepSummary:1: کد زیر نحوه تغییر رنگ متن را نشان می دهد.
//ExStepImage:1:step-2.png
//ExStepSummary:2: کد زیر نحوه تغییر زاویه چرخش TextBox را نشان می دهد.
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
با استفاده از Aspose.Cells;
با استفاده از Aspose.Cells.Drawing;

Workbook workbook = new Workbook();
برگه کار = کتاب کار.کاربرگ[0];
sheet.PageSetup.PrintGridlines = true;
sheet.PageSetup.PrintArea = "A1:F20";

ShapeCollection shapes = sheet.Shapes;

//TextBox را اضافه کنید و متن را تنظیم کنید
TextBox textBox = shapes.AddTextBox(1, 0, 1, 0, 200, 200);
textBox.Text = "Aspose.Cells for .NET یک کتابخانه کلاس برنامه نویسی است که به توسعه دهندگان نرم افزار اجازه می دهد تا فایل های صفحه گسترده را در برنامه های خود دستکاری و پردازش کنند.";

//ExStep:1-
//رنگ متن را تغییر دهید
textBox.Font.Color = Color.Blue;

//ExStep:2-
//زاویه چرخش TextBox را تغییر دهید
textBox.RotationAngle = 90;

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