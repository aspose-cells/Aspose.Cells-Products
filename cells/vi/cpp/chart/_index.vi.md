---
title: Tạo Biểu đồ Excel và Chuyển đổi sang Hình ảnh qua C++

description: C++ mã nguồn để vẽ và chuyển đổi biểu đồ hoặc sơ đồ trong Microsoft Excel bằng cách sử dụng C++ Thư viện
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Tạo Microsoft <sup> & reg; </sup> Biểu đồ Excel và Chuyển đổi sang Hình ảnh qua C++" h2="Chuyển đổi biểu đồ tài liệu Excel thành hình ảnh cũng như tạo biểu đồ bao gồm biểu đồ Hình tròn, Kim tự tháp, Đường và Bong bóng trong các ứng dụng dựa trên C++." >}}

{{% blocks/products/pf/feature-page-summary %}}

Sử dụng biểu đồ Excel, người ta có thể có được bức tranh toàn cảnh hơn và dễ dàng phân tích dữ liệu để đưa ra quyết định đúng đắn. [C++ Thư viện Excel](/cells/cpp/) hỗ trợ tạo các biểu đồ khác nhau được liệt kê bởi [enum Aspose :: Cells :: Charts :: ChartType
](https://reference.aspose.com/cells/cpp/namespace/aspose.cells.charts#a2f17e69bcefc754569019185d0621b70) bao gồm các biểu đồ diện tích, thanh, hình tròn, kim tự tháp, đường và bong bóng. Hơn nữa, Để chuyển đổi biểu đồ thành hình ảnh, API cung cấp [Hình ảnh mehtod](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_sparkline#a28d76dd585c48366e1657f2982722ddb) thành định dạng hình ảnh yêu cầu.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Tạo biểu đồ Excel" %}}

Quá trình tạo biểu đồ Excel là tạo một phiên bản của [Lớp IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) và chọn mong muốn [Bảng tính](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet_collection#a5574d624796043233420d0e0459ccc43). Thêm biểu đồ bằng cách sử dụng [Thêm phương pháp](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_chart_collection#ab7e8cce835c251a4682605299a6aa068) với các thông số liên quan bao gồm loại biểu đồ. Truy cập biểu đồ thông qua chỉ mục và [Thêm vào](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_series_collection#a8f4dc4d883f32f65b1fb673e2aa7862f) nguồn dữ liệu cho biểu đồ.

{{% blocks/products/pf/feature-page-code h3="C++ Mã để Tạo Biểu đồ Excel" %}}

{{< gist "aspose-com-gists" "da2fd423617bf9013a7673870c81d708" "create-excel-chart.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Chuyển đổi biểu đồ thành hình ảnh" %}}


Đối với quy trình chuyển đổi biểu đồ, trước tiên hãy tạo biểu đồ thuộc loại có liên quan bằng cách sử dụng mã trên hoặc truy cập nó từ trang có liên quan. Xác định đường dẫn lưu đầu ra cho hình ảnh và sử dụng phương pháp ToImage để chuyển đổi.

 
{{% blocks/products/pf/feature-page-code h3="C++ Mã để Chuyển đổi Biểu đồ Excel" %}}

{{< gist "aspose-com-gists" "da2fd423617bf9013a7673870c81d708" "convert-excel-chart-to-image.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}
