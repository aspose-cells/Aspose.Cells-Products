---
title: TextBox hozzáadása a Aspose.Cells számon keresztül
weight: 7700
limit:
description: Ismerje meg a TextBox hozzáadását.
keywords: [Add TextBox., how to add TextBox in Aspose.Cells., how to add TextBox using Aspose.Cells]
url: /hu/tutorial/add-textbox-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Ismerje meg, hogyan adhat hozzá TextBoxot a Aspose.Cells számmal" >}}

<p>
Ebben az oktatóanyagban hozzáadjuk a TextBoxot egy Excel-fájlhoz.
</p>

<p>
 Kezdjük egy új munkafüzet létrehozásával a<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells könyvtár</a> és adjunk hozzá TextBoxot.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: Kérjük, ellenőrizze a következő kódot, hogy megtudja, hogyan kell hozzáadni a TextBoxot.
//ExStepSummary:0: A következő kód bemutatja a TextBox hozzáadását és a szöveg beállítását.
//ExStepImage:0:step-1.png
//ExStepSummary:1: A következő kód megmutatja, hogyan módosíthatja a szöveg színét.
//ExStepImage:1:step-2.png
//ExStepSummary:2: A következő kód megmutatja, hogyan módosítható a TextBox elforgatási szöge.
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

//Szövegdoboz hozzáadása és szöveg beállítása
TextBox textBox = alakzatok.AddTextBox(1, 0, 1, 0, 200, 200);
textBox.Text = "Aspose.Cells for .NET egy programozási osztálykönyvtár, amely lehetővé teszi a szoftverfejlesztők számára, hogy kezeljék és feldolgozzák a táblázatfájlokat saját alkalmazásaikon belül.";

//ExStep:1-
//Módosítsa a szöveg színét
textBox.Font.Color = Color.Blue;

//ExStep:2-
//Módosítsa a TextBox elforgatási szögét
textBox.RotationAngle = 90;

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