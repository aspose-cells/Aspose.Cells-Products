---
title:  Ontgrendel XLS document via Java
weight: 6390
description: Java voorbeeldcode om het met een wachtwoord beveiligde bestand XLS te ontgrendelen op Java Runtime Environment voor JSP/JSF-applicaties en desktopapplicaties.
keywords: [Java Aspose.Cells., Java unlock XLS files., Java how to unlock XLS document., Java unprotect XLS files., remove protection from XLS files., decrypt XLS Files using Java]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Ontgrendel XLS Bestanden via Java" h2="Verwijder de beveiliging van Excel-spreadsheets, inclusief het bestand XLS, met behulp van de bibliotheek Java." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLS" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Beveiligingsbestand XLS verwijderen met behulp van Java" %}}

 Om het bestand XLS te ontgrendelen, gebruiken we
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API, een functierijk, krachtig en gebruiksvriendelijk beveiligingsplatform API for Java. U kunt de nieuwste versie rechtstreeks downloaden van
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

{{% blocks/products/pf/agp/feature-section-col title="Stappen om XLS via Java te ontgrendelen" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1.  Instantieer de werkmapklasse met het pad naar het beveiligde bestand XLS
1.  Haal de standaard of een ander werkblad op om de beveiliging te verwijderen
1.  Verwijder de werkbladbeveiliging met de Worksheet.Unprotect-methode
1.  Verwijder de werkmapbeveiliging met de Workbook.Unprotect-methode
1.  Resultaat opslaan in XLS-formaat

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="systeem vereisten" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java ondersteunt op alle belangrijke platforms en besturingssystemen. Zorg ervoor dat u aan de volgende vereisten voldoet.

{{% /blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Ontgrendel XLS Bestanden via Java" offSpacer="" %}}

```cs

Workbook wkb = new Workbook("source.xls");

WorksheetCollection wksc = wkb.getWorksheets();
Worksheet wks = wksc.get(0);

// Unprotecting the XLS
wks.unprotect();

// Save the XLS file.
wkb.save("Worksheet_out.xls", FileFormatType.EXCEL_97_TO_2003);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Over Aspose.Cells for Java API" %}}

 Aspose.Cells API kan worden gebruikt voor het maken, bewerken, converteren en renderen van Microsoft Excel-formaten naar verschillende formaten. Bovendien kan het worden gebruikt voor uitgebreide grafieken, schaalbare rapportage en betrouwbare berekeningen binnen softwareapplicaties. Aspose.Cells is een standalone API en vereist geen software zoals Microsoft of OpenOffice.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Gratis app om XLS te ontgrendelen" sectionDescription=" Bekijk onze live demo\'s om[ontgrendel XLS-bestanden](https://products.aspose.app/cells/unlock/xls) met de volgende voordelen." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" U hoeft niets te downloaden of in te stellen" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" U hoeft geen code te schrijven of te compileren" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Upload gewoon het bestand XLS en klik op de knop \'Ontgrendelen\'" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Download het resulterende XLS-bestand via de link" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}
Bestanden met de extensie XLS vertegenwoordigen het binaire bestandsformaat van Excel. Dergelijke bestanden kunnen worden gemaakt door Microsoft Excel en andere soortgelijke spreadsheetprogramma's zoals OpenOffice Calc of Apple Numbers. Bestand dat door Excel wordt opgeslagen, staat bekend als Werkmap, waarbij elke werkmap een of meer werkbladen kan hebben. Gegevens worden opgeslagen en weergegeven aan gebruikers in tabelindeling op een werkblad en kunnen numerieke waarden, tekstgegevens, formules, externe gegevensverbindingen, afbeeldingen en grafieken omvatten. Met toepassingen zoals Microsoft Excel kunt u werkmapgegevens naar verschillende formaten exporteren, waaronder PDF, CSV, XLSX, TXT, HTML, XPS en verschillende andere. Het bestandsformaat XLS werd vervangen door een meer open en gestructureerd formaat, XLSX, met de release van Microsoft Excel 2007. De nieuwste versies bieden nog steeds ondersteuning voor het maken en lezen van XLS-bestanden, hoewel XLSX nu de eerste gebruikskeuze is.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde ontgrendelingsformaten" subTitle="Met behulp van Java kan men eenvoudig de beveiliging / ontgrendeling van verschillende formaten verwijderen, waaronder." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/unlock/ods/" name="ODS" description="OpenDocument-spreadsheetbestand" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/unlock/xlsb/" name="XLSB" description="Binair Excel-werkmapbestand" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/unlock/xlsm/" name="XLSM" description="Spreadsheet-bestand" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/unlock/xlsx/" name="XLSX" description="OOXML Excel-bestand" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
