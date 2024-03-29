---
title: Chèn ảnh/Biểu tượng SVG vào Excel via Java
weight: 10
description: Chèn đối tượng sử dụng Aspose.Cells' Java API không cần bất kỳ phần mềm nào như Microsoft hay Open Office, Adobe PDF, v.v.
keywords: [Java Aspose.Cells., Java add SVG images/Icons into Excel., Java insert SVG images/Icons into Excel., Java create SVG images/Icons in Excel]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Chèn ảnh/Biểu tượng SVG vào Excel via Java" h2="Chèn SVG hình ảnh/Biểu tượng bằng Aspose.Cells\' API không cần bất kỳ phần mềm nào như Microsoft hay Open Office, Adobe PDF, v.v." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSX" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content %}}

Bạn không muốn thấy hình ảnh bị kéo giãn và nén trên bất kỳ thiết bị nào?

Bạn không muốn hình ảnh bị mờ khi phóng to?

Bạn không muốn hình ảnh bị méo ở độ phân giải cao?

Có lẽ SVG là một lựa chọn tốt. Hình ảnh SVG trông đẹp ở mọi mức thu phóng và chúng không phụ thuộc vào độ phân giải. Do độ trung thực cao của hình ảnh svg nên nó rất phổ biến đối với người dùng Excel.

Khi sử dụng Excel, bạn có thể gặp phải các vấn đề sau:

+ File Excel mục tiêu không thể thao tác trực tiếp bằng tay mà phải có chương trình để xử lý.
+ Chèn số lượng lớn ảnh svg vào cùng một file Excel.
+ Chèn hình ảnh svg vào số lượng lớn các file Excel khác nhau.

 Để giải quyết những vấn đề này, chúng tôi khuyên bạn nên sử dụng[Aspose.Cells](https://products.aspose.com/cells/)thư viện. Nó chứa nhiều giao diện phổ biến để xử lý các tệp excel và là một công cụ rất hữu ích.

{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="Cách chèn ảnh/biểu tượng SVG vào file Excel bằng Microsoft Excel" %}}

![](/cells/vi/net/icons/insert-icons-to-excel/sample.png)

Microsoft Excel cung cấp cho chúng ta ba cách để chèn svg:

+  **Chèn hình ảnh/Biểu tượng SVG cục bộ**

Bạn chỉ cần kéo và thả tệp SVG vào một vị trí cụ thể trong tài liệu. Hoặc bạn có thể chọn đường dẫn "*Insert -> Picture -> This Device...*" từ ribbon.

+  **Chèn hình ảnh/Biểu tượng cài sẵn SVG**

Microsoft Excel đã cung cấp cho chúng ta những hình ảnh svg cài sẵn để chúng ta lựa chọn. Bạn có thể mở hộp thoại lựa chọn bằng cách chọn đường dẫn "*Insert -> Picture -> Stock Images...*" từ ribbon. Hầu hết các tệp svg đều nằm trong tùy chọn "Biểu tượng" trong Hình ảnh có sẵn.

+  **Chèn SVG hình ảnh/Biểu tượng từ web**

Nếu không có cách nào ở trên đáp ứng được nhu cầu của bạn, bạn cũng có thể tìm kiếm kết quả mong muốn từ Internet thông qua Microsoft Excel. Bạn có thể mở hộp thoại lựa chọn bằng cách chọn "*Insert -> Picture -> Online Pictures...* " đường dẫn từ dải băng.

{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="Cách chèn ảnh/biểu tượng SVG vào file Excel bằng Java" %}}

 Để chèn hình ảnh/Biểu tượng SVG vào file excel chúng ta sẽ sử dụng
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API là nền tảng giàu tính năng, mạnh mẽ và dễ sử dụng API for Java. Bạn có thể tải xuống phiên bản mới nhất của nó trực tiếp từ
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) 
 và cài đặt nó trong dự án dựa trên Maven của bạn bằng cách thêm các cấu hình sau vào pom.xml.

{{% blocks/products/pf/agp/code-block title="Kho" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="phụ thuộc" offSpacer="true" %}}

```cs

<dependency>
<groupId>com.aspose</groupId>
<artifactId>aspose-cells</artifactId>
<version>version of aspose-cells API</version>
<classifier>jdk17</classifier>
</dependency>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Các bước chèn ảnh/Biểu tượng SVG vào file Excel via Java" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

+ Khởi tạo một đối tượng Workbook.(hoặc->Tải file XLSX với đường dẫn đầy đủ.)
+ Chọn Worksheet thông qua chỉ mục của nó.
 + Sử dụng[thêm phương pháp](https://reference.aspose.com/cells/java/com.aspose.cells/shapecollection/#addIcons-int-int-int-int-int-int-byte---byte---) để chèn chú thích vào bảng tính đã chọn
+ Lưu sổ làm việc ở định dạng XLSX.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="yêu cầu hệ thống" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java hỗ trợ trên tất cả các nền tảng và Hệ điều hành chính. Hãy đảm bảo rằng bạn có các điều kiện tiên quyết sau đây.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows hoặc hệ điều hành tương thích với Java Môi trường thời gian chạy cho ứng dụng JSP/JSF và ứng dụng máy tính để bàn.
- Nhận phiên bản mới nhất Aspose.Cells for Java trực tiếp từ Maven.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Chèn SVG hình ảnh/Biểu tượng - Java" offSpacer="" %}}

{{< gist "aspose-cells-gists" "5876dc77e47649b66bdb5deefb4b5639" "InsertIconsIntoWorksheet.java" >}}

{{% /blocks/products/pf/agp/code-block %}}


{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Giới thiệu Aspose.Cells for Java API" %}}

 Aspose.Cells API có thể được sử dụng để tạo, chỉnh sửa, chuyển đổi và hiển thị định dạng Microsoft Excel sang các định dạng khác nhau. Hơn nữa, nó có thể được sử dụng để lập biểu đồ toàn diện, báo cáo có thể mở rộng và tính toán đáng tin cậy trong các ứng dụng phần mềm. Aspose.Cells là API độc lập và không yêu cầu bất kỳ phần mềm nào như Microsoft hoặc OpenOffice.


    {{% /blocks/products/pf/agp/content %}}

    


{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
