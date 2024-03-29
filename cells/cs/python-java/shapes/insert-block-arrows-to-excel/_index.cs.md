---
title: Vložte šipky bloku do Excelu pomocí Python via Java
weight: 338
description: Python via Java zdrojový kód pro vložení blokových šipek do Excelu.
keywords: [Python Aspose.Cells., Python add block arrows., Python insert block arrows., Python create block arrows]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Vložte šipky bloku do Excelu pomocí Python via Java" h2="Vložte blokové šipky pomocí Aspose.Cells\' API bez jakéhokoli softwaru, jako je Microsoft nebo Open Office, Adobe PDF atd." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-python-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for Python via Java" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Python via Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-python-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/python" installationsDocsLink="https://docs.aspose.com/cells/python" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://releases.aspose.com/cells/python-java/" learnAsLink="https://docs.aspose.com/cells/python" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Jak vložit blokové šipky do souboru aplikace Excel pomocí Python via Java" %}}

 Aby bylo možné vložit blokové šipky do souboru aplikace Excel, použijeme
 [Aspose.Cells for Python via Java](https://pypi.org/project/aspose-cells/) 
 API, což je funkčně bohatá, výkonná a snadno použitelná platforma pro manipulaci s dokumenty API for Python via Java. API poskytuje vytváření, manipulaci, konverzi a vykreslování souborů Excel. Vše bez spoléhání se na aplikace Office nebo Excel Microsoft. Instalaci můžete provést z konzoly pomocí následujícího příkazu.

{{% blocks/products/pf/agp/code-block title="Příkaz" offSpacer="true" %}}

```cs

> pip install aspose-cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Kroky pro vložení blokových šipek do souboru Excel pomocí Python via Java" %}}

{{% blocks/products/pf/agp/text %}}

Abyste mohli vyzkoušet následující pracovní postup ve svém vlastním prostředí, potřebujete aspose.cells.

{{% /blocks/products/pf/agp/text %}}

+ Vytvoření instance objektu Workbook. (nebo->Načtěte soubor XLSX s úplnou cestou.)
+ Vyberte List přes jeho index.
 + Použijte[přidat metodu](https://reference.aspose.com/cells/python-java/asposecells.api/shapecollection#addAutoShape(int,%20int,%20int,%20int,%20int,%20int,%20int)) pro vložení blokových šipek do vybraného listu
+ Uložit sešit ve formátu XLSX.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na systém" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Python via Java je nezávislý na platformě API a lze jej použít na jakékoli platformě (Windows, Linux a MacOS), jen se ujistěte, že systém má Java 1.8 nebo vyšší,[Python](https://www.python.org/downloads/) 3.5 nebo vyšší.
 
{{% /blocks/products/pf/agp/text %}}

-  Jakýkoli operační systém, který může spouštět skripty Python via Java, například Windows, Linux a MacOS
- Nainstalujte Java a přidejte jej do proměnné prostředí PATH, například:<code>PATH=C:\Program Files\Java\jdk1.8.0_131;</code>.
-  Instalovat Aspose.Cells for Python via Java z<a href="https://pypi.org/project/aspose-cells/">pypi</a> , použijte příkaz jako:<code>$ pip install aspose-cells</code>.

{{% /blocks/products/pf/agp/feature-section-col %}}

Ukázkový kód níže ukazuje, jak vložit "šipku vpravo". Další typy naleznete v části „Přehled typů tvarů šipek bloku“ níže.

{{% blocks/products/pf/agp/code-block title="Vložit blokové šipky - Python via Java" offSpacer="" %}}

{{< gist "aspose-cells-gists" "32e50c6aabc547111966569f3fd39694" "InsertBlockArrowsIntoWorksheet.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

<div class="container-fluid features-section bg-gray">
 <a class="anchor" id="features" name="features">
 </a>
 <div class="row">
  <div class="container">
   <h2 class="pr-ft">
 Přehled typů tvarů šipek bloku
   </h2>
   <div class="col-lg-4">
    <!--em class="fa fa-chrome ico-blue fa-2x col-lg-2">
    </em-->
    <img src="/cells/net/shapes/insert-block-arrows-to-excel/arrow_right.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.RIGHT_ARROW
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-block-arrows-to-excel/arrow_left.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.LEFT_ARROW
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-block-arrows-to-excel/arrow_up.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.UP_ARROW
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-block-arrows-to-excel/arrow_down.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.DOWN_ARROW
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-block-arrows-to-excel/arrow_left_right.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.LEFT_RIGHT_ARROW
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-block-arrows-to-excel/arrow_up_down.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.UP_DOWN_ARROW
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-block-arrows-to-excel/arrow_quad.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.QUAD_ARROW
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-block-arrows-to-excel/arrow_left_right_up.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.LEFT_RIGHT_UP_ARROW
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-block-arrows-to-excel/arrow_bent.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.BENT_ARROW
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-block-arrows-to-excel/arrow_uturn.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
AutoShapeType.U_TURN_ARROW
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-block-arrows-to-excel/arrow_left_up.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.LEFT_UP_ARROW
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-block-arrows-to-excel/arrow_bent_up.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.BENT_UP_ARROW
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-block-arrows-to-excel/arrow_curved_right.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.CURVED_RIGHT_ARROW
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-block-arrows-to-excel/arrow_curved_left.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.CURVED_LEFT_ARROW
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-block-arrows-to-excel/arrow_curved_up.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.CURVED_UP_ARROW
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-block-arrows-to-excel/arrow_curved_down.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.CURVED_DOWN_ARROW
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-block-arrows-to-excel/arrow_striped_right.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.STRIPED_RIGHT_ARROW
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-block-arrows-to-excel/arrow_notched_right.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.NOTCHED_RIGHT_ARROW
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-block-arrows-to-excel/arrow_home_plate.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.HOME_PLATE
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-block-arrows-to-excel/arrow_chevron.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.CHEVRON
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-block-arrows-to-excel/arrow_right_callout.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.RIGHT_ARROW_CALLOUT
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-block-arrows-to-excel/arrow_down_callout.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.DOWN_ARROW_CALLOUT
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-block-arrows-to-excel/arrow_left_callout.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.LEFT_ARROW_CALLOUT
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-block-arrows-to-excel/arrow_up_callout.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.UP_ARROW_CALLOUT
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-block-arrows-to-excel/arrow_left_right_callout.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.LEFT_RIGHT_ARROW_CALLOUT
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-block-arrows-to-excel/arrow_quad_callout.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.QUAD_ARROW_CALLOUT
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-block-arrows-to-excel/arrow_circular.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.CIRCULAR_ARROW
    </p>
   </div>
  </div>
 </div>
</div>

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="Aspose.Cells for Python via Java API" %}}

Aspose.Cells API lze použít k vytváření, úpravám, převodu a vykreslování Microsoft formátů Excelu do různých formátů. Kromě toho jej lze použít pro komplexní vytváření grafů, škálovatelný reporting a spolehlivé výpočty v rámci softwarových aplikací. Aspose.Cells je samostatný API a nevyžaduje žádný software jako Microsoft nebo OpenOffice.

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
