---
title: Převod souborů Microsoft Excel prostřednictvím C++ 
url: /cs/cpp/conversion/
description: Převeďte Excel XLS, XLSX, ODS, CSV do PDF, XPS, HTML, JPEG a dalších formátů pomocí několika řádků kódu C++.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Převod dokumentů Microsoft<sup>&reg;</sup> Excel prostřednictvím C++" h2="Ukládejte soubory Microsoft<sup>&reg;</sup> Excel jako tabulkový procesor, web, obrázky a formáty s pevným rozvržením" >}}

{{% blocks/products/pf/feature-page-summary %}}
Pro jakoukoli aplikaci nebo řešení pro převod tabulek **C++ knihovna Excel** urychluje procesy kódování, automatizace a převodu při práci s více soubory včetně XLSX, XLS, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Umožňuje také **převádět Excel do PDF**, XPS, HTML, MHTML, prostý text a oblíbené obrázky jako JPG, TIFF, PNG, BMP a SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Vzájemná konverze formátů Microsoft Excel" %}}
Vzájemná konverze formátu tabulky vyžaduje pouze načtení tabulky s instancí [ intrusive_ptr<Aspose::Cells::IWorkbook>](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) ukazatel a uložení zpět v požadovaném formátu pomocí [Uložit](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) metoda [Třída sešitu](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_workbook).
{{% blocks/products/pf/feature-page-code h3="C++ Příklad kódu pro převod formátu souboru aplikace Excel" %}}

```cs

// Načtěte zdrojový formát Excel.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"src_excel_file.xls");

// Uložte v požadovaném výstupním formátu.
wkb->Save(u"output_excel_format.xlsx", SaveFormat_Xlsx);


```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Převeďte formáty Excelu do PDF s nastavením úrovně shody" %}}
C++Excel AutomationAPI podporuje převod sešitů do PDF a také podporuje nastavení úrovně souladu a data vytvoření. Vývojáři mohou použít [Možnosti IPdfSave](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_pdf_save_options) spolu s [Aspose::Cells::Vykreslování](https://apireference.aspose.com/cells/cpp/namespace/aspose.cells.rendering) pro nastavení souladu s PDF. Pro převod použijte API metodu uložení s parametrem PdfSaveOptions a zadanou cestu k výstupnímu souboru. 
{{% blocks/products/pf/feature-page-code h3="C++ Ukázkový kód pro převod Excelu do PDF" %}}

```cs
// Načtěte ukázkový soubor Excel.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sample-convert-excel-to.pdf");

// Vytvořit objekt možností uložení pdf.
intrusive_ptr<Aspose::Cells::IPdfSaveOptions> pdfSaveOptions = Factory::CreateIPdfSaveOptions();

// Nastavte shodu na PDF/A-1b.
pdfSaveOptions->SetCompliance(Aspose::Cells::Rendering::PdfCompliance_PdfA1b);

// nebo PdfCompliance_PdfA1a 
// pro normální PDF to bude PdfCompliance_None

// Uložte dokument Excel ve formátu PDF
wkb->Save(u"output-converted-excel-workbook-to.pdf", pdfSaveOptions);



```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="PDF" >}}

{{% blocks/products/pf/feature-page-section h2="Uložit Excel do obrázků" %}}
**C++ Excel Parser** má schopnost exportovat data ve formě obrázků. Každý list lze převést do různých obrazových formátů, včetně BMP, JPEG, PNG a GIF, podle nastavení [Vykreslování::IImageOrPrintOptions](https://apireference.aspose.com/cells/cpp/class/aspose.cells.rendering.i_image_or_print_options). Pro jakýkoli případ **Převést Excel na obrázky** vyberte příslušný případ z odkazů.
{{% blocks/products/pf/feature-page-code h3="C++ Kód pro převod Excelu na obrázek" %}}

```cs
// Cesta výstupního adresáře.
StringPtr outDir = new String("ImagesOutputDirectoryPath");

// Vložte XLSX.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"source-excel-file.xlsx");

// Přístup k prvnímu listu.
intrusive_ptr<Aspose::Cells::IWorksheet> wks = wkb->GetIWorksheets()->GetObjectByIndex(0);

// Vytvořte objekt možností obrázku nebo tisku.
intrusive_ptr<Aspose::Cells::Rendering::IImageOrPrintOptions> imgOptions = Factory::CreateIImageOrPrintOptions();

// Určete formát obrázku. Níže uvedený kód je pro JPEG
imgOptions->SetImageFormat(Aspose::Cells::Systems::Drawing::Imaging::ImageFormat::GetJpeg());

// Pro další obrázky jako GIF, BMP a PNG lze použít GetGif(), GetBmp() a GetPng() 

// Určete horizontální a vertikální rozlišení
imgOptions->SetHorizontalResolution(200);
imgOptions->SetVerticalResolution(200);

// Vykreslete list s ohledem na zadané možnosti obrázku nebo tisku.
intrusive_ptr<Aspose::Cells::Rendering::ISheetRender> sr = Factory::CreateISheetRender(wks, imgOptions);

// Získejte počet stránek.
Aspose::Cells::Systems::Int32 pageCount = sr->GetPageCount();

// Vytvořte objekt pro vytváření řetězců pro zřetězení řetězců.
intrusive_ptr<Aspose::Cells::Systems::Text::StringBuilder> sb = new Aspose::Cells::Systems::Text::StringBuilder();

// Vykreslete každou stránku na obrázek jpeg jednu po druhé.
for (int i = 0; i < pageCount; i++){
	// Vymažte nástroj pro tvorbu řetězců a vytvořte cestu k výstupnímu obrazu se zřetězením řetězců.
	sb->Clear();
	sb->Append(outDir);
	sb->Append((StringPtr)new String("outputConvertingWorksheetToImageJPEG_"));
	sb->Append(i);
	sb->Append((StringPtr)new String(".jpeg"));
	// Získejte cestu k výstupnímu obrazu.
	StringPtr outputJPEG = sb->ToString();
	// Převést pracovní list na obrázek.
	sr->ToImage(i, outputJPEG);
}

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xls-to-png csv-to-jpeg tsv-to-png xlsb-to-png xlsx-to-png ods-to-png spreadsheetml-to-bmp tabdelimited-to-gif xlsm-to-bmp xlt-to-gif xltm-to-png xltx-to-gif" >}}