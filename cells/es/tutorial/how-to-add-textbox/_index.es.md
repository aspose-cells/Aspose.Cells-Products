---
title: Cómo agregar TextBox a través de Aspose.Cells
weight: 7700
limit:
description: Aprende a agregar TextBox.
keywords: [Add TextBox., how to add TextBox in Aspose.Cells., how to add TextBox using Aspose.Cells]
url: /es/tutorial/add-textbox-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Aprenda a agregar TextBox con Aspose.Cells" >}}

<p>
En este tutorial, agregaremos TextBox en un archivo de Excel.
</p>

<p>
 Comenzaremos creando un nuevo libro de trabajo usando el<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells biblioteca</a> y agregue TextBox.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: consulte el siguiente código para saber cómo agregar TextBox.
//ExStepSummary:0: El siguiente código muestra cómo agregar TextBox y establecer texto.
//ExStepImage:0:paso-1.png
//ExStepSummary:1: El siguiente código muestra cómo cambiar el color del texto.
//ExStepImage:1:paso-2.png
//ExStepSummary:2: El siguiente código muestra cómo cambiar el ángulo de rotación de TextBox.
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

//Agregar cuadro de texto y establecer texto
TextBox textBox = formas.AddTextBox(1, 0, 1, 0, 200, 200);
textBox.Text = "Aspose.Cells for .NET es una biblioteca de clases de programación que permite a los desarrolladores de software manipular y procesar archivos de hojas de cálculo dentro de sus propias aplicaciones.";

//ExStep:1-
//Cambiar el color del texto
cuadro de texto.Fuente.Color = Color.Azul;

//ExStep:2-
//Cambiar el ángulo de rotación de TextBox
cuadro de texto.Ángulo de rotación = 90;

//ExStep:0-

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