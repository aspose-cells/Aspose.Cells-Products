---
title: Quản lý siêu dữ liệu tệp Excel via Java
description: Xem, thêm, chỉnh sửa, xóa hoặc trích xuất siêu dữ liệu tệp Excel chỉ bằng vài dòng mã Java
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Quản lý Microsoft<sup>&reg;</sup> Siêu dữ liệu tệp Excel via Java" h2="Xem, thêm, cập nhật, xóa hoặc trích xuất các thuộc tính tệp Excel tích hợp và tùy chỉnh bằng API Java phía máy chủ." >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Excel API](/cells/vi/java/) hỗ trợ quản lý các thuộc tính tích hợp (do hệ thống xác định) chẳng hạn như tiêu đề, tên tác giả, thống kê tài liệu, v.v. cũng như các thuộc tính tùy chỉnh (do người dùng xác định) ở dạng cặp tên/giá trị. Có[lớp sách bài tập](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) để tải các tập tin, và[Bộ sưu tập bảng tính](https://reference.aspose.com/cells/java/com.aspose.cells/WorksheetCollection)giao dịch với bộ sưu tập các bảng tính cũng như[lớp bảng tính](https://reference.aspose.com/cells/java/com.aspose.cells/Worksheet) để đại diện cho bảng tính duy nhất. Để truy cập các thuộc tính dựng sẵn và tùy chỉnh, BuildInDocumentProperties, CustomDocumentProperties giúp quy trình quản lý siêu dữ liệu trở nên đơn giản.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Quản lý các thuộc tính do hệ thống xác định" %}}

 Để quản lý các thuộc tính tích hợp, API cung cấp[BuildInDocumentProperties](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#BuiltInDocumentProperties) và các lập trình viên có thể dễ dàng truy cập một thuộc tính tích hợp sẵn và cập nhật giá trị của nó. Tùy thuộc vào yêu cầu của ứng dụng, nhà phát triển có thể sử dụng chỉ mục hoặc tên thuộc tính từ[Bộ sưu tập tài sản tài liệu](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentPropertyCollection). 

{{% blocks/products/pf/feature-page-code h3="Java Mã để quản lý các thuộc tính do hệ thống xác định" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "update-system-defined-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Thêm và xóa siêu dữ liệu được xác định tùy chỉnh" %}}

Để xử lý các thuộc tính tùy chỉnh, API cung cấp[Thuộc tính tài liệu tùy chỉnh](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#CustomDocumentProperties) và các nhà phát triển có thể dễ dàng truy cập các thuộc tính hiện có cũng như thêm các thuộc tính mới bằng cách sử dụng[thêm phương pháp](https://reference.aspose.com/cells/java/com.aspose.cells/customdocumentpropertycollection#add(java.lang.String,%20boolean) ) của[CustomDocumentPropertyCollection](https://reference.aspose.com/cells/java/com.aspose.cells/CustomDocumentPropertyCollection) lớp thêm thuộc tính và trả về một tham chiếu cho thuộc tính mới dưới dạng[Thuộc tính.DocumentProperty](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentProperty)sự vật. Lớp DocumentProperty được sử dụng để truy xuất tên, giá trị và loại thuộc tính tài liệu dưới dạng[Tài liệuProperty.Name](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Name), [Tài liệuProperty.Value](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Value),  [Tài liệuProperty.Type](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Type) trả về một trong những[Loại tài sản](https://reference.aspose.com/cells/java/com.aspose.cells/PropertyType) các giá trị liệt kê.
 
{{% blocks/products/pf/feature-page-code h3="Java Mã để thêm siêu dữ liệu trong tệp Excel" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "add-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="Java Mã để xóa thuộc tính tùy chỉnh trong tệp Excel" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "remove-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
