---
title: Tạo Biểu đồ Excel và Chuyển đổi sang Hình ảnh qua Java
url: /vi/java/chart/
description: Java mã nguồn để vẽ và chuyển đổi biểu đồ hoặc sơ đồ trong Microsoft Excel bằng cách sử dụng Java Thư viện. 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft <sup> & reg; </sup> Chuyển đổi và tạo biểu đồ tệp Excel qua Java" h2="Chuyển đổi biểu đồ tài liệu Excel sang hình ảnh cũng như tạo các biểu đồ khác nhau bằng cách sử dụng API phía máy chủ trong các ứng dụng dựa trên Java." >}}


{{% blocks/products/pf/feature-page-summary %}}

Phân tích dữ liệu qua biểu đồ cho thấy bức tranh toàn cảnh hơn và dễ dàng đưa ra quyết định sáng suốt hơn với những hiểu biết rõ ràng hơn. [Java Thư viện Excel](/cells/java/) hỗ trợ vẽ tạo biểu đồ khác nhau được liệt kê bởi [ChartType](https://apireference.aspose.com/cells/java/com.aspose.cells/ChartType) bao gồm biểu đồ hình tròn, kim tự tháp, đường và biểu đồ bong bóng. Hơn nữa, nó cũng chuyển đổi biểu đồ thành hình ảnh. API cung cấp một [Lớp biểu đồ](https://apireference.aspose.com/cells/java/com.aspose.cells/Chart) để biểu diễn một biểu đồ Excel.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Chuyển đổi Biểu đồ Excel sang Hình ảnh" %}}

Quá trình chuyển đổi biểu đồ sang hình ảnh bao gồm JPG, PNG, TIFF, BMP, v.v. là, Sử dụng [Sách bài tập](https://apireference.aspose.com/java/cells/com.aspose.cells/workbook) lớp để tải tệp Excel, hãy chọn [bàn làm việc](https://apireference.aspose.com/cells/java/com.aspose.cells/worksheet) chứa các biểu đồ hoặc lặp lại qua từng biểu đồ trong mỗi trang tính. Định nghĩa [ImageOrPrintOptions](https://apireference.aspose.com/cells/java/com.aspose.cells/ImageOrPrintOptions) và hiển thị hình ảnh đầu ra của Biểu đồ bằng cách sử dụng [Chart.toImage](https://apireference.aspose.com/cells/java/com.aspose.cells/chart#toImage(java.io.OutputStream,%20com.aspose.cells.ImageOrPrintOptions)).


{{% blocks/products/pf/feature-page-code h3="Java Mã để Chuyển đổi Biểu đồ Excel sang Hình ảnh" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "render-excel-chart-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}


{{% blocks/products/pf/feature-page-section h2="Tạo biểu đồ trong tệp Excel" %}}

Tạo biểu đồ bằng Excel API rất đơn giản, vì API cung cấp tập hợp các lớp khác nhau như Axis, Chart, ChartArea, ChartDataTable, ChartFrame, ChartPoint, ChartPointCollection, ChartCollection, v.v. cho các loại biểu đồ khác nhau. Quy trình là Tạo đối tượng lớp Workbook và chọn trang tính đầu tiên hoặc trang tính có liên quan bằng cách cung cấp chỉ mục của nó. Đối với nguồn dữ liệu của biểu đồ, hãy chèn giá trị vào các ô trang tính bằng cách sử dụng [đặt giá trị](https://apireference.aspose.com/cells/java/com.aspose.cells/cell#Value) phương pháp. Sử dụng bộ sưu tập ChartCollection của [thêm phương pháp](https://apireference.aspose.com/cells/java/com.aspose.cells/chartcollection#add(int,%20int,%20int,%20int,%20int)) để thêm biểu đồ, xác định loại biểu đồ với kiểu liệt kê ChartType. Truy cập đối tượng Biểu đồ mới từ bộ sưu tập ChartCollection bằng cách chuyển chỉ mục của nó. Sử dụng [Bộ sưu tập](https://apireference.aspose.com/cells/java/com.aspose.cells/SeriesCollection) đối tượng biểu đồ để chỉ định nguồn dữ liệu của biểu đồ.

{{% blocks/products/pf/feature-page-code h3="Java Mã để Tạo Biểu đồ Excel" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "create-excel-chart-pyramid.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}