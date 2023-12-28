---
title:  Microsoft Excel-filkonvertering via C++
description: Aspose.Cells for C++ bibliotek. Konvertera EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL, JPG, PNG och fler 9-linjers format med 4 81 koder med bara 07 1 kod.
keywords: [C++ Aspose.Cells., excel to pdf., json to excel., txt to sql., csv to json., json to pdf., xml to excel and Convert files between various formats in C++]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel-dokumentkonvertering via C++" h2="Spara Microsoft<sup>&reg;</sup> Excel-filer som kalkylblads-, webb-, bild- och format med fast layout" >}}

{{% blocks/products/pf/feature-page-summary %}}
 För alla kalkylarksomvandlarapplikationer eller -lösningar,**C++ Excel-bibliotek** snabbar upp kodnings-, automatiserings- och konverteringsprocesser samtidigt som man hanterar flera filer inklusive XLSX, XLS, XLSM, XLSB, XLTX, XLTM, CSV, CSV, 071163481, 071163481, CSV, CSV, 3711, 371, 3487, 371, 371, 3487, 3487, 34871, 37123481 Excel till PDF**, XPS, HTML, MHTML, Vanligt Text och populära bilder som JPG, TIFF, PNG, BMP och SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Interkonvertering av Microsoft Excel-format" %}}
 Konvertering mellan kalkylarksformat kräver bara att kalkylarket laddas med hjälp av[Arbetsbok](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) klass och spara den igen i önskat format med hjälp av[Spara](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/save/) metod för[Arbetsbok](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) klass.
{{% blocks/products/pf/feature-page-code h3="C++ Exempelkod för konvertering av Excel-filformat" %}}

```cpp

Aspose::Cells::Startup();

// Load the source excel format.
Workbook wkb(u"src_excel_file.xls");
// Save in required output format.
wkb.Save(u"output_excel_format.xlsx", SaveFormat::Xlsx);

Aspose::Cells::Cleanup();

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Konvertera Excel-format till PDF med inställningar för efterlevnadsnivå" %}}
C++ Excel Automation API stöder konvertering av arbetsböcker till PDF samt stöder inställning av efterlevnadsnivå och skapandedatum. Utvecklare kan använda[PdfSaveOptions](https://reference.aspose.com/cells/cpp/aspose.cells/pdfsaveoptions/) tillsammans med[Aspose::Cells::Rendering](https://reference.aspose.com/cells/cpp/aspose.cells.rendering/) för att ställa in PDF efterlevnad. För konvertering, API spara metod med PdfSaveOptions som parameter och specificerad utdatafilsökväg.
{{% blocks/products/pf/feature-page-code h3="C++ Exempelkod för Excel till PDF konvertering" %}}

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
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="PDF" >}}

{{% blocks/products/pf/feature-page-section h2="Spara Excel till bilder" %}}
**C++ Excel Parser** har möjlighet att exportera data i form av bilder. Varje kalkylblad kan konverteras till olika bildformat inklusive BMP, JPEG, PNG och GIF, inställda av[Rendering::ImageOrPrintOptions](https://reference.aspose.com/cells/cpp/aspose.cells.rendering/imageorprintoptions/) . För alla**Konvertera Excel till bilder** ärende, välj relevant ärende från länkar.
{{% blocks/products/pf/feature-page-code h3="C++ Kod för konvertering av Excel till bild" %}}

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
