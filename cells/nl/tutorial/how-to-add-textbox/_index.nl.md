---
title: Hoe TextBox toe te voegen via Aspose.Cells
weight: 7700
limit:
description: Leer hoe u TextBox kunt toevoegen.
keywords: [Add TextBox., how to add TextBox in Aspose.Cells., how to add TextBox using Aspose.Cells]
url: /nl/tutorial/add-textbox-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Leer hoe u TextBox kunt toevoegen met Aspose.Cells" >}}

<p>
In deze zelfstudie voegen we TextBox toe aan een Excel-bestand.
</p>

<p>
 We beginnen met het maken van een nieuwe werkmap met behulp van de<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells bibliotheek</a> en voeg TextBox toe.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: controleer de volgende code om te zien hoe u TextBox kunt toevoegen.
//ExStepSummary:0: De volgende code laat zien hoe u TextBox toevoegt en tekst instelt.
//ExStepImage:0:stap-1.png
//ExStepSummary:1: De volgende code laat zien hoe de kleur van tekst kan worden veranderd.
//ExStepImage:1:step-2.png
//ExStepSummary:2: De volgende code laat zien hoe de rotatiehoek van TextBox kan worden gewijzigd.
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

// Voeg TextBox toe en stel tekst in
TextBox textBox = vormen.AddTextBox(1, 0, 1, 0, 200, 200);
textBox.Text = "Aspose.Cells for .NET is een bibliotheek met programmeerklassen waarmee softwareontwikkelaars spreadsheetbestanden in hun eigen toepassingen kunnen manipuleren en verwerken.";

//ExStap:1-
// Verander de kleur van de tekst
textBox.Font.Color = Kleur.Blauw;

//ExStep:2-
// Wijzig de rotatiehoek van TextBox
textBox.RotationAngle = 90;

//ExStep:0-

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