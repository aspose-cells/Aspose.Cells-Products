---
title: Cách thêm biểu đồ hình tròn qua Aspose.Cells
weight: 7700
limit:
description: Tìm hiểu cách thêm biểu đồ hình tròn.
keywords: [Add pie chart., how to add pie chart in Aspose.Cells., how to add pie chart using Aspose.Cells]
url: /vi/tutorial/add-pie-chart-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Tìm hiểu cách thêm biểu đồ hình tròn với Aspose.Cells" >}}

<p>
Trong hướng dẫn này, chúng ta sẽ thêm biểu đồ hình tròn vào tệp excel.
</p>

<p>
 Chúng ta sẽ bắt đầu bằng cách tạo một sổ làm việc mới bằng cách sử dụng<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells thư viện</a> và thêm biểu đồ hình tròn.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: Vui lòng kiểm tra đoạn mã sau để tìm hiểu cách thêm biểu đồ hình tròn.
//ExStepSummary:0: Đoạn mã sau cho biết cách thêm biểu đồ hình tròn, đặt phạm vi dữ liệu chuỗi và đặt phạm vi dữ liệu danh mục.
//ExStepImage:0:step-1.png
//ExStepSummary:1: Đoạn mã sau cho biết cách tắt chú giải.
//ExStepImage:1:step-2.png
//ExStepSummary:2: Đoạn mã sau cho biết cách truy cập nhãn dữ liệu, bật tên danh mục, bật định dạng phần trăm và đặt vị trí.
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

//Thêm biểu đồ hình tròn, đặt phạm vi dữ liệu chuỗi và đặt phạm vi dữ liệu danh mục
int index = sheet.Charts.Add(ChartType.Pie, 6, 0, 19, 5);
Biểu đồ biểu đồ = sheet.Charts[index];
chart.NSeries.Add("B2:B5", true);
chart.NSeries.CategoryData = "A2:A5";

//ExStep:1-
// Tắt chú thích
chart.ShowLegend = false;

//ExStep:2-
// Truy cập nhãn dữ liệu, bật tên danh mục, bật định dạng phần trăm và đặt vị trí
DataLabels dataLabels = chart.NSeries[0].DataLabels;
dataLabels.ShowCategoryName = true;
dataLabels.ShowPercentage = true;
dataLabels.Position = LabelPositionType.OutsideEnd;

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