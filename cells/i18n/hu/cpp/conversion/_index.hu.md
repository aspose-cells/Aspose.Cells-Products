---
title: "Microsoft Excel fájlkonverzió a következőn keresztül: C++ "
url: /hu/cpp/conversion/
description: Konvertálja az Excel XLS-t, XLSX-et, ODS-t, CSV-t PDF, XPS, HTML, JPEG és más formátumokká, mindössze néhány soros C++ kóddal.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel-dokumentumkonverzió a következőn keresztül: C++" h2="Microsoft<sup>&reg;</sup> Excel-fájlok mentése táblázat-, web-, kép- és rögzített elrendezésű formátumban" >}}

{{% blocks/products/pf/feature-page-summary %}}
Bármilyen táblázatkezelő alkalmazás vagy megoldás esetén az **C++ Excel Library** felgyorsítja a kódolási, automatizálási és átalakítási folyamatokat, miközben több fájlt is kezel, beleértve az XLSX, XLS, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML és ODS fájlokat. Lehetővé teszi továbbá az Excel **konvertálását PDF-be**, XPS-be, HTML-be, MHTML-be, egyszerű szöveggé és olyan népszerű képekbe, mint a JPG, TIFF, PNG, BMP és SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Microsoft Excel formátumok interkonvertálása" %}}
A táblázatformátumok közötti konvertáláshoz csak egy példányt tartalmazó táblázatot kell betölteni [ intrusive_ptr<Aspose::Cells::IWorkbook>](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) mutatót, és mentse vissza a kívánt formátumba a segítségével [Megment](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) a metódusa [IWorkbook osztály](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_workbook).
{{% blocks/products/pf/feature-page-code h3="C++ Példakód az Excel fájlformátum konvertálásához" %}}

```cs

// Töltse be a forrás excel formátumot.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"src_excel_file.xls");

// Mentse el a kívánt kimeneti formátumban.
wkb->Save(u"output_excel_format.xlsx", SaveFormat_Xlsx);


```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Konvertálja az Excel formátumokat PDF-be a megfelelőségi szint beállításaival" %}}
Az C++ Excel Automation API támogatja a munkafüzetek PDF formátumba konvertálását, valamint a megfelelőségi szint és a létrehozás dátumának beállítását. A fejlesztők használhatják [IPdfSaveOptions](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_pdf_save_options) együtt [Aspose::Cells::Megjelenítés](https://apireference.aspose.com/cells/cpp/namespace/aspose.cells.rendering) a PDF megfelelőségének beállításához. A konverzióhoz a API mentési módszert használja PdfSaveOptions paraméterként és meghatározott kimeneti fájl elérési úttal. 
{{% blocks/products/pf/feature-page-code h3="C++ Mintakód az Excel PDF-be konvertálásához" %}}

```cs
// Töltse be az Excel mintafájlt.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sample-convert-excel-to.pdf");

// Pdf mentési beállítások objektum létrehozása.
intrusive_ptr<Aspose::Cells::IPdfSaveOptions> pdfSaveOptions = Factory::CreateIPdfSaveOptions();

// Állítsa be a megfelelőséget PDF/A-1b értékre.
pdfSaveOptions->SetCompliance(Aspose::Cells::Rendering::PdfCompliance_PdfA1b);

// vagy PdfCompliance_PdfA1a 
// normál PDF esetén PdfCompliance_None lesz

// Mentse el az Excel dokumentumot PDF formátumban
wkb->Save(u"output-converted-excel-workbook-to.pdf", pdfSaveOptions);



```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="PDF" >}}

{{% blocks/products/pf/feature-page-section h2="Excel mentése a Képek közé" %}}
**C++Az Excel Parser** képes adatokat exportálni képek formájában. Minden munkalap konvertálható különböző képformátumokba, mint például BMP, JPEG, PNG és GIF, amelyeket a [Rendering::IImageOrPrintOptions](https://apireference.aspose.com/cells/cpp/class/aspose.cells.rendering.i_image_or_print_options). Minden **Excel konvertálása képekké** esethez válassza ki a megfelelő esetet a hivatkozások közül.
{{% blocks/products/pf/feature-page-code h3="C++ Kód az Excel képpé konvertálásához" %}}

```cs
// Kimeneti könyvtár elérési útja.
StringPtr outDir = new String("ImagesOutputDirectoryPath");

// Töltse be az XLSX-et.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"source-excel-file.xlsx");

// Az első munkalap elérése.
intrusive_ptr<Aspose::Cells::IWorksheet> wks = wkb->GetIWorksheets()->GetObjectByIndex(0);

// Kép vagy nyomtatási beállítások objektum létrehozása.
intrusive_ptr<Aspose::Cells::Rendering::IImageOrPrintOptions> imgOptions = Factory::CreateIImageOrPrintOptions();

// Adja meg a képformátumot. Az alábbi kód a JPEG
imgOptions->SetImageFormat(Aspose::Cells::Systems::Drawing::Imaging::ImageFormat::GetJpeg());

// Más képekhez, mint a GIF, BMP és PNG, használhatja a GetGif(), GetBmp() és GetPng() parancsot. 

// Adja meg a vízszintes és függőleges felbontást
imgOptions->SetHorizontalResolution(200);
imgOptions->SetVerticalResolution(200);

// Renderje le a lapot a megadott kép- vagy nyomtatási beállításoknak megfelelően.
intrusive_ptr<Aspose::Cells::Rendering::ISheetRender> sr = Factory::CreateISheetRender(wks, imgOptions);

// Oldalszám lekérése.
Aspose::Cells::Systems::Int32 pageCount = sr->GetPageCount();

// Hozzon létre karakterlánc-építő objektumot a karakterlánc-összefűzéshez.
intrusive_ptr<Aspose::Cells::Systems::Text::StringBuilder> sb = new Aspose::Cells::Systems::Text::StringBuilder();

// Minden oldalt egyenként renderelj jpeg képpé.
for (int i = 0; i < pageCount; i++){
	// Törölje a karakterlánc-építőt, és hozzon létre kimeneti kép elérési utat karakterlánc-összefűzéssel.
	sb->Clear();
	sb->Append(outDir);
	sb->Append((StringPtr)new String("outputConvertingWorksheetToImageJPEG_"));
	sb->Append(i);
	sb->Append((StringPtr)new String(".jpeg"));
	// Szerezze meg a kimeneti kép elérési útját.
	StringPtr outputJPEG = sb->ToString();
	// Munkalap konvertálása képpé.
	sr->ToImage(i, outputJPEG);
}

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xls-to-png csv-to-jpeg tsv-to-png xlsb-to-png xlsx-to-png ods-to-png spreadsheetml-to-bmp tabdelimited-to-gif xlsm-to-bmp xlt-to-gif xltm-to-png xltx-to-gif" >}}