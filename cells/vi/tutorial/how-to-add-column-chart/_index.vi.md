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
{{< blocks/products/pf/feature-page-section h2="Tìm hiểu cách thêm biểu đồ cột với Aspose.Cells" >}}

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
//ExStepSummary:1: Đoạn mã sau cho biết cách di chuyển chú giải sang trái và đặt màu phông chữ cho chú giải.
//ExStepImage:1:step-2.png
//ExStepSummary:2: Đoạn mã sau cho biết cách đặt tiêu đề của biểu đồ và thay đổi màu phông chữ thành màu xanh lam.
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
sử dụng Aspose.Cells;
sử dụng Aspose.Cells.Bản vẽ;

Sổ làm việc của sổ làm việc = Sổ làm việc mới();
Trang tính = bảng tính.Worksheets[0];
sheet.Name = "Bảng biểu đồ";
Cells ô = sheet.Cells;
cell["A1"].Value = "Trái cây";
cell["A2"].Value = "apple";
ô["A3"].Value = "cam";
cell["A4"].Value = "blueberry";
cell["A5"].Value = "kiwi";

ô["B1"].Value = "Giá";
ô["B2"].Value = 10;
ô["B3"].Value = 5;
ô["B4"].Value = 20;
ô["B5"].Value = 8;

sheet.PageSetup.PrintGridlines = true;
sheet.PageSetup.PrintArea = "A1:F20";

Biểu đồ ChartCollection = sheet.Charts;

//Thêm biểu đồ cột
int index = Charts.Add(ChartType.Column, "=ChartSheet!A1:B5", false, 6, 0, 19, 5);
Biểu đồ biểu đồ = biểu đồ[chỉ mục];

//ExStep:1-
// Di chuyển chú giải sang trái và đặt màu phông chữ cho chú giải
Chart.Legend.Font.Color = Color.Blue;
Chart.Legend.Position = LegendPositionType.Left;

//ExStep:2-
// Đặt tiêu đề của biểu đồ và thay đổi màu phông chữ thành màu xanh
Chart.Title.Text = "Biểu đồ cột giá trái cây";
Chart.Title.Font.Color = Color.Blue;

//ExStep:0-

//ExEnd
{{< /app/cells/tutorial >}}
<br />

<br />
<br />
<div class="code-sample">
    <ul class="link-list">
        <li class="link-item"><a href="https://docs.aspose.com/cells/net/installation/">Lắp đặt Aspose.Cells</a></li>
        <li class="link-item"><a href="https://products.aspose.app/cells/editor/">Aspose.Cells Biên tập viên</a></li>
    </ul>
</div>

{{< /blocks/products/pf/feature-page-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}