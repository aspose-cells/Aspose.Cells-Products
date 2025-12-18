---
title: Microsoft การแปลงไฟล์ Excel ด้วย Go ผ่าน C++
description: Aspose.Cells สำหรับ Go ผ่านไลบรารี C++ แปลงไฟล์ EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL, JPG, PNG และรูปแบบอื่นๆ อีกมากมายด้วยโค้ด Go เพียงไม่กี่บรรทัดผ่านโค้ด C++
keywords: [Go via C++ Aspose.Cells., excel to pdf., json to excel., txt to sql., csv to json., json to pdf., xml to excel and Convert files between various formats in Go via C++]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=" Microsoft<sup>&reg;</sup> การแปลงเอกสาร Excel ด้วย Go ผ่าน C++" h2="บันทึกไฟล์ Excel หมายเลข Microsoft ในรูปแบบสเปรดชีต เว็บ รูปภาพ และรูปแบบคงที่" >}}

{{% blocks/products/pf/feature-page-summary %}}
 สำหรับแอปพลิเคชันหรือโซลูชันการแปลงสเปรดชีตใดๆ ก็ตาม**ไปที่หมายเลข C++ ในไลบรารี Excel**ช่วยเร่งกระบวนการเขียนโค้ด การทำงานอัตโนมัติ และการแปลงไฟล์ พร้อมรองรับไฟล์หลายประเภท รวมถึงไฟล์ที่มีหมายเลข XLSX, XLS, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML และ ODS นอกจากนี้ยังสามารถแปลงไฟล์ Excel เป็นไฟล์ที่มีหมายเลข PDF, XPS, HTML, MHTML, ข้อความธรรมดา และรูปภาพยอดนิยม เช่น JPG, TIFF, PNG, BMP และ SVG ได้อีกด้วย
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="การแปลงรูปแบบ Excel รหัส Microsoft" %}}
 การแปลงระหว่างรูปแบบไฟล์สเปรดชีตนั้นทำได้ง่ายๆ เพียงแค่โหลดสเปรดชีตโดยใช้โปรแกรม[สมุดงาน](https://reference.aspose.com/cells/go-cpp/workbook/) คลาสและบันทึกใหม่ในรูปแบบที่ต้องการโดยใช้[บันทึก](https://reference.aspose.com/cells/go-cpp/workbook/save_string/) วิธีการของ[สมุดงาน](https://reference.aspose.com/cells/go-cpp//workbook/) ระดับ.
{{% blocks/products/pf/feature-page-code h3="ดูที่หมายเลข C++ ตัวอย่างโค้ดสำหรับการแปลงรูปแบบไฟล์ Excel" %}}

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


{{% blocks/products/pf/feature-page-section h2="แปลงรูปแบบ Excel เป็น PDF พร้อมการตั้งค่าระดับการปฏิบัติตามข้อกำหนด" %}}
 ใช้รหัส C++ สำหรับการทำงานอัตโนมัติของ Excel รหัส API รองรับการแปลงเวิร์กบุ๊กเป็นรหัส PDF รวมถึงรองรับการตั้งค่าระดับการปฏิบัติตามข้อกำหนดและวันที่สร้าง นักพัฒนาสามารถใช้งานได้[ตัวเลือก PdfSave](https://reference.aspose.com/cells/go-cpp/pdfsaveoptions/)เพื่อตั้งค่าการปฏิบัติตามมาตรฐาน PDF สำหรับการแปลง ให้ใช้เมธอดบันทึก API โดยมีพารามิเตอร์เป็น PdfSaveOptions และระบุเส้นทางไฟล์เอาต์พุต
{{% blocks/products/pf/feature-page-code h3="ใช้รหัสตัวอย่าง C++ สำหรับการแปลง Excel เป็น PDF" %}}

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

{{% blocks/products/pf/feature-page-section h2="บันทึกไฟล์ Excel เป็นรูปภาพ" %}}
**เข้าไปที่หมายเลข C++ สำหรับโปรแกรมแยกวิเคราะห์ไฟล์ Excel** มีความสามารถในการส่งออกข้อมูลในรูปแบบรูปภาพ แต่ละเวิร์กชีตสามารถแปลงเป็นรูปแบบรูปภาพต่างๆ ได้ รวมถึง BMP, JPEG, PNG และ GIF ซึ่งกำหนดโดยโปรแกรม[การเรนเดอร์::ตัวเลือกรูปภาพหรือการพิมพ์](https://reference.aspose.com/cells/go-cpp/sheetrender/toimage_int_string/) สำหรับกรณีใดๆ**แปลงไฟล์ Excel เป็นรูปภาพ** ในกรณีดังกล่าว ให้เลือกกรณีที่เกี่ยวข้องจากลิงก์
{{% blocks/products/pf/feature-page-code h3="ใช้รหัส C++ สำหรับการแปลงไฟล์ Excel เป็นรูปภาพ" %}}

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
