---
title: Comment ajouter un diagramme circulaire via Aspose.Cells
weight: 7700
limit:
description: Découvrez comment ajouter un diagramme circulaire.
keywords: [Add pie chart., how to add pie chart in Aspose.Cells., how to add pie chart using Aspose.Cells]
url: /fr/tutorial/add-pie-chart-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Apprenez à ajouter un diagramme circulaire avec Aspose.Cells" >}}

<p>
Dans ce didacticiel, nous ajouterons un diagramme circulaire dans un fichier Excel.
</p>

<p>
 Nous allons commencer par créer un nouveau classeur en utilisant le<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells bibliothèque</a> et ajoutez un diagramme circulaire.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary : veuillez vérifier le code suivant pour savoir comment ajouter un diagramme circulaire.
//ExStepSummary:0 : Le code suivant montre comment ajouter un diagramme circulaire, définir la plage de données de série et définir la plage de données de catégorie.
//ExStepImage:0:étape-1.png
//ExStepSummary:1 : Le code suivant montre comment désactiver la légende.
//ExStepImage:1:étape-2.png
//ExStepSummary:2 : Le code suivant montre comment accéder aux étiquettes de données, activer les noms de catégorie, activer le format de pourcentage et définir la position.
//ExStepImage:2:étape-3.png
//ExDébut
//ExStep:0-
en utilisant le Aspose.Cells ;
en utilisant Aspose.Cells.Dessin ;

Classeur workbook = new Workbook();
Feuille de calcul = workbook.Worksheets[0];
feuille.Name = "ChartSheet";
Cells cellules = feuille.Cells ;
cellules["A1"].Value = "Fruit";
cellules["A2"].Value = "pomme";
cellules["A3"].Value = "orange";
cellules["A4"].Value = "myrtille";
cellules["A5"].Value = "kiwi";

cellules["B1"].Value = "Prix";
cellules["B2"].Valeur = 10 ;
cellules["B3"].Valeur = 5;
cellules["B4"].Valeur = 20 ;
cellules["B5"].Valeur = 8;

sheet.PageSetup.PrintGridlines = true;
feuille.PageSetup.PrintArea = "A1:F20";

Graphiques ChartCollection = feuille.Charts;

//Ajouter un diagramme circulaire, définir la plage de données de série et définir la plage de données de catégorie
int index = sheet.Charts.Add(ChartType.Pie, 6, 0, 19, 5);
Graphique chart = sheet.Charts[index];
chart.NSeries.Add("B2:B5", vrai);
chart.NSeries.CategoryData = "A2:A5";

//ExStep:1-
//Désactiver la légende
chart.ShowLegend = false;

//ExStep:2-
//Accéder aux étiquettes de données, activer les noms de catégories, activer le format de pourcentage et définir la position
DataLabels dataLabels = chart.NSeries[0].DataLabels;
dataLabels.ShowCategoryName = true ;
dataLabels.ShowPercentage = true ;
dataLabels.Position = LabelPositionType.OutsideEnd ;

//ExStep:0-

//ExFin
{{< /app/cells/tutorial >}}
<br />

<br />
<br />
<div class="code-sample">
    <ul class="link-list">
        <li class="link-item"><a href="https://docs.aspose.com/cells/net/installation/">Installation du Aspose.Cells</a></li>
        <li class="link-item"><a href="https://products.aspose.app/cells/editor/">Aspose.Cells Editeur</a></li>
    </ul>
</div>

{{< /blocks/products/pf/feature-page-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}