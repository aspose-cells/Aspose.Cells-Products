---
title: Jak přidat tvary přes Aspose.Cells
weight: 7700
limit:
description: Naučte se přidávat tvary.
keywords: [add shapes., how to add shapes in Aspose.Cells., how to add shapes using Aspose.Cells]
url: /cs/tutorial/add-shapes-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Naučte se přidávat tvary pomocí Aspose.Cells" >}}

<p>
V tomto tutoriálu přidáme tvary do souboru aplikace Excel.
</p>

<p>
 Začneme vytvořením nového sešitu pomocí<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells knihovna</a> a přidat tvary.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: Zkontrolujte prosím následující kód, abyste zjistili, jak přidat tvary.
//ExStepSummary:0: Následující kód ukazuje, jak přidat tvar obdélníku.
//ExStepImage:0:step-1.png
//ExStepSummary:1: Následující kód ukazuje, jak přidat tvar čáry.
//ExStepImage:1:step-2.png
//ExStepSummary:2: Následující kód ukazuje, jak přidat oválný tvar.
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

//Přidat tvar obdélníku
tvary.AddRectangle(1, 0, 1, 0, 100, 150);

//ExStep:1-
//Přidat tvar čáry
tvary.AddLine(8, 0, 1, 0, 100, 150);

//ExStep:2-
//Přidat oválný tvar
tvary.AddOval(13, 0, 1, 0, 100, 150);

//ExStep:0-
pracovní sešit
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