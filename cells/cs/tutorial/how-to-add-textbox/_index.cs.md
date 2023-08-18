---
title: Jak přidat TextBox přes Aspose.Cells
weight: 7700
limit:
description: Přečtěte si, jak přidat textové pole.
keywords: [Add TextBox., how to add TextBox in Aspose.Cells., how to add TextBox using Aspose.Cells]
url: /cs/tutorial/add-textbox-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Přečtěte si, jak přidat TextBox s Aspose.Cells" >}}

<p>
V tomto tutoriálu přidáme TextBox do souboru aplikace Excel.
</p>

<p>
 Začneme vytvořením nového sešitu pomocí<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells knihovna</a> a přidat TextBox.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: Zkontrolujte prosím následující kód, abyste zjistili, jak přidat TextBox.
//ExStepSummary:0: Následující kód ukazuje, jak přidat TextBox a nastavit text.
//ExStepImage:0:step-1.png
//ExStepSummary:1: Následující kód ukazuje, jak změnit barvu textu.
//ExStepImage:1:step-2.png
//ExStepSummary:2: Následující kód ukazuje, jak změnit úhel otočení TextBoxu.
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
pomocí Aspose.Cells;
pomocí Aspose.Cells.Výkres;

Sešit sešit = nový Sešit();
List listu = sešit.Pracovní listy[0];
sheet.PageSetup.PrintGridlines = true;
sheet.PageSetup.PrintArea = "A1:F20";

ShapeCollection tvary = list.Shapes;

//Přidat textové pole a nastavit text
TextBox textBox = shape.AddTextBox(1, 0, 1, 0, 200, 200);
textBox.Text = "Aspose.Cells for .NET je knihovna programovacích tříd, která umožňuje vývojářům softwaru manipulovat a zpracovávat tabulkové soubory v rámci jejich vlastních aplikací.";

//ExStep:1-
//Změna barvy textu
textBox.Font.Color = Color.Blue;

//ExStep:2-
//Změna úhlu otočení TextBoxu
textBox.RotationAngle = 90;

//ExStep:0-

//Konec
{{< /app/cells/tutorial >}}
<br />

<br />
<br />
<div class="code-sample">
    <ul class="link-list">
        <li class="link-item"><a href="https://docs.aspose.com/cells/net/installation/">Instalace Aspose.Cells</a></li>
        <li class="link-item"><a href="https://products.aspose.app/cells/editor/">Aspose.Cells Redaktor</a></li>
    </ul>
</div>

{{< /blocks/products/pf/feature-page-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}