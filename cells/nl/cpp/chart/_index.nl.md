---
title: Maak Excel-grafieken en converteer naar afbeeldingen via C++
description: C++ broncode om grafiek of diagram in Microsoft Excel te tekenen en om te zetten met behulp van C++ Library
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Maak Microsoft<sup>&reg;</sup> Excel-grafieken en converteer naar afbeeldingen via C++" h2="Converteer Excel-documentgrafieken naar afbeeldingen en maak grafieken, waaronder cirkel-, piramide-, lijn- en bellendiagrammen binnen op C++ gebaseerde applicaties." >}}

{{% blocks/products/pf/feature-page-summary %}}

 Met behulp van Excel-grafieken kan men een groter beeld krijgen en gemakkelijk gegevens analyseren om de juiste beslissingen te nemen.[C++ Excel-bibliotheek](/cells/nl/cpp/) ondersteunt het maken van verschillende grafieken vermeld op[enum Aspose::Cells::Charts::ChartType
](https://reference.aspose.com/cells/cpp/namespace/aspose.cells.charts#a2f17e69bcefc754569019185d0621b70) inclusief vlak-, staaf-, taart-, piramide-, lijn- en bellendiagrammen. Bovendien biedt API voor het converteren van grafieken naar afbeeldingen een[ToImage methode](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_sparkline#a28d76dd585c48366e1657f2982722ddb) in het vereiste afbeeldingsformaat.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Maak Excel-grafieken" %}}

 Het proces van het maken van een Excel-grafiek is, maak een exemplaar van de[IWorkbook klasse](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) en selecteer de gewenste[Werkblad](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet_collection#a5574d624796043233420d0e0459ccc43) . Voeg de grafiek toe met behulp van[Methode toevoegen](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_chart_collection#ab7e8cce835c251a4682605299a6aa068)met relevante parameters, waaronder grafiektype. Toegang tot de grafiek via index en[Toevoegen](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_series_collection#a8f4dc4d883f32f65b1fb673e2aa7862f) de gegevensbron voor het diagram.

{{% blocks/products/pf/feature-page-code h3="C++ Code om Excel-grafieken te maken" %}}

{{< gist "aspose-com-gists" "da2fd423617bf9013a7673870c81d708" "create-excel-chart.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Converteer grafieken naar afbeeldingen" %}}


Voor het converteren van grafieken is het proces, maak eerst een grafiek van het relevante type met behulp van bovenstaande code of open deze vanuit het relevante blad. Definieer het uitvoeropslagpad voor afbeeldingen en gebruik de ToImage-methode voor conversie.

 
{{% blocks/products/pf/feature-page-code h3="C++ Code om Excel-grafieken te converteren" %}}

{{< gist "aspose-com-gists" "da2fd423617bf9013a7673870c81d708" "convert-excel-chart-to-image.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}
