---
title: نحوه اضافه کردن اشکال از طریق Aspose.Cells
weight: 7700
limit:
description: آموزش اضافه کردن اشکال
keywords: [add shapes., how to add shapes in Aspose.Cells., how to add shapes using Aspose.Cells]
url: /fa/tutorial/add-shapes-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="آموزش اضافه کردن اشکال با Aspose.Cells" >}}

<p>
در این آموزش، شکل ها را در یک فایل اکسل اضافه می کنیم.
</p>

<p>
 ما با ایجاد یک کتاب کار جدید با استفاده از<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells کتابخانه</a> و اشکال اضافه کنید.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: لطفاً کد زیر را بررسی کنید تا نحوه اضافه کردن اشکال را بیابید.
//ExStepSummary:0: کد زیر نحوه اضافه کردن شکل مستطیل را نشان می دهد.
//ExStepImage:0:step-1.png
//ExStepSummary:1: کد زیر نحوه اضافه کردن شکل خط را نشان می دهد.
//ExStepImage:1:step-2.png
//ExStepSummary:2: کد زیر نحوه اضافه کردن شکل بیضی را نشان می دهد.
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

//شکل مستطیل را اضافه کنید
shapes.AddRectangle(1, 0, 1, 0, 100, 150);

//ExStep:1-
//افزودن شکل خط
shapes.AddLine(8، 0، 1، 0، 100، 150);

//ExStep:2-
//شکل بیضی را اضافه کنید
shapes.AddOval(13, 0, 1, 0, 100, 150);

//ExStep:0-
کتاب کار
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