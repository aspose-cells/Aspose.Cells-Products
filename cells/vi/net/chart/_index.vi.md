---
title: Tạo và chuyển đổi biểu đồ Excel thành hình ảnh via .NET
description:  C# mã nguồn để vẽ và chuyển đổi biểu đồ hoặc sơ đồ trong Microsoft Excel bằng Thư viện .NET.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Tạo và chuyển đổi biểu đồ tệp Excel via .NET" h2="Tạo biểu đồ tài liệu Excel và chuyển đổi thành hình ảnh bằng API phía máy chủ trong các ứng dụng dựa trên .NET." >}}
{{% blocks/products/pf/feature-page-summary %}}
 Vẽ biểu đồ là một nghệ thuật để hiển thị dữ liệu bằng đồ họa để dễ dàng phân tích.[.NET Thư Viện Excel](/cells/vi/net/) hỗ trợ vẽ biểu đồ trong file Excel. API hỗ trợ tạo biểu đồ khác nhau được liệt kê trong[Bảng liệt kê Loại biểu đồ](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype) bao gồm biểu đồ hình tròn, kim tự tháp, đường thẳng và bong bóng. Hơn nữa, nó cũng chuyển đổi biểu đồ thành hình ảnh. API cung cấp một[lớp biểu đồ](https://reference.aspose.com/cells/net/aspose.cells.charts) cho các khối xây dựng biểu đồ.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Tạo biểu đồ trong tệp Excel" %}}

 Tạo biểu đồ bằng Excel API rất đơn giản. Quy trình là, Tạo[lớp sách bài tập](https://reference.aspose.com/cells/net/aspose.cells/workbook) đối tượng và chọn trang tính đầu tiên hoặc trang tính có liên quan bằng cách cung cấp chỉ mục của nó. Chèn dữ liệu ô cần thiết bằng cách sử dụng[Phương thức PutValue](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index) . Thêm biểu đồ vào trang tính bằng cách sử dụng bộ sưu tập Charts[thêm phương pháp](https://reference.aspose.com/cells/net/aspose.cells.charts/chartcollection/methods/add) . Chỉ định la[Loại biểu đồ](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype)từ liệt kê ChartType.
{{% blocks/products/pf/feature-page-code h3="C# Mã để tạo biểu đồ Excel" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "create-excel-chart.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section h2="Chuyển đổi biểu đồ Excel thành hình ảnh" %}}

 Quá trình chuyển đổi biểu đồ sang hình ảnh là, Sử dụng lớp Workbook để tải tệp Excel, chọn workseet có liên quan chứa các biểu đồ và gọi hàm[Phương thức ToImage](https://reference.aspose.com/cells/net/aspose.cells.charts.chart/toimage/methods/7) để chuyển đổi.

{{% blocks/products/pf/feature-page-code h3="C# Mã để chuyển đổi biểu đồ Excel thành hình ảnh" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "convert-xlsx-file-chart-to-images.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}
