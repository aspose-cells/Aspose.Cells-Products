---
title: Przeglądaj lub edytuj metadane plików XLSX za pomocą .NET 
weight: 3430
url: /pl/net/metadata/xlsx/ 
description: C# kod źródłowy do edycji lub wyświetlania metadanych formatu XLSX na platformach .NET Framework, .NET Core, Mono lub Xamarin.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Wyodrębnij metadane XLSX przez .NET" h2="Twórz własne .NET aplikacje, aby dodawać, edytować, usuwać lub wyodrębniać metadane z plików XLSX przy użyciu interfejsów API po stronie serwera." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSX" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Jak wyodrębnić metadane XLSX za pomocą C#" %}}

 Aby wyodrębnić metadane XLSX, użyjemy
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API, który jest bogatym w funkcje, wydajnym i łatwym w użyciu metadanymi dokumentów API dla platformy C#. otwarty
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

{{% blocks/products/pf/agp/feature-section-col title="Kroki wyodrębniania metadanych XLSX za pomocą C#" %}}

{{% blocks/products/pf/agp/text %}}

 Uzyskaj dostęp do przydatnych informacji przechowywanych w pliku XLSX, w tym kiedy plik XLSX został odebrany, przetworzony, oznaczony czasem i tak dalej.

{{% /blocks/products/pf/agp/text %}}

+ Załaduj XLSX z instancją Workbook
+ Pobierz kolekcję BuiltInDocumentProperties obiektu Workbook
+ Iteruj po kolekcji
+ Wyświetl nazwę, typ i wartość właściwości

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="wymagania systemowe" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for .NET jest obsługiwany we wszystkich głównych systemach operacyjnych. Tylko upewnij się, że masz następujące wymagania wstępne.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows lub zgodny system operacyjny z .NET Framework, .NET Core, Mono lub Xamarin Platforms.- Środowisko programistyczne, takie jak Microsoft Visual Studio.- Aspose.Cells for .NET, do którego odwołuje się Twój projekt.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Wyodrębnij metadane XLSX — C#" offSpacer="" %}}

```cs

// załaduj XLSX z instancją Workbook
var book = new Aspose.Cells.Workbook("template.xlsx");
// iterować po kolekcji BuiltInDocumentProperties
foreach (Aspose.Cells.Properties.DocumentProperty property in book.Worksheets.BuiltInDocumentProperties)
{
    Console.WriteLine($"\tType:\t{property.Type}");

    // Niektóre właściwości mogą przechowywać wiele wartości
    if (property.Value is Array)
    {
        foreach (object value in property.Value as Array)
            Console.WriteLine($"\tValue:\t\"{value}\"");
    }
    else
    {
        Console.WriteLine($"\tValue:\t\"{property.Value}\"");
    }
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

        {{< blocks/products/pf/agp/demobox sectionTitle="Wyodrębnij metadane XLSX za pośrednictwem aplikacji online" sectionDescription="Przeglądaj i edytuj metadane do dokumentów XLSX za pomocą naszego [Prezentacje na żywo](https://products.aspose.app/cells/metadata) z następującymi korzyściami." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Nie musisz niczego pobierać ani konfigurować" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Nie musisz pisać żadnego kodu" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Po prostu prześlij plik XLSX i edytuj właściwości dokumentu" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Natychmiast uzyskaj link do pobrania pliku wynikowego" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSX" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsx/" >}}
XLSX to dobrze znany format dokumentów programu Microsoft Excel, który został wprowadzony przez firmę Microsoft wraz z wydaniem pakietu Microsoft Office 2007. W oparciu o strukturę zorganizowaną zgodnie z konwencjami otwartego pakowania, jak określono w części 2 standardu OOXML ECMA-376, nowy format jest pakiet zip, który zawiera wiele plików XML. Bazową strukturę i pliki można sprawdzić, po prostu rozpakowując plik .xlsx.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane formaty metadanych" subTitle="Używając C#, można również manipulować metadanymi wielu innych formatów, w tym." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/metadata/ods/" name="SZWO" description="Plik arkusza kalkulacyjnego OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/metadata/xls/" name="XLS" description="Format binarny programu Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/metadata/xlsb/" name="XLSB" description="Binarny plik skoroszytu programu Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/metadata/xlsm/" name="XLSM" description="Plik arkusza kalkulacyjnego" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}