---
title: Microsoft Conversión de archivos de Excel con Go mediante C++
description: Aspose.Cells para Go a través de la biblioteca C++. Convierta EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL, JPG, PNG y más formatos con solo unas pocas líneas de código Go a través de C++.
keywords: [Go via C++ Aspose.Cells., excel to pdf., json to excel., txt to sql., csv to json., json to pdf., xml to excel and Convert files between various formats in Go via C++]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=" Microsoft<sup>&reg;</sup> Conversión de documentos de Excel con Go mediante C++" h2="Guarde archivos de Excel Microsoft<sup>&reg;</sup> como formatos de hoja de cálculo, web, imagen y diseño fijo" >}}

{{% blocks/products/pf/feature-page-summary %}}
 Para cualquier aplicación o solución de conversión de hojas de cálculo,**Ir a través de C++ Biblioteca de Excel**acelera los procesos de codificación, automatización y conversión mientras maneja múltiples archivos, incluidos XLSX, XLS, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. También permite *convertir Excel a PDF**, XPS, HTML, MHTML, texto sin formato e imágenes populares como JPG, TIFF, PNG, BMP y SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Interconversión de formatos de Excel Microsoft" %}}
 Para convertir entre formatos de hojas de cálculo solo es necesario cargar la hoja de cálculo mediante el[Libro de trabajo](https://reference.aspose.com/cells/go-cpp/workbook/) clase y volver a guardarla en el formato requerido usando el[Ahorrar](https://reference.aspose.com/cells/go-cpp/workbook/save_string/) método de la[Libro de trabajo](https://reference.aspose.com/cells/go-cpp//workbook/) clase.
{{% blocks/products/pf/feature-page-code h3="Vaya a través del código de ejemplo C++ para la conversión del formato de archivo de Excel" %}}

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


{{% blocks/products/pf/feature-page-section h2="Convertir formatos de Excel a PDF con configuración de nivel de cumplimiento" %}}
 Acceda a la automatización de Excel C++. La automatización de Excel API admite la conversión de libros de trabajo a PDF, así como la configuración del nivel de cumplimiento y la fecha de creación. Los desarrolladores pueden usar[Opciones de guardar PDF](https://reference.aspose.com/cells/go-cpp/pdfsaveoptions/)para establecer la conformidad con PDF. Para la conversión, el método de guardado API tiene PdfSaveOptions como parámetro y una ruta de archivo de salida especificada.
{{% blocks/products/pf/feature-page-code h3="Vaya a través del código de muestra C++ para la conversión de Excel a PDF" %}}

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

{{% blocks/products/pf/feature-page-section h2="Guardar Excel en imágenes" %}}
**Ir a través del analizador de Excel C++** Tiene la capacidad de exportar datos en forma de imágenes. Cada hoja de cálculo se puede convertir a diferentes formatos de imagen, incluidos BMP, JPEG, PNG y GIF, según lo establecido por el usuario.[Rendering::ImageOrPrintOptions](https://reference.aspose.com/cells/go-cpp/sheetrender/toimage_int_string/) . Para cualquier**Convertir Excel a imágenes** Caso, seleccione el caso relevante de los enlaces.
{{% blocks/products/pf/feature-page-code h3="Vaya a través del código C++ para la conversión de Excel a imagen" %}}

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
