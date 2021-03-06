---
title: Konvertera XLS till CSV via Java 
weight: 120
url: /sv/java/conversion/xls-to-csv/ 
description: Exempel på Java-konverteringskod för XLS-format till CSV-fil. Programmerare kan använda den här exempelkoden för att exportera Excel- och OpenOffice-kalkylblad till CSV inom alla webb- eller skrivbordsbaserade Javaapplikationer.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Konvertera XLS till CSV via Java" h2="XLS till CSV Java-konvertering för att konvertera enstaka eller flera sidor till CSV med hjälp av lokalt Java-bibliotek." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="CSV" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Så här konverterar du XLS till CSV med Java" %}}

 För att rendera XLS till CSV kommer vi att använda
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API som är en funktionsrik, kraftfull och lättanvänd konverteringsplattform API for Java. Du kan ladda ner den senaste versionen direkt från
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

{{% blocks/products/pf/agp/feature-section-col title="Steg för att konvertera XLS till CSV via Java" %}}

{{% blocks/products/pf/agp/text %}}

 Java-utvecklare kan enkelt konvertera XLS-fil till CSV på bara några rader kod.

{{% /blocks/products/pf/agp/text %}}

1. Ladda XLS-fil med en instans av Workbook-klassen1. Ring Workbook.save-metoden1. Passera utdatasökväg med CSV-tillägg och SaveFormat som parametrar1. Kontrollera den angivna sökvägen för den resulterande CSV-filen
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Systemkrav" %}}

{{% blocks/products/pf/agp/text %}}

 Innan du kör källkoden för omvandlingen Java, se till att du har följande förutsättningar.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows eller ett kompatibelt operativsystem med Java Runtime Environment för JSP/JSF Application och Desktop Applications.- Hämta den senaste versionen av Aspose.Cells for Java direkt från Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XLS till CSV Java omvandlingskällkod" offSpacer="" %}}

```cs
// ladda XLS-filen i en instans av Workbook
Workbook book = new Workbook("template.xls");
// spara XLS som CSV
book.save("output.csv", SaveFormat.AUTO);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="XLS till CSV Conversion Live Demos" sectionDescription="[Konvertera XLS till CSV](https://products.aspose.app/cells/conversion/xls-to-csv) just nu genom att besöka vår Live Demos-webbplats. Livedemon har följande fördelar" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Du behöver inte ladda ned Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Du behöver inte skriva någon kod." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Ladda bara upp din XLS-fil, den konverteras omedelbart till CSV." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Du kommer att få nedladdningslänken." >}}

    {{% blocks/products/pf/agp/content h2="Java Kalkylarksmanipulationsbibliotek" %}}

 Excel API kan användas för att skapa, redigera, konvertera och återge Microsoft Excel-format till olika format. Dessutom kan den användas för omfattande kartläggning, skalbar rapportering och tillförlitliga beräkningar inom mjukvaruapplikationer. Aspose.Cells är en fristående API och kräver ingen programvara som Microsoft eller OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}

Filer med XLS-tillägg representerar Excel Binary File Format. Sådana filer kan skapas av Microsoft Excel såväl som andra liknande kalkylprogram som OpenOffice Calc eller Apple Numbers. Fil som sparas av Excel kallas arbetsbok där varje arbetsbok kan ha ett eller flera kalkylblad. Data lagras och visas för användare i tabellformat i kalkylblad och kan sträcka sig över numeriska värden, textdata, formler, externa dataanslutningar, bilder och diagram. Applikationer som Microsoft Excel låter dig exportera arbetsboksdata till flera olika format inklusive PDF, CSV, XLSX, TXT, HTML, XPS och flera andra. XLS-filformatet ersattes med ett mer öppet och strukturerat format, XLSX, med lanseringen av Microsoft Excel 2007. De senaste versionerna ger fortfarande stöd för att skapa och läsa XLS-filer, även om XLSX är förstahandsvalet för användning nu.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="CSV" readMoreLink="https://docs.fileformat.com/spreadsheet/csv/" >}}

Filer med tillägget CSV (Comma Separated Values) representerar vanliga textfiler som innehåller dataposter med kommaseparerade värden. Varje rad i en CSV-fil är en ny post från den uppsättning poster som finns i filen. Sådana filer genereras när dataöverföring är avsedd från ett lagringssystem till ett annat. Eftersom alla applikationer kan känna igen poster separerade med kommatecken, görs import av sådana datafiler till databasen mycket bekvämt. Nästan alla kalkylprogram som Microsoft Excel eller OpenOffice Calc kan importera CSV utan större ansträngning. Data som importeras från sådana filer är ordnade i celler i ett kalkylblad för representation för användaren.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andra omvandlingar som stöds" subTitle="Du kan också konvertera XLS till många andra filformat inklusive några som anges nedan." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-bmp/" name="XLS TILL BMP" description="Bitmappsbild" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-dif/" name="XLS TILL DIF" description="Datautbytesformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-emf/" name="XLS TILL EMF" description="Förbättrat metafilformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-gif/" name="XLS TILL GIF" description="Grafiskt utbytesformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-html/" name="XLS TILL HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-jpeg/" name="XLS TILL JPEG" description="JPEG-bild" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-mhtml/" name="XLS TILL MHTML" description="Arkivformat för webbsidor" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-ods/" name="XLS TILL ODS" description="OpenDocument Spreadsheet File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-pdf/" name="XLS TILL PDF" description="Portabelt dokumentformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-png/" name="XLS TILL PNG" description="Bärbar nätverksgrafik" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-svg/" name="XLS TILL SVG" description="Skalbar vektorgrafik" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-tiff/" name="XLS TILL TIFF" description="Taggad bildformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-tsv/" name="XLS TILL TSV" description="Tab-separerade värden" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-txt/" name="XLS TILL TXT" description="Textdokument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-xlsb/" name="XLS TILL XLSB" description="Binär Excel arbetsbok fil" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-xlsm/" name="XLS TILL XLSM" description="Kalkylbladsfil" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-xlsx/" name="XLS TILL XLSX" description="OOXML Excel-fil" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-xlt/" name="XLS TILL XLT" description="Microsoft Excel-mall" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-xltm/" name="XLS TILL XLTM" description="Excel Macro-aktiverad mall" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-xltx/" name="XLS TILL XLTX" description="Office OpenXML Excel-mall" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-xps/" name="XLS TILL XPS" description="XML-pappersspecifikationer" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-json/" name="XLS TILL JSON" description="JavaScript-objektnotation" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}