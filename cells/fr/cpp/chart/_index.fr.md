---
title: Créer des graphiques Excel et convertir en images via C++

description: Code source C++ pour dessiner et convertir un graphique ou un diagramme dans Microsoft Excel à l'aide de la bibliothèque C++
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Créez des graphiques Excel Microsoft<sup>&reg;</sup> et convertissez-les en images via C++" h2="Convertissez des graphiques de documents Excel en images et créez des graphiques, notamment des graphiques à secteurs, pyramidaux, linéaires et à bulles dans des applications basées sur C++." >}}

{{% blocks/products/pf/feature-page-summary %}}

À l'aide de graphiques Excel, on peut obtenir une vue d'ensemble et analyser facilement les données pour prendre les bonnes décisions. [C++ Bibliothèque Excel](/cells/cpp/) prend en charge la création de différents graphiques répertoriés par [énumération Aspose::Cells::Charts::ChartType
](https://reference.aspose.com/cells/cpp/namespace/aspose.cells.charts#a2f17e69bcefc754569019185d0621b70) y compris les graphiques en aires, à barres, à secteurs, pyramidaux, linéaires et à bulles. De plus, pour la conversion des graphiques en images, API fournit un [Méthode ToImage](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_sparkline#a28d76dd585c48366e1657f2982722ddb) dans le format d'image requis.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Créer des graphiques Excel" %}}

Le processus de création d'un graphique Excel consiste à créer une instance du [Classe IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) et sélectionnez la [Feuille de travail](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet_collection#a5574d624796043233420d0e0459ccc43). Ajoutez le graphique à l'aide de [Ajouter une méthode](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_chart_collection#ab7e8cce835c251a4682605299a6aa068) avec les paramètres pertinents, y compris le type de graphique. Accédez au graphique via l'index et [Ajouter](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_series_collection#a8f4dc4d883f32f65b1fb673e2aa7862f) la source de données pour le graphique.

{{% blocks/products/pf/feature-page-code h3="C++ Code pour créer des graphiques Excel" %}}

{{< gist "aspose-com-gists" "da2fd423617bf9013a7673870c81d708" "create-excel-chart.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Convertir des graphiques en images" %}}


Pour le processus de conversion des graphiques, créez d'abord un graphique de type pertinent en utilisant le code ci-dessus ou accédez-y à partir de la feuille appropriée. Définissez le chemin d'enregistrement de sortie pour l'image et utilisez la méthode ToImage pour la conversion.

 
{{% blocks/products/pf/feature-page-code h3="C++ Code pour convertir les graphiques Excel" %}}

{{< gist "aspose-com-gists" "da2fd423617bf9013a7673870c81d708" "convert-excel-chart-to-image.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}
