---
title: 通过 C++ 使用 Go 进行 Excel 文件转换
description: 通过 C++ 库，使用 Go 语言实现 Aspose.Cells 功能。只需几行 Go 代码（通过 C++），即可转换 EXCEL、JSON、PDF、XML、HTML、TXT、TSV、CSV、SQL、JPG、PNG 等多种格式。
keywords: [Go via C++ Aspose.Cells., excel to pdf., json to excel., txt to sql., csv to json., json to pdf., xml to excel and Convert files between various formats in Go via C++]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 Microsoft<sup>&reg;</sup> 使用 Go 进行 Excel 文档转换" h2="将 Microsoft<sup>&reg;</sup> Excel 文件保存为电子表格、网页、图像和固定布局格式" >}}

{{% blocks/products/pf/feature-page-summary %}}
对于任何电子表格转换器应用程序或解决方案，**通过 C++ Excel 库**加快编码、自动化和转换流程，同时处理多种文件格式，包括 XLSX、XLS、XLSM、XLSB、XLTX、XLTM、CSV、SpreadsheetML 和 ODS。它还允许将 Excel 文件转换为 PDF、XPS、HTML、MHTML、纯文本以及常见的图像格式，例如 JPG、TIFF、PNG、BMP 和 SVG。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Microsoft Excel 格式之间的相互转换" %}}
在电子表格格式之间进行转换只需要使用以下命令加载电子表格：[工作簿](https://reference.aspose.com/cells/go-cpp/workbook/)使用以下方式将类重新保存为所需的格式：[节省](https://reference.aspose.com/cells/go-cpp/workbook/save_string/)该方法[工作簿](https://reference.aspose.com/cells/go-cpp//workbook/)班级。
{{% blocks/products/pf/feature-page-code h3="请参阅 C++ Excel 文件格式转换示例代码" %}}

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


{{% blocks/products/pf/feature-page-section h2="将 Excel 格式转换为 PDF 格式，并设置合规级别" %}}
通过 C++ Excel 自动化工具，API 支持将工作簿转换为 PDF 格式，并支持设置合规级别和创建日期。开发人员可以使用[Pdf保存选项](https://reference.aspose.com/cells/go-cpp/pdfsaveoptions/)设置 PDF 合规性。对于转换，使用 API 保存方法，该方法以 PdfSaveOptions 为参数并指定输出文件路径。
{{% blocks/products/pf/feature-page-code h3="通过 C++ Excel 示例代码转换为 PDF" %}}

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

{{% blocks/products/pf/feature-page-section h2="将 Excel 文件保存为图像" %}}
**通过 C++ Excel 解析器**能够以图像形式导出数据。每个工作表都可以转换为不同的图像格式，包括 BMP、JPEG、PNG 和 GIF，具体格式由……设置。[渲染::图像或打印选项](https://reference.aspose.com/cells/go-cpp/sheetrender/toimage_int_string/)对于任何**将 Excel 文件转换为图像**案例，请从链接中选择相关案例。
{{% blocks/products/pf/feature-page-code h3="通过 C++ 代码进行 Excel 转图像转换" %}}

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
