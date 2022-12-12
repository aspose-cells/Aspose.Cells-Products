---
title: Microsoft Excel-bestandsconversie via C++ 

description: Converteer Excel XLS, XLSX, ODS, CSV naar PDF, XPS, HTML, JPEG en andere formaten met slechts enkele regels C++ code.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel-documentconversie via C++" h2="Sla Microsoft<sup>&reg;</sup> Excel-bestanden op als spreadsheet-, web-, afbeeldings- en vaste indelingen" >}}

{{% blocks/products/pf/feature-page-summary %}}
Voor elke toepassing of oplossing voor het converteren van spreadsheets versnelt **C++ Excel-bibliotheek** de coderings-, automatiserings- en conversieprocessen terwijl meerdere bestanden worden verwerkt, waaronder XLSX, XLS, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Het maakt het ook mogelijk om **Excel te converteren naar PDF**, XPS, HTML, MHTML, platte tekst en populaire afbeeldingen zoals JPG, TIFF, PNG, BMP en SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Interconversie van Microsoft Excel-indelingen" %}}
Interconversie van spreadsheetformaat vereist alleen het laden van een spreadsheet met een instantie van [ intrusive_ptr<Aspose::Cells::IWorkbook>](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) aanwijzer en terug opslaan in het gewenste formaat met behulp van [Opslaan](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) methode van [IWorkbook klasse](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook).
{{% blocks/products/pf/feature-page-code h3="C++ Voorbeeldcode voor conversie van Excel-bestandsindeling" %}}

```cs

// Laad het Excel-bronformaat.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"src_excel_file.xls");

// Opslaan in het vereiste uitvoerformaat.
wkb->Save(u"output_excel_format.xlsx", SaveFormat_Xlsx);


```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Converteer Excel-indelingen naar PDF met instellingen voor nalevingsniveau" %}}
C++ Excel-automatisering API ondersteunt de conversie van werkmappen naar PDF en ondersteunt het instellen van het nalevingsniveau en de aanmaakdatum. Ontwikkelaars kunnen gebruiken [IPdfSave-opties](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_pdf_save_options) samen met [Aspose::Cells::Rendering](https://reference.aspose.com/cells/cpp/namespace/aspose.cells.rendering) om de PDF-compliance in te stellen. Voor conversie API slaat u de methode op met PdfSaveOptions als parameter en het opgegeven uitvoerbestandspad. 
{{% blocks/products/pf/feature-page-code h3="C++ Voorbeeldcode voor conversie van Excel naar PDF" %}}

```cs
// Laad het voorbeeld Excel-bestand.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sample-convert-excel-to.pdf");

// Maak een pdf-optie voor het opslaan van opties.
intrusive_ptr<Aspose::Cells::IPdfSaveOptions> pdfSaveOptions = Factory::CreateIPdfSaveOptions();

// Stel de naleving in op PDF/A-1b.
pdfSaveOptions->SetCompliance(Aspose::Cells::Rendering::PdfCompliance_PdfA1b);

// of PdfCompliance_PdfA1a 
// voor normale PDF is dit PdfCompliance_None

// Sla het Excel-document op in PDF-formaat
wkb->Save(u"output-converted-excel-workbook-to.pdf", pdfSaveOptions);



```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="PDF" >}}

{{% blocks/products/pf/feature-page-section h2="Excel opslaan in afbeeldingen" %}}
**C++ Excel Parser** heeft de mogelijkheid om gegevens in de vorm van afbeeldingen te exporteren. Elk werkblad kan worden geconverteerd naar verschillende afbeeldingsindelingen, waaronder BMP, JPEG, PNG en GIF, ingesteld door de [Rendering::IImageOrPrintOptions](https://reference.aspose.com/cells/cpp/class/aspose.cells.rendering.i_image_or_print_options). Voor elke **Convert Excel to Images** case, selecteer de relevante case uit de links.
{{% blocks/products/pf/feature-page-code h3="C++ Code voor conversie van Excel naar afbeelding" %}}

```cs
// Pad van uitvoermap.
StringPtr outDir = new String("ImagesOutputDirectoryPath");

// Laad de XLSX.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"source-excel-file.xlsx");

// Toegang tot het eerste werkblad.
intrusive_ptr<Aspose::Cells::IWorksheet> wks = wkb->GetIWorksheets()->GetObjectByIndex(0);

// Maak een afbeelding of afdrukopties-object.
intrusive_ptr<Aspose::Cells::Rendering::IImageOrPrintOptions> imgOptions = Factory::CreateIImageOrPrintOptions();

// Geef het beeldformaat op. Onderstaande code is voor JPEG
imgOptions->SetImageFormat(Aspose::Cells::Systems::Drawing::Imaging::ImageFormat::GetJpeg());

// Voor andere afbeeldingen zoals GIF, BMP en PNG kan men respectievelijk GetGif(), GetBmp() en GetPng() gebruiken 

// Specificeer horizontale en verticale resolutie
imgOptions->SetHorizontalResolution(200);
imgOptions->SetVerticalResolution(200);

// Render het vel met betrekking tot de opgegeven afbeelding of afdrukopties.
intrusive_ptr<Aspose::Cells::Rendering::ISheetRender> sr = Factory::CreateISheetRender(wks, imgOptions);

// Paginatelling ophalen.
Aspose::Cells::Systems::Int32 pageCount = sr->GetPageCount();

// Maak een stringbuilder-object voor string-aaneenschakelingen.
intrusive_ptr<Aspose::Cells::Systems::Text::StringBuilder> sb = new Aspose::Cells::Systems::Text::StringBuilder();

// Render elke pagina één voor één naar jpeg-afbeelding.
for (int i = 0; i < pageCount; i++){
	// Wis stringbuilder en maak een uitvoerafbeeldingspad met string-aaneenschakelingen.
	sb->Clear();
	sb->Append(outDir);
	sb->Append((StringPtr)new String("outputConvertingWorksheetToImageJPEG_"));
	sb->Append(i);
	sb->Append((StringPtr)new String(".jpeg"));
	// Haal het pad van de uitvoerafbeelding op.
	StringPtr outputJPEG = sb->ToString();
	// Converteer werkblad naar afbeelding.
	sr->ToImage(i, outputJPEG);
}

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xls-to-png csv-to-jpeg tsv-to-png xlsb-to-png xlsx-to-png ods-to-png spreadsheetml-to-bmp tabdelimited-to-gif xlsm-to-bmp xlt-to-gif xltm-to-png xltx-to-gif" >}}
