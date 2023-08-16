---
title:  Microsoft Chuyển đổi tệp Excel qua C++
description: Chuyển đổi Excel XLS, XLSX, ODS, CSV thành PDF, XPS, HTML, JPEG và các định dạng khác chỉ với vài dòng mã C++.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Chuyển đổi tài liệu Excel qua C++" h2="Lưu Microsoft<sup>&reg;</sup> tệp Excel dưới dạng bảng tính, web, hình ảnh và định dạng bố cục cố định" >}}

{{% blocks/products/pf/feature-page-summary %}}
 Đối với bất kỳ ứng dụng hoặc giải pháp chuyển đổi bảng tính nào,**C++ Thư Viện Excel** tăng tốc quá trình mã hóa, tự động hóa và chuyển đổi trong khi xử lý nhiều tệp bao gồm XLSX, XLS, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Nó cũng cho phép * chuyển đổi Excel sang PDF**, XPS, HTML, MHTML, Đồng Bằng Văn bản và hình ảnh phổ biến như JPG, TIFF, PNG, BMP và SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Chuyển đổi giữa các định dạng Excel Microsoft" %}}
 Chuyển đổi giữa các định dạng bảng tính chỉ yêu cầu tải một bảng tính với phiên bản[ xâm nhập_ptr<Aspose::Cells::IWorkbook>](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) con trỏ và lưu lại ở định dạng mong muốn bằng cách sử dụng[Cứu](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) phương pháp của[lớp iWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook).
{{% blocks/products/pf/feature-page-code h3="C++ Mã ví dụ để chuyển đổi định dạng tệp Excel" %}}

```cs

// Load the source excel format.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"src_excel_file.xls");

// Save in required output format.
wkb->Save(u"output_excel_format.xlsx", SaveFormat_Xlsx);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Chuyển đổi định dạng Excel thành PDF với Cài đặt mức tuân thủ" %}}
 C++ Excel Automation API hỗ trợ chuyển đổi Workbook thành PDF cũng như hỗ trợ cài đặt mức độ tuân thủ và ngày tạo. Các nhà phát triển có thể sử dụng[IPdfSaveTùy chọn](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_pdf_save_options) cùng với[Aspose::Cells::Kết xuất](https://reference.aspose.com/cells/cpp/namespace/aspose.cells.rendering) để đặt tuân thủ PDF. Để chuyển đổi, phương thức lưu API có PdfSaveOptions làm tham số và đường dẫn tệp đầu ra được chỉ định.
{{% blocks/products/pf/feature-page-code h3="C++ Mã mẫu cho Chuyển đổi Excel thành PDF" %}}

```cs
// Load the sample Excel file.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sample-convert-excel-to.pdf");

// Create pdf save options object.
intrusive_ptr<Aspose::Cells::IPdfSaveOptions> pdfSaveOptions = Factory::CreateIPdfSaveOptions();

// Set the compliance to PDF/A-1b.
pdfSaveOptions->SetCompliance(Aspose::Cells::Rendering::PdfCompliance_PdfA1b);

// or PdfCompliance_PdfA1a 
// for normal PDF it will be PdfCompliance_None

// Save the Excel Document in PDF format
wkb->Save(u"output-converted-excel-workbook-to.pdf", pdfSaveOptions);


```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="PDF" >}}

{{% blocks/products/pf/feature-page-section h2="Lưu Excel vào Hình ảnh" %}}
**C++ Trình phân tích cú pháp Excel** có khả năng xuất dữ liệu dưới dạng hình ảnh. Mỗi trang tính có thể được chuyển đổi sang các định dạng hình ảnh khác nhau bao gồm BMP, JPEG, PNG và GIF, được đặt bởi[Kết xuất::IImageOrPrintTùy chọn](https://reference.aspose.com/cells/cpp/class/aspose.cells.rendering.i_image_or_print_options) . Bất cứ gì**Chuyển đổi Excel sang hình ảnh** trường hợp, chọn trường hợp có liên quan từ các liên kết.
{{% blocks/products/pf/feature-page-code h3="C++ Mã để chuyển đổi Excel sang hình ảnh" %}}

```cs
// Output directory path.
StringPtr outDir = new String("ImagesOutputDirectoryPath");

// Load the XLSX.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"source-excel-file.xlsx");

// Access first worksheet.
intrusive_ptr<Aspose::Cells::IWorksheet> wks = wkb->GetIWorksheets()->GetObjectByIndex(0);

// Create image or print options object.
intrusive_ptr<Aspose::Cells::Rendering::IImageOrPrintOptions> imgOptions = Factory::CreateIImageOrPrintOptions();

// Specify the image format. Below code is for JPEG
imgOptions->SetImageFormat(Aspose::Cells::Systems::Drawing::Imaging::ImageFormat::GetJpeg());

// For other images like GIF, BMP and PNG one can use GetGif(), GetBmp() and GetPng() respectively 

// Specify horizontal and vertical resolution
imgOptions->SetHorizontalResolution(200);
imgOptions->SetVerticalResolution(200);

// Render the sheet with respect to specified image or print options.
intrusive_ptr<Aspose::Cells::Rendering::ISheetRender> sr = Factory::CreateISheetRender(wks, imgOptions);

// Get page count.
Aspose::Cells::Systems::Int32 pageCount = sr->GetPageCount();

// Create string builder object for string concatenations.
intrusive_ptr<Aspose::Cells::Systems::Text::StringBuilder> sb = new Aspose::Cells::Systems::Text::StringBuilder();

// Render each page to jpeg image one by one.
for (int i = 0; i < pageCount; i++){
	// Clear string builder and create output image path with string concatenations.
	sb->Clear();
	sb->Append(outDir);
	sb->Append((StringPtr)new String("outputConvertingWorksheetToImageJPEG_"));
	sb->Append(i);
	sb->Append((StringPtr)new String(".jpeg"));
	// Get the output image path.
	StringPtr outputJPEG = sb->ToString();
	// Convert worksheet to image.
	sr->ToImage(i, outputJPEG);
}
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xls-to-png csv-to-jpeg tsv-to-png xlsb-to-png xlsx-to-png ods-to-png spreadsheetml-to-bmp tabdelimited-to-gif xlsm-to-bmp xlt-to-gif xltm-to-png xltx-to-gif" >}}
