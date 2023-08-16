---
title: Quản lý siêu dữ liệu tệp Excel qua C++
description: Xem, thêm, chỉnh sửa, xóa hoặc trích xuất siêu dữ liệu tệp Excel bằng thư viện C++
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Quản lý Microsoft<sup>&reg;</sup> Siêu dữ liệu tài liệu Excel qua C++" h2="Xem, chèn, cập nhật, xóa hoặc trích xuất các thuộc tính tài liệu Excel tùy chỉnh và tích hợp trong các ứng dụng C++." >}}
{{% blocks/products/pf/feature-page-summary %}}
 Siêu dữ liệu trong Excel - Cách xem, chèn và loại bỏ siêu dữ liệu tệp excel.[C++ Thư Viện Excel](/cells/vi/cpp/) tạo thuận lợi một cách dễ dàng bằng cách hỗ trợ các thuộc tính tích hợp/do hệ thống xác định, chẳng hạn như tên tác giả, tiêu đề, thống kê tài liệu, v.v. đôi khi cần kiểm tra khi tệp cuối cùng được sửa đổi hoặc lưu cùng với các thuộc tính tùy chỉnh/do người dùng xác định ở dạng cặp tên/giá trị. Để tự động hóa quy trình, thư viện hỗ trợ tạo và duy trì các tệp Excel siêu dữ liệu lớn.[Phương thức CreateIWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8) của[lớp nhà máy](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory)Mở Workbook theo đường dẫn, theo luồng và theo FileFormatType đặc biệt. Vì vậy, hãy tải tệp bằng phương pháp thích hợp để xử lý thêm. Rất ít khả năng được liệt kê bên dưới và các nhà phát triển có thể dễ dàng nâng cao mã của họ theo yêu cầu của ứng dụng.
 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Đọc và cập nhật thuộc tính dựng sẵn" %}}

 Để tự động hóa các thuộc tính tích hợp, API cung cấp[GetIBuiltInDocumentProperties()](https://reference.aspose.com/cells/cpp/class/aspose.cells.metadata.i_workbook_metadata) phương thức trả về một bộ sưu tập DocumentProperties đại diện cho tất cả các thuộc tính tài liệu tích hợp sẵn của bảng tính. Sau khi truy cập tất cả các thuộc tính dựng sẵn, hãy truy cập các thuộc tính có liên quan bằng cách sử dụng phương thức có liên quan, chẳng hạn như GetTitle(), GetSubject(), v.v. Để cập nhật các thuộc tính, API cung cấp phương thức như SetTitle, SetSubject, SetAuthor, SetComments, v.v. Xem[bộ sưu tập thuộc tính tài liệu dựng sẵn](https://reference.aspose.com/cells/cpp/class/aspose.cells.properties.i_built_in_document_property_collection) cho chức năng cần thiết.

{{% blocks/products/pf/feature-page-code h3="C++ Mã để đọc các thuộc tính do hệ thống xác định" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "read-system-defined-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C++ Mã để cập nhật thuộc tính dựng sẵn" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "update-built-in-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Xem và thêm thuộc tính được xác định tùy chỉnh" %}}

Để xử lý các thuộc tính tùy chỉnh, API cung cấp[IWorkbookMetadata::GetICustomDocumentProperties](https://reference.aspose.com/cells/cpp/class/aspose.cells.metadata.i_workbook_metadata#a69f0226813ce18c03ebc13b8ca691e79) trả về tất cả bộ sưu tập thuộc tính tài liệu tùy chỉnh của bảng tính. Trước tiên khi truy cập các thuộc tính tùy chỉnh thông qua phương pháp này, nhà phát triển có thể sử dụng các phương pháp có liên quan để thêm các thuộc tính như AddIDocumentProperty, AddLinkToContentProperty và tương tự sử dụng UpdateLinkedPropertyValue, UpdateLinkedRange để cập nhật giá trị thuộc tính tài liệu tùy chỉnh liên kết đến nội dung và phạm vi được liên kết tương ứng. Các nhà phát triển có thể sử dụng phương pháp có liên quan từ[tập hợp các thuộc tính tài liệu tùy chỉnh](https://reference.aspose.com/cells/cpp/class/aspose.cells.properties.i_custom_document_property_collection).

{{% blocks/products/pf/feature-page-code h3="C++ Mã để xem thuộc tính tùy chỉnh" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "view-custom-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C++ Mã để thêm siêu dữ liệu trong tệp Excel" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "add-custom-property.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
