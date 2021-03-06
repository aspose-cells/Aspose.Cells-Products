---
title: Chroń i blokuj dokument ODS za pomocą C++ 
weight: 10010
url: /pl/cpp/protect/ods/ 
description: C++ przykładowy kod do blokowania pliku ODS przy użyciu hasła w C++ środowisku wykonawczym dla 32-bitowego systemu Windows, 64-bitowego systemu Windows i 64-bitowego systemu Linux.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Szyfruj pliki ODS przez C++" h2="Chronione hasłem arkusze kalkulacyjne Excel, w tym format ODS, przy użyciu .NETBiblioteki." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODS" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="ODS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp/" installationsDocsLink="https://docs.aspose.com/cells/cpp/" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Jak zabezpieczyć plik ODS za pomocą C++" %}}

 Aby chronić plik ODS, użyjemy
 [Aspose.Cells dla C++](https://products.aspose.com/cells/cpp) 
 API, który jest bogatym w funkcje, wydajnym i łatwym w użyciu szyfrowaniem dokumentów API dla platformy C++. Możesz pobrać jego najnowszą wersję bezpośrednio, po prostu otwórz
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 menedżer pakietów, szukaj
 **Aspose.Cells.Cpp** 
 i zainstaluj. Możesz również użyć następującego polecenia z konsoli Menedżera pakietów.

{{% blocks/products/pf/agp/code-block title="Aspose.Cells" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Kroki ochrony plików ODS za pośrednictwem C++" %}}

{{% blocks/products/pf/agp/text %}}

 Ochrona dokumentów za pomocą interfejsów API Aspose.Cells można wykonać za pomocą zaledwie kilku linijek kodu.

{{% /blocks/products/pf/agp/text %}}

1. Załaduj plik ODS za pomocą klasy IWorkbook1. Użyj metody Protect(..) z ProtectionType i Password1. Zapisz chroniony plik ODS za pomocą metody Save()
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="wymagania systemowe" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for C++ obsługuje wszystkie główne platformy i systemy operacyjne. Upewnij się, że masz następujące wymagania wstępne.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows lub zgodny system operacyjny z C++ Runtime Environment dla Windows 32-bitowy, Windows 64-bitowy i Linux 64-bitowy.- Aspose.Cells dla C++ DLL, do którego odwołuje się Twój projekt.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Komenda" offSpacer="" %}}

```cs

// Ścieżka źródłowa.
StringPtr srcDir = new String("SourcePath\");

// Ścieżka wyjściowa.
StringPtr outDir = new String("OutputPath\");

// Załaduj plik ODS
intrusive_ptr<IWorkbook> workbook = Factory::CreateIWorkbook(srcDir->StringAppend(new String("sourceFile.ods")));

// Chroń skoroszyt, określając typ ochrony
workbook->Protect(ProtectionType::ProtectionType_All, new String("12345"));

// Zapisz plik ODS
workbook->Save(outDir->StringAppend(new String("output.ods")));


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="O Aspose.Cells dla C++ API" %}}

 Aspose.Cells API może służyć do tworzenia, edytowania, konwertowania i renderowania formatów programu Microsoft Excel do różnych formatów. Co więcej, może być używany do kompleksowych wykresów, skalowalnych raportów i niezawodnych obliczeń w aplikacjach. Aspose.Cells jest samodzielnym API i nie wymaga żadnego oprogramowania takiego jak Microsoft czy OpenOffice.  



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="Darmowa aplikacja do ochrony ODS" sectionDescription="Sprawdź nasze prezentacje na żywo, aby [szyfruj pliki ODS](https://products.aspose.app/cells/protect/ods) z następującymi korzyściami." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Nie musisz niczego pobierać ani konfigurować" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Nie ma potrzeby pisania ani kompilowania kodu" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Po prostu prześlij plik ODS i naciśnij przycisk „Odblokuj”" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Pobierz wynikowy plik ODS z linku" >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODS" readMoreLink="https://docs.fileformat.com/spreadsheet/ods/" >}}
Pliki z rozszerzeniem ODS oznaczają format dokumentu OpenDocument Spreadsheet, który może być edytowany przez użytkownika. Dane są przechowywane w pliku ODF w wierszach i kolumnach. Jest to format oparty na XML i jest jednym z kilku podtypów w rodzinie Open Document Formats (ODF). Format jest określony jako część specyfikacji ODF 1.2 opublikowanych i utrzymywanych przez OASIS. Wiele aplikacji w systemie Windows, a także innych systemach operacyjnych, może otwierać pliki ODS w celu edycji i manipulacji, w tym Microsoft Excel, NeoOffice i LibreOffice. Pliki ODS można również konwertować na inne formaty arkuszy kalkulacyjnych, takie jak XLS, XLSX i inne, za pomocą różnych aplikacji.

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane dokumenty dotyczące ochrony" subTitle="Używając C++, można chronić inne pliki, w tym." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/protect/xls/" name="XLS" description="Format binarny programu Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/protect/xlsb/" name="XLSB" description="Binarny plik skoroszytu programu Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/protect/xlsm/" name="XLSM" description="Plik arkusza kalkulacyjnego" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/protect/xlsx/" name="XLSX" description="Plik OOXML Excel" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}