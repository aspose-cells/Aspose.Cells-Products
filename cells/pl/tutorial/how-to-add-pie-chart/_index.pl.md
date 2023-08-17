---
title: Jak dodać wykres kołowy pod numerem Aspose.Cells
weight: 7700
limit:
description: Dowiedz się, jak dodać wykres kołowy.
keywords: [Add pie chart., how to add pie chart in Aspose.Cells., how to add pie chart using Aspose.Cells]
url: /pl/tutorial/add-pie-chart-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Dowiedz się, jak dodać wykres kołowy z numerem Aspose.Cells" >}}

<p>
W tym samouczku dodamy wykres kołowy w pliku programu Excel.
</p>

<p>
 Zaczniemy od utworzenia nowego skoroszytu przy użyciu<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells biblioteka</a> i dodaj wykres kołowy.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: Sprawdź poniższy kod, aby dowiedzieć się, jak dodać wykres kołowy.
//ExStepSummary:0: Poniższy kod pokazuje, jak dodać wykres kołowy, ustawić zakres danych serii i ustawić zakres danych kategorii.
//ExStepImage:0:step-1.png
//ExStepSummary:1: Poniższy kod pokazuje, jak wyłączyć legendę.
//ExStepImage:1:step-2.png
//ExStepSummary:2: Poniższy kod pokazuje, jak uzyskać dostęp do etykiet danych, włączyć nazwy kategorii, włączyć format procentowy i ustawić pozycję.
//ExStepImage:2:step-3.png
//Rozpocznij
//ExStep:0-
za pomocą Aspose.Cells;
za pomocą Aspose.Cells. Rysunek;

skoroszyt skoroszyt = nowy skoroszyt();
Arkusz roboczy = skoroszyt.Worksheets[0];
sheet.Name = "Arkusz Wykresu";
Cells komórek = arkusz.Cells;
komórki ["A1"].Wartość = "Owoc";
komórki ["A2"].Wartość = "jabłko";
komórki ["A3"].Wartość = "pomarańczowy";
komórki ["A4"].Wartość = "borówka";
komórki ["A5"].Wartość = "kiwi";

komórki ["B1"].Wartość = "Cena";
komórki ["B2"].Wartość = 10;
komórki ["B3"]. Wartość = 5;
komórki ["B4"]. Wartość = 20;
komórki ["B5"]. Wartość = 8;

sheet.PageSetup.PrintGridlines = prawda;
sheet.PageSetup.PrintArea = "A1:F20";

Wykresy ChartCollection = arkusz.Wykresy;

//Dodaj wykres kołowy, ustaw zakres danych serii i ustaw zakres danych kategorii
int index = sheet.Charts.Add(ChartType.Pie, 6, 0, 19, 5);
Chart chart = arkusz.Wykresy[indeks];
chart.NSeries.Add("B2:B5", prawda);
chart.NSeries.CategoryData = "A2:A5";

//ExStep:1-
//Wyłącz legendę
chart.ShowLegend = fałsz;

//ExStep:2-
// Uzyskaj dostęp do etykiet danych, włącz nazwy kategorii, włącz format procentowy i ustaw pozycję
DataLabels dataLabels = chart.NSeries[0].DataLabels;
dataLabels.ShowCategoryName = prawda;
dataLabels.ShowPercentage = prawda;
dataLabels.Position = LabelPositionType.OutsideEnd;

//ExStep:0-

//ExEnd
{{< /app/cells/tutorial >}}
<br />

<br />
<br />
<div class="code-sample">
    <ul class="link-list">
        <li class="link-item"><a href="https://docs.aspose.com/cells/net/installation/">Instalacja Aspose.Cells</a></li>
        <li class="link-item"><a href="https://products.aspose.app/cells/editor/">Aspose.Cells Redaktor</a></li>
    </ul>
</div>

{{< /blocks/products/pf/feature-page-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}