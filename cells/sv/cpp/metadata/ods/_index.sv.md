---
title: Redigera eller visa ODS-dokumentmetadata via C++ 
weight: 1000
url: /sv/cpp/metadata/ods/ 
description: C++ exempelkod för att redigera eller visa ODS-filmetadata i C++ Runtime Environment för Windows 32-bitars, Windows 64-bitars och Linux 64-bitars.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Extrahera ODS-metadata via C++" h2="Bygg dina egna C++-appar för att lägga till, redigera, ta bort eller extrahera metadata från ODS-filer med hjälp av API:er på serversidan." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODS" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Så här hämtar du ODS-metadata med C++" %}}

 För att extrahera ODS-metadata kommer vi att använda
 [Aspose.Cells för C++](https://products.aspose.com/cells/cpp) 
 API som är en funktionsrik, kraftfull och lättanvänd dokumentmetadataextraktion API för C++-plattformen. Du kan ladda ner den senaste versionen direkt, bara öppna
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

{{% blocks/products/pf/agp/feature-section-col title="Steg för att extrahera metadata för ODS via C++" %}}

{{% blocks/products/pf/agp/text %}}

 Få tillgång till användbar information som lagras i ODS-filen inklusive när ODS-filen togs emot, bearbetades, tidsstämplad och så vidare.

{{% /blocks/products/pf/agp/text %}}

+ Ladda ODS-fil med CreateIWorkbookMetadata
+ Skapa alternativ med CreateIMetadataOptions
+ Lägg till nya egenskaper med GetICustomDocumentProperties() och AddIDocumentProperty
+ Spara ODS-dokument

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Systemkrav" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells för C++ stöds på alla större plattformar och operativsystem. Se till att du har följande förutsättningar.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows eller ett kompatibelt operativsystem med C++ Runtime Environment för Windows 32-bitars, Windows 64-bitars och Linux 64-bitars.- Aspose.Cells för C++ DLL som refereras till i ditt projekt.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Extrahera metadata för ODS - C++" offSpacer="" %}}

```cs

intrusive_ptr<IMetadataOptions> options = Factory::CreateIMetadataOptions(MetadataType_DocumentProperties);
intrusive_ptr<IWorkbookMetadata> meta = Factory::CreateIWorkbookMetadata(new String("c:\\book1.ods"), options);
meta->GetICustomDocumentProperties()->AddIDocumentProperty(new String("test"), (StringPtr)new String("test"));
meta->Save(new String("c:\\book2.ods"));  


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Ungefär Aspose.Cells för C++ API" %}}

 Aspose.Cells API kan användas för att skapa, redigera, konvertera och återge Microsoft Excel-format till olika format. Dessutom kan den användas för omfattande kartläggning, skalbar rapportering och tillförlitliga beräkningar inom mjukvaruapplikationer. Aspose.Cells är en fristående API och kräver ingen programvara som Microsoft eller OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Extrahera metadata för ODS via onlineapp" sectionDescription="Visa och redigera metadata till ODS-dokument genom att använda vår [Livedemos](https://products.aspose.app/cells/metadata) med följande förmåner." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Du behöver inte ladda ner eller ställa in någonting" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Du behöver inte skriva någon kod" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Ladda bara upp din ODS-fil och redigera dokumentegenskaper" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Skaffa omedelbart nedladdningslänken för den resulterande filen" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODS" readMoreLink="https://docs.fileformat.com/spreadsheet/ods/" >}}
Filer med ODS-tillägg står för OpenDocument Spreadsheet Document-format som kan redigeras av användaren. Data lagras i ODF-filen i rader och kolumner. Det är XML-baserat format och är en av flera undertyper i familjen Open Document Formats (ODF). Formatet specificeras som en del av ODF 1.2-specifikationerna som publiceras och underhålls av OASIS. Ett antal applikationer på Windows såväl som andra operativsystem kan öppna ODS-filer för redigering och manipulering, inklusive Microsoft Excel, NeoOffice och LibreOffice. ODS-filer kan också konverteras till andra kalkylbladsformat som XLS, XLSX och andra av olika applikationer.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andra metadataformat som stöds" subTitle="Med hjälp av C++ kan man också manipulera metadata i många andra format, inklusive" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/metadata/xls/" name="XLS" description="Excel binärt format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/metadata/xlsb/" name="XLSB" description="Binär Excel arbetsbok fil" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/metadata/xlsm/" name="XLSM" description="Kalkylbladsfil" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/metadata/xlsx/" name="XLSX" description="OOXML Excel-fil" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}