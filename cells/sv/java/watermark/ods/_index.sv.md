---
title: Vattenstämpel ODS-dokument via Java 
weight: 1040
url: /sv/java/watermark/ods/ 
description: Java exempelkod för att lägga till eller ta bort vattenstämpel till ODS-fil i Java Runtime Environment for JSP/JSF Application and Desktop Applications.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Lägg till textvattenstämpel till ODS via Java" h2="Bygg dina egna Java-appar för att vattenmärka ODS-filer med hjälp av API:er på serversidan." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODS" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Hur man vattenmärker ODS-fil med Java" %}}

 För att vattenmärka ODS-filen kommer vi att använda
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API som är en funktionsrik, kraftfull och lättanvänd API for Java-plattform för vattenmärkning. Du kan ladda ner den senaste versionen direkt från
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) 
 och installera det i ditt Maven-baserade projekt genom att lägga till följande konfigurationer till pom.xml.

{{% blocks/products/pf/agp/code-block title="Förvar" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Beroende" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="Steg för att lägga till vattenstämpel till ODS via Java" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. Skapa ett nytt arbetsboksobjekt1. Välj kalkylblad via dess index1. Skapa en form och använd dess addTextEffect-funktion1. Ställ in färger, transparens och mer1. Spara arbetsbok i ODS-format
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Systemkrav" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java stöds på alla större plattformar och operativsystem. Se till att du har följande förutsättningar.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows eller ett kompatibelt operativsystem med Java Runtime Environment för JSP/JSF Application och Desktop Applications.- Hämta den senaste versionen av Aspose.Cells for Java direkt från Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Lägg till vattenstämpel till ODS - Java" offSpacer="" %}}

```cs

// Instantiera en ny arbetsbok
Workbook workbook = new Workbook();

// Skaffa det första standardarket
Worksheet sheet = workbook.getWorksheets().get(0);

// Lägg till vattenstämpel
Shape wordart = sheet.getShapes().addTextEffect(MsoPresetTextEffect.TEXT_EFFECT_1, "CONFIDENTIAL",
		"Arial Black", 50, false, true, 18, 8, 1, 1, 130, 800);

// Få utfyllnadsformatet för ordkonsten
FillFormat wordArtFormat = wordart.getFill();

// Ställ in färgen
wordArtFormat.setOneColorGradient(Color.getRed(), 0.2, GradientStyleType.HORIZONTAL, 2);

// Ställ in transparensen
wordArtFormat.setTransparency(0.9);

// Gör linjen osynlig
LineFormat lineFormat = wordart.getLine();
lineFormat.setWeight(0.0);

// Spara filen
workbook.save(dataDir + "AWArtWToWorksheet_out.ods");  


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Om Aspose.Cells for Java API" %}}

 Aspose.Cells API kan användas för att skapa, redigera, konvertera och återge Microsoft Excel-format till olika format. Dessutom kan den användas för omfattande kartläggning, skalbar rapportering och tillförlitliga beräkningar inom mjukvaruapplikationer. Aspose.Cells är en fristående API och kräver ingen programvara som Microsoft eller OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Vattenstämpel ODS via onlineapp" sectionDescription="Lägg till vattenstämpel till ODS-dokument genom att besöka vår [Live Demos webbplats](https://products.aspose.app/cells/watermark). Livedemon har följande fördelar" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Du behöver inte ladda ner eller ställa in någonting" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Du behöver inte skriva någon kod" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Ladda bara upp din ODS-fil, ställ in din vattenstämpel och tryck på knappen \"Lägg till\"." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Skaffa omedelbart nedladdningslänken för den resulterande filen" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODS" readMoreLink="https://docs.fileformat.com/spreadsheet/ods/" >}}
Filer med ODS-tillägg står för OpenDocument Spreadsheet Document-format som kan redigeras av användaren. Data lagras i ODF-filen i rader och kolumner. Det är XML-baserat format och är en av flera undertyper i familjen Open Document Formats (ODF). Formatet specificeras som en del av ODF 1.2-specifikationerna som publiceras och underhålls av OASIS. Ett antal applikationer på Windows såväl som andra operativsystem kan öppna ODS-filer för redigering och manipulering, inklusive Microsoft Excel, NeoOffice och LibreOffice. ODS-filer kan också konverteras till andra kalkylbladsformat som XLS, XLSX och andra av olika applikationer.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andra vattenmärkeformat som stöds" subTitle="Med Java kan man enkelt vattenmärka olika format inklusive." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/watermark/xls/" name="XLS" description="Excel binärt format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/watermark/xlsb/" name="XLSB" description="Binär Excel arbetsbok fil" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/watermark/xlsm/" name="XLSM" description="Kalkylbladsfil" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}