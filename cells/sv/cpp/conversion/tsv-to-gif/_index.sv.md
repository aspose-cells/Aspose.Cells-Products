---
title: Konvertera TSV till GIF via appen C++ 
weight: 9540
url: /sv/cpp/conversion/tsv-to-gif/ 
description: Exempel på C++-konverteringskod för TSV-dokument till GIF-format. Programmerare kan använda den här källkoden för batchkonvertering av TSV till GIF inom alla C++-program.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Konvertera TSV till GIF via C++" h2="Högpresterande TSV till GIF-konvertering med hjälp av C++-biblioteket utan behov av Microsoft Excel, OpenOffice eller Adobe Acrobat-installation." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="GIF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="TSV" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Så här konverterar du TSV till GIF med C++" %}}

 För att konvertera TSV till GIF kommer vi att använda
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

{{% blocks/products/pf/agp/feature-section-col title="Steg för att konvertera TSV till GIF via C++" %}}

{{% blocks/products/pf/agp/text %}}

 C++-utvecklare kan enkelt konvertera TSV-fil till GIF på bara några rader kod.

{{% /blocks/products/pf/agp/text %}}

1. Ladda TSV-fil med Factory::CreateIWorkbook.1. Välj det första kalkylbladet.1. Ställ in (GIF) alternativ.1. Iterera genom varje sida av arket och rendera.1. Öppna GIF-filen i ett kompatibelt program.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Systemkrav" %}}

{{% blocks/products/pf/agp/text %}}

 Innan du kör C++ omvandlingsexempelkoden, se till att du har följande förutsättningar.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows eller ett kompatibelt operativsystem med C++ Runtime Environment för Windows 32-bitars, Windows 64-bitars och Linux 64-bitars.- Aspose.Cells för C++ DLL som refereras till i ditt projekt.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="TSV till GIF C++ konverteringskällkod" offSpacer="" %}}

