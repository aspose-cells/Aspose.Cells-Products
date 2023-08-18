---
title: Hur man lägger till TextBox via Aspose.Cells
weight: 7700
limit:
description: Lär dig hur du lägger till TextBox.
keywords: [Add TextBox., how to add TextBox in Aspose.Cells., how to add TextBox using Aspose.Cells]
url: /sv/tutorial/add-textbox-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Lär dig hur du lägger till TextBox med Aspose.Cells" >}}

<p>
I den här handledningen lägger vi till TextBox i en excel-fil.
</p>

<p>
 Vi börjar med att skapa en ny arbetsbok med hjälp av<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells bibliotek</a> och lägg till TextBox.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: Kontrollera följande kod för att ta reda på hur du lägger till TextBox.
//ExStepSummary:0: Följande kod visar hur man lägger till TextBox och ställer in text.
//ExStepImage:0:step-1.png
//ExStepSummary:1: Följande kod visar hur man ändrar färgen på text.
//ExStepImage:1:step-2.png
//ExStepSummary:2: Följande kod visar hur man ändrar rotationsvinkeln för TextBox.
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
använder Aspose.Cells;
med Aspose.Cells. Ritning;

Arbetsbok arbetsbok = ny arbetsbok();
Arbetsblad = arbetsbok. Arbetsblad[0];
sheet.PageSetup.PrintGridlines = sant;
sheet.PageSetup.PrintArea = "A1:F20";

ShapeCollection former = ark.Shapes;

//Lägg till TextBox och ställ in text
TextBox textBox = shapes.AddTextBox(1, 0, 1, 0, 200, 200);
textBox.Text = "Aspose.Cells for .NET är ett programmeringsklassbibliotek som tillåter programutvecklare att manipulera och bearbeta kalkylarksfiler i sina egna applikationer.";

//ExStep:1-
//Ändra färg på text
textBox.Font.Color = Color.Blue;

//ExStep:2-
//Ändra rotationsvinkeln för TextBox
textBox.RotationAngle = 90;

//ExStep:0-

//ExEnd
{{< /app/cells/tutorial >}}
<br />

<br />
<br />
<div class="code-sample">
    <ul class="link-list">
        <li class="link-item"><a href="https://docs.aspose.com/cells/net/installation/">Installation av Aspose.Cells</a></li>
        <li class="link-item"><a href="https://products.aspose.app/cells/editor/">Aspose.Cells Redaktör</a></li>
    </ul>
</div>

{{< /blocks/products/pf/feature-page-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}