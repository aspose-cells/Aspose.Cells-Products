---
title: Vonaldiagram hozzáadása a Aspose.Cells számon keresztül
weight: 7700
limit:
description: Ismerje meg, hogyan adhat hozzá vonaldiagramot.
keywords: [Add line chart., how to add line chart in Aspose.Cells., how to add line chart using Aspose.Cells]
url: /hu/tutorial/add-line-chart-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Ismerje meg, hogyan adhat hozzá vonaldiagramot a Aspose.Cells számmal" >}}

<p>
Ebben az oktatóanyagban vonaldiagramot adunk hozzá egy Excel-fájlhoz.
</p>

<p>
 Kezdjük egy új munkafüzet létrehozásával a<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells könyvtár</a> és adjunk hozzá vonaldiagramot.
</p>

<br />
{{< app/cells/tutorial >}}
//Összefoglaló: Kérjük, ellenőrizze a következő kódot, hogy megtudja, hogyan adhat hozzá vonaldiagramot.
//ExStepSummary:0: A következő kód megmutatja, hogyan vehet fel vonaldiagramot, hogyan állíthat be sorozatadat-tartományt és kategóriaadat-tartományt.
//ExStepImage:0:step-1.png
//ExStepSummary:1: A következő kód megmutatja, hogyan helyezheti át a jelmagyarázatot alul, és hogyan állíthatja be a jelmagyarázat betűszínét.
//ExStepImage:1:step-2.png
//ExStepSummary:2: A következő kód megmutatja, hogyan lehet elérni az adatcímkéket, bekapcsolni a kategórianeveket és beállítani a pozíciót.
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
a Aspose.Cells számon;
Aspose.Cells használatával.Rajz;

Munkafüzet munkafüzet = new Workbook();
Munkalaplap = workbook.Worksheets[0];
sheet.Name = "ChartSheet";
Cells cellák = lap.Cells;
cellák["A1"].Érték = "Gyümölcs";
cellák["A2"].Érték = "alma";
cellák["A3"].Érték = "narancs";
cellák["A4"].Érték = "áfonya";
cellák["A5"].Érték = "kiwi";

cellák["B1"].Érték = "Ár";
cellák["B2"].Érték = 10;
cellák["B3"].Érték = 5;
cellák["B4"].Érték = 20;
cellák["B5"].Érték = 8;

sheet.PageSetup.PrintGridlines = igaz;
sheet.PageSetup.PrintArea = "A1:F20";

ChartCollection charts = sheet.Charts;

//Vonaldiagram hozzáadása, sorozatadat-tartomány beállítása és kategóriaadat-tartomány beállítása
int index = lap.Charts.Add(ChartType.Line, 6, 0, 19, 5);
Chart chart = lap.Charts[index];
chart.NSeries.Add("B2:B5", igaz);
chart.NSeries.CategoryData = "A2:A5";

//ExStep:1-
//Vigye le a jelmagyarázatot, és állítsa be a jelmagyarázat betűszínét
chart.Legend.Font.Color = Color.Blue;
chart.Legend.Position = LegendPositionType.Bottom;

//ExStep:2-
//Adatcímkék elérése, kategórianevek bekapcsolása és pozíció beállítása
DataLabels dataLabels = chart.NSeries[0].DataLabels;
dataLabels.ShowCategoryName = igaz;
dataLabels.Position = LabelPositionType.Center;

//ExStep:0-

//ExEnd
{{< /app/cells/tutorial >}}
<br />

<br />
<br />
<div class="code-sample">
    <ul class="link-list">
        <li class="link-item"><a href="https://docs.aspose.com/cells/net/installation/">Aspose.Cells telepítése</a></li>
        <li class="link-item"><a href="https://products.aspose.app/cells/editor/">Aspose.Cells Szerkesztő</a></li>
    </ul>
</div>

{{< /blocks/products/pf/feature-page-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}