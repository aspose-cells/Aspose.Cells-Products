---
title: Konvertera SPREADSHEETML till DIF via applikationen C++ 
url: /sv/cpp/conversion/spreadsheetml-to-dif/ 
description: Exempel på konverteringskod för C++ för SPREADSHEETML-dokument till DIF-format. Programmerare kan använda den här källkoden för batch-SPREADSHEETML till DIF-konvertering inom alla C++-program.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Konvertera SPREADSHEETML till DIF via C++" h2="Högpresterande SPREADSHEETML till DIF-konvertering med hjälp av C++-biblioteket utan behov av installation av Microsoft Excel, OpenOffice eller Adobe Acrobat." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="DIF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="SPREADSHEETML" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Så här konverterar du SPREADSHEETML till DIF med C++" %}}

 För att konvertera SPREADSHEETML till DIF kommer vi att använda
 [Aspose.Cells för C++](https://products.aspose.com/cells/cpp) 
 API som är en funktionsrik, kraftfull och lättanvänd dokumenthantering och konvertering API för C++-plattformen. Du kan ladda ner den senaste versionen direkt, bara öppna
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 pakethanterare, sök efter
 Aspose.Cells.Cpp 
 och installera. Du kan också använda följande kommando från Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Kommando" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Steg för att konvertera SPREADSHEETML till DIF via C++" %}}

{{% blocks/products/pf/agp/text %}}

 C++-utvecklare kan enkelt konvertera SPREADSHEETML-filen till DIF på bara några rader kod.

{{% /blocks/products/pf/agp/text %}}

1. Ladda SPREADSHEETML-fil med Factory::CreateIWorkbook.1. Anropa metoden Save().1. Skicka utdatafilens sökväg med (DIF) filtillägg.1. DIF-filen kommer att sparas på den angivna sökvägen.1. Öppna DIF-filen i ett kompatibelt program.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Systemkrav" %}}

{{% blocks/products/pf/agp/text %}}

 Innan du kör C++ omvandlingsexempelkoden, se till att du har följande förutsättningar.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows eller ett kompatibelt operativsystem med C++ Runtime Environment för Windows 32-bitars, Windows 64-bitars och Linux 64-bitars.- Aspose.Cells för C++ DLL som refereras till i ditt projekt.
- Microsoft Windows eller ett kompatibelt operativsystem med C++ Runtime Environment för Windows 32-bitars, Windows 64-bitars och Linux 64-bitars.- Aspose.Cells för C++ DLL som refereras till i ditt projekt.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="SPREADSHEETML till DIF C++ konverteringskällkod" offSpacer="" %}}

```cs
// Ladda Kalkylbladet.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.spreadsheetml");

// Spara i DIF-format.
wkb->Save(u"convertedFile.dif", SaveFormat_Dif);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="SPREADSHEETML till DIF Conversion Live Demos" sectionDescription="[Konvertera SPREADSHEETML till DIF](https://products.aspose.app/cells/conversion/spreadsheetml-to-dif) just nu genom att besöka vår Live Demos-webbplats. Livedemon har följande fördelar" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Du behöver inte ladda ned Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Du behöver inte skriva någon kod." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Ladda bara upp din SPREADSHEETML-fil, den konverteras omedelbart till DIF." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Du kommer att få nedladdningslänken." >}}

    {{% blocks/products/pf/agp/content h2="C++ Excel-filhanteringsbibliotek" %}}

 Excel API kan användas för att skapa, redigera, konvertera och återge Microsoft Excel-format till olika format. Dessutom kan den användas för omfattande kartläggning, skalbar rapportering och tillförlitliga beräkningar inom mjukvaruapplikationer. Aspose.Cells är en fristående API och kräver ingen programvara som Microsoft eller OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="SPREADSHEETML" readMoreLink="/{{spreadsheetml_url}}" >}}

{{spreadsheetml}}

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="DIF" readMoreLink="https://docs.fileformat.com/spreadsheet/dif/" >}}

DIF står för Data Interchange Format som används för att importera/exportera kalkylbladsdata mellan olika applikationer. Dessa inkluderar Microsoft Excel, OpenOffice Calc, StarCalc och många andra. Den lagrar data som finns i ett enda kalkylblad vilket är den enda begränsningen för detta filformat.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}