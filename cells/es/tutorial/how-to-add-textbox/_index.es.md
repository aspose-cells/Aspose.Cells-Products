---
title: Cómo agregar TextBox a través de Aspose.Cells
weight: 7700
limit:
description: Aprenda cómo agregar TextBox.
keywords: [Add TextBox., how to add TextBox in Aspose.Cells., how to add TextBox using Aspose.Cells]
url: /es/tutorial/add-textbox-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Aprenda cómo agregar TextBox con Aspose.Cells" >}}

<p>
En este tutorial, agregaremos TextBox en un archivo de Excel.
</p>

<p>
 Comenzaremos creando un nuevo libro de trabajo usando el<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells biblioteca</a> y agregue TextBox.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: verifique el siguiente código para descubrir cómo agregar TextBox.
//ExStepSummary:0: el siguiente código muestra cómo agregar TextBox y configurar texto.
//ExStepImage:0:paso-1.png
//ExStepSummary:1: el siguiente código muestra cómo cambiar el color del texto.
//ExStepImage:1:paso-2.png
//ExStepSummary:2: el siguiente código muestra cómo cambiar el ángulo de rotación de TextBox.
//ExStepImage:2:paso-3.png
//ExInicio
//ExPaso:0-
usando Aspose.Cells;
usando Aspose.Cells.Dibujo;

Libro de trabajo libro = nuevo libro de trabajo();
Hoja de trabajo = libro de trabajo.Hojas de trabajo[0];
hoja.PageSetup.PrintGridlines = verdadero;
hoja.PageSetup.PrintArea = "A1:F20";

ShapeCollection formas = hoja.Formas;

//Agregar TextBox y establecer texto
TextBox cuadro de texto = formas.AddTextBox(1, 0, 1, 0, 200, 200);
textBox.Text = "Aspose.Cells for .NET es una biblioteca de clases de programación que permite a los desarrolladores de software manipular y procesar archivos de hojas de cálculo dentro de sus propias aplicaciones.";

//ExPaso:1-
//Cambiar el color del texto
textBox.Font.Color = Color.Azul;

//ExPaso:2-
//Cambiar el ángulo de rotación de TextBox
cuadro de texto.RotationAngle = 90;

//ExPaso:0-

//ExFin
{{< /app/cells/tutorial >}}
<br />

<br />
<br />
<div class="code-sample">
    <ul class="link-list">
        <li class="link-item"><a href="https://docs.aspose.com/cells/net/installation/">Instalación de Aspose.Cells</a></li>
        <li class="link-item"><a href="https://products.aspose.app/cells/editor/">Aspose.Cells Redactor</a></li>
    </ul>
</div>

{{< /blocks/products/pf/feature-page-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}