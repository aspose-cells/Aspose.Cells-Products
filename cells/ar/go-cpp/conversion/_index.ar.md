---
title: Microsoft تحويل ملفات إكسل باستخدام Go عبر C++
description: Aspose.Cells للغة Go عبر مكتبة C++. تحويل ملفات EXCEL، JSON، PDF، XML، HTML، TXT، TSV، CSV، SQL، JPG، PNG، وغيرها من الصيغ باستخدام بضعة أسطر فقط من كود Go عبر C++.
keywords: [Go via C++ Aspose.Cells., excel to pdf., json to excel., txt to sql., csv to json., json to pdf., xml to excel and Convert files between various formats in Go via C++]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=" Microsoft<sup>&reg;</sup> تحويل مستندات إكسل باستخدام Go عبر C++" h2="احفظ ملفات Excel بصيغ Microsoft<sup>&reg;</sup> كجداول بيانات، أو مواقع ويب، أو صور، أو بتنسيقات ثابتة." >}}

{{% blocks/products/pf/feature-page-summary %}}
 لأي تطبيق أو حل لتحويل جداول البيانات،**انتقل إلى مكتبة إكسل عبر الرقم C++**يُسرّع هذا البرنامج عمليات البرمجة والأتمتة والتحويل، ويتعامل مع ملفات متعددة، بما في ذلك الملفات ذات الصيغ XLSX، XLS، XLSM، XLSB، XLTX، XLTM، CSV، SpreadsheetML، ODS. كما يُتيح تحويل ملفات Excel إلى الصيغ PDF، XPS، HTML، MHTML، بالإضافة إلى النصوص العادية والصور الشائعة مثل JPG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="التحويل المتبادل لتنسيقات Excel Microsoft" %}}
 لا يتطلب التحويل بين تنسيقات جداول البيانات سوى تحميل جدول البيانات باستخدام[دفتر العمل](https://reference.aspose.com/cells/go-cpp/workbook/) قم بتصنيف الملف وإعادة حفظه بالتنسيق المطلوب باستخدام[يحفظ](https://reference.aspose.com/cells/go-cpp/workbook/save_string/) طريقة[دفتر العمل](https://reference.aspose.com/cells/go-cpp//workbook/) فصل.
{{% blocks/products/pf/feature-page-code h3="انتقل إلى C++ مثال على كود لتحويل تنسيق ملف Excel" %}}

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


{{% blocks/products/pf/feature-page-section h2="تحويل تنسيقات Excel إلى PDF مع إعدادات مستوى الامتثال" %}}
 يمكن الوصول إلى Excel Automation عبر الرقم C++، حيث يدعم الرقم API تحويل المصنفات إلى الرقم PDF، بالإضافة إلى دعم تحديد مستوى الامتثال وتاريخ الإنشاء. يمكن للمطورين استخدام[خيارات حفظ PDF](https://reference.aspose.com/cells/go-cpp/pdfsaveoptions/)لضبط التوافق مع المعيار PDF. للتحويل، استخدم طريقة الحفظ API مع تحديد PdfSaveOptions كمعامل ومسار ملف الإخراج المحدد.
{{% blocks/products/pf/feature-page-code h3="انتقل عبر نموذج الكود C++ لبرنامج Excel إلى تحويل PDF" %}}

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

{{% blocks/products/pf/feature-page-section h2="حفظ ملف Excel كصور" %}}
**انتقل عبر C++ محلل ملفات إكسل** يتمتع البرنامج بالقدرة على تصدير البيانات على شكل صور. يمكن تحويل كل ورقة عمل إلى تنسيقات صور مختلفة، بما في ذلك BMP وJPEG وPNG وGIF، والتي يتم تحديدها بواسطة[Rendering::ImageOrPrintOptions](https://reference.aspose.com/cells/go-cpp/sheetrender/toimage_int_string/) لأي**تحويل ملفات إكسل إلى صور** في هذه الحالة، اختر الحالة ذات الصلة من الروابط.
{{% blocks/products/pf/feature-page-code h3="استخدم الرمز C++ لتحويل ملفات Excel إلى صور" %}}

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
