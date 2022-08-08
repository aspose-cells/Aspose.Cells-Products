---
title: Quản lý Siêu dữ liệu Tệp Excel qua .NET C#
url: /vi/net/metadata/
description: Xem, thêm, chỉnh sửa, xóa hoặc trích xuất siêu dữ liệu tệp Excel chỉ với vài dòng mã C#
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Quản lý Microsoft <sup> & reg; </sup> Siêu dữ liệu tệp Excel qua .NET" h2="Xem, thêm, cập nhật, xóa hoặc trích xuất các thuộc tính tệp Excel được tích hợp sẵn và tùy chỉnh bằng cách sử dụng .NET API phía máy chủ." >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Excel API](/cells/net/) hỗ trợ quản lý các thuộc tính do hệ thống xác định (tích hợp sẵn) như tiêu đề, tên tác giả, thống kê tài liệu, v.v. cũng như các thuộc tính do người dùng xác định (tùy chỉnh) ở dạng cặp tên-giá trị. Có [Lớp sổ làm việc](https://reference.aspose.com/cells/net/aspose.cells/workbook) để tải các tệp và [WorksheetCollection](https://reference.aspose.com/cells/net/aspose.cells/worksheetcollection) giao dịch với bộ sưu tập trang tính cũng như [Lớp trang tính](https://reference.aspose.com/cells/net/aspose.cells/worksheet) để đại diện cho một trang tính. Cùng với các lớp này, BuiltInDocumentProperties, CustomDocumentProperties làm cho quá trình quản lý siêu dữ liệu trở nên đơn giản. 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Quản lý các thuộc tính tích hợp" %}}

Để quản lý các thuộc tính do hệ thống xác định, API cung cấp [BuiltInDocumentProperties](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/builtindocumentproperties), và các lập trình viên có thể dễ dàng truy cập thuộc tính tích hợp sẵn và cập nhật giá trị của nó. Tùy thuộc vào yêu cầu ứng dụng, các nhà phát triển có thể sử dụng chỉ mục hoặc tên thuộc tính từ [DocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/documentpropertycollection). 

{{% blocks/products/pf/feature-page-code h3="C# Mã để Quản lý Thuộc tính Nội trang" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "manage-system-defined-excel-file-metadata.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Quản lý các thuộc tính do tùy chỉnh xác định" %}}

Để quản lý các thuộc tính do người dùng xác định, API cung cấp [CustomDocumentProperties](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/customdocumentproperties)và các nhà phát triển có thể dễ dàng truy cập các thuộc tính đã được thêm vào cũng như thêm các thuộc tính mới. Để thêm các thuộc tính tùy chỉnh, [Thêm phương pháp](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection/methods/add/index) của [CustomDocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection) lớp thêm thuộc tính và trả về một tham chiếu cho thuộc tính mới dưới dạng [Thuộc tính.DocumentProperty](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty) vật. Lớp DocumentProperty được sử dụng để truy xuất tên, giá trị và kiểu của thuộc tính tài liệu dưới dạng [DocumentProperty.Name](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/name), [DocumentProperty.Value](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/value),  [DocumentProperty.Type](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/type) nó trả về một trong những [PropertyType](https://reference.aspose.com/cells/net/aspose.cells.properties/propertytype) các giá trị liệt kê. 
 
{{% blocks/products/pf/feature-page-code h3="C# Mã để Thêm Siêu dữ liệu trong Tệp Excel" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "add-metadata-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="C# Mã để Xóa Thuộc tính Tùy chỉnh trong Tệp Excel" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "remove-custom-properties-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
