---
title: Converteer SXC naar JSON via Java 
url: /nl/java/conversion/sxc-to-json/ 
description: Voorbeeld Java conversiecode voor SXC-indeling naar JSON-bestand. Programmeurs kunnen deze voorbeeldcode gebruiken om Excel- en OpenOffice-spreadsheets naar JSON te exporteren binnen elke web- of desktoptoepassing Java.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Converteer SXC naar JSON via Java" h2="SXC naar JSON Java-conversie om enkele of meerdere pagina\'s naar JSON te converteren met behulp van een lokale bibliotheek Java." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="JSON" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="SXC" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Hoe SXC naar JSON te converteren met Java" %}}

 Om SXC naar JSON te renderen, gebruiken we
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API, een veelzijdig, krachtig en gebruiksvriendelijk conversieplatform API for Java. U kunt de nieuwste versie rechtstreeks downloaden van
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

{{% blocks/products/pf/agp/feature-section-col title="Stappen om SXC naar JSON te converteren via Java" %}}

{{% blocks/products/pf/agp/text %}}

 Java ontwikkelaars kunnen het SXC-bestand gemakkelijk converteren naar JSON in slechts een paar regels code.

{{% /blocks/products/pf/agp/text %}}

1. Laad het SXC-bestand met een instantie van de Workbook-klasse1. Maak een gegevensbereik om te exporteren met behulp van de Cells.createRange-methode1. Roep de JsonUtility.exportRangeToJson-methode aan met verwijzingen naar Range & ExportRangeToJsonOptions1. Schrijf String JSON-gegevens naar bestand via BufferedWriter.write-methode

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="systeem vereisten" %}}

{{% blocks/products/pf/agp/text %}}

 Voordat u de conversiebroncode Java uitvoert, moet u ervoor zorgen dat u aan de volgende vereisten voldoet.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows of een compatibel besturingssysteem met Java Runtime Environment voor JSP/JSF-applicaties en desktopapplicaties.- Ontvang de nieuwste versie van Aspose.Cells for Java rechtstreeks van Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="SXC naar JSON Java conversiebroncode" offSpacer="" %}}

```cs
// laad XLSX-bestand met een exemplaar van Workbook
Workbook workbook = new Workbook("template.xlsx");
// toegang tot CellsVerzameling van het werkblad met gegevens die moeten worden geconverteerd
Cells cells = workbook.getWorksheets().get(0).getCells();
// maak en stel ExportRangeToJsonOptions in voor geavanceerde opties
ExportRangeToJsonOptions exportOptions = new ExportRangeToJsonOptions();
// maak een celbereik met gegevens om te exporteren
Range range = cells.createRange(0, 0, cells.getLastCell().getRow() + 1, cells.getLastCell().getColumn() + 1);
// bereik exporteren als JSON-gegevens
String jsonData = JsonUtility.exportRangeToJson(range, exportOptions);
// gegevens naar schijf schrijven in JSON-indeling
BufferedWriter writer = new BufferedWriter(new FileWriter("output.json"));
writer.write(jsonData);
writer.close();   
   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="SXC naar JSON conversie live demo\'s" sectionDescription="[Converteer SXC naar JSON](https://products.aspose.app/cells/conversion/sxc-to-json) op dit moment door onze Live Demo\'s-website te bezoeken. De live demo heeft de volgende voordelen:" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" U hoeft Aspose API niet te downloaden." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" U hoeft geen code te schrijven." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Upload gewoon uw SXC-bestand, het wordt onmiddellijk geconverteerd naar JSON." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" U krijgt de downloadlink." >}}

    {{% blocks/products/pf/agp/content h2="Java Bibliotheek voor spreadsheetmanipulatie" %}}

 Excel API kan worden gebruikt voor het maken, bewerken, converteren en weergeven van Microsoft Excel-indelingen naar verschillende indelingen. Bovendien kan het worden gebruikt voor uitgebreide grafieken, schaalbare rapportage en betrouwbare berekeningen binnen softwaretoepassingen. Aspose.Cells is een op zichzelf staande API en vereist geen software zoals Microsoft of OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="SXC" readMoreLink="https://docs.fileformat.com/spreadsheet/sxc/" >}}

Het bestandsformaat SXC (Sun XML Calc) behoort tot een kantoorsuite genaamd OpenOffice.org. Dit formaat houdt zich over het algemeen bezig met de spreadsheetbehoeften van gebruikers, aangezien het een op XML gebaseerd spreadsheetbestandsformaat is. Het SXC-formaat ondersteunt formules, functies, macro's en grafieken samen met DataPilot, wat een ongelooflijke functie is omdat het automatisch individualiseert en samenvattingen geeft van onbewerkte geïmporteerde gegevens. De bestanden die met deze software zijn gemaakt, worden opgeslagen met de extensie .sxc.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="JSON" readMoreLink="https://docs.fileformat.com/web/json/" >}}

JSON (JavaScript Object Notation) is een open standaardbestandsindeling voor het delen van gegevens die door mensen leesbare tekst gebruikt om gegevens op te slaan en te verzenden. JSON-bestanden worden opgeslagen met de .json-extensie. JSON vereist minder opmaak en is een goed alternatief voor XML. JSON is afgeleid van JavaScript, maar is een taalonafhankelijk gegevensformaat. Het genereren en parseren van JSON wordt ondersteund door veel moderne programmeertalen. application/json is het mediatype dat voor JSON wordt gebruikt.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}