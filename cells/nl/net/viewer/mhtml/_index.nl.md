---
title:  Bekijk MHTML Bestandsformaten via .NET
description: C#-broncode voor het laden, weergeven en weergeven van MHTML-documenten op .NET Framework, .NET Core, Windows Azure, Mono of Xamarin-platforms.
keywords: [C# Aspose.Cells., c# view MHTL files., c# how to render MHTL document., c# load and display MHTL files., MHTL File Viewer using C#]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="MHTML Bestandsviewer for .NET" h2="Bekijk Excel- en OpenOffice-spreadsheets zoals MHTML zonder dat u Microsoft Excel of Kantoorautomatisering nodig heeft." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="DOC" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DOC" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Hoe u het bestand MHTML kunt bekijken met behulp van C#" %}}

 Om het bestand MHTML te bekijken, gebruiken we<a href="https://products.aspose.com/cells/net">Aspose.Cells for .NET</a>API, een functierijk, krachtig en gebruiksvriendelijk API voor C#-platform dat met elke viewer kan worden gebruikt. Open<a href="https://www.nuget.org/packages/aspose.cells">NuGet</a> pakketbeheerder, zoek naar<b>Aspose.Cells</b> en installeren. U kunt ook de volgende opdracht gebruiken vanuit de Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Pakketbeheerconsoleopdracht" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Stappen om te bezichtigen MHTML via C#" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells maakt het voor de ontwikkelaars gemakkelijk om het MHTML-bestand te bekijken met slechts enkele regels code.

{{% /blocks/products/pf/agp/text %}}

1. Laad het bestand MHTML in een exemplaar van Workbook
1. Maak een exemplaar van HtmlSaveOptions en stel de eigenschap ExportHeadings in op true
1. Sla het bestand MHTML op in de indeling HTML met behulp van de Workbook.Save-methode
1. Laad resulterende HTML in de standaardbrowser met Process.Start


{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="systeem vereisten" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for .NET wordt ondersteund op alle belangrijke besturingssystemen. Zorg ervoor dat u aan de volgende vereisten voldoet.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows of een compatibel besturingssysteem met .NET Framework, .NET Core, Windows Azure, Mono of Xamarin-platforms
-  Ontwikkelomgeving zoals Microsoft Visual Studio
-  Voeg een verwijzing toe naar de Aspose.Cells for .NET DLL in uw project

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# voorbeeldcode om het MHTML-bestand te bekijken" offSpacer="" %}}

```cs


string output = System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".html";

// load the MHTML file in an instance of Workbook
var book = new Aspose.Cells.Workbook("template.mhtml");
// create an instance of HtmlSaveOptions & set ExportHeadings property to true
var options = new Aspose.Cells.HtmlSaveOptions();
options.ExportHeadings = true;

// save the MHTML file in HTML format
book.Save(output, options);
// load resultant HTML in default browser
System.Diagnostics.Process.Start(output);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="" %}}

Aspose.Cells API kan worden gebruikt voor het maken, bewerken, converteren en renderen van Microsoft Excel-formaten naar verschillende formaten. Bovendien kan het worden gebruikt voor uitgebreide grafieken, schaalbare rapportage en betrouwbare berekeningen binnen softwareapplicaties. Aspose.Cells is een standalone API en vereist geen software zoals Microsoft of OpenOffice.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Gratis app om MHTML te bekijken" sectionDescription=" Bekijk onze live demo\'s om[Bekijk MHTML](https://products.aspose.app/cells/viewer/mhtml) met de volgende voordelen." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" U hoeft niets te downloaden of in te stellen" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" U hoeft geen code te schrijven of te compileren" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Upload gewoon het bestand MHTML en klik op de knop \"Bekijken\"." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Download indien nodig het bestand MHTML via de link" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="MHTML" readMoreLink="https://docs.fileformat.com/web/mhtml/" >}}
Bestanden met de extensie MHTML vertegenwoordigen een archiefformaat voor webpagina's dat door een aantal verschillende toepassingen kan worden gemaakt. Het formaat staat bekend als archiefformaat omdat het de web HTML-code en bijbehorende bronnen in één bestand opslaat. Deze bronnen omvatten alles wat aan de webpagina is gekoppeld, zoals afbeeldingen, applets, animaties, audiobestanden enzovoort. MHTML-bestanden kunnen worden geopend in verschillende toepassingen, zoals Internet Explorer en Microsoft Word. Microsoft Windows gebruikt de bestandsindeling MHTML voor het vastleggen van scenario's van problemen die zijn waargenomen tijdens het gebruik van een toepassing op Windows die problemen veroorzaakt. Het bestandsformaat MHTML codeert de pagina-inhoud vergelijkbaar met de specificaties die zijn gedefinieerd in message/rfc822, wat e-mailgerelateerde specificaties in platte tekst zijn. De feitelijke specificaties van het formaat zijn zoals gedetailleerd in RFC 2557.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde viewerformaten" subTitle="Met behulp van C# kan men ook vele andere bestandsformaten bekijken, waaronder." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/csv/" name="CSV" description="Door komma\'s gescheiden waarden" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/ods/" name="ODS" description="OpenDocument-spreadsheetbestand" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/tsv/" name="TSV" description="Door tabs gescheiden waarden" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/txt/" name="TXT" description="Tekstdocument" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xls/" name="XLS" description="Excel binair formaat" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xlsb/" name="XLSB" description="Binair Excel-werkmapbestand" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xlsm/" name="XLSM" description="Spreadsheet-bestand" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xlsx/" name="XLSX" description="OOXML Excel-bestand" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xlt/" name="XLT" description="Microsoft Excel-sjabloon" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xltm/" name="XLTM" description="Excel-sjabloon met macro\'s" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xltx/" name="XLTX" description="Office OpenXML Excel-sjabloon" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
