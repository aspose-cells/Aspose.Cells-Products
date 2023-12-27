---
title: Cómo agregar un gráfico de columnas a través de Aspose.Cells
weight: 7700
limit:
description: Aprenda a agregar un gráfico de columnas.
keywords: [Add column chart., how to add column chart in Aspose.Cells., how to add column chart using Aspose.Cells]
url: /es/tutorial/add-column-chart-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Aprenda a agregar un gráfico de columnas con Aspose.Cells" >}}

<p>
En este tutorial, agregaremos un gráfico de columnas en un archivo de Excel.
</p>

<p>
 Comenzaremos creando un nuevo libro de trabajo usando el<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells biblioteca</a> y agregue un gráfico de columnas.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: verifique el siguiente código para descubrir cómo agregar un gráfico de columnas.
//ExStepSummary:0: el siguiente código muestra cómo agregar un gráfico de columnas.
//ExStepImage:0:paso-1.png
//ExStepSummary:1: el siguiente código muestra cómo mover la leyenda hacia la izquierda y establecer el color de fuente de la leyenda.
//ExStepImage:1:paso-2.png
//ExStepSummary:2: el siguiente código muestra cómo configurar el título de un gráfico y cambiar el color de fuente a azul.
//ExStepImage:2:paso-3.png
//ExInicio
//ExPaso:0-
usando Aspose.Cells;
usando Aspose.Cells.Dibujo;

Libro de trabajo libro = nuevo libro de trabajo();
Hoja de trabajo = libro de trabajo.Hojas de trabajo[0];
hoja.Nombre = "Hoja de gráfico";
Cells celdas = hoja.Cells;
celdas["A1"].Valor = "Fruta";
celdas["A2"].Valor = "manzana";
celdas["A3"].Valor = "naranja";
celdas["A4"].Valor = "arándano";
celdas["A5"].Valor = "kiwi";

celdas["B1"].Valor = "Precio";
celdas["B2"].Valor = 10;
celdas["B3"].Valor = 5;
celdas["B4"].Valor = 20;
celdas["B5"].Valor = 8;

hoja.PageSetup.PrintGridlines = verdadero;
hoja.PageSetup.PrintArea = "A1:F20";

Gráficos de ChartCollection = hoja.Gráficos;

//Añadir gráfico de columnas
int index = charts.Add(ChartType.Column, "=ChartSheet!A1:B5", false, 6, 0, 19, 5);
Gráfico gráfico = gráficos[índice];

//ExPaso:1-
//Mueve la leyenda hacia la izquierda y establece el color de fuente de la leyenda
chart.Legend.Font.Color = Color.Azul;
chart.Legend.Position = LegendPositionType.Left;

//ExPaso:2-
//Establece el título de un gráfico y cambia el color de fuente a azul
chart.Title.Text = "Gráfico de columnas de precios de frutas";
chart.Title.Font.Color = Color.Azul;

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