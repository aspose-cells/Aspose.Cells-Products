---
title: Lås upp XLS-dokument via .NET 
weight: 4260
url: /sv/net/unlock/xls/ 
description: C# källkod för att låsa upp lösenordsskyddad XLS-fil på .NET Framework, .NET Core, Mono eller Xamarin-plattformar.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Lås upp XLS-kalkylark via C#" h2="Ta bort skyddet från XLS med .NET-biblioteket." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLS" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Så här låser du upp XLS-fil med C#" %}}

 För att ta bort skydds XLS-fil kommer vi att använda
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API som är ett funktionsrikt, kraftfullt och lättanvänt dokumentskydd API för C#-plattformen. Öppen
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 pakethanterare, sök efter
 **Aspose.Cells** 
 och installera. Du kan också använda följande kommando från Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Aspose.Cells" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Lås upp XLS via C#" %}}

{{% blocks/products/pf/agp/text %}}

 Du behöver
 [aspose.cells.dll](https://downloads.aspose.com/cells/net) 
 refereras i ditt projekt för att utföra följande arbetsflöde.

{{% /blocks/products/pf/agp/text %}}

1. Instantiera Workbook-klass med sökväg till skyddad XLS-fil1. Skaffa standard eller valfritt kalkylblad för att ta bort skyddet1. Ta bort kalkylbladsskydd med metoden Worksheet.Unprotect1. Ta bort Workbook-skyddet med Workbook.Unprotect-metoden1. Spara resultatet i XLS-format
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Systemkrav" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for .NET stöds på alla större operativsystem. Se bara till att du har följande förutsättningar.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows eller ett kompatibelt operativsystem med .NET Framework, .NET Core, Mono eller Xamarin-plattformar- Utvecklingsmiljö som Microsoft Visual Studio- Aspose.Cells for .NET refereras till i ditt projekt
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Kommando" offSpacer="" %}}

```cs

// instansiera ett arbetsboksobjekt med skyddad XLS-fil
var workbook = new Aspose.Cells.Workbook("protected.xls");

// komma åt standardkalkylbladet i Excel-filen
var worksheet = workbook.Worksheets[0];

// avskydda kalkylblad utan lösenord
worksheet.Unprotect();

// avskydda arbetsboken med lösenord
workbook.Unprotect("password");

// spara resultatet tillbaka i XLS-format
workbook.Save("unprotected.xls", Aspose.Cells.SaveFormat.Auto);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Om Aspose.Cells for .NET API" %}}

 Aspose.Cells API kan användas för att skapa, redigera, konvertera och återge Microsoft Excel-format till olika format. Dessutom kan den användas för omfattande kartläggning, skalbar rapportering och tillförlitliga beräkningar inom mjukvaruapplikationer. Aspose.Cells är en fristående API och kräver ingen programvara som Microsoft eller OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Gratis app för att låsa upp XLS" sectionDescription="Kolla våra livedemos för att [låsa upp XLS-filer](https://products.aspose.app/cells/unlock/xls) med följande förmåner." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Du behöver inte ladda ner eller ställa in någonting" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Inget behov av att skriva eller kompilera kod" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Ladda bara upp XLS-fil och tryck på knappen \"Lås upp\"." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Ladda ner den resulterande XLS-filen från länken" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}
Filer med XLS-tillägg representerar Excel Binary File Format. Sådana filer kan skapas av Microsoft Excel såväl som andra liknande kalkylprogram som OpenOffice Calc eller Apple Numbers. Fil som sparas av Excel kallas arbetsbok där varje arbetsbok kan ha ett eller flera kalkylblad. Data lagras och visas för användare i tabellformat i kalkylblad och kan sträcka sig över numeriska värden, textdata, formler, externa dataanslutningar, bilder och diagram. Applikationer som Microsoft Excel låter dig exportera arbetsboksdata till flera olika format inklusive PDF, CSV, XLSX, TXT, HTML, XPS och flera andra. XLS-filformatet ersattes med ett mer öppet och strukturerat format, XLSX, med lanseringen av Microsoft Excel 2007. De senaste versionerna ger fortfarande stöd för att skapa och läsa XLS-filer, även om XLSX är förstahandsvalet för användning nu.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andra upplåsningsformat som stöds" subTitle="Med hjälp av C# kan man enkelt ta bort skydd/upplåsning av olika format inklusive." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/unlock/ods/" name="ODS" description="OpenDocument Spreadsheet File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/unlock/xlsb/" name="XLSB" description="Binär Excel arbetsbok fil" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/unlock/xlsm/" name="XLSM" description="Kalkylbladsfil" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/unlock/xlsx/" name="XLSX" description="OOXML Excel-fil" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}