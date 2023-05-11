---
title: Excel-grafieken maken en converteren naar afbeeldingen via .NET
description:  C# broncode om grafiek of diagram in Microsoft Excel te tekenen en te converteren met behulp van .NET Library.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Grafieken voor Excel-bestanden maken en converteren via .NET" h2="Maak Excel-documentgrafieken en converteer naar afbeeldingen met behulp van server-side API\'s binnen op .NET gebaseerde applicaties." >}}
{{% blocks/products/pf/feature-page-summary %}}
 Grafieken tekenen is een kunst om gegevens grafisch weer te geven voor eenvoudige analyse.[.NET Excel-bibliotheek](/cells/nl/net/) ondersteunt het tekenen van grafieken in Excel-bestanden. API ondersteunt het maken van verschillende grafieken vermeld in[ChartType-opsomming](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype) inclusief taart-, piramide-, lijn- en bellendiagrammen. Bovendien converteert het ook grafieken naar afbeeldingen. API biedt een[Grafieken klasse](https://reference.aspose.com/cells/net/aspose.cells.charts) voor diagrambouwstenen.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Maak grafieken in Excel-bestand" %}}

 Grafieken maken met Excel API is eenvoudig. Proces is, creëren[Werkmap klasse](https://reference.aspose.com/cells/net/aspose.cells/workbook) object en selecteer het eerste werkblad of het relevante blad door de index op te geven. Voeg de vereiste celgegevens in met behulp van[PutValue-methode](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index) . Voeg een grafiek toe aan het werkblad met behulp van de verzameling Grafieken[Methode toevoegen](https://reference.aspose.com/cells/net/aspose.cells.charts/chartcollection/methods/add) . Specificeer de[GrafiekType](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype)van ChartType-opsomming.
{{% blocks/products/pf/feature-page-code h3="C# Code om Excel-grafieken te maken" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "create-excel-chart.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section h2="Converteer Excel-grafieken naar afbeeldingen" %}}

 Het proces van het converteren van grafieken naar afbeeldingen is: gebruik de klasse Workbook om het Excel-bestand te laden, selecteer de relevante workset met de grafieken en roep de[ToImage-methode](https://reference.aspose.com/cells/net/aspose.cells.charts.chart/toimage/methods/7) voor conversie.

{{% blocks/products/pf/feature-page-code h3="C# Code om Excel-grafiek naar afbeelding te converteren" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "convert-xlsx-file-chart-to-images.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}
