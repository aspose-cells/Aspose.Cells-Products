---
title: Tài liệu XLSB hình mờ qua Java 
weight: 5900
url: /vi/java/watermark/xlsb/ 
description: Java mã mẫu để thêm hoặc xóa hình mờ vào tệp XLSB trên Java Môi trường thời gian chạy cho Ứng dụng JSP / JSF và Ứng dụng trên máy tính để bàn.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Thêm Hình mờ Văn bản vào XLSB qua Java" h2="Tạo ứng dụng Java của riêng bạn để tạo hình mờ các tệp XLSB bằng cách sử dụng API phía máy chủ." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSB" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Cách tạo hình mờ tệp XLSB bằng cách sử dụng Java" %}}

 Để làm mờ tệp XLSB, chúng tôi sẽ sử dụng
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API là một nền tảng API for Java tạo vân nước giàu tính năng, mạnh mẽ và dễ sử dụng. Bạn có thể tải xuống phiên bản mới nhất của nó trực tiếp từ
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) 
 và cài đặt nó trong dự án dựa trên Maven của bạn bằng cách thêm các cấu hình sau vào pom.xml.

{{% blocks/products/pf/agp/code-block title="Kho" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/ </url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Sự phụ thuộc" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="Các bước để thêm hình mờ vào XLSB qua Java" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. Tạo một đối tượng Workbook mới1. Chọn Trang tính thông qua chỉ mục của nó1. Tạo một Hình dạng và sử dụng chức năng addTextEffect của nó1. Đặt màu sắc, độ trong suốt và hơn thế nữa1. Lưu sổ làm việc ở định dạng XLSB
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="yêu cầu hệ thống" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java hỗ trợ trên tất cả các nền tảng và Hệ điều hành chính. Vui lòng đảm bảo rằng bạn có các điều kiện tiên quyết sau.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows hoặc một hệ điều hành tương thích với Java Môi trường thời gian chạy cho Ứng dụng JSP / JSF và Ứng dụng trên máy tính để bàn.- Tải phiên bản mới nhất của Aspose.Cells for Java trực tiếp từ Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Thêm Hình mờ vào XLSB - Java" offSpacer="" %}}

```cs

// Khởi tạo một Workbook mới
Workbook workbook = new Workbook();

// Lấy trang tính mặc định đầu tiên
Worksheet sheet = workbook.getWorksheets().get(0);

// Thêm hình mờ
Shape wordart = sheet.getShapes().addTextEffect(MsoPresetTextEffect.TEXT_EFFECT_1, "CONFIDENTIAL",
		"Arial Black", 50, false, true, 18, 8, 1, 1, 130, 800);

// Nhận định dạng điền của nghệ thuật chữ
FillFormat wordArtFormat = wordart.getFill();

// Đặt màu
wordArtFormat.setOneColorGradient(Color.getRed(), 0.2, GradientStyleType.HORIZONTAL, 2);

// Đặt độ trong suốt
wordArtFormat.setTransparency(0.9);

// Làm cho đường vô hình
LineFormat lineFormat = wordart.getLine();
lineFormat.setWeight(0.0);

// Lưu các tập tin
workbook.save(dataDir + "AWArtWToWorksheet_out.xlsb");  


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Giới thiệu về Aspose.Cells for Java API" %}}

 Aspose.Cells API có thể được sử dụng để tạo, chỉnh sửa, chuyển đổi và hiển thị các định dạng Microsoft Excel sang các định dạng khác nhau. Hơn nữa, nó có thể được sử dụng để lập biểu đồ toàn diện, báo cáo có thể mở rộng và tính toán đáng tin cậy trong các ứng dụng phần mềm. Aspose.Cells là một phần mềm độc lập API và nó không yêu cầu bất kỳ phần mềm nào như Microsoft hoặc OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Watermark XLSB qua ứng dụng trực tuyến" sectionDescription="Thêm hình mờ vào tài liệu XLSB bằng cách truy cập [Trang web Demos Trực tiếp](https://products.aspose.app/cells/watermark). Bản demo trực tiếp có những lợi ích sau" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Không cần tải xuống hoặc thiết lập bất cứ thứ gì" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Không cần viết bất kỳ mã nào" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Chỉ cần tải lên tệp XLSB của bạn, đặt hình mờ và nhấn nút \"Thêm\"" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Nhận ngay liên kết tải xuống cho tệp kết quả" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSB" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsb/" >}}
Định dạng tệp XLSB chỉ định Định dạng tệp nhị phân Excel, là một tập hợp các bản ghi và cấu trúc chỉ định nội dung sổ làm việc Excel. Nội dung có thể bao gồm các bảng không có cấu trúc hoặc bán cấu trúc của số, văn bản hoặc cả số và văn bản, công thức, kết nối dữ liệu bên ngoài, biểu đồ và hình ảnh. Không giống như XLSX (dựa trên định dạng tệp Open XML), XLSB đại diện cho tệp sổ làm việc Excel nhị phân. Các tệp XLSB có thể được đọc và ghi nhanh hơn, điều này làm cho chúng hữu ích khi làm việc với các tệp lớn. XLSB hiếm khi được sử dụng để lưu trữ sổ làm việc vì XLSX (và trước đây là XLS) là định dạng tệp được người dùng lựa chọn phổ biến nhất để lưu sổ làm việc. Nó có thể được mở bằng Microsoft Office 2007 trở lên.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Các định dạng đánh dấu nước được hỗ trợ khác" subTitle="Sử dụng Java, người ta có thể dễ dàng đánh dấu các định dạng khác nhau bao gồm." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/watermark/ods/" name="ODS" description="Tệp bảng tính OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/watermark/xls/" name="XLS" description="Định dạng nhị phân Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/watermark/xlsm/" name="XLSM" description="Tệp Spreasheet" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}