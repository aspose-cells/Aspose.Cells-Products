---
title: Quản lý Siêu dữ liệu Tệp Excel qua C++
url: /vi/cpp/metadata/
description: Xem, thêm, chỉnh sửa, xóa hoặc trích xuất siêu dữ liệu tệp Excel bằng thư viện C++
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Quản lý Microsoft <sup> & reg; </sup> Siêu dữ liệu tài liệu Excel qua C++" h2="Xem, chèn, cập nhật, loại bỏ hoặc trích xuất các thuộc tính tài liệu Excel tùy chỉnh và cài sẵn trong các ứng dụng C++." >}}
{{% blocks/products/pf/feature-page-summary %}}
Siêu dữ liệu trong Excel - Cách xem, chèn và xóa siêu dữ liệu tệp excel. [C++ Thư viện Excel](/cells/cpp/) faclitates dễ dàng bằng cách hỗ trợ các thuộc tính cài sẵn / do hệ thống xác định như tên tác giả, tiêu đề, số liệu thống kê tài liệu, v.v. cần thiết để kiểm tra khi nào tệp cuối cùng được sửa đổi hoặc lưu cùng với các thuộc tính tùy chỉnh / do người dùng xác định ở dạng các cặp tên / giá trị. Để tự động hóa quy trình, thư viện hỗ trợ tạo và duy trì các tệp Excel siêu dữ liệu lớn. [Phương thức CreateIWorkbook](https://apireference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8) của [Lớp nhà máy](https://apireference.aspose.com/cells/cpp/class/aspose.cells.factory) Mở Workbook theo đường dẫn, theo luồng và theo FileFormatType đặc biệt. Vì vậy, hãy tải tệp bằng phương thức Appropraite để xử lý thêm. Một số khả năng được liệt kê dưới đây và các nhà phát triển có thể dễ dàng nâng cao mã của họ theo yêu cầu ứng dụng. 
 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Đọc và Cập nhật Thuộc tính Nội trang" %}}

Để tự động hóa các thuộc tính tích hợp, API cung cấp [GetIBuiltInDocumentProperties ()](https://apireference.aspose.com/cells/cpp/class/aspose.cells.metadata.i_workbook_metadata) phương thức trả về một tập hợp DocumentProperties đại diện cho tất cả các thuộc tính tài liệu được tích hợp sẵn của bảng tính. Sau khi truy cập tất cả các thuộc tính nội trang, hãy truy cập các thuộc tính có liên quan bằng cách sử dụng phương thức có liên quan như GetTitle (), GetSubject (), v.v. Để cập nhật các thuộc tính, API cung cấp phương thức như SetTitle, SetSubject, SetAuthor, SetComments, v.v. Xem [bộ sưu tập thuộc tính tài liệu nội trang](https://apireference.aspose.com/cells/cpp/class/aspose.cells.properties.i_built_in_document_property_collection) cho chức năng bắt buộc.

{{% blocks/products/pf/feature-page-code h3="C++ Mã để đọc Thuộc tính do Hệ thống xác định" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "read-system-defined-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C++ Mã để Cập nhật Thuộc tính Nội trang" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "update-built-in-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Xem và thêm các thuộc tính được xác định tùy chỉnh" %}}

Để xử lý các thuộc tính tùy chỉnh, API cung cấp [IWorkbookMetadata :: GetICustomDocumentProperties](https://apireference.aspose.com/cells/cpp/class/aspose.cells.metadata.i_workbook_metadata#a69f0226813ce18c03ebc13b8ca691e79) trả về tất cả bộ sưu tập thuộc tính tài liệu tùy chỉnh của bảng tính. Đầu tiên truy cập các thuộc tính tùy chỉnh thông qua phương pháp này, các nhà phát triển có thể sử dụng các phương pháp liên quan để thêm các thuộc tính như AddIDocumentProperty, AddLinkToContentProperty và tương tự sử dụng UpdateLinkedPropertyValue, UpdateLinkedRange để cập nhật giá trị thuộc tính tài liệu tùy chỉnh liên kết với nội dung và phạm vi được liên kết tương ứng. Các nhà phát triển có thể sử dụng phương pháp có liên quan từ [bộ sưu tập các thuộc tính tài liệu tùy chỉnh](https://apireference.aspose.com/cells/cpp/class/aspose.cells.properties.i_custom_document_property_collection).

{{% blocks/products/pf/feature-page-code h3="C++ Mã để xem thuộc tính tùy chỉnh" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "view-custom-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C++ Mã để Thêm Siêu dữ liệu trong Tệp Excel" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "add-custom-property.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}