---
title: Microsoft Преобразование файла Excel с помощью Go через C++
description: Aspose.Cells для Go через библиотеку C++. Преобразование EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL, JPG, PNG и других форматов всего несколькими строками кода Go через C++.
keywords: [Go via C++ Aspose.Cells., excel to pdf., json to excel., txt to sql., csv to json., json to pdf., xml to excel and Convert files between various formats in Go via C++]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=" Microsoft<sup>&reg;</sup> Преобразование документа Excel с помощью Go через C++" h2="Сохраняйте файлы Excel Microsoft в форматах электронных таблиц, веб-страниц, изображений и с фиксированной разметкой." >}}

{{% blocks/products/pf/feature-page-summary %}}
 Для любого приложения или решения для преобразования электронных таблиц,**Перейти по ссылке C++ Библиотека Excel**Ускоряет процессы кодирования, автоматизации и преобразования, обрабатывая множество файлов, включая XLSX, XLS, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Также позволяет *преобразовывать файлы Excel в форматы PDF**, XPS, HTML, MHTML, простой текст и популярные изображения, такие как JPG, TIFF, PNG, BMP и SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Взаимопреобразование форматов Excel Microsoft" %}}
 Для преобразования между форматами электронных таблиц достаточно загрузить электронную таблицу, используя...[Рабочая тетрадь](https://reference.aspose.com/cells/go-cpp/workbook/) класс и повторно сохранить его в требуемом формате, используя[Сохранять](https://reference.aspose.com/cells/go-cpp/workbook/save_string/) метод[Рабочая тетрадь](https://reference.aspose.com/cells/go-cpp//workbook/) сорт.
{{% blocks/products/pf/feature-page-code h3="Перейдите по ссылке C++ Пример кода для преобразования формата файла Excel" %}}

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


{{% blocks/products/pf/feature-page-section h2="Преобразование форматов Excel в формат PDF с настройками уровня соответствия." %}}
 Перейдите по ссылке C++. Автоматизация Excel API поддерживает преобразование рабочих книг в формат PDF, а также настройку уровня соответствия и даты создания. Разработчики могут использовать...[PDFSaveOptions](https://reference.aspose.com/cells/go-cpp/pdfsaveoptions/)Для установки соответствия стандарту PDF. Для преобразования используйте метод сохранения API с параметром PdfSaveOptions и указанным путем к выходному файлу.
{{% blocks/products/pf/feature-page-code h3="Переход по коду преобразования C++ из примера кода Excel в код преобразования PDF." %}}

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

{{% blocks/products/pf/feature-page-section h2="Сохранение файла Excel в виде изображений" %}}
**Перейти через C++ Excel Parser** Программа имеет возможность экспортировать данные в виде изображений. Каждый лист может быть преобразован в различные форматы изображений, включая BMP, JPEG, PNG и GIF, в зависимости от настроек программы.[Rendering::ImageOrPrintOptions](https://reference.aspose.com/cells/go-cpp/sheetrender/toimage_int_string/) Для любого**Преобразовать файлы Excel в изображения.** В данном случае выберите соответствующий случай из ссылок.
{{% blocks/products/pf/feature-page-code h3="Воспользуйтесь кодом C++ для преобразования файлов Excel в изображения." %}}

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
