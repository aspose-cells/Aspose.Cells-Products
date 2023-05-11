---
title: Tạo biểu đồ Excel và chuyển đổi thành hình ảnh qua C++
description: C++ mã nguồn để vẽ và chuyển đổi biểu đồ hoặc sơ đồ trong Microsoft Excel bằng Thư viện C++
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Tạo biểu đồ Excel và chuyển đổi thành hình ảnh Microsoft<sup>&reg;</sup> qua C++" h2="Chuyển đổi biểu đồ tài liệu Excel thành hình ảnh cũng như tạo biểu đồ bao gồm biểu đồ Hình tròn, Kim tự tháp, Đường và Bong bóng trong các ứng dụng dựa trên C++." >}}

{{% blocks/products/pf/feature-page-summary %}}

 Sử dụng biểu đồ Excel, người ta có thể có được bức tranh toàn cảnh hơn và phân tích dữ liệu dễ dàng để đưa ra quyết định đúng đắn.[C++ Thư Viện Excel](/cells/vi/cpp/) hỗ trợ tạo các biểu đồ khác nhau được liệt kê theo[enum Aspose::Cells::Charts::ChartType
](https://reference.aspose.com/cells/cpp/namespace/aspose.cells.charts#a2f17e69bcefc754569019185d0621b70) bao gồm các biểu đồ diện tích, thanh, tròn, kim tự tháp, đường và bong bóng. Hơn nữa, Để chuyển đổi biểu đồ thành hình ảnh, API cung cấp một[Phương thức ToImage](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_sparkline#a28d76dd585c48366e1657f2982722ddb) thành định dạng hình ảnh cần thiết.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Tạo biểu đồ Excel" %}}

 Quy trình tạo biểu đồ Excel là tạo một thể hiện của biểu đồ[lớp iWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) và chọn mong muốn[bảng tính](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet_collection#a5574d624796043233420d0e0459ccc43) . Thêm biểu đồ bằng cách sử dụng[thêm phương pháp](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_chart_collection#ab7e8cce835c251a4682605299a6aa068)với các thông số liên quan bao gồm cả loại biểu đồ. Truy cập biểu đồ qua chỉ mục và[Thêm vào](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_series_collection#a8f4dc4d883f32f65b1fb673e2aa7862f) nguồn dữ liệu cho biểu đồ.

{{% blocks/products/pf/feature-page-code h3="C++ Mã để tạo biểu đồ Excel" %}}

{{< gist "aspose-com-gists" "da2fd423617bf9013a7673870c81d708" "create-excel-chart.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Chuyển đổi biểu đồ thành hình ảnh" %}}


Đối với quy trình chuyển đổi biểu đồ, trước tiên hãy tạo biểu đồ thuộc loại có liên quan bằng cách sử dụng mã ở trên hoặc truy cập biểu đồ từ trang tính có liên quan. Xác định đường dẫn lưu đầu ra cho hình ảnh và sử dụng phương thức ToImage để chuyển đổi.

 
{{% blocks/products/pf/feature-page-code h3="C++ Mã để chuyển đổi biểu đồ Excel" %}}

{{< gist "aspose-com-gists" "da2fd423617bf9013a7673870c81d708" "convert-excel-chart-to-image.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}
