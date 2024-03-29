---
title:  Chroń i zablokuj dokument XLS pod numerem C++
weight: 8760
description: C++ przykładowy kod blokujący plik XLS przy użyciu hasła w C++ Środowisko wykonawcze dla Windows 32-bitowego, Windows 64-bitowego i 64-bitowego systemu Linux.
keywords: [C++ Aspose.Cells., C++ Lock XLS files., C++ How to Protect and lock XLS document., C++ Protect XLS files., Encrypt XLS Files using C++]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Szyfruj pliki XLS za pomocą C++" h2="Zabezpiecz hasłem arkusze kalkulacyjne Excel, w tym format XLS, korzystając z biblioteki .NET." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLS" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp/" installationsDocsLink="https://docs.aspose.com/cells/cpp/" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Jak zabezpieczyć plik XLS za pomocą C++" %}}

 Aby chronić plik XLS, użyjemy
 [Aspose.Cells for C++](https://products.aspose.com/cells/cpp) 
 API, która jest bogatą w funkcje, wydajną i łatwą w użyciu platformą do szyfrowania dokumentów API for C++. Możesz pobrać jego najnowszą wersję bezpośrednio, po prostu otwórz
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 menedżer pakietów, wyszukaj
 **Aspose.Cells.Cpp** 
 i zainstaluj. Możesz także użyć następującego polecenia z konsoli Menedżera pakietów.

{{% blocks/products/pf/agp/code-block title="Aspose.Cells" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Kroki, aby chronić pliki XLS za pośrednictwem C++" %}}

{{% blocks/products/pf/agp/text %}}

 Ochronę dokumentów za pomocą interfejsów API Aspose.Cells można wykonać za pomocą zaledwie kilku linijek kodu.

{{% /blocks/products/pf/agp/text %}}

1.  Załaduj plik XLS przy użyciu klasy Workbook
1.  Użyj metody Protect(..) z Typem ochrony i Hasłem
1.  Zapisz chroniony plik XLS metodą Save().

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="wymagania systemowe" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for C++ obsługuje wszystkie główne platformy i systemy operacyjne. Upewnij się, że spełniasz następujące wymagania wstępne.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows lub zgodny system operacyjny z C++ Runtime Environment dla Windows 32-bitowy, Windows 64-bitowy i Linux 64-bitowy.
-  Dodaj odwołanie do biblioteki DLL Aspose.Cells for C++ w swoim projekcie.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Komenda" offSpacer="" %}}

```cs

Aspose::Cells::Startup();

// load the ODS Excel file 
Workbook book(u"unlocked.xls");

// access the first worksheet
Worksheet worksheet = book.GetWorksheets().Get(0);

// protect the worksheet with password
worksheet.Protect(ProtectionType::All, u"password", nullptr);

// protect the whole workbook with password
book.Protect(ProtectionType::All, u"password");

// save the modified file in default format
book.Save(u"protected.xls");

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

    {{< blocks/products/pf/agp/demobox sectionTitle="Bezpłatna aplikacja do ochrony XLS" sectionDescription=" Sprawdź nasze demonstracje na żywo[zaszyfruj pliki XLS](https://products.aspose.app/cells/protect/xls) z następującymi korzyściami." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Nie trzeba niczego pobierać ani konfigurować" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Nie ma potrzeby pisania ani kompilowania kodu" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Po prostu prześlij plik XLS i naciśnij przycisk „Odblokuj”." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Pobierz wynikowy plik XLS z łącza" >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}
Pliki z rozszerzeniem XLS reprezentują format pliku binarnego programu Excel. Takie pliki można utworzyć za pomocą Microsoft Excel, a także innych podobnych programów do obsługi arkuszy kalkulacyjnych, takich jak OpenOffice Calc lub Apple Numbers. Plik zapisany w programie Excel jest znany jako skoroszyt, gdzie każdy skoroszyt może zawierać jeden lub więcej arkuszy. Dane są przechowywane i wyświetlane użytkownikom w formie tabeli w arkuszu i mogą obejmować wartości liczbowe, dane tekstowe, formuły, zewnętrzne połączenia danych, obrazy i wykresy. Aplikacje takie jak Microsoft Excel umożliwiają eksportowanie danych skoroszytu do kilku różnych formatów, w tym PDF, CSV, XLSX, TXT, HTML, XPS i kilku innych. Format pliku XLS został zastąpiony bardziej otwartym i ustrukturyzowanym formatem XLSX wraz z wydaniem Microsoft Excel 2007. Najnowsze wersje nadal zapewniają obsługę tworzenia i odczytywania plików XLS, chociaż XLSX jest obecnie pierwszym wyborem.

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane dokumenty zabezpieczające" subTitle="Używając numeru C++, można chronić inne pliki, w tym." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/protect/ods/" name="ODS" description="Plik arkusza kalkulacyjnego OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/protect/xlsb/" name="XLSB" description="Binarny plik skoroszytu programu Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/protect/xlsm/" name="XLSM" description="Plik arkusza kalkulacyjnego" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/protect/xlsx/" name="XLSX" description="Plik Excela OOXML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
