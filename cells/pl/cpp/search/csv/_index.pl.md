---
title:  Wyszukaj dokument CSV bez otwierania poprzez C++
weight: 5540
description: C++ przykładowy kod do wyszukiwania słów według wzorca w pliku CSV w C++ Środowisko wykonawcze dla Windows 32-bitowy, Windows 64-bitowy i Linux 64-bitowy.
keywords: [C++ Aspose.Cells., C++ search words with pattern in csv file., C++ find words with pattern in csv file., C++ search string with pattern in csv file., C++ find words with pattern in csv file., C++ search words in csv file., C++ find words in csv file., C++ search string in csv file., C++ find string in csv file]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Wyszukaj formaty CSV w C++" h2="Natywne i wydajne wyszukiwanie dokumentów CSV przy użyciu interfejsów API Aspose.Cells for C++ po stronie serwera, bez użycia oprogramowania takiego jak Microsoft lub Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="CSV" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Jak wyszukać plik CSV za pomocą C++" %}}

 Aby przeszukać plik CSV użyjemy
 [Aspose.Cells for C++](https://products.aspose.com/cells/cpp) 
API, która jest bogatą w funkcje, wydajną i łatwą w użyciu platformą do wyszukiwania dokumentów API for C++. Możesz pobrać jego najnowszą wersję bezpośrednio, po prostu otwórz
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 menedżer pakietów, wyszukaj
 **Aspose.Cells.Cpp** 
 i zainstaluj. Możesz także użyć następującego polecenia z konsoli Menedżera pakietów.

{{% blocks/products/pf/agp/code-block title="Komenda" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Kroki wyszukiwania plików CSV w C++" %}}

{{% blocks/products/pf/agp/text %}}

 Podstawowe wyszukiwanie dokumentów przy użyciu interfejsów API Aspose.Cells można wykonać za pomocą zaledwie kilku linijek kodu.

{{% /blocks/products/pf/agp/text %}}

+ Załaduj plik CSV, tworząc instancję klasy Workbook.
+ Utwórz instancję klasy ZamieńOpcje.
+ Ustaw wymagany wzorzec, taki jak SetCaseSensitive (wartość bool), SetMatchEntireCellContents (wartość bool).
Użyj metody Workbook::Replace(...) z odpowiednimi opcjami.
+ Zapisz plik CSV przy użyciu metody Workbook::Save(...).

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="wymagania systemowe" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for C++ obsługuje wszystkie główne platformy i systemy operacyjne. Upewnij się, że spełniasz następujące wymagania wstępne.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows lub zgodny system operacyjny z C++ Runtime Environment dla Windows 32-bitowy, Windows 64-bitowy i Linux 64-bitowy.
-  Dodaj odwołanie do biblioteki DLL Aspose.Cells for C++ w swoim projekcie.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Wyszukaj pliki CSV - C++" offSpacer="" %}}

```cs

Aspose::Cells::Startup();

// Source directory path.
U16String srcDir(u"SourcePath\\");

// Output directory path.
U16String outDir(u"OutputPath\\");

// Load CSV file
Workbook  wkb(srcDir + u"sourceFile.csv");

// Create an instance of the IReplaceOptions class
ReplaceOptions replaceOptions;

// Set case sensitivity option
replaceOptions.SetCaseSensitive(false);

// Set text matching option
replaceOptions.SetMatchEntireCellContents(false);

// Replace text
wkb.Replace(u"Text to find", u"Text replacement", replaceOptions);

// Save as CSV file
wkb.Save(outDir + u"outputFile.csv");

Aspose::Cells::Cleanup();

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="O Aspose.Cells for C++ API" %}}

 Aspose.Cells API można używać do tworzenia, edytowania, konwertowania i renderowania formatów Excel Microsoft do różnych formatów. Co więcej, można go używać do kompleksowych wykresów, skalowalnych raportów i niezawodnych obliczeń w aplikacjach. Numer Aspose.Cells jest samodzielnym numerem API i nie wymaga żadnego oprogramowania takiego jak Microsoft czy OpenOffice.



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="Online CSV Szukaj demonstracji na żywo" sectionDescription=" Wyszukaj teraz tekst, słowa i frazy w dokumentach CSV, odwiedzając naszą stronę[Witryna internetowa z prezentacjami na żywo](https://products.aspose.app/cells/search). Demo na żywo ma następujące zalety" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Nie ma potrzeby pobierania Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Nie trzeba pisać żadnego kodu." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Po prostu prześlij swoje pliki CSV." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Wynik wyszukiwania pojawia się natychmiast." >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="CSV " readMoreLink="https://docs.fileformat.com/spreadsheet/csv/" >}}
Pliki z rozszerzeniem CSV (wartości oddzielone przecinkami) reprezentują zwykłe pliki tekstowe zawierające rekordy danych z wartościami oddzielonymi przecinkami. Każda linia w pliku CSV jest nowym rekordem ze zbioru rekordów zawartych w pliku. Takie pliki są generowane, gdy planowany jest transfer danych z jednego systemu przechowywania do drugiego. Ponieważ wszystkie aplikacje rozpoznają rekordy oddzielone przecinkiem, import takich plików z danymi do bazy danych odbywa się bardzo wygodnie. Prawie wszystkie aplikacje arkuszy kalkulacyjnych, takie jak Microsoft Excel lub OpenOffice Calc, mogą importować CSV bez większego wysiłku. Dane importowane z takich plików są układane w komórkach arkusza kalkulacyjnego w celu przedstawienia ich użytkownikowi.

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane dokumenty wyszukiwania" subTitle="Za pomocą numeru C++ można także wyszukiwać inne pliki, m.in." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/ods/" name="ODS" description="Plik arkusza kalkulacyjnego OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/tsv/" name="TSV" description="Wartości rozdzielone tabulatorami" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/txt/" name="TXT" description="Dokument tekstowy" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/xls/" name="XLS" description="Format binarny Excela" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/xlsb/" name="XLSB" description="Binarny plik skoroszytu programu Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/xlsm/" name="XLSM" description="Plik arkusza kalkulacyjnego" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
