---
title:  Vložte blokové šipky do Excelu přes C++
weight: 770
description: C++ ukázkový kód pro vložení blokových šipek do souboru aplikace Excel na C++ Runtime Environment pro Windows 32 bit, Windows 64 bit a Linux 64 bit.
keywords: [C++ Aspose.Cells., C++ add block arrows., C++ insert block arrows., C++ create block arrows]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Vložte blokové šipky do Excelu přes C++" h2="Vkládejte objekty pomocí nativního a vysokého výkonu na straně serveru Aspose.Cells for C++ API bez použití jakéhokoli softwaru, jako je Microsoft nebo Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Jak vložit blokové šipky do souboru aplikace Excel pomocí C++" %}}

 Aby bylo možné vložit blokové šipky do souboru aplikace Excel, použijeme
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

{{% blocks/products/pf/agp/feature-section-col title="Kroky pro vložení blokových šipek do souboru aplikace Excel prostřednictvím C++" %}}

+ Vytvoření instance objektu Workbook. (nebo->Načtěte soubor XLSX s úplnou cestou.)
+ Vyberte List přes jeho index.
 + Použijte[přidat metodu](https://reference.aspose.com/cells/cpp/aspose.cells.drawing/shapecollection/addautoshape/) pro vložení Přehled typů blokových šipek do vybraného listu
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

Ukázkový kód níže ukazuje, jak vložit "šipku vpravo". Další typy viz "Přehled typů blokových šipek" níže.

{{% /blocks/products/pf/agp/text %}}

{{% blocks/products/pf/agp/code-block title="Vložit šipky bloku - C++" offSpacer="" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "InsertBlockArrowsIntoWorksheet-new.cpp" >}}

{{% /blocks/products/pf/agp/code-block %}}

<div class="container-fluid features-section bg-gray">
 <a class="anchor" id="features" name="features">
 </a>
 <div class="row">
  <div class="container">
   <h2 class="pr-ft">
 Přehled typů blokových šipek
   </h2>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-block-arrows-to-excel/arrow_right.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType::<br>AutoShapeType_RightArrow
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-block-arrows-to-excel/arrow_left.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType::<br>AutoShapeType_LeftArrow
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-block-arrows-to-excel/arrow_up.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType::<br>AutoShapeType_UpArrow
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-block-arrows-to-excel/arrow_down.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType::<br>AutoShapeType_DownArrow
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-block-arrows-to-excel/arrow_left_right.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType::<br>AutoShapeType_LeftRightArrow
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-block-arrows-to-excel/arrow_up_down.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType::<br>AutoShapeType_UpDownArrow
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-block-arrows-to-excel/arrow_quad.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType::<br>AutoShapeType_QuadArrow
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-block-arrows-to-excel/arrow_left_right_up.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType::<br>AutoShapeType_LeftRightUpArrow
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-block-arrows-to-excel/arrow_bent.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType::<br>AutoShapeType_BentArrow
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-block-arrows-to-excel/arrow_uturn.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType::<br>AutoShapeType_UTurnArrow
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-block-arrows-to-excel/arrow_left_up.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType::<br>AutoShapeType_LeftUpArrow
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-block-arrows-to-excel/arrow_bent_up.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType::<br>AutoShapeType_BentUpArrow
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-block-arrows-to-excel/arrow_curved_right.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType::<br>AutoShapeType_CurvedRightArrow
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-block-arrows-to-excel/arrow_curved_left.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType::<br>AutoShapeType_CurvedLeftArrow
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-block-arrows-to-excel/arrow_curved_up.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType::<br>AutoShapeType_CurvedUpArrow
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-block-arrows-to-excel/arrow_curved_down.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType::<br>AutoShapeType_CurvedDownArrow
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-block-arrows-to-excel/arrow_striped_right.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType::<br>AutoShapeType_StripedRightArrow
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-block-arrows-to-excel/arrow_notched_right.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType::<br>AutoShapeType_NotchedRightArrow
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-block-arrows-to-excel/arrow_home_plate.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType::<br>AutoShapeType_HomePlate
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-block-arrows-to-excel/arrow_chevron.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType::<br>AutoShapeType_Chevron
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-block-arrows-to-excel/arrow_right_callout.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType::<br>AutoShapeType_RightArrowCallout
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-block-arrows-to-excel/arrow_down_callout.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType::<br>AutoShapeType_DownArrowCallout
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-block-arrows-to-excel/arrow_left_callout.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType::<br>AutoShapeType_LeftArrowCallout
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-block-arrows-to-excel/arrow_up_callout.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType::<br>AutoShapeType_UpArrowCallout
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-block-arrows-to-excel/arrow_left_right_callout.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType::<br>AutoShapeType_LeftRightArrowCallout
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-block-arrows-to-excel/arrow_quad_callout.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType::<br>AutoShapeType_QuadArrowCallout
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-block-arrows-to-excel/arrow_circular.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType::<br>AutoShapeType_CircularArrow
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
