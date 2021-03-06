---
title: Converteer ODS naar XLSX via C++ applicatie 
weight: 9720
url: /nl/cpp/conversion/ods-to-xlsx/ 
description: Voorbeeld C++ conversiecode voor ODS-document naar XLSX-indeling. Programmeurs kunnen deze broncode gebruiken voor batchconversie van ODS naar XLSX binnen elke C++-toepassing.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Converteer ODS naar XLSX via C++" h2="Hoogwaardige ODS-naar-XLSX-conversie met behulp van de C++-bibliotheek zonder installatie van Microsoft Excel, OpenOffice of Adobe Acrobat." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="ODS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Hoe ODS naar XLSX te converteren met C++" %}}

 Om ODS naar XLSX te converteren, gebruiken we
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

{{% blocks/products/pf/agp/feature-section-col title="Stappen om ODS naar XLSX te converteren via C++" %}}

{{% blocks/products/pf/agp/text %}}

 C++ ontwikkelaars kunnen het ODS-bestand eenvoudig in slechts een paar regels code naar XLSX converteren.

{{% /blocks/products/pf/agp/text %}}

1. Laad het ODS-bestand met Factory::CreateIWorkbook.1. Roep de methode Save() aan.1. Geef het uitvoerbestandspad door met de (XLSX) bestandsextensie.1. XLSX-bestand wordt opgeslagen op het opgegeven pad.1. Open XLSX-bestand in een compatibel programma.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="systeem vereisten" %}}

{{% blocks/products/pf/agp/text %}}

 Voordat u de conversievoorbeeldcode C++ uitvoert, moet u ervoor zorgen dat u aan de volgende vereisten voldoet.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows of een compatibel besturingssysteem met C++ Runtime Environment voor Windows 32 bit, Windows 64 bit en Linux 64 bit.- Aspose.Cells voor C++ DLL waarnaar in uw project wordt verwezen.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="ODS naar XLSX C++ conversiebroncode" offSpacer="" %}}

```cs
// Laad de ODS.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.ods");

// Opslaan in XLSX-formaat.
wkb->Save(u"convertedFile.xlsx", SaveFormat_Xlsx);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="ODS naar XLSX conversie live demo\'s" sectionDescription="[ODS naar XLSX converteren](https://products.aspose.app/cells/conversion/ods-to-xlsx) op dit moment door onze Live Demo\'s-website te bezoeken. De live demo heeft de volgende voordelen:" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" U hoeft Aspose API niet te downloaden." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" U hoeft geen code te schrijven." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Upload gewoon uw ODS-bestand, het wordt direct geconverteerd naar XLSX." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" U krijgt de downloadlink." >}}

    {{% blocks/products/pf/agp/content h2="C++ Excel-bibliotheek voor bestandsmanipulatie" %}}

 Excel API kan worden gebruikt voor het maken, bewerken, converteren en weergeven van Microsoft Excel-indelingen naar verschillende indelingen. Bovendien kan het worden gebruikt voor uitgebreide grafieken, schaalbare rapportage en betrouwbare berekeningen binnen softwaretoepassingen. Aspose.Cells is een op zichzelf staande API en vereist geen software zoals Microsoft of OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODS" readMoreLink="https://docs.fileformat.com/spreadsheet/ods/" >}}

Bestanden met de ODS-extensie staan voor OpenDocument Spreadsheet Document-indeling die door de gebruiker kan worden bewerkt. Gegevens worden in het ODF-bestand opgeslagen in rijen en kolommen. Het is een op XML gebaseerde indeling en is een van de verschillende subtypen in de Open Document Formats (ODF)-familie. Het formaat wordt gespecificeerd als onderdeel van de ODF 1.2-specificaties die zijn gepubliceerd en onderhouden door OASIS. Een aantal toepassingen op Windows en andere besturingssystemen kunnen ODS-bestanden openen voor bewerking en manipulatie, waaronder Microsoft Excel, NeoOffice en LibreOffice. ODS-bestanden kunnen ook door verschillende toepassingen worden geconverteerd naar andere spreadsheetindelingen, zoals XLS, XLSX en andere.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSX" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsx/" >}}

XLSX is een bekende indeling voor Microsoft Excel-documenten die door Microsoft is geïntroduceerd met de release van Microsoft Office 2007. Gebaseerd op de structuur die is georganiseerd volgens de Open Packaging Conventions zoals uiteengezet in deel 2 van de OOXML-standaard ECMA-376, is de nieuwe indeling een zip-pakket dat een aantal XML-bestanden bevat. De onderliggende structuur en bestanden kunnen worden onderzocht door het .xlsx-bestand eenvoudig uit te pakken.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde conversies" subTitle="U kunt ODS ook converteren naar vele andere bestandsindelingen, waaronder enkele die hieronder worden vermeld." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-bmp/" name="ODS NAAR BMP" description="Bitmap afbeelding" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-csv/" name="ODS NAAR CSV" description="Door komma\'s gescheiden waarden" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-dif/" name="ODS NAAR DIF" description="Gegevensuitwisselingsformaat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-emf/" name="ODS NAAR EMV" description="Verbeterde metabestandsindeling" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-gif/" name="ODS NAAR GIF" description="Grafisch uitwisselingsformaat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-html/" name="ODS NAAR HTML" description="Hypertekst-opmaaktaal" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-jpeg/" name="ODS NAAR JPEG" description="JPEG-afbeelding" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-mhtml/" name="ODS NAAR MHTML" description="Webpagina-archiefindeling" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-pdf/" name="ODS NAAR PDF" description="Draagbaar documentformaat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-png/" name="ODS NAAR PNG" description="Draagbare netwerkgrafieken" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-svg/" name="ODS NAAR SVG" description="Schaalbare vectorafbeeldingen" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-tiff/" name="ODS NAAR TIFF" description="Gelabelde afbeeldingsindeling" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-tsv/" name="ODS NAAR TSV" description="Door tabs gescheiden waarden" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-xls/" name="ODS NAAR XLS" description="Excel binair formaat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-xlsb/" name="ODS NAAR XLSB" description="Binair Excel-werkmapbestand" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-xlsm/" name="ODS NAAR XLSM" description="Spreadsheetbestand" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-xltm/" name="ODS NAAR XLTM" description="Excel Macro-enabled sjabloon" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-xltx/" name="ODS NAAR XLTX" description="Office OpenXML Excel-sjabloon" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-xps/" name="ODS NAAR XPS" description="XML-papierspecificaties" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}