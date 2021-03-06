---
title: "XLT fájlformátumok megtekintése a következőn keresztül: .NET "
weight: 3610
url: /hu/net/viewer/xlt/ 
description: C# forráskód az XLT-dokumentumok betöltéséhez, megjelenítéséhez és megjelenítéséhez .NET Framework, .NET Core, Mono vagy Xamarin platformokon.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="XLT fájlnézegető for .NET" h2="Tekintse meg az Excel és OpenOffice táblázatokat, például az XLT-t Microsoft Excel vagy Office Automation nélkül." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLT" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="XLT-fájl megtekintése a következővel: C#" %}}

 Az XLT fájl megtekintéséhez használjuk
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API, amely funkciókban gazdag, hatékony és könnyen használható API a C# platformhoz, amely bármely Viewer-rel használható. Nyisd ki
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 csomagkezelő, keressen
 **Aspose.Cells** 
 és telepítse. A következő parancsot is használhatja a Package Manager konzolból.

{{% blocks/products/pf/agp/code-block title="Csomagkezelő konzolparancs" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Lépések az XLT megtekintéséhez a következőn keresztül: C#" %}}

{{% blocks/products/pf/agp/text %}}

 A Aspose.Cells segítségével a fejlesztők egyszerűen megtekinthetik az XLT-fájlt néhány sornyi kóddal.

{{% /blocks/products/pf/agp/text %}}

1. Töltse be az XLT fájlt a munkafüzet egy példányába1. Hozzon létre egy HtmlSaveOptions példányt, és állítsa igazra az ExportHeadings tulajdonságot1. Mentse az XLT fájlt HTML formátumban a Workbook.Save metódussal1. Az eredményül kapott HTML betöltése az alapértelmezett böngészőbe a Process.Start segítségével
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="rendszerkövetelmények" %}}

{{% blocks/products/pf/agp/text %}}

 A(z) Aspose.Cells for .NET minden nagyobb operációs rendszeren támogatott. Csak győződjön meg arról, hogy rendelkezik a következő előfeltételekkel.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows vagy egy kompatibilis operációs rendszer .NET Framework, .NET Core, Mono vagy Xamarin platformokkal- Fejlesztői környezet, például a Microsoft Visual Studio- A projektben hivatkozott Aspose.Cells for .NET
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# példakód az XLT fájl megtekintéséhez" offSpacer="" %}}

```cs

string output = System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".html";

// töltse be az XLT fájlt a munkafüzet egy példányába
var book = new Aspose.Cells.Workbook("template.xlt");
// hozzon létre egy HtmlSaveOptions példányt, és állítsa az ExportHeadings tulajdonságot true értékre
var options = new Aspose.Cells.HtmlSaveOptions();
options.ExportHeadings = true;

// mentse az XLT fájlt HTML formátumban
book.Save(output, options);
// Az eredményül kapott HTML betöltése az alapértelmezett böngészőbe
System.Diagnostics.Process.Start(output);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Körülbelül Aspose.Cells for .NET API" %}}

 A Aspose.Cells API segítségével Microsoft Excel formátumokat hozhat létre, szerkeszthet, konvertálhat és renderelhet különböző formátumokká. Ezenkívül használható átfogó diagramok készítésére, méretezhető jelentésekre és megbízható számításokra a szoftveralkalmazásokon belül. A Aspose.Cells egy önálló API, és nem igényel olyan szoftvert, mint a Microsoft vagy az OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Ingyenes alkalmazás az XLT megtekintéséhez" sectionDescription="Tekintse meg élő bemutatóinkat [XLT megtekintése](https://products.aspose.app/cells/viewer/xlt) a következő előnyökkel." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Nem kell letölteni vagy beállítani semmit" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Nem kell kódot írni vagy fordítani" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Csak töltsön fel XLT fájlt, és nyomja meg a \"Nézet\" gombot" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Ha szükséges, töltsön le XLT fájlt a hivatkozásról" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLT" readMoreLink="https://docs.fileformat.com/spreadsheet/xlt/" >}}
Az .XLT kiterjesztésű fájlok olyan sablonfájlok, amelyeket a Microsoft Excel programmal hoztak létre, amely egy táblázatkezelő alkalmazás, amely a Microsoft Office programcsomag része. A Microsoft Office 97-2003 támogatta az új XLT-fájlok létrehozását és megnyitását. Az Excel legújabb verziója továbbra is képes megnyitni a régi formátumú sablonfájlokat. Egy ilyen sablonfájl segítségével gyorsan hozhatók létre új Excel-fájlok alapértelmezett adatokkal és beállításokkal, például oldalformázással, betűmérettel, margókkal, diagramokkal stb., amelyek tovább menthetők új .XLS fájlként.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott megjelenítő formátumok" subTitle="A C# használatával számos más fájlformátum is megtekinthető, beleértve a." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/csv/" name="CSV" description="Vesszővel elválasztott értékek" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/ods/" name="ODS" description="OpenDocument táblázatfájl" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/tsv/" name="TSV" description="Tabulátorral elválasztott értékek" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/txt/" name="TXT" description="Szöveges dokumentum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xls/" name="XLS" description="Excel bináris formátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xlsb/" name="XLSB" description="Bináris Excel munkafüzet fájl" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xlsm/" name="XLSM" description="Táblázatfájl" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xlsx/" name="XLSX" description="OOXML Excel fájl" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xltm/" name="XLTM" description="Excel makró-kompatibilis sablon" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xltx/" name="XLTX" description="Office OpenXML Excel sablon" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}