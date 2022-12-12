---
title: Erstellen Sie Excel-Diagramme und konvertieren Sie sie in Bilder über Java

description: Java-Quellcode zum Zeichnen und Konvertieren von Diagrammen oder Diagrammen in Microsoft Excel mithilfe der Java-Bibliothek. 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertierung und Erstellung von Microsoft<sup>&reg;</sup> Excel-Dateidiagrammen über Java" h2="Konvertieren Sie Diagramme von Excel-Dokumenten in Bilder und erstellen Sie verschiedene Diagramme mit serverseitigen APIs in Java-basierten Anwendungen." >}}


{{% blocks/products/pf/feature-page-summary %}}

Die Analyse von Daten über Diagramme zeigt das Gesamtbild und es ist einfach, fundiertere Entscheidungen mit klareren Erkenntnissen zu treffen. [Java Excel-Bibliothek](/cells/java/) unterstützt das Zeichnen verschiedener Diagrammerstellung aufgelistet von [Diagramm Typ](https://reference.aspose.com/cells/java/com.aspose.cells/ChartType) einschließlich Torten-, Pyramiden-, Linien- und Blasendiagrammen. Darüber hinaus konvertiert es auch Diagramme in Bilder. API stellt eine bereit [Klasse Diagramme](https://reference.aspose.com/cells/java/com.aspose.cells/Chart) zur Darstellung eines einzelnen Excel-Diagramms.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Konvertieren Sie Excel-Diagramme in Bilder" %}}

Der Vorgang zum Konvertieren von Diagrammen in Bilder, einschließlich JPG, PNG, TIFF, BMP usw., ist: Verwenden Sie die [Arbeitsmappe](https://reference.aspose.com/java/cells/com.aspose.cells/workbook) Klasse, um die Excel-Datei zu laden, wählen Sie die entsprechende aus [Arbeitsplatz](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet) die Diagramme enthalten, oder durch jedes Diagramm in jedem Arbeitsblatt iterieren. Definieren [ImageOrPrintOptions](https://reference.aspose.com/cells/java/com.aspose.cells/ImageOrPrintOptions) und rendern Sie das Ausgabebild des Diagramms mit [Chart.toImage](https://reference.aspose.com/cells/java/com.aspose.cells/chart#toImage(java.io.OutputStream,%20com.aspose.cells.ImageOrPrintOptions)).


{{% blocks/products/pf/feature-page-code h3="Java Code zum Konvertieren eines Excel-Diagramms in ein Bild" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "render-excel-chart-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}


{{% blocks/products/pf/feature-page-section h2="Erstellen Sie Diagramme in einer Excel-Datei" %}}

Das Erstellen von Diagrammen mit Excel API ist einfach, da API verschiedene Klassen wie Axis, Chart, ChartArea, ChartDataTable, ChartFrame, ChartPoint, ChartPointCollection, ChartCollection usw. für verschiedene Arten von Diagrammen bereitstellt. Prozess ist, Erstellen Sie ein Arbeitsmappen-Klassenobjekt und wählen Sie das erste Arbeitsblatt oder das relevante Blatt aus, indem Sie seinen Index angeben. Fügen Sie als Datenquelle des Diagramms Werte in Arbeitsblattzellen ein [setValue](https://reference.aspose.com/cells/java/com.aspose.cells/cell#Value) Methode. Verwenden Sie die ChartCollection-Sammlungen [Methode hinzufügen](https://reference.aspose.com/cells/java/com.aspose.cells/chartcollection#add(int,%20int,%20int,%20int,%20int)), um das Diagramm hinzuzufügen, definieren Sie den Diagrammtyp mit der ChartType-Enumeration. Greifen Sie auf das neue Chart-Objekt aus der ChartCollection-Auflistung zu, indem Sie seinen Index übergeben. Verwenden Sie die [SerieSammlung](https://reference.aspose.com/cells/java/com.aspose.cells/SeriesCollection) charting-Objekt, um die Datenquelle des Diagramms anzugeben.

{{% blocks/products/pf/feature-page-code h3="Java Code zum Erstellen von Excel-Diagrammen" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "create-excel-chart-pyramid.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
