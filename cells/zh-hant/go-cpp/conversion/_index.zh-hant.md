---
title: 透過 C++ 使用 Go 進行 Excel 檔案轉換
description: 透過 C++ 函式庫，使用 Go 語言實現 Aspose.Cells 功能。只需幾行 Go 程式碼（透過 C++），即可轉換 EXCEL、JSON、PDF、XML、HTML、TXT、TSV、CSV、53481、TSV、CSV、J8383、J83、J
keywords: [Go via C++ Aspose.Cells., excel to pdf., json to excel., txt to sql., csv to json., json to pdf., xml to excel and Convert files between various formats in Go via C++]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="透過 Microsoft<sup>&reg;</sup> 使用 Go 進行 Excel 文件轉換" h2="將 Microsoft<sup>&reg;</sup> Excel 檔案儲存為電子表格、網頁、圖片和固定版面格式" >}}

{{% blocks/products/pf/feature-page-summary %}}
對於任何電子表格轉換器應用程式或解決方案，**通過 C++ Excel 庫**加快編碼、自動化和轉換流程，同時處理多種文件格式，包括 XLSX、XLS、XLSM、XLSB、XLTX、XLTM、CSV,0163481481163481、0163481、010173761163481、01017383。它還允許將 Excel 檔案轉換為 PDF、XPS、HTML、MHTML、純文字以及常見的影像格式，例如 JPG、TIFF、PNG、0761153761
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Microsoft Excel 格式之間的相互轉換" %}}
在電子表格格式之間進行轉換只需要使用以下命令載入電子表格：[練習冊](https://reference.aspose.com/cells/go-cpp/workbook/)使用以下方式將類別重新儲存為所需的格式：[節省](https://reference.aspose.com/cells/go-cpp/workbook/save_string/)該方法[練習冊](https://reference.aspose.com/cells/go-cpp//workbook/)班級。
{{% blocks/products/pf/feature-page-code h3="請參閱 C++ Excel 檔案格式轉換範例程式碼" %}}

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


{{% blocks/products/pf/feature-page-section h2="將 Excel 格式轉換為 PDF 格式，並設定合規級別" %}}
透過 C++ Excel 自動化工具，API 支援將工作簿轉換為 PDF 格式，並支援設定合規等級和建立日期。開發人員可以使用[Pdf保存選項](https://reference.aspose.com/cells/go-cpp/pdfsaveoptions/)設定 PDF 合規性。對於轉換，使用 API 儲存方法，該方法以 PdfSaveOptions 為參數並指定輸出檔案路徑。
{{% blocks/products/pf/feature-page-code h3="透過 C++ Excel 範例程式碼轉換為 PDF" %}}

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

{{% blocks/products/pf/feature-page-section h2="將 Excel 檔案儲存為圖像" %}}
**透過 C++ Excel 解析器**能夠以影像形式匯出資料。每個工作表都可以轉換為不同的圖像格式，包括 BMP、JPEG、PNG 和 GIF，具體格式由…設定。[渲染::圖像或列印選項](https://reference.aspose.com/cells/go-cpp/sheetrender/toimage_int_string/)對於任何**將 Excel 檔案轉換為影像**案例，請從連結中選擇相關案例。
{{% blocks/products/pf/feature-page-code h3="透過 C++ 程式碼進行 Excel 轉影像轉換" %}}

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
