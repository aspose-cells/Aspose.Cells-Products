---
title: Hoe u TextBox kunt toevoegen via Aspose.Cells
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
//ExSummary: Controleer de volgende code om te zien hoe u TextBox kunt toevoegen.
//ExStepSummary:0: De volgende code laat zien hoe u TextBox kunt toevoegen en tekst kunt instellen.
//ExStepImage:0:stap-1.png
//ExStepSummary:1: De volgende code laat zien hoe u de kleur van tekst kunt wijzigen.
//ExStepImage:1:stap-2.png
//ExStepSummary:2: De volgende code laat zien hoe u de rotatiehoek van TextBox kunt wijzigen.
//ExStepImage:2:stap-3.png
//ExStart
//ExStep:0-
via Aspose.Cells;
via Aspose.Cells.Tekening;

Werkmap werkmap = nieuwe werkmap();
Werkbladblad = werkmap.Werkbladen[0];
sheet.PageSetup.PrintGridlines = waar;
sheet.PageSetup.PrintArea = "A1:F20";

ShapeCollection-vormen = vel.Shapes;

//Voeg TextBox toe en stel tekst in
TextBox tekstBox = vormen.AddTextBox(1, 0, 1, 0, 200, 200);
textBox.Text = "Aspose.Cells for .NET is een programmeerklassebibliotheek waarmee softwareontwikkelaars spreadsheetbestanden binnen hun eigen toepassingen kunnen manipuleren en verwerken.";

//ExStap:1-
//Verander de kleur van de tekst
textBox.Font.Color = Kleur.Blauw;

//ExStap:2-
//Wijzig de rotatiehoek van TextBox
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