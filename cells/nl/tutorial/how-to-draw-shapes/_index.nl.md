---
title: Vormen toevoegen via Aspose.Cells
weight: 7700
limit:
description: Leer hoe u vormen kunt toevoegen.
keywords: [add shapes., how to add shapes in Aspose.Cells., how to add shapes using Aspose.Cells]
url: /nl/tutorial/add-shapes-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Leer hoe je vormen toevoegt met Aspose.Cells" >}}

<p>
In deze zelfstudie voegen we vormen toe aan een Excel-bestand.
</p>

<p>
 We beginnen met het maken van een nieuwe werkmap met behulp van de<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells bibliotheek</a> en voeg vormen toe.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: controleer de volgende code om erachter te komen hoe u vormen kunt toevoegen.
//ExStepSummary:0: De volgende code laat zien hoe een rechthoekige vorm kan worden toegevoegd.
//ExStepImage:0:stap-1.png
//ExStepSummary:1: De volgende code laat zien hoe een lijnvorm kan worden toegevoegd.
//ExStepImage:1:step-2.png
//ExStepSummary:2: De volgende code laat zien hoe je een ovale vorm kunt toevoegen.
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
met behulp van Aspose.Cells;
met behulp van Aspose.Cells.Tekening;





Werkmap werkmap = nieuwe werkmap();
Werkblad = werkboek. Werkbladen [0];
blad.PageSetup.PrintGridlines = waar;
blad.PageSetup.PrintArea = "A1:F20";

ShapeCollection-vormen = blad.Vormen;

// Voeg een rechthoekige vorm toe
vormen.ToevoegenRechthoek(1, 0, 1, 0, 100, 150);

//ExStap:1-
// Lijnvorm toevoegen
vormen.AddLine(8, 0, 1, 0, 100, 150);

//ExStep:2-
//Voeg ovale vorm toe
vormen.AddOval(13, 0, 1, 0, 100, 150);

//ExStep:0-
werkboek
//ExEnd
{{< /app/cells/tutorial >}}
<br />

<br />
<br />
<div class="code-sample">
    <ul class="link-list">
        <li class="link-item"><a href="https://docs.aspose.com/cells/net/installation/">Installatie van Aspose.Cells</a></li>
        <li class="link-item"><a href="https://products.aspose.app/cells/editor/">Aspose.Cells Redacteur</a></li>
    </ul>
</div>

{{< /blocks/products/pf/feature-page-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}