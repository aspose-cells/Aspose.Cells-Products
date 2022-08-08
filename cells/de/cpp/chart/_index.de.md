---
title: Erstellen Sie Excel-Diagramme und konvertieren Sie sie in Bilder über C++
url: /de/cpp/chart/
description: C++-Quellcode zum Zeichnen und Konvertieren von Diagrammen oder Diagrammen in Microsoft Excel mithilfe der C++-Bibliothek
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Erstellen Sie Microsoft<sup>&reg;</sup> Excel-Diagramme und konvertieren Sie sie über C++ in Bilder" h2="Konvertieren Sie Diagramme aus Excel-Dokumenten in Bilder und erstellen Sie Diagramme, einschließlich Kreis-, Pyramiden-, Linien- und Blasendiagramme, in C++-basierten Anwendungen." >}}

{{% blocks/products/pf/feature-page-summary %}}

Mit Excel-Diagrammen kann man sich einen Überblick verschaffen und Daten einfach analysieren, um die richtigen Entscheidungen zu treffen. [C++ Excel-Bibliothek](/cells/cpp/) unterstützt das Erstellen verschiedener Diagramme, die aufgelistet werden von [Aufzählung Aspose::Cells::Charts::ChartType
](https://reference.aspose.com/cells/cpp/namespace/aspose.cells.charts#a2f17e69bcefc754569019185d0621b70) einschließlich Flächen-, Balken-, Torten-, Pyramiden-, Linien- und Blasendiagrammen. Darüber hinaus bietet API für die Konvertierung von Diagrammen in Bilder a [ToImage-Methode](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_sparkline#a28d76dd585c48366e1657f2982722ddb) in das erforderliche Bildformat.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Erstellen Sie Excel-Diagramme" %}}

Der Vorgang zum Erstellen eines Excel-Diagramms besteht darin, eine Instanz der zu erstellen [IWorkbook-Klasse](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) und wählen Sie die gewünschte aus [Arbeitsblatt](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet_collection#a5574d624796043233420d0e0459ccc43). Fügen Sie das Diagramm mit hinzu [Methode hinzufügen](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_chart_collection#ab7e8cce835c251a4682605299a6aa068) mit relevanten Parametern einschließlich Diagrammtyp. Greifen Sie über Index und auf das Diagramm zu [Hinzufügen](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_series_collection#a8f4dc4d883f32f65b1fb673e2aa7862f) die Datenquelle für Diagramm.

{{% blocks/products/pf/feature-page-code h3="C++ Code zum Erstellen von Excel-Diagrammen" %}}

{{< gist "aspose-com-gists" "da2fd423617bf9013a7673870c81d708" "create-excel-chart.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Konvertieren Sie Diagramme in Bilder" %}}


Erstellen Sie zum Konvertieren von Diagrammen zunächst ein Diagramm des relevanten Typs mit dem obigen Code oder greifen Sie über das entsprechende Blatt darauf zu. Definieren Sie den Ausgabespeicherpfad für das Bild und verwenden Sie die ToImage-Methode für die Konvertierung.

 
{{% blocks/products/pf/feature-page-code h3="C++ Code zum Konvertieren von Excel-Diagrammen" %}}

{{< gist "aspose-com-gists" "da2fd423617bf9013a7673870c81d708" "convert-excel-chart-to-image.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}