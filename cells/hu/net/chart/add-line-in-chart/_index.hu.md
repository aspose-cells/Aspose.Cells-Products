---
title: "Adjon hozzá egy sort a diagramhoz a következőn keresztül: C# "
url: /hu/net/add-line-in-chart/ 
description: C# Mintakód egy vonal hozzáadásához a diagramhoz az Excelben a .NET Library használatával. Használja ezt a kódot egy vonal hozzáadásához a diagramhoz az MS Excel programban VB.NET, Asp.NET vagy bármely .NET alapú alkalmazáson belül.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Adjon hozzá egy sort a diagramhoz a következőn keresztül: C#" h2="Natív és nagy teljesítményű MS Excel-készítés programozottan szerveroldali .NET API-k segítségével." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells" subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="" %}}

Egy vonal dinamikus hozzáadása a diagramhoz a futó alkalmazáson belül egyszerű. Annak érdekében, hogy az MS Office használata nélkül, a semmiből készíthessünk különféle diagramokat táblázatokká, [Aspose.Cells for .NET](https://products.aspose.com/cells/net)  API, amely különböző funkciókat kínál a táblázatok létrehozásához, kezeléséhez és konvertálásához a .NET platformon. A Aspose.Cells számos rugalmas diagramobjektumot biztosít.
{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Vonal hozzáadása a diagramokhoz a következőn keresztül: C#" %}}

{{% blocks/products/pf/agp/text %}}

 fejlesztők könnyen hozzáadhatnak egy sort a diagramhoz a különböző jelentéskészítő alkalmazások futtatásához, mindössze néhány sornyi kóddal.

{{% /blocks/products/pf/agp/text %}}

1. Teremt [**Munkafüzet**](https://apireference.aspose.com/cells/net/aspose.cells/workbook) osztály példány.1. Adjon hozzá néhány adatot a munkalap celláihoz a [**Cell**](https://apireference.aspose.com/cells/net/aspose.cells/cell) tárgyat [**PutValue**](https://apireference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index) módszer.   Ez lesz a diagram adatforrása.
1. Adjon hozzá egy diagramot a munkalaphoz a [**Diagramok**](https://apireference.aspose.com/cells/net/aspose.cells.charts/chartcollection) gyűjteményét [**Hozzáadás**](https://apireference.aspose.com/cells/net/aspose.cells.charts/chartcollection/methods/add) módszerrel, a [**Munkalap**](https://apireference.aspose.com/cells/net/aspose.cells/worksheet) tárgy.1. Hozzáférés az újhoz [**Diagram**](https://apireference.aspose.com/cells/net/aspose.cells.charts/chart) objektumot a Charts gyűjteményből indexének átadásával, hívással adja meg a diagram adatforrását [**Chart.SetChartDataRange**](https://https://apireference.aspose.com/cells/net/aspose.cells.charts/chart/methods/setchartdatarange).1. Számítsa ki a diagram pozícióját hívással [**Kiszámítja**](https://https://apireference.aspose.com/cells/net/aspose.cells.charts/chart/methods/Calculate) módszer.1. Add hozzá a [**Vonal**](https://apireference.aspose.com/cells/net/aspose.cells.drawing/shape/properties/msodrawingtype) Alakzat a Chart.Shapes.AddShapeInChartByScale metódus hívásával.1. Állítsa be a vonal formátumát
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="rendszerkövetelmények" %}}

{{% blocks/products/pf/agp/text %}}

 Csak győződjön meg arról, hogy a rendszer Microsoft Windows vagy kompatibilis operációs rendszerrel rendelkezik .NET Framework, .NET Core, Windows Azure, Mono vagy Xamarin platformokkal, valamint olyan fejlesztői környezettel, mint a Microsoft Visual Studio. 

{{% /blocks/products/pf/agp/text %}}

- Telepítés parancssorból mint <code>nuget install Aspose.Cells</code> vagy a Visual Studio Package Manager konzolján keresztül <code>Install-Package Aspose.Cells</code>.- Másik megoldásként letöltheti az offline MSI telepítőt vagy a ZIP-fájlban lévő összes DLL-t innen <a href="https://downloads.aspose.com/cells/net">letöltések</a>
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="A következő forráskód bemutatja, hogyan adhat hozzá egy sort a diagramhoz az MS Excel XLSX fájlhoz a C# használatával." offSpacer="" %}}

{{< gist "aspose-cells-gists" "88c9872508ec3150c552eb5155edf06e" "Examples-CSharp-Charts-AddLineInChart.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

Hajtsa végre a fenti kódot, és a következő eredményeket kapja:

![](line-in-chart.png)

{{< /blocks/products/pf/agp/feature-section >}}


<!-- aboutfile Starts -->
