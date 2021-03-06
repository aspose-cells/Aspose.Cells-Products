---
title: Skapa HTML-filer via Java 
url: /sv/java/create-html/ 
description: Java Exempelkod för att generera HTML-dokument. Använd den här koden för att skapa HTML-filer inom Java-baserade skrivbords- eller webbapplikationer.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Skapa HTML-dokument via Java" h2="Native och högpresterande HTML (Hyper Text Markup Language) skapas programmatiskt med hjälp av Java-biblioteket." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="HTML" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="" %}}

 Det är enkelt att generera HTML-fil dynamiskt i ett program som körs. För att skapa HTML-dokument från grunden utan att behöva MS Office, kommer vi att använda
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API som erbjuder olika funktioner för att skapa, manipulera och konvertera kalkylark med hjälp av Java-plattformen. Utvecklare kan enkelt förbättra kod för att uppdatera celldata, generera diagram eller grafer samt skapa pivottabeller, lägga till formler på cellnivå och mer i kalkylblad.
{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Så här skapar du HTML via Java" %}}

{{% blocks/products/pf/agp/text %}}

 Det är lätt för utvecklarna att skapa, ladda, modifiera och konvertera HTML (Hyper Text Markup Language) i att köra olika rapporteringsapplikationer för databehandling på bara några rader kod.

{{% /blocks/products/pf/agp/text %}}

1. Skapa en instans av [Arbetsbok klass](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook).1. Öppna det relevanta kalkylbladet med metoden getWorksheets.get().1. Välj den relevanta cellen, mata in värdet i den önskade cellen med cellnamnet, som A1, B3, etc.1. Spara arbetsboken som HTML-format med metoden save().
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Systemkrav" %}}

{{% blocks/products/pf/agp/text %}}

Innan du kör källkoden för Java omvandlingsexempel, se till att du har följande förutsättningar.  

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows eller ett kompatibelt operativsystem med Java Runtime Environment för JSP/JSF Application och Desktop Applications.- Aspose.Cells for Java stöder följande Java versioner: J2SE 6.0 (1.6), J2SE 7.0 (1.7) eller högre.- [Hämta den senaste versionen av Aspose.Cells for Java direkt från Maven.](https://docs.aspose.com/cells/java/installation/) 
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Följande källkod visar hur du skapar en HTML-fil med Java." offSpacer="" %}}

```cs

// Skapa en ny arbetsbok
Workbook wkb = new Workbook();

// Öppna det första kalkylbladet i arbetsboken.
Worksheet worksheet = wkb.getWorksheets().get(0);

// Lägg till relevant innehåll i cellen
worksheet.getCells().get("A1").putValue("ColumnA");
worksheet.getCells().get("B1").putValue("ColumnB")
worksheet.getCells().get("A2").putValue("ValueA")
worksheet.getCells().get("B2").putValue("ValueB")

// Spara arbetsboken som HTML-fil
wkb.save("Excel.html"); 

// För att förbättra koden för ytterligare funktioner finns här fler funktioner
// getCells() och setValue för att modifiera cellinnehållet
// getCharts().add() för att lägga till diagram
// getPivotTables().add() för att skapa en pivottabell
// getCells().get(int cell id).setFormel för att lägga till cellnivåformel


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<!-- aboutfile Starts -->

     
     {{% blocks/products/pf/agp/content h2="" %}}

 Ett Excel Spreadsheet Programming Library som kan bygga plattformsoberoende applikationer med förmågan att generera, modifiera, konvertera, rendera och skriva ut HTML-filer. Java Excel API konverterar inte bara mellan kalkylarksformat, det kan också återge Excel-filer som bilder, PDF, HTML, ODS och mer, vilket gör det till ett perfekt val för att utbyta dokument i branschstandardformat.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="HTML" readMoreLink="https://docs.fileformat.com/web/html/" >}}

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< /blocks/products/pf/agp/about-file-section >}}

          

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Annan kalkylarksgenerering som stöds" subTitle="Du kan också skapa andra Microsoft Excel-format inklusive några som anges nedan." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create-xls/" name="XLS" description="Microsoft Excel-kalkylblad (legacy)" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create-xlsx/" name="XLSX" description="Öppna XML-arbetsbok" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create-xlsb/" name="XLSB" description="Excel binär arbetsbok" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create-xlsm/" name="XLSM" description="Makroaktiverat kalkylblad" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create-xlt/" name="XLT" description="Excel 97 - 2003 mall" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create-xltx/" name="XLTX" description="Excel-mall" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create-xltm/" name="XLTM" description="Excel-makroaktiverad mall" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create-csv/" name="CSV" description="Kommaseparerade värden" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create-tsv/" name="TSV" description="Flikseparerade värden" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create-ods/" name="ODS" description="OpenDocument Kalkylblad" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
