---
title:  Microsoft C++을 통한 Excel 파일 변환
description: Aspose.Cells for C++ 도서관. C++ 코드 몇 줄만으로 EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL, JPG, PNG 및 기타 형식을 변환할 수 있습니다.
keywords: [C++ Aspose.Cells., excel to pdf., json to excel., txt to sql., csv to json., json to pdf., xml to excel and Convert files between various formats in C++]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> C++을 통한 Excel 문서 변환" h2="Microsoft<sup>&reg;</sup> Excel 파일을 스프레드시트, 웹, 이미지 및 고정 레이아웃 형식으로 저장" >}}

{{% blocks/products/pf/feature-page-summary %}}
 스프레드시트 변환기 애플리케이션 또는 솔루션의 경우**C++ 엑셀 라이브러리** XLSX, XLS, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS을 포함한 여러 파일을 처리하면서 코딩, 자동화 및 변환 프로세스 속도를 높입니다. 또한 *Excel을 07로 변환할 수도 있습니다. 6193481**, XPS, HTML, MHTML, 일반 JPG, TIFF, PNG, BMP 및 SVG과 같은 텍스트 및 인기 이미지.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Microsoft Excel 형식의 상호 변환" %}}
 스프레드시트 형식 간 변환은 다음을 사용하여 스프레드시트를 로드하기만 하면 됩니다.[학습장](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) 클래스를 사용하여 필요한 형식으로 다시 저장합니다.[구하다](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/save/) 의 방법[학습장](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) 수업.
{{% blocks/products/pf/feature-page-code h3="C++ Excel 파일 형식 변환을 위한 예제 코드" %}}

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


{{% blocks/products/pf/feature-page-section h2="규정 준수 수준 설정을 사용하여 Excel 형식을 PDF로 변환" %}}
C++ Excel 자동화 API은 통합 문서를 PDF로 변환하고 규정 준수 수준 및 생성 날짜 설정을 지원합니다. 개발자는 다음을 사용할 수 있습니다.[PDF저장옵션](https://reference.aspose.com/cells/cpp/aspose.cells/pdfsaveoptions/) 와 함께[Aspose::Cells::렌더링 중](https://reference.aspose.com/cells/cpp/aspose.cells.rendering/) PDF 준수를 설정합니다. 변환을 위해 PdfSaveOptions를 매개변수로 사용하고 출력 파일 경로를 지정하는 API 저장 메소드입니다.
{{% blocks/products/pf/feature-page-code h3="C++ Excel에서 PDF로 변환하는 샘플 코드" %}}

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

{{% blocks/products/pf/feature-page-section h2="Excel을 이미지로 저장" %}}
**C++ 엑셀 파서** 이미지 형식으로 데이터를 내보내는 기능이 있습니다. 각 워크시트는 BMP, JPEG, PNG 및 GIF을 포함한 다양한 이미지 형식으로 변환될 수 있습니다.[렌더링::ImageOrPrintOptions](https://reference.aspose.com/cells/cpp/aspose.cells.rendering/imageorprintoptions/) . 어떠한 것도**Excel을 이미지로 변환** 경우, 링크에서 해당 사례를 선택하세요.
{{% blocks/products/pf/feature-page-code h3="C++ Excel에서 이미지로 변환하는 코드" %}}

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
