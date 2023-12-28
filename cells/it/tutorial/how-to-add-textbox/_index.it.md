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
In questo tutorial aggiungeremo TextBox in un file Excel.
</p>

<p>
 Inizieremo creando una nuova cartella di lavoro utilizzando il file<a href="https://www.nuget.org/packages/Aspose.Cells">Biblioteca Aspose.Cells</a> e aggiungi TextBox.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: controlla il codice seguente per scoprire come aggiungere TextBox.
//ExStepSummary:0: il codice seguente mostra come aggiungere TextBox e impostare il testo.
//ExStepImage:0:step-1.png
//ExStepSummary:1: il codice seguente mostra come modificare il colore del testo.
//ExStepImage:1:step-2.png
//ExStepSummary:2: il codice seguente mostra come modificare l'angolo di rotazione di TextBox.
//ExStepImage:2:step-3.png
//ExStart
//PassoEx:0-
utilizzando Aspose.Cells;
utilizzando Aspose.Cells.Disegno;

Cartella di lavoro cartella di lavoro = nuova cartella di lavoro();
Foglio di lavoro = cartella di lavoro.Fogli di lavoro[0];
sheet.PageSetup.PrintGridlines = true;
foglio.PageSetup.PrintArea = "A1:F20";

ShapeCollection forme = sheet.Shapes;

//Aggiungi TextBox e imposta il testo
Casella di testo casella di testo = forme.AddTextBox(1, 0, 1, 0, 200, 200);
textBox.Text = "Aspose.Cells for .NET è una libreria di classi di programmazione che consente agli sviluppatori di software di manipolare ed elaborare file di fogli di calcolo all'interno delle proprie applicazioni.";

//ExPassaggio:1-
//Cambia il colore del testo
textBox.Font.Color = Colore.Blu;

//ExPassaggio:2-
//Cambia l'angolo di rotazione di TextBox
textBox.RotationAngle = 90;

//PassoEx:0-

//Exend
{{< /app/cells/tutorial >}}
<br />

<br />
<br />
<div class="code-sample">
    <ul class="link-list">
        <li class="link-item"><a href="https://docs.aspose.com/cells/net/installation/">Installazione dello Aspose.Cells</a></li>
        <li class="link-item"><a href="https://products.aspose.app/cells/editor/">Aspose.Cells Redattore</a></li>
    </ul>
</div>

{{< /blocks/products/pf/feature-page-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}