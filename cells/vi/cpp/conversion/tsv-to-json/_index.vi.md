---
title: Chuyển đổi TSV sang JSON qua ứng dụng C++ 
url: /vi/cpp/conversion/tsv-to-json/ 
description: Mã chuyển đổi C++ mẫu cho tài liệu TSV sang định dạng JSON. Các lập trình viên có thể sử dụng mã nguồn này để chuyển đổi hàng loạt TSV sang JSON trong bất kỳ Ứng dụng C++ nào.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Chuyển đổi TSV sang JSON qua C++" h2="Chuyển đổi TSV sang JSON hiệu suất cao bằng cách sử dụng thư viện C++ mà không cần cài đặt Microsoft Excel, OpenOffice hoặc Adobe Acrobat." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="JSON" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="TSV" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Cách chuyển đổi TSV sang JSON bằng cách sử dụng C++" %}}

 Để chuyển đổi TSV sang JSON, chúng tôi sẽ sử dụng
 [Aspose.Cells cho C++](https://products.aspose.com/cells/cpp) 
 API là một nền tảng thao tác và chuyển đổi tài liệu API giàu tính năng, mạnh mẽ và dễ sử dụng API cho C++. Bạn có thể tải xuống phiên bản mới nhất của nó trực tiếp, chỉ cần mở
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 quản lý gói, tìm kiếm
 Aspose.Cells .Cpp 
 và cài đặt. Bạn cũng có thể sử dụng lệnh sau từ Bảng điều khiển Trình quản lý Gói.

{{% blocks/products/pf/agp/code-block title="Yêu cầu" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Các bước chuyển đổi TSV sang JSON qua C++" %}}

{{% blocks/products/pf/agp/text %}}

 C++ các nhà phát triển có thể dễ dàng chuyển đổi tệp TSV sang JSON chỉ trong một vài dòng mã.

{{% /blocks/products/pf/agp/text %}}

1. Tải tệp TSV bằng Factory :: CreateIWorkbook.1. Gọi phương thức Save ().1. Chuyển đường dẫn tệp đầu ra với phần mở rộng tệp (JSON).1. Tệp JSON sẽ được lưu tại đường dẫn đã chỉ định.1. Mở tệp JSON trong chương trình tương thích.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="yêu cầu hệ thống" %}}

{{% blocks/products/pf/agp/text %}}

 Trước khi chạy mã mẫu chuyển đổi C++, hãy đảm bảo rằng bạn có các điều kiện tiên quyết sau.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows hoặc hệ điều hành tương thích với C++ Runtime Environment dành cho Windows 32 bit, Windows 64 bit và Linux 64 bit.- Aspose.Cells cho C++ DLL được tham chiếu trong dự án của bạn.
- Microsoft Windows hoặc hệ điều hành tương thích với C++ Runtime Environment dành cho Windows 32 bit, Windows 64 bit và Linux 64 bit.- Aspose.Cells cho C++ DLL được tham chiếu trong dự án của bạn.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Mã nguồn chuyển đổi TSV sang JSON C++" offSpacer="" %}}

```cs
// Tải TSV.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.tsv");

// Lưu ở định dạng JSON.
wkb->Save(u"convertedFile.json", SaveFormat_Json);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Bản trình diễn trực tiếp chuyển đổi TSV sang JSON" sectionDescription="[Chuyển đổi TSV sang JSON](https://products.aspose.app/cells/conversion/tsv-to-json) ngay bây giờ bằng cách truy cập trang web Demos Trực tiếp của chúng tôi. Bản demo trực tiếp có những lợi ích sau" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Không cần tải xuống Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Không cần phải viết bất kỳ mã nào." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Chỉ cần tải lên tệp TSV của bạn, tệp sẽ được chuyển đổi ngay lập tức sang JSON." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Bạn sẽ nhận được liên kết tải xuống." >}}

    {{% blocks/products/pf/agp/content h2="C++ Thư viện Thao tác Tệp Excel" %}}

 Excel API có thể được sử dụng để tạo, chỉnh sửa, chuyển đổi và hiển thị các định dạng Microsoft Excel sang các định dạng khác nhau. Hơn nữa, nó có thể được sử dụng để lập biểu đồ toàn diện, báo cáo có thể mở rộng và tính toán đáng tin cậy trong các ứng dụng phần mềm. Aspose.Cells là một phần mềm độc lập API và nó không yêu cầu bất kỳ phần mềm nào như Microsoft hoặc OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="TSV" readMoreLink="https://docs.fileformat.com/spreadsheet/tsv/" >}}

Định dạng tệp Giá trị được phân tách bằng tab (TSV) biểu thị dữ liệu được phân tách bằng các tab ở định dạng văn bản thuần túy. Định dạng tệp, tương tự như CSV, được sử dụng để tổ chức dữ liệu theo cách có cấu trúc nhằm nhập và xuất giữa các ứng dụng khác nhau. Định dạng này chủ yếu được sử dụng để nhập / xuất và trao đổi dữ liệu trong các ứng dụng và cơ sở dữ liệu Bảng tính. Mỗi bản ghi trong tệp TSV được chứa trong một dòng tệp văn bản trong đó mỗi giá trị trường được phân tách bằng một ký tự tab. Loại phương tiện cho định dạng tệp TSV là văn bản / giá trị được phân tách bằng tab.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="JSON" readMoreLink="https://docs.fileformat.com/web/json/" >}}

JSON (JavaScript Object Notation) là một định dạng tệp tiêu chuẩn mở để chia sẻ dữ liệu sử dụng văn bản có thể đọc được của con người để lưu trữ và truyền dữ liệu. Các tệp JSON được lưu trữ với phần mở rộng .json. JSON yêu cầu ít định dạng hơn và là một giải pháp thay thế tốt cho XML. JSON có nguồn gốc từ JavaScript nhưng là một định dạng dữ liệu độc lập với ngôn ngữ. Việc tạo và phân tích cú pháp JSON được hỗ trợ bởi nhiều ngôn ngữ lập trình hiện đại. application / json là loại phương tiện được sử dụng cho JSON.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Các chuyển đổi được hỗ trợ khác" subTitle="Bạn cũng có thể chuyển đổi TSV thành nhiều định dạng tệp khác, bao gồm một số định dạng được liệt kê bên dưới." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-bmp/" name="TSV ĐẾN BMP" description="Hình ảnh bitmap" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-csv/" name="TSV ĐẾN CSV" description="Các giá trị được phân tách bằng dấu phẩy" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-dif/" name="TSV ĐẾN DIF" description="Định dạng trao đổi dữ liệu" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-emf/" name="TSV ĐẾN EMF" description="Định dạng siêu tệp nâng cao" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-gif/" name="TSV TỚI GIF" description="Định dạng trao đổi đồ họa" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-html/" name="TSV ĐẾN HTML" description="Ngôn ngữ đánh dấu siêu văn bản" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-jpeg/" name="TSV ĐẾN JPEG" description="Hình ảnh JPEG" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-mhtml/" name="TSV ĐẾN MHTML" description="Định dạng lưu trữ trang web" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-ods/" name="TSV ĐẾN ODS" description="Tệp bảng tính OpenDocument" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-pdf/" name="TSV TỚI PDF" description="Định dạng tài liệu di động" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-png/" name="TSV ĐẾN PNG" description="Biểu đồ minh họa mạng lưới không dây" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-svg/" name="TSV ĐẾN SVG" description="Đồ họa vector có thể mở rộng" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-tiff/" name="TSV ĐẾN TIFF" description="Định dạng hình ảnh được gắn thẻ" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-xls/" name="TSV ĐẾN XLS" description="Định dạng nhị phân Excel" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-xlsb/" name="TSV ĐẾN XLSB" description="Tệp sổ làm việc Excel nhị phân" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-xlsm/" name="TSV ĐẾN XLSM" description="Tệp Spreasheet" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-xlsx/" name="TSV ĐẾN XLSX" description="Tệp Excel OOXML" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-xltm/" name="TSV ĐẾN XLTM" description="Mẫu hỗ trợ macro Excel" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-xltx/" name="TSV ĐẾN XLTX" description="Mẫu Office OpenXML Excel" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-xps/" name="TSV ĐẾN XPS" description="Thông số kỹ thuật giấy XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}