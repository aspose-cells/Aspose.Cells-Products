---
title: Excel-grafieken maken en converteren naar afbeeldingen via Java
description:  Java broncode om grafiek of diagram in Microsoft Excel te tekenen en te converteren met behulp van Java Library.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Conversie en creatie van Excel-bestandsgrafieken via Java" h2="Converteer Excel-documentgrafieken naar afbeeldingen en maak verschillende grafieken met behulp van server-side API\'s binnen op Java gebaseerde applicaties." >}}


{{% blocks/products/pf/feature-page-summary %}}

 Het analyseren van gegevens via grafieken toont het grotere geheel en het is gemakkelijk om beter geïnformeerde beslissingen te nemen met duidelijkere inzichten.[Java Excel-bibliotheek](/cells/nl/java/) ondersteunt het tekenen van verschillende grafieken die worden vermeld door[GrafiekType](https://reference.aspose.com/cells/java/com.aspose.cells/ChartType) inclusief taart-, piramide-, lijn- en bellendiagrammen. Bovendien converteert het ook grafieken naar afbeeldingen. API biedt een[Grafieken klasse](https://reference.aspose.com/cells/java/com.aspose.cells/Chart)voor het weergeven van een enkele Excel-grafiek.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Converteer Excel-grafieken naar afbeeldingen" %}}

 Het proces van het converteren van grafieken naar afbeeldingen, waaronder JPG, PNG, TIFF, BMP enz. is, Gebruik de[Werkboek](https://reference.aspose.com/java/cells/com.aspose.cells/workbook) class om het Excel-bestand te laden, selecteert u het relevante[werkbank](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet) met de grafieken of doorloop elke grafiek in elk werkblad. Definiëren[ImageOrPrintOptions](https://reference.aspose.com/cells/java/com.aspose.cells/ImageOrPrintOptions) en geef het uitvoerbeeld van de kaart weer met behulp van[Grafiek.naarAfbeelding](https://reference.aspose.com/cells/java/com.aspose.cells/chart#toImage(java.io.OutputStream,%20com.aspose.cells.ImageOrPrintOptions)).


{{% blocks/products/pf/feature-page-code h3="Java Code om Excel-grafiek naar afbeelding te converteren" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "render-excel-chart-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}


{{% blocks/products/pf/feature-page-section h2="Maak grafieken in Excel-bestand" %}}

 Grafieken maken met Excel API is eenvoudig, aangezien API een reeks verschillende klassen biedt, zoals Axis, Chart, ChartArea, ChartDataTable, ChartFrame, ChartPoint, ChartPointCollection, ChartCollection enz. Voor verschillende soorten grafieken. Proces is, Create Workbook class object en selecteer het eerste werkblad of het relevante blad door de index op te geven. Voeg voor de gegevensbron van het diagram waarden in werkbladcellen in met behulp van[waarde instellen](https://reference.aspose.com/cells/java/com.aspose.cells/cell#Value)methode. Gebruik ChartCollection-collecties[methode toevoegen](https://reference.aspose.com/cells/java/com.aspose.cells/chartcollection#add(int,%20int,%20int,%20int,%20int) ) om het diagram toe te voegen, definieert u het type diagram met de ChartType-opsomming. Open het nieuwe Chart-object uit de ChartCollection-collectie door de index door te geven. Gebruik de[SerieCollection](https://reference.aspose.com/cells/java/com.aspose.cells/SeriesCollection) grafiekobject om de gegevensbron van de grafiek op te geven.

{{% blocks/products/pf/feature-page-code h3="Java Code om Excel-grafieken te maken" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "create-excel-chart-pyramid.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
