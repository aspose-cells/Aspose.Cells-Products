---
title: Converteer XLTM naar SVG via Java 
weight: 5230
url: /nl/java/conversion/xltm-to-svg/ 
description: Voorbeeld Java conversiecode voor XLTM-indeling naar SVG-bestand. Programmeurs kunnen deze voorbeeldcode gebruiken om Excel- en OpenOffice-spreadsheets naar SVG te exporteren binnen elke web- of desktoptoepassing Java.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Converteer XLTM naar SVG via Java" h2="Conversie van XLTM naar SVG Java om enkele of meerdere pagina\'s naar SVG te converteren met behulp van de lokale bibliotheek Java." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="SVG" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLTM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="XLTM naar SVG converteren met Java" %}}

 Om XLTM naar SVG te renderen, gebruiken we
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

{{% blocks/products/pf/agp/feature-section-col title="Stappen om XLTM naar SVG te converteren via Java" %}}

{{% blocks/products/pf/agp/text %}}

 Java ontwikkelaars kunnen XLTM-bestanden gemakkelijk converteren naar SVG in slechts een paar regels code.

{{% /blocks/products/pf/agp/text %}}

1. Laad XLTM-bestand met een exemplaar van Workbook1. Selecteer standaard of een werkblad uit de verzameling1. Maak en stel het object van ImageOrPrintOptions in1. Maak SheetRender met Worksheet & ImageOrPrintOptions-objecten1. Roep de methode SheetRender.toImage aan om het resultaat in SVG-indeling op te slaan
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="systeem vereisten" %}}

{{% blocks/products/pf/agp/text %}}

 Voordat u de conversiebroncode Java uitvoert, moet u ervoor zorgen dat u aan de volgende vereisten voldoet.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows of een compatibel besturingssysteem met Java Runtime Environment voor JSP/JSF-applicaties en desktopapplicaties.- Ontvang de nieuwste versie van Aspose.Cells for Java rechtstreeks van Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XLTM naar SVG Java Conversiebroncode" offSpacer="" %}}

```cs
// laad het XLTM-bestand dat moet worden weergegeven
Workbook workbook = new Workbook("sourceFile.xltm");
// toegang tot het standaard werkblad uit de verzameling
Worksheet worksheet = workbook.getWorksheets().get(0);
// parameters definiëren voor de resulterende afbeelding
ImageOrPrintOptions options = new ImageOrPrintOptions();
options.setOnePagePerSheet(true);
options.setImageType(ImageType.SVG);
// werkblad naar afbeelding converteren in SVG-indeling
SheetRender renderer = new SheetRender(worksheet, options);
renderer.toImage(0, "output.svg");   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Live demo\'s van XLTM naar SVG-conversie" sectionDescription="[Converteer XLTM naar SVG](https://products.aspose.app/cells/conversion/xltm-to-svg) op dit moment door onze Live Demo\'s-website te bezoeken. De live demo heeft de volgende voordelen:" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" U hoeft Aspose API niet te downloaden." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" U hoeft geen code te schrijven." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Upload gewoon uw XLTM-bestand, het wordt direct geconverteerd naar SVG." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" U krijgt de downloadlink." >}}

    {{% blocks/products/pf/agp/content h2="Java Bibliotheek voor spreadsheetmanipulatie" %}}

 Excel API kan worden gebruikt voor het maken, bewerken, converteren en weergeven van Microsoft Excel-indelingen naar verschillende indelingen. Bovendien kan het worden gebruikt voor uitgebreide grafieken, schaalbare rapportage en betrouwbare berekeningen binnen softwaretoepassingen. Aspose.Cells is een op zichzelf staande API en vereist geen software zoals Microsoft of OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLTM" readMoreLink="https://docs.fileformat.com/spreadsheet/xltm/" >}}

De XLTM-bestandsextensie vertegenwoordigt bestanden die door Microsoft Excel zijn gegenereerd als sjabloonbestanden met ingeschakelde macro's. XLTM-bestanden lijken qua structuur op XLTX, behalve dat de laatste geen ondersteuning biedt voor het maken van sjabloonbestanden met macro's. Dergelijke sjabloonbestanden worden gebruikt om de lay-out, opmaak en andere instellingen samen met de macro's te genereren en in te stellen om het maken van vergelijkbare XLSX-bestanden te vergemakkelijken.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="SVG" readMoreLink="https://docs.fileformat.com/page-description-language/svg/" >}}

SVG-bestanden zijn schaalbare vectorafbeeldingsbestanden die op XML gebaseerde tekstindeling gebruiken om het uiterlijk van de afbeelding te beschrijven. Het woord Scalable verwijst naar het feit dat de SVG kan worden geschaald naar verschillende formaten zonder kwaliteitsverlies. Op tekst gebaseerde beschrijving van dergelijke bestanden maakt ze onafhankelijk van resolutie. Het is een van de meest gebruikte formaten voor het bouwen van website- en printafbeeldingen om schaalbaarheid te bereiken. Het formaat kan echter alleen worden gebruikt voor tweedimensionale afbeeldingen. SVG-bestanden kunnen in bijna alle moderne browsers worden bekeken/geopend, waaronder Chrome, Internet Explorer, Firefox en Safari.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde conversies" subTitle="U kunt XLTM ook converteren naar vele andere bestandsindelingen, waaronder enkele die hieronder worden vermeld." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltm-to-bmp/" name="XLTM NAAR BMP" description="Bitmap afbeelding" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltm-to-csv/" name="XLTM NAAR CSV" description="Door komma\'s gescheiden waarden" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltm-to-dif/" name="XLTM NAAR DIF" description="Gegevensuitwisselingsformaat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltm-to-emf/" name="XLTM NAAR EMF" description="Verbeterde metabestandsindeling" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltm-to-gif/" name="XLTM NAAR GIF" description="Grafisch uitwisselingsformaat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltm-to-html/" name="XLTM NAAR HTML" description="Hypertekst-opmaaktaal" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltm-to-jpeg/" name="XLTM NAAR JPEG" description="JPEG-afbeelding" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltm-to-mhtml/" name="XLTM NAAR MHTML" description="Webpagina-archiefindeling" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltm-to-ods/" name="XLTM NAAR ODS" description="OpenDocument-spreadsheetbestand" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltm-to-pdf/" name="XLTM NAAR PDF" description="Draagbaar documentformaat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltm-to-png/" name="XLTM NAAR PNG" description="Draagbare netwerkgrafieken" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltm-to-tiff/" name="XLTM NAAR TIFF" description="Gelabelde afbeeldingsindeling" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltm-to-tsv/" name="XLTM NAAR TSV" description="Door tabs gescheiden waarden" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltm-to-txt/" name="XLTM NAAR TXT" description="Tekstdocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltm-to-xlm/" name="XLTM NAAR XLM" description="Excel-macrobestand" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltm-to-xls/" name="XLTM NAAR XLS" description="Excel binair formaat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltm-to-xlsb/" name="XLTM NAAR XLSB" description="Binair Excel-werkmapbestand" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltm-to-xlsx/" name="XLTM NAAR XLSX" description="OOXML Excel-bestand" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltm-to-xlt/" name="XLTM NAAR XLT" description="Microsoft Excel-sjabloon" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltm-to-xltx/" name="XLTM NAAR XLTX" description="Office OpenXML Excel-sjabloon" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltm-to-xps/" name="XLTM NAAR XPS" description="XML-papierspecificaties" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltm-to-json/" name="XLTM NAAR JSON" description="JavaScript-objectnotatie" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}