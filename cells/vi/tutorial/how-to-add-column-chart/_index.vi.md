---
title: Cách thêm biểu đồ cột qua Aspose.Cells
weight: 7700
limit:
description: Tìm hiểu cách thêm biểu đồ cột.
keywords: [Add column chart., how to add column chart in Aspose.Cells., how to add column chart using Aspose.Cells]
url: /vi/tutorial/add-column-chart-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Học cách thêm biểu đồ cột với Aspose.Cells" >}}

<p>
Trong hướng dẫn này, chúng ta sẽ thêm biểu đồ cột vào tệp excel.
</p>

<p>
 Chúng ta sẽ bắt đầu bằng cách tạo một sổ làm việc mới bằng cách sử dụng<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells thư viện</a> và thêm biểu đồ cột.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: Vui lòng kiểm tra đoạn mã sau để tìm hiểu cách thêm biểu đồ cột.
//ExStepSummary:0: Đoạn mã sau cho biết cách thêm biểu đồ cột.
//ExStepImage:0:step-1.png
//ExStepSummary:1: Đoạn mã sau cho biết cách di chuyển chú giải sang trái và đặt màu phông chữ của chú giải.
//ExStepImage:1:step-2.png
//ExStepSummary:2: Đoạn mã sau cho biết cách đặt tiêu đề của biểu đồ và thay đổi màu phông chữ thành xanh lam.
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
sử dụng Aspose.Cells;
sử dụng Aspose.Cells.Drawing;

Sổ làm việc sổ làm việc = Sổ làm việc mới();
Bảng tính = workbook.Worksheets[0];
sheet.Name = "ChartSheet";
Cells ô = tờ.Cells;
cells["A1"].Value = "Trái cây";
các ô ["A2"]. Giá trị = "quả táo";
các ô ["A3"]. Giá trị = "màu cam";
cells["A4"].Value = "quả việt quất";
cells["A5"].Value = "kiwi";

các ô ["B1"]. Giá trị = "Giá";
các ô ["B2"]. Giá trị = 10;
các ô ["B3"]. Giá trị = 5;
các ô ["B4"]. Giá trị = 20;
các ô ["B5"]. Giá trị = 8;

sheet.PageSetup.PrintGridlines = true;
sheet.PageSetup.PrintArea = "A1:F20";

ChartCollection chart = sheet.Charts;

//Thêm biểu đồ cột
int index = chart.Add(ChartType.Column, "=ChartSheet!A1:B5", false, 6, 0, 19, 5);
Biểu đồ biểu đồ = biểu đồ [chỉ mục];

//ExStep:1-
// Di chuyển chú thích sang trái và đặt màu phông chữ của chú giải
chart.Legend.Font.Color = Color.Blue;
chart.Legend.Position = LegendPositionType.Left;

//ExStep:2-
//Đặt tiêu đề của biểu đồ và thay đổi màu phông chữ thành màu xanh lam
chart.Title.Text = "Biểu đồ cột giá trái cây";
chart.Title.Font.Color = Color.Blue;

//ExStep:0-

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