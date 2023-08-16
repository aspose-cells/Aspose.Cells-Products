---
title: So fügen Sie Formen über Aspose.Cells hinzu
weight: 7700
limit:
description: Erfahren Sie, wie Sie Formen hinzufügen.
keywords: [add shapes., how to add shapes in Aspose.Cells., how to add shapes using Aspose.Cells]
url: /de/tutorial/add-shapes-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Erfahren Sie, wie Sie mit Aspose.Cells Formen hinzufügen" >}}

<p>
In diesem Tutorial fügen wir Formen in einer Excel-Datei hinzu.
</p>

<p>
 Wir beginnen mit der Erstellung einer neuen Arbeitsmappe mithilfe von<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells Bibliothek</a> und Formen hinzufügen.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: Bitte überprüfen Sie den folgenden Code, um herauszufinden, wie Formen hinzugefügt werden.
//ExStepSummary:0: Der folgende Code zeigt, wie man eine Rechteckform hinzufügt.
//ExStepImage:0:step-1.png
//ExStepSummary:1: Der folgende Code zeigt, wie eine Linienform hinzugefügt wird.
//ExStepImage:1:step-2.png
//ExStepSummary:2: Der folgende Code zeigt, wie man eine ovale Form hinzufügt.
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
unter Aspose.Cells;
mit Aspose.Cells.Zeichnung;





Arbeitsmappe Arbeitsmappe = new Workbook();
Arbeitsblatt sheet = workbook.Worksheets[0];
sheet.PageSetup.PrintGridlines = true;
sheet.PageSetup.PrintArea = "A1:F20";

ShapeCollection Shapes = sheet.Shapes;

//Rechteckform hinzufügen
Formen.AddRectangle(1, 0, 1, 0, 100, 150);

//ExStep:1-
//Linienform hinzufügen
Formen.AddLine(8, 0, 1, 0, 100, 150);

//ExStep:2-
//Ovale Form hinzufügen
Formen.AddOval(13, 0, 1, 0, 100, 150);

//ExStep:0-
Arbeitsmappe
//ExEnd
{{< /app/cells/tutorial >}}
<br />

<br />
<br />
<div class="code-sample">
    <ul class="link-list">
        <li class="link-item"><a href="https://docs.aspose.com/cells/net/installation/">Installation von Aspose.Cells</a></li>
        <li class="link-item"><a href="https://products.aspose.app/cells/editor/">Aspose.Cells Herausgeber</a></li>
    </ul>
</div>

{{< /blocks/products/pf/feature-page-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}