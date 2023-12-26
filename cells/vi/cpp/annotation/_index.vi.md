---
title: Thêm hoặc xóa chú thích file Excel qua C++
description: Thêm hoặc xóa chú thích dữ liệu của bảng tính Excel, OpenOffice với thư viện C++.
keywords: [C++ Aspose.Cells., add excel annotation., insert excel annotation., access excel annotation., remove excel annotation., delete excel annotation., add annotation in excel., insert annotation in excel., access annotation in excel., remove annotation in excel., delete annotation in excel]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Quản lý Microsoft<sup>&reg;</sup> Chú thích File Excel qua C++" h2="Thêm hoặc xóa các ghi chú đơn giản để chú thích hoặc nhận xét trong các ứng dụng dựa trên C++." >}}
{{% blocks/products/pf/feature-page-summary %}}
[C++ Excel API](/cells/vi/cpp/) cung cấp hỗ trợ quản lý chú thích ở cấp độ ô bằng cách thêm, truy cập và xóa nhận xét. API cung cấp[Bình luận](https://reference.aspose.com/cells/cpp/aspose.cells/comment/) Và[Bộ sưu tập bình luận](https://reference.aspose.com/cells/cpp/aspose.cells/commentcollection/) cũng như[GetComments()](https://reference.aspose.com/cells/cpp/aspose.cells/worksheet/getcomments/)để xử lý các ý kiến về mọi mặt. Các định dạng Excel được hỗ trợ bao gồm ODS, XLS, XLSX, XLSB và XLSM.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Chú thích dữ liệu tệp Excel" %}}
 Thao tác nhận xét trong bảng tính - Không giới hạn số lượng nhận xét trên một trang tính trong MS Excel. Người ta có thể chèn bao nhiêu tùy theo nhu cầu của ứng dụng. Quá trình chèn bình luận là tạo[Sách bài tập](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) đối tượng lớp để tải một tệp hiện có và chọn trang tính nơi bạn muốn thêm nhận xét. Nhận tất cả các nhận xét của nó bằng getComments(). Thêm nhận xét bằng cách sử dụng[Thêm(const char16_t* cellName)](https://reference.aspose.com/cells/cpp/aspose.cells/commentcollection/add/) phương pháp. Lấy chỉ mục ô và sử dụng[Đặt Ghi chú](https://reference.aspose.com/cells/cpp/aspose.cells/comment/setnote/) để chèn bình luận. Hơn nữa, API còn có khả năng xóa mọi bình luận. Một số phương pháp được[ClearComments()](https://reference.aspose.com/cells/cpp/aspose.cells/worksheet/clearcomments/) để Xóa tất cả nhận xét trong bảng tính của nhà thiết kế. Hơn thế nữa,***XóaTại*** phương thức để loại bỏ phần tử tại một chỉ mục được chỉ định hoặc với tên được chỉ định.

{{% blocks/products/pf/feature-page-code h3="C++ Mã để thêm nhận xét trong tệp Excel" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "add-comment-in-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}
