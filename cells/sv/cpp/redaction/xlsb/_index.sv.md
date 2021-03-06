---
title: Sök och ersätt text i XLSB-dokument via C++ 
weight: 6660
url: /sv/cpp/redaction/xlsb/ 
description: C++ exempelkod för att redigera känslig information i XLSB-filen i C++ Runtime Environment för Windows 32-bitars, Windows 64-bitars och Linux 64-bitars.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Redigera XLSB-format i C++" h2="Inbyggd och högpresterande XLSB-dokumentkänslig redaktionsinformation med hjälp av Aspose.Cells på serversidan för C++ API:er, utan användning av någon programvara som Microsoft eller Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLSB" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Så här redigerar du XLSB-fil med C++" %}}

 För att redigera XLSB-fil kommer vi att använda
 [Aspose.Cells för C++](https://products.aspose.com/cells/cpp) 
 API som är en funktionsrik, kraftfull och lättanvänd dokumentredigering API för C++-plattformen. Du kan ladda ner den senaste versionen direkt, bara öppna
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 pakethanterare, sök efter
 **Aspose.Cells.Cpp** 
 och installera. Du kan också använda följande kommando från Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Kommando" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Steg för att redigera XLSB-filer i C++" %}}

{{% blocks/products/pf/agp/text %}}

 En grundläggande dokumentsökning och ersätt text i innehåll, kommentarer eller metadata med
 [Aspose.Cells för C++](https://products.aspose.com/cells/cpp) 
 API:er kan göras med bara några rader kod.

{{% /blocks/products/pf/agp/text %}}

+ Ladda XLSB-fil.
+ Definiera ersättningsalternativ.
+ Ställ in skiftlägeskänslighet.
+ Ställ in textmatchningsalternativ
+ Ersätt text med metoden Ersätt(...).
+ Spara arbetsboken.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Systemkrav" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells för C++ stöds på alla större plattformar och operativsystem. Se till att du har följande förutsättningar.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows eller ett kompatibelt operativsystem med C++ Runtime Environment för Windows 32-bitars, Windows 64-bitars och Linux 64-bitars.- Aspose.Cells för C++ DLL som refereras till i ditt projekt.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Redigera XLSB-filer - C++" offSpacer="" %}}

```cs
// Källkatalogens sökväg.
StringPtr srcDir = new String("SourceFolder\\");

// Utdatakatalogsökväg.
StringPtr outDir = new String("OutputFolder\\");

// Ladda XLSB-fil
intrusive_ptr<IWorkbook>  workbook = Factory::CreateIWorkbook(srcDir->StringAppend(new String("book1.xlsb")));

// Skapa en instans av klassen IReplaceOptions
intrusive_ptr<IReplaceOptions> replaceOptions = Factory::CreateIReplaceOptions();

// Ställ in skiftlägeskänslighet
replaceOptions->SetCaseSensitive(false);

// Ställ in textmatchningsalternativ
replaceOptions->SetMatchEntireCellContents(false);

// Byt ut text
workbook->Replace(new String("Text to find"), new String("Text replacement"), replaceOptions);

// Spara som XLSB-fil
workbook->Save(outDir->StringAppend(new String("book1_out.xlsb")));


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="Ungefär Aspose.Cells för C++ API" %}}

 Aspose.Cells API kan användas för att skapa, redigera, konvertera och återge Microsoft Excel-format till olika format. Dessutom kan den användas för omfattande kartläggning, skalbar rapportering och tillförlitliga beräkningar inom mjukvaruapplikationer. Aspose.Cells är en fristående API och kräver ingen programvara som Microsoft eller OpenOffice.  



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="Online XLSB Redaction Live Demos" sectionDescription="Sök och ersätt text i innehåll, kommentarer eller metadata i XLSB-dokument just nu genom att besöka vår [Live Demos webbplats](https://products.aspose.app/cells/redaction). Livedemon har följande fördelar" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Du behöver inte ladda ned Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Du behöver inte skriva någon kod." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Ladda bara upp dina XLSB-filer." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Den kommer att redigeras omedelbart." >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSB" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsb/" >}}
XLSB-filformatet anger det binära filformatet för Excel, som är en samling poster och strukturer som anger innehållet i Excel-arbetsboken. Innehållet kan innehålla ostrukturerade eller semistrukturerade tabeller med siffror, text, eller både siffror och text, formler, externa dataanslutningar, diagram och bilder. Till skillnad från XLSX (som är baserat på Open XML-filformat), representerar XLSB en binär Excel-arbetsboksfil. XLSB-filer kan läsas och skrivas till snabbare vilket gör dem användbara för att arbeta med stora filer. XLSB används sällan för att lagra arbetsböcker eftersom XLSX (och tidigare XLS) är de vanligaste användarvalda filformaten för att spara arbetsböcker. Den kan öppnas av Microsoft Office 2007 och senare. 

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andra stödda redigeringsdokument" subTitle="Med C++ kan man enkelt redigera olika format inklusive." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/redaction/ods/" name="ODS" description="OpenDocument Spreadsheet File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/redaction/xls/" name="XLS" description="Excel binärt format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/redaction/xlsm/" name="XLSM" description="Kalkylbladsfil" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}