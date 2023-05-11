---
title:  Microsoft Převod souborů Excel přes C++
description: Převeďte Excel XLS, XLSX, ODS, CSV na PDF, XPS, XPS, HTML, JPEG a další formáty 381 81 jen s několika málo řádky 381
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Konverze dokumentů aplikace Excel prostřednictvím čísla C++" h2="Uložte Microsoft<sup>&reg;</sup> soubory Excel jako tabulkový procesor, web, obrázky a formáty s pevným rozvržením" >}}

{{% blocks/products/pf/feature-page-summary %}}
 Pro jakoukoli aplikaci nebo řešení pro převod tabulek,**C++ Knihovna Excel**urychluje procesy kódování, automatizace a konverze při práci s více soubory včetně XLSX, XLS, XLSM, XLSB, XLTX, XLTM, CSV, CSV, CSV, 807481, umožňuje také převést na 3818183,81,81. Excel na PDF**, XPS, HTML, MHTML, obyčejný Text a oblíbené obrázky jako JPG, TIFF, PNG, BMP a SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Vzájemná konverze Microsoft formátů Excel" %}}
 Vzájemná konverze formátu tabulky vyžaduje pouze načtení tabulky s instancí[ intrusive_ptr<Aspose::Cells::IWorkbook>](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) ukazatel a uložení zpět v požadovaném formátu pomocí[Uložit](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) metoda[Třída IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook).
{{% blocks/products/pf/feature-page-code h3="C++ Příklad kódu pro převod formátu souboru aplikace Excel" %}}

```cs

// Load the source excel format.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"src_excel_file.xls");

// Save in required output format.
wkb->Save(u"output_excel_format.xlsx", SaveFormat_Xlsx);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Převeďte formáty Excelu na PDF s nastavením úrovně souladu" %}}
 C++ Excel Automation API podporuje převod sešitů na PDF a také podporuje nastavení úrovně souladu a data vytvoření. Vývojáři mohou použít[Možnosti IPdfSave](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_pdf_save_options) spolu s[Aspose::Cells::Vykreslování](https://reference.aspose.com/cells/cpp/namespace/aspose.cells.rendering)pro nastavení souladu PDF. Pro převod API metoda uložení s parametrem PdfSaveOptions a zadanou cestou k výstupnímu souboru.
{{% blocks/products/pf/feature-page-code h3="C++ Ukázkový kód pro převod Excel na PDF" %}}

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

{{% blocks/products/pf/feature-page-section h2="Uložit Excel do obrázků" %}}
**C++ Parser Excel** má možnost exportovat data ve formě obrázků. Každý list lze převést do různých obrazových formátů, včetně BMP, JPEG, PNG a GIF, nastavených[Vykreslování::IImageOrPrintOptions](https://reference.aspose.com/cells/cpp/class/aspose.cells.rendering.i_image_or_print_options) . Pro jakékoli**Převést Excel na obrázky** případ, vyberte příslušný případ z odkazů.
{{% blocks/products/pf/feature-page-code h3="C++ Kód pro převod Excelu na obrázek" %}}

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
