---
title:  Microsoft Konwersja plików Excel za pośrednictwem C++
description: Aspose.Cells for C++ biblioteka. Konwertuj formaty EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL, JPG, PNG i więcej za pomocą zaledwie kilku linii kodu C++.
keywords: [C++ Aspose.Cells., excel to pdf., json to excel., txt to sql., csv to json., json to pdf., xml to excel and Convert files between various formats in C++]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Konwersja dokumentów Excel pod numerem C++" h2="Zapisz Microsoft<sup>&reg;</sup> pliki Excel w formacie arkusza kalkulacyjnego, internetowego, obrazu i o stałym układzie" >}}

{{% blocks/products/pf/feature-page-summary %}}
 W przypadku dowolnej aplikacji lub rozwiązania konwertującego arkusze kalkulacyjne**C++ Biblioteka Excela** przyspiesza procesy kodowania, automatyzacji i konwersji podczas obsługi wielu plików, w tym XLSX, XLS, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Pozwala także *konwertować Excel do 0 76193481**, XPS, HTML, MHTML, Gładki Tekst i popularne obrazy, takie jak JPG, TIFF, PNG, BMP i SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Wzajemna konwersja formatów Excel Microsoft" %}}
 Konwersja między formatami arkuszy kalkulacyjnych wymaga jedynie załadowania arkusza kalkulacyjnego za pomocą[zeszyt ćwiczeń](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) class i ponowne zapisanie jej w wymaganym formacie przy użyciu pliku[Ratować](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/save/) metoda[zeszyt ćwiczeń](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) klasa.
{{% blocks/products/pf/feature-page-code h3="C++ Przykładowy kod konwersji formatu pliku Excel" %}}

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


{{% blocks/products/pf/feature-page-section h2="Konwertuj formaty Excel na PDF z ustawieniami poziomu zgodności" %}}
C++ Excel Automation API obsługuje konwersję skoroszytów do PDF, a także obsługuje ustawianie poziomu zgodności i daty utworzenia. Deweloperzy mogą korzystać[Opcje zapisywania PDF](https://reference.aspose.com/cells/cpp/aspose.cells/pdfsaveoptions/) wraz z[Aspose::Cells::Renderowanie](https://reference.aspose.com/cells/cpp/aspose.cells.rendering/) aby ustawić zgodność PDF. Do konwersji zapisz metodę API posiadającą PdfSaveOptions jako parametr i określoną ścieżkę pliku wyjściowego.
{{% blocks/products/pf/feature-page-code h3="C++ Przykładowy kod programu Excel do konwersji PDF" %}}

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

{{% blocks/products/pf/feature-page-section h2="Zapisz Excela w obrazach" %}}
**C++ Parser Excela** posiada możliwość eksportu danych w postaci obrazów. Każdy arkusz można przekonwertować na różne formaty obrazów, w tym BMP, JPEG, PNG i GIF, ustawione przez[Renderowanie::ImageOrPrintOptions](https://reference.aspose.com/cells/cpp/aspose.cells.rendering/imageorprintoptions/) . Dla każdego**Konwertuj program Excel na obrazy** przypadku wybierz odpowiedni przypadek z łączy.
{{% blocks/products/pf/feature-page-code h3="C++ Kod do konwersji programu Excel na obraz" %}}

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
