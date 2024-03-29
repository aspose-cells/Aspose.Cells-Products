---
title:  Szúrjon be kiemeléseket az Excel via .NET-be
weight: 360
description: C# Kódminta kiemelések Excelbe való hozzáadásához vagy beszúrásához a .NET könyvtár használatával. Ezzel a kóddal hozzon létre kiemeléseket MS Excelben a VB.NET, Asp.NET vagy bármely .NET alapú alkalmazáson belül.
keywords: [C# Aspose.Cells., c# add Callouts shape., c# insert Callouts shape., c# create Callouts shape]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Szúrjon be kiemeléseket az Excel via .NET-be" h2="Szúrjon be kiemeléseket a Aspose.Cells\' API használatával, szoftverek, például Microsoft vagy Open Office, Adobe PDF stb. nélkül." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Kiemelések beszúrása Excel-fájlba a C# használatával" %}}

 A kiemelések excel fájlba történő beszúrásához használjuk
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API, amely funkciókban gazdag, hatékony és könnyen használható dokumentumkezelési és -osztó API a C# platformhoz. Nyisd ki
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 csomagkezelő, keressen
 Aspose.Cells 
 és telepítse. A következő parancsot is használhatja a Package Manager konzolból.

{{% blocks/products/pf/agp/code-block title="Parancs" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="A kiemelések Excel-fájlba való beszúrásának lépései a C#-es számon keresztül" %}}

{{% blocks/products/pf/agp/text %}}

Szüksége van az aspose.cells.dll fájlra a következő munkafolyamat kipróbálásához a saját környezetében.

{{% /blocks/products/pf/agp/text %}}

+ Munkafüzet objektum példányosítása. (vagy->Töltse be a XLSX fájlt a teljes elérési úttal.)
+ Válassza ki a munkalapot az indexén keresztül.
 + Használja a[módszer hozzáadása](https://reference.aspose.com/cells/net/aspose.cells.drawing/shapecollection/addautoshape) feliratok beszúrásához a kiválasztott munkalapba
+ Mentse a munkafüzetet XLSX formátumban.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="rendszerkövetelmények" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for .NET minden nagyobb operációs rendszeren támogatott. Csak győződjön meg arról, hogy rendelkezik a következő előfeltételekkel.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows vagy kompatibilis operációs rendszer .NET Framework, .NET Core, Mono vagy Xamarin platformokkal
-  Fejlesztői környezet, például Microsoft Visual Studio
-  Adjon hivatkozást a Aspose.Cells for .NET DLL-re a projektben - Telepítse a NuGet-es számról a fenti Letöltés gomb segítségével

{{% /blocks/products/pf/agp/feature-section-col %}}

Az alábbi mintakód bemutatja, hogyan kell beilleszteni egy „Gondolatbuborék: Felhőt”. További típusokért tekintse meg az alábbi „A kiemeléstípusok áttekintését” című részt.

{{% blocks/products/pf/agp/code-block title="Feliratok beszúrása - C#" offSpacer="" %}}

{{< gist "aspose-cells-gists" "59a1901d62ea9ceb08456a818431a898" "InsertCalloutsIntoWorksheet.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

<div class="container-fluid features-section bg-gray">
 <a class="anchor" id="features" name="features">
 </a>
 <div class="row">
  <div class="container">
   <h2 class="pr-ft">
 A kiemelés típusainak áttekintése
   </h2>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-callouts-to-excel/speech_bubble_rectangle.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.RectangularCallout
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-callouts-to-excel/speech_bubble_rectangle_with_corners_rounded.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.RoundedRectangularCallout
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-callouts-to-excel/speech_bubble_oval.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.OvalCallout
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-callouts-to-excel/thought_bubble_cloud.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.CloudCallout
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-callouts-to-excel/line.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.LineCalloutWithBorder1
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-callouts-to-excel/bent_line.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
AutoShapeType.LineCalloutWithBorder2
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-callouts-to-excel/double_bent_line.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.LineCalloutWithBorder3
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-callouts-to-excel/line_with_accent_bar.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.LineCalloutWithAccentBar1
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-callouts-to-excel/bent_line_with_accent_bar.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.LineCalloutWithAccentBar2
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-callouts-to-excel/double_bent_line_with_accent_bar.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.LineCalloutWithAccentBar3
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-callouts-to-excel/line_with_no_border.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.LineCalloutNoBorder1
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-callouts-to-excel/bent_line_with_no_border.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.LineCalloutNoBorder2
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-callouts-to-excel/double_bent_line_with_no_border.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.LineCalloutNoBorder3
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-callouts-to-excel/line_with_border_and_accent_bar.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.LineCalloutWithBorderAndAccentBar1
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-callouts-to-excel/bent_line_with_border_and_accent_bar.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.LineCalloutWithBorderAndAccentBar2
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-callouts-to-excel/double_bent_line_with_border_and_accent_bar.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.LineCalloutWithBorderAndAccentBar3
    </p>
   </div>
  </div>
 </div>
</div>

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="Körülbelül Aspose.Cells for .NET API" %}}

Aspose.Cells API használható Microsoft Excel formátumok létrehozására, szerkesztésére, konvertálására és renderelésére különböző formátumokba. Ezen túlmenően használható átfogó diagramok készítésére, skálázható jelentésekre és megbízható számításokra a szoftveralkalmazásokon belül. A Aspose.Cells egy önálló API, és nem igényel olyan szoftvert, mint a Microsoft vagy az OpenOffice.

{{% /blocks/products/pf/agp/content %}}



<!-- aboutfile Ends -->
<!--
{{< blocks/products/pf/agp/other-supported-section title="Other Supported Splitting Formats" subTitle="Using C#, One can also split large file into chunks of many other file formats including." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/splitter/ods/" name="ODS" description="OpenDocument Spreadsheet File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/splitter/xls/" name="XLS" description="Excel Binary Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/splitter/xlsb/" name="XLSB" description="Binary Excel Workbook File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/splitter/xlsm/" name="XLSM" description="Spreadsheet File" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

-->

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
