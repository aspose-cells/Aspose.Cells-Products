---
title:  Microsoft Excel-fájl konvertálása a C++ számon keresztül
description: Aspose.Cells for C++ könyvtár. EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL, JPG, PNG, PNG és több formátumú 3071 kód1 és több 3071-es formátumok.
keywords: [C++ Aspose.Cells., excel to pdf., json to excel., txt to sql., csv to json., json to pdf., xml to excel and Convert files between various formats in C++]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel-dokumentumkonverzió a C++-es számon keresztül" h2="Microsoft<sup>&reg;</sup> Excel-fájlok mentése táblázat-, web-, kép- és rögzített elrendezésű formátumokba" >}}

{{% blocks/products/pf/feature-page-summary %}}
 Bármilyen táblázatkezelő alkalmazáshoz vagy megoldáshoz,**C++ Excel Library** felgyorsítja a kódolási, automatizálási és átalakítási folyamatokat, miközben több fájlt is kezel, beleértve a XLSX, XLS, XLSM, XLSB, XLTX, XLTM, XLTM, CSV, Excel-beállításokat, 307183481, 30718, 3071-as verziót is. számra: PDF**, XPS, HTML, MHTML, sima Szöveg és népszerű képek, például JPG, TIFF, PNG, BMP és SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="A Microsoft Excel-formátumok interkonverziója" %}}
 A táblázatformátumok közötti konvertáláshoz csak a táblázat segítségével kell betölteni a táblázatot[Munkafüzet](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) osztályt, majd a kívánt formátumban újra elmenteni a segítségével[Megment](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/save/) módszere a[Munkafüzet](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) osztály.
{{% blocks/products/pf/feature-page-code h3="C++ Példakód az Excel fájlformátum konvertálásához" %}}

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


{{% blocks/products/pf/feature-page-section h2="Konvertálja az Excel-formátumokat PDF-re a megfelelőségi szint beállításaival" %}}
 C++ Excel Automation API támogatja a munkafüzetek PDF-es számra való konvertálását, valamint a megfelelőségi szint és a létrehozás dátumának beállítását. A fejlesztők használhatják[PdfSaveOptions](https://reference.aspose.com/cells/cpp/aspose.cells/pdfsaveoptions/) együtt[Aspose::Cells::Rendering](https://reference.aspose.com/cells/cpp/aspose.cells.rendering/) a PDF megfelelőség beállításához. Az átalakításhoz a API mentési módszer PdfSaveOptions paraméterrel és meghatározott kimeneti fájl elérési úttal.
{{% blocks/products/pf/feature-page-code h3="C++ Mintakód az Excelhez PDF konvertáláshoz" %}}

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

{{% blocks/products/pf/feature-page-section h2="Excel mentése a Képek közé" %}}
**C++ Excel elemző** képes adatokat exportálni képek formájában. Minden munkalap konvertálható különböző képformátumokba, beleértve a BMP, JPEG, PNG és GIF formátumokat, amelyeket a[Rendering::ImageOrPrintOptions](https://reference.aspose.com/cells/cpp/aspose.cells.rendering/imageorprintoptions/) . Bármilyen**Az Excel konvertálása képekké** esetet, válassza ki a megfelelő esetet a hivatkozások közül.
{{% blocks/products/pf/feature-page-code h3="C++ Kód az Excel képpé konvertálásához" %}}

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
