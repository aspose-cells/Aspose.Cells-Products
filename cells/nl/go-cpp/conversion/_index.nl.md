---
title: Microsoft Excel-bestandconversie met Go via C++
description: Aspose.Cells voor Go via de C++-bibliotheek. Converteer EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL, JPG, PNG en meer formaten met slechts een paar regels Go-code via C++.
keywords: [Go via C++ Aspose.Cells., excel to pdf., json to excel., txt to sql., csv to json., json to pdf., xml to excel and Convert files between various formats in Go via C++]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=" Microsoft<sup>&reg;</sup> Excel-documentconversie met Go via C++" h2="Sla de Excel-bestanden Microsoft<sup>&reg;</sup> op als spreadsheet-, web-, afbeeldings- en lay-outbestandsformaten." >}}

{{% blocks/products/pf/feature-page-summary %}}
 Voor elke spreadsheetconvertertoepassing of -oplossing,**Ga via C++ Excel-bibliotheek**Het versnelt codeer-, automatiserings- en conversieprocessen bij het verwerken van meerdere bestanden, waaronder XLSX, XLS, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML en ODS. Het maakt ook conversie mogelijk van Excel naar PDF, XPS, HTML, MHTML, platte tekst en populaire afbeeldingsformaten zoals JPG, TIFF, PNG, BMP en SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Interconversie van Microsoft Excel-formaten" %}}
 Om tussen spreadsheetformaten te converteren, hoeft u alleen de spreadsheet te laden met behulp van de[Werkboek](https://reference.aspose.com/cells/go-cpp/workbook/) klasse en deze opnieuw opslaan in het vereiste formaat met behulp van de[Redden](https://reference.aspose.com/cells/go-cpp/workbook/save_string/) methode van de[Werkboek](https://reference.aspose.com/cells/go-cpp//workbook/) klas.
{{% blocks/products/pf/feature-page-code h3="Ga via C++ Voorbeeldcode voor conversie van Excel-bestandsindelingen" %}}

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


{{% blocks/products/pf/feature-page-section h2="Converteer Excel-indelingen naar PDF met nalevingsniveau-instellingen" %}}
 Ga via C++ Excel Automation. API ondersteunt de conversie van werkmappen naar PDF en biedt ondersteuning voor het instellen van het nalevingsniveau en de aanmaakdatum. Ontwikkelaars kunnen dit gebruiken.[PdfSaveOpties](https://reference.aspose.com/cells/go-cpp/pdfsaveoptions/)Om te voldoen aan de PDF-norm. Voor de conversie moet de API-opslagmethode worden gebruikt met PdfSaveOptions als parameter en een opgegeven pad naar het uitvoerbestand.
{{% blocks/products/pf/feature-page-code h3="Ga via de voorbeeldcode C++ voor Excel naar de conversie PDF" %}}

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

{{% blocks/products/pf/feature-page-section h2="Sla Excel op als afbeeldingen" %}}
**Ga via C++ Excel Parser** Het programma biedt de mogelijkheid om gegevens als afbeeldingen te exporteren. Elk werkblad kan worden geconverteerd naar verschillende afbeeldingsformaten, waaronder BMP, JPEG, PNG en GIF, zoals ingesteld door de[Rendering::ImageOrPrintOptions](https://reference.aspose.com/cells/go-cpp/sheetrender/toimage_int_string/) Voor elke**Excel-bestanden omzetten naar afbeeldingen** Selecteer in dat geval de relevante casus via de links.
{{% blocks/products/pf/feature-page-code h3="Ga via code C++ voor het converteren van Excel naar afbeeldingen." %}}

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
