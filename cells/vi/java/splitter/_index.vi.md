---
title: Tách bảng tính Excel thành bảng tính ở Java
description: Mã nguồn Java giải thích cách chia file Excel Microsoft thành nhiều tài liệu bằng thư viện Excel Java
keywords: [Java Aspose.Cells., Java split excel files., Java how to split excel files into multiple files., Java excel splitter., Java split Cell., Cell splitter using Java]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Tách file Excel via Java" h2="Chia bảng tính Excel thành các bảng tính trong các ứng dụng dựa trên Java" >}}
{{% blocks/products/pf/feature-page-summary %}}
Có nhiều tình huống khác nhau, Khi cần chia các tệp Excel giống như một bảng tính chứa dữ liệu học sinh với việc phân bổ từng trang tính cho mỗi học sinh. Và cần phải chia mỗi tờ học sinh thành một file riêng biệt. Để tự động hóa ứng dụng via Java,[Java Excel API](/cells/vi/java/) ở đó để chia tài liệu Excel theo từng trang. Các định dạng được hỗ trợ bao gồm XLS, XLSX, XLSB, XLSM, ODS.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Tách tài liệu Excel thành nhiều tệp" %}}

 Cách đơn giản nhất để chia tệp Excel thành trang tính là Truy cập tất cả các trang tính, lặp qua từng trang tính và lưu từng trang tính theo định dạng mong muốn. Để tải bảng tính, API cung cấp[Sách bài tập](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) lớp học.[getWorksheets().getCount()](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#Count) phương pháp nhận được tổng số tờ. Lặp lại qua từng trang tính và sử dụng[getWorksheets().get(sheetindex)](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#get) để truy cập trang tính cụ thể. Di chuyển dữ liệu trang tính đã chọn vào đối tượng lớp Workbook mới được tạo bằng cách sử dụng[Phương pháp sao chép](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#copy(com.aspose.cells.Workbook)). Cuối cùng lưu nó vào định dạng yêu cầu.

{{% blocks/products/pf/feature-page-code h3="Java Mã để chia tệp Excel" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-xls-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="Chia bảng tính Excel thành các ngăn" %}}

API cũng cung cấp chức năng chia bảng tính Excel thành các khung khác nhau. Quá trình là, Tải tệp bằng lớp Workbook. Chọn trang tính đầu tiên hoặc bất kỳ trang tính nào được yêu cầu bằng cách cung cấp chỉ mục của nó. Gọi setActiveCell có tham số là chỉ mục ô liên quan. Và cuối cùng chia cửa sổ bảng tính thành các khung khác nhau bằng cách gọi phương thức Split().

{{% blocks/products/pf/feature-page-code h3="Java Mã để chia trang tính Excel thành dạng xem ngăn" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-excel-spreadsheet-into-panes.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
