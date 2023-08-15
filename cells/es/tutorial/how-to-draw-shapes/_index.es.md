---
title: Cómo agregar formas a través de Aspose.Cells
weight: 7700
limit:
description: Aprende a agregar formas.
keywords: [add shapes., how to add shapes in Aspose.Cells., how to add shapes using Aspose.Cells]
url: /es/tutorial/add-shapes-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Aprende a agregar formas con Aspose.Cells" >}}

<p>
En este tutorial, agregaremos formas en un archivo de Excel.
</p>

<p>
 Comenzaremos creando un nuevo libro de trabajo usando el<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells biblioteca</a> y agregar formas.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: consulte el siguiente código para saber cómo agregar formas.
//ExStepSummary:0: el siguiente código muestra cómo agregar una forma de rectángulo.
//ExStepImage:0:paso-1.png
//ExStepSummary:1: el siguiente código muestra cómo agregar una forma de línea.
//ExStepImage:1:paso-2.png
//ExStepSummary:2: El siguiente código muestra cómo agregar una forma ovalada.
//ExStepImage:2:paso-3.png
//ExStart
//ExStep:0-
usando Aspose.Cells;
usando Aspose.Cells.Dibujo;





Libro de trabajo libro de trabajo = nuevo libro de trabajo ();
Hoja de trabajo hoja = libro de trabajo.Hojas de trabajo[0];
hoja.PageSetup.PrintGridlines = verdadero;
hoja.PageSetup.PrintArea = "A1:F20";

ShapeCollection formas = hoja.Formas;

//Añadir forma de rectángulo
formas.AddRectangle(1, 0, 1, 0, 100, 150);

//ExStep:1-
//Añadir forma de línea
formas.AddLine(8, 0, 1, 0, 100, 150);

//ExStep:2-
//Añadir forma ovalada
formas.AddOval(13, 0, 1, 0, 100, 150);

//ExStep:0-
libro de trabajo
//ExFin
{{< /app/cells/tutorial >}}
<br />

<br />
<br />
<div class="code-sample">
    <ul class="link-list">
        <li class="link-item"><a href="https://docs.aspose.com/cells/net/installation/">Instalación de Aspose.Cells</a></li>
        <li class="link-item"><a href="https://products.aspose.app/cells/editor/">Aspose.Cells Editor</a></li>
    </ul>
</div>

{{< /blocks/products/pf/feature-page-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}