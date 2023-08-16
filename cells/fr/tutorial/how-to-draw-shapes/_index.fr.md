---
title: Comment ajouter des formes via Aspose.Cells
weight: 7700
limit:
description: Découvrez comment ajouter des formes.
keywords: [add shapes., how to add shapes in Aspose.Cells., how to add shapes using Aspose.Cells]
url: /fr/tutorial/add-shapes-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Apprenez à ajouter des formes avec Aspose.Cells" >}}

<p>
Dans ce tutoriel, nous allons ajouter des formes dans un fichier Excel.
</p>

<p>
 Nous allons commencer par créer un nouveau classeur à l'aide de<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells bibliothèque</a> et ajouter des formes.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary : veuillez vérifier le code suivant pour savoir comment ajouter des formes.
//ExStepSummary:0 : le code suivant montre comment ajouter une forme de rectangle.
//ExStepImage:0:step-1.png
//ExStepSummary:1 : le code suivant montre comment ajouter une forme de ligne.
//ExStepImage:1:step-2.png
//ExStepSummary:2 : le code suivant montre comment ajouter une forme ovale.
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
en utilisant Aspose.Cells ;
en utilisant Aspose.Cells.Dessin ;





classeur classeur = nouveau classeur();
Feuille de calcul = workbook.Worksheets[0] ;
feuille.PageSetup.PrintGridlines = vrai;
feuille.PageSetup.PrintArea = "A1:F20";

Formes ShapeCollection = feuille. Formes ;

//Ajouter une forme de rectangle
formes.AjouterRectangle(1, 0, 1, 0, 100, 150);

//ExStep:1-
//Ajouter une forme de ligne
formes. AddLine (8, 0, 1, 0, 100, 150);

//ExStep:2-
//Ajouter une forme ovale
formes.AddOval(13, 0, 1, 0, 100, 150);

//ExStep:0-
classeur
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