---
title:  Skydda och lås ODS dokument via .NET
weight: 5580
description: C# källkod för att låsa filen ODS med lösenord på .NET Framework, .NET Core, Mono eller Xamarin Platforms.
keywords: [C# Aspose.Cells., c# Lock ODS files., c# How to Protect and lock ODS document., c# Protect ODS files., Encrypt ODS Files using C#]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Kryptera ODS filer via C#" h2="Lösenordsskydda Excel-kalkylblad inklusive ODS-format med .NET Library." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODS" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="ODS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Hur man skyddar ODS-fil med C#" %}}

 För att skydda ODS-filen kommer vi att använda
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API som är en funktionsrik, kraftfull och lättanvänd dokumentskydd API för C# plattform. Öppen
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

{{% blocks/products/pf/agp/feature-section-col title="Skydda ODS via C#" %}}

{{% blocks/products/pf/agp/text %}}

 Du behöver
 [aspose.cells.dll](https://downloads.aspose.com/cells/net) 
 refereras i ditt projekt för att utföra följande arbetsflöde.

{{% /blocks/products/pf/agp/text %}}

1.  Instantiera Workbook-klass med sökväg till ODS-fil
1.  Skaffa standard eller valfritt kalkylblad för att lägga till skydd
1.  Skydda kalkylblad med arbetsblad.Protect-metoden
1.  Skydda Workbook med Workbook.Protect-metoden
1.  Spara resultatet i formatet ODS

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Systemkrav" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for .NET stöds på alla större operativsystem. Se bara till att du har följande förutsättningar.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows eller ett kompatibelt operativsystem med .NET Framework, .NET Core, Mono eller Xamarin Platforms
-  Utvecklingsmiljö som Microsoft Visual Studio
-  Lägg till referens till Aspose.Cells for .NET DLL i ditt projekt

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Kommando" offSpacer="" %}}

```cs

// load the ODS Excel file 
var book = new Aspose.Cells.Workbook("unlocked.ods");

// access the first worksheet
var worksheet = book.Worksheets[0];

// protect the worksheet with password
worksheet.Protect(Aspose.Cells.ProtectionType.All, "password", null);

// protect the whole workbook with password
book.Protect(Aspose.Cells.ProtectionType.All, "password");

// save the modified file in default format
book.Save("protected.ods");

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Om Aspose.Cells for .NET API" %}}

 Aspose.Cells API kan användas för att skapa, redigera, konvertera och rendera Microsoft Excel-format till olika format. Dessutom kan den användas för omfattande kartläggning, skalbar rapportering och tillförlitliga beräkningar inom mjukvaruapplikationer. Aspose.Cells är en fristående API och den kräver ingen programvara som Microsoft eller OpenOffice.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Gratis app för att skydda ODS" sectionDescription=" Kolla våra livedemos för att[kryptera ODS-filer](https://products.aspose.app/cells/protect/ods) med följande förmåner." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Du behöver inte ladda ner eller ställa in någonting" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Inget behov av att skriva eller kompilera kod" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Ladda bara upp filen ODS och tryck på knappen \"Lås upp\"." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Ladda ner den resulterande ODS-filen från länken" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODS" readMoreLink="https://docs.fileformat.com/spreadsheet/ods/" >}}
Filer med tillägget ODS står för OpenDocument Spreadsheet Document-format som kan redigeras av användaren. Data lagras i ODF-filen i rader och kolumner. Det är XML-baserat format och är en av flera undertyper i familjen Open Document Formats (ODF). Formatet specificeras som en del av ODF 1.2-specifikationerna som publiceras och underhålls av OASIS. Ett antal applikationer på Windows såväl som andra operativsystem kan öppna ODS-filer för redigering och manipulering, inklusive Microsoft Excel, NeoOffice och LibreOffice. ODS-filer kan också konverteras till andra kalkylbladsformat, liksom XLS, XLSX och andra av olika applikationer.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andra skyddsformat som stöds" subTitle="Med C# kan man enkelt skydda andra format inklusive." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/xls/" name="XLS" description="Excel binärt format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/xlsb/" name="XLSB" description="Binär Excel arbetsbok fil" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/xlsm/" name="XLSM" description="Kalkylbladsfil" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/xlsx/" name="XLSX" description="OOXML Excel-fil" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
