---
title: Maak Excel-diagrammen en converteer naar afbeeldingen via Java
url: /nl/java/chart/
description: Java broncode om een diagram of diagram in Microsoft Excel te tekenen en om te zetten met behulp van Java Bibliotheek. 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel-bestandsdiagrammen converteren en maken via Java" h2="Converteer Excel-documentgrafieken naar afbeeldingen en maak verschillende grafieken met behulp van server-side API\'s in Java-gebaseerde applicaties." >}}


{{% blocks/products/pf/feature-page-summary %}}

Het analyseren van gegevens via grafieken toont het grotere geheel en het is gemakkelijk om beter geïnformeerde beslissingen te nemen met duidelijkere inzichten. [Java Excel-bibliotheek](/cells/java/) ondersteunt het tekenen van verschillende diagrammen die worden weergegeven door: [Grafiektype](https://reference.aspose.com/cells/java/com.aspose.cells/ChartType) inclusief taart-, piramide-, lijn- en bellendiagrammen. Bovendien converteert het ook grafieken naar afbeeldingen. API biedt een [Grafieken klasse](https://reference.aspose.com/cells/java/com.aspose.cells/Chart) voor het weergeven van een enkele Excel-grafiek.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Converteer Excel-diagrammen naar afbeeldingen" %}}

Het proces van het converteren van grafieken naar afbeeldingen, waaronder JPG, PNG, TIFF, BMP enz [Werkboek](https://reference.aspose.com/java/cells/com.aspose.cells/workbook) class om het Excel-bestand te laden, selecteer de relevante [werkset](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet) met de grafieken of doorloop elke grafiek in elk werkblad. Definiëren [AfbeeldingOfAfdrukopties](https://reference.aspose.com/cells/java/com.aspose.cells/ImageOrPrintOptions) en render de afbeelding van de grafiek met behulp van [Grafiek.naarAfbeelding](https://reference.aspose.com/cells/java/com.aspose.cells/chart#toImage(java.io.OutputStream,%20com.aspose.cells.ImageOrPrintOptions)).


{{% blocks/products/pf/feature-page-code h3="Java Code om Excel-diagram naar afbeelding te converteren" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "render-excel-chart-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}


{{% blocks/products/pf/feature-page-section h2="Maak grafieken in Excel-bestand" %}}

Het maken van grafieken met Excel API is eenvoudig, aangezien API een reeks verschillende klassen biedt, zoals Axis, Chart, ChartArea, ChartDataTable, ChartFrame, ChartPoint, ChartPointCollection, ChartCollection enz. voor verschillende soorten grafieken. Proces is, Werkmap-klasseobject maken en selecteer het eerste werkblad of het relevante blad door de index op te geven. Voeg voor de gegevensbron van de grafiek waarden in werkbladcellen in met [setValue](https://reference.aspose.com/cells/java/com.aspose.cells/cell#Value) methode. Gebruik de collecties van ChartCollection [methode toevoegen](https://reference.aspose.com/cells/java/com.aspose.cells/chartcollection#add(int,%20int,%20int,%20int,%20int)) om de grafiek toe te voegen, definieert u het type grafiek met de ChartType-opsomming. Krijg toegang tot het nieuwe Chart-object uit de ChartCollection-verzameling door de index ervan door te geven. Gebruik de [SerieCollectie](https://reference.aspose.com/cells/java/com.aspose.cells/SeriesCollection) diagramobject om de gegevensbron van het diagram op te geven.

{{% blocks/products/pf/feature-page-code h3="Java Code om Excel-diagrammen te maken" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "create-excel-chart-pyramid.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}