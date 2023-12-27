---
title:  Microsoft Převod souborů Excel přes C++
description: Aspose.Cells for C++ knihovna. Převeďte EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL, JPG, PNG a další formáty kódu 0381 s několika řádky
keywords: [C++ Aspose.Cells., excel to pdf., json to excel., txt to sql., csv to json., json to pdf., xml to excel and Convert files between various formats in C++]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Konverze dokumentů aplikace Excel prostřednictvím čísla C++" h2="Uložte Microsoft<sup>&reg;</sup> soubory Excel jako tabulkový procesor, web, obrázky a formáty s pevným rozvržením" >}}

{{% blocks/products/pf/feature-page-summary %}}
 Pro jakoukoli aplikaci nebo řešení pro převod tabulek,**C++ Knihovna Excel** urychluje procesy kódování, automatizace a převodu při práci s více soubory včetně XLSX, XLS, XLSM, XLSB, XLSB, XLTX, XLTM, CSV, CSV, 871,81, umožňuje také převést Excel na 317734076. PDF**, XPS, HTML, MHTML, rovina Text a oblíbené obrázky jako JPG, TIFF, PNG, BMP a SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Vzájemná konverze Microsoft formátů Excel" %}}
 Převod mezi formáty tabulky vyžaduje pouze načtení tabulky pomocí souboru[pracovní sešit](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) třídy a znovu jej uložte v požadovaném formátu pomocí[Uložit](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/save/) metoda[pracovní sešit](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) třída.
{{% blocks/products/pf/feature-page-code h3="C++ Příklad kódu pro převod formátu souboru aplikace Excel" %}}

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


{{% blocks/products/pf/feature-page-section h2="Převeďte formáty Excelu na PDF s nastavením úrovně souladu" %}}
C++ Excel Automation API podporuje převod sešitů na PDF a také podporuje nastavení úrovně souladu a data vytvoření. Vývojáři mohou použít[Možnosti PdfSave](https://reference.aspose.com/cells/cpp/aspose.cells/pdfsaveoptions/) spolu s[Aspose::Cells::Vykreslování](https://reference.aspose.com/cells/cpp/aspose.cells.rendering/) pro nastavení souladu PDF. Pro převod API metoda uložení s parametrem PdfSaveOptions a zadanou cestou k výstupnímu souboru.
{{% blocks/products/pf/feature-page-code h3="C++ Ukázkový kód pro převod Excel na PDF" %}}

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

{{% blocks/products/pf/feature-page-section h2="Uložit Excel do obrázků" %}}
**C++ Parser Excel** má možnost exportovat data ve formě obrázků. Každý list lze převést do různých obrazových formátů, včetně BMP, JPEG, PNG a GIF, nastavených[Vykreslování::ImageOrPrintOptions](https://reference.aspose.com/cells/cpp/aspose.cells.rendering/imageorprintoptions/) . Pro jakékoli**Převést Excel na obrázky** případ, vyberte příslušný případ z odkazů.
{{% blocks/products/pf/feature-page-code h3="C++ Kód pro převod Excelu na obrázek" %}}

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
