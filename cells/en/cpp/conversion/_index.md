---
title: Microsoft Excel File Conversion via C++ 

description: Aspose.Cells for C++ library. Convert EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL, JPG, PNG and more formats with just few lines of C++ code.
keywords: [C++ Aspose.Cells., excel to pdf., json to excel., txt to sql., csv to json., json to pdf., xml to excel and Convert files between various formats in C++]
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel Document Conversion via C++" h2="Save Microsoft<sup>&reg;</sup> Excel files as spreadsheet, web, image and fixed-layout formats" >}}

{{% blocks/products/pf/feature-page-summary %}}
For any spreadsheet converter application or solution, **C++ Excel Library** speeds up coding, automation and conversion processes while handling multiple files including XLSX, XLS, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS.  It also allows to **convert Excel to PDF**, XPS, HTML, MHTML, Plain Text and popular images such as JPG, TIFF, PNG, BMP and SVG.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Inter-conversion of Microsoft Excel Formats" %}}
Converting between spreadsheet formats only requires loading the spreadsheet using the [Workbook](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) class and re-saving it in the required format using the [Save](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/save/) method of the [Workbook](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) class.
{{% blocks/products/pf/feature-page-code h3="C++ Example Code for Excel File Format Conversion" %}}

```cpp

Aspose::Cells::Startup();

// Load the source excel format.
Workbook wkb(u"src_excel_file.xls");
// Save in required output format.
wkb.Save(u"output_excel_format.xlsx", SaveFormat::Xlsx);

Aspose::Cells::Cleanup();

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section  h2="Convert Excel Formats to PDF with Compliance Level Settings" %}}
C++ Excel Automation API supports conversion of Workbooks to PDF as well as support setting of compliance level and creation date. Developers can use [PdfSaveOptions](https://reference.aspose.com/cells/cpp/aspose.cells/pdfsaveoptions/) along with [Aspose::Cells::Rendering](https://reference.aspose.com/cells/cpp/aspose.cells.rendering/) to set the PDF compliance.  For conversion, API save method having PdfSaveOptions as parameter and speicified output file path. 
{{% blocks/products/pf/feature-page-code h3="C++ Sample Code for Excel to PDF Conversion" %}}

```cpp

Aspose::Cells::Startup();

// Load the sample Excel file.
Workbook wkb(u"sample-convert-excel-to.pdf");
// Create pdf save options object.
PdfSaveOptions pdfSaveOptions;

// Set the compliance to PDF/A-1b.
pdfSaveOptions.SetCompliance(PdfCompliance::PdfA1b);

// or PdfCompliance::PdfA1a
// for normal PDF it will be PdfCompliance::None

// Save the Excel Document in PDF format
wkb.Save(u"output-converted-excel-workbook-to.pdf", pdfSaveOptions);

Aspose::Cells::Cleanup();

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="PDF">}}

{{% blocks/products/pf/feature-page-section  h2="Save Excel to Images" %}}
**C++ Excel Parser** has the ability to export data in the form of images. Each worksheet can be converted to different image formats including BMP, JPEG, PNG and GIF, set by the [Rendering::ImageOrPrintOptions](https://reference.aspose.com/cells/cpp/aspose.cells.rendering/imageorprintoptions/). For any **Convert Excel to Images** case, select the relevant case from links.
{{% blocks/products/pf/feature-page-code h3="C++ Code for Excel to Image Conversion" %}}

```cpp

Aspose::Cells::Startup();

// Load the XLSX.
Aspose::Cells::Workbook wkb(u"source-excel-file.xlsx");

// Access first worksheet.
Aspose::Cells::Worksheet wks = wkb.GetWorksheets().Get(0);

// Create image or print options object.
Aspose::Cells::Rendering::ImageOrPrintOptions imgOptions;

// Specify the image format. Below code is for JPEG
imgOptions.SetImageType(ImageType::Jpeg);

// For other images like GIF, BMP and PNG one can use ImageType::Gif, ImageType::Bmp and ImageType::Png respectively 

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

Aspose::Cells::Cleanup();
	
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xls-to-png csv-to-jpeg tsv-to-png xlsb-to-png xlsx-to-png ods-to-png spreadsheetml-to-bmp tabdelimited-to-gif xlsm-to-bmp xlt-to-gif xltm-to-png xltx-to-gif" >}}
