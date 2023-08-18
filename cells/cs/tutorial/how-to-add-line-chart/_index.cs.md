---
title: Jak přidat spojnicový graf přes Aspose.Cells
weight: 7700
limit:
description: Přečtěte si, jak přidat spojnicový graf.
keywords: [Add line chart., how to add line chart in Aspose.Cells., how to add line chart using Aspose.Cells]
url: /cs/tutorial/add-line-chart-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Přečtěte si, jak přidat spojnicový graf s číslem Aspose.Cells" >}}

<p>
V tomto tutoriálu přidáme spojnicový graf do souboru aplikace Excel.
</p>

<p>
 Začneme vytvořením nového sešitu pomocí<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells knihovna</a> a přidejte spojnicový graf.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: Zkontrolujte prosím následující kód, abyste zjistili, jak přidat spojnicový graf.
//ExStepSummary:0: Následující kód ukazuje, jak přidat spojnicový graf, nastavit rozsah dat řady a nastavit rozsah dat kategorie.
//ExStepImage:0:step-1.png
//ExStepSummary:1: Následující kód ukazuje, jak přesunout legendu dolů a nastavit barvu písma legendy.
//ExStepImage:1:step-2.png
//ExStepSummary:2: Následující kód ukazuje, jak získat přístup k štítkům dat, zapnout názvy kategorií a nastavit pozici.
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
pomocí Aspose.Cells;
pomocí Aspose.Cells.Výkres;

Sešit sešit = nový Sešit();
List listu = sešit.Pracovní listy[0];
list.Name = "ChartSheet";
Cells buňky = list.Cells;
buňky["A1"].Value = "Ovoce";
buňky["A2"].Value = "jablko";
buňky["A3"].Hodnota = "oranžová";
buňky["A4"].Hodnota = "borůvka";
buňky["A5"].Hodnota = "kiwi";

buňky["B1"].Value = "Cena";
buňky["B2"].Hodnota = 10;
buňky["B3"].Hodnota = 5;
buňky["B4"].Hodnota = 20;
buňky["B5"].Hodnota = 8;

sheet.PageSetup.PrintGridlines = true;
sheet.PageSetup.PrintArea = "A1:F20";

ChartCollection grafy = list.Charts;

//Přidat spojnicový graf, nastavit rozsah dat série a nastavit rozsah dat kategorie
int index = list.Charts.Add(ChartType.Line, 6, 0, 19, 5);
Graf graf = list.Charts[index];
chart.NSeries.Add("B2:B5", true);
chart.NSeries.CategoryData = "A2:A5";

//ExStep:1-
//Přesuňte legendu dolů a nastavte barvu písma legendy
chart.Legend.Font.Color = Barva.Modrá;
chart.Legend.Position = LegendPositionType.Bottom;

//ExStep:2-
//Přístup k štítkům dat, zapnutí názvů kategorií a nastavení pozice
DataLabels dataLabels = chart.NSeries[0].DataLabels;
dataLabels.ShowCategoryName = true;
dataLabels.Position = LabelPositionType.Center;

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