---
title: Konvertera XLT till XLTX via Java 
weight: 9750
url: /sv/java/conversion/xlt-to-xltx/ 
description: Exempel Java-konverteringskod för XLT-format till XLTX-fil. Programmerare kan använda den här exempelkoden för att exportera Excel- och OpenOffice-kalkylblad till XLTX inom alla webb- eller skrivbordsbaserade Java-applikationer.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Konvertera XLT till XLTX via Java" h2="XLT till XLTX Java-konvertering för att konvertera enstaka eller flera sidor till XLTX med hjälp av lokalt Java-bibliotek." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLTX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Så här konverterar du XLT till XLTX med Java" %}}

 För att rendera XLT till XLTX kommer vi att använda
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

{{% blocks/products/pf/agp/feature-section-col title="Steg för att konvertera XLT till XLTX via Java" %}}

{{% blocks/products/pf/agp/text %}}

 Java-utvecklare kan enkelt konvertera XLT-fil till XLTX på bara några rader kod.

{{% /blocks/products/pf/agp/text %}}

1. Ladda XLT-fil med en instans av Workbook-klassen1. Ring Workbook.save-metoden1. Passera utdatasökväg med XLTX-tillägg och SaveFormat som parametrar1. Kontrollera den angivna sökvägen för den resulterande XLTX-filen
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Systemkrav" %}}

{{% blocks/products/pf/agp/text %}}

 Innan du kör källkoden för omvandlingen Java, se till att du har följande förutsättningar.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows eller ett kompatibelt operativsystem med Java Runtime Environment för JSP/JSF Application och Desktop Applications.- Hämta den senaste versionen av Aspose.Cells for Java direkt från Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XLT till XLTX Java konverteringskällkod" offSpacer="" %}}

```cs
// ladda XLT-filen i en instans av Workbook
Workbook book = new Workbook("template.xlt");
// spara XLT som XLTX
book.save("output.xltx", SaveFormat.AUTO);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="XLT till XLTX Conversion Live Demos" sectionDescription="[Konvertera XLT till XLTX](https://products.aspose.app/cells/conversion/xlt-to-xltx) just nu genom att besöka vår Live Demos-webbplats. Livedemon har följande fördelar" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Du behöver inte ladda ned Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Du behöver inte skriva någon kod." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Ladda bara upp din XLT-fil, den konverteras omedelbart till XLTX." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Du kommer att få nedladdningslänken." >}}

    {{% blocks/products/pf/agp/content h2="Java Kalkylarksmanipulationsbibliotek" %}}

 Excel API kan användas för att skapa, redigera, konvertera och återge Microsoft Excel-format till olika format. Dessutom kan den användas för omfattande kartläggning, skalbar rapportering och tillförlitliga beräkningar inom mjukvaruapplikationer. Aspose.Cells är en fristående API och kräver ingen programvara som Microsoft eller OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLT" readMoreLink="https://docs.fileformat.com/spreadsheet/xlt/" >}}

Filer med filtillägget .XLT är mallfiler skapade med Microsoft Excel som är ett kalkylprogram som ingår i Microsoft Office-paketet. Microsoft Office 97-2003 stödde att skapa nya XLT-filer samt att öppna dessa. Den senaste versionen av Excel kan fortfarande öppna detta gamla formatmallfiler. En sådan mallfil används för att snabbt skapa nya Excel-filer med standarddata och inställningar som sidformatering, teckenstorlek, marginaler, diagram, etc som kan sparas ytterligare som nya .XLS-filer.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLTX" readMoreLink="https://docs.fileformat.com/spreadsheet/xltx/" >}}

Filer med tillägget XLTX representerar Microsoft Excel-mallfiler som är baserade på Office OpenXML-filformatspecifikationerna. Den används för att skapa en standardmallfil som kan användas för att generera XLSX-filer som uppvisar samma inställningar som anges i XLTX-filen.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andra omvandlingar som stöds" subTitle="Du kan också konvertera XLT till många andra filformat, inklusive några som anges nedan." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-bmp/" name="XLT TILL BMP" description="Bitmappsbild" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-csv/" name="XLT TILL CSV" description="Kommaseparerade värden" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-dif/" name="XLT TILL DIF" description="Datautbytesformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-emf/" name="XLT TILL EMF" description="Förbättrat metafilformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-gif/" name="XLT TILL GIF" description="Grafiskt utbytesformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-html/" name="XLT TILL HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-jpeg/" name="XLT TILL JPEG" description="JPEG-bild" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-mhtml/" name="XLT TILL MHTML" description="Arkivformat för webbsidor" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-ods/" name="XLT TILL ODS" description="OpenDocument Spreadsheet File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-pdf/" name="XLT TILL PDF" description="Portabelt dokumentformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-png/" name="XLT TILL PNG" description="Bärbar nätverksgrafik" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-svg/" name="XLT TILL SVG" description="Skalbar vektorgrafik" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-tiff/" name="XLT TILL TIFF" description="Taggad bildformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-tsv/" name="XLT TILL TSV" description="Tab-separerade värden" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-txt/" name="XLT TILL TXT" description="Textdokument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-xlm/" name="XLT TILL XLM" description="Excel makrofil" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-xls/" name="XLT TILL XLS" description="Excel binärt format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-xlsb/" name="XLT TILL XLSB" description="Binär Excel arbetsbok fil" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-xlsx/" name="XLT TILL XLSX" description="OOXML Excel-fil" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-xltm/" name="XLT TILL XLTM" description="Excel Macro-aktiverad mall" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-xps/" name="XLT TILL XPS" description="XML-pappersspecifikationer" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-json/" name="XLT TILL JSON" description="JavaScript-objektnotation" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}