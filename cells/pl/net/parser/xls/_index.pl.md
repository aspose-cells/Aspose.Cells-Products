---
title: Wyodrębnij tekst i obrazy z dokumentu XLS za pomocą .NET 
weight: 5600
url: /pl/net/parser/xls/ 
description: C# kod źródłowy do wyodrębniania tekstu i obrazów z pliku XLS na platformach .NET Framework, .NET Core, Mono lub Xamarin.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Analizuj formaty XLS w C#" h2="Natywne i wysoce wydajne analizowanie dokumentów XLS przy użyciu interfejsów API Aspose.Cellsfor .NET po stronie serwera, bez użycia oprogramowania, takiego jak Microsoft lub Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Jak przeanalizować plik XLS za pomocą C#" %}}

 Aby przeanalizować plik XLS, użyjemy
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API to bogata w funkcje, wydajna i łatwa w użyciu platforma do manipulacji dokumentami API na C#. otwarty
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 menedżer pakietów, szukaj
 ***** 
 i zainstaluj. Możesz również użyć następującego polecenia z konsoli Menedżera pakietów.

{{% blocks/products/pf/agp/code-block title="Komenda" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Kroki, aby przeanalizować pliki XLS w C#" %}}

{{% blocks/products/pf/agp/text %}}

 Podstawowe parsowanie dokumentów za pomocą
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API można wykonać za pomocą kilku linijek kodu. Analizuj tekst i obrazy z plików Microsoft Excel XLS, XLSX, XLSM, XLSB i OpenDocument ODS.

{{% /blocks/products/pf/agp/text %}}

Załaduj dokument XLS.
+ Wybierz arkusz.
+ Pobierz obraz i typ obrazu.
+ Zapisz obraz.
+ Zapisz dokument

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="wymagania systemowe" %}}

{{% blocks/products/pf/agp/text %}}

 Nasze interfejsy API są obsługiwane na wszystkich głównych platformach i systemach operacyjnych. Przed wykonaniem poniższego kodu upewnij się, że masz w systemie następujące wymagania wstępne.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows lub zgodny system operacyjny z .NET Framework, .NET Core, Mono lub Xamarin Platforms- Środowisko programistyczne, takie jak Microsoft Visual Studio- Aspose.Cells for .NET Biblioteka DLL, do której odwołuje się Twój projekt — zainstaluj z NuGet za pomocą przycisku Pobierz powyżej
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Analizuj pliki XLS — C#" offSpacer="" %}}

```cs
    // wyodrębnij obrazy z arkuszy roboczych 
    // otwórz szablon pliku Excel
    Workbook workbook = new Workbook("sampleExtractImagesFromWorksheets.xls");
    
    // zdobądź pierwszy arkusz roboczy
    Worksheet worksheet = workbook.Worksheets[0];
    
    // zdobądź pierwsze zdjęcie w pierwszym arkuszu
    Aspose.Cells.Drawing.Picture pic = worksheet.Pictures[0];
    
    // ustaw ścieżkę pliku obrazu wyjściowego
    string picformat = pic.ImageType.ToString();
                
    // Uwaga: możesz ocenić format obrazu przed określeniem ścieżki obrazu
    // zdefiniuj opcje obrazu lub wydruku
    Aspose.Cells.Rendering.ImageOrPrintOptions printoption = new  Aspose.Cells.Rendering.ImageOrPrintOptions();
    
    // określ format obrazu
    printoption.ImageType =  Aspose.Cells.Drawing.ImageType.Jpeg;
                
    // zapisz obraz
    pic.ToImage("outputExtractImagesFromWorksheets.jpg", printoption);  

    


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="O Aspose.Cells for .NET API" %}}

 Aspose.Cells API może służyć do tworzenia, edytowania, konwertowania i renderowania formatów programu Microsoft Excel do różnych formatów. Co więcej, może być używany do kompleksowych wykresów, skalowalnych raportów i niezawodnych obliczeń w aplikacjach. Aspose.Cells jest samodzielnym API i nie wymaga żadnego oprogramowania takiego jak Microsoft czy OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Internetowe prezentacje na żywo Parser XLS" sectionDescription="Wyodrębnij tekst i obrazy z dokumentów XLS już teraz, odwiedzając nasz [Witryna demonstracyjna na żywo](https://products.aspose.app/cells/parser). Demo na żywo ma następujące zalety" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Nie ma potrzeby pobierania Aspose API." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Nie musisz pisać żadnego kodu." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Po prostu prześlij swoje pliki XLS." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Zostanie on natychmiast przeanalizowany." >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}
Pliki z rozszerzeniem XLS reprezentują format pliku binarnego Excel. Takie pliki mogą być tworzone przez Microsoft Excel, a także inne podobne programy do arkuszy kalkulacyjnych, takie jak OpenOffice Calc lub Apple Numbers. Plik zapisany przez program Excel jest znany jako skoroszyt, w którym każdy skoroszyt może zawierać jeden lub więcej arkuszy. Dane są przechowywane i wyświetlane użytkownikom w formacie tabeli w arkuszu i mogą obejmować wartości liczbowe, dane tekstowe, formuły, połączenia danych zewnętrznych, obrazy i wykresy. Aplikacje takie jak Microsoft Excel umożliwiają eksportowanie danych ze skoroszytu do kilku różnych formatów, w tym PDF, CSV, XLSX, TXT, HTML, XPS i kilku innych. Format pliku XLS został zastąpiony bardziej otwartym i ustrukturyzowanym formatem, XLSX, wraz z wydaniem Microsoft Excel 2007. Najnowsze wersje nadal zapewniają obsługę tworzenia i odczytywania plików XLS, chociaż XLSX jest teraz pierwszym wyborem. 

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane formaty analizowania" subTitle="Używając C#, można łatwo analizować inne formaty, w tym." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/parser/ods/" name="SZWO" description="Plik arkusza kalkulacyjnego OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/parser/xlsb/" name="XLSB" description="Binarny plik skoroszytu programu Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/parser/xlsm/" name="XLSM" description="Plik arkusza kalkulacyjnego" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}