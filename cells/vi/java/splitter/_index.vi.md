---
title: Chia Bảng tính Excel thành các Trang tính trong Java
description: Java mã nguồn giải thích cách chia Microsoft tệp Excel thành nhiều tài liệu bằng thư viện Java Excel
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Tách tệp Excel via Java" h2="Tách bảng tính Excel thành các trang tính trong các ứng dụng dựa trên Java" >}}
{{% blocks/products/pf/feature-page-summary %}}
 Có nhiều tình huống khác nhau, Khi cần chia nhỏ các tệp Excel như bảng tính chứa dữ liệu học sinh với việc phân bổ một trang tính cho mỗi học sinh. Và cần phải chia từng tờ học sinh một cách khôn ngoan thành một tệp riêng biệt. Để tự động hóa ứng dụng via Java,[Java Excel API](/cells/vi/java/) có để chia nhỏ tài liệu Excel theo chiều dọc. Các định dạng được hỗ trợ bao gồm XLS, XLSX, XLSB, XLSM, ODS.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Tách tài liệu Excel thành nhiều tệp" %}}

 Cách đơn giản nhất để chia tệp Excel thành trang tính là Truy cập tất cả các trang tính, lặp qua từng trang tính và lưu từng trang một ở định dạng mong muốn. Để tải trang tính, API cung cấp[Sách bài tập](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) lớp học.[getWorksheets().getCount()](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#Count) phương pháp lấy tổng số tờ. Lặp lại qua từng trang tính và sử dụng[getWorksheets().get(sheetindex)](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#get)để truy cập trang tính cụ thể. Di chuyển dữ liệu trang tính đã chọn vào đối tượng lớp Workbook mới được tạo bằng cách sử dụng[phương pháp sao chép](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#copy(com.aspose.cells.Workbook)). Cuối cùng lưu nó vào định dạng cần thiết.

{{% blocks/products/pf/feature-page-code h3="Java Code Tách File Excel" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-xls-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="Chia trang tính Excel thành các ngăn" %}}

API cũng cung cấp chức năng chia trang tính Excel thành các bảng khác nhau. Quy trình là, Tải tệp bằng lớp Workbook. Chọn trang tính đầu tiên hoặc bất kỳ trang tính nào được yêu cầu bằng cách cung cấp chỉ mục của nó. Gọi setActiveCell có chỉ số ô liên quan làm tham số. Và cuối cùng chia cửa sổ trang tính thành các ô khác nhau bằng cách gọi phương thức split().

{{% blocks/products/pf/feature-page-code h3="Java Mã để chia Trang tính Excel thành Chế độ xem ngăn" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-excel-spreadsheet-into-panes.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
