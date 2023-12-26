---
title:  Microsoft Chuyển đổi file Excel qua C++
description: Aspose.Cells for C++ thư viện. Chuyển đổi EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL, JPG, PNG và nhiều định dạng khác chỉ với vài dòng mã C++.
keywords: [C++ Aspose.Cells., excel to pdf., json to excel., txt to sql., csv to json., json to pdf., xml to excel and Convert files between various formats in C++]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Chuyển đổi tài liệu Excel qua C++" h2="Lưu Microsoft<sup>&reg;</sup> tệp Excel dưới dạng bảng tính, web, hình ảnh và bố cục cố định" >}}

{{% blocks/products/pf/feature-page-summary %}}
 Đối với bất kỳ ứng dụng hoặc giải pháp chuyển đổi bảng tính nào,**C++ Thư viện Excel** tăng tốc quá trình mã hóa, tự động hóa và chuyển đổi trong khi xử lý nhiều tệp bao gồm XLSX, XLS, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Nó cũng cho phép *chuyển đổi Excel sang 07 6193481**, XPS, HTML, MHTML, Trơn Văn bản và hình ảnh phổ biến như JPG, TIFF, PNG, BMP và SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Chuyển đổi giữa các định dạng Excel Microsoft" %}}
 Chuyển đổi giữa các định dạng bảng tính chỉ yêu cầu tải bảng tính bằng cách sử dụng[Sách bài tập](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) lớp và lưu lại nó ở định dạng được yêu cầu bằng cách sử dụng[Cứu](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/save/) phương pháp của[Sách bài tập](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) lớp học.
{{% blocks/products/pf/feature-page-code h3="C++ Mã ví dụ để chuyển đổi định dạng tệp Excel" %}}

```cpp

Aspose::Cells::Startup();

// Load the source excel format.
Workbook wkb(u"src_excel_file.xls");
// Save in required output format.
wkb.Save(u"output_excel_format.xlsx", SaveFormat::Xlsx);

Aspose::Cells::Cleanup();

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Chuyển đổi định dạng Excel thành PDF với Cài đặt mức tuân thủ" %}}
C++ Excel Automation API hỗ trợ chuyển đổi Workbook thành PDF cũng như hỗ trợ thiết lập mức độ tuân thủ và ngày tạo. Các nhà phát triển có thể sử dụng[Tùy chọn lưu Pdf](https://reference.aspose.com/cells/cpp/aspose.cells/pdfsaveoptions/) cùng với[Aspose::Cells::Đang kết xuất](https://reference.aspose.com/cells/cpp/aspose.cells.rendering/) để thiết lập tuân thủ PDF. Để chuyển đổi, phương thức lưu API có PdfSaveOptions làm tham số và đường dẫn tệp đầu ra được chỉ định.
{{% blocks/products/pf/feature-page-code h3="Chuyển đổi mã mẫu C++ Excel sang PDF" %}}

```cpp

Aspose::Cells::Startup();

// Load the sample Excel file.
Workbook wkb(u"sample-convert-excel-to.pdf");
// Create pdf save options object.
PdfSaveOptions pdfSaveOptions;

// Set the compliance to PDF/A-1b.
pdfSaveOptions.SetCompliance(PdfCompliance::PdfA1b);

// or PdfCompliance::PdfA1a
// for normal PDF it will be PdfCompliance::None

// Save the Excel Document in PDF format
wkb.Save(u"output-converted-excel-workbook-to.pdf", pdfSaveOptions);

Aspose::Cells::Cleanup();

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="PDF" >}}

{{% blocks/products/pf/feature-page-section h2="Lưu Excel vào hình ảnh" %}}
**C++ Trình phân tích cú pháp Excel** có khả năng xuất dữ liệu dưới dạng hình ảnh. Mỗi bảng tính có thể chuyển đổi sang các định dạng ảnh khác nhau gồm BMP, JPEG, PNG và GIF do người dùng thiết lập.[Đang hiển thị::ImageOrPrintOptions](https://reference.aspose.com/cells/cpp/aspose.cells.rendering/imageorprintoptions/) . Bất cứ gì**Chuyển đổi Excel thành hình ảnh** trường hợp, chọn trường hợp có liên quan từ các liên kết.
{{% blocks/products/pf/feature-page-code h3="C++ Mã chuyển đổi Excel sang hình ảnh" %}}

```cpp

Aspose::Cells::Startup();

// Load the XLSX.
Aspose::Cells::Workbook wkb(u"source-excel-file.xlsx");

// Access first worksheet.
Aspose::Cells::Worksheet wks = wkb.GetWorksheets().Get(0);

// Create image or print options object.
Aspose::Cells::Rendering::ImageOrPrintOptions imgOptions;

// Specify the image format. Below code is for JPEG
imgOptions.SetImageType(ImageType::Jpeg);

// For other images like GIF, BMP and PNG one can use ImageType::Gif, ImageType::Bmp and ImageType::Png respectively 

// Specify horizontal and vertical resolution
imgOptions.SetHorizontalResolution(200);
imgOptions.SetVerticalResolution(200);

// Render the sheet with respect to specified image or print options.
Aspose::Cells::Rendering::SheetRender sr(wks, imgOptions);

// Get page count.
int pageCount = sr.GetPageCount();

std::string sb = "";
// Render each page to jpeg image one by one.
for (int i = 0; i < pageCount; i++) {
	sb = ""; 
	sb += "ImagesOutputDirectoryPath/";
	sb += "outputConvertingWorksheetToImageJPEG_";
	sb += std::to_string(i);
	sb += ".jpeg";
	// Get the output image path.
	U16String outputJPEG(sb.c_str());
	// Convert worksheet to image.
	sr.ToImage(i, outputJPEG);
}

Aspose::Cells::Cleanup();
	
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xls-to-png csv-to-jpeg tsv-to-png xlsb-to-png xlsx-to-png ods-to-png spreadsheetml-to-bmp tabdelimited-to-gif xlsm-to-bmp xlt-to-gif xltm-to-png xltx-to-gif" >}}
