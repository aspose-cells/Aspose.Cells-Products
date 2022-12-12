---
title: Maak Excel-diagrammen en converteer naar afbeeldingen via C++

description: C++ broncode om een diagram of diagram in Microsoft Excel te tekenen en te converteren met C++Bibliotheek
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Maak Microsoft<sup>&reg;</sup> Excel-diagrammen en converteer naar afbeeldingen via C++" h2="Converteer Excel-documentdiagrammen naar afbeeldingen en maak diagrammen, waaronder taart-, piramide-, lijn- en bellendiagrammen in op C++ gebaseerde toepassingen." >}}

{{% blocks/products/pf/feature-page-summary %}}

Met behulp van Excel-diagrammen kan men het grotere geheel krijgen en gegevens gemakkelijk analyseren om de juiste beslissingen te nemen. [C++ Excel-bibliotheek](/cells/cpp/) ondersteunt het maken van verschillende grafieken weergegeven door [opsomming Aspose::Cells::Charts::ChartType
](https://reference.aspose.com/cells/cpp/namespace/aspose.cells.charts#a2f17e69bcefc754569019185d0621b70) inclusief oppervlakte-, staaf-, taart-, piramide-, lijn- en bellendiagrammen. Bovendien biedt API voor de conversie van grafieken naar afbeeldingen een: [NaarAfbeeldingsmethode](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_sparkline#a28d76dd585c48366e1657f2982722ddb) in het vereiste afbeeldingsformaat.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Excel-diagrammen maken" %}}

Het proces van het maken van een Excel-diagram is, maak een exemplaar van de [IWorkbook klasse](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) en selecteer de gewenste [werkblad](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet_collection#a5574d624796043233420d0e0459ccc43). Voeg de grafiek toe met [Methode toevoegen](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_chart_collection#ab7e8cce835c251a4682605299a6aa068) met relevante parameters inclusief grafiektype. Toegang tot de grafiek via index en [Toevoegen](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_series_collection#a8f4dc4d883f32f65b1fb673e2aa7862f) de gegevensbron voor de grafiek.

{{% blocks/products/pf/feature-page-code h3="C++ Code om Excel-diagrammen te maken" %}}

{{< gist "aspose-com-gists" "da2fd423617bf9013a7673870c81d708" "create-excel-chart.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Grafieken converteren naar afbeeldingen" %}}


Voor het converteren van grafieken moet u eerst een grafiek maken van het relevante type met behulp van bovenstaande code of deze openen vanaf het relevante blad. Definieer het uitvoeropslagpad voor afbeelding en gebruik de ToImage-methode voor conversie.

 
{{% blocks/products/pf/feature-page-code h3="C++ Code om Excel-diagrammen te converteren" %}}

{{< gist "aspose-com-gists" "da2fd423617bf9013a7673870c81d708" "convert-excel-chart-to-image.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}
