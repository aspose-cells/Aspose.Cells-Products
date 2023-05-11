---
title: Erstellen Sie Excel-Diagramme und konvertieren Sie sie in Bilder via Java
description:  Java-Quellcode zum Zeichnen und Konvertieren von Diagrammen oder Diagrammen in Microsoft Excel mithilfe der Java-Bibliothek.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Konvertierung und Erstellung von Excel-Dateidiagrammen via Java" h2="Konvertieren Sie Excel-Dokumentdiagramme in Bilder und erstellen Sie verschiedene Diagramme mithilfe serverseitiger APIs in Java-basierten Anwendungen." >}}


{{% blocks/products/pf/feature-page-summary %}}

 Die Analyse von Daten mithilfe von Diagrammen zeigt das Gesamtbild und es ist einfacher, fundiertere Entscheidungen mit klareren Erkenntnissen zu treffen.[Java Excel-Bibliothek](/cells/de/java/) Unterstützt das Zeichnen verschiedener Diagrammerstellungslisten nach[Diagramm Typ](https://reference.aspose.com/cells/java/com.aspose.cells/ChartType) einschließlich Kreis-, Pyramiden-, Linien- und Blasendiagrammen. Darüber hinaus werden auch Diagramme in Bilder umgewandelt. API bietet a[Klasse „Diagramme“.](https://reference.aspose.com/cells/java/com.aspose.cells/Chart)zur Darstellung eines einzelnen Excel-Diagramms.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Konvertieren Sie Excel-Diagramme in Bilder" %}}

 Der Prozess zum Konvertieren von Diagrammen in Bilder, einschließlich JPG, PNG, TIFF, BMP usw., besteht darin, die zu verwenden[Arbeitsmappe](https://reference.aspose.com/java/cells/com.aspose.cells/workbook) Klasse, um die Excel-Datei zu laden, wählen Sie die entsprechende aus[Arbeitsblatt](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet) mit den Diagrammen oder durchlaufen Sie jedes Diagramm in jedem Arbeitsblatt. Definieren[ImageOrPrintOptions](https://reference.aspose.com/cells/java/com.aspose.cells/ImageOrPrintOptions) und rendern Sie das Ausgabebild des Diagramms mit[Chart.toImage](https://reference.aspose.com/cells/java/com.aspose.cells/chart#toImage(java.io.OutputStream,%20com.aspose.cells.ImageOrPrintOptions)).


{{% blocks/products/pf/feature-page-code h3="Java Code zum Konvertieren eines Excel-Diagramms in ein Bild" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "render-excel-chart-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}


{{% blocks/products/pf/feature-page-section h2="Erstellen Sie Diagramme in einer Excel-Datei" %}}

 Das Erstellen von Diagrammen mit Excel API ist einfach, da API eine Reihe verschiedener Klassen wie Axis, Chart, ChartArea, ChartDataTable, ChartFrame, ChartPoint, ChartPointCollection, ChartCollection usw. für verschiedene Arten von Diagrammen bereitstellt. Der Prozess besteht darin, ein Arbeitsmappenklassenobjekt zu erstellen und das erste Arbeitsblatt oder das relevante Blatt auszuwählen, indem Sie seinen Index angeben. Geben Sie als Datenquelle des Diagramms Werte in Arbeitsblattzellen ein[setValue](https://reference.aspose.com/cells/java/com.aspose.cells/cell#Value)Methode. Verwenden Sie ChartCollection-Sammlungen[Methode hinzufügen](https://reference.aspose.com/cells/java/com.aspose.cells/chartcollection#add(int,%20int,%20int,%20int,%20int) ), um das Diagramm hinzuzufügen, definieren Sie den Diagrammtyp mit der ChartType-Enumeration. Greifen Sie über die ChartCollection-Auflistung auf das neue Chart-Objekt zu, indem Sie seinen Index übergeben. Benutzen Sie die[SeriesCollection](https://reference.aspose.com/cells/java/com.aspose.cells/SeriesCollection) Diagrammobjekt, um die Datenquelle des Diagramms anzugeben.

{{% blocks/products/pf/feature-page-code h3="Java Code zum Erstellen von Excel-Diagrammen" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "create-excel-chart-pyramid.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
