---
title: Chuyển đổi Tệp Microsoft Excel qua C++ 

description: Chuyển đổi Excel XLS, XLSX, ODS, CSV sang PDF, XPS, HTML, JPEG và các định dạng khác chỉ với vài dòng mã C++.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft <sup> & reg; </sup> Chuyển đổi Tài liệu Excel qua C++" h2="Lưu các tệp Microsoft <sup> & reg; </sup> Excel dưới dạng bảng tính, web, hình ảnh và các định dạng bố cục cố định" >}}

{{% blocks/products/pf/feature-page-summary %}}
Đối với bất kỳ ứng dụng hoặc giải pháp chuyển đổi bảng tính nào, ** C++ Excel Library ** tăng tốc quá trình mã hóa, tự động hóa và chuyển đổi trong khi xử lý nhiều tệp bao gồm XLSX, XLS, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Nó cũng cho phép ** chuyển đổi Excel sang PDF **, XPS, HTML, MHTML, Văn bản thuần túy và các hình ảnh phổ biến như JPG, TIFF, PNG, BMP và SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Chuyển đổi giữa các Định dạng Microsoft Excel" %}}
Việc chuyển đổi giữa các định dạng bảng tính chỉ yêu cầu tải một bảng tính có phiên bản của [ intrusive_ptr <Aspose :: Cells :: IWorkbook>](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) con trỏ và lưu lại ở định dạng mong muốn bằng cách sử dụng [Cứu](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) phương pháp của [Lớp IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook).
{{% blocks/products/pf/feature-page-code h3="C++ Mã Ví dụ cho Chuyển đổi Định dạng Tệp Excel" %}}

```cs

// Tải định dạng excel nguồn.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"src_excel_file.xls");

// Lưu ở định dạng đầu ra bắt buộc.
wkb->Save(u"output_excel_format.xlsx", SaveFormat_Xlsx);


```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Chuyển đổi Định dạng Excel sang PDF với Cài đặt Mức độ Tuân thủ" %}}
C++ Tự động hóa Excel API hỗ trợ chuyển đổi Sổ làm việc sang PDF cũng như hỗ trợ thiết lập mức tuân thủ và ngày tạo. Các nhà phát triển có thể sử dụng [IPdfSaveOptions](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_pdf_save_options) cùng với [Aspose :: Cells :: Kết xuất](https://reference.aspose.com/cells/cpp/namespace/aspose.cells.rendering) để thiết lập tuân thủ PDF. Đối với chuyển đổi, API lưu phương pháp có PdfSaveOptions làm tham số và đường dẫn tệp đầu ra rõ ràng. 
{{% blocks/products/pf/feature-page-code h3="C++ Mã Mẫu cho Chuyển đổi Excel sang PDF" %}}

```cs
// Tải tệp Excel mẫu.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sample-convert-excel-to.pdf");

// Tạo đối tượng tùy chọn lưu pdf.
intrusive_ptr<Aspose::Cells::IPdfSaveOptions> pdfSaveOptions = Factory::CreateIPdfSaveOptions();

// Đặt tuân thủ thành PDF / A-1b.
pdfSaveOptions->SetCompliance(Aspose::Cells::Rendering::PdfCompliance_PdfA1b);

// hoặc PdfCompliance_PdfA1a 
// đối với PDF thông thường, nó sẽ là PdfCompliance_None

// Lưu tài liệu Excel ở định dạng PDF
wkb->Save(u"output-converted-excel-workbook-to.pdf", pdfSaveOptions);



```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="PDF" >}}

{{% blocks/products/pf/feature-page-section h2="Lưu Excel vào Hình ảnh" %}}
** C++ Excel Parser ** có khả năng xuất dữ liệu dưới dạng hình ảnh. Mỗi trang tính có thể được chuyển đổi sang các định dạng hình ảnh khác nhau bao gồm BMP, JPEG, PNG và GIF, được thiết lập bởi [Kết xuất :: IImageOrPrintOptions](https://reference.aspose.com/cells/cpp/class/aspose.cells.rendering.i_image_or_print_options). Đối với bất kỳ trường hợp ** Chuyển Excel sang Hình ảnh ** nào, hãy chọn trường hợp liên quan từ các liên kết.
{{% blocks/products/pf/feature-page-code h3="C++ Mã chuyển đổi Excel sang Hình ảnh" %}}

```cs
// Đường dẫn thư mục đầu ra.
StringPtr outDir = new String("ImagesOutputDirectoryPath");

// Tải XLSX.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"source-excel-file.xlsx");

// Truy cập trang tính đầu tiên.
intrusive_ptr<Aspose::Cells::IWorksheet> wks = wkb->GetIWorksheets()->GetObjectByIndex(0);

// Tạo hình ảnh hoặc đối tượng tùy chọn in.
intrusive_ptr<Aspose::Cells::Rendering::IImageOrPrintOptions> imgOptions = Factory::CreateIImageOrPrintOptions();

// Chỉ định định dạng hình ảnh. Mã dưới đây dành cho JPEG
imgOptions->SetImageFormat(Aspose::Cells::Systems::Drawing::Imaging::ImageFormat::GetJpeg());

// Đối với các hình ảnh khác như GIF, BMP và PNG, người ta có thể sử dụng GetGif (), GetBmp () và GetPng () tương ứng 

// Chỉ định độ phân giải ngang và dọc
imgOptions->SetHorizontalResolution(200);
imgOptions->SetVerticalResolution(200);

// Kết xuất trang tính đối với các tùy chọn hình ảnh hoặc in được chỉ định.
intrusive_ptr<Aspose::Cells::Rendering::ISheetRender> sr = Factory::CreateISheetRender(wks, imgOptions);

// Nhận số lượng trang.
Aspose::Cells::Systems::Int32 pageCount = sr->GetPageCount();

// Tạo đối tượng trình tạo chuỗi để nối chuỗi.
intrusive_ptr<Aspose::Cells::Systems::Text::StringBuilder> sb = new Aspose::Cells::Systems::Text::StringBuilder();

// Hiển thị từng trang thành ảnh jpeg từng cái một.
for (int i = 0; i < pageCount; i++){
	// Xóa trình tạo chuỗi và tạo đường dẫn hình ảnh đầu ra với các đoạn nối chuỗi.
	sb->Clear();
	sb->Append(outDir);
	sb->Append((StringPtr)new String("outputConvertingWorksheetToImageJPEG_"));
	sb->Append(i);
	sb->Append((StringPtr)new String(".jpeg"));
	// Nhận đường dẫn hình ảnh đầu ra.
	StringPtr outputJPEG = sb->ToString();
	// Chuyển đổi bảng tính thành hình ảnh.
	sr->ToImage(i, outputJPEG);
}

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xls-to-png csv-to-jpeg tsv-to-png xlsb-to-png xlsx-to-png ods-to-png spreadsheetml-to-bmp tabdelimited-to-gif xlsm-to-bmp xlt-to-gif xltm-to-png xltx-to-gif" >}}
