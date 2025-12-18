---
title: Microsoft Konwersja plików Excel z Go za pośrednictwem C++
description: Aspose.Cells dla języka Go za pomocą biblioteki C++. Konwertuj formaty EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL, JPG, PNG i inne za pomocą zaledwie kilku linijek kodu Go za pomocą biblioteki C++.
keywords: [Go via C++ Aspose.Cells., excel to pdf., json to excel., txt to sql., csv to json., json to pdf., xml to excel and Convert files between various formats in Go via C++]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=" Microsoft<sup>&reg;</sup> Konwersja dokumentów Excela za pomocą Go przez C++" h2="Zapisz pliki Excel Microsoft<sup>&reg;</sup> w formatach arkuszy kalkulacyjnych, stron internetowych, obrazów i o stałym układzie" >}}

{{% blocks/products/pf/feature-page-summary %}}
 W przypadku każdej aplikacji lub rozwiązania do konwersji arkuszy kalkulacyjnych,**Przejdź przez bibliotekę Excel C++**Przyspiesza procesy kodowania, automatyzacji i konwersji podczas obsługi wielu plików, w tym XLSX, XLS, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Umożliwia także *konwersję pliku Excel do formatów PDF**, XPS, HTML, MHTML, zwykłego tekstu i popularnych obrazów, takich jak JPG, TIFF, PNG, BMP i SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Konwersja między formatami Excel Microsoft" %}}
 Konwersja między formatami arkuszy kalkulacyjnych wymaga jedynie załadowania arkusza kalkulacyjnego za pomocą[zeszyt ćwiczeń](https://reference.aspose.com/cells/go-cpp/workbook/) klasę i ponowne zapisanie jej w wymaganym formacie za pomocą[Ratować](https://reference.aspose.com/cells/go-cpp/workbook/save_string/) metoda[zeszyt ćwiczeń](https://reference.aspose.com/cells/go-cpp//workbook/) klasa.
{{% blocks/products/pf/feature-page-code h3="Przejdź przez C++ Przykładowy kod konwersji formatu pliku Excel" %}}

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


{{% blocks/products/pf/feature-page-section h2="Konwertuj formaty Excela na PDF z ustawieniami poziomu zgodności" %}}
 Przejdź przez C++. Automatyzacja programu Excel API obsługuje konwersję skoroszytów do formatu PDF, a także ustawianie poziomu zgodności i daty utworzenia. Programiści mogą z niej korzystać.[Opcje zapisywania PDF](https://reference.aspose.com/cells/go-cpp/pdfsaveoptions/)Aby ustawić zgodność z PDF. W celu konwersji, metoda zapisu API musi mieć parametr PdfSaveOptions i określoną ścieżkę do pliku wyjściowego.
{{% blocks/products/pf/feature-page-code h3="Przejdź przez przykładowy kod C++ dla konwersji Excela na PDF" %}}

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

{{% blocks/products/pf/feature-page-section h2="Zapisz Excela w obrazach" %}}
**Przejdź przez C++ Excel Parser** Posiada możliwość eksportu danych w postaci obrazów. Każdy arkusz kalkulacyjny można przekonwertować na różne formaty obrazów, w tym BMP, JPEG, PNG i GIF, ustawione przez[Renderowanie::ImageOrPrintOptions](https://reference.aspose.com/cells/go-cpp/sheetrender/toimage_int_string/) . Dla każdego**Konwertuj Excela na obrazy** przypadku wybierz odpowiedni przypadek z linków.
{{% blocks/products/pf/feature-page-code h3="Przejdź przez kod C++ do konwersji pliku Excel na obraz" %}}

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
