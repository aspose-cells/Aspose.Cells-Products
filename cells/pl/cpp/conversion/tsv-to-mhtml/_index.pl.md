---
title: Konwertuj TSV na MHTML za pomocą aplikacji C++ 
weight: 9310
url: /pl/cpp/conversion/tsv-to-mhtml/ 
description: Przykładowy kod konwersji C++ dla dokumentu TSV do formatu MHTML. Programiści mogą używać tego kodu źródłowego do wsadowej konwersji TSV na MHTML w dowolnej aplikacji C++.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Konwertuj TSV na MHTML przez C++" h2="Wysokowydajna konwersja TSV do MHTML przy użyciu biblioteki C++ bez konieczności instalacji Microsoft Excel, OpenOffice lub Adobe Acrobat." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="MHTML" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="TSV" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Jak przekonwertować TSV na MHTML za pomocą C++" %}}

 Aby przekonwertować TSV na MHTML, użyjemy
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

{{% blocks/products/pf/agp/feature-section-col title="Kroki, aby przekonwertować TSV na MHTML za pomocą C++" %}}

{{% blocks/products/pf/agp/text %}}

 C++ programiści mogą łatwo przekonwertować plik TSV na MHTML w zaledwie kilku wierszach kodu.

{{% /blocks/products/pf/agp/text %}}

1. Załaduj plik TSV przy użyciu Factory::CreateIWorkbook.1. Wywołaj metodę Save().1. Przekaż ścieżkę pliku wyjściowego z rozszerzeniem pliku (MHTML).1. Plik MHTML zostanie zapisany pod określoną ścieżką.1. Otwórz plik MHTML w kompatybilnym programie.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="wymagania systemowe" %}}

{{% blocks/products/pf/agp/text %}}

 Przed uruchomieniem przykładowego kodu konwersji C++ upewnij się, że spełniasz następujące wymagania wstępne.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows lub zgodny system operacyjny z C++ Runtime Environment dla Windows 32-bitowy, Windows 64-bitowy i Linux 64-bitowy.- Aspose.Cells dla C++ DLL, do którego odwołuje się Twój projekt.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Kod źródłowy konwersji TSV do MHTML C++" offSpacer="" %}}

```cs
// Załaduj TSV.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.tsv");

// Zapisz w formacie MHTML.
wkb->Save(u"convertedFile.mhtml", SaveFormat_Mhtml);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Prezentacje na żywo konwersji TSV do MHTML" sectionDescription="[Konwertuj TSV na MHTML](https://products.aspose.app/cells/conversion/tsv-to-mhtml) teraz, odwiedzając naszą stronę Live Demos. Demo na żywo ma następujące zalety" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Nie ma potrzeby pobierania Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Nie musisz pisać żadnego kodu." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Po prostu prześlij plik TSV, zostanie on natychmiast przekonwertowany do formatu MHTML." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Otrzymasz link do pobrania." >}}

    {{% blocks/products/pf/agp/content h2="C++ Biblioteka manipulacji plikami Excel" %}}

 Excel API może być używany do tworzenia, edytowania, konwertowania i renderowania formatów Microsoft Excel do różnych formatów. Co więcej, może być używany do kompleksowych wykresów, skalowalnych raportów i niezawodnych obliczeń w aplikacjach. Aspose.Cells jest samodzielnym API i nie wymaga żadnego oprogramowania takiego jak Microsoft czy OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="TSV" readMoreLink="https://docs.fileformat.com/spreadsheet/tsv/" >}}

Format pliku wartości rozdzielanych tabulatorami (TSV) reprezentuje dane oddzielone tabulatorami w formacie zwykłego tekstu. Format pliku, podobny do CSV, służy do organizowania danych w sposób ustrukturyzowany w celu importowania i eksportowania między różnymi aplikacjami. Format jest używany głównie do importu/eksportu i wymiany danych w aplikacjach arkuszy kalkulacyjnych i bazach danych. Każdy rekord w pliku TSV jest zawarty w pojedynczym wierszu pliku tekstowego, w którym każda wartość pola jest oddzielona znakiem tabulacji. Typ mediów dla formatu pliku TSV to tekst/wartości rozdzielane tabulatorami.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="MHTML" readMoreLink="https://docs.fileformat.com/web/mhtml/" >}}

Pliki z rozszerzeniem MHTML reprezentują format archiwum stron internetowych, który może być tworzony przez wiele różnych aplikacji. Format ten jest znany jako format archiwum, ponieważ zapisuje internetowy kod HTML i powiązane zasoby w jednym pliku. Zasoby te obejmują wszystko, co jest powiązane ze stroną internetową, takie jak obrazy, aplety, animacje, pliki audio i tak dalej. Pliki MHTML można otwierać w różnych aplikacjach, takich jak Internet Explorer i Microsoft Word. Microsoft Windows używa formatu pliku MHTML do rejestrowania scenariuszy problemów zaobserwowanych podczas korzystania z dowolnej aplikacji w systemie Windows, która powoduje problemy. Format pliku MHTML koduje zawartość strony podobną do specyfikacji zdefiniowanych w message/rfc822, czyli specyfikacjach związanych ze zwykłym tekstem wiadomości e-mail. Rzeczywiste specyfikacje formatu są zgodne z RFC 2557.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane konwersje" subTitle="Możesz także przekonwertować TSV na wiele innych formatów plików, w tym kilka wymienionych poniżej." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-bmp/" name="TSV DO BMP" description="Bitmapa" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-csv/" name="TSV DO CSV" description="Wartości oddzielone przecinkami" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-dif/" name="TSV DO DIF" description="Format wymiany danych" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-emf/" name="TSV DO EMF" description="Ulepszony format metapliku" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-gif/" name="TSV DO GIF" description="Graficzny format wymiany" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-html/" name="TSV DO HTML" description="hipertekstowy język znaczników" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-jpeg/" name="TSV DO JPEG" description="Obraz JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-ods/" name="TSV DO ODS" description="Plik arkusza kalkulacyjnego OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-pdf/" name="TSV DO PDF" description="format dokumentu przenośnego" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-png/" name="TSV DO PNG" description="Przenośna Grafika Sieciowa" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-svg/" name="TSV DO SVG" description="Skalowalna Grafika wektorowa" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-tiff/" name="TSV DO TIFF" description="Oznaczony format obrazu" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-xls/" name="TSV DO XLS" description="Format binarny programu Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-xlsb/" name="TSV DO XLSB" description="Binarny plik skoroszytu programu Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-xlsm/" name="TSV DO XLSM" description="Plik arkusza kalkulacyjnego" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-xlsx/" name="TSV DO XLSX" description="Plik OOXML Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-xltm/" name="TSV DO XLTM" description="Szablon programu Excel z obsługą makr" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-xltx/" name="TSV DO XLTX" description="Szablon Office OpenXML Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-xps/" name="TSV DO XPS" description="Specyfikacje papieru XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}