---
title: Vložte vývojový diagram do Excelu přes C++
weight: 790
description: C++ ukázkový kód pro vložení vývojového diagramu do souboru aplikace Excel na C++ Runtime Environment pro Windows 32 bit, Windows 64 bit a Linux 64 bit.
keywords: [C++ Aspose.Cells., C++ add FlowChart., C++ insert FlowChart., C++ create FlowChart]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Vložte vývojový diagram do Excelu přes C++" h2="Vkládejte objekty pomocí nativního a vysokého výkonu na straně serveru Aspose.Cells for C++ API bez použití jakéhokoli softwaru, jako je Microsoft nebo Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Jak vložit vývojový diagram do souboru aplikace Excel pomocí C++" %}}

 Abychom mohli vložit vývojový diagram do souboru aplikace Excel, použijeme
 [Aspose.Cells for C++](https://products.aspose.com/cells/cpp) 
API, což je funkčně bohatá, výkonná a snadno použitelná platforma pro vyhledávání dokumentů API for C++. Jeho nejnovější verzi si můžete stáhnout přímo, stačí otevřít
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 správce balíčků, vyhledejte
 **Aspose.Cells.Cpp** 
 a nainstalovat. Můžete také použít následující příkaz z konzoly Správce balíčků.

{{% blocks/products/pf/agp/code-block title="Příkaz" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Kroky pro vložení vývojového diagramu do souboru aplikace Excel prostřednictvím C++" %}}

+ Vytvoření instance objektu Workbook. (nebo->Načtěte soubor XLSX s úplnou cestou.)
+ Vyberte List přes jeho index.
 + Použijte[přidat metodu](https://reference.aspose.com/cells/cpp/aspose.cells.drawing/shapecollection/addautoshape/) pro vložení vývojového diagramu do vybraného listu
+ Uložit sešit ve formátu XLSX.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na systém" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for C++ podporuje všechny hlavní platformy a operační systémy. Ujistěte se prosím, že máte následující předpoklady.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows nebo kompatibilní OS s C++ Runtime Environment pro Windows 32 bit, Windows 64 bit a Linux 64 bit.
-  Přidejte odkaz na Aspose.Cells for C++ DLL ve svém projektu.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/text %}}

Ukázkový kód níže ukazuje, jak vložit "Multidocument". Další typy naleznete v části „Přehled typů vývojových diagramů“ níže.

{{% /blocks/products/pf/agp/text %}}

{{% blocks/products/pf/agp/code-block title="Vložte vývojový diagram – C++" offSpacer="" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "InsertFlowChartIntoWorksheet-new.cpp" >}}

{{% /blocks/products/pf/agp/code-block %}}

<div class="container-fluid features-section bg-gray">
 <a class="anchor" id="features" name="features">
 </a>
 <div class="row">
  <div class="container">
   <h2 class="pr-ft">
 Přehled typů vývojových diagramů
   </h2>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-flowchart-to-excel/process.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType::<br>AutoShapeType_FlowChartProcess
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-flowchart-to-excel/alternate_process.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType::<br>AutoShapeType_FlowChartAlternateProcess
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-flowchart-to-excel/decision.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType::<br>AutoShapeType_FlowChartDecision
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-flowchart-to-excel/data.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType::<br>AutoShapeType_FlowChartData
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-flowchart-to-excel/predefined_process.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType::<br>AutoShapeType_FlowChartPredefinedProcess
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-flowchart-to-excel/internal_storage.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType::<br>AutoShapeType_FlowChartInternalStorage
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-flowchart-to-excel/document.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType::<br>AutoShapeType_FlowChartDocument
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-flowchart-to-excel/multidocument.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType::<br>AutoShapeType_FlowChartMultidocument
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-flowchart-to-excel/terminator.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType::<br>AutoShapeType_FlowChartTerminator
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-flowchart-to-excel/preparation.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType::<br>AutoShapeType_FlowChartPreparation
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-flowchart-to-excel/manual_input.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType::<br>AutoShapeType_FlowChartManualInput
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-flowchart-to-excel/manual_operation.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType::<br>AutoShapeType_FlowChartManualOperation
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-flowchart-to-excel/connector.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType::<br>AutoShapeType_FlowChartConnector
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-flowchart-to-excel/offpage_connector.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType::<br>AutoShapeType_FlowChartOffpageConnector
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-flowchart-to-excel/card.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType::<br>AutoShapeType_FlowChartCard
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-flowchart-to-excel/punched_tape.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType::<br>AutoShapeType_FlowChartPunchedTape
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-flowchart-to-excel/summing_junction.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType::<br>AutoShapeType_FlowChartSummingJunction
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-flowchart-to-excel/or.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType::<br>AutoShapeType_FlowChartOr
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-flowchart-to-excel/collate.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType::<br>AutoShapeType_FlowChartCollate
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-flowchart-to-excel/sort.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType::<br>AutoShapeType_FlowChartSort
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-flowchart-to-excel/extract.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType::<br>AutoShapeType_FlowChartExtract
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-flowchart-to-excel/merge.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType::<br>AutoShapeType_FlowChartMerge
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-flowchart-to-excel/stored_data.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType::<br>AutoShapeType_FlowChartStoredData
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-flowchart-to-excel/delay.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType::<br>AutoShapeType_FlowChartDelay
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-flowchart-to-excel/sequential_access_storage.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType::<br>AutoShapeType_FlowChartSequentialAccessStorage
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-flowchart-to-excel/magnetic_disk.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType::<br>AutoShapeType_FlowChartMagneticDisk
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-flowchart-to-excel/direct_access_storage.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType::<br>AutoShapeType_FlowChartDirectAccessStorage
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-flowchart-to-excel/display.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType::<br>AutoShapeType_FlowChartDisplay
    </p>
   </div>
  </div>
 </div>
</div>

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/faq-item question="" answer="" >}}


{{% blocks/products/pf/agp/content h2="O Aspose.Cells for C++ API" %}}

Aspose.Cells API lze použít k vytváření, úpravám, převodu a vykreslování Microsoft formátů Excelu do různých formátů. Kromě toho jej lze použít pro komplexní vytváření grafů, škálovatelný reporting a spolehlivé výpočty v rámci softwarových aplikací. Aspose.Cells je samostatný API a nevyžaduje žádný software jako Microsoft nebo OpenOffice.

{{% /blocks/products/pf/agp/content %}}


{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
