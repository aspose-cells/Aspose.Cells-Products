---
title: Konvertera TXT till TIFF via appen C++ 
url: /sv/cpp/conversion/txt-to-tiff/ 
description: Exempel på C++-konverteringskod för TXT-dokument till TIFF-format. Programmerare kan använda den här källkoden för batchkonvertering av TXT till TIFF inom alla C++-program.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Konvertera TXT till TIFF via C++" h2="Högpresterande TXT till TIFF-konvertering med hjälp av C++-biblioteket utan behov av Microsoft Excel, OpenOffice eller Adobe Acrobat-installation." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="TIFF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="TXT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Så här konverterar du TXT till TIFF med C++" %}}

 För att konvertera TXT till TIFF kommer vi att använda
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

{{% blocks/products/pf/agp/feature-section-col title="Steg för att konvertera TXT till TIFF via C++" %}}

{{% blocks/products/pf/agp/text %}}

 C++-utvecklare kan enkelt konvertera TXT-fil till TIFF på bara några rader kod.

{{% /blocks/products/pf/agp/text %}}

1. Ladda TXT-fil med Factory::CreateIWorkbook.1. Välj det första kalkylbladet.1. Ställ in (TIFF) alternativ.1. Iterera genom varje sida av arket och rendera.1. Öppna TIFF-filen i ett kompatibelt program.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Systemkrav" %}}

{{% blocks/products/pf/agp/text %}}

 Innan du kör C++ omvandlingsexempelkoden, se till att du har följande förutsättningar.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows eller ett kompatibelt operativsystem med C++ Runtime Environment för Windows 32-bitars, Windows 64-bitars och Linux 64-bitars.- Aspose.Cells för C++ DLL som refereras till i ditt projekt.
- Microsoft Windows eller ett kompatibelt operativsystem med C++ Runtime Environment för Windows 32-bitars, Windows 64-bitars och Linux 64-bitars.- Aspose.Cells för C++ DLL som refereras till i ditt projekt.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="TXT till TIFF C++ omvandlingskällkod" offSpacer="" %}}

```cs
// Utdatakatalogsökväg.
StringPtr outDir = new String("OutputDirectoryPath");

// Ladda TXT.
intrusive_ptr<Aspose::Cells::IWorkbook> workbook = Factory::CreateIWorkbook(u"sourceFile.txt");

// Öppna första kalkylbladet.
intrusive_ptr<Aspose::Cells::IWorksheet> worksheet = workbook->GetIWorksheets()->GetObjectByIndex(0);

// Skapa bild- eller utskriftsalternativ.
intrusive_ptr<Aspose::Cells::Rendering::IImageOrPrintOptions> imgOptions = Factory::CreateIImageOrPrintOptions();

// Ange bildformat.
imgOptions->SetImageFormat(Aspose::Cells::Systems::Drawing::Imaging::ImageFormat::GetTiff());

// Ange horisontell och vertikal upplösning
imgOptions->SetHorizontalResolution(200);
imgOptions->SetVerticalResolution(200);

// Rendera arket med hänsyn till angivna bild- eller utskriftsalternativ.
intrusive_ptr<Aspose::Cells::Rendering::ISheetRender> sr = Factory::CreateISheetRender(worksheet, imgOptions);

// Få sidantal.
Aspose::Cells::Systems::Int32 pageCount = sr->GetPageCount();

// Skapa strängbyggarobjekt för strängsammansättningar.
intrusive_ptr<Aspose::Cells::Systems::Text::StringBuilder> sb = new Aspose::Cells::Systems::Text::StringBuilder();

// Gör varje sida till tiff-bild en efter en.
for (int i = 0; i Clear();
	sb->Append(outDir);
	sb->Append((StringPtr)new String("outputConvertingWorksheetToImageTIFF_"));
	sb->Append(i);
	sb->Append((StringPtr)new String(".tiff"));

	// Hämta utdatabildens sökväg.
	StringPtr outputTIFF = sb->ToString();

	// Konvertera kalkylblad till tiff-bild.
	sr->ToImage(i, outputTIFF);
}


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="TXT till TIFF Conversion Live Demos" sectionDescription="[Konvertera TXT till TIFF](https://products.aspose.app/cells/conversion/txt-to-tiff) just nu genom att besöka vår Live Demos-webbplats. Livedemon har följande fördelar" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Du behöver inte ladda ned Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Du behöver inte skriva någon kod." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Ladda bara upp din TXT-fil, den kommer omedelbart att konverteras till TIFF." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Du kommer att få nedladdningslänken." >}}

    {{% blocks/products/pf/agp/content h2="C++ Excel-filhanteringsbibliotek" %}}

 Excel API kan användas för att skapa, redigera, konvertera och återge Microsoft Excel-format till olika format. Dessutom kan den användas för omfattande kartläggning, skalbar rapportering och tillförlitliga beräkningar inom mjukvaruapplikationer. Aspose.Cells är en fristående API och kräver ingen programvara som Microsoft eller OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="TXT" readMoreLink="https://docs.fileformat.com/word-processing/txt/" >}}

En fil med tillägget .TXT representerar ett textdokument som innehåller vanlig text i form av rader. Stycken i ett textdokument känns igen av vagnreturer och används för bättre arrangemang av filinnehåll. Ett standardtextdokument kan öppnas i alla textredigerare eller ordbehandlingsprogram på olika operativsystem. All text som finns i en sådan fil är i läsbart format och representeras av teckensekvenser.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="TIFF" readMoreLink="https://docs.fileformat.com/image/tiff/" >}}

TIFF eller TIF, Tagged Image File Format, representerar rasterbilder som är avsedda för användning på en mängd olika enheter som överensstämmer med denna filformatstandard. Den kan beskriva bilevel-, gråskala-, palett-färg- och fullfärgsbilddata i flera färgrymder. Den stöder såväl förlustfria som förlustfria komprimeringssystem för att välja mellan utrymme och tid för applikationer som använder formatet. Formatet är utbyggbart och har genomgått flera revisioner som tillåter inkludering av en obegränsad mängd privat information eller information för speciella ändamål. Formatet är inte maskinberoende och är fritt från gränser som processor, operativsystem eller filsystem.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}