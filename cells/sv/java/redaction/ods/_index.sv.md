---
title:  Sök och ersätt text i ODS dokument via Java
weight: 9210
description: Java exempelkod för att redigera känslig information i ODS-filen på Java Runtime Environment för JSP/JSF Application och Desktop Applications.
keywords: [Java Aspose.Cells., Java Search and replace text in ODS file., Java redact ODS file., Java edit ODS file., Java ODS file redaction., Java Search and replace string in ODS file]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Redigera ODS-format i Java" h2="Inbyggd och högpresterande ODS dokumentkänslig redaktionsinformation med hjälp av Aspose.Cells for Java API:er på serversidan, utan användning av någon programvara som Microsoft eller Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="ODS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Hur man redigerar ODS-fil med Java" %}}

 För att redigera filen ODS kommer vi att använda[Aspose.Cells for Java](https://products.aspose.com/cells/java) API som är en funktionsrik, kraftfull och lättanvänd redigeringsplattform API for Java. Du kan ladda ner den senaste versionen direkt från[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) och installera det i ditt Maven-baserade projekt genom att lägga till följande konfigurationer till pom.xml.

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

{{% blocks/products/pf/agp/feature-section-col title="Steg för att redigera ODS filer i Java" %}}

{{% blocks/products/pf/agp/text %}}

 En grundläggande dokumentsökning och ersätt text i innehåll, kommentarer eller metadata med[Aspose.Cells for Java](https://products.aspose.com/cells/java) API:er kan göras med bara några rader kod.

{{% /blocks/products/pf/agp/text %}}

+ Ladda ODS fil.
+ Välj relevant blad.
+ Definiera och specificera Sökalternativ.
+ Ange intervallet där du vill söka
Gå igenom varje cell och använd getCells().find(...).
+ Byt ut värdet.
+ Spara arbetsboken.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Systemkrav" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java stöder på alla större plattformar och operativsystem. Se till att du har följande förutsättningar.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows eller ett kompatibelt operativsystem med Java Runtime Environment för JSP/JSF Application och Desktop Applications.
-  Hämta senaste versionen av Aspose.Cells for Java direkt från
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells)  .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Redagera ODS Filer - Java" offSpacer="" %}}

```cs
Workbook workbook = new Workbook(dataDir + "sourceFile.ods");

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
workbook.save(dataDir + "output.ods");

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="Om Aspose.Cells for Java API" %}}

 Aspose.Cells API kan användas för att skapa, redigera, konvertera och rendera Microsoft Excel-format till olika format. Dessutom kan den användas för omfattande kartläggning, skalbar rapportering och tillförlitliga beräkningar inom mjukvaruapplikationer. Aspose.Cells är en fristående API och den kräver ingen programvara som Microsoft eller OpenOffice.



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="Online ODS Redaction Live Demos" sectionDescription=" Sök och ersätt text i innehåll, kommentarer eller metadata i ODS dokument just nu genom att besöka vår[Live Demos webbplats](https://products.aspose.app/cells/redaction). Livedemon har följande fördelar" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Du behöver inte ladda ner Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Du behöver inte skriva någon kod." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Ladda bara upp dina ODS-filer." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Den kommer att redigeras omedelbart." >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODS" readMoreLink="https://docs.fileformat.com/spreadsheet/ods/" >}}
 Filer med tillägget ODS står för OpenDocument Spreadsheet Document-format som kan redigeras av användaren. Data lagras i ODF-filen i rader och kolumner. Det är XML-baserat format och är en av flera undertyper i familjen Open Document Formats (ODF). Formatet specificeras som en del av ODF 1.2-specifikationerna som publiceras och underhålls av OASIS. Ett antal applikationer på Windows såväl som andra operativsystem kan öppna ODS-filer för redigering och manipulering, inklusive Microsoft Excel, NeoOffice och LibreOffice. ODS-filer kan också konverteras till andra kalkylbladsformat, liksom XLS, XLSX och andra av olika applikationer.

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andra omarbetningsdokument som stöds" subTitle="Med hjälp av Java kan man enkelt redigera olika format inklusive." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/redaction/xls/" name="XLS" description="Excel binärt format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/redaction/xlsb/" name="XLSB" description="Binär Excel arbetsbok fil" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/redaction/xlsm/" name="XLSM" description="Kalkylbladsfil" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/redaction/xlsx/" name="XLSX" description="OOXML Excel-fil" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
