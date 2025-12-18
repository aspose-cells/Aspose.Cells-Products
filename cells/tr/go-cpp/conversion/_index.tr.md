---
title: Microsoft Go ile Excel Dosyası Dönüştürme (C++ üzerinden)
description: C++ kütüphanesi aracılığıyla Go için Aspose.Cells. EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL, JPG, PNG ve daha birçok formatı sadece birkaç satır Go koduyla C++ aracılığıyla dönüştürün.
keywords: [Go via C++ Aspose.Cells., excel to pdf., json to excel., txt to sql., csv to json., json to pdf., xml to excel and Convert files between various formats in Go via C++]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=" Microsoft<sup>&reg;</sup> Go ile Excel Belge Dönüştürme (C++ üzerinden)" h2="Excel dosyalarını elektronik tablo, web, resim ve sabit düzen formatlarında kaydedin." >}}

{{% blocks/products/pf/feature-page-summary %}}
 Herhangi bir elektronik tablo dönüştürme uygulaması veya çözümü için,**C++ Excel Kütüphanesi üzerinden gidin.**XLSX, XLS, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS dahil olmak üzere birden fazla dosyayı işlerken kodlama, otomasyon ve dönüştürme süreçlerini hızlandırır. Ayrıca Excel dosyalarını *PDF**, XPS, HTML, MHTML, Düz Metin ve JPG, TIFF, PNG, BMP ve SVG gibi popüler resim formatlarına dönüştürmeye olanak tanır.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Microsoft Excel Formatlarının Birbirine Dönüştürülmesi" %}}
 Elektronik tablo formatları arasında dönüştürme işlemi, yalnızca elektronik tabloyu yüklemeyi gerektirir.[Çalışma kitabı](https://reference.aspose.com/cells/go-cpp/workbook/) sınıfı kullanarak ve onu gerekli formatta yeniden kaydederek[Kaydetmek](https://reference.aspose.com/cells/go-cpp/workbook/save_string/) yönteminin[Çalışma kitabı](https://reference.aspose.com/cells/go-cpp//workbook/) sınıf.
{{% blocks/products/pf/feature-page-code h3="C++ üzerinden gidin Excel Dosya Biçimi Dönüştürme Örnek Kodu" %}}

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


{{% blocks/products/pf/feature-page-section h2="Excel Formatlarını Uyumluluk Düzeyi Ayarlarıyla PDF\'e Dönüştürün" %}}
 C++ Excel Otomasyonu üzerinden ilerleyin. API, çalışma kitaplarının PDF'e dönüştürülmesini ve uyumluluk düzeyi ile oluşturma tarihinin ayarlanmasını destekler. Geliştiriciler kullanabilir.[PdfKaydetmeSeçenekleri](https://reference.aspose.com/cells/go-cpp/pdfsaveoptions/)PDF uyumluluğunu ayarlamak için. Dönüştürme için, parametre olarak PdfSaveOptions ve belirtilen çıktı dosya yoluna sahip API kaydetme yöntemi kullanılır.
{{% blocks/products/pf/feature-page-code h3="Excel\'den PDF\'e Dönüştürme için C++ Örnek Kodu üzerinden gidin." %}}

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

{{% blocks/products/pf/feature-page-section h2="Excel dosyasını resimlere kaydet" %}}
**C++ Excel Ayrıştırıcısı üzerinden gidin** Verileri resim formatında dışa aktarma özelliğine sahiptir. Her çalışma sayfası, BMP, JPEG, PNG ve GIF dahil olmak üzere farklı resim formatlarına dönüştürülebilir; bu formatlar tarafından belirlenir.[Oluşturma::GörüntüOrYazdırmaSeçenekleri](https://reference.aspose.com/cells/go-cpp/sheetrender/toimage_int_string/) Herhangi bir**Excel'i Görüntülere Dönüştür** İlgili vakayı bağlantılardan seçin.
{{% blocks/products/pf/feature-page-code h3="Excel\'den Görüntüye Dönüştürme için C++ kodunu kullanın." %}}

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
