---
title: Excel-grafieken maken en converteren naar afbeeldingen via .NET
description:  C# broncode om diagram of diagram te tekenen en te converteren in Microsoft Excel met behulp van de .NET-bibliotheek.
keywords: [C# Aspose.Cells., c# Convert chart to image., c# Save chart to image., c# chart to image., create charts in c#., insert charts in c#., manage charts in c#]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel-bestandsgrafieken maken en converteren via .NET" h2="Maak Excel-documentdiagrammen en converteer naar afbeeldingen met behulp van server-side API\'s binnen op .NET gebaseerde applicaties." >}}
{{% blocks/products/pf/feature-page-summary %}}
 Grafieken tekenen is een kunst om gegevens grafisch weer te geven voor eenvoudige analyse.[.NET Excel-bibliotheek](/cells/nl/net/) ondersteunt het tekenen van grafieken in Excel-bestanden. API ondersteunt verschillende diagramcreaties die worden vermeld in[ChartType-opsomming](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype) inclusief taart-, piramide-, lijn- en bellendiagrammen. Bovendien converteert het ook grafieken naar afbeeldingen. API biedt een[Grafieken klasse](https://reference.aspose.com/cells/net/aspose.cells.charts) voor diagrambouwstenen.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Maak grafieken in Excel-bestand" %}}

 Grafieken maken met Excel API is eenvoudig. Het proces is: creëren[Werkmap klasse](https://reference.aspose.com/cells/net/aspose.cells/workbook)object en selecteer het eerste werkblad of het relevante blad door de index ervan op te geven. Voeg de vereiste celgegevens in met behulp van[PutValue-methode](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index) . Voeg een diagram toe aan het werkblad met behulp van de Charts-collectie[Methode toevoegen](https://reference.aspose.com/cells/net/aspose.cells.charts/chartcollection/methods/add) . Specificeer de[Grafiektype](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype) van ChartType-opsomming.
{{% blocks/products/pf/feature-page-code h3="C# Code om Excel-grafieken te maken" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "create-excel-chart.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section h2="Converteer Excel-grafieken naar afbeeldingen" %}}

 Het proces voor het converteren van diagrammen naar afbeeldingen is: gebruik de Workbook-klasse om het Excel-bestand te laden, selecteer de relevante werkset die de diagrammen bevat en roep de[ToImage-methode](https://reference.aspose.com/cells/net/aspose.cells.charts.chart/toimage/methods/7) voor conversie.

{{% blocks/products/pf/feature-page-code h3="C# Code om Excel-diagram naar afbeelding te converteren" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "convert-xlsx-file-chart-to-images.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}
