---
title:  Zoek en vervang tekst in XLSM document via Java
weight: 1590
description: Java voorbeeldcode om gevoelige informatie in bestand XLSM te redigeren op Java Runtime Environment voor JSP/JSF-applicaties en desktopapplicaties.
keywords: [Java Aspose.Cells., Java Search and replace text in XLSM file., Java redact XLSM file., Java edit XLSM file., Java XLSM file redaction., Java Search and replace string in XLSM file]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="XLSM redigeren Formaten in Java" h2="Native en krachtige XLSM documentgevoelige redactieinformatie met behulp van server-side Aspose.Cells for Java API\'s, zonder het gebruik van software zoals Microsoft of Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLSM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Hoe u een XLSM-bestand kunt redigeren met behulp van Java" %}}

 Om het bestand XLSM te redigeren, gebruiken we[Aspose.Cells for Java](https://products.aspose.com/cells/java) API, een rijk, krachtig en gebruiksvriendelijk redactieplatform API for Java. U kunt de nieuwste versie rechtstreeks downloaden van[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) en installeer het binnen uw op Maven gebaseerde project door de volgende configuraties toe te voegen aan pom.xml.

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

{{% blocks/products/pf/agp/feature-section-col title="Stappen om XLSM-bestanden in Java te redigeren" %}}

{{% blocks/products/pf/agp/text %}}

 Een basisdocument zoeken en tekst in inhoud, opmerkingen of metagegevens vervangen[Aspose.Cells for Java](https://products.aspose.com/cells/java) API's kunnen met slechts enkele regels code worden uitgevoerd.

{{% /blocks/products/pf/agp/text %}}

+ Laad XLSM-bestand.
+ Selecteer het betreffende blad.
+ Definieer en specificeer zoekopties.
+ Geef het bereik op waarin u wilt zoeken
Loop door elke cel en gebruik getCells().find(...).
+ Vervang de waarde.
+ Bewaar de werkmap.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="systeem vereisten" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java ondersteunt op alle belangrijke platforms en besturingssystemen. Zorg ervoor dat u aan de volgende vereisten voldoet.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows of een compatibel besturingssysteem met Java Runtime Environment voor JSP/JSF-applicatie en desktopapplicaties.
-  Ontvang de nieuwste versie van Aspose.Cells for Java rechtstreeks van
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells)  .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XLSM-bestanden redigeren - Java" offSpacer="" %}}

```cs
Workbook workbook = new Workbook(dataDir + "sourceFile.xlsm");

Worksheet worksheet = workbook.getWorksheets().get(0);

// Specify the range where you want to search
// Here the range is E3:H6
CellArea area = CellArea.createCellArea("E3", "H6");

// Specify Find options
FindOptions opts = new FindOptions();
opts.setLookInType(LookInType.VALUES);
opts.setLookAtType(LookAtType.ENTIRE_CONTENT);
opts.setRange(area);

Cell cell = null;

do {
	// Search the cell with value search within range
	cell = worksheet.getCells().find("search", cell, opts);

	// If no such cell found, then break the loop
	if (cell == null)
		break;

	// Replace the cell with value replace
	cell.putValue("replace");

} while (true);

// Save the workbook
workbook.save(dataDir + "output.xlsm");

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="Over Aspose.Cells for Java API" %}}

 Aspose.Cells API kan worden gebruikt voor het maken, bewerken, converteren en renderen van Microsoft Excel-formaten naar verschillende formaten. Bovendien kan het worden gebruikt voor uitgebreide grafieken, schaalbare rapportage en betrouwbare berekeningen binnen softwareapplicaties. Aspose.Cells is een standalone API en vereist geen software zoals Microsoft of OpenOffice.



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="Online XLSM Live-demo\'s voor redactie" sectionDescription=" Zoek en vervang nu tekst in de inhoud, opmerkingen of metagegevens in XLSM-documenten door naar onze[Live demo-website](https://products.aspose.app/cells/redaction). De live demo heeft de volgende voordelen" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" U hoeft Aspose API niet te downloaden." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" U hoeft geen code te schrijven." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Upload gewoon uw XLSM-bestanden." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Het wordt onmiddellijk geredigeerd." >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSM" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsm/" >}}
Bestanden met de extensie XLSM zijn een soort spreadsheetbestanden die macro's ondersteunen. Vanuit toepassingsoogpunt is een macro een reeks instructies die worden gebruikt voor het automatiseren van processen. Een macro wordt gebruikt om de stappen vast te leggen die herhaaldelijk worden uitgevoerd en vergemakkelijkt het uitvoeren van de acties door de macro opnieuw uit te voeren. Macro's worden geprogrammeerd met Visual Basic for Applications (VBA) van Microsoft vanuit de Excel-werkmap met behulp van de Visual Basic Editor en kunnen vanaf daar rechtstreeks worden uitgevoerd/debuggen.

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde redactiedocumenten" subTitle="Met behulp van Java kunt u eenvoudig verschillende formaten redigeren, waaronder." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/redaction/ods/" name="ODS" description="OpenDocument-spreadsheetbestand" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/redaction/xls/" name="XLS" description="Excel binair formaat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/redaction/xlsb/" name="XLSB" description="Binair Excel-werkmapbestand" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/redaction/xlsx/" name="XLSX" description="OOXML Excel-bestand" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
