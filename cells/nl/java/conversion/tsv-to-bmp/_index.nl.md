---
title: Converteer TSV naar BMP via Java 
weight: 4200
url: /nl/java/conversion/tsv-to-bmp/ 
description: Voorbeeld Java conversiecode voor TSV-indeling naar BMP-bestand. Programmeurs kunnen deze voorbeeldcode gebruiken om Excel- en OpenOffice-spreadsheets naar BMP te exporteren binnen elke web- of desktoptoepassing Java.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Converteer TSV naar BMP via Java" h2="TSV naar BMP Java-conversie om enkele of meerdere pagina\'s naar BMP te converteren met behulp van een lokale bibliotheek Java." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="BMP" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="TSV" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Hoe TSV naar BMP te converteren met Java" %}}

 Om TSV naar BMP te renderen, gebruiken we
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

{{% blocks/products/pf/agp/feature-section-col title="Stappen om TSV naar BMP te converteren via Java" %}}

{{% blocks/products/pf/agp/text %}}

 Java ontwikkelaars kunnen TSV-bestanden eenvoudig in slechts een paar regels code naar BMP converteren.

{{% /blocks/products/pf/agp/text %}}

1. Laad TSV-bestand met een exemplaar van Workbook1. Selecteer standaard of een werkblad uit de verzameling1. Maak en stel het object van ImageOrPrintOptions in1. Maak SheetRender met Worksheet & ImageOrPrintOptions-objecten1. Roep de methode SheetRender.toImage aan om het resultaat op te slaan in BMP-formaat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="systeem vereisten" %}}

{{% blocks/products/pf/agp/text %}}

 Voordat u de conversiebroncode Java uitvoert, moet u ervoor zorgen dat u aan de volgende vereisten voldoet.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows of een compatibel besturingssysteem met Java Runtime Environment voor JSP/JSF-applicaties en desktopapplicaties.- Ontvang de nieuwste versie van Aspose.Cells for Java rechtstreeks van Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="TSV naar BMP Java Conversiebroncode" offSpacer="" %}}

```cs
// laad het TSV-bestand dat moet worden weergegeven
Workbook workbook = new Workbook("sourceFile.tsv");
// toegang tot het standaard werkblad uit de verzameling
Worksheet worksheet = workbook.getWorksheets().get(0);
// parameters definiëren voor de resulterende afbeelding
ImageOrPrintOptions options = new ImageOrPrintOptions();
options.setOnePagePerSheet(true);
options.setImageType(ImageType.BMP);
// werkblad converteren naar afbeelding in BMP-formaat
SheetRender renderer = new SheetRender(worksheet, options);
renderer.toImage(0, "output.bmp");   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="TSV naar BMP conversie live demo\'s" sectionDescription="[Converteer TSV naar BMP](https://products.aspose.app/cells/conversion/tsv-to-bmp) op dit moment door onze Live Demo\'s-website te bezoeken. De live demo heeft de volgende voordelen:" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" U hoeft Aspose API niet te downloaden." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" U hoeft geen code te schrijven." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Upload gewoon uw TSV-bestand, het wordt direct geconverteerd naar BMP." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" U krijgt de downloadlink." >}}

    {{% blocks/products/pf/agp/content h2="Java Bibliotheek voor spreadsheetmanipulatie" %}}

 Excel API kan worden gebruikt voor het maken, bewerken, converteren en weergeven van Microsoft Excel-indelingen naar verschillende indelingen. Bovendien kan het worden gebruikt voor uitgebreide grafieken, schaalbare rapportage en betrouwbare berekeningen binnen softwaretoepassingen. Aspose.Cells is een op zichzelf staande API en vereist geen software zoals Microsoft of OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="TSV" readMoreLink="https://docs.fileformat.com/spreadsheet/tsv/" >}}

Een bestandsindeling met door tabs gescheiden waarden (TSV) vertegenwoordigt gegevens die zijn gescheiden door tabbladen in platte tekst. Het bestandsformaat, vergelijkbaar met CSV, wordt gebruikt om gegevens op een gestructureerde manier te ordenen om te importeren en exporteren tussen verschillende applicaties. Het formaat wordt voornamelijk gebruikt voor het importeren/exporteren en uitwisselen van gegevens in Spreadsheet-applicaties en databases. Elk record in een TSV-bestand bevindt zich in een enkele regel tekstbestand waarin elke veldwaarde wordt gescheiden door een tabteken. Mediatype voor TSV-bestandsindeling is tekst/door tabs gescheiden waarden.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="BMP" readMoreLink="https://docs.fileformat.com/image/bmp/" >}}

Bestanden met de extensie .BMP vertegenwoordigen Bitmap Image-bestanden die worden gebruikt om digitale bitmapafbeeldingen op te slaan. Deze afbeeldingen zijn onafhankelijk van de grafische adapter en worden ook wel apparaatonafhankelijke bitmap (DIB)-bestandsindeling genoemd. Deze onafhankelijkheid dient om het bestand op meerdere platforms te openen, zoals Microsoft Windows en Mac. Het BMP-bestandsformaat kan gegevens opslaan als tweedimensionale digitale afbeeldingen in zowel zwart-wit als kleurformaat met verschillende kleurdiepten.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde conversies" subTitle="U kunt TSV ook converteren naar vele andere bestandsindelingen, waaronder enkele die hieronder worden vermeld." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-csv/" name="TSV NAAR CSV" description="Door komma\'s gescheiden waarden" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-dif/" name="TSV NAAR DIF" description="Gegevensuitwisselingsformaat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-emf/" name="TSV NAAR EMF" description="Verbeterde metabestandsindeling" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-gif/" name="TSV NAAR GIF" description="Grafisch uitwisselingsformaat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-html/" name="TSV NAAR HTML" description="Hypertekst-opmaaktaal" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-jpeg/" name="TSV NAAR JPEG" description="JPEG-afbeelding" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-mhtml/" name="TSV NAAR MHTML" description="Webpagina-archiefindeling" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-ods/" name="TSV NAAR ODS" description="OpenDocument-spreadsheetbestand" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-pdf/" name="TSV NAAR PDF" description="Draagbaar documentformaat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-png/" name="TSV NAAR PNG" description="Draagbare netwerkgrafieken" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-svg/" name="TSV NAAR SVG" description="Schaalbare vectorafbeeldingen" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-tiff/" name="TSV NAAR TIFF" description="Gelabelde afbeeldingsindeling" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-txt/" name="TSV NAAR TXT" description="Tekstdocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-xlm/" name="TSV NAAR XLM" description="Excel-macrobestand" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-xls/" name="TSV NAAR XLS" description="Excel binair formaat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-xlsb/" name="TSV NAAR XLSB" description="Binair Excel-werkmapbestand" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-xlsx/" name="TSV NAAR XLSX" description="OOXML Excel-bestand" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-xlt/" name="TSV NAAR XLT" description="Microsoft Excel-sjabloon" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-xltm/" name="TSV NAAR XLTM" description="Excel Macro-enabled sjabloon" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-xltx/" name="TSV NAAR XLTX" description="Office OpenXML Excel-sjabloon" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-xps/" name="TSV NAAR XPS" description="XML-papierspecificaties" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-json/" name="TSV NAAR JSON" description="JavaScript-objectnotatie" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}