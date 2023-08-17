---
title: Oszlopdiagram hozzáadása a Aspose.Cells számon keresztül
weight: 7700
limit:
description: Ismerje meg, hogyan adhat hozzá oszlopdiagramot.
keywords: [Add column chart., how to add column chart in Aspose.Cells., how to add column chart using Aspose.Cells]
url: /hu/tutorial/add-column-chart-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Ismerje meg, hogyan adhat hozzá oszlopdiagramot a Aspose.Cells számmal" >}}

<p>
Ebben az oktatóanyagban oszlopdiagramot adunk hozzá egy Excel-fájlhoz.
</p>

<p>
 Kezdjük egy új munkafüzet létrehozásával a<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells könyvtár</a> és adjunk hozzá oszlopdiagramot.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: Kérjük, ellenőrizze a következő kódot, hogy megtudja, hogyan adhat hozzá oszlopdiagramot.
//ExStepSummary:0: A következő kód az oszlopdiagram hozzáadását mutatja be.
//ExStepImage:0:step-1.png
//ExStepSummary:1: A következő kód megmutatja, hogyan mozgassa a jelmagyarázatot balra, és hogyan állítsa be a jelmagyarázat betűszínét.
//ExStepImage:1:step-2.png
//ExStepSummary:2: A következő kód megmutatja, hogyan állíthatja be a diagram címét, és hogyan módosíthatja a betűtípus színét kékre.
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

//Oszlopdiagram hozzáadása
int index = diagramok.Add(ChartType.Column, "=ChartSheet!A1:B5", false, 6, 0, 19, 5);
Chart chart = diagramok[index];

//ExStep:1-
//Vigye balra a jelmagyarázatot, és állítsa be a jelmagyarázat betűszínét
chart.Legend.Font.Color = Color.Blue;
chart.Legend.Position = LegendPositionType.Left;

//ExStep:2-
//Állítsa be a diagram címét, és módosítsa a betűszínt kékre
chart.Title.Text = "Gyümölcsárak oszlopdiagramja";
chart.Title.Font.Color = Color.Blue;

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