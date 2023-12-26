---
title: Quản lý siêu dữ liệu tệp Excel qua C++
description: Xem, thêm, sửa, xóa hoặc trích xuất siêu dữ liệu tệp Excel bằng thư viện C++
keywords: [C++ Aspose.Cells., C++ view excel metadata., C++ add excel metadata., C++ insert excel metadata., C++ edit excel metadata., C++ remove excel metadata., C++ extract excel metadata., C++ modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Quản lý Microsoft<sup>&reg;</sup> Siêu dữ liệu tài liệu Excel qua C++" h2="Xem, chèn, cập nhật, xóa hoặc trích xuất các thuộc tính tài liệu Excel tùy chỉnh và tích hợp trong ứng dụng C++." >}}
{{% blocks/products/pf/feature-page-summary %}}
 Metadata trong Excel - Cách xem, chèn và xóa siêu dữ liệu file excel.[C++ Thư viện Excel](/cells/vi/cpp/) tạo điều kiện một cách dễ dàng bằng cách hỗ trợ các thuộc tính tích hợp/do hệ thống xác định như tên tác giả, tiêu đề, số liệu thống kê tài liệu, v.v. đôi khi muốn kiểm tra khi tệp cuối cùng được sửa đổi hoặc lưu cùng với các thuộc tính tùy chỉnh/do người dùng xác định ở dạng cặp tên/giá trị. Để tự động hóa quy trình, thư viện hỗ trợ tạo và duy trì các tệp Excel siêu dữ liệu lớn.[Sách bài tập](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/)class Mở một sổ làm việc theo đường dẫn, theo luồng và theo FileFormatType đặc biệt. Vì vậy hãy tải tệp bằng phương pháp thích hợp để xử lý tiếp. Một số khả năng được liệt kê bên dưới và các nhà phát triển có thể dễ dàng nâng cao mã của họ theo yêu cầu của ứng dụng.
 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Đọc và cập nhật thuộc tính dựng sẵn" %}}

 Để tự động hóa các thuộc tính tích hợp, API cung cấp[GetBuiltInDocumentProperties()](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/getbuiltindocumentproperties/) phương thức trả về bộ sưu tập DocumentProperties đại diện cho tất cả các thuộc tính tài liệu tích hợp của bảng tính. Sau khi truy cập tất cả các thuộc tính dựng sẵn, hãy truy cập các thuộc tính có liên quan bằng phương thức liên quan như GetTitle(), GetSubject(), v.v. Để cập nhật các thuộc tính, API cung cấp phương thức như SetTitle, SetSubject, SetAuthor, SetComments, v.v. Xem[bộ sưu tập thuộc tính tài liệu dựng sẵn](https://reference.aspose.com/cells/cpp/aspose.cells.properties/builtindocumentpropertycollection/) cho chức năng cần thiết.

{{% blocks/products/pf/feature-page-code h3="C++ Mã để đọc thuộc tính do hệ thống xác định" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "read-system-defined-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C++ Mã để cập nhật thuộc tính dựng sẵn" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "update-built-in-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Xem và thêm thuộc tính được xác định tùy chỉnh" %}}

Để xử lý các thuộc tính tùy chỉnh, API cung cấp[Sổ làm việc::GetCustomDocumentProperties](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/getcustomdocumentproperties/) trả về tất cả bộ sưu tập thuộc tính tài liệu tùy chỉnh của bảng tính. Trước tiên, truy cập các thuộc tính tùy chỉnh thông qua phương pháp này, nhà phát triển có thể sử dụng các phương pháp có liên quan để thêm các thuộc tính như AddIDocumentProperty, AddLinkToContentProperty và sử dụng tương tự UpdateLinkedPropertyValue, UpdateLinkedRange để cập nhật giá trị thuộc tính tài liệu tùy chỉnh liên kết đến nội dung và phạm vi được liên kết tương ứng. Các nhà phát triển có thể sử dụng phương pháp liên quan từ[bộ sưu tập các thuộc tính tài liệu tùy chỉnh](https://reference.aspose.com/cells/cpp/aspose.cells.properties/customdocumentpropertycollection/).

{{% blocks/products/pf/feature-page-code h3="C++ Mã để xem thuộc tính tùy chỉnh" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "view-custom-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C++ Mã để thêm siêu dữ liệu vào tệp Excel" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "add-custom-property.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
