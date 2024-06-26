---
title: Trích xuất văn bản và hình ảnh từ tài liệu ODS qua C++
weight: 9130
description: Mã ví dụ C++ để trích xuất văn bản và hình ảnh từ tệp ODS trên C++ Môi trường thời gian chạy cho Windows 32 bit, Windows 64 bit và Linux 64 bit.
keywords: [C++ Aspose.Cells., C++ Extract text and images from ODS file., C++ How to Parse ODS File., C++ Extract text from ODS file., Extract images from ODS file using C++]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Phân tích định dạng ODS trong C++" h2="Phân tích cú pháp tài liệu ODS gốc và hiệu suất cao bằng API Aspose.Cells for C++ phía máy chủ mà không cần sử dụng bất kỳ phần mềm nào như Microsoft hoặc Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="ODS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Cách phân tích tệp ODS bằng C++" %}}

 Để phân tích tệp ODS, chúng tôi sẽ sử dụng[Aspose.Cells for C++](https://products.aspose.com/cells/cpp) API là nền tảng phân tích tài liệu giàu tính năng, mạnh mẽ và dễ sử dụng API for C++. Bạn có thể tải trực tiếp phiên bản mới nhất của nó, chỉ cần mở[NuGet](https://www.nuget.org/packages/aspose.cells) quản lý gói, tìm kiếm**Aspose.Cells.Cpp** và cài đặt. Bạn cũng có thể sử dụng lệnh sau từ Bảng điều khiển quản lý gói.

{{% blocks/products/pf/agp/code-block title="Yêu cầu" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Các bước để phân tích tệp ODS trong C++" %}}

{{% blocks/products/pf/agp/text %}}

 Phân tích tài liệu cơ bản với[Aspose.Cells for C++](https://products.aspose.com/cells/cpp)API có thể được thực hiện chỉ với vài dòng mã. Phân tích văn bản & hình ảnh từ các tệp Microsoft Excel XLS, XLSX, XLSM, XLSB và OpenDocument ODS.

{{% /blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="yêu cầu hệ thống" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for C++ hỗ trợ trên tất cả các nền tảng và Hệ điều hành chính. Hãy đảm bảo rằng bạn có các điều kiện tiên quyết sau đây.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows hoặc HĐH tương thích với C++ Môi trường chạy cho Windows 32 bit, Windows 64 bit và Linux 64 bit.
-  Thêm tham chiếu đến DLL Aspose.Cells for C++ trong dự án của bạn.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Phân tích tệp ODS - C++" offSpacer="" %}}

```cs

Aspose::Cells::Startup();

// extract images from Worksheets 
// open a template Excel file
Workbook workbook(u"sampleExtractImagesFromWorksheets.ods");

// get the first worksheet
Worksheet worksheet = workbook.GetWorksheets().Get(0);

// get the first Picture in the first worksheet
Picture pic = worksheet.GetPictures().Get(0);

// Note: you may evaluate the image format before specifying the image path
// define ImageOrPrintOptions
ImageOrPrintOptions printoption;

// specify the image format
printoption.SetImageType(ImageType::Jpeg);

// save the image
pic.ToImage(u"outputExtractImagesFromWorksheets.jpg", printoption);

Aspose::Cells::Cleanup();

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="Giới thiệu Aspose.Cells for C++ API" %}}

 Aspose.Cells API có thể được sử dụng để tạo, chỉnh sửa, chuyển đổi và hiển thị định dạng Microsoft Excel sang các định dạng khác nhau. Hơn nữa, nó có thể được sử dụng để lập biểu đồ toàn diện, báo cáo có thể mở rộng và tính toán đáng tin cậy trong các ứng dụng phần mềm. Aspose.Cells là API độc lập và không yêu cầu bất kỳ phần mềm nào như Microsoft hoặc OpenOffice.



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="Trực tuyến ODS Trình phân tích cú pháp trực tiếp" sectionDescription="Trích xuất văn bản và hình ảnh từ tài liệu ODS ngay bây giờ bằng cách truy cập của chúng tôi[Trang web demo trực tiếp](https://products.aspose.app/cells/parser). Bản demo trực tiếp có những lợi ích sau" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Không cần tải Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Không cần phải viết bất kỳ mã nào." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Chỉ cần tải lên tệp ODS của bạn." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Nó sẽ được phân tích cú pháp ngay lập tức." >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODS" readMoreLink="https://docs.fileformat.com/spreadsheet/ods/" >}}
 Các tệp có phần mở rộng ODS là viết tắt của định dạng Tài liệu Bảng tính OpenDocument mà người dùng có thể chỉnh sửa. Dữ liệu được lưu trữ bên trong tệp ODF thành hàng và cột. Đây là định dạng dựa trên XML và là một trong một số kiểu con trong họ Định dạng Tài liệu Mở (ODF). Định dạng được chỉ định như một phần của thông số kỹ thuật ODF 1.2 do OASIS xuất bản và duy trì. Một số ứng dụng trên Windows cũng như các hệ điều hành khác có thể mở file ODS để chỉnh sửa và thao tác bao gồm Microsoft Excel, NeoOffice và LibreOffice. Các tệp ODS cũng có thể được chuyển đổi sang các định dạng bảng tính khác như XLS, XLSX và các định dạng khác bằng các ứng dụng khác nhau.

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Các tài liệu phân tích cú pháp được hỗ trợ khác" subTitle="Sử dụng C++, người ta có thể dễ dàng phân tích các định dạng khác bao gồm." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/parser/xls/" name="XLS" description="Định dạng nhị phân Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/parser/xlsb/" name="XLSB" description="Tệp sổ làm việc Excel nhị phân" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/parser/xlsm/" name="XLSM" description="Tệp bảng tính" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/parser/xlsx/" name="XLSX" description="Tệp Excel OOXML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
