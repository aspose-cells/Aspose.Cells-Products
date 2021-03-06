---
title: Chuyển đổi XLSM sang EMF qua ứng dụng C++ 
url: /vi/cpp/conversion/xlsm-to-emf/ 
description: Mã chuyển đổi C++ mẫu cho tài liệu XLSM sang định dạng EMF. Lập trình viên có thể sử dụng mã nguồn này để chuyển đổi hàng loạt XLSM sang EMF trong bất kỳ Ứng dụng C++ nào.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Chuyển đổi XLSM sang EMF qua C++" h2="Chuyển đổi XLSM sang EMF hiệu suất cao bằng cách sử dụng thư viện C++ mà không cần cài đặt Microsoft Excel, OpenOffice hoặc Adobe Acrobat." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="EMF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Cách chuyển đổi XLSM sang EMF bằng cách sử dụng C++" %}}

 Để chuyển đổi XLSM sang EMF, chúng tôi sẽ sử dụng
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

{{% blocks/products/pf/agp/feature-section-col title="Các bước chuyển đổi XLSM sang EMF qua C++" %}}

{{% blocks/products/pf/agp/text %}}

 C++ các nhà phát triển có thể dễ dàng chuyển đổi tệp XLSM sang EMF chỉ trong một vài dòng mã.

{{% /blocks/products/pf/agp/text %}}

1. Tải tệp XLSM bằng Factory :: CreateIWorkbook.1. Chọn trang tính đầu tiên.1. Đặt tùy chọn (EMF).1. Lặp lại từng trang của trang tính và kết xuất.1. Mở tệp EMF trong chương trình tương thích.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="yêu cầu hệ thống" %}}

{{% blocks/products/pf/agp/text %}}

 Trước khi chạy mã mẫu chuyển đổi C++, hãy đảm bảo rằng bạn có các điều kiện tiên quyết sau.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows hoặc hệ điều hành tương thích với C++ Runtime Environment dành cho Windows 32 bit, Windows 64 bit và Linux 64 bit.- Aspose.Cells cho C++ DLL được tham chiếu trong dự án của bạn.
- Microsoft Windows hoặc hệ điều hành tương thích với C++ Runtime Environment dành cho Windows 32 bit, Windows 64 bit và Linux 64 bit.- Aspose.Cells cho C++ DLL được tham chiếu trong dự án của bạn.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Mã nguồn chuyển đổi XLSM sang EMF C++" offSpacer="" %}}

```cs
// Đường dẫn thư mục đầu ra.
StringPtr outDir = new String("OutputDirectoryPath");

// Tải XLSM.
intrusive_ptr<Aspose::Cells::IWorkbook> workbook = Factory::CreateIWorkbook(u"sourceFile.xlsm");

// Truy cập trang tính đầu tiên.
intrusive_ptr<Aspose::Cells::IWorksheet> worksheet = workbook->GetIWorksheets()->GetObjectByIndex(0);

// Tạo hình ảnh hoặc đối tượng tùy chọn in.
intrusive_ptr<Aspose::Cells::Rendering::IImageOrPrintOptions> imgOptions = Factory::CreateIImageOrPrintOptions();

// Chỉ định định dạng hình ảnh.
imgOptions->SetImageFormat(Aspose::Cells::Systems::Drawing::Imaging::ImageFormat::GetEmf());

// Chỉ định độ phân giải ngang và dọc
imgOptions->SetHorizontalResolution(200);
imgOptions->SetVerticalResolution(200);

// Kết xuất trang tính đối với các tùy chọn hình ảnh hoặc in được chỉ định.
intrusive_ptr<Aspose::Cells::Rendering::ISheetRender> sr = Factory::CreateISheetRender(worksheet, imgOptions);

// Nhận số lượng trang.
Aspose::Cells::Systems::Int32 pageCount = sr->GetPageCount();

// Tạo đối tượng trình tạo chuỗi để nối chuỗi.
intrusive_ptr<Aspose::Cells::Systems::Text::StringBuilder> sb = new Aspose::Cells::Systems::Text::StringBuilder();

// Hiển thị từng trang thành ảnh emf từng cái một.
for (int i = 0; i Clear();
	sb->Append(outDir);
	sb->Append((StringPtr)new String("outputConvertingWorksheetToImageEMF_"));
	sb->Append(i);
	sb->Append((StringPtr)new String(".emf"));

	// Nhận đường dẫn hình ảnh đầu ra.
	StringPtr outputEMF = sb->ToString();

	// Chuyển đổi bảng tính thành hình ảnh emf.
	sr->ToImage(i, outputEMF);
}


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Bản trình diễn trực tiếp chuyển đổi XLSM sang EMF" sectionDescription="[Chuyển đổi XLSM sang EMF](https://products.aspose.app/cells/conversion/xlsm-to-emf) ngay bây giờ bằng cách truy cập trang web Demos Trực tiếp của chúng tôi. Bản demo trực tiếp có những lợi ích sau" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Không cần tải xuống Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Không cần phải viết bất kỳ mã nào." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Chỉ cần tải lên tệp XLSM của bạn, nó sẽ được chuyển đổi ngay lập tức sang EMF." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Bạn sẽ nhận được liên kết tải xuống." >}}

    {{% blocks/products/pf/agp/content h2="C++ Thư viện Thao tác Tệp Excel" %}}

 Excel API có thể được sử dụng để tạo, chỉnh sửa, chuyển đổi và hiển thị các định dạng Microsoft Excel sang các định dạng khác nhau. Hơn nữa, nó có thể được sử dụng để lập biểu đồ toàn diện, báo cáo có thể mở rộng và tính toán đáng tin cậy trong các ứng dụng phần mềm. Aspose.Cells là một phần mềm độc lập API và nó không yêu cầu bất kỳ phần mềm nào như Microsoft hoặc OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSM" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsm/" >}}

Tệp có phần mở rộng XLSM là một loại tệp Spreasheet hỗ trợ Macro. Theo quan điểm của ứng dụng, Macro là một tập hợp các hướng dẫn được sử dụng để tự động hóa các quy trình. Macro được sử dụng để ghi lại các bước được thực hiện lặp đi lặp lại và tạo điều kiện thực hiện các hành động bằng cách chạy lại macro. Macro được lập trình với Visual Basic for Applications (VBA) của Microsoft từ trong Excel Workbook bằng Visual Basic Editor và có thể chạy / gỡ lỗi trực tiếp từ đó.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="EMF" readMoreLink="https://docs.fileformat.com/image/emf/" >}}

Định dạng metafile nâng cao (EMF) lưu trữ hình ảnh đồ họa độc lập với thiết bị. Siêu tệp EMF bao gồm các bản ghi có độ dài thay đổi theo thứ tự thời gian có thể hiển thị hình ảnh được lưu trữ sau khi phân tích cú pháp trên bất kỳ thiết bị đầu ra nào. Các bản ghi có độ dài thay đổi này có thể là định nghĩa của các đối tượng kèm theo, các lệnh để vẽ và các thuộc tính đồ họa quan trọng để hiển thị hình ảnh một cách chính xác. Khi một thiết bị mở siêu tệp EMF bằng cách sử dụng môi trường đồ họa của riêng nó, tỷ lệ, kích thước, màu sắc và các thuộc tính đồ họa khác của hình ảnh gốc vẫn giữ nguyên bất kể nền tảng thiết bị đang mở.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}