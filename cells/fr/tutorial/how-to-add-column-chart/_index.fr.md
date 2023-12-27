---
title: Comment ajouter un histogramme via Aspose.Cells
weight: 7700
limit:
description: Découvrez comment ajouter un histogramme.
keywords: [Add column chart., how to add column chart in Aspose.Cells., how to add column chart using Aspose.Cells]
url: /fr/tutorial/add-column-chart-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Apprenez à ajouter un histogramme avec Aspose.Cells" >}}

<p>
Dans ce didacticiel, nous ajouterons un histogramme dans un fichier Excel.
</p>

<p>
 Nous allons commencer par créer un nouveau classeur en utilisant le<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells bibliothèque</a> et ajoutez un histogramme.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary : veuillez vérifier le code suivant pour savoir comment ajouter un histogramme.
//ExStepSummary:0 : le code suivant montre comment ajouter un histogramme.
//ExStepImage:0:étape-1.png
//ExStepSummary:1 : Le code suivant montre comment déplacer la légende vers la gauche et définir la couleur de police de la légende.
//ExStepImage:1:étape-2.png
//ExStepSummary:2 : Le code suivant montre comment définir le titre d'un graphique et changer la couleur de la police en bleu.
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

//Ajouter un histogramme
int index = charts.Add(ChartType.Column, "=ChartSheet!A1:B5", false, 6, 0, 19, 5);
Graphique graphique = graphiques[index] ;

//ExStep:1-
// Déplace la légende vers la gauche et définit la couleur de la police de la légende
chart.Legend.Font.Color = Couleur.Bleu;
chart.Legend.Position = LegendPositionType.Left;

//ExStep:2-
//Définit le titre d'un graphique et change la couleur de la police en bleu
chart.Title.Text = "Graphique à colonnes du prix des fruits";
chart.Title.Font.Color = Couleur.Bleu;

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