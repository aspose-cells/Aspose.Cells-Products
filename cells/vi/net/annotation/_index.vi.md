---
title: Chú thích tệp Excel NET C#
description: Thêm hoặc xóa chú thích dữ liệu của bảng tính Excel và OpenOffice chỉ bằng vài dòng mã C#.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Xóa Microsoft<sup>&reg;</sup> Chú thích tệp Excel via .NET" h2="Thêm hoặc xóa các chú thích tệp Excel bằng mã C# trong các ứng dụng dựa trên .NET." >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Thư Viện Excel](/cells/vi/net/) cung cấp hỗ trợ để quản lý chú thích ở cấp ô bằng cách thêm, truy cập và xóa nhận xét. Sử dụng nhận xét ở cấp ô, thông tin liên quan có thể được lưu trữ cho người dùng cuối. Các định dạng tệp được hỗ trợ bao gồm ODS, XLS, XLSX, XLSB và XLSM.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Chú thích dữ liệu tệp Excel" %}}
 Quản lý Nhận xét trong Trang tính - Không có bất kỳ giới hạn nào về số lượng nhận xét mà một trang tính có trong MS Excel. Người ta có thể thêm bao nhiêu tùy theo yêu cầu của ứng dụng. chúng tôi sẽ sử dụng[Nhận xét lớp học](https://reference.aspose.com/cells/net/aspose.cells/comment)cho tất cả các chức năng này.

+ Nạp file Excel sử dụng đối tượng lớp Workbook
+ Truy cập Bảng tính có liên quan và chỉ mục Cell có liên quan của nó
+ Gọi RemoveAt với Id Cell để gỡ bỏ nó
 + Sử dụng[lưu ý thuộc tính](https://reference.aspose.com/cells/net/aspose.cells/comment/properties/note) để thêm nội dung bình luận
+ Lưu workbook trước & sau khi gọi phương thức RemoveAt để so sánh

{{% blocks/products/pf/feature-page-code h3="C# Mã Truy cập, Chèn và Xóa Tệp Excel Cell Bình luận" %}}


{{< gist "aspose-com-gists" "e3dcb9c341b81d4db3a404ca7cd6e4cf" "access-insert-and-delete-excel-files-cell-comments.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}
