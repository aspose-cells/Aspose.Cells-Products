---
title: Comment ajouter un graphique linéaire via Aspose.Cells
weight: 7700
limit:
description: Découvrez comment ajouter un graphique en courbes.
keywords: [Add line chart., how to add line chart in Aspose.Cells., how to add line chart using Aspose.Cells]
url: /fr/tutorial/add-line-chart-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Apprenez à ajouter un graphique en courbes avec Aspose.Cells" >}}

<p>
Dans ce didacticiel, nous allons ajouter un graphique linéaire dans un fichier Excel.
</p>

<p>
 Nous allons commencer par créer un nouveau classeur à l'aide de<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells bibliothèque</a> et ajouter un graphique en courbes.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary : Veuillez vérifier le code suivant pour savoir comment ajouter un graphique en courbes.
//ExStepSummary:0 : le code suivant montre comment ajouter un graphique en courbes, définir une plage de données de série et définir une plage de données de catégorie.
//ExStepImage:0:step-1.png
//ExStepSummary:1 : le code suivant montre comment déplacer la légende vers le bas et définir la couleur de la police de la légende.
//ExStepImage:1:step-2.png
//ExStepSummary:2 : le code suivant montre comment accéder aux étiquettes de données, activer les noms de catégorie et définir la position.
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
en utilisant Aspose.Cells ;
en utilisant Aspose.Cells.Dessin ;

classeur classeur = nouveau classeur();
Feuille de calcul = workbook.Worksheets[0] ;
feuille.Name = "ChartSheet" ;
Cells cellules = feuille.Cells ;
cellules["A1"].Valeur = "Fruit" ;
cellules["A2"].Valeur = "pomme" ;
cellules["A3"].Valeur = "orange" ;
cellules["A4"].Valeur = "myrtille" ;
cellules["A5"].Valeur = "kiwi" ;

cellules["B1"].Valeur = "Prix" ;
cellules["B2"].Valeur = 10 ;
cellules["B3"].Valeur = 5 ;
cellules["B4"].Valeur = 20 ;
cellules["B5"].Valeur = 8 ;

feuille.PageSetup.PrintGridlines = vrai;
feuille.PageSetup.PrintArea = "A1:F20";

Graphiques ChartCollection = feuille.Charts ;

// Ajouter un graphique linéaire, définir la plage de données de la série et définir la plage de données de la catégorie
int index = feuille.Charts.Add(ChartType.Line, 6, 0, 19, 5);
Graphique graphique = feuille.Charts[index] ;
chart.NSeries.Add("B2:B5", vrai);
chart.NSeries.CategoryData = "A2:A5" ;

//ExStep:1-
//Déplacer la légende vers le bas et définir la couleur de la police de la légende
chart.Legend.Font.Color = Couleur.Bleu ;
chart.Legend.Position = LegendPositionType.Bottom ;

//ExStep:2-
// Accéder aux étiquettes de données, activer les noms de catégorie et définir la position
DataLabels dataLabels = chart.NSeries[0].DataLabels ;
dataLabels.ShowCategoryName = true ;
dataLabels.Position = LabelPositionType.Center ;

//ExStep:0-

//ExFin
{{< /app/cells/tutorial >}}
<br />

<br />
<br />
<div class="code-sample">
    <ul class="link-list">
        <li class="link-item"><a href="https://docs.aspose.com/cells/net/installation/">Mise en place du Aspose.Cells</a></li>
        <li class="link-item"><a href="https://products.aspose.app/cells/editor/">Aspose.Cells Éditeur</a></li>
    </ul>
</div>

{{< /blocks/products/pf/feature-page-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}