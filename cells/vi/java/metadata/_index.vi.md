---
title: Quản lý Siêu dữ liệu Tệp Excel qua Java
url: /vi/java/metadata/
description: Xem, thêm, chỉnh sửa, xóa hoặc trích xuất siêu dữ liệu tệp Excel chỉ với vài dòng mã Java
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Quản lý Microsoft <sup> & reg; </sup> Siêu dữ liệu tệp Excel qua Java" h2="Xem, thêm, cập nhật, xóa hoặc trích xuất các thuộc tính tệp Excel tùy chỉnh và tích hợp sẵn bằng cách sử dụng API Java phía máy chủ." >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Excel API](/cells/java/) hỗ trợ quản lý các thuộc tính cài sẵn (do hệ thống xác định) như tiêu đề, tên tác giả, thống kê tài liệu, v.v. cũng như các thuộc tính tùy chỉnh (do người dùng xác định) ở dạng cặp tên / giá trị. Có [Lớp sổ làm việc](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) để tải các tệp và [WorksheetCollection](https://apireference.aspose.com/cells/java/com.aspose.cells/WorksheetCollection) giao dịch với bộ sưu tập trang tính cũng như [Lớp trang tính](https://apireference.aspose.com/cells/java/com.aspose.cells/Worksheet) để đại diện cho một trang tính. Để truy cập các thuộc tính nội trang và tùy chỉnh, BuiltInDocumentProperties, CustomDocumentProperties làm cho quá trình quản lý siêu dữ liệu trở nên đơn giản. 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Quản lý các thuộc tính do hệ thống xác định" %}}

Để quản lý các thuộc tính tích hợp, API cung cấp [BuiltInDocumentProperties](https://apireference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#BuiltInDocumentProperties), và các lập trình viên có thể dễ dàng truy cập thuộc tính tích hợp sẵn và cập nhật giá trị của nó. Tùy thuộc vào yêu cầu ứng dụng, các nhà phát triển có thể sử dụng chỉ mục hoặc tên thuộc tính từ [DocumentPropertyCollection](https://apireference.aspose.com/cells/java/com.aspose.cells/DocumentPropertyCollection). 

{{% blocks/products/pf/feature-page-code h3="Java Mã để quản lý các thuộc tính do hệ thống xác định" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "update-system-defined-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Thêm và xóa siêu dữ liệu được xác định tùy chỉnh" %}}

Để xử lý các thuộc tính tùy chỉnh, API cung cấp [CustomDocumentProperties](https://apireference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#CustomDocumentProperties)và các nhà phát triển có thể dễ dàng truy cập các thuộc tính hiện có cũng như thêm các thuộc tính mới bằng cách sử dụng [thêm phương pháp](https://apireference.aspose.com/cells/java/com.aspose.cells/customdocumentpropertycollection#add(java.lang.String,%20boolean)) của [CustomDocumentPropertyCollection](https://apireference.aspose.com/cells/java/com.aspose.cells/CustomDocumentPropertyCollection) lớp thêm thuộc tính và trả về một tham chiếu cho thuộc tính mới dưới dạng [Thuộc tính.DocumentProperty](https://apireference.aspose.com/cells/java/com.aspose.cells/DocumentProperty) vật. Lớp DocumentProperty được sử dụng để truy xuất tên, giá trị và kiểu của thuộc tính tài liệu dưới dạng [DocumentProperty.Name](https://apireference.aspose.com/cells/java/com.aspose.cells/documentproperty#Name), [DocumentProperty.Value](https://apireference.aspose.com/cells/java/com.aspose.cells/documentproperty#Value),  [DocumentProperty.Type](https://apireference.aspose.com/cells/java/com.aspose.cells/documentproperty#Type) nó trả về một trong những [PropertyType](https://apireference.aspose.com/cells/java/com.aspose.cells/PropertyType) các giá trị liệt kê. 
 
{{% blocks/products/pf/feature-page-code h3="Java Mã để Thêm Siêu dữ liệu trong Tệp Excel" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "add-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="Java Mã để Xóa Thuộc tính Tùy chỉnh trong Tệp Excel" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "remove-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
