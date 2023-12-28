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
In questo tutorial, aggiungeremo forme in un file Excel.
</p>

<p>
 Inizieremo creando una nuova cartella di lavoro utilizzando il file<a href="https://www.nuget.org/packages/Aspose.Cells">Biblioteca Aspose.Cells</a> e aggiungere forme.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: controlla il codice seguente per scoprire come aggiungere forme.
//ExStepSummary:0: il codice seguente mostra come aggiungere la forma rettangolare.
//ExStepImage:0:step-1.png
//ExStepSummary:1: il codice seguente mostra come aggiungere la forma della linea.
//ExStepImage:1:step-2.png
//ExStepSummary:2: il codice seguente mostra come aggiungere una forma ovale.
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

//Aggiunge la forma rettangolare
forme.AddRectangle(1, 0, 1, 0, 100, 150);

//ExPassaggio:1-
//Aggiunge la forma della linea
forme.AddLine(8, 0, 1, 0, 100, 150);

//ExPassaggio:2-
//Aggiungi forma ovale
forme.AddOvale(13, 0, 1, 0, 100, 150);

//PassoEx:0-
cartella di lavoro
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