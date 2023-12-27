---
title: Créer des graphiques Excel et convertir en images via Java
description:  Code source Java pour dessiner et convertir un graphique ou un diagramme dans Excel Microsoft à l'aide de la bibliothèque Java.
keywords: [Java Aspose.Cells., Java Convert chart to image., Java Save chart to image., Java chart to image., create charts in Java., insert charts in Java., manage charts in Java]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Conversion et création de graphiques de fichiers Excel via Java" h2="Convertissez les graphiques de documents Excel en images et créez divers graphiques à l\'aide d\'API côté serveur dans les applications basées sur Java." >}}


{{% blocks/products/pf/feature-page-summary %}}

 L'analyse des données via des graphiques montre une vue d'ensemble et il est facile de prendre des décisions plus éclairées avec des informations plus claires.[Java Bibliothèque Excel](/cells/fr/java/) prend en charge le dessin de différentes créations de graphiques répertoriées par[Type de graphique](https://reference.aspose.com/cells/java/com.aspose.cells/ChartType) y compris des graphiques à secteurs, pyramides, courbes et à bulles. De plus, il convertit également les graphiques en images. API fournit un[Classe de graphiques](https://reference.aspose.com/cells/java/com.aspose.cells/Chart) pour représenter un seul graphique Excel.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Convertir des graphiques Excel en images" %}}

 Le processus de conversion de graphiques en images, notamment JPG, PNG, TIFF, BMP, etc., utilise le[Cahier d'exercices](https://reference.aspose.com/java/cells/com.aspose.cells/workbook) classe pour charger le fichier Excel, sélectionnez la classe appropriée[table de travail](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet) contenant les graphiques ou parcourir chaque graphique dans chaque feuille de calcul. Définir[Options ImageOuImpression](https://reference.aspose.com/cells/java/com.aspose.cells/ImageOrPrintOptions) et restituez l'image de sortie du graphique en utilisant[Graphique.toImage](https://reference.aspose.com/cells/java/com.aspose.cells/chart#toImage(java.io.OutputStream,%20com.aspose.cells.ImageOrPrintOptions)).


{{% blocks/products/pf/feature-page-code h3="Java Code pour convertir un graphique Excel en image" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "render-excel-chart-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}


{{% blocks/products/pf/feature-page-section h2="Créer des graphiques dans un fichier Excel" %}}

La création de graphiques à l'aide d'Excel API est simple, car API fournit un ensemble de différentes classes telles que Axis, Chart, ChartArea, ChartDataTable, ChartFrame, ChartPoint, ChartPointCollection, ChartCollection, etc. pour différents types de graphiques. Le processus consiste à créer un objet de classe Workbook et à sélectionner la première feuille de calcul ou la feuille appropriée en fournissant son index. Pour la source de données du graphique, insérez des valeurs dans les cellules de la feuille de calcul à l'aide de[définirValeur](https://reference.aspose.com/cells/java/com.aspose.cells/cell#Value) méthode. Utiliser la collection ChartCollection[ajouter une méthode](https://reference.aspose.com/cells/java/com.aspose.cells/chartcollection#add(int,%20int,%20int,%20int,%20int) ) pour ajouter le graphique, définissez le type de graphique avec l'énumération ChartType. Accédez au nouvel objet Chart de la collection ChartCollection en passant son index. Utilisez le[SérieCollection](https://reference.aspose.com/cells/java/com.aspose.cells/SeriesCollection) objet graphique pour spécifier la source de données du graphique.

{{% blocks/products/pf/feature-page-code h3="Java Code pour créer des graphiques Excel" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "create-excel-chart-pyramid.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
