---
title:  XLSM Fájlok metaadatainak megtekintése vagy szerkesztése via .NET
weight: 5590
description: C# forráskód a XLSM formátumú metaadatok szerkesztéséhez vagy megtekintéséhez a .NET Framework, .NET Core, Mono vagy Xamarin platformokon.
keywords: [C# Aspose.Cells., c# view xlsm metadata., c# add xlsm metadata., c# insert xlsm metadata., c# edit xlsm metadata., c# remove xlsm metadata., c# extract xlsm metadata., c# modify xlsm metadata]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Kivonat XLSM Metaadatok via .NET" h2="Készítse el saját .NET-es alkalmazásait a XLSM fájlok metaadatok hozzáadásához, szerkesztéséhez, eltávolításához vagy kibontásához szerveroldali API-k segítségével." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSM" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="A XLSM metaadatok kinyerése a C# használatával" %}}

 XLSM metaadatok kinyeréséhez a következőket fogjuk használni
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API, amely funkciókban gazdag, hatékony és könnyen használható metaadatok API a C# platformhoz. Nyisd ki
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 csomagkezelő, keressen
 **Aspose.Cells** 
 és telepítse. A következő parancsot is használhatja a Package Manager konzolból.

{{% blocks/products/pf/agp/code-block title="Parancs" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Lépések a XLSM metaadatainak C#-en keresztül történő kinyeréséhez" %}}

{{% blocks/products/pf/agp/text %}}

 Hozzáférhet a XLSM-es fájlban tárolt hasznos információkhoz, beleértve a XLSM-es fájl fogadásának, feldolgozásának, időbélyegzésének és így tovább.

{{% /blocks/products/pf/agp/text %}}

+ A XLSM betöltése a munkafüzet egy példányával
+ Szerezze be a Workbook objektum BuiltInDocumentProperties gyűjteményét
+ Ismételje meg a gyűjteményt
+ Megjelenítési tulajdonság neve, típusa és értéke

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="rendszerkövetelmények" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for .NET minden nagyobb operációs rendszeren támogatott. Csak győződjön meg arról, hogy rendelkezik a következő előfeltételekkel.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows vagy kompatibilis operációs rendszer .NET Framework, .NET Core, Mono vagy Xamarin platformokkal.
-  Fejlesztői környezet, például Microsoft Visual Studio.
-  Adjon hivatkozást a Aspose.Cells for .NET DLL-re a projektben.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="A XLSM - C# metaadatainak kivonata" offSpacer="" %}}

```cs

// load the XLSM with an instance of Workbook
var book = new Aspose.Cells.Workbook("template.xlsm");
// iterate over the BuiltInDocumentProperties collection
foreach (Aspose.Cells.Properties.DocumentProperty property in book.Worksheets.BuiltInDocumentProperties)
{
    Console.WriteLine($"\tType:\t{property.Type}");

    // Some properties may store multiple values
    if (property.Value is Array)
    {
        foreach (object value in property.Value as Array)
            Console.WriteLine($"\tValue:\t\"{value}\"");
    }
    else
    {
        Console.WriteLine($"\tValue:\t\"{property.Value}\"");
    }
}  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Körülbelül Aspose.Cells for .NET API" %}}

 Aspose.Cells API használható Microsoft Excel formátumok létrehozására, szerkesztésére, konvertálására és renderelésére különböző formátumokba. Ezen túlmenően használható átfogó diagramok készítésére, skálázható jelentésekre és megbízható számításokra a szoftveralkalmazásokon belül. A Aspose.Cells egy önálló API, és nem igényel olyan szoftvert, mint a Microsoft vagy az OpenOffice.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Kivonja a XLSM metaadatait online alkalmazáson keresztül" sectionDescription=" Tekintse meg és szerkessze a XLSM számú dokumentumok metaadatait a mi használatával[Élő bemutatók](https://products.aspose.app/cells/metadata) a következő előnyökkel." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Nem kell letölteni vagy beállítani semmit" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Nem kell kódot írni" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Csak töltse fel a XLSM fájlt, és szerkessze a dokumentum tulajdonságait" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Azonnal megkapja a letöltési linket az eredményül kapott fájlhoz" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSM" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsm/" >}}
XLSM kiterjesztésű fájlok olyan táblázatkezelő fájlok, amelyek támogatják a makrókat. Alkalmazási szempontból a makró a folyamatok automatizálására használt utasítások halmaza. A makró rögzíti az ismételten végrehajtott lépéseket, és megkönnyíti a műveletek végrehajtását a makró újbóli futtatásával. A makrók a Microsoft Visual Basic for Applications (VBA) programmal programozhatók az Excel-munkafüzetből a Visual Basic Editor segítségével, és onnan közvetlenül futtathatók/hibakereshetők.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott metaadat-formátumok" subTitle="A C# használatával sok más formátum metaadatait is lehet manipulálni, beleértve." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/metadata/ods/" name="ODS" description="OpenDocument táblázatfájl" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/metadata/xls/" name="XLS" description="Excel bináris formátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/metadata/xlsb/" name="XLSB" description="Bináris Excel munkafüzet fájl" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/metadata/xlsx/" name="XLSX" description="OOXML Excel fájl" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
