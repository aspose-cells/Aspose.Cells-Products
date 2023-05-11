---
title:  Microsoft Excel-Dateikonvertierung über C++
description: Konvertieren Sie Excel XLS, XLSX, ODS, CSV in PDF, XPS, HTML, JPEG und andere Formate mit nur wenigen Zeilen C++-Code.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel-Dokumentkonvertierung über C++" h2="Speichern Sie Microsoft<sup>&reg;</sup> Excel-Dateien als Tabellenkalkulation, Web, Bild und Format mit festem Layout" >}}

{{% blocks/products/pf/feature-page-summary %}}
 Für jede Anwendung oder Lösung zum Konvertieren von Tabellenkalkulationen:**C++ Excel-Bibliothek**Beschleunigt Codierungs-, Automatisierungs- und Konvertierungsprozesse bei der Verarbeitung mehrerer Dateien, einschließlich XLSX, XLS, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Es ermöglicht auch die *Konvertierung von Excel in PDF**, XPS, HTML, MHTML, Uni Text und beliebte Bilder wie JPG, TIFF, PNG, BMP und SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Interkonvertierung von Microsoft Excel-Formaten" %}}
 Für die gegenseitige Konvertierung des Tabellenformats ist lediglich das Laden einer Tabelle mit einer Instanz von erforderlich[ intrusive_ptr<Aspose::Cells::IWorkbook>](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) Zeiger und Zurückspeichern im gewünschten Format mit[Speichern](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) Methode von[IWorkbook-Klasse](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook).
{{% blocks/products/pf/feature-page-code h3="C++ Beispielcode für die Konvertierung des Excel-Dateiformats" %}}

```cs

// Load the source excel format.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"src_excel_file.xls");

// Save in required output format.
wkb->Save(u"output_excel_format.xlsx", SaveFormat_Xlsx);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Konvertieren Sie Excel-Formate mit Konformitätsstufeneinstellungen in PDF" %}}
 C++ Excel-Automatisierung API unterstützt die Konvertierung von Arbeitsmappen in PDF sowie die Einstellung der Konformitätsstufe und des Erstellungsdatums. Entwickler können verwenden[IPdfSaveOptions](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_pdf_save_options) zusammen mit[Aspose::Cells::Rendering](https://reference.aspose.com/cells/cpp/namespace/aspose.cells.rendering)um die PDF-Konformität festzulegen. Für die Konvertierung verwenden Sie die Speichermethode API mit PdfSaveOptions als Parameter und dem angegebenen Ausgabedateipfad.
{{% blocks/products/pf/feature-page-code h3="C++ Beispielcode für die Konvertierung von Excel in PDF" %}}

```cs
// Load the sample Excel file.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sample-convert-excel-to.pdf");

// Create pdf save options object.
intrusive_ptr<Aspose::Cells::IPdfSaveOptions> pdfSaveOptions = Factory::CreateIPdfSaveOptions();

// Set the compliance to PDF/A-1b.
pdfSaveOptions->SetCompliance(Aspose::Cells::Rendering::PdfCompliance_PdfA1b);

// or PdfCompliance_PdfA1a 
// for normal PDF it will be PdfCompliance_None

// Save the Excel Document in PDF format
wkb->Save(u"output-converted-excel-workbook-to.pdf", pdfSaveOptions);


```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="PDF" >}}

{{% blocks/products/pf/feature-page-section h2="Speichern Sie Excel in Bildern" %}}
**C++ Excel-Parser** verfügt über die Möglichkeit, Daten in Form von Bildern zu exportieren. Jedes Arbeitsblatt kann in verschiedene Bildformate konvertiert werden, einschließlich BMP, JPEG, PNG und GIF, die von festgelegt werden[Rendering::IImageOrPrintOptions](https://reference.aspose.com/cells/cpp/class/aspose.cells.rendering.i_image_or_print_options) . Für jeden**Konvertieren Sie Excel in Bilder** Wählen Sie den entsprechenden Fall aus den Links aus.
{{% blocks/products/pf/feature-page-code h3="C++ Code für die Konvertierung von Excel in Bilder" %}}

```cs
// Output directory path.
StringPtr outDir = new String("ImagesOutputDirectoryPath");

// Load the XLSX.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"source-excel-file.xlsx");

// Access first worksheet.
intrusive_ptr<Aspose::Cells::IWorksheet> wks = wkb->GetIWorksheets()->GetObjectByIndex(0);

// Create image or print options object.
intrusive_ptr<Aspose::Cells::Rendering::IImageOrPrintOptions> imgOptions = Factory::CreateIImageOrPrintOptions();

// Specify the image format. Below code is for JPEG
imgOptions->SetImageFormat(Aspose::Cells::Systems::Drawing::Imaging::ImageFormat::GetJpeg());

// For other images like GIF, BMP and PNG one can use GetGif(), GetBmp() and GetPng() respectively 

// Specify horizontal and vertical resolution
imgOptions->SetHorizontalResolution(200);
imgOptions->SetVerticalResolution(200);

// Render the sheet with respect to specified image or print options.
intrusive_ptr<Aspose::Cells::Rendering::ISheetRender> sr = Factory::CreateISheetRender(wks, imgOptions);

// Get page count.
Aspose::Cells::Systems::Int32 pageCount = sr->GetPageCount();

// Create string builder object for string concatenations.
intrusive_ptr<Aspose::Cells::Systems::Text::StringBuilder> sb = new Aspose::Cells::Systems::Text::StringBuilder();

// Render each page to jpeg image one by one.
for (int i = 0; i < pageCount; i++){
	// Clear string builder and create output image path with string concatenations.
	sb->Clear();
	sb->Append(outDir);
	sb->Append((StringPtr)new String("outputConvertingWorksheetToImageJPEG_"));
	sb->Append(i);
	sb->Append((StringPtr)new String(".jpeg"));
	// Get the output image path.
	StringPtr outputJPEG = sb->ToString();
	// Convert worksheet to image.
	sr->ToImage(i, outputJPEG);
}
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xls-to-png csv-to-jpeg tsv-to-png xlsb-to-png xlsx-to-png ods-to-png spreadsheetml-to-bmp tabdelimited-to-gif xlsm-to-bmp xlt-to-gif xltm-to-png xltx-to-gif" >}}
