---
title: Zoek TSV-document zonder te openen via Java 
weight: 4940
url: /nl/java/search/tsv/ 
description: Java voorbeeldcode om woorden met patroon te zoeken in TSV-bestand op Java Runtime-omgeving voor JSP/JSF-applicaties en desktopapplicaties.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Zoek TSV-indelingen in Java" h2="Native en high-performance TSV-document zoeken met server-side Aspose.Cells for Java API\'s, zonder het gebruik van software zoals Microsoft of Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="TSV" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Hoe TSV-bestand te zoeken met Java" %}}

 Om het TSV-bestand te zoeken, gebruiken we
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API, een uitgebreid, krachtig en gebruiksvriendelijk zoekplatform API for Java. U kunt de nieuwste versie rechtstreeks downloaden van
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

{{% blocks/products/pf/agp/feature-section-col title="Stappen om TSV-bestanden te zoeken in Java" %}}

{{% blocks/products/pf/agp/text %}}

 U kunt eenvoudig documenten zoeken met Aspose.Cells API's met slechts enkele regels code.

{{% /blocks/products/pf/agp/text %}}

+ Laad TSV-bestand door een werkmapobject te instantiëren.
+ Open het eerste werkblad in het TSV-bestand.
+ Zoek de cel met de opgegeven formule.
+ Instantieer FindOptions.
+ Zoek de cel met een tekenreekswaarde
+ Print de gevonden cellen na het zoekresultaat

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="systeem vereisten" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java ondersteunt op alle belangrijke platforms en besturingssystemen. Zorg ervoor dat u aan de volgende vereisten voldoet.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows of een compatibel besturingssysteem met Java Runtime Environment voor JSP/JSF-applicaties en desktopapplicaties.- Ontvang de nieuwste versie van Aspose.Cells for Java rechtstreeks van [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells)  .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="TSV-bestanden zoeken - Java" offSpacer="" %}}

```cs
// Een werkmapobject instantiëren
Workbook workbook = new Workbook(dataDir + "book1.tsv");

// Toegang tot het eerste werkblad in het TSV-bestand
Worksheet worksheet = workbook.getWorksheets().get(0);

// De cel zoeken die de opgegeven formule bevat
Cells cells = worksheet.getCells();

// Zoekopties instantiëren
FindOptions findOptions = new FindOptions();

// De cel zoeken met een tekenreekswaarde die begint met Or
findOptions.setLookAtType(LookAtType.START_WITH);

Cell cell = cells.find("SH", null, findOptions);

// De naam van de gevonden cel afdrukken na het zoeken 
System.out.println("Name of the cell containing String: " + cell.getName());  


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="Over Aspose.Cells for Java API" %}}

 Aspose.Cells API kan worden gebruikt voor het maken, bewerken, converteren en weergeven van Microsoft Excel-indelingen naar verschillende indelingen. Bovendien kan het worden gebruikt voor uitgebreide grafieken, schaalbare rapportage en betrouwbare berekeningen binnen softwaretoepassingen. Aspose.Cells is een zelfstandige API en vereist geen software zoals Microsoft of OpenOffice.  



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="Online TSV Zoeken in live demo\'s" sectionDescription="Zoek nu tekst, woorden, zinnen in TSV-documenten door naar onze [Live demo\'s website](https://products.aspose.app/cells/search). De live demo heeft de volgende voordelen:" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" U hoeft Aspose API niet te downloaden." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" U hoeft geen code te schrijven." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Upload gewoon uw TSV-bestanden." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Zoekresultaat verschijnt direct." >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="TSV " readMoreLink="https://docs.fileformat.com/spreadsheet/tsv/" >}}
Een bestandsindeling met door tabs gescheiden waarden (TSV) vertegenwoordigt gegevens die zijn gescheiden door tabbladen in platte tekst. Het bestandsformaat, vergelijkbaar met CSV, wordt gebruikt om gegevens op een gestructureerde manier te ordenen om te importeren en exporteren tussen verschillende applicaties. Het formaat wordt voornamelijk gebruikt voor het importeren/exporteren en uitwisselen van gegevens in Spreadsheet-applicaties en databases. Elk record in een TSV-bestand bevindt zich in een enkele regel tekstbestand waarin elke veldwaarde wordt gescheiden door een tabteken. Mediatype voor TSV-bestandsindeling is tekst/door tabs gescheiden waarden. 

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde zoekdocumenten" subTitle="Met Java kan men ook in andere bestanden zoeken, waaronder." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/csv/" name="CSV" description="Door komma\'s gescheiden waarden" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/ods/" name="ODS" description="OpenDocument-spreadsheetbestand" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/txt/" name="tekst" description="Tekstdocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/xls/" name="XLS" description="Excel binair formaat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/xlsb/" name="XLSB" description="Binair Excel-werkmapbestand" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/xlsm/" name="XLSM" description="Spreadsheetbestand" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}