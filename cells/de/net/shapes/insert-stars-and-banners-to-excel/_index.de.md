---
title:  Stern/Banner in Excel via .NET einfügen
weight: 381
description: C# Beispielcode zum Hinzufügen oder Einfügen von Sternen/Bannern in Excel mithilfe der Bibliothek .NET. Verwenden Sie diesen Code, um Stern/Banner in MS Excel in VB.NET, Asp.NET oder einer anderen .NET-basierten Anwendung zu erstellen.
keywords: [C# Aspose.Cells., c# add Star/Banner., c# insert Star/Banner., c# create Star/Banner]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Stern/Banner in Excel via .NET einfügen" h2="Fügen Sie Stern/Banner mit Aspose.Cells\' API ohne Software wie Microsoft oder Open Office, Adobe PDF usw. ein." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="So fügen Sie mit C# einen Stern/Banner in eine Excel-Datei ein" %}}

 Um einen Stern/Banner in eine Excel-Datei einzufügen, verwenden wir
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API, eine funktionsreiche, leistungsstarke und benutzerfreundliche Plattform zur Dokumentenbearbeitung und -spaltung API für C#. Offen
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 Paketmanager, suchen Sie nach
 Aspose.Cells 
 und installieren. Sie können auch den folgenden Befehl über die Paket-Manager-Konsole verwenden.

{{% blocks/products/pf/agp/code-block title="Befehl" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Schritte zum Einfügen eines Sterns/Banners in eine Excel-Datei über C#" %}}

{{% blocks/products/pf/agp/text %}}

Sie benötigen die aspose.cells.dll, um den folgenden Workflow in Ihrer eigenen Umgebung auszuprobieren.

{{% /blocks/products/pf/agp/text %}}

+ Instanziieren eines Arbeitsmappenobjekts. (Oder->Laden Sie die Datei XLSX mit vollständigem Pfad.)
+ Wählen Sie Arbeitsblatt über seinen Index aus.
 + Benutzen Sie die[Methode hinzufügen](https://reference.aspose.com/cells/net/aspose.cells.drawing/shapecollection/addautoshape) um Stern/Banner in das ausgewählte Arbeitsblatt einzufügen
+ Arbeitsmappe im Format XLSX speichern.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Anforderungen" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for .NET wird auf allen gängigen Betriebssystemen unterstützt. Stellen Sie einfach sicher, dass Sie die folgenden Voraussetzungen erfüllen.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows oder ein kompatibles Betriebssystem mit .NET Framework, .NET Core, Mono oder Xamarin-Plattformen
-  Entwicklungsumgebung wie Microsoft Visual Studio
-  Fügen Sie in Ihrem Projekt einen Verweis auf die DLL Aspose.Cells for .NET hinzu – Installieren Sie von NuGet aus über die Schaltfläche „Herunterladen“ oben

{{% /blocks/products/pf/agp/feature-section-col %}}

Der folgende Beispielcode zeigt, wie „Band: gebogen und nach oben geneigt“ und „Explosion: 8 Punkte“ eingefügt werden. Weitere Typen finden Sie unten im „Überblick über Stern- und Bannertypen“.

{{% blocks/products/pf/agp/code-block title="Stern/Banner einfügen – C#" offSpacer="" %}}

{{< gist "aspose-cells-gists" "59a1901d62ea9ceb08456a818431a898" "InsertStarsAndBannersIntoWorksheet.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

<div class="container-fluid features-section bg-gray">
 <a class="anchor" id="features" name="features">
 </a>
 <div class="row">
  <div class="container">
   <h2 class="pr-ft">
 Übersicht über Stern- und Bannertypen
   </h2>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-stars-and-banners-to-excel/explosion_8_points.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType.Explosion1
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-stars-and-banners-to-excel/explosion_14_points.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType.Explosion2
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-stars-and-banners-to-excel/star_4_points.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType.Star4
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-stars-and-banners-to-excel/star_5_points.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType.Star5
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-stars-and-banners-to-excel/star_6_points.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType.Star6
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-stars-and-banners-to-excel/star_7_points.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType.Star7
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-stars-and-banners-to-excel/star_8_points.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType.Star8
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-stars-and-banners-to-excel/star_10_points.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType.Star10
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-stars-and-banners-to-excel/star_12_points.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType.Star12
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-stars-and-banners-to-excel/star_16_points.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType.Star16
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-stars-and-banners-to-excel/star_24_points.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType.Star24
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-stars-and-banners-to-excel/star_32_points.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType.Star32
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-stars-and-banners-to-excel/ribbon_tilted_up.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType.UpRibbon
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-stars-and-banners-to-excel/ribbon_tilted_down.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType.DownRibbon
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-stars-and-banners-to-excel/ribbon_curved_and_tilted_up.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType.CurvedUpRibbon
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-stars-and-banners-to-excel/ribbon_curved_and_tilted_down.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType.CurvedDownRibbon
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-stars-and-banners-to-excel/scroll_vertical.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType.VerticalScroll
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-stars-and-banners-to-excel/scroll_horizontal.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType.HorizontalScroll
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-stars-and-banners-to-excel/wave.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType.Wave
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-stars-and-banners-to-excel/double_wave.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType.DoubleWave
    </p>
   </div>
  </div>
 </div>
</div>

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="Über Aspose.Cells for .NET API" %}}

Aspose.Cells API kann zum Erstellen, Bearbeiten, Konvertieren und Rendern von Microsoft Excel-Formaten in verschiedene Formate verwendet werden. Darüber hinaus kann es für umfassende Diagramme, skalierbare Berichte und zuverlässige Berechnungen innerhalb von Softwareanwendungen verwendet werden. Aspose.Cells ist ein eigenständiges API und erfordert keine Software wie Microsoft oder OpenOffice.

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
