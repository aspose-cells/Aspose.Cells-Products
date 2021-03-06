---
title: Konwertuj TXT na BMP za pomocą aplikacji C++ 
url: /pl/cpp/conversion/txt-to-bmp/ 
description: Przykładowy kod konwersji C++ dla dokumentu TXT do formatu BMP. Programiści mogą używać tego kodu źródłowego do wsadowej konwersji TXT na BMP w dowolnej aplikacji C++.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Konwertuj TXT na BMP przez C++" h2="Wydajna konwersja TXT do BMP przy użyciu biblioteki C++ bez konieczności instalowania Microsoft Excel, OpenOffice lub Adobe Acrobat." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="BMP" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="TXT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Jak przekonwertować TXT na BMP za pomocą C++" %}}

 Aby przekonwertować TXT na BMP, użyjemy
 [Aspose.Cells dla C++](https://products.aspose.com/cells/cpp) 
 API, który jest bogatym w funkcje, wydajnym i łatwym w użyciu narzędziem do manipulacji i konwersji dokumentów API na platformę C++. Możesz pobrać jego najnowszą wersję bezpośrednio, po prostu otwórz
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 menedżer pakietów, szukaj
 Aspose.Cells.Cpp 
 i zainstaluj. Możesz również użyć następującego polecenia z konsoli Menedżera pakietów.

{{% blocks/products/pf/agp/code-block title="Komenda" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Kroki, aby przekonwertować TXT na BMP za pomocą C++" %}}

{{% blocks/products/pf/agp/text %}}

 C++ programiści mogą łatwo przekonwertować plik TXT na BMP w zaledwie kilku linijkach kodu.

{{% /blocks/products/pf/agp/text %}}

1. Załaduj plik TXT przy użyciu Factory::CreateIWorkbook.1. Wybierz pierwszy arkusz.1. Ustaw opcje (BMP).1. Iteruj przez każdą stronę arkusza i renderuj.1. Otwórz plik BMP w kompatybilnym programie.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="wymagania systemowe" %}}

{{% blocks/products/pf/agp/text %}}

 Przed uruchomieniem przykładowego kodu konwersji C++ upewnij się, że spełniasz następujące wymagania wstępne.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows lub zgodny system operacyjny z C++ Runtime Environment dla Windows 32-bitowy, Windows 64-bitowy i Linux 64-bitowy.- Aspose.Cells dla C++ DLL, do którego odwołuje się Twój projekt.
- Microsoft Windows lub zgodny system operacyjny z C++ Runtime Environment dla Windows 32-bitowy, Windows 64-bitowy i Linux 64-bitowy.- Aspose.Cells dla C++ DLL, do którego odwołuje się Twój projekt.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Kod źródłowy konwersji TXT do BMP C++" offSpacer="" %}}

```cs
// Ścieżka katalogu wyjściowego.
StringPtr outDir = new String("OutputDirectoryPath");

// Załaduj TXT.
intrusive_ptr<Aspose::Cells::IWorkbook> workbook = Factory::CreateIWorkbook(u"sourceFile.txt");

// Uzyskaj dostęp do pierwszego arkusza.
intrusive_ptr<Aspose::Cells::IWorksheet> worksheet = workbook->GetIWorksheets()->GetObjectByIndex(0);

// Utwórz obiekt opcji obrazu lub wydruku.
intrusive_ptr<Aspose::Cells::Rendering::IImageOrPrintOptions> imgOptions = Factory::CreateIImageOrPrintOptions();

// Określ format obrazu.
imgOptions->SetImageFormat(Aspose::Cells::Systems::Drawing::Imaging::ImageFormat::GetBmp());

// Określ rozdzielczość poziomą i pionową
imgOptions->SetHorizontalResolution(200);
imgOptions->SetVerticalResolution(200);

// Renderuj arkusz z uwzględnieniem określonych opcji obrazu lub drukowania.
intrusive_ptr<Aspose::Cells::Rendering::ISheetRender> sr = Factory::CreateISheetRender(worksheet, imgOptions);

// Uzyskaj liczbę stron.
Aspose::Cells::Systems::Int32 pageCount = sr->GetPageCount();

// Utwórz obiekt konstruktora ciągów dla konkatenacji ciągów.
intrusive_ptr<Aspose::Cells::Systems::Text::StringBuilder> sb = new Aspose::Cells::Systems::Text::StringBuilder();

// Renderuj każdą stronę do obrazu bmp jeden po drugim.
for (int i = 0; i Clear();
	sb->Append(outDir);
	sb->Append((StringPtr)new String("outputConvertingWorksheetToImageBMP_"));
	sb->Append(i);
	sb->Append((StringPtr)new String(".bmp"));

	// Pobierz ścieżkę obrazu wyjściowego.
	StringPtr outputBMP = sb->ToString();

	// Konwertuj arkusz na obraz bmp.
	sr->ToImage(i, outputBMP);
}


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Prezentacje na żywo z konwersją TXT do BMP" sectionDescription="[Konwertuj TXT na BMP](https://products.aspose.app/cells/conversion/txt-to-bmp) teraz, odwiedzając naszą stronę Live Demos. Demo na żywo ma następujące zalety" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Nie ma potrzeby pobierania Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Nie musisz pisać żadnego kodu." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Po prostu prześlij swój plik TXT, zostanie on natychmiast przekonwertowany do formatu BMP." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Otrzymasz link do pobrania." >}}

    {{% blocks/products/pf/agp/content h2="C++ Biblioteka manipulacji plikami Excel" %}}

 Excel API może być używany do tworzenia, edytowania, konwertowania i renderowania formatów Microsoft Excel do różnych formatów. Co więcej, może być używany do kompleksowych wykresów, skalowalnych raportów i niezawodnych obliczeń w aplikacjach. Aspose.Cells jest samodzielnym API i nie wymaga żadnego oprogramowania takiego jak Microsoft czy OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="TXT" readMoreLink="https://docs.fileformat.com/word-processing/txt/" >}}

Plik z rozszerzeniem .TXT reprezentuje dokument tekstowy, który zawiera zwykły tekst w postaci linii. Akapity w dokumencie tekstowym są rozpoznawane przez znaki powrotu karetki i służą do lepszego rozmieszczenia zawartości pliku. Standardowy dokument tekstowy można otworzyć w dowolnym edytorze tekstu lub aplikacji do przetwarzania tekstu w różnych systemach operacyjnych. Cały tekst zawarty w takim pliku jest w formacie czytelnym dla człowieka i reprezentowany przez ciąg znaków.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="BMP" readMoreLink="https://docs.fileformat.com/image/bmp/" >}}

Pliki o rozszerzeniu .BMP reprezentują pliki obrazów bitmapowych, które są używane do przechowywania cyfrowych obrazów bitmapowych. Obrazy te są niezależne od karty graficznej i są również nazywane formatem plików mapy bitowej niezależnej od urządzenia (DIB). Ta niezależność służy do otwierania pliku na wielu platformach, takich jak Microsoft Windows i Mac. Format pliku BMP może przechowywać dane jako dwuwymiarowe obrazy cyfrowe zarówno w formacie monochromatycznym, jak i kolorowym z różnymi głębiami kolorów.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}