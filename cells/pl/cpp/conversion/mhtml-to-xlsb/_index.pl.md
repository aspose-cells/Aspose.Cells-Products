---
title: Konwertuj MHTML na XLSB za pomocą aplikacji C++ 
weight: 7450
url: /pl/cpp/conversion/mhtml-to-xlsb/ 
description: Przykładowy kod konwersji C++ dla dokumentu MHTML do formatu XLSB. Programiści mogą używać tego kodu źródłowego do wsadowej konwersji MHTML na XLSB w dowolnej aplikacji C++.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Konwertuj MHTML na XLSB przez C++" h2="Wysokowydajna konwersja MHTML do XLSB przy użyciu biblioteki C++ bez konieczności instalacji Microsoft Excel, OpenOffice lub Adobe Acrobat." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSB" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="MHTML" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Jak przekonwertować MHTML na XLSB za pomocą C++" %}}

 Aby przekonwertować MHTML na XLSB, użyjemy
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

{{% blocks/products/pf/agp/feature-section-col title="Kroki, aby przekonwertować MHTML na XLSB za pomocą C++" %}}

{{% blocks/products/pf/agp/text %}}

 C++ programiści mogą łatwo przekonwertować plik MHTML na XLSB w zaledwie kilku wierszach kodu.

{{% /blocks/products/pf/agp/text %}}

1. Załaduj plik MHTML przy użyciu Factory::CreateIWorkbook.1. Wywołaj metodę Save().1. Przekaż ścieżkę pliku wyjściowego z rozszerzeniem pliku (XLSB).1. Plik XLSB zostanie zapisany pod określoną ścieżką.1. Otwórz plik XLSB w kompatybilnym programie.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="wymagania systemowe" %}}

{{% blocks/products/pf/agp/text %}}

 Przed uruchomieniem przykładowego kodu konwersji C++ upewnij się, że spełniasz następujące wymagania wstępne.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows lub zgodny system operacyjny z C++ Runtime Environment dla Windows 32-bitowy, Windows 64-bitowy i Linux 64-bitowy.- Aspose.Cells dla C++ DLL, do którego odwołuje się Twój projekt.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Kod źródłowy konwersji MHTML do XLSB C++" offSpacer="" %}}

```cs
// Załaduj MHTML.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.mhtml");

// Zapisz w formacie XLSB.
wkb->Save(u"convertedFile.xlsb", SaveFormat_Xlsb);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Prezentacje na żywo z konwersją MHTML na XLSB" sectionDescription="[Konwertuj MHTML na XLSB](https://products.aspose.app/cells/conversion/mhtml-to-xlsb) teraz, odwiedzając naszą stronę Live Demos. Demo na żywo ma następujące zalety" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Nie ma potrzeby pobierania Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Nie musisz pisać żadnego kodu." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Po prostu prześlij swój plik MHTML, zostanie on natychmiast przekonwertowany na XLSB." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Otrzymasz link do pobrania." >}}

    {{% blocks/products/pf/agp/content h2="C++ Biblioteka manipulacji plikami Excel" %}}

 Excel API może być używany do tworzenia, edytowania, konwertowania i renderowania formatów Microsoft Excel do różnych formatów. Co więcej, może być używany do kompleksowych wykresów, skalowalnych raportów i niezawodnych obliczeń w aplikacjach. Aspose.Cells jest samodzielnym API i nie wymaga żadnego oprogramowania takiego jak Microsoft czy OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="MHTML" readMoreLink="https://docs.fileformat.com/web/mhtml/" >}}

Pliki z rozszerzeniem MHTML reprezentują format archiwum stron internetowych, który może być tworzony przez wiele różnych aplikacji. Format ten jest znany jako format archiwum, ponieważ zapisuje internetowy kod HTML i powiązane zasoby w jednym pliku. Zasoby te obejmują wszystko, co jest powiązane ze stroną internetową, takie jak obrazy, aplety, animacje, pliki audio i tak dalej. Pliki MHTML można otwierać w różnych aplikacjach, takich jak Internet Explorer i Microsoft Word. Microsoft Windows używa formatu pliku MHTML do rejestrowania scenariuszy problemów zaobserwowanych podczas korzystania z dowolnej aplikacji w systemie Windows, która powoduje problemy. Format pliku MHTML koduje zawartość strony podobną do specyfikacji zdefiniowanych w message/rfc822, czyli specyfikacjach związanych ze zwykłym tekstem wiadomości e-mail. Rzeczywiste specyfikacje formatu są zgodne z RFC 2557.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSB" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsb/" >}}

Format pliku XLSB określa format pliku binarnego programu Excel, który jest zbiorem rekordów i struktur określających zawartość skoroszytu programu Excel. Treść może obejmować nieustrukturyzowane lub częściowo ustrukturyzowane tabele liczb, tekst lub zarówno liczby, jak i tekst, formuły, połączenia danych zewnętrznych, wykresy i obrazy. W przeciwieństwie do XLSX (który jest oparty na formacie pliku Open XML), XLSB reprezentuje binarny plik skoroszytu programu Excel. Pliki XLSB można szybciej odczytywać i zapisywać, co czyni je przydatnymi do pracy z dużymi plikami. XLSB jest rzadko używany do przechowywania skoroszytów, ponieważ XLSX (i wcześniej XLS) to najczęściej wybierane przez użytkowników formaty plików do zapisywania skoroszytów. Można go otworzyć w Microsoft Office 2007 i nowszych.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane konwersje" subTitle="Możesz także przekonwertować MHTML na wiele innych formatów plików, w tym kilka wymienionych poniżej." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-bmp/" name="MHTML DO BMP" description="Bitmapa" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-csv/" name="MHTML DO CSV" description="Wartości oddzielone przecinkami" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-dif/" name="MHTML DO RÓŻNICY" description="Format wymiany danych" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-emf/" name="MHTML DO EMF" description="Ulepszony format metapliku" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-gif/" name="MHTML DO GIF" description="Graficzny format wymiany" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-html/" name="MHTML DO HTML" description="hipertekstowy język znaczników" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-jpeg/" name="MHTML DO JPEG" description="Obraz JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-ods/" name="MHTML DO SZWO" description="Plik arkusza kalkulacyjnego OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-pdf/" name="MHTML DO PDF" description="format dokumentu przenośnego" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-png/" name="MHTML DO PNG" description="Przenośna Grafika Sieciowa" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-svg/" name="MHTML DO SVG" description="Skalowalna Grafika wektorowa" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-tiff/" name="MHTML DO TIFF" description="Oznaczony format obrazu" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-tsv/" name="MHTML DO TSV" description="Wartości rozdzielane tabulatorami" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-xls/" name="MHTML DO XLS" description="Format binarny programu Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-xlsm/" name="MHTML DO XLSM" description="Plik arkusza kalkulacyjnego" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-xlsx/" name="MHTML DO XLSX" description="Plik OOXML Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-xltm/" name="MHTML DO XLTM" description="Szablon programu Excel z obsługą makr" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-xltx/" name="MHTML DO XLTX" description="Szablon Office OpenXML Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-xps/" name="MHTML DO XPS" description="Specyfikacje papieru XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}