---
title:  Zoek het document CSV zonder via .NET te openen
weight: 7510
description: C# broncode om woorden met patroon te zoeken in het CSV-bestand op .NET Framework, .NET Core, Mono of Xamarin Platforms.
keywords: [C# Aspose.Cells., c# search words with pattern in csv file., c# find words with pattern in csv file., c# search string with pattern in csv file., c# find words with pattern in csv file., c# search words in csv file., c# find words in csv file., c# search string in csv file., c# find string in csv file]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Zoek CSV Formaten in C#" h2="Native en krachtige CSV-documentzoekopdracht met behulp van server-side Aspose.Cells for .NET API\'s, zonder het gebruik van software zoals Microsoft of Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="CSV" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Hoe u het bestand CSV kunt zoeken met behulp van C#" %}}

 Om het bestand CSV te doorzoeken, gebruiken we
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API, een functierijke, krachtige en gebruiksvriendelijke documentzoekfunctie API voor het C#-platform. Open
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 pakketbeheerder, zoek naar
 **Aspose.Cells** 
 en installeren. U kunt ook de volgende opdracht gebruiken vanuit de Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Commando" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Stappen om CSV-bestanden te zoeken in C#" %}}

{{% blocks/products/pf/agp/text %}}

 Een eenvoudige documentzoekopdracht met
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API's kunnen met slechts enkele regels code worden uitgevoerd.

{{% /blocks/products/pf/agp/text %}}

+ Laad CSV-bestand met behulp van de werkmapklasse.
+ Haal de cellen op in het relevante blad.
+ Zoek Numbers, datum en tekst met behulp van de zoekmethode

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="systeem vereisten" %}}

{{% blocks/products/pf/agp/text %}}

 Onze API's worden ondersteund op alle belangrijke platforms en besturingssystemen. Voordat u de onderstaande code uitvoert, moet u ervoor zorgen dat uw systeem aan de volgende vereisten voldoet.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows of een compatibel besturingssysteem met .NET Framework, .NET Core, Mono of Xamarin-platforms
-  Ontwikkelomgeving zoals Microsoft Visual Studio
-  Voeg een verwijzing toe naar de Aspose.Cells for .NET DLL in uw project - Installeer vanaf NuGet met behulp van de downloadknop hierboven

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Zoek CSV Bestanden - C#" offSpacer="" %}}

```cs
// searching cells containing specified string value or number
Workbook workbook = new Workbook("book1.csv");

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

    {{% blocks/products/pf/agp/content h2="Over Aspose.Cells for .NET API" %}}

 Aspose.Cells API kan worden gebruikt voor het maken, bewerken, converteren en renderen van Microsoft Excel-formaten naar verschillende formaten. Bovendien kan het worden gebruikt voor uitgebreide grafieken, schaalbare rapportage en betrouwbare berekeningen binnen softwareapplicaties. Aspose.Cells is een standalone API en vereist geen software zoals Microsoft of OpenOffice.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Online CSV Zoek live demo\'s" sectionDescription=" Zoek nu tekst, woorden en zinnen in CSV-documenten door naar onze[Live demo-website](https://products.aspose.app/cells/search). De live demo heeft de volgende voordelen" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" U hoeft Aspose API niet te downloaden." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" U hoeft geen code te schrijven." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Upload gewoon uw CSV-bestanden." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Het zoekresultaat verschijnt onmiddellijk." >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="CSV " readMoreLink="https://docs.fileformat.com/spreadsheet/csv/" >}}
Bestanden met de extensie CSV (door komma's gescheiden waarden) vertegenwoordigen tekstbestanden die gegevensrecords bevatten met door komma's gescheiden waarden. Elke regel in een CSV-bestand is een nieuw record uit de set records in het bestand. Dergelijke bestanden worden gegenereerd wanneer gegevensoverdracht van het ene opslagsysteem naar het andere is bedoeld. Omdat alle toepassingen records kunnen herkennen, gescheiden door komma's, is het importeren van dergelijke gegevensbestanden naar de database heel gemakkelijk gedaan. Bijna alle spreadsheetprogramma's zoals Microsoft Excel of OpenOffice Calc kunnen CSV zonder veel moeite importeren. Gegevens die uit dergelijke bestanden worden geïmporteerd, worden in cellen van een spreadsheet gerangschikt voor weergave aan de gebruiker.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde zoekformaten" subTitle="Met behulp van C# kan men ook in andere formaten zoeken, waaronder." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/search/ods/" name="ODS" description="OpenDocument-spreadsheetbestand" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/search/tsv/" name="TSV" description="Door tabs gescheiden waarden" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/search/txt/" name="TXT" description="Tekstdocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/search/xls/" name="XLS" description="Excel binair formaat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/search/xlsb/" name="XLSB" description="Binair Excel-werkmapbestand" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/search/xlsm/" name="XLSM" description="Spreadsheet-bestand" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
