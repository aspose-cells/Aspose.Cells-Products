---
title: Kiemelések beszúrása az Excelbe a Python via Java használatával
weight: 360
description: Python via Java forráskód a kiemelések Excelbe való beillesztéséhez.
keywords: [Python Aspose.Cells., Python add Callouts shape., Python insert Callouts shape., Python create Callouts shape]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Kiemelések beszúrása az Excelbe a Python via Java használatával" h2="Szúrjon be kiemeléseket a Aspose.Cells\' API használatával, szoftverek, például Microsoft vagy Open Office, Adobe PDF stb. nélkül." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-python-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for Python via Java" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Python via Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-python-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/python" installationsDocsLink="https://docs.aspose.com/cells/python" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://releases.aspose.com/cells/python-java/" learnAsLink="https://docs.aspose.com/cells/python" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Kiemelések beszúrása Excel-fájlba a Python via Java használatával" %}}

 A kiemelések excel fájlba történő beszúrásához használjuk
 [Aspose.Cells for Python via Java](https://pypi.org/project/aspose-cells/) 
 API, amely funkciókban gazdag, hatékony és könnyen használható dokumentumkezelési API for Python via Java platform. A API Excel-fájlok létrehozását, kezelését, konvertálását és megjelenítését biztosítja. Mindezt anélkül, hogy a Microsoft Office- vagy Excel-alkalmazásokra hagyatkozna. A következő paranccsal telepítheti a konzolról.

{{% blocks/products/pf/agp/code-block title="Parancs" offSpacer="true" %}}

```cs

> pip install aspose-cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="kiemelések Excel-fájlba való beszúrásának lépései a Python via Java használatával" %}}

{{% blocks/products/pf/agp/text %}}

Szüksége van az aspose.cells-re a következő munkafolyamat kipróbálásához a saját környezetében.

{{% /blocks/products/pf/agp/text %}}

+ Munkafüzet objektum példányosítása. (vagy->Töltse be a XLSX fájlt a teljes elérési úttal.)
+ Válassza ki a munkalapot az indexén keresztül.
 + Használja a[módszer hozzáadása](https://reference.aspose.com/cells/python-java/asposecells.api/shapecollection#addAutoShape(int,%20int,%20int,%20int,%20int,%20int,%20int)) feliratok beszúrásához a kiválasztott munkalapba
+ Mentse a munkafüzetet XLSX formátumban.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="rendszerkövetelmények" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Python via Java platformfüggetlen API, és bármilyen platformon használható (Windows, Linux és MacOS), csak győződjön meg arról, hogy a rendszer Java 1.8 vagy újabb[Python](https://www.python.org/downloads/) 3,5 vagy magasabb.
 
{{% /blocks/products/pf/agp/text %}}

-  Bármilyen operációs rendszer, amely Python via Java szkripteket futtat, például Windows, Linux és MacOS
- Telepítse a Java-et, és adja hozzá a PATH környezeti változóhoz, például:<code>PATH=C:\Program Files\Java\jdk1.8.0_131;</code>.
-  Telepítés: Aspose.Cells for Python via Java innen<a href="https://pypi.org/project/aspose-cells/">pypi</a> , használja a parancsot a következőképpen:<code>$ pip install aspose-cells</code>.

{{% /blocks/products/pf/agp/feature-section-col %}}

Az alábbi mintakód bemutatja, hogyan kell beilleszteni egy „Gondolatbuborék: Felhőt”. További típusokért tekintse meg az alábbi „A kiemeléstípusok áttekintését” című részt.

{{% blocks/products/pf/agp/code-block title="Feliratok beszúrása - Python via Java" offSpacer="" %}}

{{< gist "aspose-cells-gists" "32e50c6aabc547111966569f3fd39694" "InsertCalloutsIntoWorksheet.py" >}}

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
    <!--em class="fa fa-chrome ico-blue fa-2x col-lg-2">
    </em-->
    <img src="/cells/net/shapes/insert-callouts-to-excel/speech_bubble_rectangle.png" align="left" width="28" height="28">
    <p class="col-lg-12" style="font-size:0.8rem !important;">
 AutoShapeType.<br>RECTANGULAR_CALLOUT
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-callouts-to-excel/speech_bubble_rectangle_with_corners_rounded.png" align="left" width="28" height="28">
    <p class="col-lg-12" style="font-size:0.8rem !important;">
 AutoShapeType.<br>ROUNDED_RECTANGULAR_CALLOUT
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-callouts-to-excel/speech_bubble_oval.png" align="left" width="28" height="28">
    <p class="col-lg-12" style="font-size:0.8rem !important;">
 AutoShapeType.<br>OVAL_CALLOUT
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-callouts-to-excel/thought_bubble_cloud.png" align="left" width="28" height="28">
    <p class="col-lg-12" style="font-size:0.8rem !important;">
 AutoShapeType.<br>CLOUD_CALLOUT
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-callouts-to-excel/line.png" align="left" width="28" height="28">
    <p class="col-lg-12" style="font-size:0.8rem !important;">
 AutoShapeType.<br>LINE_CALLOUT_WITH_BORDER_1
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-callouts-to-excel/bent_line.png" align="left" width="28" height="28">
    <p class="col-lg-12" style="font-size:0.8rem !important;">
 AutoShapeType.<br>LINE_CALLOUT_WITH_BORDER_2
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-callouts-to-excel/double_bent_line.png" align="left" width="28" height="28">
    <p class="col-lg-12" style="font-size:0.8rem !important;">
 AutoShapeType.<br>LINE_CALLOUT_WITH_BORDER_3
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-callouts-to-excel/line_with_accent_bar.png" align="left" width="28" height="28">
    <p class="col-lg-12" style="font-size:0.8rem !important;">
 AutoShapeType.<br>LINE_CALLOUT_WITH_ACCENT_BAR_1
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-callouts-to-excel/bent_line_with_accent_bar.png" align="left" width="28" height="28">
    <p class="col-lg-12" style="font-size:0.8rem !important;">
 AutoShapeType.<br>LINE_CALLOUT_WITH_ACCENT_BAR_2
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-callouts-to-excel/double_bent_line_with_accent_bar.png" align="left" width="28" height="28">
    <p class="col-lg-12" style="font-size:0.8rem !important;">
 AutoShapeType.<br>LINE_CALLOUT_WITH_ACCENT_BAR_3
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-callouts-to-excel/line_with_no_border.png" align="left" width="28" height="28">
    <p class="col-lg-12" style="font-size:0.8rem !important;">
 AutoShapeType.<br>LINE_CALLOUT_NO_BORDER_1
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-callouts-to-excel/bent_line_with_no_border.png" align="left" width="28" height="28">
    <p class="col-lg-12" style="font-size:0.8rem !important;">
 AutoShapeType.<br>LINE_CALLOUT_NO_BORDER_2
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-callouts-to-excel/double_bent_line_with_no_border.png" align="left" width="28" height="28">
    <p class="col-lg-12" style="font-size:0.8rem !important;">
 AutoShapeType.<br>LINE_CALLOUT_NO_BORDER_3
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-callouts-to-excel/line_with_border_and_accent_bar.png" align="left" width="28" height="28">
    <p class="col-lg-12" style="font-size:0.8rem !important;">
 AutoShapeType.<br>LINE_CALLOUT_WITH_BORDER_AND_ACCENT_BAR_1
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-callouts-to-excel/bent_line_with_border_and_accent_bar.png" align="left" width="28" height="28">
    <p class="col-lg-12" style="font-size:0.8rem !important;">
 AutoShapeType.<br>LINE_CALLOUT_WITH_BORDER_AND_ACCENT_BAR_2
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-callouts-to-excel/double_bent_line_with_border_and_accent_bar.png" align="left" width="28" height="28">
    <p class="col-lg-12" style="font-size:0.8rem !important;">
 AutoShapeType.<br>LINE_CALLOUT_WITH_BORDER_AND_ACCENT_BAR_3
    </p>
   </div>
  </div>
 </div>
</div>

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="Körülbelül Aspose.Cells for Python via Java API" %}}

Aspose.Cells API használható Microsoft Excel formátumok létrehozására, szerkesztésére, konvertálására és renderelésére különböző formátumokba. Ezen túlmenően használható átfogó diagramok készítésére, skálázható jelentésekre és megbízható számításokra a szoftveralkalmazásokon belül. A Aspose.Cells egy önálló API, és nem igényel olyan szoftvert, mint a Microsoft vagy az OpenOffice.

{{% /blocks/products/pf/agp/content %}}



<!-- aboutfile Ends -->
<!--
{{< blocks/products/pf/agp/other-supported-section title="Other Supported Splitting Formats" subTitle="Using Python, One can also split large file into chunks of many other file formats including." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/splitter/ods/" name="ODS" description="OpenDocument Spreadsheet File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/splitter/xls/" name="XLS" description="Excel Binary Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/splitter/xlsb/" name="XLSB" description="Binary Excel Workbook File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/splitter/xlsm/" name="XLSM" description="Spreadsheet File" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

-->

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
