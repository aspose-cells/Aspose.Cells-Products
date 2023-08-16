---
title: Cách thêm biểu đồ đường qua Aspose.Cells
weight: 7700
limit:
description: Tìm hiểu cách thêm biểu đồ đường.
keywords: [Add line chart., how to add line chart in Aspose.Cells., how to add line chart using Aspose.Cells]
url: /vi/tutorial/add-line-chart-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Tìm hiểu cách thêm biểu đồ đường với Aspose.Cells" >}}

<p>
Trong hướng dẫn này, chúng ta sẽ thêm biểu đồ đường trong tệp excel.
</p>

<p>
 Chúng ta sẽ bắt đầu bằng cách tạo một sổ làm việc mới bằng cách sử dụng<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells thư viện</a> và thêm biểu đồ đường.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: Vui lòng kiểm tra đoạn mã sau để tìm hiểu cách thêm biểu đồ đường.
//ExStepSummary:0: Đoạn mã sau cho biết cách thêm biểu đồ đường, đặt phạm vi dữ liệu chuỗi và đặt phạm vi dữ liệu danh mục.
//ExStepImage:0:step-1.png
//ExStepSummary:1: Đoạn mã sau cho biết cách di chuyển chú giải xuống dưới cùng và đặt màu phông chữ của chú giải.
//ExStepImage:1:step-2.png
//ExStepSummary:2: Đoạn mã sau cho biết cách truy cập nhãn dữ liệu, bật tên danh mục và đặt vị trí.
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

//Thêm biểu đồ đường, đặt phạm vi dữ liệu chuỗi và đặt phạm vi dữ liệu danh mục
int index = sheet.Charts.Add(ChartType.Line, 6, 0, 19, 5);
Biểu đồ biểu đồ = sheet.Charts[index];
chart.NSeries.Add("B2:B5", true);
chart.NSeries.CategoryData = "A2:A5";

//ExStep:1-
// Di chuyển chú thích xuống dưới cùng và đặt màu phông chữ của chú giải
chart.Legend.Font.Color = Color.Blue;
chart.Legend.Position = LegendPositionType.Bottom;

//ExStep:2-
// Truy cập nhãn dữ liệu, bật tên danh mục và đặt vị trí
DataLabels dataLabels = chart.NSeries[0].DataLabels;
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
        <li class="link-item"><a href="https://docs.aspose.com/cells/net/installation/">Lh cài đặt Aspose.Cells</a></li>
        <li class="link-item"><a href="https://products.aspose.app/cells/editor/">Aspose.Cells BTV</a></li>
    </ul>
</div>

{{< /blocks/products/pf/feature-page-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}