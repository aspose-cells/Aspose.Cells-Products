---
title: Xem hoặc chỉnh sửa siêu dữ liệu tệp XLS qua .NET 
weight: 1410
url: /vi/net/metadata/xls/ 
description: C# mã nguồn để chỉnh sửa hoặc xem siêu dữ liệu định dạng XLS trên Nền tảng .NET Framework, .NET Core Mono hoặc Xamarin.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Trích xuất Siêu dữ liệu XLS qua .NET" h2="Tạo ứng dụng .NET của riêng bạn để thêm, chỉnh sửa, xóa hoặc trích xuất siêu dữ liệu từ các tệp XLS bằng cách sử dụng API phía máy chủ." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLS" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Cách trích xuất siêu dữ liệu XLS bằng C#" %}}

 Để trích xuất siêu dữ liệu XLS, chúng tôi sẽ sử dụng
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API là siêu dữ liệu tài liệu giàu tính năng, mạnh mẽ và dễ sử dụng API cho nền tảng C#. Mở
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 quản lý gói, tìm kiếm
 ** Aspose.Cells ** 
 và cài đặt. Bạn cũng có thể sử dụng lệnh sau từ Bảng điều khiển Trình quản lý Gói.

{{% blocks/products/pf/agp/code-block title="Yêu cầu" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Các bước để trích xuất siêu dữ liệu của XLS qua C#" %}}

{{% blocks/products/pf/agp/text %}}

 Truy cập thông tin hữu ích được lưu trữ trong tệp XLS bao gồm thời điểm tệp XLS được nhận, xử lý, đánh dấu thời gian, v.v.

{{% /blocks/products/pf/agp/text %}}

+ Tải XLS với một phiên bản của Workbook
+ Nhận bộ sưu tập BuiltInDocumentProperties của đối tượng Workbook
+ Lặp lại bộ sưu tập
+ Hiển thị Tên thuộc tính, Loại & Giá trị

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="yêu cầu hệ thống" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for .NET được hỗ trợ trên tất cả các hệ điều hành chính. Chỉ cần đảm bảo rằng bạn có các điều kiện tiên quyết sau.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows hoặc hệ điều hành tương thích với Nền tảng .NET Framework, .NET Core Mono hoặc Xamarin.- Môi trường phát triển như Microsoft Visual Studio.- Aspose.Cells for .NET được tham chiếu trong dự án của bạn.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Trích xuất siêu dữ liệu của XLS - C#" offSpacer="" %}}

```cs

// tải XLS với một phiên bản của Workbook
var book = new Aspose.Cells.Workbook("template.xls");
// lặp qua bộ sưu tập BuiltInDocumentProperties
foreach (Aspose.Cells.Properties.DocumentProperty property in book.Worksheets.BuiltInDocumentProperties)
{
    Console.WriteLine($"\tType:\t{property.Type}");

    // Một số thuộc tính có thể lưu trữ nhiều giá trị
    if (property.Value is Array)
    {
        foreach (object value in property.Value as Array)
            Console.WriteLine($"\tValue:\t\"{value}\"");
    }
    else
    {
        Console.WriteLine($"\tValue:\t\"{property.Value}\"");
    }
}  


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Giới thiệu về Aspose.Cells for .NET API" %}}

 Aspose.Cells API có thể được sử dụng để tạo, chỉnh sửa, chuyển đổi và hiển thị các định dạng Microsoft Excel sang các định dạng khác nhau. Hơn nữa, nó có thể được sử dụng để lập biểu đồ toàn diện, báo cáo có thể mở rộng và tính toán đáng tin cậy trong các ứng dụng phần mềm. Aspose.Cells là một phần mềm độc lập API và nó không yêu cầu bất kỳ phần mềm nào như Microsoft hoặc OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Trích xuất siêu dữ liệu của XLS thông qua ứng dụng trực tuyến" sectionDescription="Xem và chỉnh sửa Siêu dữ liệu sang tài liệu XLS bằng cách sử dụng [Bản trình diễn trực tiếp](https://products.aspose.app/cells/metadata) với những lợi ích sau đây." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Không cần tải xuống hoặc thiết lập bất cứ thứ gì" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Không cần viết bất kỳ mã nào" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Chỉ cần tải lên tệp XLS của bạn và chỉnh sửa các thuộc tính tài liệu" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Nhận ngay liên kết tải xuống cho tệp kết quả" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}
Các tệp có phần mở rộng XLS đại diện cho Định dạng tệp nhị phân của Excel. Các tệp như vậy có thể được tạo bằng Microsoft Excel cũng như các chương trình bảng tính tương tự khác như OpenOffice Calc hoặc Apple Numbers. Tệp được lưu bởi Excel được gọi là Sổ làm việc trong đó mỗi sổ làm việc có thể có một hoặc nhiều trang tính. Dữ liệu được lưu trữ và hiển thị cho người dùng ở định dạng bảng trong trang tính và có thể mở rộng giá trị số, dữ liệu văn bản, công thức, kết nối dữ liệu bên ngoài, hình ảnh và biểu đồ. Các ứng dụng như Microsoft Excel cho phép bạn xuất dữ liệu sổ làm việc sang một số định dạng khác nhau bao gồm PDF, CSV, XLSX, TXT, HTML, XPS và một số định dạng khác. Định dạng tệp XLS đã được thay thế bằng định dạng có cấu trúc và mở hơn, XLSX, với việc phát hành Microsoft Excel 2007. Các phiên bản mới nhất vẫn cung cấp hỗ trợ để tạo và đọc tệp XLS, mặc dù XLSX là lựa chọn sử dụng hàng đầu hiện nay.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Các định dạng siêu dữ liệu được hỗ trợ khác" subTitle="Sử dụng C#, Người ta cũng có thể thao túng siêu dữ liệu của nhiều định dạng khác bao gồm." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/metadata/ods/" name="ODS" description="Tệp bảng tính OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/metadata/xlsb/" name="XLSB" description="Tệp sổ làm việc Excel nhị phân" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/metadata/xlsm/" name="XLSM" description="Tệp Spreasheet" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/metadata/xlsx/" name="XLSX" description="Tệp Excel OOXML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}