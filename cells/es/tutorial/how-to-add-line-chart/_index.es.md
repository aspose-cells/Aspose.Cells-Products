---
title: Cómo agregar un gráfico de líneas a través de Aspose.Cells
weight: 7700
limit:
description: Aprenda a agregar un gráfico de líneas.
keywords: [Add line chart., how to add line chart in Aspose.Cells., how to add line chart using Aspose.Cells]
url: /es/tutorial/add-line-chart-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Aprenda a agregar un gráfico de líneas con Aspose.Cells" >}}

<p>
En este tutorial, agregaremos un gráfico de líneas en un archivo de Excel.
</p>

<p>
 Comenzaremos creando un nuevo libro de trabajo usando el<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells biblioteca</a> y agregue un gráfico de líneas.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: consulte el siguiente código para averiguar cómo agregar un gráfico de líneas.
//ExStepSummary:0: el siguiente código muestra cómo agregar un gráfico de líneas, establecer un rango de datos de serie y establecer un rango de datos de categoría.
//ExStepImage:0:paso-1.png
//ExStepSummary:1: el siguiente código muestra cómo mover la leyenda hacia abajo y establecer el color de fuente de la leyenda.
//ExStepImage:1:paso-2.png
//ExStepSummary:2: el siguiente código muestra cómo acceder a las etiquetas de datos, activar los nombres de categoría y establecer la posición.
//ExStepImage:2:paso-3.png
//ExStart
//ExStep:0-
usando Aspose.Cells;
usando Aspose.Cells.Dibujo;

Libro de trabajo libro de trabajo = nuevo libro de trabajo ();
Hoja de trabajo hoja = libro de trabajo.Hojas de trabajo[0];
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

ChartCollection gráficos = hoja.Gráficos;

// Agregar gráfico de líneas, establecer rango de datos de serie y establecer rango de datos de categoría
índice int = hoja.Charts.Add(ChartType.Line, 6, 0, 19, 5);
Gráfico gráfico = hoja.Gráficos[índice];
gráfico.NSeries.Add("B2:B5", verdadero);
gráfico.NSeries.CategoryData = "A2:A5";

//ExStep:1-
//Mueva la leyenda hacia abajo y establezca el color de fuente de la leyenda
chart.Legend.Font.Color = Color.Blue;
chart.Legend.Position = LegendPositionType.Bottom;

//ExStep:2-
//Acceda a las etiquetas de datos, active los nombres de categoría y establezca la posición
DataLabels dataLabels = chart.NSeries[0].DataLabels;
dataLabels.ShowCategoryName = verdadero;
dataLabels.Position = LabelPositionType.Center;

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