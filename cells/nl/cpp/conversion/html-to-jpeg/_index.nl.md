---
title: Converteer HTML naar JPEG via C++ applicatie 
weight: 7270
url: /nl/cpp/conversion/html-to-jpeg/ 
description: Voorbeeld C++ conversiecode voor HTML-document naar JPEG-indeling. Programmeurs kunnen deze broncode gebruiken voor batch-HTML-naar-JPEG-conversie binnen elke C++-toepassing.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Converteer HTML naar JPEG via C++" h2="Hoogwaardige HTML-naar-JPEG-conversie met behulp van de C++-bibliotheek zonder installatie van Microsoft Excel, OpenOffice of Adobe Acrobat." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="JPEG" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="HTML" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="HTML converteren naar JPEG met C++" %}}

 Om HTML naar JPEG te converteren, gebruiken we
 [Aspose.Cells voor C++](https://products.aspose.com/cells/cpp) 
 API, een veelzijdige, krachtige en gebruiksvriendelijke documentmanipulatie en conversie API voor C++-platform. Je kunt de nieuwste versie direct downloaden, gewoon openen
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 pakketbeheerder, zoek naar
 Aspose.Cells.Cpp 
 en installeren. U kunt ook de volgende opdracht gebruiken vanuit de Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Opdracht" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Stappen om HTML naar JPEG te converteren via C++" %}}

{{% blocks/products/pf/agp/text %}}

 C++ ontwikkelaars kunnen HTML-bestanden gemakkelijk converteren naar JPEG in slechts een paar regels code.

{{% /blocks/products/pf/agp/text %}}

1. Laad HTML-bestand met behulp van Factory::CreateIWorkbook.1. Selecteer het eerste werkblad.1. Stel (JPEG)-opties in.1. Doorloop elke pagina van het blad en render.1. Open het JPEG-bestand in een compatibel programma.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="systeem vereisten" %}}

{{% blocks/products/pf/agp/text %}}

 Voordat u de conversievoorbeeldcode C++ uitvoert, moet u ervoor zorgen dat u aan de volgende vereisten voldoet.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows of een compatibel besturingssysteem met C++ Runtime Environment voor Windows 32 bit, Windows 64 bit en Linux 64 bit.- Aspose.Cells voor C++ DLL waarnaar in uw project wordt verwezen.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="HTML naar JPEG C++ Conversiebroncode" offSpacer="" %}}

