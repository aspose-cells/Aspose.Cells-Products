---
title:  Microsoft Konwersja plików programu Excel za pośrednictwem C++
description: Konwertuj Excel XLS, XLSX, ODS, CSV na PDF, XPS, HTML, JPEG i inne formaty za pomocą zaledwie kilku linii kodu C++.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Konwersja dokumentu Excel przez C++" h2="Zapisz Microsoft<sup>&reg;</sup> pliki programu Excel jako formaty arkuszy kalkulacyjnych, internetowych, graficznych i o stałym układzie" >}}

{{% blocks/products/pf/feature-page-summary %}}
 W przypadku dowolnej aplikacji lub rozwiązania do konwertowania arkuszy kalkulacyjnych**C++ Biblioteka programu Excel** przyspiesza kodowanie, automatyzację i procesy konwersji podczas obsługi wielu plików, w tym XLSX, XLS, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. PDF**, XPS, HTML, MHTML, Gładki Tekst i popularne obrazy, takie jak JPG, TIFF, PNG, BMP i SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Wzajemna konwersja formatów Excel Microsoft" %}}
 Wzajemna konwersja formatu arkusza kalkulacyjnego wymaga jedynie załadowania arkusza kalkulacyjnego z instancją[ natrętny_ptr<Aspose::Cells::IWorkbook>](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) wskaźnika i zapisywanie z powrotem w żądanym formacie za pomocą[Ratować](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) metoda[Klasa IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook).
{{% blocks/products/pf/feature-page-code h3="C++ Przykładowy kod konwersji formatu pliku programu Excel" %}}

```cs

// Load the source excel format.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"src_excel_file.xls");

// Save in required output format.
wkb->Save(u"output_excel_format.xlsx", SaveFormat_Xlsx);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Konwertuj formaty Excel na PDF z ustawieniami poziomu zgodności" %}}
 C++ Excel Automation API obsługuje konwersję skoroszytów do PDF, a także obsługuje ustawianie poziomu zgodności i daty utworzenia. Deweloperzy mogą korzystać[IPdfSaveOptions](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_pdf_save_options) wraz z[Aspose::Cells::Renderowanie](https://reference.aspose.com/cells/cpp/namespace/aspose.cells.rendering) aby ustawić zgodność PDF. Do konwersji należy zapisać metodę API z parametrem PdfSaveOptions i określoną ścieżką pliku wyjściowego.
{{% blocks/products/pf/feature-page-code h3="C++ Przykładowy kod programu Excel do konwersji PDF" %}}

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

{{% blocks/products/pf/feature-page-section h2="Zapisz program Excel w obrazach" %}}
**C++ Parser programu Excel** posiada możliwość eksportu danych w postaci obrazów. Każdy arkusz roboczy można przekonwertować na różne formaty obrazu, w tym BMP, JPEG, PNG i GIF, ustawione przez[Renderowanie::IImageOrPrintOptions](https://reference.aspose.com/cells/cpp/class/aspose.cells.rendering.i_image_or_print_options) . Dla każdego**Konwertuj Excel na obrazy** przypadek, wybierz odpowiedni przypadek z linków.
{{% blocks/products/pf/feature-page-code h3="C++ Kod do konwersji programu Excel na obraz" %}}

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
