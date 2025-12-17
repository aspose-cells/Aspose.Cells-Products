---
title: Microsoft एक्सेल फ़ाइल कन्वर्ज़न Go के ज़रिए C++
description: Go के लिए Aspose.Cells लाइब्रेरी से C++ कन्वर्ट करें। Go के C++ कोड की कुछ लाइनों से EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL, JPG, PNG और दूसरे फॉर्मेट कन्वर्ट करें।
keywords: [Go via C++ Aspose.Cells., excel to pdf., json to excel., txt to sql., csv to json., json to pdf., xml to excel and Convert files between various formats in Go via C++]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=" Microsoft<sup>&reg;</sup> C++ के ज़रिए Go के साथ Excel डॉक्यूमेंट कन्वर्ज़न" h2="Microsoft<sup>&reg;</sup> Excel फ़ाइलों को स्प्रेडशीट, वेब, इमेज और फिक्स्ड-लेआउट फ़ॉर्मेट में सेव करें" >}}

{{% blocks/products/pf/feature-page-summary %}}
 किसी भी स्प्रेडशीट कनवर्टर एप्लिकेशन या सॉल्यूशन के लिए,**C++ एक्सेल लाइब्रेरी के ज़रिए जाएं**XLSX, XLS, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS सहित कई फ़ाइलों को संभालते समय कोडिंग, स्वचालन और रूपांतरण प्रक्रियाओं को गति देता है। यह *एक्सेल को PDF**, XPS, HTML, MHTML, प्लेन टेक्स्ट और JPG, TIFF, PNG, BMP और SVG जैसी लोकप्रिय छवियों में परिवर्तित करने की भी अनुमति देता है।
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Microsoft एक्सेल फ़ॉर्मैट का इंटर-कन्वर्ज़न" %}}
 स्प्रेडशीट फ़ॉर्मैट के बीच कनवर्ट करने के लिए सिर्फ़ स्प्रेडशीट को लोड करना होता है[वर्कबुक](https://reference.aspose.com/cells/go-cpp/workbook/) क्लास का इस्तेमाल करके इसे ज़रूरी फ़ॉर्मैट में फिर से सेव करना[बचाना](https://reference.aspose.com/cells/go-cpp/workbook/save_string/) की विधि[वर्कबुक](https://reference.aspose.com/cells/go-cpp//workbook/) कक्षा।
{{% blocks/products/pf/feature-page-code h3="एक्सेल फ़ाइल फ़ॉर्मेट बदलने के लिए C++ उदाहरण कोड देखें" %}}

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


{{% blocks/products/pf/feature-page-section h2="कम्प्लायंस लेवल सेटिंग्स के साथ Excel फ़ॉर्मेट को PDF में बदलें" %}}
 C++ पर जाएं एक्सेल ऑटोमेशन API वर्कबुक को PDF में बदलने के साथ-साथ कंप्लायंस लेवल और बनाने की तारीख की सेटिंग को भी सपोर्ट करता है। डेवलपर्स इसका इस्तेमाल कर सकते हैं[पीडीएफसहेजेंविकल्प](https://reference.aspose.com/cells/go-cpp/pdfsaveoptions/)PDF कम्प्लायंस सेट करने के लिए। कन्वर्ज़न के लिए, API सेव मेथड में PdfSaveOptions पैरामीटर और स्पेसिफाइड आउटपुट फ़ाइल पाथ है।
{{% blocks/products/pf/feature-page-code h3="C++ सैंपल कोड फॉर एक्सेल से PDF कन्वर्ज़न पर जाएं" %}}

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

{{% blocks/products/pf/feature-page-section h2="Excel को इमेज में सेव करें" %}}
**C++ Excel Parser के ज़रिए जाएं** इसमें इमेज के रूप में डेटा एक्सपोर्ट करने की क्षमता है। हर वर्कशीट को अलग-अलग इमेज फ़ॉर्मैट में बदला जा सकता है, जिसमें BMP, JPEG, PNG और GIF शामिल हैं, जो इसके द्वारा सेट किए गए हैं।[रेंडरिंग::इमेजऑरप्रिंटऑप्शन](https://reference.aspose.com/cells/go-cpp/sheetrender/toimage_int_string/) . किसी भी**एक्सेल को इमेज में बदलें** केस के लिए, लिंक से संबंधित केस चुनें।
{{% blocks/products/pf/feature-page-code h3="एक्सेल से इमेज कन्वर्ज़न के लिए C++ कोड पर जाएं" %}}

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
