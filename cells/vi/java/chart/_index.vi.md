---
title: Tạo biểu đồ Excel và chuyển đổi sang hình ảnh via Java
description:  Java mã nguồn vẽ và chuyển đổi biểu đồ hoặc sơ đồ trong Microsoft Excel sử dụng Thư viện Java.
keywords: [Java Aspose.Cells., Java Convert chart to image., Java Save chart to image., Java chart to image., create charts in Java., insert charts in Java., manage charts in Java]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Chuyển đổi và tạo biểu đồ tệp Excel via Java" h2="Chuyển đổi biểu đồ tài liệu Excel thành hình ảnh cũng như tạo các biểu đồ khác nhau bằng API phía máy chủ trong các ứng dụng dựa trên Java." >}}


{{% blocks/products/pf/feature-page-summary %}}

 Phân tích dữ liệu qua biểu đồ cho thấy bức tranh toàn cảnh hơn và dễ dàng đưa ra quyết định sáng suốt hơn với thông tin chi tiết rõ ràng hơn.[Java Thư viện Excel](/cells/vi/java/) hỗ trợ vẽ tạo biểu đồ khác nhau được liệt kê bởi[Loại biểu đồ](https://reference.aspose.com/cells/java/com.aspose.cells/ChartType) bao gồm biểu đồ hình tròn, kim tự tháp, đường và bong bóng. Hơn nữa, nó còn chuyển đổi biểu đồ thành hình ảnh. API cung cấp[Lớp biểu đồ](https://reference.aspose.com/cells/java/com.aspose.cells/Chart) để thể hiện một biểu đồ Excel duy nhất.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Chuyển đổi biểu đồ Excel thành hình ảnh" %}}

 Quá trình chuyển đổi biểu đồ thành hình ảnh bao gồm JPG, PNG, TIFF, BMP v.v., hãy sử dụng[Sách bài tập](https://reference.aspose.com/java/cells/com.aspose.cells/workbook) lớp để tải tệp Excel, chọn lớp có liên quan[bàn làm việc](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet) chứa các biểu đồ hoặc lặp qua từng biểu đồ trong mỗi bảng tính. Định nghĩa[Tùy chọn Hình ảnh Hoặc In](https://reference.aspose.com/cells/java/com.aspose.cells/ImageOrPrintOptions) và hiển thị hình ảnh đầu ra của Biểu đồ bằng cách sử dụng[Chart.toImage](https://reference.aspose.com/cells/java/com.aspose.cells/chart#toImage(java.io.OutputStream,%20com.aspose.cells.ImageOrPrintOptions)).


{{% blocks/products/pf/feature-page-code h3="Java Mã Chuyển Biểu Đồ Excel Thành Hình Ảnh" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "render-excel-chart-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}


{{% blocks/products/pf/feature-page-section h2="Tạo biểu đồ trong tệp Excel" %}}

Tạo biểu đồ bằng Excel API rất đơn giản, vì API cung cấp tập hợp các lớp khác nhau như Axis, Chart, ChartArea, ChartDataTable, ChartFrame, ChartPoint, ChartPointCollection, ChartCollection, v.v. cho các loại biểu đồ khác nhau. Quy trình là Tạo đối tượng lớp Workbook và chọn trang tính đầu tiên hoặc trang tính có liên quan bằng cách cung cấp chỉ mục của nó. Đối với nguồn dữ liệu của biểu đồ, hãy chèn giá trị vào các ô trang tính bằng cách sử dụng[đặt giá trị](https://reference.aspose.com/cells/java/com.aspose.cells/cell#Value) phương pháp. Sử dụng bộ sưu tập ChartCollection[thêm phương pháp](https://reference.aspose.com/cells/java/com.aspose.cells/chartcollection#add(int,%20int,%20int,%20int,%20int) ) để thêm biểu đồ, xác định loại biểu đồ bằng bảng liệt kê ChartType. Truy cập đối tượng Biểu đồ mới từ bộ sưu tập ChartCollection bằng cách chuyển chỉ mục của nó. Sử dụng[Bộ sưu tập hàng loạt](https://reference.aspose.com/cells/java/com.aspose.cells/SeriesCollection) đối tượng biểu đồ để chỉ định nguồn dữ liệu của biểu đồ.

{{% blocks/products/pf/feature-page-code h3="Java Mã tạo biểu đồ Excel" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "create-excel-chart-pyramid.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
