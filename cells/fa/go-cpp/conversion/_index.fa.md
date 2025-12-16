---
title: تبدیل فایل اکسل با Go از طریق Microsoft
description: Aspose.Cells برای Go از طریق کتابخانه C++. تبدیل فرمت‌های EXCEL، JSON، PDF، XML، HTML، TXT، TSV، CSV، SQL، JPG، PNG و فرمت‌های دیگر تنها با چند خط کد Go از طریق C++.
keywords: [Go via C++ Aspose.Cells., excel to pdf., json to excel., txt to sql., csv to json., json to pdf., xml to excel and Convert files between various formats in Go via C++]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=" ‎Microsoft تبدیل اسناد اکسل با Go از طریق ‎C++‎" h2="فایل‌های اکسل Microsoft را به صورت فرمت‌های صفحه گسترده، وب، تصویر و قالب‌های با طرح ثابت ذخیره کنید" >}}

{{% blocks/products/pf/feature-page-summary %}}
 برای هر برنامه یا راهکار مبدل صفحه گسترده،**از طریق C++ به کتابخانه اکسل بروید**سرعت کدنویسی، اتوماسیون و فرآیندهای تبدیل را هنگام مدیریت چندین فایل از جمله XLSX، XLS، XLSM، XLSB، XLTX، XLTM، CSV، SpreadsheetML، ODS افزایش می‌دهد. همچنین امکان *تبدیل اکسل به PDF**، XPS، HTML، MHTML، متن ساده و تصاویر محبوب مانند JPG، TIFF، PNG، BMP و SVG را فراهم می‌کند.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="تبدیل فرمت‌های اکسل Microsoft به یکدیگر" %}}
 تبدیل بین قالب‌های صفحه‌گسترده فقط نیاز به بارگیری صفحه‌گسترده با استفاده از[کتاب کار](https://reference.aspose.com/cells/go-cpp/workbook/) کلاس و ذخیره مجدد آن در قالب مورد نیاز با استفاده از[ذخیره](https://reference.aspose.com/cells/go-cpp/workbook/save_string/) روش[کتاب کار](https://reference.aspose.com/cells/go-cpp//workbook/) کلاس
{{% blocks/products/pf/feature-page-code h3="از طریق کد نمونه C++ برای تبدیل فرمت فایل اکسل اقدام کنید" %}}

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


{{% blocks/products/pf/feature-page-section h2="تبدیل فرمت‌های اکسل به PDF با تنظیمات سطح انطباق" %}}
 برو از طریق C++ اتوماسیون اکسل API از تبدیل کتاب‌های کاری به PDF و همچنین تنظیم سطح انطباق و تاریخ ایجاد پشتیبانی می‌کند. توسعه‌دهندگان می‌توانند از[گزینه‌های ذخیره پی‌دی‌اف](https://reference.aspose.com/cells/go-cpp/pdfsaveoptions/)برای تنظیم انطباق با استاندارد PDF. برای تبدیل، متد ذخیره API با پارامتر PdfSaveOptions و مسیر فایل خروجی مشخص شده.
{{% blocks/products/pf/feature-page-code h3="از طریق نمونه کد C++ برای تبدیل اکسل به PDF اقدام کنید" %}}

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

{{% blocks/products/pf/feature-page-section h2="ذخیره اکسل به صورت تصویر" %}}
**از طریق تجزیه‌گر اکسل C++ اقدام کنید** قابلیت خروجی گرفتن از داده‌ها به شکل تصاویر را دارد. هر برگه کاری را می‌توان به فرمت‌های تصویری مختلف از جمله BMP، JPEG، PNG و GIF که توسط ... تنظیم شده‌اند، تبدیل کرد.[رندرینگ::ImageOrPrintOptions](https://reference.aspose.com/cells/go-cpp/sheetrender/toimage_int_string/) برای هر**تبدیل اکسل به تصاویر** مورد، مورد مربوطه را از لینک‌ها انتخاب کنید.
{{% blocks/products/pf/feature-page-code h3="برای تبدیل اکسل به تصویر، از طریق کد C++ اقدام کنید" %}}

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
