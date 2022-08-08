---
title: Excel-diagrammen maken en converteren naar afbeeldingen via .NET
url: /nl/net/chart/
description: C# broncode om een diagram of diagram in Microsoft Excel te tekenen en om te zetten met behulp van .NET Bibliotheek. 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel-bestandsdiagrammen maken en converteren via .NET" h2="Maak Excel-documentdiagrammen en converteer ze naar afbeeldingen met behulp van server-side API\'s in .NET-gebaseerde applicaties." >}}
{{% blocks/products/pf/feature-page-summary %}}
Het tekenen van grafieken is een kunst om gegevens grafisch weer te geven voor eenvoudige analyse. [.NET Excel-bibliotheek](/cells/net/) ondersteunt het tekenen van grafieken in Excel-bestanden. API ondersteunt het maken van verschillende grafieken die worden vermeld in [Grafiektype opsomming](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype) inclusief taart-, piramide-, lijn- en bellendiagrammen. Bovendien converteert het ook grafieken naar afbeeldingen. API biedt een [Grafieken klasse](https://reference.aspose.com/cells/net/aspose.cells.charts) voor kaartbouwstenen.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Maak grafieken in Excel-bestand" %}}

Het maken van grafieken met Excel API is eenvoudig. Proces is, Creëren [Werkboek klasse](https://reference.aspose.com/cells/net/aspose.cells/workbook) object en selecteer het eerste werkblad of het relevante werkblad door de index op te geven. Voeg de vereiste celgegevens in met [PutValue-methode](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index). Voeg een diagram toe aan het werkblad met behulp van de verzamelingen van grafieken [Methode toevoegen](https://reference.aspose.com/cells/net/aspose.cells.charts/chartcollection/methods/add). Specificeer de [Grafiektype](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype) van ChartType-opsomming.
{{% blocks/products/pf/feature-page-code h3="C# Code om Excel-diagrammen te maken" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "create-excel-chart.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section h2="Converteer Excel-diagrammen naar afbeeldingen" %}}

Het proces van het converteren van grafieken naar afbeeldingen is: gebruik de klasse Werkboek om het Excel-bestand te laden, selecteer de relevante werkset die de grafieken bevat en roep de [ToImage-methode](https://reference.aspose.com/cells/net/aspose.cells.charts.chart/toimage/methods/7) voor conversie.

{{% blocks/products/pf/feature-page-code h3="C# Code om Excel-diagram naar afbeelding te converteren" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "convert-xlsx-file-chart-to-images.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}