```cs
// Pad van uitvoermap.
StringPtr outDir = new String("OutputDirectoryPath");

// Laad de HTML-code.
intrusive_ptr<Aspose::Cells::IWorkbook> workbook = Factory::CreateIWorkbook(u"sourceFile.html");

// Toegang tot het eerste werkblad.
intrusive_ptr<Aspose::Cells::IWorksheet> worksheet = workbook->GetIWorksheets()->GetObjectByIndex(0);

// Maak een afbeelding of afdrukopties-object.
intrusive_ptr<Aspose::Cells::Rendering::IImageOrPrintOptions> imgOptions = Factory::CreateIImageOrPrintOptions();

// Geef het beeldformaat op.
imgOptions->SetImageFormat(Aspose::Cells::Systems::Drawing::Imaging::ImageFormat::GetJpeg());

// Specificeer horizontale en verticale resolutie
imgOptions->SetHorizontalResolution(200);
imgOptions->SetVerticalResolution(200);

// Render het vel met betrekking tot de opgegeven afbeelding of afdrukopties.
intrusive_ptr<Aspose::Cells::Rendering::ISheetRender> sr = Factory::CreateISheetRender(worksheet, imgOptions);

// Paginatelling ophalen.
Aspose::Cells::Systems::Int32 pageCount = sr->GetPageCount();

// Maak een stringbuilder-object voor string-aaneenschakelingen.
intrusive_ptr<Aspose::Cells::Systems::Text::StringBuilder> sb = new Aspose::Cells::Systems::Text::StringBuilder();

// Render elke pagina één voor één naar jpeg-afbeelding.
for (int i = 0; i Clear();
	sb->Append(outDir);
	sb->Append((StringPtr)new String("outputConvertingWorksheetToImageJPEG_"));
	sb->Append(i);
	sb->Append((StringPtr)new String(".jpeg"));

	// Haal het pad van de uitvoerafbeelding op.
	StringPtr outputJPEG = sb->ToString();

	// Converteer werkblad naar jpeg-afbeelding.
	sr->ToImage(i, outputJPEG);
}


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="HTML naar JPEG conversie Live demo\'s" sectionDescription="[HTML naar JPEG converteren](https://products.aspose.app/cells/conversion/html-to-jpeg) op dit moment door onze Live Demo\'s-website te bezoeken. De live demo heeft de volgende voordelen:" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" U hoeft Aspose API niet te downloaden." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" U hoeft geen code te schrijven." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Upload gewoon uw HTML-bestand, het wordt direct geconverteerd naar JPEG." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" U krijgt de downloadlink." >}}

    {{% blocks/products/pf/agp/content h2="C++ Excel-bibliotheek voor bestandsmanipulatie" %}}

 Excel API kan worden gebruikt voor het maken, bewerken, converteren en weergeven van Microsoft Excel-indelingen naar verschillende indelingen. Bovendien kan het worden gebruikt voor uitgebreide grafieken, schaalbare rapportage en betrouwbare berekeningen binnen softwaretoepassingen. Aspose.Cells is een op zichzelf staande API en vereist geen software zoals Microsoft of OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="HTML" readMoreLink="https://docs.fileformat.com/web/html/" >}}

HTML (Hyper Text Markup Language) is de extensie voor webpagina's die zijn gemaakt voor weergave in browsers. HTML, dat bekend staat als de taal van het web, is geëvolueerd met vereisten van nieuwe informatievereisten die moeten worden weergegeven als onderdeel van webpagina's. De nieuwste variant staat bekend als HTML 5 die veel flexibiliteit geeft voor het werken met de taal. HTML-pagina's worden ofwel ontvangen van de server, waar deze worden gehost, of kunnen ook vanuit het lokale systeem worden geladen. Elke HTML-pagina bestaat uit HTML-elementen zoals formulieren, tekst, afbeeldingen, animaties, links, enz. Deze elementen worden weergegeven door tags zoals img, a, p en verschillende andere waarbij elke tag een begin en einde heeft. Het kan ook applicaties insluiten die zijn geschreven in scripttalen zoals JavaScript en Style Sheets (CSS) voor algemene lay-outrepresentatie.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="JPEG" readMoreLink="https://docs.fileformat.com/image/jpeg/" >}}

Een JPEG is een type afbeeldingsformaat dat wordt opgeslagen met de methode van compressie met verlies. Het uitvoerbeeld, als resultaat van compressie, is een afweging tussen opslaggrootte en beeldkwaliteit. Gebruikers kunnen het compressieniveau aanpassen om het gewenste kwaliteitsniveau te bereiken en tegelijkertijd de opslagruimte verkleinen. De beeldkwaliteit wordt verwaarloosbaar beïnvloed als 10:1 compressie op de afbeelding wordt toegepast. Hoe hoger de compressiewaarde, hoe groter de verslechtering van de beeldkwaliteit. Het JPEG-beeldbestandsformaat is gestandaardiseerd door de Joint Photographic Experts Group en vandaar de naam JPEG. Het formaat is de keuze geweest voor het opslaan en verzenden van fotografische afbeeldingen op het web. Bijna alle besturingssystemen hebben nu viewers die de visualisatie van JPEG-afbeeldingen ondersteunen, die vaak ook met de JPG-extensie worden opgeslagen. Zelfs de webbrowsers ondersteunen visualisatie van JPEG-afbeeldingen.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde conversies" subTitle="U kunt HTML ook converteren naar vele andere bestandsindelingen, waaronder enkele die hieronder worden vermeld." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-bmp/" name="HTML NAAR BMP" description="Bitmap afbeelding" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-csv/" name="HTML NAAR CSV" description="Door komma\'s gescheiden waarden" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-dif/" name="HTML NAAR DIF" description="Gegevensuitwisselingsformaat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-emf/" name="HTML NAAR EMF" description="Verbeterde metabestandsindeling" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-gif/" name="HTML NAAR GIF" description="Grafisch uitwisselingsformaat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-mhtml/" name="HTML NAAR MHTML" description="Webpagina-archiefindeling" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-ods/" name="HTML NAAR ODS" description="OpenDocument-spreadsheetbestand" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-pdf/" name="HTML NAAR PDF" description="Draagbaar documentformaat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-png/" name="HTML NAAR PNG" description="Draagbare netwerkgrafieken" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-svg/" name="HTML NAAR SVG" description="Schaalbare vectorafbeeldingen" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-tiff/" name="HTML NAAR TIFF" description="Gelabelde afbeeldingsindeling" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-tsv/" name="HTML NAAR TSV" description="Door tabs gescheiden waarden" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-xls/" name="HTML NAAR XLS" description="Excel binair formaat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-xlsb/" name="HTML NAAR XLSB" description="Binair Excel-werkmapbestand" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-xlsm/" name="HTML NAAR XLSM" description="Spreadsheetbestand" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-xlsx/" name="HTML NAAR XLSX" description="OOXML Excel-bestand" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-xltm/" name="HTML NAAR XLTM" description="Excel Macro-enabled sjabloon" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-xltx/" name="HTML NAAR XLTX" description="Office OpenXML Excel-sjabloon" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-xps/" name="HTML NAAR XPS" description="XML-papierspecificaties" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}