---
title: Maak Excel-grafieken en converteer naar afbeeldingen via C++
description: C++ broncode om diagram of diagram te tekenen en te converteren in Microsoft Excel met behulp van de C++-bibliotheek
keywords: [C++ Aspose.Cells., C++ Convert chart to image., C++ Save chart to image., C++ chart to image., create charts in C++., insert charts in C++., manage charts in C++]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Maak Microsoft<sup>&reg;</sup> Excel-grafieken en converteer naar afbeeldingen via C++" h2="Converteer Excel-documentdiagrammen naar afbeeldingen en maak diagrammen, waaronder cirkel-, piramide-, lijn- en bellendiagrammen binnen op C++ gebaseerde toepassingen." >}}

{{% blocks/products/pf/feature-page-summary %}}

 Met behulp van Excel-grafieken krijgt u een groter beeld en kunt u gegevens eenvoudig analyseren om de juiste beslissingen te nemen.[C++ Excel-bibliotheek](/cells/nl/cpp/) ondersteunt het maken van verschillende grafieken vermeld door[enum Aspose::Cells::Grafieken::ChartType
](https://reference.aspose.com/cells/cpp/aspose.cells.charts/charttype/) inclusief vlak-, staaf-, cirkel-, piramide-, lijn- en bellendiagrammen. Bovendien biedt API voor de conversie van grafieken naar afbeeldingen een[NaarAfbeelding](https://reference.aspose.com/cells/cpp/aspose.cells.charts/chart/toimage/) methode in het vereiste afbeeldingsformaat.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Excel-grafieken maken" %}}

 Het proces voor het maken van een Excel-diagram is: maak een exemplaar van het[Werkmap klasse](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) en selecteer de gewenste[Werkblad](https://reference.aspose.com/cells/cpp/aspose.cells/worksheet/) . Voeg het diagram toe met[Methode toevoegen](https://reference.aspose.com/cells/cpp/aspose.cells.charts/chartcollection/add/)met relevante parameters, inclusief diagramtype. Toegang tot het diagram via index en[Toevoegen](https://reference.aspose.com/cells/cpp/aspose.cells.charts/seriescollection/add/) de gegevensbron voor het diagram.

{{% blocks/products/pf/feature-page-code h3="C++ Code om Excel-grafieken te maken" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "create-excel-chart.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Converteer grafieken naar afbeeldingen" %}}


Voor het converteren van diagrammen moet u eerst een diagram van het relevante type maken met behulp van bovenstaande code of deze openen via het relevante blad. Definieer het uitvoeropslagpad voor de afbeelding en gebruik de ToImage-methode voor conversie.

 
{{% blocks/products/pf/feature-page-code h3="C++ Code om Excel-grafieken te converteren" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "convert-excel-chart-to-image.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}
