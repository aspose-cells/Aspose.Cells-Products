---
title:  Chroń i zablokuj dokument XLSM via .NET
weight: 7530
description: C# kod źródłowy do blokowania pliku XLSM przy użyciu hasła w platformie .NET, .NET Core, Mono lub platformach Xamarin.
keywords: [C# Aspose.Cells., c# Lock XLSM files., c# How to Protect and lock XLSM document., c# Protect XLSM files., Encrypt XLSM Files using C#]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Szyfruj pliki XLSM za pomocą C#" h2="Zabezpiecz hasłem arkusze kalkulacyjne Excel, w tym format XLSM, korzystając z biblioteki .NET." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSM" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Jak chronić plik XLSM za pomocą C#" %}}

 Aby chronić plik XLSM, użyjemy
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API, który jest bogatym w funkcje, wydajnym i łatwym w użyciu narzędziem do ochrony dokumentów API dla platformy C#. otwarty
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 menedżer pakietów, wyszukaj
 **Aspose.Cells** 
 i zainstaluj. Możesz także użyć następującego polecenia z konsoli Menedżera pakietów.

{{% blocks/products/pf/agp/code-block title="Aspose.Cells" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Chroń numer XLSM pod numerem C#" %}}

{{% blocks/products/pf/agp/text %}}

 Potrzebujesz
 [aspose.cells.dll](https://downloads.aspose.com/cells/net) 
 do którego odwołuje się Twój projekt, aby wykonać następujący przepływ pracy.

{{% /blocks/products/pf/agp/text %}}

1.  Utwórz instancję klasy skoroszytu ze ścieżką do pliku XLSM
1.  Pobierz domyślny lub dowolny arkusz, aby dodać ochronę
1.  Chroń arkusz za pomocą metody Worksheet.Protect
1.  Chroń skoroszyt za pomocą metody Workbook.Protect
1.  Zapisz wynik w formacie XLSM

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="wymagania systemowe" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for .NET jest obsługiwany we wszystkich głównych systemach operacyjnych. Upewnij się tylko, że spełniasz następujące wymagania wstępne.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows lub kompatybilny system operacyjny z .NET Framework, .NET Core, Mono lub platformami Xamarin
-  Środowisko programistyczne, takie jak Microsoft Visual Studio
-  Dodaj odniesienie do biblioteki DLL Aspose.Cells for .NET w swoim projekcie

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Komenda" offSpacer="" %}}

```cs

// load the XLSM Excel file 
var book = new Aspose.Cells.Workbook("unlocked.xlsm");

// access the first worksheet
var worksheet = book.Worksheets[0];

// protect the worksheet with password
worksheet.Protect(Aspose.Cells.ProtectionType.All, "password", null);

// protect the whole workbook with password
book.Protect(Aspose.Cells.ProtectionType.All, "password");

// save the modified file in default format
book.Save("protected.xlsm");

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="O Aspose.Cells for .NET API" %}}

 Aspose.Cells API można używać do tworzenia, edytowania, konwertowania i renderowania formatów Excel Microsoft do różnych formatów. Co więcej, można go używać do kompleksowych wykresów, skalowalnych raportów i niezawodnych obliczeń w aplikacjach. Numer Aspose.Cells jest samodzielnym numerem API i nie wymaga żadnego oprogramowania takiego jak Microsoft czy OpenOffice.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Bezpłatna aplikacja do ochrony XLSM" sectionDescription=" Sprawdź nasze demonstracje na żywo[zaszyfruj pliki XLSM](https://products.aspose.app/cells/protect/xlsm) z następującymi korzyściami." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Nie trzeba niczego pobierać ani konfigurować" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Nie ma potrzeby pisania ani kompilowania kodu" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Po prostu prześlij plik XLSM i naciśnij przycisk „Odblokuj”." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Pobierz wynikowy plik XLSM z łącza" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSM" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsm/" >}}
Pliki z rozszerzeniem XLSM to rodzaj plików arkuszy kalkulacyjnych obsługujących makra. Z aplikacyjnego punktu widzenia Makro to zestaw instrukcji służących do automatyzacji procesów. Makro służy do rejestrowania powtarzających się kroków i ułatwia wykonanie czynności poprzez ponowne uruchomienie makra. Makra są programowane w języku Visual Basic for Applications (VBA) Microsoft z poziomu skoroszytu programu Excel za pomocą edytora Visual Basic i można je bezpośrednio z niego uruchamiać/debugować.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane formaty ochrony" subTitle="Używając numeru C#, można łatwo chronić inne formaty, w tym." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/ods/" name="ODS" description="Plik arkusza kalkulacyjnego OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/xls/" name="XLS" description="Format binarny Excela" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/xlsb/" name="XLSB" description="Binarny plik skoroszytu programu Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/xlsx/" name="XLSX" description="Plik Excela OOXML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
