---
title: Xem Định dạng Tệp XLT qua .NET 
weight: 3610
url: /vi/net/viewer/xlt/ 
description: C# mã nguồn để tải, hiển thị và hiển thị tài liệu XLT trên Nền tảng .NET Framework, .NET Core Mono hoặc Xamarin.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Trình xem tệp XLT for .NET" h2="Xem bảng tính Excel & OpenOffice chẳng hạn như XLT mà không yêu cầu Microsoft Excel hoặc Office Automation." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLT" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Cách xem tệp XLT bằng C#" %}}

 Để xem tệp XLT, chúng tôi sẽ sử dụng
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API là nền tảng API dành cho C# giàu tính năng, mạnh mẽ và dễ sử dụng, được sử dụng với bất kỳ Người xem nào. Mở
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 quản lý gói, tìm kiếm
 ** Aspose.Cells ** 
 và cài đặt. Bạn cũng có thể sử dụng lệnh sau từ Bảng điều khiển Trình quản lý Gói.

{{% blocks/products/pf/agp/code-block title="Lệnh Bảng điều khiển Trình quản lý Gói" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Các bước để xem XLT qua C#" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells giúp các nhà phát triển dễ dàng xem tệp XLT chỉ với vài dòng mã.

{{% /blocks/products/pf/agp/text %}}

1. Tải tệp XLT trong một phiên bản của Workbook1. Tạo một phiên bản của HtmlSaveOptions và đặt thuộc tính ExportHeadings thành true1. Lưu tệp XLT ở định dạng HTML bằng phương pháp Workbook.Save1. Tải HTML kết quả trong trình duyệt mặc định với Process.Start
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="yêu cầu hệ thống" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for .NET được hỗ trợ trên tất cả các hệ điều hành chính. Chỉ cần đảm bảo rằng bạn có các điều kiện tiên quyết sau.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows hoặc hệ điều hành tương thích với Nền tảng .NET Framework, .NET Core Mono hoặc Xamarin- Môi trường phát triển như Microsoft Visual Studio- Aspose.Cells for .NET được tham chiếu trong dự án của bạn
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# mã mẫu để xem tệp XLT" offSpacer="" %}}

```cs

string output = System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".html";

// tải tệp XLT trong một phiên bản của Workbook
var book = new Aspose.Cells.Workbook("template.xlt");
// tạo một phiên bản của HtmlSaveOptions và đặt thuộc tính ExportHeadings thành true
var options = new Aspose.Cells.HtmlSaveOptions();
options.ExportHeadings = true;

// lưu tệp XLT ở định dạng HTML
book.Save(output, options);
// tải HTML kết quả trong trình duyệt mặc định
System.Diagnostics.Process.Start(output);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Giới thiệu về Aspose.Cells for .NET API" %}}

 Aspose.Cells API có thể được sử dụng để tạo, chỉnh sửa, chuyển đổi và hiển thị các định dạng Microsoft Excel sang các định dạng khác nhau. Hơn nữa, nó có thể được sử dụng để lập biểu đồ toàn diện, báo cáo có thể mở rộng và tính toán đáng tin cậy trong các ứng dụng phần mềm. Aspose.Cells là một phần mềm độc lập API và nó không yêu cầu bất kỳ phần mềm nào như Microsoft hoặc OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Ứng dụng miễn phí để xem XLT" sectionDescription="Kiểm tra các bản trình diễn trực tiếp của chúng tôi để [Xem XLT](https://products.aspose.app/cells/viewer/xlt) với những lợi ích sau đây." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Không cần tải xuống hoặc thiết lập bất cứ thứ gì" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Không cần viết hoặc biên dịch mã" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Chỉ cần tải lên tệp XLT và nhấn nút \"Xem\"" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Tải xuống tệp XLT từ liên kết, nếu cần" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLT" readMoreLink="https://docs.fileformat.com/spreadsheet/xlt/" >}}
Các tệp có phần mở rộng .XLT là các tệp mẫu được tạo bằng Microsoft Excel, một ứng dụng bảng tính nằm trong bộ Microsoft Office. Microsoft Office 97-2003 hỗ trợ tạo các tệp XLT mới cũng như mở các tệp này. Phiên bản Excel mới nhất vẫn có khả năng mở tệp mẫu định dạng cũ này. Tệp mẫu như vậy được sử dụng để nhanh chóng tạo tệp Excel mới với dữ liệu và cài đặt mặc định như định dạng trang, cỡ chữ, lề, biểu đồ, v.v. có thể được lưu dưới dạng tệp .XLS mới.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Các định dạng trình xem được hỗ trợ khác" subTitle="Sử dụng C#, Người ta cũng có thể xem nhiều định dạng tệp khác bao gồm." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/csv/" name="CSV" description="Các giá trị được phân tách bằng dấu phẩy" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/ods/" name="ODS" description="Tệp bảng tính OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/tsv/" name="TSV" description="Giá trị được phân tách bằng tab" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/txt/" name="TXT" description="Tai liệu kiểm tra" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xls/" name="XLS" description="Định dạng nhị phân Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xlsb/" name="XLSB" description="Tệp sổ làm việc Excel nhị phân" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xlsm/" name="XLSM" description="Tệp Spreasheet" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xlsx/" name="XLSX" description="Tệp Excel OOXML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xltm/" name="XLTM" description="Mẫu hỗ trợ macro Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xltx/" name="XLTX" description="Mẫu Office OpenXML Excel" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}