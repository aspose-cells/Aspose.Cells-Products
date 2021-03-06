---
title: Konvertera XLS till JPEG via Java 
weight: 8280
url: /sv/java/conversion/xls-to-jpeg/ 
description: Exempel Java-konverteringskod för XLS-format till JPEG-fil. Programmerare kan använda den här exempelkoden för att exportera Excel- och OpenOffice-kalkylblad till JPEG inom alla webb- eller skrivbordsbaserade Java-applikationer.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Konvertera XLS till JPEG via Java" h2="XLS till JPEG Java-konvertering för att konvertera enstaka eller flera sidor till JPEG med hjälp av lokalt Java-bibliotek." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="JPEG" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Så här konverterar du XLS till JPEG med Java" %}}

 För att rendera XLS till JPEG kommer vi att använda
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

{{% blocks/products/pf/agp/feature-section-col title="Steg för att konvertera XLS till JPEG via Java" %}}

{{% blocks/products/pf/agp/text %}}

 Java-utvecklare kan enkelt konvertera XLS-fil till JPEG på bara några rader kod.

{{% /blocks/products/pf/agp/text %}}

1. Ladda XLS-fil med en instans av Workbook1. Välj standard eller valfritt kalkylblad från samlingen1. Skapa och ställ in objektet för ImageOrPrintOptions1. Skapa SheetRender med Worksheet & ImageOrPrintOptions-objekt1. Ring SheetRender.toImage-metoden för att spara resultatet i JPEG-format
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Systemkrav" %}}

{{% blocks/products/pf/agp/text %}}

 Innan du kör källkoden för omvandlingen Java, se till att du har följande förutsättningar.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows eller ett kompatibelt operativsystem med Java Runtime Environment för JSP/JSF Application och Desktop Applications.- Hämta den senaste versionen av Aspose.Cells for Java direkt från Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XLS till JPEG Java omvandlingskällkod" offSpacer="" %}}

```cs
// ladda XLS-filen som ska renderas
Workbook workbook = new Workbook("sourceFile.xls");
// komma åt standardkalkylbladet från samlingen
Worksheet worksheet = workbook.getWorksheets().get(0);
// definiera parametrar för den resulterande bilden
ImageOrPrintOptions options = new ImageOrPrintOptions();
options.setOnePagePerSheet(true);
options.setImageType(ImageType.JPEG);
// konvertera kalkylblad till bild i JPEG-format
SheetRender renderer = new SheetRender(worksheet, options);
renderer.toImage(0, "output.jpeg");   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="XLS till JPEG Conversion Live Demos" sectionDescription="[Konvertera XLS till JPEG](https://products.aspose.app/cells/conversion/xls-to-jpeg) just nu genom att besöka vår Live Demos-webbplats. Livedemon har följande fördelar" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Du behöver inte ladda ned Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Du behöver inte skriva någon kod." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Ladda bara upp din XLS-fil, den konverteras omedelbart till JPEG." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Du kommer att få nedladdningslänken." >}}

    {{% blocks/products/pf/agp/content h2="Java Kalkylarksmanipulationsbibliotek" %}}

 Excel API kan användas för att skapa, redigera, konvertera och återge Microsoft Excel-format till olika format. Dessutom kan den användas för omfattande kartläggning, skalbar rapportering och tillförlitliga beräkningar inom mjukvaruapplikationer. Aspose.Cells är en fristående API och kräver ingen programvara som Microsoft eller OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}

Filer med XLS-tillägg representerar Excel Binary File Format. Sådana filer kan skapas av Microsoft Excel såväl som andra liknande kalkylprogram som OpenOffice Calc eller Apple Numbers. Fil som sparas av Excel kallas arbetsbok där varje arbetsbok kan ha ett eller flera kalkylblad. Data lagras och visas för användare i tabellformat i kalkylblad och kan sträcka sig över numeriska värden, textdata, formler, externa dataanslutningar, bilder och diagram. Applikationer som Microsoft Excel låter dig exportera arbetsboksdata till flera olika format inklusive PDF, CSV, XLSX, TXT, HTML, XPS och flera andra. XLS-filformatet ersattes med ett mer öppet och strukturerat format, XLSX, med lanseringen av Microsoft Excel 2007. De senaste versionerna ger fortfarande stöd för att skapa och läsa XLS-filer, även om XLSX är förstahandsvalet för användning nu.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="JPEG" readMoreLink="https://docs.fileformat.com/image/jpeg/" >}}

En JPEG är en typ av bildformat som sparas med metoden för förlustkomprimering. Utdatabilden, som ett resultat av komprimering, är en kompromiss mellan lagringsstorlek och bildkvalitet. Användare kan justera komprimeringsnivån för att uppnå önskad kvalitetsnivå samtidigt som lagringsstorleken minskas. Bildkvaliteten påverkas försumbart om 10:1-komprimering tillämpas på bilden. Ju högre komprimeringsvärde, desto högre försämring i bildkvalitet. JPEG-bildfilformatet standardiserades av Joint Photographic Experts Group och därav namnet JPEG. Formatet har varit valet av att lagra och överföra fotografiska bilder på webben. Nästan alla operativsystem har nu tittare som stöder visualisering av JPEG-bilder, som ofta också lagras med JPG-tillägg. Även webbläsarna stöder visualisering av JPEG-bilder.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andra omvandlingar som stöds" subTitle="Du kan också konvertera XLS till många andra filformat inklusive några som anges nedan." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-bmp/" name="XLS TILL BMP" description="Bitmappsbild" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-csv/" name="XLS TILL CSV" description="Kommaseparerade värden" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-dif/" name="XLS TILL DIF" description="Datautbytesformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-emf/" name="XLS TILL EMF" description="Förbättrat metafilformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-gif/" name="XLS TILL GIF" description="Grafiskt utbytesformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-html/" name="XLS TILL HTML" description="Hyper Text Markup Language" >}}
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