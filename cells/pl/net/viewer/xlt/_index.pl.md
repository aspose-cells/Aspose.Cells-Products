---
title:  Zobacz XLT Formaty plików via .NET
weight: 3610
description: Kod źródłowy C# do ładowania, renderowania i wyświetlania dokumentów XLT na platformach .NET Framework, .NET Core, Mono lub platformach Xamarin.
keywords: [C# Aspose.Cells., c# view XLT files., c# how to render XLT document., c# load and display XLT files., XLT File Viewer using C#]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="XLT Przeglądarka plików for .NET" h2="Przeglądaj arkusze kalkulacyjne Excel i OpenOffice, takie jak XLT, bez konieczności używania Microsoft Excel lub Office Automation." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLT" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Jak wyświetlić plik XLT przy użyciu C#" %}}

 Aby wyświetlić plik XLT, użyjemy
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API, który jest bogatą w funkcje, wydajną i łatwą w użyciu platformą API dla C#, której można używać z dowolną przeglądarką. otwarty
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 menedżer pakietów, wyszukaj
 **Aspose.Cells** 
 i zainstaluj. Możesz także użyć następującego polecenia z konsoli Menedżera pakietów.

{{% blocks/products/pf/agp/code-block title="Polecenie konsoli Menedżera pakietów" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Kroki, aby wyświetlić XLT przez C#" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells ułatwia programistom przeglądanie pliku XLT za pomocą zaledwie kilku linii kodu.

{{% /blocks/products/pf/agp/text %}}

1.  Załaduj plik XLT do instancji skoroszytu
1.  Utwórz instancję HtmlSaveOptions i ustaw właściwość ExportHeadings na true
1. Zapisz plik XLT w formacie HTML przy użyciu metody Workbook.Save
1.  Załaduj wynikowy HTML do domyślnej przeglądarki za pomocą Process.Start

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="wymagania systemowe" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for .NET jest obsługiwany we wszystkich głównych systemach operacyjnych. Upewnij się tylko, że spełniasz następujące wymagania wstępne.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows lub kompatybilny system operacyjny z .NET Framework, .NET Core, Mono lub platformami Xamarin
-  Środowisko programistyczne, takie jak Microsoft Visual Studio
-  Dodaj odniesienie do biblioteki DLL Aspose.Cells for .NET w swoim projekcie

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# przykładowy kod do wyświetlenia pliku XLT" offSpacer="" %}}

```cs

string output = System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".html";

// load the XLT file in an instance of Workbook
var book = new Aspose.Cells.Workbook("template.xlt");
// create an instance of HtmlSaveOptions & set ExportHeadings property to true
var options = new Aspose.Cells.HtmlSaveOptions();
options.ExportHeadings = true;

// save the XLT file in HTML format
book.Save(output, options);
// load resultant HTML in default browser
System.Diagnostics.Process.Start(output);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="O Aspose.Cells for .NET API" %}}

 Aspose.Cells API można używać do tworzenia, edytowania, konwertowania i renderowania formatów Excel Microsoft do różnych formatów. Co więcej, można go używać do kompleksowych wykresów, skalowalnych raportów i niezawodnych obliczeń w aplikacjach. Numer Aspose.Cells jest samodzielnym numerem API i nie wymaga żadnego oprogramowania takiego jak Microsoft czy OpenOffice.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Bezpłatna aplikacja do przeglądania XLT" sectionDescription=" Sprawdź nasze demonstracje na żywo[Zobacz XLT](https://products.aspose.app/cells/viewer/xlt) z następującymi korzyściami." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Nie trzeba niczego pobierać ani konfigurować" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Nie ma potrzeby pisania ani kompilowania kodu" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Po prostu prześlij plik XLT i naciśnij przycisk „Wyświetl”." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" W razie potrzeby pobierz plik XLT z łącza" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLT" readMoreLink="https://docs.fileformat.com/spreadsheet/xlt/" >}}
Pliki z rozszerzeniem .XLT to pliki szablonów utworzone za pomocą programu Microsoft Excel, który jest aplikacją arkusza kalkulacyjnego wchodzącą w skład pakietu Office Microsoft. Microsoft Pakiet Office 97-2003 obsługiwał tworzenie nowych plików XLT oraz ich otwieranie. Najnowsza wersja programu Excel nadal umożliwia otwieranie plików szablonów w starym formacie. Taki plik szablonu służy do szybkiego tworzenia nowych plików Excel z domyślnymi danymi i ustawieniami, takimi jak formatowanie strony, rozmiar czcionki, marginesy, wykresy itp., które można później zapisać jako nowe pliki .XLS.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane formaty przeglądarek" subTitle="Korzystając z numeru C#, można także przeglądać wiele innych formatów plików, w tym." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/csv/" name="CSV" description="Wartości oddzielone przecinkami" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/ods/" name="ODS" description="Plik arkusza kalkulacyjnego OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/tsv/" name="TSV" description="Wartości rozdzielone tabulatorami" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/txt/" name="TXT" description="Dokument tekstowy" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xls/" name="XLS" description="Format binarny Excela" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xlsb/" name="XLSB" description="Binarny plik skoroszytu programu Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xlsm/" name="XLSM" description="Plik arkusza kalkulacyjnego" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xlsx/" name="XLSX" description="Plik Excela OOXML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xltm/" name="XLTM" description="Szablon programu Excel z obsługą makr" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xltx/" name="XLTX" description="Szablon programu Excel pakietu Office OpenXML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
