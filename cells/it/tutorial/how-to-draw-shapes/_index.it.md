---
title: Come aggiungere forme tramite Aspose.Cells
weight: 7700
limit:
description: Scopri come aggiungere forme.
keywords: [add shapes., how to add shapes in Aspose.Cells., how to add shapes using Aspose.Cells]
url: /it/tutorial/add-shapes-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Scopri come aggiungere forme con Aspose.Cells" >}}

<p>
In questo tutorial, aggiungeremo forme in un file excel.
</p>

<p>
 Inizieremo creando una nuova cartella di lavoro utilizzando il file<a href="https://www.nuget.org/packages/Aspose.Cells">biblioteca Aspose.Cells</a> e aggiungi forme.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: controllare il codice seguente per scoprire come aggiungere forme.
//ExStepSummary:0: il codice seguente mostra come aggiungere una forma rettangolare.
//ExStepImage:0:step-1.png
//ExStepSummary:1: il codice seguente mostra come aggiungere la forma della linea.
//ExStepImage:1:step-2.png
//ExStepSummary:2: il codice seguente mostra come aggiungere una forma ovale.
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

//Aggiungi forma rettangolare
forme.AddRectangle(1, 0, 1, 0, 100, 150);

//ExStep:1-
//Aggiungi la forma della linea
forme.AddLine(8, 0, 1, 0, 100, 150);

//ExStep:2-
//Aggiungi forma ovale
forme.AddOval(13, 0, 1, 0, 100, 150);

//ExPasso:0-
cartella di lavoro
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