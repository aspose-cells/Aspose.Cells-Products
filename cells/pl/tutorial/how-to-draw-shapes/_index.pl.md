---
title: Jak dodawać kształty pod numerem Aspose.Cells
weight: 7700
limit:
description: Dowiedz się, jak dodawać kształty.
keywords: [add shapes., how to add shapes in Aspose.Cells., how to add shapes using Aspose.Cells]
url: /pl/tutorial/add-shapes-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Dowiedz się, jak dodawać kształty za pomocą numeru Aspose.Cells" >}}

<p>
W tym samouczku dodamy kształty w pliku programu Excel.
</p>

<p>
 Zaczniemy od utworzenia nowego skoroszytu przy użyciu<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells biblioteka</a> i dodaj kształty.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: Sprawdź poniższy kod, aby dowiedzieć się, jak dodawać kształty.
//ExStepSummary:0: Poniższy kod pokazuje, jak dodać kształt prostokąta.
//ExStepImage:0:step-1.png
//ExStepSummary:1: Poniższy kod pokazuje, jak dodać kształt linii.
//ExStepImage:1:step-2.png
//ExStepSummary:2: Poniższy kod pokazuje, jak dodać owalny kształt.
//ExStepImage:2:step-3.png
//Rozpocznij
//ExStep:0-
za pomocą Aspose.Cells;
za pomocą Aspose.Cells. Rysunek;





skoroszyt skoroszyt = nowy skoroszyt();
Arkusz roboczy = skoroszyt.Worksheets[0];
sheet.PageSetup.PrintGridlines = prawda;
sheet.PageSetup.PrintArea = "A1:F20";

kształty ShapeCollection = arkusz.Kształty;

//Dodaj kształt prostokąta
kształty.AddRectangle(1, 0, 1, 0, 100, 150);

//ExStep:1-
//Dodaj kształt linii
kształty.AddLine(8, 0, 1, 0, 100, 150);

//ExStep:2-
//Dodaj owalny kształt
kształty.AddOval(13, 0, 1, 0, 100, 150);

//ExStep:0-
zeszyt ćwiczeń
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