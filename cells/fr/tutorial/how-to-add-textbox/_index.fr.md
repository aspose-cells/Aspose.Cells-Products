---
title: Comment ajouter TextBox via Aspose.Cells
weight: 7700
limit:
description: Découvrez comment ajouter TextBox.
keywords: [Add TextBox., how to add TextBox in Aspose.Cells., how to add TextBox using Aspose.Cells]
url: /fr/tutorial/add-textbox-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Apprenez à ajouter TextBox avec Aspose.Cells" >}}

<p>
Dans ce tutoriel, nous allons ajouter TextBox dans un fichier Excel.
</p>

<p>
 Nous allons commencer par créer un nouveau classeur à l'aide de<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells bibliothèque</a> et ajoutez TextBox.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary : Veuillez vérifier le code suivant pour savoir comment ajouter TextBox.
//ExStepSummary:0 : le code suivant montre comment ajouter TextBox et définir du texte.
//ExStepImage:0:step-1.png
//ExStepSummary:1 : le code suivant montre comment changer la couleur du texte.
//ExStepImage:1:step-2.png
//ExStepSummary:2 : le code suivant montre comment modifier l'angle de rotation de TextBox.
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

// Ajouter TextBox et définir le texte
TextBox textBox = formes.AddTextBox(1, 0, 1, 0, 200, 200);
textBox.Text = "Aspose.Cells for .NET est une bibliothèque de classes de programmation qui permet aux développeurs de logiciels de manipuler et de traiter des fichiers de feuille de calcul dans leurs propres applications.";

//ExStep:1-
// Changer la couleur du texte
textBox.Font.Color = Couleur.Bleu ;

//ExStep:2-
//Modifier l'angle de rotation de TextBox
textBox. RotationAngle = 90 ;

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