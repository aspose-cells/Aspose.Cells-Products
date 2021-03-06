---
title: Mở khóa tài liệu XLS qua .NET 
weight: 4260
url: /vi/net/unlock/xls/ 
description: C# mã nguồn để mở khóa tệp XLS được bảo vệ bằng mật khẩu trên Nền tảng .NET Framework, .NET Core Mono hoặc Xamarin.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Mở khóa Bảng tính XLS qua C#" h2="Xóa bảo vệ khỏi XLS bằng cách sử dụng thư viện .NET." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLS" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Cách mở khóa tệp XLS bằng C#" %}}

 Để xóa tệp XLS bảo vệ, chúng tôi sẽ sử dụng
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API là một nền tảng bảo vệ tài liệu giàu tính năng, mạnh mẽ và dễ sử dụng API cho C#. Mở
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 quản lý gói, tìm kiếm
 ** Aspose.Cells ** 
 và cài đặt. Bạn cũng có thể sử dụng lệnh sau từ Bảng điều khiển Trình quản lý Gói.

{{% blocks/products/pf/agp/code-block title="Aspose.Cells" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Mở khóa XLS qua C#" %}}

{{% blocks/products/pf/agp/text %}}

 Bạn cần
 [aspose.cells.dll](https://downloads.aspose.com/cells/net) 
 được tham chiếu trong dự án của bạn để thực hiện quy trình làm việc sau.

{{% /blocks/products/pf/agp/text %}}

1. Khởi tạo lớp Workbook với đường dẫn đến tệp XLS được bảo vệ1. Lấy trang tính mặc định hoặc bất kỳ Trang tính nào để loại bỏ bảo vệ1. Loại bỏ tính năng bảo vệ Trang tính bằng phương pháp Worksheet.Unprotect1. Loại bỏ tính năng bảo vệ Workbook bằng phương pháp Workbook.Unprotect1. Lưu kết quả ở định dạng XLS
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="yêu cầu hệ thống" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for .NET được hỗ trợ trên tất cả các hệ điều hành chính. Chỉ cần đảm bảo rằng bạn có các điều kiện tiên quyết sau.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows hoặc hệ điều hành tương thích với Nền tảng .NET Framework, .NET Core Mono hoặc Xamarin- Môi trường phát triển như Microsoft Visual Studio- Aspose.Cells for .NET được tham chiếu trong dự án của bạn
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Yêu cầu" offSpacer="" %}}

```cs

// khởi tạo một đối tượng Workbook với tệp XLS được bảo vệ
var workbook = new Aspose.Cells.Workbook("protected.xls");

// truy cập trang tính mặc định trong tệp Excel
var worksheet = workbook.Worksheets[0];

// bỏ bảo vệ trang tính mà không có mật khẩu
worksheet.Unprotect();

// bỏ bảo vệ sổ làm việc bằng mật khẩu
workbook.Unprotect("password");

// lưu lại kết quả ở định dạng XLS
workbook.Save("unprotected.xls", Aspose.Cells.SaveFormat.Auto);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Giới thiệu về Aspose.Cells for .NET API" %}}

 Aspose.Cells API có thể được sử dụng để tạo, chỉnh sửa, chuyển đổi và hiển thị các định dạng Microsoft Excel sang các định dạng khác nhau. Hơn nữa, nó có thể được sử dụng để lập biểu đồ toàn diện, báo cáo có thể mở rộng và tính toán đáng tin cậy trong các ứng dụng phần mềm. Aspose.Cells là một phần mềm độc lập API và nó không yêu cầu bất kỳ phần mềm nào như Microsoft hoặc OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Ứng dụng miễn phí để mở khóa XLS" sectionDescription="Kiểm tra các bản trình diễn trực tiếp của chúng tôi để [mở khóa các tệp XLS](https://products.aspose.app/cells/unlock/xls) với những lợi ích sau đây." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Không cần tải xuống hoặc thiết lập bất cứ thứ gì" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Không cần viết hoặc biên dịch mã" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Chỉ cần tải lên tệp XLS và nhấn nút \"Mở khóa\"" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Tải xuống tệp XLS kết quả từ liên kết" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}
Các tệp có phần mở rộng XLS đại diện cho Định dạng tệp nhị phân của Excel. Các tệp như vậy có thể được tạo bằng Microsoft Excel cũng như các chương trình bảng tính tương tự khác như OpenOffice Calc hoặc Apple Numbers. Tệp được lưu bởi Excel được gọi là Sổ làm việc trong đó mỗi sổ làm việc có thể có một hoặc nhiều trang tính. Dữ liệu được lưu trữ và hiển thị cho người dùng ở định dạng bảng trong trang tính và có thể mở rộng giá trị số, dữ liệu văn bản, công thức, kết nối dữ liệu bên ngoài, hình ảnh và biểu đồ. Các ứng dụng như Microsoft Excel cho phép bạn xuất dữ liệu sổ làm việc sang một số định dạng khác nhau bao gồm PDF, CSV, XLSX, TXT, HTML, XPS và một số định dạng khác. Định dạng tệp XLS đã được thay thế bằng định dạng có cấu trúc và mở hơn, XLSX, với việc phát hành Microsoft Excel 2007. Các phiên bản mới nhất vẫn cung cấp hỗ trợ để tạo và đọc tệp XLS, mặc dù XLSX là lựa chọn sử dụng hàng đầu hiện nay.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Các định dạng mở khóa được hỗ trợ khác" subTitle="Sử dụng C#, người ta có thể dễ dàng loại bỏ tính năng bảo vệ / mở khóa của các định dạng khác nhau, bao gồm cả." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/unlock/ods/" name="ODS" description="Tệp bảng tính OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/unlock/xlsb/" name="XLSB" description="Tệp sổ làm việc Excel nhị phân" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/unlock/xlsm/" name="XLSM" description="Tệp Spreasheet" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/unlock/xlsx/" name="XLSX" description="Tệp Excel OOXML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}