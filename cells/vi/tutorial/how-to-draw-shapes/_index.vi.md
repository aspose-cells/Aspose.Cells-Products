---
title: Cách thêm hình qua Aspose.Cells
weight: 7700
limit:
description: Tìm hiểu cách thêm hình dạng.
keywords: [add shapes., how to add shapes in Aspose.Cells., how to add shapes using Aspose.Cells]
url: /vi/tutorial/add-shapes-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Học cách thêm hình với Aspose.Cells" >}}

<p>
Trong hướng dẫn này, chúng ta sẽ thêm các hình dạng trong tệp excel.
</p>

<p>
 Chúng ta sẽ bắt đầu bằng cách tạo một sổ làm việc mới bằng cách sử dụng<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells thư viện</a> và thêm hình dạng.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: Vui lòng kiểm tra đoạn mã sau để tìm hiểu cách thêm hình dạng.
//ExStepSummary:0: Đoạn mã sau cho biết cách thêm hình chữ nhật.
//ExStepImage:0:step-1.png
//ExStepSummary:1: Đoạn mã sau cho biết cách thêm hình dạng đường.
//ExStepImage:1:step-2.png
//ExStepSummary:2: Đoạn mã sau cho biết cách thêm hình bầu dục.
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
sử dụng Aspose.Cells;
sử dụng Aspose.Cells.Drawing;





Sổ làm việc sổ làm việc = Sổ làm việc mới();
Bảng tính = workbook.Worksheets[0];
sheet.PageSetup.PrintGridlines = true;
sheet.PageSetup.PrintArea = "A1:F20";

Hình dạng ShapeCollection = sheet.Shapes;

//Thêm hình chữ nhật
hình dạng.AddRectangle(1, 0, 1, 0, 100, 150);

//ExStep:1-
//Thêm hình dạng đường
hình dạng.AddLine(8, 0, 1, 0, 100, 150);

//ExStep:2-
//Thêm hình bầu dục
hình dạng.AddOval(13, 0, 1, 0, 100, 150);

//ExStep:0-
sách bài tập
//ExEnd
{{< /app/cells/tutorial >}}
<br />

<br />
<br />
<div class="code-sample">
    <ul class="link-list">
        <li class="link-item"><a href="https://docs.aspose.com/cells/net/installation/">Lh cài đặt Aspose.Cells</a></li>
        <li class="link-item"><a href="https://products.aspose.app/cells/editor/">Aspose.Cells BTV</a></li>
    </ul>
</div>

{{< /blocks/products/pf/feature-page-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}