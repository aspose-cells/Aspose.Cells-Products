---
title: Création de graphiques Excel et conversion en images via .NET
url: /fr/net/chart/
description: Code source C# pour dessiner et convertir un graphique ou un diagramme dans Microsoft Excel à l'aide de la bibliothèque .NET. 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Création et conversion de graphiques de fichiers Microsoft<sup>&reg;</sup> Excel via .NET" h2="Créez des tableaux de documents Excel et convertissez-les en images à l\'aide d\'API côté serveur dans des applications basées sur .NET." >}}
{{% blocks/products/pf/feature-page-summary %}}
Dessiner des graphiques est un art d'afficher des données graphiquement pour une analyse facile. [.NET Bibliothèque Excel](/cells/net/) prend en charge les graphiques de dessin dans les fichiers Excel. API prend en charge différentes créations de graphiques répertoriées dans [Énumération de type de graphique](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype) y compris les diagrammes circulaires, pyramidaux, linéaires et à bulles. De plus, il convertit également les graphiques en images. API fournit un [Classe de graphiques](https://reference.aspose.com/cells/net/aspose.cells.charts) pour les blocs de construction de graphique.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Créer des graphiques dans un fichier Excel" %}}

La création de graphiques à l'aide d'Excel API est simple. Le processus est, Créer [Classe de classeur](https://reference.aspose.com/cells/net/aspose.cells/workbook) objet et sélectionnez la première feuille de calcul ou la feuille pertinente en fournissant son index. Insérez les données de cellules requises à l'aide de [Méthode PutValue](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index). Ajouter un graphique à la feuille de calcul à l'aide de la collection Charts [Ajouter une méthode](https://reference.aspose.com/cells/net/aspose.cells.charts/chartcollection/methods/add). Spécifie le [Type de graphique](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype) à partir de l'énumération ChartType.
{{% blocks/products/pf/feature-page-code h3="C# Code pour créer des graphiques Excel" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "create-excel-chart.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section h2="Convertir des graphiques Excel en images" %}}

Le processus de conversion des graphiques en images consiste à utiliser la classe Workbook pour charger le fichier Excel, sélectionner le workset approprié contenant les graphiques et appeler le [Méthode ToImageToImage method](https://reference.aspose.com/cells/net/aspose.cells.charts.chart/toimage/methods/7) pour conversion.

{{% blocks/products/pf/feature-page-code h3="C# Code pour convertir le graphique Excel en image" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "convert-xlsx-file-chart-to-images.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}