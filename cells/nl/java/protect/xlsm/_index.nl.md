---
title: Bescherm en vergrendel XLSM-document via Java 
weight: 9620
url: /nl/java/protect/xlsm/ 
description: Java voorbeeldcode om XLSM-bestand te vergrendelen met wachtwoord in Java Runtime-omgeving voor JSP/JSF-applicaties en desktopapplicaties.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Versleutel XLSM-bestanden via Java" h2="Beveilig Excel-spreadsheets met een wachtwoord, inclusief XLSM-indeling, met .NET Library." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSM" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java/" installationsDocsLink="https://docs.aspose.com/cells/java/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java/" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Hoe XLSM-bestand te beveiligen met Java" %}}

 Om het XLSM-bestand te beschermen, gebruiken we
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API, een veelzijdig, krachtig en gebruiksvriendelijk versleutelings API for Java-platform. U kunt de nieuwste versie rechtstreeks downloaden van
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) 
 en installeer het binnen uw op Maven gebaseerde project door de volgende configuraties toe te voegen aan pom.xml.

{{% blocks/products/pf/agp/code-block title="Aspose.Cells" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Opslagplaats" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="Stappen om XLSM-bestanden te beschermen via Java" %}}

{{% blocks/products/pf/agp/text %}}

 Documentbeveiliging met Aspose.Cells API's is mogelijk met slechts enkele regels code.

{{% /blocks/products/pf/agp/text %}}

1. Laad het XLSM-bestand door de Workbook-klasse te instantiëren1. Gebruik de methode protect(..) met ProtectionType en Password1. Sla het beveiligde XLSM-bestand op met de methode save()
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="systeem vereisten" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java ondersteunt op alle belangrijke platforms en besturingssystemen. Zorg ervoor dat u aan de volgende vereisten voldoet.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows of een compatibel besturingssysteem met Java Runtime Environment voor JSP/JSF-applicaties en desktopapplicaties.- Ontvang de nieuwste versie van Aspose.Cells for Java rechtstreeks van [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells)  .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Afhankelijkheid" offSpacer="" %}}

```cs

// Open het XLSM-bestand
Workbook wkb = new Workbook("sourceFile.xlsm");

// Werkmap beveiligen door het beveiligingstype op te geven
wkb.protect(ProtectionType.ALL, "12345");

// Sla het XLSM-bestand op
wkb.save("lockedFile.xlsm");


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="Over Aspose.Cells for Java API" %}}

 Aspose.Cells API kan worden gebruikt voor het maken, bewerken, converteren en weergeven van Microsoft Excel-indelingen naar verschillende indelingen. Bovendien kan het worden gebruikt voor uitgebreide grafieken, schaalbare rapportage en betrouwbare berekeningen binnen softwaretoepassingen. Aspose.Cells is een zelfstandige API en vereist geen software zoals Microsoft of OpenOffice.  



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="Gratis app om XLSM te beschermen" sectionDescription="Bekijk onze live demo\'s om [versleutel XLSM-bestanden](https://products.aspose.app/cells/protect/xlsm) met volgende voordelen." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" U hoeft niets te downloaden of in te stellen" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" hoeft geen code te schrijven of te compileren" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Upload gewoon het XLSM-bestand en druk op de knop \"Ontgrendelen\"" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Download het resulterende XLSM-bestand via de link" >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSM" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsm/" >}}
Bestanden met de extensie XLSM zijn een soort Spreadsheet-bestanden die macro's ondersteunen. Vanuit toepassingsoogpunt is een macro een set instructies die worden gebruikt voor het automatiseren van processen. Een macro wordt gebruikt om de stappen die herhaaldelijk worden uitgevoerd vast te leggen en vergemakkelijkt het uitvoeren van de acties door de macro opnieuw uit te voeren. Macro's worden geprogrammeerd met Microsoft's Visual Basic for Applications (VBA) vanuit de Excel-werkmap met behulp van de Visual Basic Editor en kunnen direct vanaf daar worden uitgevoerd/foutopsporing.

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde beveiligingsdocumenten" subTitle="Met Java kan men andere bestanden beschermen, waaronder." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/protect/ods/" name="ODS" description="OpenDocument-spreadsheetbestand" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/protect/xls/" name="XLS" description="Excel binair formaat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/protect/xlsb/" name="XLSB" description="Binair Excel-werkmapbestand" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/protect/xlsx/" name="XLSX" description="OOXML Excel-bestand" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}