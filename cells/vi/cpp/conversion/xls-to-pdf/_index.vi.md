---
title: Chuyển XLS sang PDF qua ứng dụng C++ 
weight: 8010
url: /vi/cpp/conversion/xls-to-pdf/ 
description: Mã chuyển đổi C++ mẫu cho tài liệu XLS sang định dạng PDF. Lập trình viên có thể sử dụng mã nguồn này để chuyển đổi hàng loạt XLS sang PDF trong bất kỳ Ứng dụng C++ nào.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Chuyển XLS sang PDF qua C++" h2="Chuyển đổi XLS sang PDF hiệu suất cao bằng cách sử dụng thư viện C++ mà không cần cài đặt Microsoft Excel, OpenOffice hoặc Adobe Acrobat." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PDF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Cách chuyển XLS sang PDF bằng C++" %}}

 Để chuyển XLS sang PDF, chúng tôi sẽ sử dụng
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

{{% blocks/products/pf/agp/feature-section-col title="Các bước chuyển đổi XLS sang PDF qua C++" %}}

{{% blocks/products/pf/agp/text %}}

 C++ các nhà phát triển có thể dễ dàng chuyển đổi tệp XLS sang PDF chỉ trong một vài dòng mã.

{{% /blocks/products/pf/agp/text %}}

1. Tải tệp XLS bằng Factory :: CreateIWorkbook.1. Gọi phương thức Save ().1. Chuyển đường dẫn tệp đầu ra với phần mở rộng tệp (PDF).1. Tập tin PDF sẽ được lưu theo đường dẫn đã chỉ định.1. Mở tệp PDF trong chương trình tương thích.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="yêu cầu hệ thống" %}}

{{% blocks/products/pf/agp/text %}}

 Trước khi chạy mã mẫu chuyển đổi C++, hãy đảm bảo rằng bạn có các điều kiện tiên quyết sau.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows hoặc hệ điều hành tương thích với C++ Runtime Environment dành cho Windows 32 bit, Windows 64 bit và Linux 64 bit.- Aspose.Cells cho C++ DLL được tham chiếu trong dự án của bạn.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Mã nguồn chuyển đổi XLS sang PDF C++" offSpacer="" %}}

