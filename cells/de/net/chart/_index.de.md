---
title: Erstellung und Konvertierung von Excel-Diagrammen in Bilder via .NET
description:  C#-Quellcode zum Zeichnen und Konvertieren von Diagrammen oder Diagrammen in Microsoft Excel mithilfe der .NET-Bibliothek.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Erstellung und Konvertierung von Excel-Dateidiagrammen via .NET" h2="Erstellen Sie Excel-Dokumentdiagramme und konvertieren Sie sie mithilfe serverseitiger APIs in .NET-basierten Anwendungen in Bilder." >}}
{{% blocks/products/pf/feature-page-summary %}}
 Das Zeichnen von Diagrammen ist eine Kunst, Daten zur einfachen Analyse grafisch darzustellen.[.NET Excel-Bibliothek](/cells/de/net/) unterstützt das Zeichnen von Diagrammen in Excel-Dateien. API unterstützt die verschiedenen unter aufgeführten Diagrammerstellung[ChartType-Aufzählung](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype) einschließlich Kreis-, Pyramiden-, Linien- und Blasendiagrammen. Darüber hinaus werden auch Diagramme in Bilder umgewandelt. API bietet a[Klasse „Diagramme“.](https://reference.aspose.com/cells/net/aspose.cells.charts) für Diagrammbausteine.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Erstellen Sie Diagramme in einer Excel-Datei" %}}

 Das Erstellen von Diagrammen mit Excel API ist einfach. Der Prozess ist Erstellen[Arbeitsbuchklasse](https://reference.aspose.com/cells/net/aspose.cells/workbook) Objekt und wählen Sie das erste Arbeitsblatt oder das relevante Blatt aus, indem Sie seinen Index angeben. Fügen Sie die erforderlichen Zelldaten mit ein[PutValue-Methode](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index) . Fügen Sie mithilfe der Charts-Sammlung ein Diagramm zum Arbeitsblatt hinzu[Methode hinzufügen](https://reference.aspose.com/cells/net/aspose.cells.charts/chartcollection/methods/add) . Präzisiere das[Diagramm Typ](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype)aus der ChartType-Aufzählung.
{{% blocks/products/pf/feature-page-code h3="C# Code zum Erstellen von Excel-Diagrammen" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "create-excel-chart.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section h2="Konvertieren Sie Excel-Diagramme in Bilder" %}}

 Der Vorgang zum Konvertieren von Diagrammen in Bilder besteht darin, die Excel-Datei mit der Workbook-Klasse zu laden, die entsprechende Arbeitstabelle mit den Diagrammen auszuwählen und die aufzurufen[ToImage-Methode](https://reference.aspose.com/cells/net/aspose.cells.charts.chart/toimage/methods/7) zur Konvertierung.

{{% blocks/products/pf/feature-page-code h3="C# Code zum Konvertieren eines Excel-Diagramms in ein Bild" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "convert-xlsx-file-chart-to-images.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}
