---
title: Microsoft Excel-filkonvertering med Go via C++
description: Aspose.Cells för Go via C++-biblioteket. Konvertera EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL, JPG, PNG och fler format med bara några få rader Go via C++-kod.
keywords: [Go via C++ Aspose.Cells., excel to pdf., json to excel., txt to sql., csv to json., json to pdf., xml to excel and Convert files between various formats in Go via C++]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=" Microsoft<sup>&reg;</sup> Konvertering av Excel-dokument med Go via C++" h2="Spara Microsoft<sup>&reg;</sup> Excel-filer som kalkylblad, webb, bild och fast layoutformat" >}}

{{% blocks/products/pf/feature-page-summary %}}
 För alla kalkylprogram eller lösningar för konvertering,**Gå via C++ Excel-bibliotek**snabbar upp kodnings-, automatiserings- och konverteringsprocesser samtidigt som den hanterar flera filer, inklusive XLSX, XLS, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Det gör det också möjligt att *konvertera Excel till PDF**, XPS, HTML, MHTML, vanlig text och populära bilder som JPG, TIFF, PNG, BMP och SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Interkonvertering av Microsoft Excel-format" %}}
 Konvertering mellan kalkylbladsformat kräver bara att kalkylbladet laddas med hjälp av[Arbetsbok](https://reference.aspose.com/cells/go-cpp/workbook/) klassen och spara den igen i önskat format med hjälp av[Spara](https://reference.aspose.com/cells/go-cpp/workbook/save_string/) metod för[Arbetsbok](https://reference.aspose.com/cells/go-cpp//workbook/) klass.
{{% blocks/products/pf/feature-page-code h3="Gå via C++ Exempelkod för konvertering av Excel-filformat" %}}

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


{{% blocks/products/pf/feature-page-section h2="Konvertera Excel-format till PDF med inställningar för efterlevnadsnivå" %}}
 Gå via C++ Excel Automation API stöder konvertering av arbetsböcker till PDF samt stöder inställning av efterlevnadsnivå och skapandedatum. Utvecklare kan använda[PDFSparaAlternativ](https://reference.aspose.com/cells/go-cpp/pdfsaveoptions/)för att ställa in PDF-efterlevnaden. För konvertering, använd API-sparametoden med PdfSaveOptions som parameter och angiven sökväg till utdatafilen.
{{% blocks/products/pf/feature-page-code h3="Gå via C++ Exempelkod för Excel till PDF Konvertering" %}}

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

{{% blocks/products/pf/feature-page-section h2="Spara Excel till bilder" %}}
**Gå via C++ Excel-parser** har möjlighet att exportera data i form av bilder. Varje arbetsblad kan konverteras till olika bildformat, inklusive BMP, JPEG, PNG och GIF, inställda av[Rendering::BildEllerUtskriftsalternativ](https://reference.aspose.com/cells/go-cpp/sheetrender/toimage_int_string/) För alla**Konvertera Excel till bilder** ärende, välj relevant ärende från länkarna.
{{% blocks/products/pf/feature-page-code h3="Gå via C++-koden för konvertering av Excel till bild" %}}

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
