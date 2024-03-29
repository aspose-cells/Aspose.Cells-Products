---
title:  Zoek document XLS zonder te openen via C++
weight: 4560
description: C++ voorbeeldcode om woorden met patroon te zoeken in het bestand XLS op C++ Runtime Environment voor Windows 32 bit, Windows 64 bit en Linux 64 bit.
keywords: [C++ Aspose.Cells., C++ search words with pattern in xls file., C++ find words with pattern in xls file., C++ search string with pattern in xls file., C++ find words with pattern in xls file., C++ search words in xls file., C++ find words in xls file., C++ search string in xls file., C++ find string in xls file]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Zoek XLS Formaten in C++" h2="Native en krachtige XLS-documentzoekopdracht met behulp van server-side Aspose.Cells for C++ API\'s, zonder het gebruik van software zoals Microsoft of Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Hoe u het bestand XLS kunt zoeken met behulp van C++" %}}

 Om het bestand XLS te doorzoeken, gebruiken we
 [Aspose.Cells for C++](https://products.aspose.com/cells/cpp) 
API, een functierijk, krachtig en gebruiksvriendelijk platform voor het zoeken naar documenten API for C++. U kunt de nieuwste versie direct downloaden, gewoon openen
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 pakketbeheerder, zoek naar
 **Aspose.Cells.Cpp** 
 en installeren. U kunt ook de volgende opdracht gebruiken vanuit de Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Commando" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Stappen om XLS-bestanden te zoeken in C++" %}}

{{% blocks/products/pf/agp/text %}}

 Een eenvoudige documentzoekopdracht met behulp van Aspose.Cells API's kan met slechts enkele regels code worden uitgevoerd.

{{% /blocks/products/pf/agp/text %}}

+ Laad het bestand XLS door een werkmapklasse te instantiëren.
+ Instantie ReplaceOptions-klasse.
+ Stel het vereiste patroon in, zoals SetCaseSensitive(bool value), SetMatchEntireCellContents(bool value) .
Gebruik de methode Workbook::Replace(...) met relevante opties.
+ Bewaar het XLS-bestand met de methode Workbook::Save(...).

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="systeem vereisten" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for C++ ondersteunt op alle belangrijke platforms en besturingssystemen. Zorg ervoor dat u aan de volgende vereisten voldoet.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows of een compatibel besturingssysteem met C++ Runtime Environment voor Windows 32 bit, Windows 64 bit en Linux 64 bit.
-  Voeg een verwijzing toe naar de Aspose.Cells for C++ DLL in uw project.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Zoek XLS Bestanden - C++" offSpacer="" %}}

```cs

Aspose::Cells::Startup();

// Source directory path.
U16String srcDir(u"SourcePath\\");

// Output directory path.
U16String outDir(u"OutputPath\\");

// Load XLS file
Workbook  wkb(srcDir + u"sourceFile.xls");

// Create an instance of the IReplaceOptions class
ReplaceOptions replaceOptions;

// Set case sensitivity option
replaceOptions.SetCaseSensitive(false);

// Set text matching option
replaceOptions.SetMatchEntireCellContents(false);

// Replace text
wkb.Replace(u"Text to find", u"Text replacement", replaceOptions);

// Save as XLS file
wkb.Save(outDir + u"outputFile.xls");

Aspose::Cells::Cleanup();

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="Over Aspose.Cells for C++ API" %}}

 Aspose.Cells API kan worden gebruikt voor het maken, bewerken, converteren en renderen van Microsoft Excel-formaten naar verschillende formaten. Bovendien kan het worden gebruikt voor uitgebreide grafieken, schaalbare rapportage en betrouwbare berekeningen binnen softwareapplicaties. Aspose.Cells is een standalone API en vereist geen software zoals Microsoft of OpenOffice.



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="Online XLS Zoek live demo\'s" sectionDescription=" Zoek nu tekst, woorden en zinnen in XLS-documenten door naar onze[Live demo-website](https://products.aspose.app/cells/search). De live demo heeft de volgende voordelen" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" U hoeft Aspose API niet te downloaden." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" U hoeft geen code te schrijven." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Upload gewoon uw XLS-bestanden." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Het zoekresultaat verschijnt onmiddellijk." >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS " readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}
Bestanden met de extensie XLS vertegenwoordigen het binaire bestandsformaat van Excel. Dergelijke bestanden kunnen worden gemaakt door Microsoft Excel en andere soortgelijke spreadsheetprogramma's zoals OpenOffice Calc of Apple Numbers. Bestand dat door Excel wordt opgeslagen, staat bekend als Werkmap, waarbij elke werkmap een of meer werkbladen kan hebben. Gegevens worden opgeslagen en weergegeven aan gebruikers in tabelindeling op een werkblad en kunnen numerieke waarden, tekstgegevens, formules, externe gegevensverbindingen, afbeeldingen en grafieken omvatten. Met toepassingen zoals Microsoft Excel kunt u werkmapgegevens naar verschillende formaten exporteren, waaronder PDF, CSV, XLSX, TXT, HTML, XPS en verschillende andere. Het bestandsformaat XLS werd vervangen door een meer open en gestructureerd formaat, XLSX, met de release van Microsoft Excel 2007. De nieuwste versies bieden nog steeds ondersteuning voor het maken en lezen van XLS-bestanden, hoewel XLSX nu de eerste gebruikskeuze is.

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde zoekdocumenten" subTitle="Met behulp van C++ kan men ook naar andere bestanden zoeken, waaronder." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/csv/" name="CSV" description="Door komma\'s gescheiden waarden" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/ods/" name="ODS" description="OpenDocument-spreadsheetbestand" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/tsv/" name="TSV" description="Door tabs gescheiden waarden" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/txt/" name="TXT" description="Tekstdocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/xlsb/" name="XLSB" description="Binair Excel-werkmapbestand" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/xlsm/" name="XLSM" description="Spreadsheet-bestand" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
