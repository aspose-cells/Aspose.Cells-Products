---
title:  Microsoft Excel-Dateikonvertierung über C++
description: Aspose.Cells for C++ Bibliothek. Konvertieren Sie Excel, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL, JPG, PNG und weitere Formate mit nur wenigen Zeilen C++-Code.
keywords: [C++ Aspose.Cells., excel to pdf., json to excel., txt to sql., csv to json., json to pdf., xml to excel and Convert files between various formats in C++]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel-Dokumentkonvertierung über C++" h2="Speichern Sie Microsoft<sup>&reg;</sup> Excel-Dateien als Tabellenkalkulation, Web, Bild und Format mit festem Layout" >}}

{{% blocks/products/pf/feature-page-summary %}}
 Für jede Anwendung oder Lösung zum Konvertieren von Tabellenkalkulationen:**C++ Excel-Bibliothek** Beschleunigt Codierungs-, Automatisierungs- und Konvertierungsprozesse bei der Verarbeitung mehrerer Dateien, einschließlich XLSX, XLS, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Es ermöglicht auch die *Konvertierung von Excel in 0 76193481**, XPS, HTML, MHTML, Einfach Text und beliebte Bilder wie JPG, TIFF, PNG, BMP und SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Interkonvertierung von Microsoft Excel-Formaten" %}}
 Für die Konvertierung zwischen Tabellenkalkulationsformaten ist lediglich das Laden der Tabellenkalkulation mit erforderlich[Arbeitsmappe](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) Klasse und speichern Sie sie erneut im erforderlichen Format mit der[Speichern](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/save/) Methode der[Arbeitsmappe](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) Klasse.
{{% blocks/products/pf/feature-page-code h3="C++ Beispielcode für die Konvertierung des Excel-Dateiformats" %}}

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


{{% blocks/products/pf/feature-page-section h2="Konvertieren Sie Excel-Formate mit Konformitätsstufeneinstellungen in PDF" %}}
C++ Excel-Automatisierung API unterstützt die Konvertierung von Arbeitsmappen in PDF sowie die Einstellung der Konformitätsstufe und des Erstellungsdatums. Entwickler können verwenden[PDFSaveOptions](https://reference.aspose.com/cells/cpp/aspose.cells/pdfsaveoptions/) zusammen mit[Aspose::Cells::Rendering](https://reference.aspose.com/cells/cpp/aspose.cells.rendering/) um die PDF-Konformität festzulegen. Für die Konvertierung verwenden Sie die Speichermethode API mit PdfSaveOptions als Parameter und dem angegebenen Ausgabedateipfad.
{{% blocks/products/pf/feature-page-code h3="C++ Beispielcode für die Konvertierung von Excel in PDF" %}}

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

{{% blocks/products/pf/feature-page-section h2="Speichern Sie Excel in Bildern" %}}
**C++ Excel-Parser** verfügt über die Möglichkeit, Daten in Form von Bildern zu exportieren. Jedes Arbeitsblatt kann in verschiedene Bildformate konvertiert werden, einschließlich BMP, JPEG, PNG und GIF, die von festgelegt werden[Rendering::ImageOrPrintOptions](https://reference.aspose.com/cells/cpp/aspose.cells.rendering/imageorprintoptions/) . Für jeden**Konvertieren Sie Excel in Bilder** Wählen Sie den entsprechenden Fall aus den Links aus.
{{% blocks/products/pf/feature-page-code h3="C++ Code für die Konvertierung von Excel in Bilder" %}}

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
