---
title: Conversion de fichiers Excel avec Go via C++
description: Aspose.Cells pour Go via la bibliothèque C++. Convertissez des fichiers EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL, JPG, PNG et bien d'autres formats en quelques lignes de code Go via C++.
keywords: [Go via C++ Aspose.Cells., excel to pdf., json to excel., txt to sql., csv to json., json to pdf., xml to excel and Convert files between various formats in Go via C++]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=" Conversion de documents Excel avec Go via Microsoft" h2="Enregistrez les fichiers Excel Microsoft aux formats tableur, web, image et mise en page fixe." >}}

{{% blocks/products/pf/feature-page-summary %}}
 Pour toute application ou solution de conversion de feuilles de calcul,**Accédez à la bibliothèque Excel via C++**Ce logiciel accélère les processus de codage, d'automatisation et de conversion tout en gérant plusieurs fichiers, notamment les formats suivants : XLSX, XLS, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML et ODS. Il permet également de convertir des fichiers Excel aux formats suivants : PDF, XPS, HTML, MHTML, texte brut et images courantes telles que JPG, TIFF, PNG, BMP et SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Interconversion des formats Excel Microsoft" %}}
 La conversion entre différents formats de tableur nécessite uniquement le chargement du tableur à l'aide de[Cahier d'exercices](https://reference.aspose.com/cells/go-cpp/workbook/) classe et l'enregistrer à nouveau au format requis en utilisant le[Sauvegarder](https://reference.aspose.com/cells/go-cpp/workbook/save_string/) la méthode de la[Cahier d'exercices](https://reference.aspose.com/cells/go-cpp//workbook/) classe.
{{% blocks/products/pf/feature-page-code h3="Accédez à l\'exemple de code C++ pour la conversion du format de fichier Excel" %}}

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


{{% blocks/products/pf/feature-page-section h2="Convertir les formats Excel au format PDF avec les paramètres de niveau de conformité" %}}
 Accédez à la documentation Excel Automation (C++). Cette documentation prend en charge la conversion des classeurs au format PDF et permet également de définir le niveau de conformité et la date de création. Les développeurs peuvent l'utiliser.[Options d'enregistrement PDF](https://reference.aspose.com/cells/go-cpp/pdfsaveoptions/)Pour définir la conformité PDF. Pour la conversion, utiliser la méthode d'enregistrement API avec PdfSaveOptions comme paramètre et le chemin du fichier de sortie spécifié.
{{% blocks/products/pf/feature-page-code h3="Accédez à l\'exemple de code C++ pour la conversion d\'Excel en PDF." %}}

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

{{% blocks/products/pf/feature-page-section h2="Enregistrer Excel sous forme d\'images" %}}
**Accédez à l'analyseur Excel via C++** Ce logiciel permet d'exporter des données sous forme d'images. Chaque feuille de calcul peut être convertie en différents formats d'image, notamment BMP, JPEG, PNG et GIF, définis par le système.[Rendu::Options d'image ou d'impression](https://reference.aspose.com/cells/go-cpp/sheetrender/toimage_int_string/) Pour tout**Convertir Excel en images** Dans ce cas, sélectionnez le cas pertinent à partir des liens.
{{% blocks/products/pf/feature-page-code h3="Utilisez le code C++ pour la conversion d\'Excel en image" %}}

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
