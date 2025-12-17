---
title: Créez des graphiques Excel et convertissez-les en images avec Go via C++
description: Utilisez le code source C++ pour dessiner et convertir un graphique ou un diagramme dans Excel Microsoft à l'aide de la bibliothèque Go via C++.
keywords: [Go via C++ Aspose.Cells., Go via C++ Convert chart to image., Go via C++ Save chart to image., Go via C++ chart to image., create charts in Go via C++., insert charts in Go via C++., manage charts in Go via C++]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Créez des graphiques Excel (Microsoft) et convertissez-les en images avec Go via C++" h2="Convertissez les graphiques de documents Excel en images et créez des graphiques, notamment des graphiques circulaires, pyramidaux, linéaires et à bulles, dans Go via des applications basées sur C++." >}}

{{% blocks/products/pf/feature-page-summary %}}

 Grâce aux graphiques Excel, on peut avoir une vue d'ensemble et analyser facilement les données afin de prendre les bonnes décisions.[Accédez à la bibliothèque Excel via C++](/cells/fr/go-cpp/) permet de créer différents graphiques répertoriés par[énumération Aspose::Cells::Charts::ChartType
](https://reference.aspose.com/cells/go-cpp/charttype/) y compris les graphiques en aires, à barres, circulaires, pyramidaux, linéaires et à bulles. De plus, pour la conversion des graphiques en images, API fournit une[ToImage](https://reference.aspose.com/cells/go-cpp/chart/toimage_string/) méthode dans le format d'image requis.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Créer des graphiques Excel" %}}

 Le processus de création d'un graphique Excel consiste à créer une instance de celui-ci.[Classe de cahier d'exercices](https://reference.aspose.com/cells/go-cpp/workbook/) et sélectionnez le désiré[Feuille de travail](https://reference.aspose.com/cells/go-cpp/worksheet/) Ajoutez le graphique en utilisant[Ajouter une méthode](https://reference.aspose.com/cells/go-cpp/chartcollection/addfloatingchart/) avec les paramètres pertinents, notamment le type de graphique. Accédez au graphique via l'index et[Ajouter](https://reference.aspose.com/cells/go-cpp/seriescollection/add_string_bool_bool/)la source de données du graphique.

{{% blocks/products/pf/feature-page-code h3="Utilisez le code C++ pour créer des graphiques Excel." %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "create-excel-chart.go" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Convertir les graphiques en images" %}}


Pour convertir un graphique, commencez par créer un graphique du type approprié à l'aide du code ci-dessus ou accédez-y depuis la feuille correspondante. Définissez ensuite le chemin d'enregistrement de l'image et utilisez la méthode ToImage pour la conversion.


{{% blocks/products/pf/feature-page-code h3="Utilisez le code C++ pour convertir les graphiques Excel." %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "convert-excel-chart-to-image.go" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}


{{< /blocks/products/pf/feature-page-wrap >}}