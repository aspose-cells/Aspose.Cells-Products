---
title:  Xem HTML Định dạng tệp via .NET
description: Mã nguồn C# để tải, kết xuất và hiển thị HTML tài liệu trên .NET Framework, .NET Core, Windows Azure, Mono hoặc Xamarin Platforms.
keywords: [C# Aspose.Cells., c# view HTML files., c# how to render HTML document., c# load and display HTML files., HTML File Viewer using C#]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="HTML Trình xem tệp for .NET" h2="Xem bảng tính Excel & OpenOffice như HTML mà không cần Microsoft Excel hay Office Automation." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="DOC" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DOC" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Cách xem tệp HTML bằng C#" %}}

 Để xem tệp HTML, chúng tôi sẽ sử dụng<a href="https://products.aspose.com/cells/net">Aspose.Cells for .NET</a>API là một nền tảng giàu tính năng, mạnh mẽ và dễ sử dụng API dành cho nền tảng C# có thể sử dụng với bất kỳ Trình xem nào. Mở<a href="https://www.nuget.org/packages/aspose.cells">NuGet</a> quản lý gói, tìm kiếm<b>Aspose.Cells</b> và cài đặt. Bạn cũng có thể sử dụng lệnh sau từ Bảng điều khiển quản lý gói.

{{% blocks/products/pf/agp/code-block title="Lệnh điều khiển quản lý gói" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Các Bước Xem HTML qua C#" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells giúp các nhà phát triển dễ dàng xem tệp HTML chỉ với vài dòng mã.

{{% /blocks/products/pf/agp/text %}}

1. Tải tệp HTML trong một phiên bản của Workbook
1. Tạo một phiên bản của HtmlSaveOptions và đặt thuộc tính ExportHeadings thành true
1. Lưu file HTML ở định dạng HTML bằng phương pháp Workbook.Save
1. Tải kết quả HTML trong trình duyệt mặc định với Process.Start


{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="yêu cầu hệ thống" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for .NET được hỗ trợ trên tất cả các hệ điều hành chính. Chỉ cần đảm bảo rằng bạn có các điều kiện tiên quyết sau đây.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows hoặc hệ điều hành tương thích với .NET Framework, .NET Core, Windows Azure, Mono hoặc Nền tảng Xamarin
-  Môi trường phát triển như Microsoft Visual Studio
-  Thêm tham chiếu đến DLL Aspose.Cells for .NET trong dự án của bạn

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Mã ví dụ C# để xem file HTML" offSpacer="" %}}

```cs


string output = System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".html";

// load the HTML file in an instance of Workbook
var book = new Aspose.Cells.Workbook("template.html");
// create an instance of HtmlSaveOptions & set ExportHeadings property to true
var options = new Aspose.Cells.HtmlSaveOptions();
options.ExportHeadings = true;

// save the HTML file in HTML format
book.Save(output, options);
// load resultant HTML in default browser
System.Diagnostics.Process.Start(output);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="" %}}

Aspose.Cells API có thể được sử dụng để tạo, chỉnh sửa, chuyển đổi và hiển thị định dạng Microsoft Excel sang các định dạng khác nhau. Hơn nữa, nó có thể được sử dụng để lập biểu đồ toàn diện, báo cáo có thể mở rộng và tính toán đáng tin cậy trong các ứng dụng phần mềm. Aspose.Cells là API độc lập và không yêu cầu bất kỳ phần mềm nào như Microsoft hoặc OpenOffice.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="App xem miễn phí HTML" sectionDescription=" Kiểm tra các bản demo trực tiếp của chúng tôi để[Xem HTML](https://products.aspose.app/cells/viewer/html) với những lợi ích sau." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Không cần tải xuống hay thiết lập bất cứ thứ gì" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Không cần phải viết hoặc biên dịch mã" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Chỉ cần tải lên tệp HTML và nhấn nút \"Xem\"" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Tải file HTML từ link nếu cần" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="HTML" readMoreLink="https://docs.fileformat.com/web/html/" >}}
HTML (Ngôn ngữ đánh dấu siêu văn bản) là phần mở rộng cho các trang web được tạo để hiển thị trên trình duyệt. Được biết đến như ngôn ngữ của trang web, HTML đã phát triển với những yêu cầu về thông tin mới được hiển thị như một phần của trang web. Biến thể mới nhất được gọi là HTML 5 mang lại sự linh hoạt cao khi làm việc với ngôn ngữ này. Các trang HTML được nhận từ máy chủ, nơi chúng được lưu trữ hoặc cũng có thể được tải từ hệ thống cục bộ. Mỗi trang HTML được tạo thành từ HTML phần tử như biểu mẫu, văn bản, hình ảnh, hoạt ảnh, liên kết, v.v. Các phần tử này được thể hiện bằng các thẻ như img, a, p và một số phần tử khác trong đó mỗi thẻ có phần bắt đầu và kết thúc. Nó cũng có thể nhúng các ứng dụng được viết bằng ngôn ngữ kịch bản như JavaScript và Style Sheets (CSS) để thể hiện bố cục tổng thể.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
