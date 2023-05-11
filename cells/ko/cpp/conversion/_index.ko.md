---
title:  Microsoft C++을 통한 Excel 파일 변환
description: Excel XLS, XLSX, ODS, CSV을 단 몇 줄의 C++ 코드로 PDF, XPS, HTML, JPEG 및 기타 형식으로 변환합니다.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> C++을 통한 Excel 문서 변환" h2="Microsoft<sup>&reg;</sup> Excel 파일을 스프레드시트, 웹, 이미지 및 고정 레이아웃 형식으로 저장" >}}

{{% blocks/products/pf/feature-page-summary %}}
 모든 스프레드시트 변환기 애플리케이션 또는 솔루션의 경우,**C++ 엑셀 라이브러리**XLSX, XLS, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS을 포함한 여러 파일을 처리하면서 코딩, 자동화 및 변환 프로세스의 속도를 높입니다. PDF**, XPS, HTML, MHTML, 일반 JPG, TIFF, PNG, BMP 및 SVG과 같은 텍스트 및 인기있는 이미지.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Microsoft Excel 형식의 상호 변환" %}}
 스프레드시트 형식의 상호 변환은 인스턴스가 있는 스프레드시트를 로드하기만 하면 됩니다.[ intrusive_ptr<Aspose::Cells::IWorkbook>](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) 포인터를 사용하여 원하는 형식으로 다시 저장[구하다](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) 의 방법[IWorkbook 클래스](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook).
{{% blocks/products/pf/feature-page-code h3="C++ Excel 파일 형식 변환을 위한 예제 코드" %}}

```cs

// Load the source excel format.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"src_excel_file.xls");

// Save in required output format.
wkb->Save(u"output_excel_format.xlsx", SaveFormat_Xlsx);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="규정 준수 수준 설정을 사용하여 Excel 형식을 PDF로 변환" %}}
 C++ Excel 자동화 API은 통합 문서를 PDF로 변환하고 준수 수준 및 생성 날짜 설정을 지원합니다. 개발자는 다음을 사용할 수 있습니다.[IPdf저장 옵션](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_pdf_save_options) 와 함께[Aspose::Cells::렌더링](https://reference.aspose.com/cells/cpp/namespace/aspose.cells.rendering)PDF 준수를 설정합니다. 변환을 위해 API PdfSaveOptions를 매개변수로 갖는 저장 방법과 지정된 출력 파일 경로.
{{% blocks/products/pf/feature-page-code h3="C++ Excel에서 PDF로 변환하는 샘플 코드" %}}

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

{{% blocks/products/pf/feature-page-section h2="Excel을 이미지에 저장" %}}
**C++ 엑셀 파서** 이미지 형태로 데이터를 내보내는 기능이 있습니다. 각 워크시트는 BMP, JPEG, PNG 및 GIF을 포함한 다양한 이미지 형식으로 변환할 수 있습니다.[렌더링::IImageOrPrintOptions](https://reference.aspose.com/cells/cpp/class/aspose.cells.rendering.i_image_or_print_options) . 어떠한 것도**Excel을 이미지로 변환** 사례, 링크에서 해당 사례를 선택합니다.
{{% blocks/products/pf/feature-page-code h3="C++ Excel에서 이미지로 변환하는 코드" %}}

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
