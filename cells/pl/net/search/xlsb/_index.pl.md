---
title: Wyszukaj dokument XLSB bez otwierania przez .NET 
weight: 8880
url: /pl/net/search/xlsb/ 
description: C# kod źródłowy do wyszukiwania słów ze wzorem w pliku XLSB na platformach .NET Framework, .NET Core, Mono lub Xamarin.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Wyszukaj formaty XLSB w C#" h2="Natywne i wysokowydajne wyszukiwanie dokumentów XLSB przy użyciu interfejsów API Aspose.Cellsfor .NET po stronie serwera, bez użycia oprogramowania, takiego jak Microsoft lub Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLSB" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Jak wyszukać plik XLSB za pomocą C#" %}}

 Aby przeszukać plik XLSB, użyjemy
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API to bogata w funkcje, wydajna i łatwa w użyciu platforma przeszukiwania dokumentów API dla C#. otwarty
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

{{% blocks/products/pf/agp/feature-section-col title="Kroki wyszukiwania plików XLSB w C#" %}}

{{% blocks/products/pf/agp/text %}}

 Podstawowe wyszukiwanie dokumentów za pomocą
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API można wykonać za pomocą kilku linijek kodu.

{{% /blocks/products/pf/agp/text %}}

+ Załaduj plik XLSB za pomocą klasy Workbook.
+ Pobierz komórki w odpowiednim arkuszu.
+ Wyszukaj numery, datę i tekst za pomocą metody Znajdź

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="wymagania systemowe" %}}

{{% blocks/products/pf/agp/text %}}

 Nasze interfejsy API są obsługiwane na wszystkich głównych platformach i systemach operacyjnych. Przed wykonaniem poniższego kodu upewnij się, że masz w systemie następujące wymagania wstępne.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows lub zgodny system operacyjny z .NET Framework, .NET Core, Mono lub Xamarin Platforms- Środowisko programistyczne, takie jak Microsoft Visual Studio- Aspose.Cells for .NET Biblioteka DLL, do której odwołuje się Twój projekt — zainstaluj z NuGet za pomocą przycisku Pobierz powyżej
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Wyszukaj pliki XLSB — C#" offSpacer="" %}}

```cs
// wyszukiwanie komórek zawierających określoną wartość ciągu lub liczbę
Workbook workbook = new Workbook("book1.xlsb");

// pobierz kolekcję komórek
Cells cells = workbook.Worksheets[0].Cells;

FindOptions opts = new FindOptions();
opts.LookInType = LookInType.Values;
opts.LookAtType = LookAtType.EntireContent;

// znajdź komórkę z wejściową liczbą całkowitą lub podwójną
Cell cell1 = cells.Find(205, null, opts);

if (cell1 != null){
    Console.WriteLine("Name of the cell containing the value: " + cell1.Name);
}else{
    Console.WriteLine("Record not found ");
}

// znajdź komórkę z ciągiem wejściowym
Aspose.Cells.Cell cell2 = cells.Find("Items A", null, opts);

if (cell2 != null){
    Console.WriteLine("Name of the cell containing the value: " + cell2.Name);
}else{
    Console.WriteLine("Record not found ");
}

// znajdź komórkę zawierającą z ciągiem wejściowym
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

 Aspose.Cells API może służyć do tworzenia, edytowania, konwertowania i renderowania formatów programu Microsoft Excel do różnych formatów. Co więcej, może być używany do kompleksowych wykresów, skalowalnych raportów i niezawodnych obliczeń w aplikacjach. Aspose.Cells jest samodzielnym API i nie wymaga żadnego oprogramowania takiego jak Microsoft czy OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Online XLSB Szukaj na żywo w wersji demonstracyjnej" sectionDescription="Wyszukaj tekst, słowa, frazy w dokumentach XLSB już teraz, odwiedzając nasz [Witryna demonstracyjna na żywo](https://products.aspose.app/cells/search). Demo na żywo ma następujące zalety" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Nie ma potrzeby pobierania Aspose API." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Nie musisz pisać żadnego kodu." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Po prostu prześlij swoje pliki XLSB." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Wynik wyszukiwania pojawia się natychmiast." >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSB " readMoreLink="https://docs.fileformat.com/spreadsheet/xlsb/" >}}
Format pliku XLSB określa format pliku binarnego programu Excel, który jest zbiorem rekordów i struktur określających zawartość skoroszytu programu Excel. Treść może obejmować nieustrukturyzowane lub częściowo ustrukturyzowane tabele liczb, tekst lub zarówno liczby, jak i tekst, formuły, połączenia danych zewnętrznych, wykresy i obrazy. W przeciwieństwie do XLSX (który jest oparty na formacie pliku Open XML), XLSB reprezentuje binarny plik skoroszytu programu Excel. Pliki XLSB można szybciej odczytywać i zapisywać, co czyni je przydatnymi do pracy z dużymi plikami. XLSB jest rzadko używany do przechowywania skoroszytów, ponieważ XLSX (i wcześniej XLS) to najczęściej wybierane przez użytkowników formaty plików do zapisywania skoroszytów. Można go otworzyć w Microsoft Office 2007 i nowszych. 

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane formaty wyszukiwania" subTitle="Używając C#, można również przeszukiwać inne formaty, w tym." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/search/csv/" name="CSV" description="Wartości oddzielone przecinkami" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/search/ods/" name="SZWO" description="Plik arkusza kalkulacyjnego OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/search/tsv/" name="TSV" description="Wartości rozdzielane tabulatorami" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/search/txt/" name="tekst" description="Dokument tekstowy" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/search/xls/" name="XLS" description="Format binarny programu Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/search/xlsm/" name="XLSM" description="Plik arkusza kalkulacyjnego" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}