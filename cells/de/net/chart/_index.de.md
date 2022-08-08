---
title: Erstellung von Excel-Diagrammen und Umwandlung in Bilder über .NET
url: /de/net/chart/
description: C#-Quellcode zum Zeichnen und Konvertieren von Diagrammen oder Diagrammen in Microsoft Excel mithilfe der .NET-Bibliothek. 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Erstellung und Konvertierung von Diagrammen in Microsoft<sup>&reg;</sup> Excel-Dateien über .NET" h2="Erstellen Sie Diagramme für Excel-Dokumente und konvertieren Sie sie mithilfe serverseitiger APIs in .NET-basierten Anwendungen in Bilder." >}}
{{% blocks/products/pf/feature-page-summary %}}
Das Zeichnen von Diagrammen ist eine Kunst, um Daten zur einfachen Analyse grafisch darzustellen. [.NET Excel-Bibliothek](/cells/net/) unterstützt das Zeichnen von Diagrammen in Excel-Dateien. API unterstützt verschiedene in aufgeführte Diagrammerstellung [ChartType-Aufzählung](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype) einschließlich Torten-, Pyramiden-, Linien- und Blasendiagrammen. Darüber hinaus konvertiert es auch Diagramme in Bilder. API stellt eine bereit [Klasse Diagramme](https://reference.aspose.com/cells/net/aspose.cells.charts) für Diagrammbausteine.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Erstellen Sie Diagramme in einer Excel-Datei" %}}

Das Erstellen von Diagrammen mit Excel API ist einfach. Prozess ist, Erstellen [Klasse Arbeitsbuch](https://reference.aspose.com/cells/net/aspose.cells/workbook) Objekt und wählen Sie das erste Arbeitsblatt oder das relevante Blatt aus, indem Sie seinen Index angeben. Fügen Sie die erforderlichen Zellendaten mit ein [PutValue-Methode](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index). Fügen Sie dem Arbeitsblatt ein Diagramm hinzu, indem Sie die Diagrammsammlung verwenden [Methode hinzufügen](https://reference.aspose.com/cells/net/aspose.cells.charts/chartcollection/methods/add). Präzisiere das [Diagramm Typ](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype) aus der ChartType-Enumeration.
{{% blocks/products/pf/feature-page-code h3="C# Code zum Erstellen von Excel-Diagrammen" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "create-excel-chart.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section h2="Konvertieren Sie Excel-Diagramme in Bilder" %}}

Der Vorgang zum Konvertieren von Diagrammen in Bilder lautet: Verwenden Sie die Workbook-Klasse, um die Excel-Datei zu laden, wählen Sie das entsprechende Workset mit den Diagrammen aus und rufen Sie die auf [ToImage-Methode](https://reference.aspose.com/cells/net/aspose.cells.charts.chart/toimage/methods/7) für die Konvertierung.

{{% blocks/products/pf/feature-page-code h3="C# Code zum Konvertieren eines Excel-Diagramms in ein Bild" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "convert-xlsx-file-chart-to-images.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}