```cs
// Utdatakatalogsökväg.
StringPtr outDir = new String("OutputDirectoryPath");

// Ladda TSV.
intrusive_ptr<Aspose::Cells::IWorkbook> workbook = Factory::CreateIWorkbook(u"sourceFile.tsv");

// Öppna första kalkylbladet.
intrusive_ptr<Aspose::Cells::IWorksheet> worksheet = workbook->GetIWorksheets()->GetObjectByIndex(0);

// Skapa bild- eller utskriftsalternativ.
intrusive_ptr<Aspose::Cells::Rendering::IImageOrPrintOptions> imgOptions = Factory::CreateIImageOrPrintOptions();

// Ange bildformat.
imgOptions->SetImageFormat(Aspose::Cells::Systems::Drawing::Imaging::ImageFormat::GetGif());

// Ange horisontell och vertikal upplösning
imgOptions->SetHorizontalResolution(200);
imgOptions->SetVerticalResolution(200);

// Rendera arket med hänsyn till angivna bild- eller utskriftsalternativ.
intrusive_ptr<Aspose::Cells::Rendering::ISheetRender> sr = Factory::CreateISheetRender(worksheet, imgOptions);

// Få sidantal.
Aspose::Cells::Systems::Int32 pageCount = sr->GetPageCount();

// Skapa strängbyggarobjekt för strängsammansättningar.
intrusive_ptr<Aspose::Cells::Systems::Text::StringBuilder> sb = new Aspose::Cells::Systems::Text::StringBuilder();

// Gör varje sida till gif-bild en efter en.
for (int i = 0; i Clear();
	sb->Append(outDir);
	sb->Append((StringPtr)new String("outputConvertingWorksheetToImageGIF_"));
	sb->Append(i);
	sb->Append((StringPtr)new String(".gif"));

	// Hämta utdatabildens sökväg.
	StringPtr outputGIF = sb->ToString();

	// Konvertera kalkylblad till gif-bild.
	sr->ToImage(i, outputGIF);
}


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="TSV till GIF Conversion Live Demos" sectionDescription="[Konvertera TSV till GIF](https://products.aspose.app/cells/conversion/tsv-to-gif) just nu genom att besöka vår Live Demos-webbplats. Livedemon har följande fördelar" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Du behöver inte ladda ned Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Du behöver inte skriva någon kod." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Ladda bara upp din TSV-fil, den konverteras omedelbart till GIF." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Du kommer att få nedladdningslänken." >}}

    {{% blocks/products/pf/agp/content h2="C++ Excel-filhanteringsbibliotek" %}}

 Excel API kan användas för att skapa, redigera, konvertera och återge Microsoft Excel-format till olika format. Dessutom kan den användas för omfattande kartläggning, skalbar rapportering och tillförlitliga beräkningar inom mjukvaruapplikationer. Aspose.Cells är en fristående API och kräver ingen programvara som Microsoft eller OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="TSV" readMoreLink="https://docs.fileformat.com/spreadsheet/tsv/" >}}

Ett TSV-filformat (Tab-Separated Values) representerar data separerade med flikar i vanligt textformat. Filformatet, liknande CSV, används för att organisera data på ett strukturerat sätt för att importera och exportera mellan olika applikationer. Formatet används främst för dataimport/export och utbyte i kalkylbladsapplikationer och databaser. Varje post i en TSV-fil finns i en enda rad med textfil där varje fältvärde separeras med ett tabbtecken. Medietyp för TSV-filformat är text/tab-separerade-värden.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="GIF" readMoreLink="https://docs.fileformat.com/image/gif/" >}}

En GIF eller Graphical Interchange Format är en typ av mycket komprimerad bild. Ägs av Unisys, GIF använder LZW-komprimeringsalgoritmen som inte försämrar bildkvaliteten. För varje bild tillåter GIF vanligtvis upp till 8 bitar per pixel och upp till 256 färger är tillåtna över hela bilden. I motsats till en JPEG-bild, som kan visa upp till 16 miljoner färger och ganska tangerar gränserna för det mänskliga ögat. När internet dök upp förblev GIF det bästa valet eftersom de krävde låg bandbredd och kompatibla för grafiken som konsumerar solida färgområden. En animerad GIF kombinerar många bilder eller ramar till en enda fil och visar dem i en sekvens för att generera ett animerat klipp eller en kort video. Färgbegränsningarna är upp till 256 för varje bildruta och är troligen de minst lämpade för att återge andra bilder och fotografier med färggradient.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andra omvandlingar som stöds" subTitle="Du kan också konvertera TSV till många andra filformat inklusive några som anges nedan." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-bmp/" name="TSV TILL BMP" description="Bitmappsbild" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-csv/" name="TSV TILL CSV" description="Kommaseparerade värden" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-dif/" name="TSV TILL DIF" description="Datautbytesformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-emf/" name="TSV TILL EMF" description="Förbättrat metafilformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-html/" name="TSV TILL HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-jpeg/" name="TSV TILL JPEG" description="JPEG-bild" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-mhtml/" name="TSV TILL MHTML" description="Arkivformat för webbsidor" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-ods/" name="TSV TILL ODS" description="OpenDocument Spreadsheet File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-pdf/" name="TSV TILL PDF" description="Portabelt dokumentformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-png/" name="TSV TILL PNG" description="Bärbar nätverksgrafik" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-svg/" name="TSV TILL SVG" description="Skalbar vektorgrafik" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-tiff/" name="TSV TILL TIFF" description="Taggad bildformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-xls/" name="TSV TILL XLS" description="Excel binärt format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-xlsb/" name="TSV TILL XLSB" description="Binär Excel arbetsbok fil" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-xlsm/" name="TSV TILL XLSM" description="Kalkylbladsfil" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-xlsx/" name="TSV TILL XLSX" description="OOXML Excel-fil" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-xltm/" name="TSV TILL XLTM" description="Excel Macro-aktiverad mall" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-xltx/" name="TSV TILL XLTX" description="Office OpenXML Excel-mall" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-xps/" name="TSV TILL XPS" description="XML-pappersspecifikationer" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}