---
title: Konwersja plików Microsoft Excel przez C++ 
url: /pl/cpp/conversion/
description: Konwertuj Excel XLS, XLSX, ODS, CSV do PDF, XPS, HTML, JPEG i innych formatów za pomocą zaledwie kilku linijek kodu C++.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konwersja dokumentów Microsoft<sup>&reg;</sup> Excel przez C++" h2="Zapisuj pliki Microsoft<sup>&reg;</sup> Excel jako arkusze kalkulacyjne, strony internetowe, obrazy i formaty o stałym układzie" >}}

{{% blocks/products/pf/feature-page-summary %}}
W przypadku dowolnej aplikacji lub rozwiązania konwertującego arkusze kalkulacyjne **C++ Biblioteka Excel** przyspiesza procesy kodowania, automatyzacji i konwersji podczas obsługi wielu plików, w tym XLSX, XLS, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Pozwala także na **konwertowanie Excela na PDF**, XPS, HTML, MHTML, zwykły tekst i popularne obrazy, takie jak JPG, TIFF, PNG, BMP i SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Konwersja wzajemna formatów Microsoft Excel" %}}
Konwersja między formatami arkusza kalkulacyjnego wymaga tylko załadowania arkusza kalkulacyjnego z wystąpieniem [ intrusive_ptr<Aspose::Cells::IWorkbook>](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) wskaźnik i zapisywanie z powrotem w żądanym formacie za pomocą [Ratować](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) metoda [Klasa IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook).
{{% blocks/products/pf/feature-page-code h3="C++ Przykładowy kod konwersji formatu pliku Excel" %}}

```cs

// Załaduj źródłowy format Excela.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"src_excel_file.xls");

// Zapisz w wymaganym formacie wyjściowym.
wkb->Save(u"output_excel_format.xlsx", SaveFormat_Xlsx);


```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Konwertuj formaty Excela na PDF z ustawieniami poziomu zgodności" %}}
C++ Automatyzacja programu Excel API obsługuje konwersję skoroszytów do formatu PDF, a także obsługuje ustawianie poziomu zgodności i daty utworzenia. Programiści mogą używać [IPdfSaveOptions](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_pdf_save_options) wraz z [Aspose::Cells::Renderowanie](https://reference.aspose.com/cells/cpp/namespace/aspose.cells.rendering) aby ustawić zgodność z PDF. W przypadku konwersji API zapisz metodę z parametrem PdfSaveOptions i określoną ścieżką pliku wyjściowego. 
{{% blocks/products/pf/feature-page-code h3="C++ Przykładowy kod konwersji programu Excel do PDF" %}}

```cs
// Załaduj przykładowy plik Excel.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sample-convert-excel-to.pdf");

// Utwórz obiekt opcji zapisu pdf.
intrusive_ptr<Aspose::Cells::IPdfSaveOptions> pdfSaveOptions = Factory::CreateIPdfSaveOptions();

// Ustaw zgodność na PDF/A-1b.
pdfSaveOptions->SetCompliance(Aspose::Cells::Rendering::PdfCompliance_PdfA1b);

// lub PdfCompliance_PdfA1a 
// dla normalnego pliku PDF będzie to PdfCompliance_None

// Zapisz dokument Excel w formacie PDF
wkb->Save(u"output-converted-excel-workbook-to.pdf", pdfSaveOptions);



```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="PDF" >}}

{{% blocks/products/pf/feature-page-section h2="Zapisz Excel w obrazach" %}}
**C++ Parser Excel** umożliwia eksportowanie danych w postaci obrazów. Każdy arkusz roboczy można przekonwertować na różne formaty obrazu, w tym BMP, JPEG, PNG i GIF, ustawione przez [Renderowanie::IImageOrPrintOptions](https://reference.aspose.com/cells/cpp/class/aspose.cells.rendering.i_image_or_print_options). W przypadku dowolnego przypadku **Konwertuj Excel na obrazy** wybierz odpowiednią sprawę z łączy.
{{% blocks/products/pf/feature-page-code h3="C++ Kod programu Excel do konwersji obrazu" %}}

```cs
// Ścieżka katalogu wyjściowego.
StringPtr outDir = new String("ImagesOutputDirectoryPath");

// Załaduj XLSX.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"source-excel-file.xlsx");

// Uzyskaj dostęp do pierwszego arkusza.
intrusive_ptr<Aspose::Cells::IWorksheet> wks = wkb->GetIWorksheets()->GetObjectByIndex(0);

// Utwórz obiekt opcji obrazu lub wydruku.
intrusive_ptr<Aspose::Cells::Rendering::IImageOrPrintOptions> imgOptions = Factory::CreateIImageOrPrintOptions();

// Określ format obrazu. Poniższy kod dotyczy JPEG
imgOptions->SetImageFormat(Aspose::Cells::Systems::Drawing::Imaging::ImageFormat::GetJpeg());

// W przypadku innych obrazów, takich jak GIF, BMP i PNG, można użyć odpowiednio GetGif(), GetBmp() i GetPng() 

// Określ rozdzielczość poziomą i pionową
imgOptions->SetHorizontalResolution(200);
imgOptions->SetVerticalResolution(200);

// Renderuj arkusz z uwzględnieniem określonych opcji obrazu lub drukowania.
intrusive_ptr<Aspose::Cells::Rendering::ISheetRender> sr = Factory::CreateISheetRender(wks, imgOptions);

// Uzyskaj liczbę stron.
Aspose::Cells::Systems::Int32 pageCount = sr->GetPageCount();

// Utwórz obiekt konstruktora ciągów dla konkatenacji ciągów.
intrusive_ptr<Aspose::Cells::Systems::Text::StringBuilder> sb = new Aspose::Cells::Systems::Text::StringBuilder();

// Renderuj każdą stronę do obrazu jpeg jeden po drugim.
for (int i = 0; i < pageCount; i++){
	// Wyczyść konstruktora ciągów i utwórz ścieżkę obrazu wyjściowego z konkatenacjami ciągów.
	sb->Clear();
	sb->Append(outDir);
	sb->Append((StringPtr)new String("outputConvertingWorksheetToImageJPEG_"));
	sb->Append(i);
	sb->Append((StringPtr)new String(".jpeg"));
	// Pobierz ścieżkę obrazu wyjściowego.
	StringPtr outputJPEG = sb->ToString();
	// Konwertuj arkusz na obraz.
	sr->ToImage(i, outputJPEG);
}

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xls-to-png csv-to-jpeg tsv-to-png xlsb-to-png xlsx-to-png ods-to-png spreadsheetml-to-bmp tabdelimited-to-gif xlsm-to-bmp xlt-to-gif xltm-to-png xltx-to-gif" >}}