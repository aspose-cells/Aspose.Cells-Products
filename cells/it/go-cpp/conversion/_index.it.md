---
title: Microsoft Conversione file Excel con Go tramite C++
description: Aspose.Cells per Go tramite la libreria C++. Converti EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL, JPG, PNG e altri formati con poche righe di codice Go tramite C++.
keywords: [Go via C++ Aspose.Cells., excel to pdf., json to excel., txt to sql., csv to json., json to pdf., xml to excel and Convert files between various formats in Go via C++]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=" Microsoft<sup>&reg;</sup> Conversione di documenti Excel con Go tramite C++" h2="Salva i file Excel Microsoft<sup>&reg;</sup> come fogli di calcolo, formati web, immagini e layout fissi" >}}

{{% blocks/products/pf/feature-page-summary %}}
 Per qualsiasi applicazione o soluzione di conversione di fogli di calcolo,**Vai alla libreria Excel C++**velocizza i processi di codifica, automazione e conversione durante la gestione di più file, tra cui XLSX, XLS, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Consente inoltre di *convertire Excel in PDF**, XPS, HTML, MHTML, testo normale e immagini comuni come JPG, TIFF, PNG, BMP e SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Conversione reciproca dei formati Excel Microsoft" %}}
 La conversione tra formati di foglio di calcolo richiede solo il caricamento del foglio di calcolo utilizzando[Cartella di lavoro](https://reference.aspose.com/cells/go-cpp/workbook/) classe e salvandola nuovamente nel formato richiesto utilizzando il[Salva](https://reference.aspose.com/cells/go-cpp/workbook/save_string/) metodo del[Cartella di lavoro](https://reference.aspose.com/cells/go-cpp//workbook/) classe.
{{% blocks/products/pf/feature-page-code h3="Vai al codice di esempio C++ per la conversione del formato file Excel" %}}

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


{{% blocks/products/pf/feature-page-section h2="Converti i formati Excel in PDF con le impostazioni del livello di conformità" %}}
 Passare a C++ Excel Automation API supporta la conversione delle cartelle di lavoro in PDF e supporta l'impostazione del livello di conformità e della data di creazione. Gli sviluppatori possono utilizzare[Opzioni di salvataggio PDF](https://reference.aspose.com/cells/go-cpp/pdfsaveoptions/)per impostare la conformità PDF. Per la conversione, metodo di salvataggio API con PdfSaveOptions come parametro e percorso del file di output specificato.
{{% blocks/products/pf/feature-page-code h3="Vai al codice di esempio C++ per la conversione da Excel a PDF" %}}

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

{{% blocks/products/pf/feature-page-section h2="Salva Excel in immagini" %}}
**Vai tramite C++ Excel Parser** ha la possibilità di esportare dati sotto forma di immagini. Ogni foglio di lavoro può essere convertito in diversi formati immagine, tra cui BMP, JPEG, PNG e GIF, impostati da[Rendering::ImageOrPrintOptions](https://reference.aspose.com/cells/go-cpp/sheetrender/toimage_int_string/) Per qualsiasi**Converti Excel in immagini** caso, selezionare il caso pertinente dai link.
{{% blocks/products/pf/feature-page-code h3="Vai al codice C++ per la conversione da Excel a immagine" %}}

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
