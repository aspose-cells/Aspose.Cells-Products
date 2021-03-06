---
title: Wyświetl formaty plików MHT za pośrednictwem .NET 
url: /pl/net/viewer/mht/ 
description: C# kod źródłowy do ładowania, renderowania i wyświetlania dokumentów MHT na platformach .NET Framework, .NET Core, Windows Azure, Mono lub Xamarin.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Przeglądarka plików MHT for .NET" h2="Przeglądaj arkusze kalkulacyjne Excel i OpenOffice, takie jak MHT, bez konieczności korzystania z programu Microsoft Excel lub automatyzacji pakietu Office." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="DOC" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DOC" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Jak wyświetlić plik MHT za pomocą C#" %}}

Aby wyświetlić plik MHT, użyjemy <a href="https://products.aspose.com/cells/net">Aspose.Cells for .NET</a> API to bogata w funkcje, wydajna i łatwa w użyciu platforma API dla C#, której można używać z dowolną przeglądarką. otwarty <a href="https://www.nuget.org/packages/aspose.cells">NuGet</a> menedżer pakietów, szukaj <b>Aspose.Cells</b> i zainstaluj. Możesz również użyć następującego polecenia z konsoli Menedżera pakietów.

{{% blocks/products/pf/agp/code-block title="Polecenie konsoli menedżera pakietów" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Kroki, aby wyświetlić MHT przez C#" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells ułatwia programistom przeglądanie pliku MHT za pomocą zaledwie kilku linijek kodu.

{{% /blocks/products/pf/agp/text %}}

1. Załaduj plik MHT w instancji Workbook1. Utwórz instancję HtmlSaveOptions i ustaw właściwość ExportHeadings na true1. Zapisz plik MHT w formacie HTML za pomocą metody Workbook.Save1. Załaduj wynikowy kod HTML w domyślnej przeglądarce za pomocą Process.Start

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="wymagania systemowe" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for .NET jest obsługiwany we wszystkich głównych systemach operacyjnych. Tylko upewnij się, że masz następujące wymagania wstępne.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows lub zgodny system operacyjny z .NET Framework, .NET Core, Windows Azure, Mono lub Xamarin Platforms- Środowisko programistyczne, takie jak Microsoft Visual Studio- Aspose.Cells for .NET, o którym mowa w Twoim projekcie
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# przykładowy kod do wyświetlenia pliku MHT" offSpacer="" %}}

```cs


string output = System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".html";

// załaduj plik MHT w instancji Workbook
var book = new Aspose.Cells.Workbook("template.mht");
// utwórz instancję HtmlSaveOptions i ustaw właściwość ExportHeadings na true
var options = new Aspose.Cells.HtmlSaveOptions();
options.ExportHeadings = true;

// zapisz plik MHT w formacie HTML
book.Save(output, options);
// załaduj wynikowy kod HTML w domyślnej przeglądarce
System.Diagnostics.Process.Start(output);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="" %}}

Aspose.Cells API może służyć do tworzenia, edytowania, konwertowania i renderowania formatów programu Microsoft Excel do różnych formatów. Co więcej, może być używany do kompleksowych wykresów, skalowalnych raportów i niezawodnych obliczeń w aplikacjach. Aspose.Cells jest samodzielnym API i nie wymaga żadnego oprogramowania takiego jak Microsoft czy OpenOffice.    



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Darmowa aplikacja do przeglądania MHT" sectionDescription="Sprawdź nasze prezentacje na żywo, aby [Zobacz MHT](https://products.aspose.app/cells/viewer/mht) z następującymi korzyściami." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Nie musisz niczego pobierać ani konfigurować" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Nie ma potrzeby pisania ani kompilowania kodu" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Po prostu prześlij plik MHT i naciśnij przycisk „Wyświetl”" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" W razie potrzeby pobierz plik MHT z linku" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="MHT" readMoreLink="https://docs.fileformat.com/web/mht/" >}}
Plik z rozszerzeniem .mht to format pliku archiwizacji z obsługą MIME, który zawiera różne typy danych w jednym pliku. Może przechowywać dane, takie jak tekst, obrazy, style strony w postaci plików CSS, JavaScript i innych zasobów jako osadzone w nim zasoby. Pliki MHT, mające komunikat typu MIME/rfc822, hermetyzują całą zawartość pliku HTML jako pojedynczy plik archiwum do przechowywania podczas archiwizacji na urządzeniach pamięci masowej. Aplikacje programowe, takie jak Microsoft Word, umożliwiają konwersję dokumentów WORD do MHT poprzez eksportowanie ich do pliku MHT. Pliki MHT można otwierać za pomocą popularnych przeglądarek, takich jak Microsoft Internet Explorer i Google Chrome.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}