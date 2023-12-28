---
title: Jak dodać wykres kolumnowy pod numerem Aspose.Cells
weight: 7700
limit:
description: Dowiedz się, jak dodać wykres kolumnowy.
keywords: [Add column chart., how to add column chart in Aspose.Cells., how to add column chart using Aspose.Cells]
url: /pl/tutorial/add-column-chart-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Dowiedz się, jak dodać wykres kolumnowy za pomocą numeru Aspose.Cells" >}}

<p>
W tym samouczku dodamy wykres kolumnowy w pliku Excel.
</p>

<p>
 Zaczniemy od utworzenia nowego skoroszytu za pomocą metody<a href="https://www.nuget.org/packages/Aspose.Cells">Biblioteka Aspose.Cells</a> i dodaj wykres kolumnowy.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: Sprawdź poniższy kod, aby dowiedzieć się, jak dodać wykres kolumnowy.
//ExStepSummary:0: Poniższy kod pokazuje, jak dodać wykres kolumnowy.
//ExStepImage:0:step-1.png
//ExStepSummary:1: Poniższy kod pokazuje, jak przenieść legendę w lewo i ustawić kolor czcionki legendy.
//ExStepImage:1:step-2.png
//ExStepSummary:2: Poniższy kod pokazuje, jak ustawić tytuł wykresu i zmienić kolor czcionki na niebieski.
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
używając numeru Aspose.Cells;
za pomocą Aspose.Cells. Rysunek;

Skoroszyt skoroszyt = nowy skoroszyt();
Arkusz arkusza = skoroszyt.Arkusze[0];
arkusz.Name = "Arkusz Wykresu";
Cells komórek = arkusz.Cells;
komórki["A1"].Wartość = "Owoc";
komórki["A2"].Wartość = "jabłko";
komórki["A3"].Wartość = "pomarańczowy";
komórki["A4"].Wartość = "borówka";
komórki["A5"].Wartość = "kiwi";

komórki["B1"].Wartość = "Cena";
komórki["B2"].Wartość = 10;
komórki["B3"].Wartość = 5;
komórki["B4"].Wartość = 20;
komórki["B5"].Wartość = 8;

arkusz.PageSetup.PrintGridlines = true;
arkusz.PageSetup.PrintArea = "A1:F20";

Wykresy ChartCollection = arkusz.Wykresy;

//Dodaj wykres kolumnowy
int indeks = wykresy.Add(ChartType.Column, "=ChartSheet!A1:B5", false, 6, 0, 19, 5);
Wykres wykres = wykresy[indeks];

//ExStep:1-
//Przesuń legendę w lewo i ustaw kolor czcionki legendy
wykres.Legend.Font.Color = Kolor.Niebieski;
wykres.Legend.Position = LegendPositionType.Left;

//ExStep:2-
//Ustaw tytuł wykresu i zmień kolor czcionki na niebieski
chart.Title.Text = "Wykres kolumnowy cen owoców";
wykres.Title.Font.Color = Kolor.Niebieski;

//ExStep:0-

//RozwińKoniec
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