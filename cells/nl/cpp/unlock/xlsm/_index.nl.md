---
title: XLSM-document ontgrendelen via C++ 
weight: 6070
url: /nl/cpp/unlock/xlsm/ 
description: C++ voorbeeldcode om met een wachtwoord beveiligd XLSM-bestand te ontgrendelen op C++ Runtime Environment voor Windows 32 bit, Windows 64 bit en Linux 64 bit.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Ontgrendel XLSM-bestanden via C++" h2="Verwijder de beveiliging van Excel-spreadsheets, inclusief XLSM-bestanden, met C++ Library." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSM" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Bescherming van XLSM-bestand verwijderen met C++" %}}

 Om het XLSM-bestand te ontgrendelen, gebruiken we
 [Aspose.Cells voor C++](https://products.aspose.com/cells/cpp) 
 API, een veelzijdige, krachtige en gebruiksvriendelijke documentbeveiliging API voor C++-platform. Je kunt de nieuwste versie direct downloaden, gewoon openen
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 pakketbeheerder, zoek naar
 **Aspose.Cells.Cpp** 
 en installeren. U kunt ook de volgende opdracht gebruiken vanuit de Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Aspose.Cells" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Ontgrendel XLSM via C++" %}}

{{% blocks/products/pf/agp/text %}}

 Jij hebt nodig
 [aspose.cells.dll](https://downloads.aspose.com/cells/cpp) 
 waarnaar in uw project wordt verwezen om de volgende workflow uit te voeren.

{{% /blocks/products/pf/agp/text %}}

1. Laad XLSM-vergrendeld bestand met CreateIWorkbook.1. Roep de functie Unprotect() aan om te ontgrendelen.1. Stel het wachtwoord in op NULL met behulp van SetPassword.1. Sla het XLSM-bestand op een opgegeven locatie op.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="systeem vereisten" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for C++ ondersteunt alle belangrijke platforms en besturingssystemen. Zorg ervoor dat u aan de volgende vereisten voldoet.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows of een compatibel besturingssysteem met C++ Runtime Environment voor Windows 32 bit, Windows 64 bit en Linux 64 bit.- Aspose.Cells voor C++ DLL waarnaar in uw project wordt verwezen.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Opdracht" offSpacer="" %}}

```cs

// Pad naar bronmap.
StringPtr srcDir = new String("SourceDirectory\\");

// Pad van uitvoermap.
StringPtr outDir = new String("OutputDirectory\\");

// Laad XLSM-bestand
intrusive_ptr<IWorkbook> workbook = Factory::CreateIWorkbook(srcDir->StringAppend(new String("sampleExcelFileProtected.xlsm")));

// Beveiliging van werkmap opheffen
workbook->Unprotect(new String("12345"));

// Stel wachtwoord in op null
workbook->GetISettings()->SetPassword(NULL);

// Sla het XLSM-bestand op
workbook->Save(outDir->StringAppend(new String("sampleExcelFileUnprotected_out.xlsm")));


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Ongeveer Aspose.Cells voor C++ API" %}}

 Aspose.Cells API kan worden gebruikt voor het maken, bewerken, converteren en weergeven van Microsoft Excel-indelingen naar verschillende indelingen. Bovendien kan het worden gebruikt voor uitgebreide grafieken, schaalbare rapportage en betrouwbare berekeningen binnen softwaretoepassingen. Aspose.Cells is een zelfstandige API en vereist geen software zoals Microsoft of OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Gratis app om XLSM te ontgrendelen" sectionDescription="Bekijk onze live demo\'s om [ontgrendel XLSM-bestanden](https://products.aspose.app/cells/unlock/xlsm) met volgende voordelen." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" U hoeft niets te downloaden of in te stellen" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" hoeft geen code te schrijven of te compileren" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Upload gewoon het XLSM-bestand en druk op de knop \"Ontgrendelen\"" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Download het resulterende XLSM-bestand via de link" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSM" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsm/" >}}
Bestanden met de extensie XLSM zijn een soort Spreadsheet-bestanden die macro's ondersteunen. Vanuit toepassingsoogpunt is een macro een set instructies die worden gebruikt voor het automatiseren van processen. Een macro wordt gebruikt om de stappen die herhaaldelijk worden uitgevoerd vast te leggen en vergemakkelijkt het uitvoeren van de acties door de macro opnieuw uit te voeren. Macro's worden geprogrammeerd met Microsoft's Visual Basic for Applications (VBA) vanuit de Excel-werkmap met behulp van de Visual Basic Editor en kunnen direct vanaf daar worden uitgevoerd/foutopsporing.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde ontgrendelingsindelingen" subTitle="Met behulp van C++ kan men gemakkelijk de bescherming / ontgrendeling van verschillende formaten verwijderen, waaronder." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/unlock/ods/" name="ODS" description="OpenDocument-spreadsheetbestand" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/unlock/xls/" name="XLS" description="Excel binair formaat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/unlock/xlsb/" name="XLSB" description="Binair Excel-werkmapbestand" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/unlock/xlsx/" name="XLSX" description="OOXML Excel-bestand" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}