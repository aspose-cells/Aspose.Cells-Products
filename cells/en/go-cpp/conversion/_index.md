---
title: Microsoft Excel File Conversion with Go via C++

description: Aspose.Cells for Go via C++ library. Convert EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL, JPG, PNG and more formats with just few lines of Go via C++ code.
keywords: [Go via C++ Aspose.Cells., excel to pdf., json to excel., txt to sql., csv to json., json to pdf., xml to excel and Convert files between various formats in Go via C++]
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel Document Conversion with Go via C++ " h2="Save Microsoft<sup>&reg;</sup> Excel files as spreadsheet, web, image and fixed-layout formats" >}}

{{% blocks/products/pf/feature-page-summary %}}
For any spreadsheet converter application or solution, **Go via C++ Excel Library** speeds up coding, automation and conversion processes while handling multiple files including XLSX, XLS, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS.  It also allows to **convert Excel to PDF**, XPS, HTML, MHTML, Plain Text and popular images such as JPG, TIFF, PNG, BMP and SVG.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Inter-conversion of Microsoft Excel Formats" %}}
Converting between spreadsheet formats only requires loading the spreadsheet using the [Workbook](https://reference.aspose.com/cells/go-cpp/workbook/) class and re-saving it in the required format using the [Save](https://reference.aspose.com/cells/go-cpp/workbook/save_string/) method of the [Workbook](https://reference.aspose.com/cells/go-cpp//workbook/) class.
{{% blocks/products/pf/feature-page-code h3="Go via C++ Example Code for Excel File Format Conversion" %}}

```go

package main

import (
    . "github.com/Aspose-Cells/aspose-cells-go-cpp/v24"
)
// Load the source excel format.
workbook, := NewWorkbook("src_excel_file.xlsx")
// Save in required output format.
workbook.Save_String("output_excel_format.xlsx")

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section  h2="Convert Excel Formats to PDF with Compliance Level Settings" %}}
Go via C++ Excel Automation API supports conversion of Workbooks to PDF as well as support setting of compliance level and creation date. Developers can use [PdfSaveOptions](https://reference.aspose.com/cells/go-cpp/pdfsaveoptions/) to set the PDF compliance.  For conversion, API save method having PdfSaveOptions as parameter and speicified output file path.
{{% blocks/products/pf/feature-page-code h3="Go via C++ Sample Code for Excel to PDF Conversion" %}}

```go

package main

import (
    . "github.com/Aspose-Cells/aspose-cells-go-cpp/v24"
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
workbook.Save_String("../Data/Output/HELLO_Convert.pdf")
println("Finish to convert to PDF , check .pdf file in output folder.")


```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="PDF">}}

{{% blocks/products/pf/feature-page-section  h2="Save Excel to Images" %}}
**Go via C++ Excel Parser** has the ability to export data in the form of images. Each worksheet can be converted to different image formats including BMP, JPEG, PNG and GIF, set by the [Rendering::ImageOrPrintOptions](https://reference.aspose.com/cells/go-cpp/sheetrender/toimage_int_string/). For any **Convert Excel to Images** case, select the relevant case from links.
{{% blocks/products/pf/feature-page-code h3="Go via C++ Code for Excel to Image Conversion" %}}

```go

package main

import (
    . "github.com/Aspose-Cells/aspose-cells-go-cpp/v24"
)

// Load the XLSX.
workbook, := NewWorkbook("source-excel-file.xlsx")

// Access first worksheet.
worksheets, _ := workbook.GetWorksheets()
worksheet, _ := worksheets.Get_Int(0)

// Create image or print options object.
imgOptions := NewImageOrPrintOptions()

// Specify the image format. Below code is for JPEG
imgOptions.SetImageType(ImageType::Jpeg)

// Specify horizontal and vertical resolution
imgOptions.SetHorizontalResolution(200);
imgOptions.SetVerticalResolution(200);

// Render the sheet with respect to specified image or print options.
Aspose::Cells::Rendering::SheetRender sr(wks, imgOptions);

// Get page count.
int pageCount = sr.GetPageCount();

std::string sb = "";
// Render each page to jpeg image one by one.
for (int i = 0; i < pageCount; i++) {
	sb = "";
	sb += "ImagesOutputDirectoryPath/";
	sb += "outputConvertingWorksheetToImageJPEG_";
	sb += std::to_string(i);
	sb += ".jpeg";
	// Get the output image path.
	U16String outputJPEG(sb.c_str());
	// Convert worksheet to image.
	sr.ToImage(i, outputJPEG);
}


```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xls-to-png csv-to-jpeg tsv-to-png xlsb-to-png xlsx-to-png ods-to-png spreadsheetml-to-bmp tabdelimited-to-gif xlsm-to-bmp xlt-to-gif xltm-to-png xltx-to-gif" >}}

{{< /blocks/products/pf/feature-page-wrap >}}
