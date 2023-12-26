---
title: Tạo biểu đồ Excel và chuyển đổi sang hình ảnh via .NET
description:  C# mã nguồn vẽ và chuyển đổi biểu đồ hoặc sơ đồ trong Microsoft Excel sử dụng Thư viện .NET.
keywords: [C# Aspose.Cells., c# Convert chart to image., c# Save chart to image., c# chart to image., create charts in c#., insert charts in c#., manage charts in c#]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Tạo và chuyển đổi biểu đồ tệp Excel via .NET" h2="Tạo biểu đồ tài liệu Excel và chuyển đổi thành hình ảnh bằng API phía máy chủ trong các ứng dụng dựa trên .NET." >}}
{{% blocks/products/pf/feature-page-summary %}}
 Vẽ biểu đồ là một nghệ thuật hiển thị dữ liệu bằng đồ họa để dễ dàng phân tích.[.NET Thư viện Excel](/cells/vi/net/) hỗ trợ vẽ biểu đồ trong file Excel. API hỗ trợ tạo biểu đồ khác nhau được liệt kê trong[Bảng liệt kê kiểu biểu đồ](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype) bao gồm biểu đồ hình tròn, kim tự tháp, đường và bong bóng. Hơn nữa, nó còn chuyển đổi biểu đồ thành hình ảnh. API cung cấp[Lớp biểu đồ](https://reference.aspose.com/cells/net/aspose.cells.charts) cho các khối xây dựng biểu đồ.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Tạo biểu đồ trong tệp Excel" %}}

 Tạo biểu đồ bằng Excel API rất đơn giản. Quá trình là, Tạo[Lớp sổ làm việc](https://reference.aspose.com/cells/net/aspose.cells/workbook)đối tượng và chọn trang tính đầu tiên hoặc trang tính có liên quan bằng cách cung cấp chỉ mục của nó. Chèn dữ liệu ô cần thiết bằng cách sử dụng[Phương thức PutValue](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index) . Thêm biểu đồ vào trang tính bằng cách sử dụng bộ sưu tập Biểu đồ[Thêm phương pháp](https://reference.aspose.com/cells/net/aspose.cells.charts/chartcollection/methods/add) . Chỉ định la[Loại biểu đồ](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype) từ bảng liệt kê ChartType.
{{% blocks/products/pf/feature-page-code h3="C# Mã tạo biểu đồ Excel" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "create-excel-chart.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section h2="Chuyển đổi biểu đồ Excel thành hình ảnh" %}}

 Quá trình chuyển đổi biểu đồ thành hình ảnh là Sử dụng lớp Workbook để tải tệp Excel, chọn bảng tính có chứa biểu đồ và gọi[Phương thức ToImage](https://reference.aspose.com/cells/net/aspose.cells.charts.chart/toimage/methods/7) để chuyển đổi.

{{% blocks/products/pf/feature-page-code h3="C# Mã Chuyển Biểu Đồ Excel Thành Hình Ảnh" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "convert-xlsx-file-chart-to-images.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}
