---
title: Comment ajouter des formes via Aspose.Cells
weight: 7700
limit:
description: Apprenez à ajouter des formes.
keywords: [add shapes., how to add shapes in Aspose.Cells., how to add shapes using Aspose.Cells]
url: /fr/tutorial/add-shapes-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Apprenez à ajouter des formes avec le Aspose.Cells" >}}

<p>
Dans ce didacticiel, nous ajouterons des formes dans un fichier Excel.
</p>

<p>
 Nous allons commencer par créer un nouveau classeur en utilisant le<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells bibliothèque</a> et ajoutez des formes.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary : veuillez vérifier le code suivant pour savoir comment ajouter des formes.
//ExStepSummary:0 : Le code suivant montre comment ajouter une forme rectangulaire.
//ExStepImage:0:étape-1.png
//ExStepSummary:1 : Le code suivant montre comment ajouter une forme de ligne.
//ExStepImage:1:étape-2.png
//ExStepSummary:2 : Le code suivant montre comment ajouter une forme ovale.
//ExStepImage:2:étape-3.png
//ExDébut
//ExStep:0-
en utilisant le Aspose.Cells ;
en utilisant Aspose.Cells.Dessin ;





Classeur workbook = new Workbook();
Feuille de calcul = workbook.Worksheets[0];
sheet.PageSetup.PrintGridlines = true;
feuille.PageSetup.PrintArea = "A1:F20";

Formes ShapeCollection = feuille.Shapes;

//Ajouter une forme de rectangle
formes.AddRectangle(1, 0, 1, 0, 100, 150);

//ExStep:1-
//Ajouter une forme de ligne
formes.AddLine(8, 0, 1, 0, 100, 150);

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
        <li class="link-item"><a href="https://docs.aspose.com/cells/net/installation/">Installation du Aspose.Cells</a></li>
        <li class="link-item"><a href="https://products.aspose.app/cells/editor/">Aspose.Cells Editeur</a></li>
    </ul>
</div>

{{< /blocks/products/pf/feature-page-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}