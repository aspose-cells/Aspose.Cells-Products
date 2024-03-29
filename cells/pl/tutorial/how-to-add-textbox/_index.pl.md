---
title: Jak dodać TextBox pod numerem Aspose.Cells
weight: 7700
limit:
description: Dowiedz się, jak dodać TextBox.
keywords: [Add TextBox., how to add TextBox in Aspose.Cells., how to add TextBox using Aspose.Cells]
url: /pl/tutorial/add-textbox-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Dowiedz się, jak dodać TextBox za pomocą numeru Aspose.Cells" >}}

<p>
W tym samouczku dodamy TextBox do pliku Excela.
</p>

<p>
 Zaczniemy od utworzenia nowego skoroszytu za pomocą metody<a href="https://www.nuget.org/packages/Aspose.Cells">Biblioteka Aspose.Cells</a> i dodaj TextBox.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: Sprawdź poniższy kod, aby dowiedzieć się, jak dodać TextBox.
//ExStepSummary:0: Poniższy kod pokazuje, jak dodać TextBox i ustawić tekst.
//ExStepImage:0:step-1.png
//ExStepSummary:1: Poniższy kod pokazuje, jak zmienić kolor tekstu.
//ExStepImage:1:step-2.png
//ExStepSummary:2: Poniższy kod pokazuje, jak zmienić kąt obrotu TextBox.
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
używając numeru Aspose.Cells;
za pomocą Aspose.Cells. Rysunek;

Skoroszyt skoroszyt = nowy skoroszyt();
Arkusz arkusza = skoroszyt.Arkusze[0];
arkusz.PageSetup.PrintGridlines = true;
arkusz.PageSetup.PrintArea = "A1:F20";

Kształty ShapeCollection = arkusz.Kształty;

//Dodaj pole tekstowe i ustaw tekst
TextBox tekstBox = kształty.AddTextBox(1, 0, 1, 0, 200, 200);
textBox.Text = "Aspose.Cells for .NET to biblioteka klas programistycznych, która umożliwia programistom manipulowanie i przetwarzanie plików arkuszy kalkulacyjnych w ich własnych aplikacjach.";

//ExStep:1-
//Zmień kolor tekstu
textBox.Font.Color = Kolor.Niebieski;

//ExStep:2-
//Zmień kąt obrotu TextBox
tekstBox.RotationAngle = 90;

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