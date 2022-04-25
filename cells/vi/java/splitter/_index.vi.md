---
title: Chia Bảng tính Excel thành Trang tính trong Java
url: /vi/java/splitter/
description: Java mã nguồn giải thích cách chia tệp Microsoft Excel thành nhiều tài liệu bằng cách sử dụng Java thư viện Excel
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft <sup> & reg; </sup> Tách tệp Excel qua Java" h2="Chia bảng tính Excel thành các trang tính trong các ứng dụng dựa trên Java" >}}
{{% blocks/products/pf/feature-page-summary %}}
Có nhiều tình huống khác nhau, Khi cần chia các tệp Excel như một bảng tính chứa dữ liệu học sinh với phân bổ từng trang tính cho từng học sinh. Và cần phải tách mỗi học sinh trang tính thành một tệp riêng biệt. Để tự động hóa nó qua ứng dụng Java, [Java Excel API](/cells/java/) ở đó để chia tài liệu Excel theo chiều dọc trang tính. Các định dạng được hỗ trợ bao gồm XLS, XLSX, XLSB, XLSM, ODS. 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Chia tài liệu Excel thành nhiều tệp" %}}

Cách đơn giản nhất để chia tệp Excel thành trang tính là Truy cập tất cả các trang tính, lặp qua từng trang tính và lưu từng trang một ở định dạng mong muốn. Để tải trang tính, API cung cấp [Sách bài tập](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) lớp. [getWorksheets (). getCount ()](https://apireference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#Count) phương thức nhận tổng số trang tính. Lặp lại từng trang tính và sử dụng [getWorksheets (). get (sheetindex)](https://apireference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#get) để truy cập trang tính cụ thể. Di chuyển dữ liệu trang tính đã chọn vào đối tượng lớp Sổ làm việc mới được tạo bằng cách sử dụng [Sao chép phương pháp](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#copy(com.aspose.cells.Workbook)). Cuối cùng lưu nó vào định dạng yêu cầu.

{{% blocks/products/pf/feature-page-code h3="Java Mã để tách các tệp Excel" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-xls-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="Chia bảng tính Excel thành các ngăn" %}}

API cũng cung cấp chức năng chia trang tính Excel thành các ngăn khác nhau. Quy trình là, Tải tệp bằng lớp Workbook. Chọn trang tính đầu tiên hoặc bất kỳ trang tính nào được yêu cầu bằng cách cung cấp chỉ mục của nó. Gọi setActiveCell có chỉ mục ô liên quan làm tham số. Và cuối cùng chia cửa sổ trang tính thành các ngăn khác nhau bằng cách gọi phương thức split ().

{{% blocks/products/pf/feature-page-code h3="Java Mã để tách Trang tính Excel thành Chế độ xem ngăn" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-excel-spreadsheet-into-panes.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}