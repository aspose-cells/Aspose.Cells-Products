---
title:  Converteer ODS naar Byte Array via C#
weight: 7690
description: C# Voorbeeldcode voor conversie van ODS naar byte-array. Gebruik deze code voor conversie van Excel ODS naar Byte Array binnen VB.NET, Asp.NET of een op .NET gebaseerde toepassing.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Converteer ODS naar byte-array via C#" h2="Native en krachtige Microsoft Excel ODS naar byte-arrayconversie of omgekeerd voor gegevensverwerking in spreadsheets met behulp van server-side .NET API\'s." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PDF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="ODS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="" %}}

 Byte Array is handig voor het verwerken of opslaan van gegevens. U kunt het ODS-bestand converteren naar Byte Array en naar een**Bytearray naar ODS** document met de taal C#. Om ODS naar byte-array te converteren, gebruiken we
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API dat verschillende functies biedt voor documentmanipulatie en -conversie met behulp van het .NET-platform.
{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Hoe ODS naar Byte Array te converteren via C#" %}}

{{% blocks/products/pf/agp/text %}}

 Het is voor de ontwikkelaars gemakkelijk om ODS-bestanden in slechts een paar regels code te laden en te converteren naar een byte-array voor verdere manipulatietaken.

{{% /blocks/products/pf/agp/text %}}

1.  Neem de naamruimte op in uw klassenbestand
1.  Laad invoer ODS Bestand met behulp van werkmap
1.  Initialiseer MemoryStream-object
1.  Converteer streamgegevens naar byte-array
1.  Verwerk gegevens vanaf uw behoefte

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="systeem vereisten" %}}

{{% blocks/products/pf/agp/text %}}

Zorg ervoor dat het systeem Microsoft Windows heeft of een compatibel besturingssysteem met .NET Framework, .NET Core, Windows Azure, Mono of Xamarin Platforms, evenals een ontwikkelomgeving zoals Microsoft Visual Studio.

{{% /blocks/products/pf/agp/text %}}

-  Installeer vanaf de opdrachtregel als<code>nuget install Aspose.Cells</code> of via Package Manager Console van Visual Studio met<code>Install-Package Aspose.Cells</code>.
-  U kunt ook het offline MSI-installatieprogramma of alle DLL's in een ZIP-bestand downloaden<a href="https://downloads.aspose.com/cells/net">downloads</a>

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Deze voorbeeldcode toont ODS naar byte-array C# Conversie" offSpacer="" %}}

```cs
Workbook workbook = new Workbook("sourceFile.ods");

//Save the workbook in memory stream
MemoryStream ms = new MemoryStream();

workbook.Save(ms, SaveFormat.Ods);

//Read bytes from memory stream
byte[] byte_array = new byte[ms.Length];
ms.Read(byte_array, 0, byte_array.Length);

// Process the memory stream byte array data as of your requirement 

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<!-- aboutfile Starts -->

      
     {{% blocks/products/pf/agp/content h2="" %}}

Een Excel Spreadsheet-programmeerbibliotheek die platformonafhankelijke applicaties kan bouwen met de mogelijkheid om alle Excel-bestanden te genereren, wijzigen, converteren, weergeven en afdrukken. .NET Excel API converteert niet alleen tussen spreadsheetformaten, het kan ook Excel-bestanden weergeven, waaronder ODS als afbeeldingen, PDF, HTML, ODS en meer, waardoor het een perfecte keuze is om documenten uit te wisselen in industriestandaardformaten.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODS" readMoreLink="https://docs.fileformat.com/spreadsheet/ods/" >}}
Bestanden met de extensie .ods staan voor OpenDocument Spreadsheet Document-indeling die door de gebruiker kan worden bewerkt. Gegevens worden in het ODF-bestand opgeslagen in rijen en kolommen. Het is een op XML gebaseerd formaat en is een van de verschillende subtypen in de Open Document Formats (ODF)-familie. Het formaat is gespecificeerd als onderdeel van de ODF 1.2-specificaties die zijn gepubliceerd en onderhouden door OASIS. Een aantal toepassingen op Windows en andere besturingssystemen kunnen ODS-bestanden openen voor bewerking en manipulatie, waaronder Microsoft Excel, NeoOffice en LibreOffice. ODS-bestanden kunnen ook door verschillende toepassingen worden geconverteerd naar andere spreadsheetformaten, zoals XLS, XLSX en andere.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

           {{< /blocks/products/pf/agp/about-file-section >}}


<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde conversies" subTitle="U kunt ook andere bestandsformaten converteren naar byte-array of omgekeerd, waaronder enkele hieronder vermeld." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xls-to-byte-array/" name="XLS Naar bytearray" description="Microsoft Excel-spreadsheet (verouderd)" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlsx-to-byte-array/" name="XLSX Naar bytearray" description="Open XML-werkmap" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlsb-to-byte-array/" name="XLSB Naar bytearray" description="Excel binaire werkmap" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlsm-to-byte-array/" name="XLSM Naar bytearray" description="Spreadsheet met ingeschakelde macro\'s" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlt-to-byte-array/" name="XLT Naar bytearray" description="Excel 97 - 2003-sjabloon" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xltx-to-byte-array/" name="XLTX Naar bytearray" description="Excel-sjabloon" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xltm-to-byte-array/" name="XLTM Naar bytearray" description="Excel-sjabloon met ingeschakelde macro\'s" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/csv-to-byte-array/" name="CSV Naar bytearray" description="Door komma\'s gescheiden waarden" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/tsv-to-byte-array/" name="TSV Naar bytearray" description="Door tabs gescheiden waarden" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/ods-to-byte-array/" name="ODS Naar bytearray" description="OpenDocument-spreadsheet" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xls-to-pdf/" name="XLS Naar PDF" description="Draagbaar documentformaat" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xls-to-html/" name="XLS Naar HTML" description="HyperText-opmaaktaal" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlsx-to-pdf/" name="XLSX Naar XPS" description="Microsoft Excel OOXML Excel-bestand" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlsx-to-html/" name="XLSX Naar HTML" description="OOXML Excel-bestand" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlsx-to-svg/" name="XLSX Naar SVG" description="Schaalbare vectorafbeeldingen" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xls-to-jpeg/" name="XLS Naar JPEG" description="JPEG Afb" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
