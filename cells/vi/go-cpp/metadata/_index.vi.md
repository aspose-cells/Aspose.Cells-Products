---
title: Quản lý siêu dữ liệu tệp Excel bằng Go qua số C++
description: Xem, thêm, chỉnh sửa, xóa hoặc trích xuất siêu dữ liệu của các tệp Excel bằng Go thông qua thư viện C++.
keywords: [Go via C++ Aspose.Cells., Go via C++ view excel metadata., Go via C++ add excel metadata., Go via C++ insert excel metadata., Go via C++ edit excel metadata., Go via C++ remove excel metadata., Go via C++ extract excel metadata., Go via C++ modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Quản lý siêu dữ liệu tài liệu Excel qua Go (C++)" h2="Xem, chèn, cập nhật, xóa hoặc trích xuất các thuộc tính tài liệu Excel tùy chỉnh và tích hợp sẵn trong ứng dụng C++." >}}
{{% blocks/products/pf/feature-page-summary %}}
 Siêu dữ liệu trong Excel - Cách xem, chèn và xóa siêu dữ liệu trong tệp Excel.[Truy cập qua số C++ Thư viện Excel](/cells/vi/go-cpp/)Thư viện hỗ trợ thao tác dễ dàng bằng cách tích hợp các thuộc tính do hệ thống định nghĩa như tên tác giả, tiêu đề, thống kê tài liệu, v.v., đôi khi cần thiết để kiểm tra thời điểm tệp được sửa đổi hoặc lưu lần cuối, cùng với các thuộc tính tùy chỉnh/do người dùng định nghĩa dưới dạng cặp tên/giá trị. Để tự động hóa quy trình, thư viện hỗ trợ tạo và duy trì các tệp Excel siêu dữ liệu lớn.[Sách bài tập](https://reference.aspose.com/cells/go-cpp/workbook/) Lớp này mở một sổ làm việc theo đường dẫn, theo luồng và theo định dạng tệp đặc biệt (FileFormatType). Vì vậy, hãy tải tệp bằng phương pháp thích hợp để xử lý tiếp. Một vài khả năng được liệt kê bên dưới và các nhà phát triển có thể dễ dàng cải tiến mã của họ theo yêu cầu của ứng dụng.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Đọc và cập nhật các thuộc tính tích hợp sẵn" %}}

 Để tự động hóa các thuộc tính tích hợp sẵn, mã sản phẩm API cung cấp...[GetBuiltInDocumentProperties()](https://reference.aspose.com/cells/go-cpp/workbook/getbuiltindocumentproperties/)Phương thức này trả về một tập hợp DocumentProperties đại diện cho tất cả các thuộc tính tài liệu tích hợp sẵn của bảng tính. Sau khi truy cập tất cả các thuộc tính tích hợp sẵn, hãy truy cập các thuộc tính liên quan bằng cách sử dụng phương thức tương ứng như GetTitle(), GetSubject(), v.v. Để cập nhật các thuộc tính, API cung cấp các phương thức như SetTitle, SetSubject, SetAuthor, SetComments, v.v. Xem thêm[bộ sưu tập thuộc tính tài liệu tích hợp](https://reference.aspose.com/cells/go-cpp/workbook/getbuiltindocumentproperties/) cho chức năng cần thiết.

{{% blocks/products/pf/feature-page-code h3="Truy cập mã C++ để đọc các thuộc tính do hệ thống định nghĩa." %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "read-system-defined-properties.go" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Vui lòng sử dụng mã C++ để cập nhật các thuộc tính tích hợp sẵn." %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "update-built-in-properties.go" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Xem và thêm các thuộc tính do người dùng tự định nghĩa." %}}

 Để xử lý các thuộc tính tùy chỉnh, mã số API cung cấp[Sổ làm việc::Lấy thuộc tính tài liệu tùy chỉnh](https://reference.aspose.com/cells/go-cpp/workbook/getcustomdocumentproperties/)Phương thức này trả về toàn bộ tập hợp các thuộc tính tài liệu tùy chỉnh của bảng tính. Trước tiên, khi truy cập các thuộc tính tùy chỉnh thông qua phương thức này, các nhà phát triển có thể sử dụng các phương thức liên quan để thêm thuộc tính như AddIDocumentProperty, AddLinkToContentProperty và tương tự như vậy, sử dụng UpdateLinkedPropertyValue, UpdateLinkedRange để cập nhật giá trị thuộc tính tài liệu tùy chỉnh liên kết đến nội dung và phạm vi liên kết tương ứng. Các nhà phát triển có thể sử dụng phương thức liên quan từ[tập hợp các thuộc tính tài liệu tùy chỉnh](https://reference.aspose.com/cells/go-cpp/workbook/getcustomdocumentproperties/).

{{% blocks/products/pf/feature-page-code h3="Truy cập bằng mã C++ để xem các thuộc tính tùy chỉnh." %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "view-custom-properties.go" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="Truy cập mã C++ để thêm siêu dữ liệu vào tệp Excel." %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "add-custom-property.go" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< /blocks/products/pf/feature-page-wrap >}}