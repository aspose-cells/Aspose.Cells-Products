---
title: Chú thích tệp Excel qua C++
description: Thêm bớt ghi chú chú thích dữ liệu bảng tính Excel, OpenOffice với thư viện C++.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Quản lý Microsoft<sup>&reg;</sup> Chú thích tệp Excel qua C++" h2="Thêm hoặc xóa các ghi chú đơn giản cho chú thích hoặc nhận xét trong các ứng dụng dựa trên C++." >}}
{{% blocks/products/pf/feature-page-summary %}}
[C++ Excel API](/cells/vi/cpp/) cung cấp hỗ trợ để quản lý chú thích ở cấp ô bằng cách thêm, truy cập và xóa nhận xét. API cung cấp[iComment](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment) Và[Bộ sưu tập IComment](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection) cũng như[GetIComments()](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ae7cce5f85b7b25a1e5c58df1b613ca5a)để xử lý các ý kiến về mọi mặt. Các định dạng Excel được hỗ trợ bao gồm ODS, XLS, XLSX, XLSB và XLSM.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Chú thích dữ liệu tệp Excel" %}}
 Thao tác Nhận xét trong Trang tính - Không giới hạn số lượng nhận xét mà một trang tính có trong MS Excel. Người ta có thể chèn bao nhiêu tùy theo nhu cầu của ứng dụng. Quy trình chèn bình luận là, tạo[iWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) class để tải một tệp hiện có và chọn trang tính nơi bạn muốn thêm nhận xét. Nhận tất cả các bình luận của nó bằng cách sử dụng getComments(). Thêm nhận xét bằng cách sử dụng[Thêm vào](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection#a3f014415e292fa15c6220e9727dad384) (xâm nhập_ptr< Aspose::Cells::Systems::String > phương thức cellName). Lấy chỉ mục ô và sử dụng[setNote](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment#a791b9d4e9bf3975709a7f93b5db09580) để chèn bình luận. Hơn nữa, API có khả năng xóa tất cả các bình luận. Rất ít phương pháp được[ClearComments()](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ad4e0ea291ae60fc1b5d815e520edc6c3) để Xóa tất cả nhận xét trong bảng tính của nhà thiết kế. Hơn thế nữa,[Loại bỏ At](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet_collection#addabcc7d7d76874694018fb3ba37b72c)(xâm nhập_ptr< Aspose::Cells::Systems::String > name) để xóa phần tử tại một chỉ mục được chỉ định hoặc với tên được chỉ định.

{{% blocks/products/pf/feature-page-code h3="C++ Mã để thêm nhận xét trong tệp Excel" %}}

{{< gist "aspose-com-gists" "e144512d2c395c3336f12ce960424686" "add-comment-in-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}
