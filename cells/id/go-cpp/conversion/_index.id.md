---
title: Microsoft Konversi File Excel dengan Go via C++
description: Aspose.Cells untuk Go melalui pustaka C++. Konversi EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL, JPG, PNG dan format lainnya hanya dengan beberapa baris kode Go melalui C++.
keywords: [Go via C++ Aspose.Cells., excel to pdf., json to excel., txt to sql., csv to json., json to pdf., xml to excel and Convert files between various formats in Go via C++]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=" Konversi Dokumen Excel dengan Go via C++" h2="Simpan file Excel Microsoft<sup>&reg;</sup> sebagai format spreadsheet, web, gambar, dan tata letak tetap." >}}

{{% blocks/products/pf/feature-page-summary %}}
 Untuk aplikasi atau solusi konverter spreadsheet apa pun,**Buka melalui C++ Perpustakaan Excel**Mempercepat proses pengkodean, otomatisasi, dan konversi sambil menangani banyak file termasuk XLSX, XLS, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Ini juga memungkinkan untuk *mengonversi Excel ke PDF**, XPS, HTML, MHTML, Teks Biasa, dan gambar populer seperti JPG, TIFF, PNG, BMP, dan SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Konversi antar format Excel Microsoft" %}}
 Mengonversi antar format spreadsheet hanya memerlukan pemuatan spreadsheet menggunakan[Buku Kerja](https://reference.aspose.com/cells/go-cpp/workbook/) kelas dan menyimpannya kembali dalam format yang dibutuhkan menggunakan[Menyimpan](https://reference.aspose.com/cells/go-cpp/workbook/save_string/) metode[Buku Kerja](https://reference.aspose.com/cells/go-cpp//workbook/) kelas.
{{% blocks/products/pf/feature-page-code h3="Gunakan kode contoh C++ untuk konversi format file Excel." %}}

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


{{% blocks/products/pf/feature-page-section h2="Konversikan Format Excel ke PDF dengan Pengaturan Tingkat Kepatuhan" %}}
 Melalui C++ Otomatisasi Excel API mendukung konversi Buku Kerja ke PDF serta mendukung pengaturan tingkat kepatuhan dan tanggal pembuatan. Pengembang dapat menggunakan[OpsiSimpan Pdf](https://reference.aspose.com/cells/go-cpp/pdfsaveoptions/)untuk mengatur kepatuhan PDF. Untuk konversi, metode penyimpanan API memiliki parameter PdfSaveOptions dan jalur file output yang ditentukan.
{{% blocks/products/pf/feature-page-code h3="Gunakan Kode Contoh C++ untuk Konversi Excel ke PDF" %}}

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

{{% blocks/products/pf/feature-page-section h2="Simpan Excel ke Gambar" %}}
**Lewati C++ Excel Parser** Memiliki kemampuan untuk mengekspor data dalam bentuk gambar. Setiap lembar kerja dapat dikonversi ke berbagai format gambar termasuk BMP, JPEG, PNG dan GIF, yang ditetapkan oleh[Rendering::Opsi Gambar atau Cetak](https://reference.aspose.com/cells/go-cpp/sheetrender/toimage_int_string/) Untuk apa pun**Konversi Excel ke Gambar** Jika perlu, pilih kasus yang relevan dari tautan yang tersedia.
{{% blocks/products/pf/feature-page-code h3="Gunakan kode C++ untuk konversi Excel ke Gambar." %}}

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
