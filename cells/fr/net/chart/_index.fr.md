---
title: Création de graphiques Excel et conversion en images via .NET
description:  Code source C# pour dessiner et convertir un graphique ou un diagramme dans Excel Microsoft à l'aide de la bibliothèque .NET.
keywords: [C# Aspose.Cells., c# Convert chart to image., c# Save chart to image., c# chart to image., create charts in c#., insert charts in c#., manage charts in c#]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Création et conversion de graphiques de fichiers Excel via .NET" h2="Créez des graphiques de documents Excel et convertissez-les en images à l\'aide des API côté serveur dans les applications basées sur .NET." >}}
{{% blocks/products/pf/feature-page-summary %}}
 Dessiner des graphiques est un art pour afficher des données graphiquement pour une analyse facile.[.NET Bibliothèque Excel](/cells/fr/net/) prend en charge le dessin de graphiques dans des fichiers Excel. API prend en charge différentes créations de graphiques répertoriées dans[Énumération ChartType](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype) y compris des graphiques à secteurs, pyramides, courbes et à bulles. De plus, il convertit également les graphiques en images. API fournit un[Classe de graphiques](https://reference.aspose.com/cells/net/aspose.cells.charts) pour les blocs de construction de graphiques.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Créer des graphiques dans un fichier Excel" %}}

 La création de graphiques à l'aide d'Excel API est simple. Le processus est, créer[Classe de classeur](https://reference.aspose.com/cells/net/aspose.cells/workbook)objet et sélectionnez la première feuille de calcul ou la feuille concernée en fournissant son index. Insérez les données de cellules requises en utilisant[Méthode PutValue](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index) . Ajoutez un graphique à la feuille de calcul à l'aide de la collection Charts.[Ajouter une méthode](https://reference.aspose.com/cells/net/aspose.cells.charts/chartcollection/methods/add) . Spécifie le[Type de graphique](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype) à partir de l’énumération ChartType.
{{% blocks/products/pf/feature-page-code h3="C# Code pour créer des graphiques Excel" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "create-excel-chart.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section h2="Convertir des graphiques Excel en images" %}}

 Le processus de conversion de graphiques en images consiste à utiliser la classe Workbook pour charger le fichier Excel, à sélectionner la classe de travail appropriée contenant les graphiques et à appeler le[Méthode ToImage](https://reference.aspose.com/cells/net/aspose.cells.charts.chart/toimage/methods/7) pour conversion.

{{% blocks/products/pf/feature-page-code h3="C# Code pour convertir un graphique Excel en image" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "convert-xlsx-file-chart-to-images.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}
