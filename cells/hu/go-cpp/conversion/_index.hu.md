---
title: Microsoft Excel fájlkonverzió Go-val via C++
description: Aspose.Cells Go-hoz a C++ könyvtáron keresztül. EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL, JPG, PNG és további formátumok konvertálása mindössze néhány sor Go-val a C++ kódon keresztül.
keywords: [Go via C++ Aspose.Cells., excel to pdf., json to excel., txt to sql., csv to json., json to pdf., xml to excel and Convert files between various formats in Go via C++]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=" Microsoft<sup>&reg;</sup> Excel dokumentum konvertálása Go-val a C++-en keresztül" h2="Microsoft<sup>&reg;</sup> Excel fájlok mentése táblázatkezelő, webes, kép- és fix elrendezésű formátumban" >}}

{{% blocks/products/pf/feature-page-summary %}}
 Bármely táblázatkezelő alkalmazás vagy megoldás esetében,**Látogasson el a C++-es Excel könyvtárba**Felgyorsítja a kódolási, automatizálási és konvertálási folyamatokat több fájl kezelése közben, beleértve a XLSX, XLS, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS fájlokat. Lehetővé teszi továbbá az *Excel konvertálását PDF**, XPS, HTML, MHTML formátumúra, sima szöveggé és népszerű képekké, például JPG, TIFF, PNG, BMP és SVG formátumúra.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Microsoft Excel formátumok egymás közötti konvertálása" %}}
 A táblázatformátumok közötti konvertáláshoz csak a táblázatot kell betölteni a[Munkafüzet](https://reference.aspose.com/cells/go-cpp/workbook/) osztályt, és mentse el újra a kívánt formátumban a[Megtakarítás](https://reference.aspose.com/cells/go-cpp/workbook/save_string/) a módszer[Munkafüzet](https://reference.aspose.com/cells/go-cpp//workbook/) osztály.
{{% blocks/products/pf/feature-page-code h3="Menj végig a C++-es számon Példakód az Excel fájlformátum-konverzióhoz" %}}

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


{{% blocks/products/pf/feature-page-section h2="Excel formátumok konvertálása PDF-re megfelelőségi szintbeállításokkal" %}}
 Menj végig a C++-en. Az Excel Automation API támogatja a munkafüzetek PDF-re konvertálását, valamint a megfelelőségi szint és a létrehozási dátum beállítását. A fejlesztők használhatják[PDF mentési beállításai](https://reference.aspose.com/cells/go-cpp/pdfsaveoptions/) PDF megfelelőség beállításához. Az átalakításhoz a API mentési metódus szükséges, amelynek paramétere a PdfSaveOptions, és meg kell adni a kimeneti fájl elérési útját.
{{% blocks/products/pf/feature-page-code h3="Menj végig a C++ mintakódon az Excel PDF-re konvertálásához" %}}

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

{{% blocks/products/pf/feature-page-section h2="Excel mentése képekbe" %}}
**Menj a C++-es Excel-elemzőn keresztül** képes képek formájában exportálni az adatokat. Minden munkalap különböző képformátumokba konvertálható, beleértve a BMP, JPEG, PNG és GIF formátumokat, amelyeket a[Renderelés::KépVagyNyomtatásiBeállítások](https://reference.aspose.com/cells/go-cpp/sheetrender/toimage_int_string/) Bármelyikhez**Excel konvertálása képekké** eset, válassza ki a megfelelő esetet a linkek közül.
{{% blocks/products/pf/feature-page-code h3="Menj végig a C++ kódon az Excel képpé konvertálásához" %}}

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
