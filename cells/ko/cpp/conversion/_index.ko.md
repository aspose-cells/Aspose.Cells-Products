---
title: C++을 통한 Microsoft Excel 파일 변환 
url: /ko/cpp/conversion/
description: 몇 줄의 C++ 코드로 Excel XLS, XLSX, ODS, CSV를 PDF, XPS, HTML, JPEG 및 기타 형식으로 변환합니다.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C++을 통한 Microsoft<sup>&reg;</sup> Excel 문서 변환" h2="Microsoft<sup>&reg;</sup> Excel 파일을 스프레드시트, 웹, 이미지 및 고정 레이아웃 형식으로 저장" >}}

{{% blocks/products/pf/feature-page-summary %}}
모든 스프레드시트 변환기 애플리케이션 또는 솔루션의 경우 **C++ Excel 라이브러리**는 XLSX, XLS, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS를 비롯한 여러 파일을 처리하는 동시에 코딩, 자동화 및 변환 프로세스의 속도를 높입니다. 또한 **Excel을 PDF**, XPS, HTML, MHTML, 일반 텍스트 및 JPG, TIFF, PNG, BMP 및 SVG와 같은 인기 있는 이미지로 변환할 수 있습니다.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Microsoft Excel 형식의 상호 변환" %}}
스프레드시트 형식의 상호 변환은 다음 인스턴스가 있는 스프레드시트를 로드하기만 하면 됩니다. [ intrusive_ptr<Aspose::Cells::IWorkbook>](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) 포인터를 사용하여 원하는 형식으로 다시 저장 [구하다](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) 의 방법 [아이워크북 클래스](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_workbook).
{{% blocks/products/pf/feature-page-code h3="C++ Excel 파일 형식 변환을 위한 예제 코드" %}}

```cs

// 소스 엑셀 형식을 로드합니다.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"src_excel_file.xls");

// 필요한 출력 형식으로 저장합니다.
wkb->Save(u"output_excel_format.xlsx", SaveFormat_Xlsx);


```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="준수 수준 설정을 사용하여 Excel 형식을 PDF로 변환" %}}
C++ Excel 자동화API는 통합 문서를 PDF로 변환하고 규정 준수 수준 및 생성 날짜 설정을 지원합니다. 개발자가 사용할 수 있는 [IPdfSave 옵션](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_pdf_save_options) 와 함께 [Aspose::Cells::렌더링](https://apireference.aspose.com/cells/cpp/namespace/aspose.cells.rendering) PDF 준수를 설정합니다. 변환을 위해 API PdfSaveOptions를 매개변수로 갖는 저장 메소드와 지정된 출력 파일 경로. 
{{% blocks/products/pf/feature-page-code h3="C++ Excel에서 PDF로 변환을 위한 샘플 코드" %}}

```cs
// 샘플 Excel 파일을 로드합니다.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sample-convert-excel-to.pdf");

// pdf 저장 옵션 개체를 만듭니다.
intrusive_ptr<Aspose::Cells::IPdfSaveOptions> pdfSaveOptions = Factory::CreateIPdfSaveOptions();

// 준수를 PDF/A-1b로 설정합니다.
pdfSaveOptions->SetCompliance(Aspose::Cells::Rendering::PdfCompliance_PdfA1b);

// 또는 PdfCompliance_PdfA1a 
// 일반 PDF의 경우 PdfCompliance_None이 됩니다.

// Excel 문서를 PDF 형식으로 저장
wkb->Save(u"output-converted-excel-workbook-to.pdf", pdfSaveOptions);



```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="PDF" >}}

{{% blocks/products/pf/feature-page-section h2="Excel을 이미지에 저장" %}}
**C++ Excel 파서**에는 데이터를 이미지 형식으로 내보낼 수 있는 기능이 있습니다. 각 워크시트는 BMP, JPEG, PNG 및 GIF를 포함한 다양한 이미지 형식으로 변환할 수 있습니다. [렌더링::IImageOrPrintOptions](https://apireference.aspose.com/cells/cpp/class/aspose.cells.rendering.i_image_or_print_options). **Excel을 이미지로 변환** 사례의 경우 링크에서 관련 사례를 선택합니다.
{{% blocks/products/pf/feature-page-code h3="C++ Excel에서 이미지로 변환하는 코드" %}}

```cs
// 출력 디렉토리 경로.
StringPtr outDir = new String("ImagesOutputDirectoryPath");

// XLSX를 로드합니다.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"source-excel-file.xlsx");

// 첫 번째 워크시트에 액세스합니다.
intrusive_ptr<Aspose::Cells::IWorksheet> wks = wkb->GetIWorksheets()->GetObjectByIndex(0);

// 이미지 또는 인쇄 옵션 개체를 만듭니다.
intrusive_ptr<Aspose::Cells::Rendering::IImageOrPrintOptions> imgOptions = Factory::CreateIImageOrPrintOptions();

// 이미지 형식을 지정합니다. 아래 코드는 JPEG용입니다.
imgOptions->SetImageFormat(Aspose::Cells::Systems::Drawing::Imaging::ImageFormat::GetJpeg());

// GIF, BMP 및 PNG와 같은 다른 이미지의 경우 각각 GetGif(), GetBmp() 및 GetPng()를 사용할 수 있습니다. 

// 수평 및 수직 해상도 지정
imgOptions->SetHorizontalResolution(200);
imgOptions->SetVerticalResolution(200);

// 지정된 이미지 또는 인쇄 옵션과 관련하여 시트를 렌더링합니다.
intrusive_ptr<Aspose::Cells::Rendering::ISheetRender> sr = Factory::CreateISheetRender(wks, imgOptions);

// 페이지 수를 가져옵니다.
Aspose::Cells::Systems::Int32 pageCount = sr->GetPageCount();

// 문자열 연결을 위한 문자열 빌더 개체를 만듭니다.
intrusive_ptr<Aspose::Cells::Systems::Text::StringBuilder> sb = new Aspose::Cells::Systems::Text::StringBuilder();

// 각 페이지를 jpeg 이미지로 하나씩 렌더링합니다.
for (int i = 0; i < pageCount; i++){
	// 문자열 빌더를 지우고 문자열 연결로 출력 이미지 경로를 만듭니다.
	sb->Clear();
	sb->Append(outDir);
	sb->Append((StringPtr)new String("outputConvertingWorksheetToImageJPEG_"));
	sb->Append(i);
	sb->Append((StringPtr)new String(".jpeg"));
	// 출력 이미지 경로를 가져옵니다.
	StringPtr outputJPEG = sb->ToString();
	// 워크시트를 이미지로 변환합니다.
	sr->ToImage(i, outputJPEG);
}

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xls-to-png csv-to-jpeg tsv-to-png xlsb-to-png xlsx-to-png ods-to-png spreadsheetml-to-bmp tabdelimited-to-gif xlsm-to-bmp xlt-to-gif xltm-to-png xltx-to-gif" >}}