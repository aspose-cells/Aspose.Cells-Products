---
title: Come aggiungere TextBox tramite Aspose.Cells
weight: 7700
limit:
description: Scopri come aggiungere TextBox.
keywords: [Add TextBox., how to add TextBox in Aspose.Cells., how to add TextBox using Aspose.Cells]
url: /it/tutorial/add-textbox-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Scopri come aggiungere TextBox con Aspose.Cells" >}}

<p>
In questo tutorial, aggiungeremo TextBox in un file excel.
</p>

<p>
 Inizieremo creando una nuova cartella di lavoro utilizzando il file<a href="https://www.nuget.org/packages/Aspose.Cells">biblioteca Aspose.Cells</a> e aggiungi TextBox.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: controllare il codice seguente per scoprire come aggiungere TextBox.
//ExStepSummary:0: il codice seguente mostra come aggiungere TextBox e impostare il testo.
//ExStepImage:0:step-1.png
//ExStepSummary:1: il codice seguente mostra come modificare il colore del testo.
//ExStepImage:1:step-2.png
//ExStepSummary:2: il codice seguente mostra come modificare l'angolo di rotazione di TextBox.
//ExStepImage:2:step-3.png
//ExStart
//ExPasso:0-
utilizzando il numero Aspose.Cells;
utilizzando Aspose.Cells.Drawing;

Cartella di lavoro cartella di lavoro = nuova cartella di lavoro();
Foglio di lavoro = workbook.Worksheets[0];
sheet.PageSetup.PrintGridlines = true;
sheet.PageSetup.PrintArea = "A1:F20";

ShapeCollection forme = foglio.Forme;

//Aggiungi TextBox e imposta il testo
Casella di testo casella di testo = forme.AddTextBox(1, 0, 1, 0, 200, 200);
textBox.Text = "Aspose.Cells for .NET è una libreria di classi di programmazione che consente agli sviluppatori di software di manipolare ed elaborare file di fogli di calcolo all'interno delle proprie applicazioni.";

//ExStep:1-
//Cambia il colore del testo
textBox.Font.Color = Color.Blue;

//ExStep:2-
//Cambia l'angolo di rotazione di TextBox
textBox.RotationAngle = 90;

//ExPasso:0-

//ExFine
{{< /app/cells/tutorial >}}
<br />

<br />
<br />
<div class="code-sample">
    <ul class="link-list">
        <li class="link-item"><a href="https://docs.aspose.com/cells/net/installation/">Installazione di Aspose.Cells</a></li>
        <li class="link-item"><a href="https://products.aspose.app/cells/editor/">Aspose.Cells Editore</a></li>
    </ul>
</div>

{{< /blocks/products/pf/feature-page-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}