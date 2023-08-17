---
title: Alakzatok hozzáadása a Aspose.Cells számon keresztül
weight: 7700
limit:
description: Ismerje meg, hogyan adhat hozzá alakzatokat.
keywords: [add shapes., how to add shapes in Aspose.Cells., how to add shapes using Aspose.Cells]
url: /hu/tutorial/add-shapes-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Ismerje meg, hogyan adhat hozzá alakzatokat a Aspose.Cells számmal" >}}

<p>
Ebben az oktatóanyagban alakzatokat adunk hozzá egy Excel-fájlhoz.
</p>

<p>
 Kezdjük egy új munkafüzet létrehozásával a<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells könyvtár</a> és adjunk hozzá formákat.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: Kérjük, ellenőrizze a következő kódot, hogy megtudja, hogyan adhat hozzá alakzatokat.
//ExStepSummary:0: A következő kód megmutatja, hogyan adhat hozzá téglalap alakzatot.
//ExStepImage:0:step-1.png
//ExStepSummary:1: A következő kód megmutatja, hogyan adhat hozzá vonal alakzatot.
//ExStepImage:1:step-2.png
//ExStepSummary:2: A következő kód megmutatja, hogyan adhat hozzá ovális alakot.
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
a Aspose.Cells számon;
Aspose.Cells használatával.Rajz;





Munkafüzet munkafüzet = new Workbook();
Munkalaplap = workbook.Worksheets[0];
sheet.PageSetup.PrintGridlines = igaz;
sheet.PageSetup.PrintArea = "A1:F20";

ShapeCollection alakzatok = sheet.Shapes;

//Téglalap alakzat hozzáadása
alakzatok.AddRectangle(1, 0, 1, 0, 100, 150);

//ExStep:1-
//Vonal alakzat hozzáadása
alakzatok.AddLine(8, 0, 1, 0, 100, 150);

//ExStep:2-
//Ovális alak hozzáadása
alakzatok.AddOval(13, 0, 1, 0, 100, 150);

//ExStep:0-
munkafüzet
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