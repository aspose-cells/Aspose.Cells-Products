---
title: Microsoft Go를 이용한 Excel 파일 변환 (C++ 경유)
description: Go 언어용 라이브러리(C++)를 사용하여 EXCEL, XML, SQL, JPG 등 다양한 형식을 Go 언어 코드(C++)로 단 몇 줄만으로 변환할 수 있습니다.
keywords: [Go via C++ Aspose.Cells., excel to pdf., json to excel., txt to sql., csv to json., json to pdf., xml to excel and Convert files between various formats in Go via C++]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=" Microsoft<sup>&reg;</sup> Go를 이용한 Excel 문서 변환 (C++번)" h2="Microsoft<sup>&reg;</sup> Excel 파일을 스프레드시트, 웹, 이미지 및 고정 레이아웃 형식으로 저장하세요." >}}

{{% blocks/products/pf/feature-page-summary %}}
 모든 스프레드시트 변환 애플리케이션 또는 솔루션의 경우,**C++ 엑셀 라이브러리를 통해 이동하세요**이 프로그램은 XLSX, XLS, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS을 포함한 여러 파일을 처리하면서 코딩, 자동화 및 변환 프로세스의 속도를 향상시킵니다. 또한 Excel 파일을 PDF, XPS, HTML, MHTML과 같은 일반 텍스트 파일 및 JPG, TIFF, PNG, BMP, SVG과 같은 인기 이미지 파일로 변환할 수 있습니다.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Microsoft 엑셀 형식 간 변환" %}}
 스프레드시트 형식 간 변환은 스프레드시트를 불러오기만 하면 됩니다.[학습장](https://reference.aspose.com/cells/go-cpp/workbook/) 클래스를 사용하여 필요한 형식으로 다시 저장합니다.[구하다](https://reference.aspose.com/cells/go-cpp/workbook/save_string/) 방법[학습장](https://reference.aspose.com/cells/go-cpp//workbook/) 수업.
{{% blocks/products/pf/feature-page-code h3="C++번 예제 코드를 통해 Excel 파일 형식 변환을 진행하세요." %}}

```go

package main

import (
    . "github.com/Aspose-Cells/aspose-cells-go-cpp/v25"
)
// Load the source excel format.
workbook,_:= NewWorkbook_String("src_excel_file.xlsx")
// Save in required output format.
workbook.Save_String("output_excel_format.xlsx")

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="규정 준수 수준 설정을 사용하여 Excel 형식을 PDF로 변환합니다." %}}
 C++ Excel 자동화 API을 통해 접속하세요. 워크북을 PDF 형식으로 변환하는 것은 물론, 규정 준수 수준 및 생성 날짜 설정도 지원합니다. 개발자는 다음을 사용할 수 있습니다.[PDF저장옵션](https://reference.aspose.com/cells/go-cpp/pdfsaveoptions/)PDF 규격 준수를 설정하려면, 변환을 위해 PdfSaveOptions를 매개변수로 사용하고 출력 파일 경로를 지정하는 API 저장 방식을 사용하십시오.
{{% blocks/products/pf/feature-page-code h3="C++ Excel 샘플 코드를 통해 PDF 변환으로 이동하세요." %}}

```go

package main

import (
    . "github.com/Aspose-Cells/aspose-cells-go-cpp/v25"
)

workbook, _ := NewWorkbook()
worksheets, _ := workbook.GetWorksheets()
worksheet, _ := worksheets.Get_Int(0)
cells, _ := worksheet.GetCells()
cell, _ := cells.Get_String("A1")
cell.PutValue_Int(5)
cell, _ = cells.Get_String("A2")
cell.PutValue_Int(15)
cell, _ = cells.Get_String("A3")
cell.PutValue_Int(25)
workbook.Save_String("HELLO_Convert.pdf")
println("Finish to convert to PDF , check .pdf file in output folder.")


```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="PDF" >}}

{{% blocks/products/pf/feature-page-section h2="Excel 파일을 이미지로 저장" %}}
**C++ Excel 파서를 통해 이동하세요** 데이터를 이미지 형태로 내보낼 수 있는 기능이 있습니다. 각 워크시트는 BMP, JPEG, PNG, GIF 등 다양한 이미지 형식으로 변환할 수 있으며, 이러한 형식은 설정에 따라 지정됩니다.[렌더링::이미지 또는 인쇄 옵션](https://reference.aspose.com/cells/go-cpp/sheetrender/toimage_int_string/) 어떤 경우든**엑셀 파일을 이미지로 변환** 해당 사례의 경우, 링크에서 관련 사례를 선택하십시오.
{{% blocks/products/pf/feature-page-code h3="C++ 코드를 통해 Excel 파일을 이미지로 변환하세요." %}}

```go

package main

import (
    . "github.com/Aspose-Cells/aspose-cells-go-cpp/v25"
)

 // Load the XLSX.
    workbook, _ := NewWorkbook("source-excel-file.xlsx")

// Access first worksheet.
    worksheets, _ := workbook.GetWorksheets()
    worksheet, _ := worksheets.Get_Int(0)

// Create image or print options object.
    imgOptions, _ := NewImageOrPrintOptions()

// Specify the image format. Below code is for JPEG
    imgOptions.SetImageType(ImageType_Jpeg)

// Specify horizontal and vertical resolution
    imgOptions.SetHorizontalResolution(200)
    imgOptions.SetVerticalResolution(200)

// Render the sheet with respect to specified image or print options.
    sheetRender, _ := NewSheetRender(worksheet, imgOptions)

// Get page count.
    pageCount, _ := sheetRender.GetPageCount()

// Render each page to jpeg image one by one.
    for i := int32(0); i < pageCount; i++ {
        data, _ := sheetRender.ToImage_Int(i)
        filename := "Image" + string(i) + ".jpg"
        file, _ := os.OpenFile(filename, os.O_WRONLY|os.O_CREATE|os.O_APPEND, 0644)
        defer file.Close()
        file.Write(data)
    }

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xls-to-png csv-to-jpeg tsv-to-png xlsb-to-png xlsx-to-png ods-to-png spreadsheetml-to-bmp tabdelimited-to-gif xlsm-to-bmp xlt-to-gif xltm-to-png xltx-to-gif" >}}

{{< /blocks/products/pf/feature-page-wrap >}}
