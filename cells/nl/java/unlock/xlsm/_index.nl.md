---
title:  Ontgrendel XLSM document via Java
weight: 7700
description: Java voorbeeldcode om het met een wachtwoord beveiligde bestand XLSM te ontgrendelen op Java Runtime Environment voor JSP/JSF-applicaties en desktopapplicaties.
keywords: [Java Aspose.Cells., Java unlock XLSM files., Java how to unlock XLSM document., Java unprotect XLSM files., remove protection from XLSM files., decrypt XLSM Files using Java]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Ontgrendel XLSM Bestanden via Java" h2="Verwijder de beveiliging van Excel-spreadsheets, inclusief het bestand XLSM, met behulp van de bibliotheek Java." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSM" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Beveiligingsbestand XLSM verwijderen met behulp van Java" %}}

 Om het bestand XLSM te ontgrendelen, gebruiken we
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

{{% blocks/products/pf/agp/feature-section-col title="Stappen om XLSM via Java te ontgrendelen" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1.  Instantieer de werkmapklasse met het pad naar het beveiligde bestand XLSM
1.  Haal de standaard of een ander werkblad op om de beveiliging te verwijderen
1.  Verwijder de werkbladbeveiliging met de Worksheet.Unprotect-methode
1.  Verwijder de werkmapbeveiliging met de Workbook.Unprotect-methode
1.  Resultaat opslaan in XLSM-formaat

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="systeem vereisten" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java ondersteunt op alle belangrijke platforms en besturingssystemen. Zorg ervoor dat u aan de volgende vereisten voldoet.

{{% /blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Ontgrendel XLSM Bestanden via Java" offSpacer="" %}}

```cs

Workbook wkb = new Workbook("source.xlsm");

WorksheetCollection wksc = wkb.getWorksheets();
Worksheet wks = wksc.get(0);

// Unprotecting the XLSM
wks.unprotect();

// Save the XLSM file.
wkb.save("Worksheet_out.xlsm", FileFormatType.EXCEL_97_TO_2003);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Over Aspose.Cells for Java API" %}}

 Aspose.Cells API kan worden gebruikt voor het maken, bewerken, converteren en renderen van Microsoft Excel-formaten naar verschillende formaten. Bovendien kan het worden gebruikt voor uitgebreide grafieken, schaalbare rapportage en betrouwbare berekeningen binnen softwareapplicaties. Aspose.Cells is een standalone API en vereist geen software zoals Microsoft of OpenOffice.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Gratis app om XLSM te ontgrendelen" sectionDescription=" Bekijk onze live demo\'s om[ontgrendel XLSM-bestanden](https://products.aspose.app/cells/unlock/xlsm) met de volgende voordelen." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" U hoeft niets te downloaden of in te stellen" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" U hoeft geen code te schrijven of te compileren" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Upload gewoon het bestand XLSM en klik op de knop \'Ontgrendelen\'" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Download het resulterende XLSM-bestand via de link" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSM" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsm/" >}}
Bestanden met de extensie XLSM zijn een soort spreadsheetbestanden die macro's ondersteunen. Vanuit toepassingsoogpunt is een macro een reeks instructies die worden gebruikt voor het automatiseren van processen. Een macro wordt gebruikt om de stappen vast te leggen die herhaaldelijk worden uitgevoerd en vergemakkelijkt het uitvoeren van de acties door de macro opnieuw uit te voeren. Macro's worden geprogrammeerd met Visual Basic for Applications (VBA) van Microsoft vanuit de Excel-werkmap met behulp van de Visual Basic Editor en kunnen vanaf daar rechtstreeks worden uitgevoerd/debuggen.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde ontgrendelingsformaten" subTitle="Met behulp van Java kan men eenvoudig de beveiliging / ontgrendeling van verschillende formaten verwijderen, waaronder." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/unlock/ods/" name="ODS" description="OpenDocument-spreadsheetbestand" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/unlock/xls/" name="XLS" description="Excel binair formaat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/unlock/xlsb/" name="XLSB" description="Binair Excel-werkmapbestand" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/unlock/xlsx/" name="XLSX" description="OOXML Excel-bestand" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
