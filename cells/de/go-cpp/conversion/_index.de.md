---
title: Microsoft Excel-Dateikonvertierung mit Go über C++
description: Aspose.Cells für Go über die Bibliothek C++. Konvertieren Sie EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL, JPG, PNG und weitere Formate mit nur wenigen Zeilen Go-Code über die Bibliothek C++.
keywords: [Go via C++ Aspose.Cells., excel to pdf., json to excel., txt to sql., csv to json., json to pdf., xml to excel and Convert files between various formats in Go via C++]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=" Microsoft<sup>&reg;</sup> Excel-Dokumentkonvertierung mit Go über C++" h2="Speichern Sie Microsoft<sup>&reg;</sup> Excel-Dateien als Tabellenkalkulations-, Web-, Bild- und Festlayoutformate." >}}

{{% blocks/products/pf/feature-page-summary %}}
 Für jede Tabellenkalkulationskonvertierungsanwendung oder -lösung,**Gehen Sie über die C++ Excel-Bibliothek**Beschleunigt Codierungs-, Automatisierungs- und Konvertierungsprozesse bei der Verarbeitung mehrerer Dateien, darunter XLSX, XLS, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML und ODS. Es ermöglicht außerdem die Konvertierung von Excel-Dateien in die Formate PDF, XPS, HTML, MHTML, Klartext und gängige Bildformate wie JPG, TIFF, PNG, BMP und SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Interkonvertierung von Excel-Formaten (Microsoft)" %}}
 Zum Konvertieren zwischen Tabellenkalkulationsformaten muss lediglich die Tabellenkalkulation mit dem[Arbeitsmappe](https://reference.aspose.com/cells/go-cpp/workbook/) Klasse und speichern Sie sie anschließend im erforderlichen Format mithilfe der[Speichern](https://reference.aspose.com/cells/go-cpp/workbook/save_string/) Methode der[Arbeitsmappe](https://reference.aspose.com/cells/go-cpp//workbook/) Klasse.
{{% blocks/products/pf/feature-page-code h3="Gehen Sie zu Beispielcode C++ für die Excel-Dateiformatkonvertierung" %}}

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


{{% blocks/products/pf/feature-page-section h2="Excel-Formate mit Konformitätsstufeneinstellungen in PDF konvertieren" %}}
 Gehen Sie über C++ Excel Automation API, um die Konvertierung von Arbeitsmappen in PDF zu unterstützen sowie die Festlegung des Konformitätsniveaus und des Erstellungsdatums zu ermöglichen. Entwickler können verwenden[PdfSpeichernOptionen](https://reference.aspose.com/cells/go-cpp/pdfsaveoptions/)Um die Konformität mit PDF festzulegen, verwenden Sie für die Konvertierung die Speichermethode API mit dem Parameter PdfSaveOptions und dem angegebenen Ausgabedateipfad.
{{% blocks/products/pf/feature-page-code h3="Gehen Sie über den Beispielcode C++ für Excel zur Konvertierung von PDF." %}}

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

{{% blocks/products/pf/feature-page-section h2="Excel-Dateien als Bilder speichern" %}}
**Gehen Sie über C++ Excel Parser** Das Programm bietet die Möglichkeit, Daten als Bilder zu exportieren. Jedes Arbeitsblatt kann in verschiedene Bildformate konvertiert werden, darunter BMP, JPEG, PNG und GIF, die vom Programm festgelegt wurden.[Rendering::ImageOrPrintOptions](https://reference.aspose.com/cells/go-cpp/sheetrender/toimage_int_string/) Für jeden**Excel-Dateien in Bilder konvertieren** Fall, wählen Sie den relevanten Fall aus den Links aus.
{{% blocks/products/pf/feature-page-code h3="Gehen Sie über den Code C++ zur Excel-zu-Bild-Konvertierung." %}}

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
