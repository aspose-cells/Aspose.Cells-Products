---
title: Microsoft Konverze souborů Excelu pomocí Go přes C++
description: Aspose.Cells pro Go přes knihovnu C++. Převeďte EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL, JPG, PNG a další formáty pomocí několika řádků kódu Go přes knihovnu C++.
keywords: [Go via C++ Aspose.Cells., excel to pdf., json to excel., txt to sql., csv to json., json to pdf., xml to excel and Convert files between various formats in Go via C++]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=" Microsoft<sup>&reg;</sup> Konverze dokumentů Excelu pomocí Go přes C++" h2="Uložte si soubory Excelu Microsoft<sup>&reg;</sup> jako tabulkový, webový, obrázkový a formát s pevným rozvržením" >}}

{{% blocks/products/pf/feature-page-summary %}}
 Pro jakoukoli aplikaci nebo řešení pro převod tabulek,**Přejděte přes C++ Knihovna Excelu**Zrychluje procesy kódování, automatizace a konverze při práci s více soubory, včetně XLSX, XLS, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Umožňuje také *konvertovat Excel na PDF**, XPS, HTML, MHTML, prostý text a oblíbené obrázky jako JPG, TIFF, PNG, BMP a SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Interkonverze formátů Excelu Microsoft" %}}
 Převod mezi formáty tabulek vyžaduje pouze načtení tabulky pomocí[pracovní sešit](https://reference.aspose.com/cells/go-cpp/workbook/) třídu a její opětovné uložení v požadovaném formátu pomocí[Uložit](https://reference.aspose.com/cells/go-cpp/workbook/save_string/) metoda[pracovní sešit](https://reference.aspose.com/cells/go-cpp//workbook/) třída.
{{% blocks/products/pf/feature-page-code h3="Přejděte přes C++ Příklad kódu pro převod formátu souboru Excel" %}}

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


{{% blocks/products/pf/feature-page-section h2="Převod formátů aplikace Excel na PDF s nastavením úrovně shody" %}}
 Přejděte přes C++. Automatizace Excelu API podporuje převod sešitů na PDF a také podporuje nastavení úrovně shody a data vytvoření. Vývojáři mohou používat[Možnosti PdfSave](https://reference.aspose.com/cells/go-cpp/pdfsaveoptions/)pro nastavení kompatibility PDF. Pro převod použijte metodu ukládání API s parametrem PdfSaveOptions a zadanou cestou k výstupnímu souboru.
{{% blocks/products/pf/feature-page-code h3="Přejděte přes ukázkový kód C++ pro Excel na konverzi PDF" %}}

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

{{% blocks/products/pf/feature-page-section h2="Uložit Excel do obrázků" %}}
**Přejděte přes C++ analyzátor Excelu** má možnost exportovat data ve formě obrázků. Každý pracovní list lze převést do různých obrazových formátů, včetně BMP, JPEG, PNG a GIF, nastavených[Rendering::ImageOrPrintMožnosti](https://reference.aspose.com/cells/go-cpp/sheetrender/toimage_int_string/) Pro jakékoli**Převod Excelu do obrázků** případ, vyberte příslušný případ z odkazů.
{{% blocks/products/pf/feature-page-code h3="Přejděte přes kód C++ pro převod Excelu do obrázku" %}}

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
