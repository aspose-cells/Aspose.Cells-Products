---
title: Comment ajouter un graphique à colonnes via Aspose.Cells
weight: 7700
limit:
description: Découvrez comment ajouter un histogramme.
keywords: [Add column chart., how to add column chart in Aspose.Cells., how to add column chart using Aspose.Cells]
url: /fr/tutorial/add-column-chart-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Apprenez à ajouter un graphique à colonnes avec Aspose.Cells" >}}

<p>
Dans ce didacticiel, nous allons ajouter un histogramme dans un fichier Excel.
</p>

<p>
 Nous allons commencer par créer un nouveau classeur à l'aide de<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells bibliothèque</a> et ajouter un graphique à colonnes.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary : Veuillez vérifier le code suivant pour savoir comment ajouter un histogramme.
//ExStepSummary:0 : le code suivant montre comment ajouter un histogramme.
//ExStepImage:0:step-1.png
//ExStepSummary:1 : le code suivant montre comment déplacer la légende vers la gauche et définir la couleur de la police de la légende.
//ExStepImage:1:step-2.png
//ExStepSummary:2 : le code suivant montre comment définir le titre d'un graphique et changer la couleur de la police en bleu.
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

//Ajouter un histogramme
int index = charts.Add(ChartType.Column, "=ChartSheet!A1:B5", false, 6, 0, 19, 5);
Graphique graphique = graphiques[index] ;

//ExStep:1-
// Déplacer la légende vers la gauche et définir la couleur de la police de la légende
chart.Legend.Font.Color = Couleur.Bleu ;
chart.Legend.Position = LegendPositionType.Left ;

//ExStep:2-
// Définissez le titre d'un graphique et changez la couleur de la police en bleu
chart.Title.Text = "Graphique à colonnes des prix des fruits" ;
chart.Title.Font.Color = Couleur.Bleu ;

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