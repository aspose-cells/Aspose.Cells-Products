---
title: Créez des graphiques Excel et convertissez-les en images via C++
description: Code source C++ pour dessiner et convertir un graphique ou un diagramme dans Excel Microsoft à l'aide de la bibliothèque C++
keywords: [C++ Aspose.Cells., C++ Convert chart to image., C++ Save chart to image., C++ chart to image., create charts in C++., insert charts in C++., manage charts in C++]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Créez des graphiques Excel Microsoft<sup>&reg;</sup> et convertissez-les en images via C++" h2="Convertissez les graphiques de documents Excel en images et créez des graphiques, notamment des graphiques à secteurs, en pyramide, en courbes et à bulles dans les applications basées sur C++." >}}

{{% blocks/products/pf/feature-page-summary %}}

 À l’aide de graphiques Excel, on peut avoir une vue d’ensemble et analyser facilement les données pour prendre les bonnes décisions.[C++ Bibliothèque Excel](/cells/fr/cpp/) prend en charge la création de différents graphiques répertoriés par[enum Aspose :: Cells :: Charts :: ChartType
](https://reference.aspose.com/cells/cpp/aspose.cells.charts/charttype/) y compris les graphiques à aires, à barres, à secteurs, en pyramide, en courbes et à bulles. De plus, pour la conversion de graphiques en images, API fournit un[VersImage](https://reference.aspose.com/cells/cpp/aspose.cells.charts/chart/toimage/) converti dans le format d'image requis.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Créer des graphiques Excel" %}}

 Le processus de création d'un graphique Excel consiste à créer une instance du[Classe de classeur](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) et sélectionnez le souhaité[Feuille de travail](https://reference.aspose.com/cells/cpp/aspose.cells/worksheet/) . Ajoutez le graphique en utilisant[Ajouter une méthode](https://reference.aspose.com/cells/cpp/aspose.cells.charts/chartcollection/add/)avec les paramètres pertinents, y compris le type de graphique. Accédez au graphique via index et[Ajouter](https://reference.aspose.com/cells/cpp/aspose.cells.charts/seriescollection/add/) la source de données pour le graphique.

{{% blocks/products/pf/feature-page-code h3="C++ Code pour créer des graphiques Excel" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "create-excel-chart.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Convertir des graphiques en images" %}}


Pour le processus de conversion de graphiques, créez d'abord un graphique du type pertinent en utilisant le code ci-dessus ou accédez-y à partir de la feuille appropriée. Définissez le chemin d’enregistrement de sortie pour l’image et utilisez la méthode ToImage pour la conversion.

 
{{% blocks/products/pf/feature-page-code h3="C++ Code pour convertir des graphiques Excel" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "convert-excel-chart-to-image.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}
