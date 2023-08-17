---
title: Kördiagram hozzáadása a Aspose.Cells számon keresztül
weight: 7700
limit:
description: Ismerje meg, hogyan adhat hozzá kördiagramot.
keywords: [Add pie chart., how to add pie chart in Aspose.Cells., how to add pie chart using Aspose.Cells]
url: /hu/tutorial/add-pie-chart-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Ismerje meg, hogyan adhat hozzá kördiagramot a Aspose.Cells számmal" >}}

<p>
Ebben az oktatóanyagban kördiagramot adunk hozzá egy Excel-fájlhoz.
</p>

<p>
 Kezdjük egy új munkafüzet létrehozásával a<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells könyvtár</a> és adjunk hozzá kördiagramot.
</p>

<br />
{{< app/cells/tutorial >}}
//Összefoglaló: Kérjük, ellenőrizze a következő kódot, hogy megtudja, hogyan adhat hozzá kördiagramot.
//ExStepSummary:0: A következő kód megmutatja, hogyan vehet fel kördiagramot, hogyan állíthat be sorozatadat-tartományt és kategóriaadat-tartományt.
//ExStepImage:0:step-1.png
//ExStepSummary:1: A következő kód a jelmagyarázat kikapcsolásának módját mutatja be.
//ExStepImage:1:step-2.png
//ExStepSummary:2: A következő kód megmutatja, hogyan lehet elérni az adatcímkéket, bekapcsolni a kategórianeveket, bekapcsolni a százalékos formátumot és beállítani a pozíciót.
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

//Kördiagram hozzáadása, sorozatadat-tartomány beállítása és kategóriaadat-tartomány beállítása
int index = lap.Charts.Add(ChartType.Pie, 6, 0, 19, 5);
Chart chart = lap.Charts[index];
chart.NSeries.Add("B2:B5", igaz);
chart.NSeries.CategoryData = "A2:A5";

//ExStep:1-
//A jelmagyarázat kikapcsolása
chart.ShowLegend = false;

//ExStep:2-
//Adatcímkék elérése, kategórianevek bekapcsolása, százalékos formátum bekapcsolása és pozíció beállítása
DataLabels dataLabels = chart.NSeries[0].DataLabels;
dataLabels.ShowCategoryName = igaz;
dataLabels.ShowPercentage = igaz;
dataLabels.Position = LabelPositionType.OutsideEnd;

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