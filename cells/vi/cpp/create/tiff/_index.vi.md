---
title: Tạo TIFF - Tạo file TIFF trong C++
description:  Aspose Excel. C++ Tạo file TIFF nhanh chóng và dễ dàng với Aspose.Cells. Tạo file TIFF bằng C++. Tạo TIFF trong C++. C++ TIFF Creator.
keywords: [Aspose Excel., C++ Aspose.Cells., C++ Create TIFF file., Generate TIFF file in C++., Create TIFF file using C++., Write data to TIFF file via C++., Create a TIFF file in C++., C++ Generate a TIFF file., C++ TIFF Creater]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Tạo file TIFF trong C++" h2="Tạo tệp TIFF gốc và hiệu suất cao theo chương trình mà không cần Micorsoft Office sử dụng thư viện C++." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="TIFF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://releases.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Tạo tệp TIFF bằng C++" %}}

 Làm cách nào để tạo tệp TIFF? Với thư viện Aspose.Cells for C++, bạn có thể dễ dàng Tạo tệp TIFF theo chương trình với một vài dòng mã.[Aspose.Cells for C++](https://products.aspose.com/cells/cpp) có khả năng xây dựng các ứng dụng đa nền tảng với khả năng tạo, sửa đổi, chuyển đổi, kết xuất và in tất cả các tệp Excel. C++ Excel API không chỉ chuyển đổi giữa các định dạng bảng tính mà còn có thể hiển thị các tệp Excel dưới dạng hình ảnh, PDF, HTML, ODS, CSV, SVG, JSON, WORD, PPT và hơn thế nữa, do đó biến nó thành một lựa chọn hoàn hảo để trao đổi tài liệu ở các định dạng tiêu chuẩn ngành. Bạn có thể tải trực tiếp phiên bản mới nhất của nó, chỉ cần mở[NuGet](https://www.nuget.org/packages/Aspose.Cells.Cpp/)quản lý gói, tìm kiếm Aspose.Cells.Cpp và cài đặt. Bạn cũng có thể sử dụng lệnh sau từ Bảng điều khiển quản lý gói.

{{% blocks/products/pf/agp/code-block title="Yêu cầu" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}                                                                             


{{% blocks/products/pf/agp/content h2="Cách tạo TIFF trong C++" %}}

{{% blocks/products/pf/agp/text %}}

 Các nhà phát triển có thể dễ dàng tạo, tải, sửa đổi và chuyển đổi tệp TIFF trong khi chạy các ứng dụng báo cáo để xử lý dữ liệu chỉ trong vài dòng mã.

{{% /blocks/products/pf/agp/text %}}

1.  Tạo một đối tượng của lớp Workbook.
1.  Đưa trang tính đầu tiên vào đối tượng Worksheet.
1.  Sử dụng phương thức Worksheet.GetCells() để đưa các ô của bảng tính vào đối tượng Cells.
1.  Sử dụng phương thức Cells.Get() để truy cập ô mong muốn của bảng tính vào đối tượng Cell.
1.  Sử dụng phương thức Cell.PutValue() để nhập giá trị vào ô.
1.  Lưu sổ làm việc dưới dạng tệp .tiff bằng phương thức Save().

{{% blocks/products/pf/agp/code-block title="Mã mẫu hiển thị cách tạo tệp TIFF trong C++." offSpacer="" %}}

```cs
Aspose::Cells::Startup();

// Create an object of the Workbook class.
Workbook wkb;
// Get the first sheet into an Worksheet object.
WorksheetCollection wsc = wkb.GetWorksheets();
Worksheet ws = wsc.Get(0);


// Use Worksheet.GetCells() method to get the cells of the worksheet into an Cells object.
Cells cells = ws.GetCells();


// Use Cells.Get() method to access the desired cell of the worksheet into an Cell object.
Cell cell00 = cells.Get(0, 0);
Cell cell01 = cells.Get(0, 1);
Cell cell10 = cells.Get(1, 0);
Cell cell11 = cells.Get(1, 1);


// Use Cell.PutValue() method to input value into the cell.
cell00.PutValue(u"ColumnA");
cell01.PutValue(u"ColumnB");
cell10.PutValue(u"ValueA");
cell11.PutValue(u"ValueB");

// Save workbook to resultFile folder
wkb.Save(u"created_one.tiff");

Aspose::Cells::Cleanup();

```

{{% /blocks/products/pf/agp/code-block %}}
{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="Thư viện C++ tạo file TIFF" %}}

{{% blocks/products/pf/agp/text %}}

Có ba tùy chọn để cài đặt "Aspose.Cells for C++" vào hệ thống của bạn. Vui lòng chọn một cái phù hợp với nhu cầu của bạn và làm theo hướng dẫn từng bước:

{{% /blocks/products/pf/agp/text %}}

1.  Cài đặt một[Gói NuGet](https://www.nuget.org/packages/Aspose.Cells.Cpp/) . Nhìn thấy[Tài liệu](https://docs.aspose.com/cells/cpp/installation/#using-nuget-package-manager)
1.  Cài đặt thư viện bằng Thư mục Bao gồm và lib. Nhìn thấy[Tài liệu](https://docs.aspose.com/cells/cpp/installation/#using-include-and-lib-folders)
1.  Cài đặt Aspose.Cells for C++ trong Linux. Nhìn thấy[Tài liệu](https://docs.aspose.com/cells/cpp/installation/#installing-asposecells-for-c-in-linux)

{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="yêu cầu hệ thống" %}}

{{% blocks/products/pf/agp/text %}}

 Trước khi chạy mã nguồn mẫu chuyển đổi C++, hãy đảm bảo rằng bạn có các điều kiện tiên quyết sau.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows hoặc HĐH tương thích với C++ Môi trường chạy cho Windows 32 bit, Windows 64 bit và Linux 64 bit.
- Thêm tham chiếu đến DLL Aspose.Cells for C++ trong dự án của bạn.

{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->
    {{< blocks/products/pf/agp/about-file-section >}}
        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="TIFF" readMoreLink="https://docs.fileformat.com/image/tiff/" >}}TIFF hoặc TIF, Định dạng tệp hình ảnh được gắn thẻ, đại diện cho hình ảnh raster được sử dụng trên nhiều thiết bị tuân thủ tiêu chuẩn định dạng tệp này. Nó có khả năng mô tả dữ liệu hình ảnh hai cấp độ, thang độ xám, bảng màu và đủ màu trong một số không gian màu. Nó hỗ trợ các sơ đồ nén có mất dữ liệu cũng như không mất dữ liệu để lựa chọn giữa không gian và thời gian cho các ứng dụng sử dụng định dạng này. Định dạng này không phụ thuộc vào máy và không bị giới hạn như bộ xử lý, hệ điều hành hoặc hệ thống tệp.{{< /blocks/products/pf/agp/i18n/about-file-text >}}
    {{< /blocks/products/pf/agp/about-file-section >}}
<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Tạo trang tính được hỗ trợ khác" subTitle="Bạn cũng có thể tạo các tệp Excel Microsoft khác, bao gồm một số tệp được liệt kê bên dưới." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/create/xls/" name="XLS" description="Microsoft Bảng tính Excel (Cũ)" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/create/xlsx/" name="XLSX" description="Mở sổ làm việc XML" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/create/xlsb/" name="XLSB" description="Sổ làm việc nhị phân Excel" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/create/xlsm/" name="XLSM" description="Bảng tính hỗ trợ macro" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/create/xlt/" name="XLT" description="Mẫu Excel 97 - 2003" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/create/xltx/" name="XLTX" description="Mẫu Excel" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/create/xltm/" name="XLTM" description="Mẫu hỗ trợ macro Excel" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/create/csv/" name="CSV" description="Giá trị được phân tách bằng dấu phẩy" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/create/tsv/" name="TSV" description="Giá trị được phân tách bằng tab" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/create/ods/" name="ODS" description="Bảng tính OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/create/pdf/" name="PDF" description="Định dạng tài liệu di động" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/create/html/" name="HTML" description="Ngôn ngữ đánh dấu siêu văn bản" >}} 


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
