---
title: Lås upp XLSB-dokument via Java 
weight: 5860
url: /sv/java/unlock/xlsb/ 
description: Java exempelkod för att låsa upp lösenordsskyddad XLSB-fil i Java Runtime Environment för JSP/JSF Application och Desktop Applications.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Lås upp XLSB-filer via Java" h2="Ta bort skyddet från Excel-kalkylark inklusive XLSB-fil med hjälp av Java Library." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSB" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSB" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Så här tar du bort skyddsfilen XLSB med Java" %}}

 För att låsa upp XLSB-fil kommer vi att använda
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API som är en funktionsrik, kraftfull och lättanvänd skyddsplattform API for Java. Du kan ladda ner den senaste versionen direkt från
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

{{% blocks/products/pf/agp/feature-section-col title="Steg för att låsa upp XLSB via Java" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. Instantiera Workbook-klass med sökväg till skyddad XLSB-fil1. Skaffa standard eller valfritt kalkylblad för att ta bort skyddet1. Ta bort kalkylbladsskydd med metoden Worksheet.Unprotect1. Ta bort Workbook-skyddet med Workbook.Unprotect-metoden1. Spara resultatet i XLSB-format
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Systemkrav" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java stöds på alla större plattformar och operativsystem. Se till att du har följande förutsättningar.

{{% /blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Lås upp XLSB-filer via C#" offSpacer="" %}}

```cs

Workbook wkb = new Workbook("source.xlsb");

WorksheetCollection wksc = wkb.getWorksheets();
Worksheet wks = wksc.get(0);

// Avskydda XLSB
wks.unprotect();

// Spara XLSB-filen.
wkb.save("Worksheet_out.xlsb", FileFormatType.EXCEL_97_TO_2003);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Om Aspose.Cells for Java API" %}}

 Aspose.Cells API kan användas för att skapa, redigera, konvertera och återge Microsoft Excel-format till olika format. Dessutom kan den användas för omfattande kartläggning, skalbar rapportering och tillförlitliga beräkningar inom mjukvaruapplikationer. Aspose.Cells är en fristående API och kräver ingen programvara som Microsoft eller OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Gratis app för att låsa upp XLSB" sectionDescription="Kolla våra livedemos för att [låsa upp XLSB-filer](https://products.aspose.app/cells/unlock/xlsb) med följande förmåner." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Du behöver inte ladda ner eller ställa in någonting" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Inget behov av att skriva eller kompilera kod" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Ladda bara upp XLSB-filen och tryck på knappen \"Lås upp\"." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Ladda ner den resulterande XLSB-filen från länken" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSB" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsb/" >}}
XLSB-filformatet anger det binära filformatet för Excel, som är en samling poster och strukturer som anger innehållet i Excel-arbetsboken. Innehållet kan innehålla ostrukturerade eller semistrukturerade tabeller med siffror, text, eller både siffror och text, formler, externa dataanslutningar, diagram och bilder. Till skillnad från XLSX (som är baserat på Open XML-filformat), representerar XLSB en binär Excel-arbetsboksfil. XLSB-filer kan läsas och skrivas till snabbare vilket gör dem användbara för att arbeta med stora filer. XLSB används sällan för att lagra arbetsböcker eftersom XLSX (och tidigare XLS) är de vanligaste användarvalda filformaten för att spara arbetsböcker. Den kan öppnas av Microsoft Office 2007 och senare.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andra upplåsningsformat som stöds" subTitle="Med hjälp av Java kan man enkelt ta bort skydd/upplåsning av olika format inklusive." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/unlock/ods/" name="ODS" description="OpenDocument Spreadsheet File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/unlock/xls/" name="XLS" description="Excel binärt format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/unlock/xlsm/" name="XLSM" description="Kalkylbladsfil" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/unlock/xlsx/" name="XLSX" description="OOXML Excel-fil" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}