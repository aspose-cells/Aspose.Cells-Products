---
title:  Wyszukaj dokument ODS bez otwierania via .NET
weight: 160
description: Kod źródłowy C# do wyszukiwania słów ze wzorcem w pliku ODS na platformach .NET Framework, .NET Core, Mono lub platformach Xamarin.
keywords: [C# Aspose.Cells., c# search words with pattern in ods file., c# find words with pattern in ods file., c# search string with pattern in ods file., c# find words with pattern in ods file., c# search words in ods file., c# find words in ods file., c# search string in ods file., c# find string in ods file]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Wyszukaj formaty ODS w C#" h2="Natywne i wydajne wyszukiwanie dokumentów ODS przy użyciu interfejsów API Aspose.Cells for .NET po stronie serwera, bez użycia oprogramowania takiego jak Microsoft lub Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="ODS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Jak wyszukać plik ODS za pomocą C#" %}}

 Aby przeszukać plik ODS użyjemy
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API, który jest bogatym w funkcje, wydajnym i łatwym w użyciu narzędziem do wyszukiwania dokumentów API dla platformy C#. otwarty
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 menedżer pakietów, wyszukaj
 **Aspose.Cells** 
 i zainstaluj. Możesz także użyć następującego polecenia z konsoli Menedżera pakietów.

{{% blocks/products/pf/agp/code-block title="Komenda" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Kroki wyszukiwania plików ODS w C#" %}}

{{% blocks/products/pf/agp/text %}}

 Podstawowe wyszukiwanie dokumentów za pomocą
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 Interfejsy API można wykonać za pomocą zaledwie kilku linii kodu.

{{% /blocks/products/pf/agp/text %}}

+ Załaduj plik ODS przy użyciu klasy Workbook.
+ Pobierz komórki w odpowiednim arkuszu.
+ Wyszukaj Numbers, datę i tekst za pomocą metody Znajdź

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="wymagania systemowe" %}}

{{% blocks/products/pf/agp/text %}}

 Nasze interfejsy API są obsługiwane na wszystkich głównych platformach i systemach operacyjnych. Przed wykonaniem poniższego kodu upewnij się, że w Twoim systemie znajdują się następujące wymagania wstępne.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows lub kompatybilny system operacyjny z .NET Framework, .NET Core, Mono lub platformami Xamarin
-  Środowisko programistyczne, takie jak Microsoft Visual Studio
-  Dodaj odniesienie do biblioteki DLL Aspose.Cells for .NET w swoim projekcie — zainstaluj od NuGet, korzystając z przycisku Pobierz powyżej

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Wyszukaj pliki ODS - C#" offSpacer="" %}}

```cs
// searching cells containing specified string value or number
Workbook workbook = new Workbook("book1.ods");

// get cells collection
Cells cells = workbook.Worksheets[0].Cells;

FindOptions opts = new FindOptions();
opts.LookInType = LookInType.Values;
opts.LookAtType = LookAtType.EntireContent;

// find the cell with the input integer or double
Cell cell1 = cells.Find(205, null, opts);

if (cell1 != null){
    Console.WriteLine("Name of the cell containing the value: " + cell1.Name);
}else{
    Console.WriteLine("Record not found ");
}

// find the cell with the input string
Aspose.Cells.Cell cell2 = cells.Find("Items A", null, opts);

if (cell2 != null){
    Console.WriteLine("Name of the cell containing the value: " + cell2.Name);
}else{
    Console.WriteLine("Record not found ");
}

// find the cell containing with the input string
opts.LookAtType = LookAtType.Contains;
Cell cell3 = cells.Find("Data", null, opts);

if (cell3 != null){
    Console.WriteLine("Name of the cell containing the value: " + cell3.Name);
}else{
    Console.WriteLine("Record not found ");
}  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="O Aspose.Cells for .NET API" %}}

 Aspose.Cells API można używać do tworzenia, edytowania, konwertowania i renderowania formatów Excel Microsoft do różnych formatów. Co więcej, można go używać do kompleksowych wykresów, skalowalnych raportów i niezawodnych obliczeń w aplikacjach. Numer Aspose.Cells jest samodzielnym numerem API i nie wymaga żadnego oprogramowania takiego jak Microsoft czy OpenOffice.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Online ODS Szukaj demonstracji na żywo" sectionDescription=" Wyszukaj teraz tekst, słowa i frazy w dokumentach ODS, odwiedzając naszą stronę[Witryna internetowa z prezentacjami na żywo](https://products.aspose.app/cells/search). Demo na żywo ma następujące zalety" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Nie ma potrzeby pobierania Aspose API." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Nie trzeba pisać żadnego kodu." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Po prostu prześlij swoje pliki ODS." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Wynik wyszukiwania pojawia się natychmiast." >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODS " readMoreLink="https://docs.fileformat.com/spreadsheet/ods/" >}}
Pliki z rozszerzeniem ODS dla formatu dokumentu arkusza kalkulacyjnego OpenDocument, które mogą być edytowane przez użytkownika. Dane są przechowywane w pliku ODF w wierszach i kolumnach. Jest to format oparty na języku XML i jest jednym z kilku podtypów rodziny formatów dokumentów otwartych (ODF). Format jest określony jako część specyfikacji ODF 1.2 opublikowanej i utrzymywanej przez firmę OASIS. Wiele aplikacji na Windows, a także na innych systemach operacyjnych może otwierać pliki ODS do edycji i manipulacji, w tym Microsoft Excel, NeoOffice i LibreOffice. Pliki ODS można również konwertować na inne formaty arkuszy kalkulacyjnych, takie jak XLS, XLSX i inne, za pomocą różnych aplikacji.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane formaty wyszukiwania" subTitle="Za pomocą numeru C# można wyszukiwać także w innych formatach, m.in." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/search/csv/" name="CSV" description="Wartości oddzielone przecinkami" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/search/tsv/" name="TSV" description="Wartości rozdzielone tabulatorami" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/search/txt/" name="TXT" description="Dokument tekstowy" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/search/xls/" name="XLS" description="Format binarny Excela" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/search/xlsb/" name="XLSB" description="Binarny plik skoroszytu programu Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/search/xlsm/" name="XLSM" description="Plik arkusza kalkulacyjnego" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
