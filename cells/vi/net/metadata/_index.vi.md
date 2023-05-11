---
title: Quản lý siêu dữ liệu tệp Excel via .NET C#
description: Xem, thêm, chỉnh sửa, xóa hoặc trích xuất siêu dữ liệu tệp Excel chỉ bằng vài dòng mã C#
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Quản lý Microsoft<sup>&reg;</sup> Siêu dữ liệu tệp Excel via .NET" h2="Xem, thêm, cập nhật, xóa hoặc trích xuất các thuộc tính tệp Excel tùy chỉnh và tích hợp sẵn bằng API .NET phía máy chủ." >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Excel API](/cells/vi/net/) hỗ trợ quản lý các thuộc tính do hệ thống xác định (tích hợp sẵn) chẳng hạn như tiêu đề, tên tác giả, thống kê tài liệu, v.v. cũng như các thuộc tính do người dùng xác định (tùy chỉnh) ở dạng cặp tên-giá trị. Có[lớp sách bài tập](https://reference.aspose.com/cells/net/aspose.cells/workbook) để tải các tập tin, và[Bộ sưu tập bảng tính](https://reference.aspose.com/cells/net/aspose.cells/worksheetcollection) giao dịch với bộ sưu tập các bảng tính cũng như[lớp bảng tính](https://reference.aspose.com/cells/net/aspose.cells/worksheet) để đại diện cho bảng tính duy nhất. Cùng với các lớp này, BuildInDocumentProperties, CustomDocumentProperties làm cho quy trình quản lý siêu dữ liệu trở nên đơn giản.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Quản lý thuộc tính tích hợp" %}}

 Để quản lý các thuộc tính do hệ thống xác định, API cung cấp[BuildInDocumentProperties](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/builtindocumentproperties) và các lập trình viên có thể dễ dàng truy cập một thuộc tính tích hợp sẵn và cập nhật giá trị của nó. Tùy thuộc vào yêu cầu của ứng dụng, nhà phát triển có thể sử dụng chỉ mục hoặc tên thuộc tính từ[Bộ sưu tập tài sản tài liệu](https://reference.aspose.com/cells/net/aspose.cells.properties/documentpropertycollection). 

{{% blocks/products/pf/feature-page-code h3="C# Mã để quản lý thuộc tính dựng sẵn" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "manage-system-defined-excel-file-metadata.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Quản lý thuộc tính được xác định tùy chỉnh" %}}

 Để quản lý các thuộc tính do người dùng xác định, API cung cấp[Thuộc tính tài liệu tùy chỉnh](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/customdocumentproperties) và các nhà phát triển có thể dễ dàng truy cập các thuộc tính đã thêm cũng như thêm các thuộc tính mới. Để thêm thuộc tính tùy chỉnh,[thêm phương pháp](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection/methods/add/index) của[CustomDocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection) lớp thêm thuộc tính và trả về một tham chiếu cho thuộc tính mới dưới dạng[Thuộc tính.DocumentProperty](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty) sự vật. Lớp DocumentProperty được sử dụng để truy xuất tên, giá trị và loại thuộc tính tài liệu dưới dạng[Tài liệuProperty.Name](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/name), [Tài liệuProperty.Value](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/value),  [Tài liệuProperty.Type](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/type) trả về một trong những[Loại tài sản](https://reference.aspose.com/cells/net/aspose.cells.properties/propertytype) các giá trị liệt kê.
 
{{% blocks/products/pf/feature-page-code h3="C# Mã để thêm siêu dữ liệu trong tệp Excel" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "add-metadata-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="C# Mã để xóa thuộc tính tùy chỉnh trong tệp Excel" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "remove-custom-properties-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
