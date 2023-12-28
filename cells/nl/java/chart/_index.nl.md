---
title: Maak Excel-grafieken en converteer naar afbeeldingen via Java
description:  Java broncode om diagram of diagram te tekenen en te converteren in Microsoft Excel met behulp van de Java-bibliotheek.
keywords: [Java Aspose.Cells., Java Convert chart to image., Java Save chart to image., Java chart to image., create charts in Java., insert charts in Java., manage charts in Java]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Conversie en creatie van Excel-bestandsgrafieken via Java" h2="Converteer Excel-documentgrafieken naar afbeeldingen en maak verschillende grafieken met behulp van server-side API\'s binnen op Java gebaseerde applicaties." >}}


{{% blocks/products/pf/feature-page-summary %}}

 Het analyseren van gegevens via grafieken toont het grotere geheel en het is gemakkelijk om beter geïnformeerde beslissingen te nemen met duidelijkere inzichten.[Java Excel-bibliotheek](/cells/nl/java/) ondersteunt het tekenen van verschillende diagramcreaties, vermeld door[Grafiektype](https://reference.aspose.com/cells/java/com.aspose.cells/ChartType) inclusief taart-, piramide-, lijn- en bellendiagrammen. Bovendien converteert het ook grafieken naar afbeeldingen. API biedt een[Grafieken klasse](https://reference.aspose.com/cells/java/com.aspose.cells/Chart) voor het weergeven van een enkel Excel-diagram.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Converteer Excel-grafieken naar afbeeldingen" %}}

 Het proces voor het converteren van grafieken naar afbeeldingen, waaronder JPG, PNG, TIFF, BMP enz. is: Gebruik de[Werkboek](https://reference.aspose.com/java/cells/com.aspose.cells/workbook) klasse om het Excel-bestand te laden, selecteert u het relevante[werktafel](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet) met de diagrammen of doorloop elk diagram in elk werkblad. Definiëren[AfbeeldingOfAfdrukopties](https://reference.aspose.com/cells/java/com.aspose.cells/ImageOrPrintOptions) en geef het uitvoerbeeld van de grafiek weer met behulp van[Grafiek.naarAfbeelding](https://reference.aspose.com/cells/java/com.aspose.cells/chart#toImage(java.io.OutputStream,%20com.aspose.cells.ImageOrPrintOptions)).


{{% blocks/products/pf/feature-page-code h3="Java Code om Excel-diagram naar afbeelding te converteren" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "render-excel-chart-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}


{{% blocks/products/pf/feature-page-section h2="Maak grafieken in Excel-bestand" %}}

Het maken van diagrammen met Excel API is eenvoudig, omdat API een reeks verschillende klassen biedt, zoals Axis, Chart, ChartArea, ChartDataTable, ChartFrame, ChartPoint, ChartPointCollection, ChartCollection enz. voor verschillende soorten diagrammen. Het proces is: maak een werkmapklasseobject en selecteer het eerste werkblad of het relevante blad door de index op te geven. Voor de gegevensbron van het diagram voegt u waarden in werkbladcellen in met behulp van[setWaarde](https://reference.aspose.com/cells/java/com.aspose.cells/cell#Value) methode. Gebruik ChartCollection-collecties[methode toevoegen](https://reference.aspose.com/cells/java/com.aspose.cells/chartcollection#add(int,%20int,%20int,%20int,%20int) ) om het diagram toe te voegen, definieert u het type diagram met de ChartType-opsomming. Krijg toegang tot het nieuwe Chart-object uit de ChartCollection-collectie door de index ervan door te geven. Gebruik de[SerieCollectie](https://reference.aspose.com/cells/java/com.aspose.cells/SeriesCollection) grafiekobject om de gegevensbron van het diagram op te geven.

{{% blocks/products/pf/feature-page-code h3="Java Code om Excel-grafieken te maken" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "create-excel-chart-pyramid.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
