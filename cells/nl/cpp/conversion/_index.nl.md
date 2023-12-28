---
title:  Microsoft Excel-bestandsconversie via C++
description: Aspose.Cells for C++ bibliotheek. Converteer EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL, JPG, PNG en meer formaten met slechts enkele regels C++-code.
keywords: [C++ Aspose.Cells., excel to pdf., json to excel., txt to sql., csv to json., json to pdf., xml to excel and Convert files between various formats in C++]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel-documentconversie via C++" h2="Sla Microsoft<sup>&reg;</sup> Excel-bestanden op als spreadsheet-, web-, afbeeldings- en vaste lay-outformaten" >}}

{{% blocks/products/pf/feature-page-summary %}}
 Voor elke spreadsheetconvertertoepassing of -oplossing:**C++ Excel-bibliotheek** versnelt coderings-, automatiserings- en conversieprocessen terwijl meerdere bestanden worden verwerkt, waaronder XLSX, XLS, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Het maakt het ook mogelijk om *Excel te converteren naar PDF**, XPS, HTML, MHTML, Gewoon Tekst en populaire afbeeldingen zoals JPG, TIFF, PNG, BMP en SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Interconversie van Microsoft Excel-formaten" %}}
 Voor het converteren tussen spreadsheetformaten hoeft u alleen het spreadsheet te laden met behulp van de[Werkboek](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) class en sla het opnieuw op in het gewenste formaat met behulp van de[Redden](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/save/) werkwijze van de[Werkboek](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) klas.
{{% blocks/products/pf/feature-page-code h3="C++ Voorbeeldcode voor conversie van Excel-bestandsindeling" %}}

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


{{% blocks/products/pf/feature-page-section h2="Converteer Excel-indelingen naar PDF met instellingen voor nalevingsniveau" %}}
C++ Excel Automation API ondersteunt de conversie van werkmappen naar PDF en ondersteunt het instellen van het nalevingsniveau en de aanmaakdatum. Ontwikkelaars kunnen gebruiken[PdfSaveOpties](https://reference.aspose.com/cells/cpp/aspose.cells/pdfsaveoptions/) samen met[Aspose::Cells::Rendering](https://reference.aspose.com/cells/cpp/aspose.cells.rendering/) om de PDF-naleving in te stellen. Voor conversie gebruikt u de opslagmethode API met PdfSaveOptions als parameter en een gespecificeerd uitvoerbestandspad.
{{% blocks/products/pf/feature-page-code h3="C++ Voorbeeldcode voor Excel naar PDF Conversie" %}}

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

{{% blocks/products/pf/feature-page-section h2="Excel opslaan in afbeeldingen" %}}
**C++ Excel-parser** heeft de mogelijkheid om gegevens in de vorm van afbeeldingen te exporteren. Elk werkblad kan worden geconverteerd naar verschillende afbeeldingsformaten, waaronder BMP, JPEG, PNG en GIF, ingesteld door de[Rendering::ImageOrPrintOptions](https://reference.aspose.com/cells/cpp/aspose.cells.rendering/imageorprintoptions/) . Voor enige**Converteer Excel naar afbeeldingen** zaak, selecteer de relevante zaak uit de links.
{{% blocks/products/pf/feature-page-code h3="C++ Code voor conversie van Excel naar afbeelding" %}}

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
