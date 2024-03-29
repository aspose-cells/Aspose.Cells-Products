---
title: Einfügen/Erstellen eines Flussdiagramms in Excel via Java
weight: 360
description: Einfügen/Erstellen eines Flussdiagramms mit Aspose.Cells' Java API ohne Software wie Microsoft oder Open Office, Adobe PDF usw.
keywords: [Java Aspose.Cells., Java add FlowChart., Java insert FlowChart., Java create FlowChart]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Einfügen/Erstellen eines Flussdiagramms in Excel via Java" h2="Einfügen/Erstellen eines Flussdiagramms mit Aspose.Cells\' API ohne Software wie Microsoft oder Open Office, Adobe PDF usw." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSX" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="So fügen Sie mit Java ein Flussdiagramm in eine Excel-Datei ein bzw. erstellen es" %}}

 Um ein FlowChart in eine Excel-Datei einzufügen/zu erstellen, verwenden wir
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API, eine funktionsreiche, leistungsstarke und benutzerfreundliche API for Java Plattform. Sie können die neueste Version direkt von herunterladen
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) 
 und installieren Sie es in Ihrem Maven-basierten Projekt, indem Sie der pom.xml die folgenden Konfigurationen hinzufügen.

{{% blocks/products/pf/agp/code-block title="Repository" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Abhängigkeit" offSpacer="true" %}}

```cs

<dependency>
<groupId>com.aspose</groupId>
<artifactId>aspose-cells</artifactId>
<version>version of aspose-cells API</version>
<classifier>jdk17</classifier>
</dependency>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Schritte zum Einfügen/Erstellen einer FlowChart-zu-Excel-Datei via Java" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

+ Instanziieren eines Arbeitsmappenobjekts. (Oder->Laden Sie die Datei XLSX mit vollständigem Pfad.)
+ Wählen Sie Arbeitsblatt über seinen Index aus.
 + Benutzen Sie die[Methode hinzufügen](https://reference.aspose.com/cells/java/com.aspose.cells/shapecollection/#addAutoShape-int-int-int-int-int-int-int-) um ein Flussdiagramm in das ausgewählte Arbeitsblatt einzufügen/zu erstellen
+ Arbeitsmappe im Format XLSX speichern.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Anforderungen" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java unterstützt auf allen wichtigen Plattformen und Betriebssystemen. Bitte stellen Sie sicher, dass Sie die folgenden Voraussetzungen erfüllen.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows oder ein kompatibles Betriebssystem mit Java Laufzeitumgebung für JSP/JSF-Anwendungen und Desktop-Anwendungen.
- Holen Sie sich die neueste Version von Aspose.Cells for Java direkt von Maven.

{{% /blocks/products/pf/agp/feature-section-col %}}

Der folgende Beispielcode zeigt, wie ein „Multidocument“ eingefügt wird. Weitere Typen finden Sie unten im Abschnitt „Übersicht über die Blockpfeilformtypen“.

{{% blocks/products/pf/agp/code-block title="Ein Flussdiagramm einfügen/erstellen – Java" offSpacer="" %}}

{{< gist "aspose-cells-gists" "5876dc77e47649b66bdb5deefb4b5639" "InsertFlowChartIntoWorksheet.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

<div class="container-fluid features-section bg-gray">
 <a class="anchor" id="features" name="features">
 </a>
 <div class="row">
  <div class="container">
   <h2 class="pr-ft">
 Übersicht über FlowChart-Typen
   </h2>
   <div class="col-lg-4">
    <!--em class="fa fa-chrome ico-blue fa-2x col-lg-2">
    </em-->
    <img src="/cells/net/shapes/insert-flowchart-to-excel/process.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.<br>FLOW_CHART_PROCESS
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-flowchart-to-excel/alternate_process.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.<br>FLOW_CHART_ALTERNATE_PROCESS
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-flowchart-to-excel/decision.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.<br>FLOW_CHART_DECISION
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-flowchart-to-excel/data.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.<br>FLOW_CHART_DATA
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-flowchart-to-excel/predefined_process.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.<br>FLOW_CHART_PREDEFINED_PROCESS
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-flowchart-to-excel/internal_storage.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.<br>FLOW_CHART_INTERNAL_STORAGE
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-flowchart-to-excel/document.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.<br>FLOW_CHART_DOCUMENT
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-flowchart-to-excel/multidocument.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.<br>FLOW_CHART_MULTIDOCUMENT
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-flowchart-to-excel/terminator.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.<br>FLOW_CHART_TERMINATOR
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-flowchart-to-excel/preparation.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.<br>FLOW_CHART_PREPARATION
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-flowchart-to-excel/manual_input.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.<br>FLOW_CHART_MANUAL_INPUT
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-flowchart-to-excel/manual_operation.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.<br>FLOW_CHART_MANUAL_OPERATION
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-flowchart-to-excel/connector.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.<br>FLOW_CHART_CONNECTOR
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-flowchart-to-excel/offpage_connector.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.<br>FLOW_CHART_OFFPAGE_CONNECTOR
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-flowchart-to-excel/card.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.<br>FLOW_CHART_CARD
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-flowchart-to-excel/punched_tape.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.<br>FLOW_CHART_PUNCHED_TAPE
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-flowchart-to-excel/summing_junction.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.<br>FLOW_CHART_SUMMING_JUNCTION
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-flowchart-to-excel/or.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.<br>FLOW_CHART_OR
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-flowchart-to-excel/collate.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.<br>FLOW_CHART_COLLATE
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-flowchart-to-excel/sort.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.<br>FLOW_CHART_SORT
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-flowchart-to-excel/extract.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.<br>FLOW_CHART_EXTRACT
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-flowchart-to-excel/merge.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.<br>FLOW_CHART_MERGE
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-flowchart-to-excel/stored_data.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.<br>FLOW_CHART_STORED_DATA
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-flowchart-to-excel/delay.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.<br>FLOW_CHART_DELAY
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-flowchart-to-excel/sequential_access_storage.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.<br>FLOW_CHART_SEQUENTIAL_ACCESS_STORAGE
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-flowchart-to-excel/magnetic_disk.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.<br>FLOW_CHART_MAGNETIC_DISK
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-flowchart-to-excel/direct_access_storage.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.<br>FLOW_CHART_DIRECT_ACCESS_STORAGE
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-flowchart-to-excel/display.png" align="left" width="28" height="28">
    <p class="col-lg-10" style="font-size:0.8rem !important;">
 AutoShapeType.<br>FLOW_CHART_DISPLAY
    </p>
   </div>
  </div>
 </div>
</div>

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Über Aspose.Cells for Java API" %}}

 Aspose.Cells API kann zum Erstellen, Bearbeiten, Konvertieren und Rendern von Microsoft Excel-Formaten in verschiedene Formate verwendet werden. Darüber hinaus kann es für umfassende Diagramme, skalierbare Berichte und zuverlässige Berechnungen innerhalb von Softwareanwendungen verwendet werden. Aspose.Cells ist ein eigenständiges API und erfordert keine Software wie Microsoft oder OpenOffice.


    {{% /blocks/products/pf/agp/content %}}

    


{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
