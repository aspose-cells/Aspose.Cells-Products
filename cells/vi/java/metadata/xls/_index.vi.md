---
title:  Chỉnh sửa hoặc xem XLS Siêu dữ liệu tệp via Java
weight: 730
description: Mã mẫu Java để chỉnh sửa hoặc xem siêu dữ liệu định dạng XLS trên Môi trường thời gian chạy Java cho Ứng dụng JSP/JSF và Ứng dụng máy tính để bàn.
keywords: [Java Aspose.Cells., Java view xls metadata., Java add xls metadata., Java insert xls metadata., Java edit xls metadata., Java remove xls metadata., Java extract xls metadata., Java modify xls metadata]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Trích xuất XLS Siêu dữ liệu via Java" h2="Xây dựng ứng dụng Java của riêng bạn để thêm, chỉnh sửa, xóa hoặc trích xuất siêu dữ liệu từ các tệp XLS bằng API phía máy chủ." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLS" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Cách trích xuất siêu dữ liệu XLS bằng Java" %}}

 Để có được siêu dữ liệu tệp XLS, chúng tôi sẽ sử dụng
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API là nền tảng siêu dữ liệu giàu tính năng, mạnh mẽ và dễ sử dụng API for Java. Bạn có thể tải xuống phiên bản mới nhất của nó trực tiếp từ
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

{{% blocks/products/pf/agp/feature-section-col title="Các bước trích xuất siêu dữ liệu của XLS via Java" %}}

{{% blocks/products/pf/agp/text %}}

 Truy cập thông tin hữu ích được lưu trữ trong tệp XLS bao gồm cả thời điểm tệp XLS được nhận, xử lý, đánh dấu thời gian, v.v.

{{% /blocks/products/pf/agp/text %}}

+ Tải file XLS trong WorkbookMetadata
+ Tạo đối tượng MetadataOptions với các tùy chọn liên quan
+ Thiết lập các thuộc tính liên quan
+ Lưu thông tin siêu dữ liệu XLS

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="yêu cầu hệ thống" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java hỗ trợ trên tất cả các nền tảng và Hệ điều hành chính. Hãy đảm bảo rằng bạn có các điều kiện tiên quyết sau đây.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows hoặc hệ điều hành tương thích với Java Môi trường thời gian chạy cho ứng dụng JSP/JSF và ứng dụng máy tính để bàn.
-  Nhận phiên bản mới nhất của Aspose.Cells for Java trực tiếp từ
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells)  .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Trích xuất siêu dữ liệu của XLS - Java" offSpacer="" %}}

```cs

// Open Workbook metadata
MetadataOptions options = new MetadataOptions(MetadataType.DOCUMENT_PROPERTIES);
WorkbookMetadata meta = new WorkbookMetadata("Sample1.xls", options);

// Set some properties
meta.getCustomDocumentProperties().add("test", "test");

// Save the metadata info
meta.save("Sample1.out.xls");

// Open the workbook
Workbook w = new Workbook("Sample1.out.xls");

// Read document property
System.out.println(w.getCustomDocumentProperties().get("test"));  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Giới thiệu Aspose.Cells for Java API" %}}

 Aspose.Cells API có thể được sử dụng để tạo, chỉnh sửa, chuyển đổi và hiển thị định dạng Microsoft Excel sang các định dạng khác nhau. Hơn nữa, nó có thể được sử dụng để lập biểu đồ toàn diện, báo cáo có thể mở rộng và tính toán đáng tin cậy trong các ứng dụng phần mềm. Aspose.Cells là API độc lập và không yêu cầu bất kỳ phần mềm nào như Microsoft hoặc OpenOffice.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Trích xuất siêu dữ liệu của XLS qua ứng dụng trực tuyến" sectionDescription=" Xem và chỉnh sửa Siêu dữ liệu thành tài liệu XLS bằng cách sử dụng[Bản demo trực tiếp](https://products.aspose.app/cells/metadata) với những lợi ích sau." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Không cần tải xuống hay thiết lập bất cứ thứ gì" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Không cần phải viết bất kỳ mã nào" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Chỉ cần tải lên tệp XLS của bạn và chỉnh sửa thuộc tính tài liệu" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Nhận ngay link tải file kết quả" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}
Các tệp có phần mở rộng XLS biểu thị Định dạng tệp nhị phân Excel. Những tệp như vậy có thể được tạo bởi Microsoft Excel cũng như các chương trình bảng tính tương tự khác như OpenOffice Calc hoặc Apple Numbers. Tệp được lưu bởi Excel được gọi là Sổ làm việc trong đó mỗi sổ làm việc có thể có một hoặc nhiều trang tính. Dữ liệu được lưu trữ và hiển thị cho người dùng ở định dạng bảng trong trang tính và có thể bao gồm các giá trị số, dữ liệu văn bản, công thức, kết nối dữ liệu ngoài, hình ảnh và biểu đồ. Các ứng dụng như Microsoft Excel cho phép bạn xuất dữ liệu sổ làm việc sang nhiều định dạng khác nhau bao gồm PDF, CSV, XLSX, TXT, HTML, XPS và một số định dạng khác. Định dạng tệp XLS đã được thay thế bằng định dạng có cấu trúc và mở hơn, XLSX, với bản phát hành Microsoft Excel 2007. Các phiên bản mới nhất vẫn cung cấp hỗ trợ tạo và đọc tệp XLS, mặc dù XLSX hiện là lựa chọn sử dụng đầu tiên.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Các định dạng siêu dữ liệu được hỗ trợ khác" subTitle="Sử dụng Java, Người ta cũng có thể thao tác siêu dữ liệu ở nhiều định dạng khác bao gồm" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/metadata/ods/" name="ODS" description="Tệp bảng tính OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/metadata/xlsb/" name="XLSB" description="Tệp sổ làm việc Excel nhị phân" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/metadata/xlsm/" name="XLSM" description="Tệp bảng tính" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/metadata/xlsx/" name="XLSX" description="Tệp Excel OOXML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
