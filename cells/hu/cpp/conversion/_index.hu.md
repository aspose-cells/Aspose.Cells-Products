---
title:  Microsoft Excel-fájl konvertálása a C++ számon keresztül
description: Alakítsa át az Excel XLS, XLSX, ODS, CSV, PDF, XPS, HTML, JPEG, JPEG és egyéb formátumokat 3071 kóddal, mindössze néhány 481 soros 3081 kóddal.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel-dokumentumkonverzió a C++-es számon keresztül" h2="Microsoft<sup>&reg;</sup> Excel-fájlok mentése táblázat-, web-, kép- és rögzített elrendezésű formátumokba" >}}

{{% blocks/products/pf/feature-page-summary %}}
 Bármilyen táblázatkezelő alkalmazáshoz vagy megoldáshoz,**C++ Excel Library**felgyorsítja a kódolási, automatizálási és átalakítási folyamatokat, miközben több fájlt is kezel, beleértve a XLSX, XLS, XLSM, XLSB, XLTX, XLTM, CSV, CSV, 40163481, 407183, 3018-3043 it. vert Excel PDF**, XPS, HTML, MHTML, sima számra Szöveg és népszerű képek, például JPG, TIFF, PNG, BMP és SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="A Microsoft Excel-formátumok interkonverziója" %}}
 A táblázatos formátumok közötti konvertáláshoz csak egy példányt tartalmazó táblázatot kell betölteni[ intrusive_ptr<Aspose::Cells::IWorkbook>](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) mutatót, és mentse vissza a kívánt formátumba a segítségével[Megment](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) a metódusa[IWorkbook osztály](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook).
{{% blocks/products/pf/feature-page-code h3="C++ Példakód az Excel fájlformátum konvertálásához" %}}

```cs

// Load the source excel format.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"src_excel_file.xls");

// Save in required output format.
wkb->Save(u"output_excel_format.xlsx", SaveFormat_Xlsx);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Konvertálja az Excel-formátumokat PDF-re a megfelelőségi szint beállításaival" %}}
 A C++ Excel Automation API támogatja a munkafüzetek PDF-es számra való konvertálását, valamint a megfelelőségi szint és a létrehozás dátumának beállítását. A fejlesztők használhatják[IPdfSaveOptions](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_pdf_save_options) együtt[Aspose::Cells::Rendering](https://reference.aspose.com/cells/cpp/namespace/aspose.cells.rendering) PDF megfelelőség beállításához. Az átalakításhoz a API mentési módszer PdfSaveOptions paraméterrel és meghatározott kimeneti fájl elérési úttal.
{{% blocks/products/pf/feature-page-code h3="C++ Mintakód az Excelhez PDF konvertáláshoz" %}}

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

{{% blocks/products/pf/feature-page-section h2="Excel mentése a Képek közé" %}}
**C++ Excel elemző** képes adatokat exportálni képek formájában. Minden munkalap konvertálható különböző képformátumokba, beleértve a BMP, JPEG, PNG és GIF formátumokat, amelyeket a[Rendering::IImageOrPrintOptions](https://reference.aspose.com/cells/cpp/class/aspose.cells.rendering.i_image_or_print_options) . Bármilyen**Az Excel konvertálása képekké** esetet, válassza ki a megfelelő esetet a hivatkozások közül.
{{% blocks/products/pf/feature-page-code h3="C++ Kód az Excel képpé konvertálásához" %}}

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
