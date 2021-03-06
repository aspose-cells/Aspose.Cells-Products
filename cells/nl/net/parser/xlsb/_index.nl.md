---
title: Extraheer tekst en afbeeldingen uit XLSB-document via .NET 
weight: 2200
url: /nl/net/parser/xlsb/ 
description: C# broncode om tekst en afbeeldingen uit XLSB-bestanden te extraheren op .NET Framework, .NET Core, Mono of Xamarin Platforms.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Parseer XLSB-indelingen in C#" h2="Native en krachtige XLSB-documentparsering met server-side Aspose.Cells for .NET API\'s, zonder het gebruik van software zoals Microsoft of Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLSB" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Hoe een XLSB-bestand te parseren met C#" %}}

 Om het XLSB-bestand te ontleden, gebruiken we
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API, een veelzijdige, krachtige en gebruiksvriendelijke documentmanipulatie API voor C#-platform. Open
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 pakketbeheerder, zoek naar
 **Aspose.Cells** 
 en installeren. U kunt ook de volgende opdracht gebruiken vanuit de Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Opdracht" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Stappen om XLSB-bestanden te parseren in C#" %}}

{{% blocks/products/pf/agp/text %}}

 Een basisdocument ontleden met
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API's kunnen worden gemaakt met slechts enkele regels code. Ontleden tekst en afbeeldingen uit Microsoft Excel XLS-, XLSX-, XLSM-, XLSB- en OpenDocument ODS-bestanden.

{{% /blocks/products/pf/agp/text %}}

+ Laad XLSB-document.
+ Selecteer blad.
+ Verkrijg de afbeelding en het afbeeldingstype.
+ Sla de afbeelding op.
+ Document opslaan

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="systeem vereisten" %}}

{{% blocks/products/pf/agp/text %}}

 Onze API's worden ondersteund op alle belangrijke platforms en besturingssystemen. Voordat u de onderstaande code uitvoert, moet u ervoor zorgen dat u de volgende vereisten op uw systeem hebt.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows of een compatibel besturingssysteem met .NET Framework, .NET Core, Mono of Xamarin Platforms- Ontwikkelomgeving zoals Microsoft Visual Studio- Aspose.Cells for .NET DLL waarnaar wordt verwezen in uw project - Installeer vanaf NuGet met de downloadknop hierboven
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XLSB-bestanden ontleden - C#" offSpacer="" %}}

```cs
    // afbeeldingen extraheren uit werkbladen 
    // open een sjabloon Excel-bestand
    Workbook workbook = new Workbook("sampleExtractImagesFromWorksheets.xlsb");
    
    // pak het eerste werkblad
    Worksheet worksheet = workbook.Worksheets[0];
    
    // haal de eerste afbeelding in het eerste werkblad
    Aspose.Cells.Drawing.Picture pic = worksheet.Pictures[0];
    
    // stel het pad van het uitvoerafbeeldingsbestand in
    string picformat = pic.ImageType.ToString();
                
    // Opmerking: u kunt het afbeeldingsformaat evalueren voordat u het afbeeldingspad opgeeft
    // definieer ImageOrPrintOptions
    Aspose.Cells.Rendering.ImageOrPrintOptions printoption = new  Aspose.Cells.Rendering.ImageOrPrintOptions();
    
    // specificeer het afbeeldingsformaat
    printoption.ImageType =  Aspose.Cells.Drawing.ImageType.Jpeg;
                
    // sla de afbeelding op
    pic.ToImage("outputExtractImagesFromWorksheets.jpg", printoption);  

    


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Over Aspose.Cells for .NET API" %}}

 Aspose.Cells API kan worden gebruikt voor het maken, bewerken, converteren en weergeven van Microsoft Excel-indelingen naar verschillende indelingen. Bovendien kan het worden gebruikt voor uitgebreide grafieken, schaalbare rapportage en betrouwbare berekeningen binnen softwaretoepassingen. Aspose.Cells is een zelfstandige API en vereist geen software zoals Microsoft of OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Online XLSB Parser Live-demo\'s" sectionDescription="Extraheer nu tekst en afbeeldingen uit XLSB-documenten door naar onze [Live demo\'s website](https://products.aspose.app/cells/parser). De live demo heeft de volgende voordelen:" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" U hoeft Aspose API niet te downloaden." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" U hoeft geen code te schrijven." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Upload gewoon uw XLSB-bestanden." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Het wordt onmiddellijk geparseerd." >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSB" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsb/" >}}
XLSB-bestandsindeling specificeert de Excel Binary File Format, een verzameling records en structuren die de inhoud van de Excel-werkmap specificeren. De inhoud kan ongestructureerde of semi-gestructureerde tabellen met getallen, tekst of zowel getallen als tekst, formules, externe gegevensverbindingen, grafieken en afbeeldingen bevatten. In tegenstelling tot XLSX (dat is gebaseerd op het Open XML-bestandsformaat), vertegenwoordigt de XLSB een binair Excel-werkmapbestand. XLSB-bestanden kunnen sneller worden gelezen en geschreven, waardoor ze handig zijn voor het werken met grote bestanden. XLSB wordt zelden gebruikt om werkmappen op te slaan, aangezien XLSX (en voorheen XLS) de meest gebruikte door de gebruiker geselecteerde bestandsindelingen zijn voor het opslaan van werkmappen. Het kan worden geopend door Microsoft Office 2007 en hoger. 

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde parseerformaten" subTitle="Met behulp van C# kan men gemakkelijk andere formaten ontleden, waaronder." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/parser/ods/" name="ODS" description="OpenDocument-spreadsheetbestand" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/parser/xls/" name="XLS" description="Excel binair formaat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/parser/xlsm/" name="XLSM" description="Spreadsheetbestand" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}