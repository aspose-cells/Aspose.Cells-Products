---
title: Jak dodać wykres liniowy pod numerem Aspose.Cells
weight: 7700
limit:
description: Dowiedz się, jak dodać wykres liniowy.
keywords: [Add line chart., how to add line chart in Aspose.Cells., how to add line chart using Aspose.Cells]
url: /pl/tutorial/add-line-chart-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Dowiedz się, jak dodać wykres liniowy z numerem Aspose.Cells" >}}

<p>
W tym samouczku dodamy wykres liniowy w pliku programu Excel.
</p>

<p>
 Zaczniemy od utworzenia nowego skoroszytu przy użyciu<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells biblioteka</a> i dodaj wykres liniowy.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: Sprawdź poniższy kod, aby dowiedzieć się, jak dodać wykres liniowy.
//ExStepSummary:0: Poniższy kod pokazuje, jak dodać wykres liniowy, ustawić zakres danych serii i ustawić zakres danych kategorii.
//ExStepImage:0:step-1.png
//ExStepSummary:1: Poniższy kod pokazuje, jak przenieść legendę na dół i ustawić kolor czcionki legendy.
//ExStepImage:1:step-2.png
//ExStepSummary:2: Poniższy kod pokazuje, jak uzyskać dostęp do etykiet danych, włączyć nazwy kategorii i ustawić pozycję.
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

//Dodaj wykres liniowy, ustaw zakres danych serii i ustaw zakres danych kategorii
int index = sheet.Charts.Add(ChartType.Line, 6, 0, 19, 5);
Chart chart = arkusz.Wykresy[indeks];
chart.NSeries.Add("B2:B5", prawda);
chart.NSeries.CategoryData = "A2:A5";

//ExStep:1-
//Przenieś legendę na dół i ustaw kolor czcionki legendy
chart.Legend.Font.Color = Kolor.Niebieski;
chart.Legend.Position = LegendPositionType.Bottom;

//ExStep:2-
//Uzyskaj dostęp do etykiet danych, włącz nazwy kategorii i ustaw pozycję
DataLabels dataLabels = chart.NSeries[0].DataLabels;
dataLabels.ShowCategoryName = prawda;
dataLabels.Position = LabelPositionType.Center;

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