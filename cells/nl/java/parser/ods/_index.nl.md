---
title: Extraheer tekst en afbeeldingen uit ODS-document via Java 
weight: 4740
url: /nl/java/parser/ods/ 
description: Java voorbeeldcode voor het extraheren van tekst en afbeeldingen uit het ODS-bestand in Java Runtime Environment voor JSP/JSF-applicaties en desktopapplicaties.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="ODS-indelingen ontleden in Java" h2="Native en hoogwaardige ODS-documentparsering met server-side Aspose.Cells for Java API\'s, zonder het gebruik van software zoals Microsoft of Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="ODS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Hoe een ODS-bestand te parseren met Java" %}}

 Om het ODS-bestand te ontleden, gebruiken we
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API, een uitgebreid, krachtig en gebruiksvriendelijk parseringsplatform API for Java. U kunt de nieuwste versie rechtstreeks downloaden van
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) 
 en installeer het binnen uw op Maven gebaseerde project door de volgende configuraties toe te voegen aan pom.xml.

{{% blocks/products/pf/agp/code-block title="Opslagplaats" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Afhankelijkheid" offSpacer="true" %}}

```cs
<dependency>
<groupId>com.aspose</groupId>
<artifactId>aspose-cells</artifactId>
<version>version of aspose-cells API</version>
<classifier>jdk17</classifier>
</dependency>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Stappen om ODS-bestanden te parseren in Java" %}}

{{% blocks/products/pf/agp/text %}}

 Een basisdocument ontleden met
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API's kunnen worden gemaakt met slechts enkele regels code. Ontleden tekst en afbeeldingen uit Microsoft Excel XLS-, XLSX-, XLSM-, XLSB- en OpenDocument ODS-bestanden.

{{% /blocks/products/pf/agp/text %}}

+ Laad ODS-document met behulp van de werkmapklasse.
+ Selecteer het vereiste blad met de methode getWorksheets().get.
+ Haal alle cellen van het geselecteerde blad op met getCells().
+ Herhaal elke cel, haal de tekst op.
+ Druk elke celwaarde af of gebruik de StringBuilder append()-methode om als geheel te bekijken

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="systeem vereisten" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java ondersteunt op alle belangrijke platforms en besturingssystemen. Zorg ervoor dat u aan de volgende vereisten voldoet.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows of een compatibel besturingssysteem met Java Runtime Environment voor JSP/JSF-applicaties en desktopapplicaties.- Ontvang de nieuwste versie van Aspose.Cells for Java rechtstreeks van [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells)  .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="ODS-bestanden ontleden - Java" offSpacer="" %}}

```cs
StringBuilder stringBuilder = new StringBuilder();
Workbook book = new Workbook(dir + "book1.ods");
Worksheet sheet = book.getWorksheets().get(0);
Cells cells = sheet.getCells();
Iterator iterator = cells.iterator();
while(iterator.hasNext())
{
Cell cell = (Cell)iterator.next();
stringBuilder.append(cell.getStringValue());
stringBuilder.append(" ");
}
System.out.println(stringBuilder.toString());  

    


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="Over Aspose.Cells for Java API" %}}

 Aspose.Cells API kan worden gebruikt voor het maken, bewerken, converteren en weergeven van Microsoft Excel-indelingen naar verschillende indelingen. Bovendien kan het worden gebruikt voor uitgebreide grafieken, schaalbare rapportage en betrouwbare berekeningen binnen softwaretoepassingen. Aspose.Cells is een zelfstandige API en vereist geen software zoals Microsoft of OpenOffice.  



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="Online ODS Parser Live-demo\'s" sectionDescription="Extraheer tekst en afbeeldingen uit ODS-documenten nu door naar onze [Live demo\'s website](https://products.aspose.app/cells/parser). De live demo heeft de volgende voordelen:" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" U hoeft Aspose API niet te downloaden." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" U hoeft geen code te schrijven." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Upload gewoon uw ODS-bestanden." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Het wordt onmiddellijk geparseerd." >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODS" readMoreLink="https://docs.fileformat.com/spreadsheet/ods/" >}}
Bestanden met de ODS-extensie staan voor OpenDocument Spreadsheet Document-indeling die door de gebruiker kan worden bewerkt. Gegevens worden in het ODF-bestand opgeslagen in rijen en kolommen. Het is een op XML gebaseerde indeling en is een van de verschillende subtypen in de Open Document Formats (ODF)-familie. Het formaat wordt gespecificeerd als onderdeel van de ODF 1.2-specificaties die zijn gepubliceerd en onderhouden door OASIS. Een aantal toepassingen op Windows en andere besturingssystemen kunnen ODS-bestanden openen voor bewerking en manipulatie, waaronder Microsoft Excel, NeoOffice en LibreOffice. ODS-bestanden kunnen ook door verschillende toepassingen worden geconverteerd naar andere spreadsheetindelingen, zoals XLS, XLSX en andere. 

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde documenten parseren" subTitle="Met behulp van Java kan men gemakkelijk andere formaten ontleden, waaronder." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/parser/xls/" name="XLS" description="Excel binair formaat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/parser/xlsb/" name="XLSB" description="Binair Excel-werkmapbestand" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/parser/xlsm/" name="XLSM" description="Spreadsheetbestand" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}