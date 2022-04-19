---
title: Chú thích Tệp Excel qua C++
url: /vi/cpp/annotation/
description: Thêm hoặc xóa nhận xét chú thích dữ liệu của bảng tính Excel và OpenOffice với thư viện C++.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Quản lý Microsoft <sup> & reg; </sup> Chú thích Tệp Excel qua C++" h2="Thêm hoặc xóa các ghi chú đơn giản cho chú thích hoặc nhận xét trong các ứng dụng dựa trên C++." >}}
{{% blocks/products/pf/feature-page-summary %}}
[C++ Excel API](/cells/cpp/) cung cấp hỗ trợ để quản lý chú thích ở cấp độ ô bằng cách thêm, truy cập và xóa nhận xét. API cung cấp [IComment](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_comment) và [ICommentCollection](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection) cũng như [GetIComments ()](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ae7cce5f85b7b25a1e5c58df1b613ca5a) để xử lý các ý kiến về mọi mặt. Các định dạng Excel được hỗ trợ bao gồm ODS, XLS, XLSX, XLSB và XLSM.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Chú thích Dữ liệu Tệp Excel" %}}
Thao tác với Nhận xét trong Trang tính - Không giới hạn số lượng nhận xét mà một trang tính có trong MS Excel. Người ta có thể chèn nhiều tùy theo nhu cầu của ứng dụng. Quá trình chèn bình luận là, tạo [IWorkbook](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) đối tượng lớp để tải tệp hiện có và chọn trang tính mà bạn muốn thêm nhận xét. Nhận tất cả các bình luận của nó bằng cách sử dụng getComments (). Thêm nhận xét bằng cách sử dụng [Thêm vào](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection#a3f014415e292fa15c6220e9727dad384)(intrusive_ptr < Aspose::Cells::Systems::String > cellName). Nhận chỉ mục ô và sử dụng [setNote](https://apireference.aspose.com/cells/cpp/com.aspose.cells/comment#Note) để chèn bình luận. Hơn nữa, API có thể xóa tất cả các nhận xét. Một số phương pháp là [ClearComments ()](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ad4e0ea291ae60fc1b5d815e520edc6c3) để Xóa tất cả nhận xét trong bảng tính của nhà thiết kế. Hơn thế nữa, [RemoveAt](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet_collection#addabcc7d7d76874694018fb3ba37b72c)(intrusive_ptr< Aspose::Cells::Systems::String > name) phương thức để loại bỏ phần tử tại một chỉ mục được chỉ định hoặc với tên đã chỉ định.

{{% blocks/products/pf/feature-page-code h3="C++ Mã để thêm nhận xét trong tệp Excel" %}}

{{< gist "aspose-com-gists" "e144512d2c395c3336f12ce960424686" "add-comment-in-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}