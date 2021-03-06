---
title: Bảo vệ và khóa tài liệu XLS qua C++ 
weight: 8760
url: /vi/cpp/protect/xls/ 
description: C++ mã ví dụ để khóa tệp XLS bằng mật khẩu trên C++ Môi trường thời gian chạy cho Windows 32 bit, Windows 64 bit và Linux 64 bit.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Mã hóa tệp XLS qua C++" h2="Các bảng tính Excel được bảo vệ bằng mật khẩu bao gồm định dạng XLS bằng cách sử dụng .NET Thư viện." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLS" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp/" installationsDocsLink="https://docs.aspose.com/cells/cpp/" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Cách bảo mật tệp XLS bằng C++" %}}

 Để bảo vệ tệp XLS, chúng tôi sẽ sử dụng
 [Aspose.Cells cho C++](https://products.aspose.com/cells/cpp) 
 API là một mã hóa tài liệu giàu tính năng, mạnh mẽ và dễ sử dụng API cho nền tảng C++. Bạn có thể tải xuống phiên bản mới nhất của nó trực tiếp, chỉ cần mở
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 quản lý gói, tìm kiếm
 ** Aspose.Cells .Cpp ** 
 và cài đặt. Bạn cũng có thể sử dụng lệnh sau từ Bảng điều khiển Trình quản lý Gói.

{{% blocks/products/pf/agp/code-block title="Aspose.Cells" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Các bước để bảo vệ tệp XLS qua C++" %}}

{{% blocks/products/pf/agp/text %}}

 Bảo vệ tài liệu bằng Aspose.Cells API có thể được thực hiện chỉ với vài dòng mã.

{{% /blocks/products/pf/agp/text %}}

1. Tải tệp XLS bằng lớp IWorkbook1. Sử dụng phương thức Protect (..) với ProtectionType và Password1. Lưu tệp XLS được bảo vệ bằng phương thức Save ()
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="yêu cầu hệ thống" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells cho C++ hỗ trợ trên tất cả các nền tảng và Hệ điều hành chính. Vui lòng đảm bảo rằng bạn có các điều kiện tiên quyết sau.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows hoặc hệ điều hành tương thích với C++ Runtime Environment dành cho Windows 32 bit, Windows 64 bit và Linux 64 bit.- Aspose.Cells cho C++ DLL được tham chiếu trong dự án của bạn.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Yêu cầu" offSpacer="" %}}

```cs

// Đường dẫn nguồn.
StringPtr srcDir = new String("SourcePath\");

// Đường đầu ra.
StringPtr outDir = new String("OutputPath\");

// Tải tệp XLS
intrusive_ptr<IWorkbook> workbook = Factory::CreateIWorkbook(srcDir->StringAppend(new String("sourceFile.xls")));

// Bảo vệ sổ làm việc bằng cách chỉ định loại bảo vệ
workbook->Protect(ProtectionType::ProtectionType_All, new String("12345"));

// Lưu tệp XLS
workbook->Save(outDir->StringAppend(new String("output.xls")));


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="Giới thiệu về Aspose.Cells cho C++ API" %}}

 Aspose.Cells API có thể được sử dụng để tạo, chỉnh sửa, chuyển đổi và hiển thị các định dạng Microsoft Excel sang các định dạng khác nhau. Hơn nữa, nó có thể được sử dụng để lập biểu đồ toàn diện, báo cáo có thể mở rộng và tính toán đáng tin cậy trong các ứng dụng phần mềm. Aspose.Cells là một phần mềm độc lập API và nó không yêu cầu bất kỳ phần mềm nào như Microsoft hoặc OpenOffice.  



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="Ứng dụng miễn phí để bảo vệ XLS" sectionDescription="Kiểm tra các bản trình diễn trực tiếp của chúng tôi để [mã hóa các tệp XLS](https://products.aspose.app/cells/protect/xls) với những lợi ích sau đây." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Không cần tải xuống hoặc thiết lập bất cứ thứ gì" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Không cần viết hoặc biên dịch mã" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Chỉ cần tải lên tệp XLS và nhấn nút \"Mở khóa\"" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Tải xuống tệp XLS kết quả từ liên kết" >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}
Các tệp có phần mở rộng XLS đại diện cho Định dạng tệp nhị phân của Excel. Các tệp như vậy có thể được tạo bằng Microsoft Excel cũng như các chương trình bảng tính tương tự khác như OpenOffice Calc hoặc Apple Numbers. Tệp được lưu bởi Excel được gọi là Sổ làm việc trong đó mỗi sổ làm việc có thể có một hoặc nhiều trang tính. Dữ liệu được lưu trữ và hiển thị cho người dùng ở định dạng bảng trong trang tính và có thể mở rộng giá trị số, dữ liệu văn bản, công thức, kết nối dữ liệu bên ngoài, hình ảnh và biểu đồ. Các ứng dụng như Microsoft Excel cho phép bạn xuất dữ liệu sổ làm việc sang một số định dạng khác nhau bao gồm PDF, CSV, XLSX, TXT, HTML, XPS và một số định dạng khác. Định dạng tệp XLS đã được thay thế bằng định dạng có cấu trúc và mở hơn, XLSX, với việc phát hành Microsoft Excel 2007. Các phiên bản mới nhất vẫn cung cấp hỗ trợ để tạo và đọc tệp XLS, mặc dù XLSX là lựa chọn sử dụng hàng đầu hiện nay.

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Các tài liệu bảo vệ được hỗ trợ khác" subTitle="Sử dụng C++, người ta có thể bảo vệ các tệp khác bao gồm." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/protect/ods/" name="ODS" description="Tệp bảng tính OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/protect/xlsb/" name="XLSB" description="Tệp sổ làm việc Excel nhị phân" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/protect/xlsm/" name="XLSM" description="Tệp Spreasheet" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/protect/xlsx/" name="XLSX" description="Tệp Excel OOXML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}