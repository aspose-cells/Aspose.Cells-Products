---
title: Konvertera JSON till EMF via appen C++ 
url: /sv/cpp/conversion/json-to-emf/ 
description: Exempel på konverteringskod för C++ för JSON-dokument till EMF-format. Programmerare kan använda den här källkoden för batchkonvertering av JSON till EMF inom vilken C++-applikation som helst.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Konvertera JSON till EMF via C++" h2="Högpresterande JSON till EMF-konvertering med hjälp av C++-biblioteket utan behov av installation av Microsoft Excel, OpenOffice eller Adobe Acrobat." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="EMF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="JSON" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Så här konverterar du JSON till EMF med C++" %}}

 För att konvertera JSON till EMF kommer vi att använda
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

{{% blocks/products/pf/agp/feature-section-col title="Steg för att konvertera JSON till EMF via C++" %}}

{{% blocks/products/pf/agp/text %}}

 C++-utvecklare kan enkelt konvertera JSON-fil till EMF på bara några rader kod.

{{% /blocks/products/pf/agp/text %}}

1. Ladda JSON-fil med Factory::CreateIWorkbook.1. Välj det första kalkylbladet.1. Ställ in (EMF) alternativ.1. Iterera genom varje sida av arket och rendera.1. Öppna EMF-filen i ett kompatibelt program.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Systemkrav" %}}

{{% blocks/products/pf/agp/text %}}

 Innan du kör C++ omvandlingsexempelkoden, se till att du har följande förutsättningar.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows eller ett kompatibelt operativsystem med C++ Runtime Environment för Windows 32-bitars, Windows 64-bitars och Linux 64-bitars.- Aspose.Cells för C++ DLL som refereras till i ditt projekt.
- Microsoft Windows eller ett kompatibelt operativsystem med C++ Runtime Environment för Windows 32-bitars, Windows 64-bitars och Linux 64-bitars.- Aspose.Cells för C++ DLL som refereras till i ditt projekt.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="JSON till EMF C++ omvandlingskällkod" offSpacer="" %}}

```cs
// Utdatakatalogsökväg.
StringPtr outDir = new String("OutputDirectoryPath");

// Ladda JSON.
intrusive_ptr<Aspose::Cells::IWorkbook> workbook = Factory::CreateIWorkbook(u"sourceFile.json");

// Öppna första kalkylbladet.
intrusive_ptr<Aspose::Cells::IWorksheet> worksheet = workbook->GetIWorksheets()->GetObjectByIndex(0);

// Skapa bild- eller utskriftsalternativ.
intrusive_ptr<Aspose::Cells::Rendering::IImageOrPrintOptions> imgOptions = Factory::CreateIImageOrPrintOptions();

// Ange bildformat.
imgOptions->SetImageFormat(Aspose::Cells::Systems::Drawing::Imaging::ImageFormat::GetEmf());

// Ange horisontell och vertikal upplösning
imgOptions->SetHorizontalResolution(200);
imgOptions->SetVerticalResolution(200);

// Rendera arket med hänsyn till angivna bild- eller utskriftsalternativ.
intrusive_ptr<Aspose::Cells::Rendering::ISheetRender> sr = Factory::CreateISheetRender(worksheet, imgOptions);

// Få sidantal.
Aspose::Cells::Systems::Int32 pageCount = sr->GetPageCount();

// Skapa strängbyggarobjekt för strängsammansättningar.
intrusive_ptr<Aspose::Cells::Systems::Text::StringBuilder> sb = new Aspose::Cells::Systems::Text::StringBuilder();

// Gör varje sida till emf-bild en efter en.
for (int i = 0; i Clear();
	sb->Append(outDir);
	sb->Append((StringPtr)new String("outputConvertingWorksheetToImageEMF_"));
	sb->Append(i);
	sb->Append((StringPtr)new String(".emf"));

	// Hämta utdatabildens sökväg.
	StringPtr outputEMF = sb->ToString();

	// Konvertera kalkylblad till emf-bild.
	sr->ToImage(i, outputEMF);
}


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="JSON till EMF Conversion Live Demos" sectionDescription="[Konvertera JSON till EMF](https://products.aspose.app/cells/conversion/json-to-emf) just nu genom att besöka vår Live Demos-webbplats. Livedemon har följande fördelar" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Du behöver inte ladda ned Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Du behöver inte skriva någon kod." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Ladda bara upp din JSON-fil, den konverteras omedelbart till EMF." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Du kommer att få nedladdningslänken." >}}

    {{% blocks/products/pf/agp/content h2="C++ Excel-filhanteringsbibliotek" %}}

 Excel API kan användas för att skapa, redigera, konvertera och återge Microsoft Excel-format till olika format. Dessutom kan den användas för omfattande kartläggning, skalbar rapportering och tillförlitliga beräkningar inom mjukvaruapplikationer. Aspose.Cells är en fristående API och kräver ingen programvara som Microsoft eller OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="JSON" readMoreLink="https://docs.fileformat.com/web/json/" >}}

JSON (JavaScript Object Notation) är ett öppet standardfilformat för att dela data som använder läsbar text för att lagra och överföra data. JSON-filer lagras med tillägget .json. JSON kräver mindre formatering och är ett bra alternativ för XML. JSON härrör från JavaScript men är ett språkoberoende dataformat. Generering och analys av JSON stöds av många moderna programmeringsspråk. application/json är mediatypen som används för JSON.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="EMF" readMoreLink="https://docs.fileformat.com/image/emf/" >}}

Enhanced metafile format (EMF) lagrar grafiska bilder enhetsoberoende. Metafiler av EMF består av poster med variabel längd i kronologisk ordning som kan återge den lagrade bilden efter analys på valfri utenhet. Dessa poster med variabel längd kan vara definitioner av inneslutna objekt, kommandon för ritning och grafikegenskaper som är viktiga för att återge bilden korrekt. När en enhet öppnar en EMF-metafil med sin egen grafikmiljö förblir proportionerna, dimensionerna, färgerna och andra grafiska egenskaper för originalbilden desamma oavsett vilken enhetsplattform som öppnas.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}