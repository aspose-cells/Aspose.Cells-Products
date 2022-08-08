---
title: Microsoft Excel-filkonvertering via C++ 
url: /sv/cpp/conversion/
description: Konvertera Excel XLS, XLSX, ODS, CSV till PDF, XPS, HTML, JPEG och andra format med bara några rader med C++-kod.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel-dokumentkonvertering via C++" h2="Spara Microsoft<sup>&reg;</sup> Excel-filer som kalkylblads-, webb-, bild- och format med fast layout" >}}

{{% blocks/products/pf/feature-page-summary %}}
För alla applikationer eller lösningar för kalkylarksomvandlare snabbar **C++ Excel Library** upp kodnings-, automatiserings- och konverteringsprocesser samtidigt som du hanterar flera filer inklusive XLSX, XLS, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Det gör det också möjligt att **konvertera Excel till PDF**, XPS, HTML, MHTML, vanlig text och populära bilder som JPG, TIFF, PNG, BMP och SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Interkonvertering av Microsoft Excel-format" %}}
Interkonvertering av kalkylarksformat kräver bara att ett kalkylblad laddas med en instans av [ intrusive_ptr<Aspose::Cells::IWorkbook>](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) pekaren och spara tillbaka i önskat format med hjälp av [Spara](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) metod av [IWorkbook klass](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook).
{{% blocks/products/pf/feature-page-code h3="C++ Exempelkod för konvertering av Excel-filformat" %}}

```cs

// Ladda källans Excel-format.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"src_excel_file.xls");

// Spara i önskat utdataformat.
wkb->Save(u"output_excel_format.xlsx", SaveFormat_Xlsx);


```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Konvertera Excel-format till PDF med inställningar för efterlevnadsnivå" %}}
C++ Excel Automation API stöder konvertering av arbetsböcker till PDF samt stödinställning av efterlevnadsnivå och skapandedatum. Utvecklare kan använda [IPdfSaveOptions](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_pdf_save_options) tillsammans med [Aspose::Cells::Rendering](https://reference.aspose.com/cells/cpp/namespace/aspose.cells.rendering) för att ställa in PDF-kompatibilitet. För konvertering, API spara metod med PdfSaveOptions som parameter och specificerad utdatafilsökväg. 
{{% blocks/products/pf/feature-page-code h3="C++ Exempelkod för konvertering av Excel till PDF" %}}

```cs
// Ladda Excel-exempelfilen.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sample-convert-excel-to.pdf");

// Skapa pdf spara alternativ objekt.
intrusive_ptr<Aspose::Cells::IPdfSaveOptions> pdfSaveOptions = Factory::CreateIPdfSaveOptions();

// Ställ in överensstämmelsen till PDF/A-1b.
pdfSaveOptions->SetCompliance(Aspose::Cells::Rendering::PdfCompliance_PdfA1b);

// eller PdfCompliance_PdfA1a 
// för normal PDF blir det PdfCompliance_None

// Spara Excel-dokumentet i PDF-format
wkb->Save(u"output-converted-excel-workbook-to.pdf", pdfSaveOptions);



```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="PDF" >}}

{{% blocks/products/pf/feature-page-section h2="Spara Excel till bilder" %}}
**C++ Excel Parser** har möjlighet att exportera data i form av bilder. Varje kalkylblad kan konverteras till olika bildformat inklusive BMP, JPEG, PNG och GIF, inställda av [Rendering::IImageOrPrintOptions](https://reference.aspose.com/cells/cpp/class/aspose.cells.rendering.i_image_or_print_options). För alla fall av **Konvertera Excel till bilder**, välj relevant fall från länkarna.
{{% blocks/products/pf/feature-page-code h3="C++ Kod för konvertering av Excel till bild" %}}

```cs
// Utdatakatalogsökväg.
StringPtr outDir = new String("ImagesOutputDirectoryPath");

// Ladda XLSX.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"source-excel-file.xlsx");

// Öppna första kalkylbladet.
intrusive_ptr<Aspose::Cells::IWorksheet> wks = wkb->GetIWorksheets()->GetObjectByIndex(0);

// Skapa bild- eller utskriftsalternativ.
intrusive_ptr<Aspose::Cells::Rendering::IImageOrPrintOptions> imgOptions = Factory::CreateIImageOrPrintOptions();

// Ange bildformat. Nedanstående kod är för JPEG
imgOptions->SetImageFormat(Aspose::Cells::Systems::Drawing::Imaging::ImageFormat::GetJpeg());

// För andra bilder som GIF, BMP och PNG kan man använda GetGif(), GetBmp() respektive GetPng() 

// Ange horisontell och vertikal upplösning
imgOptions->SetHorizontalResolution(200);
imgOptions->SetVerticalResolution(200);

// Rendera arket med hänsyn till angivna bild- eller utskriftsalternativ.
intrusive_ptr<Aspose::Cells::Rendering::ISheetRender> sr = Factory::CreateISheetRender(wks, imgOptions);

// Få sidantal.
Aspose::Cells::Systems::Int32 pageCount = sr->GetPageCount();

// Skapa strängbyggarobjekt för strängsammansättningar.
intrusive_ptr<Aspose::Cells::Systems::Text::StringBuilder> sb = new Aspose::Cells::Systems::Text::StringBuilder();

// Gör varje sida till jpeg-bild en efter en.
for (int i = 0; i < pageCount; i++){
	// Rensa strängbyggare och skapa utdatabildsökväg med strängsammansättningar.
	sb->Clear();
	sb->Append(outDir);
	sb->Append((StringPtr)new String("outputConvertingWorksheetToImageJPEG_"));
	sb->Append(i);
	sb->Append((StringPtr)new String(".jpeg"));
	// Hämta utdatabildens sökväg.
	StringPtr outputJPEG = sb->ToString();
	// Konvertera kalkylblad till bild.
	sr->ToImage(i, outputJPEG);
}

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xls-to-png csv-to-jpeg tsv-to-png xlsb-to-png xlsx-to-png ods-to-png spreadsheetml-to-bmp tabdelimited-to-gif xlsm-to-bmp xlt-to-gif xltm-to-png xltx-to-gif" >}}