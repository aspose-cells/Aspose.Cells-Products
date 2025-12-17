---
title: Microsoft Go による Excel ファイル変換（C++ 経由）
description: Aspose.Cells を Go 用 C++ ライブラリ経由で変換します。わずか数行の Go 用 C++ コードで、EXCEL、JSON、PDF、XML、HTML、TXT、TSV、CSV、SQL、JPG、PNG などの形式に変換できます。
keywords: [Go via C++ Aspose.Cells., excel to pdf., json to excel., txt to sql., csv to json., json to pdf., xml to excel and Convert files between various formats in Go via C++]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=" Microsoft<sup>&reg;</sup> Go による Excel ドキュメントの変換（C++ 経由）" h2="Microsoft<sup>&reg;</sup> Excel ファイルをスプレッドシート、ウェブ、画像、固定レイアウト形式で保存します" >}}

{{% blocks/products/pf/feature-page-summary %}}
スプレッドシートコンバータアプリケーションやソリューションでは、**C++ Excelライブラリ経由でアクセス**XLSX、XLS、XLSM、XLSB、XLTX、XLTM、CSV、SpreadsheetML、ODS を含む複数のファイルを処理しながら、コーディング、自動化、および変換プロセスを高速化します。また、*Excel を PDF**、XPS、HTML、MHTML、プレーン テキスト、JPG、TIFF、PNG、BMP、SVG などの一般的な画像に変換することもできます。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Microsoft Excel形式の相互変換" %}}
スプレッドシートの形式を変換するには、スプレッドシートを読み込むだけで済みます。[ワークブック](https://reference.aspose.com/cells/go-cpp/workbook/)クラスを作成し、必要な形式で再保存します。[保存](https://reference.aspose.com/cells/go-cpp/workbook/save_string/)方法[ワークブック](https://reference.aspose.com/cells/go-cpp//workbook/)クラス。
{{% blocks/products/pf/feature-page-code h3="C++ Excelファイル形式変換のサンプルコード" %}}

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


{{% blocks/products/pf/feature-page-section h2="コンプライアンスレベル設定を使用して Excel 形式を PDF に変換する" %}}
C++ Excel Automation API は、ワークブックを PDF に変換するだけでなく、コンプライアンスレベルと作成日の設定もサポートします。開発者は、[Pdf保存オプション](https://reference.aspose.com/cells/go-cpp/pdfsaveoptions/)PDF準拠を設定します。変換には、PdfSaveOptionsをパラメータとして持ち、出力ファイルパスを指定するAPI保存メソッドを使用します。
{{% blocks/products/pf/feature-page-code h3="C++ サンプルコードを経由して Excel から PDF に変換します" %}}

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

{{% blocks/products/pf/feature-page-section h2="Excel を画像に保存" %}}
**C++ Excelパーサー経由でアクセス**画像形式でデータをエクスポートする機能があります。各ワークシートは、BMP、JPEG、PNG、GIFなどの異なる画像形式に変換できます。[レンダリング::ImageOrPrintOptions](https://reference.aspose.com/cells/go-cpp/sheetrender/toimage_int_string/) . いかなる**Excelを画像に変換する**該当するケースについては、リンクから該当するケースを選択してください。
{{% blocks/products/pf/feature-page-code h3="C++ Excelから画像への変換コード" %}}

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
