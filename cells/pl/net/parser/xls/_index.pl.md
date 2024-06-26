---
title:  Wyodrębnij tekst i obrazy z dokumentu XLS via .NET
weight: 5600
description: Kod źródłowy C# do wyodrębniania tekstu i obrazów z pliku XLS na platformie .NET, .NET Core, Mono lub platformach Xamarin.
keywords: [C# Aspose.Cells., c# Extract text and images from XLS file., c# How to Parse XLS File., c# Extract text from XLS file., Extract images from XLS file using C#]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Przeanalizuj formaty XLS w C#" h2="Natywne i wydajne analizowanie dokumentów XLS przy użyciu interfejsów API Aspose.Cells for .NET po stronie serwera, bez użycia oprogramowania takiego jak Microsoft lub Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Jak przeanalizować plik XLS przy użyciu C#" %}}

 Aby przeanalizować plik XLS, użyjemy[Aspose.Cells for .NET](https://products.aspose.com/cells/net) API, który jest bogatym w funkcje, wydajnym i łatwym w użyciu narzędziem do manipulacji dokumentami API dla platformy C#. otwarty[NuGet](https://www.nuget.org/packages/aspose.cells) menedżer pakietów, wyszukaj
 **Aspose.Cells** i zainstaluj. Możesz także użyć następującego polecenia z konsoli Menedżera pakietów.

{{% blocks/products/pf/agp/code-block title="Komenda" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Kroki, aby przeanalizować pliki XLS w C#" %}}

{{% blocks/products/pf/agp/text %}}

 Podstawowa analiza dokumentów za pomocą[Aspose.Cells for .NET](https://products.aspose.com/cells/net)Interfejsy API można wykonać za pomocą zaledwie kilku linii kodu. Analizuj tekst i obrazy z plików Microsoft Excel XLS, XLSX, XLSM, XLSB i OpenDocument ODS.

{{% /blocks/products/pf/agp/text %}}

+ Załaduj dokument XLS.
+ Wybierz arkusz.
+ Uzyskaj obraz i typ obrazu.
+ Zapisz obraz.
+ Zapisz dokument

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="wymagania systemowe" %}}

{{% blocks/products/pf/agp/text %}}

 Nasze interfejsy API są obsługiwane na wszystkich głównych platformach i systemach operacyjnych. Przed wykonaniem poniższego kodu upewnij się, że w Twoim systemie znajdują się następujące wymagania wstępne.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows lub kompatybilny system operacyjny z .NET Framework, .NET Core, Mono lub platformami Xamarin
-  Środowisko programistyczne, takie jak Microsoft Visual Studio
-  Dodaj odniesienie do biblioteki DLL Aspose.Cells for .NET w swoim projekcie — zainstaluj od NuGet, korzystając z przycisku Pobierz powyżej

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Przeanalizuj pliki XLS - C#" offSpacer="" %}}

```cs
    // extract images from Worksheets 
    // open a template Excel file
    Workbook workbook = new Workbook("sampleExtractImagesFromWorksheets.xls");
    
    // get the first worksheet
    Worksheet worksheet = workbook.Worksheets[0];
    
    // get the first Picture in the first worksheet
    Aspose.Cells.Drawing.Picture pic = worksheet.Pictures[0];
    
    // set the output image file path
    string picformat = pic.ImageType.ToString();
                
    // Note: you may evaluate the image format before specifying the image path
    // define ImageOrPrintOptions
    Aspose.Cells.Rendering.ImageOrPrintOptions printoption = new  Aspose.Cells.Rendering.ImageOrPrintOptions();
    
    // specify the image format
    printoption.ImageType =  Aspose.Cells.Drawing.ImageType.Jpeg;
                
    // save the image
    pic.ToImage("outputExtractImagesFromWorksheets.jpg", printoption);  

    

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="O Aspose.Cells for .NET API" %}}

 Aspose.Cells API można używać do tworzenia, edytowania, konwertowania i renderowania formatów Excel Microsoft do różnych formatów. Co więcej, można go używać do kompleksowych wykresów, skalowalnych raportów i niezawodnych obliczeń w aplikacjach. Numer Aspose.Cells jest samodzielnym numerem API i nie wymaga żadnego oprogramowania takiego jak Microsoft czy OpenOffice.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Demo online XLS Parsera na żywo" sectionDescription="Wyodrębnij tekst i obrazy z dokumentów XLS, odwiedzając naszą stronę[Witryna internetowa z prezentacjami na żywo](https://products.aspose.app/cells/parser). Demo na żywo ma następujące zalety" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Nie ma potrzeby pobierania Aspose API." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Nie trzeba pisać żadnego kodu." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Po prostu prześlij swoje pliki XLS." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Zostanie natychmiast przeanalizowany." >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}
Pliki z rozszerzeniem XLS reprezentują format pliku binarnego programu Excel. Takie pliki można utworzyć za pomocą Microsoft Excel, a także innych podobnych programów do obsługi arkuszy kalkulacyjnych, takich jak OpenOffice Calc lub Apple Numbers. Plik zapisany w programie Excel jest znany jako skoroszyt, gdzie każdy skoroszyt może zawierać jeden lub więcej arkuszy. Dane są przechowywane i wyświetlane użytkownikom w formie tabeli w arkuszu i mogą obejmować wartości liczbowe, dane tekstowe, formuły, zewnętrzne połączenia danych, obrazy i wykresy. Aplikacje takie jak Microsoft Excel umożliwiają eksportowanie danych skoroszytu do kilku różnych formatów, w tym PDF, CSV, XLSX, TXT, HTML, XPS i kilku innych. Format pliku XLS został zastąpiony bardziej otwartym i ustrukturyzowanym formatem XLSX wraz z wydaniem Microsoft Excel 2007. Najnowsze wersje nadal zapewniają obsługę tworzenia i odczytywania plików XLS, chociaż XLSX jest obecnie pierwszym wyborem.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane formaty analizowania" subTitle="Używając numeru C#, można łatwo analizować inne formaty, w tym." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/parser/ods/" name="ODS" description="Plik arkusza kalkulacyjnego OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/parser/xlsb/" name="XLSB" description="Binarny plik skoroszytu programu Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/parser/xlsm/" name="XLSM" description="Plik arkusza kalkulacyjnego" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/parser/xlsx/" name="XLSX" description="Plik Excela OOXML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
