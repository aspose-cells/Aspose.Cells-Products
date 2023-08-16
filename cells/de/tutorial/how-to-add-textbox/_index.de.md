---
title: So fügen Sie TextBox über Aspose.Cells hinzu
weight: 7700
limit:
description: Erfahren Sie, wie Sie TextBox hinzufügen.
keywords: [Add TextBox., how to add TextBox in Aspose.Cells., how to add TextBox using Aspose.Cells]
url: /de/tutorial/add-textbox-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Erfahren Sie, wie Sie TextBox mit Aspose.Cells hinzufügen" >}}

<p>
In diesem Tutorial fügen wir TextBox in eine Excel-Datei ein.
</p>

<p>
 Wir beginnen mit der Erstellung einer neuen Arbeitsmappe mithilfe von<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells Bibliothek</a> und TextBox hinzufügen.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: Bitte überprüfen Sie den folgenden Code, um herauszufinden, wie TextBox hinzugefügt wird.
//ExStepSummary:0: Der folgende Code zeigt, wie TextBox hinzugefügt und Text festgelegt wird.
//ExStepImage:0:step-1.png
//ExStepSummary:1: Der folgende Code zeigt, wie man die Farbe von Text ändert.
//ExStepImage:1:step-2.png
//ExStepSummary:2: Der folgende Code zeigt, wie der Drehwinkel von TextBox geändert wird.
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

//TextBox hinzufügen und Text festlegen
TextBox textBox = Shapes.AddTextBox(1, 0, 1, 0, 200, 200);
textBox.Text = "Aspose.Cells for .NET ist eine Programmierklassenbibliothek, die es Softwareentwicklern ermöglicht, Tabellenkalkulationsdateien in ihren eigenen Anwendungen zu manipulieren und zu verarbeiten.";

//ExStep:1-
//Ändern Sie die Textfarbe
textBox.Font.Color = Color.Blue;

//ExStep:2-
//Ändern Sie den Drehwinkel von TextBox
textBox.RotationAngle = 90;

//ExStep:0-

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