```cs
// Tải XLS.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.xls");

// Lưu ở định dạng PDF.
wkb->Save(u"convertedFile.pdf", SaveFormat_Pdf);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Bản trình diễn trực tiếp chuyển đổi XLS sang PDF" sectionDescription="[Chuyển XLS sang PDF](https://products.aspose.app/cells/conversion/xls-to-pdf) ngay bây giờ bằng cách truy cập trang web Demos Trực tiếp của chúng tôi. Bản demo trực tiếp có những lợi ích sau" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Không cần tải xuống Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Không cần phải viết bất kỳ mã nào." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Chỉ cần tải lên tệp XLS của bạn, nó sẽ được chuyển đổi ngay lập tức sang PDF." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Bạn sẽ nhận được liên kết tải xuống." >}}

    {{% blocks/products/pf/agp/content h2="C++ Thư viện Thao tác Tệp Excel" %}}

 Excel API có thể được sử dụng để tạo, chỉnh sửa, chuyển đổi và hiển thị các định dạng Microsoft Excel sang các định dạng khác nhau. Hơn nữa, nó có thể được sử dụng để lập biểu đồ toàn diện, báo cáo có thể mở rộng và tính toán đáng tin cậy trong các ứng dụng phần mềm. Aspose.Cells là một phần mềm độc lập API và nó không yêu cầu bất kỳ phần mềm nào như Microsoft hoặc OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}

Các tệp có phần mở rộng XLS đại diện cho Định dạng tệp nhị phân của Excel. Các tệp như vậy có thể được tạo bằng Microsoft Excel cũng như các chương trình bảng tính tương tự khác như OpenOffice Calc hoặc Apple Numbers. Tệp được lưu bởi Excel được gọi là Sổ làm việc trong đó mỗi sổ làm việc có thể có một hoặc nhiều trang tính. Dữ liệu được lưu trữ và hiển thị cho người dùng ở định dạng bảng trong trang tính và có thể mở rộng giá trị số, dữ liệu văn bản, công thức, kết nối dữ liệu bên ngoài, hình ảnh và biểu đồ. Các ứng dụng như Microsoft Excel cho phép bạn xuất dữ liệu sổ làm việc sang một số định dạng khác nhau bao gồm PDF, CSV, XLSX, TXT, HTML, XPS và một số định dạng khác. Định dạng tệp XLS đã được thay thế bằng định dạng có cấu trúc và mở hơn, XLSX, với việc phát hành Microsoft Excel 2007. Các phiên bản mới nhất vẫn cung cấp hỗ trợ để tạo và đọc tệp XLS, mặc dù XLSX là lựa chọn sử dụng hàng đầu hiện nay.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PDF" readMoreLink="https://docs.fileformat.com/view/pdf/" >}}

Định dạng tài liệu di động (PDF) là một loại tài liệu được tạo bởi Adobe vào những năm 1990. Mục đích của định dạng tệp này là giới thiệu một tiêu chuẩn để trình bày tài liệu và tài liệu tham khảo khác ở định dạng độc lập với phần mềm ứng dụng, phần cứng cũng như Hệ điều hành. Các tệp PDF có thể được mở trong Adobe Acrobat Reader / Writer cũng như trong hầu hết các trình duyệt hiện đại như Chrome, Safari, Firefox thông qua các phần mở rộng / plug-in. Hầu hết các bộ phần mềm thương mại có sẵn cũng cung cấp tính năng chuyển đổi tài liệu của họ sang định dạng tệp PDF mà không yêu cầu bất kỳ thành phần phần mềm bổ sung nào. Do đó, định dạng tệp PDF có đầy đủ khả năng chứa thông tin như văn bản, hình ảnh, siêu liên kết, trường biểu mẫu, đa phương tiện, chữ ký số, tệp đính kèm, siêu dữ liệu, tính năng không gian địa lý và các đối tượng 3D trong đó có thể trở thành một phần của tài liệu nguồn.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Các chuyển đổi được hỗ trợ khác" subTitle="Bạn cũng có thể chuyển đổi XLS thành nhiều định dạng tệp khác, bao gồm một số định dạng được liệt kê bên dưới." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-bmp/" name="XLS ĐẾN BMP" description="Hình ảnh bitmap" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-csv/" name="XLS ĐẾN CSV" description="Các giá trị được phân tách bằng dấu phẩy" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-dif/" name="XLS ĐỂ DIF" description="Định dạng trao đổi dữ liệu" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-emf/" name="XLS ĐẾN EMF" description="Định dạng siêu tệp nâng cao" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-gif/" name="XLS TO GIF" description="Định dạng trao đổi đồ họa" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-html/" name="XLS ĐẾN HTML" description="Ngôn ngữ đánh dấu siêu văn bản" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-jpeg/" name="XLS TO JPEG" description="Hình ảnh JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-mhtml/" name="XLS ĐẾN MHTML" description="Định dạng lưu trữ trang web" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-ods/" name="XLS ĐẾN ODS" description="Tệp bảng tính OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-png/" name="XLS ĐẾN PNG" description="Biểu đồ minh họa mạng lưới không dây" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-svg/" name="XLS ĐẾN SVG" description="Đồ họa vector có thể mở rộng" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-tiff/" name="XLS ĐẾN TIFF" description="Định dạng hình ảnh được gắn thẻ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-tsv/" name="XLS ĐẾN TSV" description="Giá trị được phân tách bằng tab" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-xlsb/" name="XLS ĐẾN XLSB" description="Tệp sổ làm việc Excel nhị phân" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-xlsm/" name="XLS ĐẾN XLSM" description="Tệp Spreasheet" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-xlsx/" name="XLS ĐẾN XLSX" description="Tệp Excel OOXML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-xltm/" name="XLS ĐẾN XLTM" description="Mẫu hỗ trợ macro Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-xltx/" name="XLS ĐẾN XLTX" description="Mẫu Office OpenXML Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-xps/" name="XLS ĐẾN XPS" description="Thông số kỹ thuật giấy XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}