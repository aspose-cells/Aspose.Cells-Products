---
title: Tìm kiếm tài liệu XLS mà không cần mở qua C++ 
weight: 4560
url: /vi/cpp/search/xls/ 
description: C++ mã ví dụ để tìm kiếm các từ có mẫu trong tệp XLS trên C++ Môi trường thời gian chạy cho Windows 32 bit, Windows 64 bit và Linux 64 bit.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Tìm kiếm Định dạng XLS trong C++" h2="Tìm kiếm tài liệu XLS tự nhiên và hiệu suất cao bằng cách sử dụng API Aspose.Cells phía máy chủ cho C++ mà không cần sử dụng bất kỳ phần mềm nào như Microsoft hoặc Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Cách tìm kiếm tệp XLS bằng C++" %}}

 Để tìm kiếm tệp XLS, chúng tôi sẽ sử dụng
 [Aspose.Cells cho C++](https://products.aspose.com/cells/cpp) 
 API là một nền tảng tìm kiếm tài liệu API cho C++ giàu tính năng, mạnh mẽ và dễ sử dụng. Bạn có thể tải xuống phiên bản mới nhất của nó trực tiếp, chỉ cần mở
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 quản lý gói, tìm kiếm
 ** Aspose.Cells .Cpp ** 
 và cài đặt. Bạn cũng có thể sử dụng lệnh sau từ Bảng điều khiển Trình quản lý Gói.

{{% blocks/products/pf/agp/code-block title="Yêu cầu" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Các bước tìm kiếm tệp XLS trong C++" %}}

{{% blocks/products/pf/agp/text %}}

 Tìm kiếm tài liệu cơ bản sử dụng Aspose.Cells API có thể được thực hiện chỉ với vài dòng mã.

{{% /blocks/products/pf/agp/text %}}

+ Tải tệp XLS bằng cách khởi tạo một lớp IWorkbook.
Khởi tạo lớp IReplaceOptions.
+ Đặt các Pattern cần thiết như SetCaseSensitive (giá trị bool), SetMatchEntireCellContents (giá trị bool).
+ Sử dụng phương thức IWorkbook-> Replace (..) với các tùy chọn liên quan.
+ Lưu tệp XLS bằng phương thức IWorkbook-> Save (.).

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="yêu cầu hệ thống" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells cho C++ hỗ trợ trên tất cả các nền tảng và Hệ điều hành chính. Vui lòng đảm bảo rằng bạn có các điều kiện tiên quyết sau.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows hoặc hệ điều hành tương thích với C++ Runtime Environment dành cho Windows 32 bit, Windows 64 bit và Linux 64 bit.- Aspose.Cells cho C++ DLL được tham chiếu trong dự án của bạn.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Tìm kiếm tệp XLS - C++" offSpacer="" %}}

```cs

// Đường dẫn thư mục nguồn.
StringPtr srcDir = new String("SourcePath\\");

// Đường dẫn thư mục đầu ra.
StringPtr outDir = new String("OutputPath\\");

// Tải tệp XLS
intrusive_ptr<IWorkbook>  wkb = Factory::CreateIWorkbook(srcDir->StringAppend(new String("sourceFile.xls")));

// Tạo một phiên bản của lớp IReplaceOptions
intrusive_ptr<IReplaceOptions> replaceOptions = Factory::CreateIReplaceOptions();

// Đặt tùy chọn phân biệt chữ hoa chữ thường
replaceOptions->SetCaseSensitive(false);

// Đặt tùy chọn đối sánh văn bản
replaceOptions->SetMatchEntireCellContents(false);

// Thay thế văn bản
wkb->Replace(new String("Text to find"), new String("Text replacement"), replaceOptions);

// Lưu dưới dạng tệp XLS
wkb->Save(outDir->StringAppend(new String("outputFile.xls")));  


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="Giới thiệu về Aspose.Cells cho C++ API" %}}

 Aspose.Cells API có thể được sử dụng để tạo, chỉnh sửa, chuyển đổi và hiển thị các định dạng Microsoft Excel sang các định dạng khác nhau. Hơn nữa, nó có thể được sử dụng để lập biểu đồ toàn diện, báo cáo có thể mở rộng và tính toán đáng tin cậy trong các ứng dụng phần mềm. Aspose.Cells là một phần mềm độc lập API và nó không yêu cầu bất kỳ phần mềm nào như Microsoft hoặc OpenOffice.  



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="Bản trình diễn trực tuyến tìm kiếm XLS trực tuyến" sectionDescription="Tìm kiếm văn bản, từ, cụm từ trong tài liệu XLS ngay bây giờ bằng cách truy cập [Trang web Demos Trực tiếp](https://products.aspose.app/cells/search). Bản demo trực tiếp có những lợi ích sau" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Không cần tải xuống Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Không cần phải viết bất kỳ mã nào." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Chỉ cần tải lên các tệp XLS của bạn." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Kết quả tìm kiếm xuất hiện ngay lập tức." >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS " readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}
Các tệp có phần mở rộng XLS đại diện cho Định dạng tệp nhị phân của Excel. Các tệp như vậy có thể được tạo bằng Microsoft Excel cũng như các chương trình bảng tính tương tự khác như OpenOffice Calc hoặc Apple Numbers. Tệp được lưu bởi Excel được gọi là Sổ làm việc trong đó mỗi sổ làm việc có thể có một hoặc nhiều trang tính. Dữ liệu được lưu trữ và hiển thị cho người dùng ở định dạng bảng trong trang tính và có thể mở rộng giá trị số, dữ liệu văn bản, công thức, kết nối dữ liệu bên ngoài, hình ảnh và biểu đồ. Các ứng dụng như Microsoft Excel cho phép bạn xuất dữ liệu sổ làm việc sang một số định dạng khác nhau bao gồm PDF, CSV, XLSX, TXT, HTML, XPS và một số định dạng khác. Định dạng tệp XLS đã được thay thế bằng định dạng có cấu trúc và mở hơn, XLSX, với việc phát hành Microsoft Excel 2007. Các phiên bản mới nhất vẫn cung cấp hỗ trợ để tạo và đọc tệp XLS, mặc dù XLSX là lựa chọn sử dụng hàng đầu hiện nay. 

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Các tài liệu tìm kiếm được hỗ trợ khác" subTitle="Sử dụng C++, người ta cũng có thể tìm kiếm các tệp khác bao gồm." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/csv/" name="CSV" description="Các giá trị được phân tách bằng dấu phẩy" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/ods/" name="ODS" description="Tệp bảng tính OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/tsv/" name="TSV" description="Giá trị được phân tách bằng tab" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/txt/" name="TXT" description="Tai liệu kiểm tra" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/xlsb/" name="XLSB" description="Tệp sổ làm việc Excel nhị phân" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/xlsm/" name="XLSM" description="Tệp Spreasheet" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}