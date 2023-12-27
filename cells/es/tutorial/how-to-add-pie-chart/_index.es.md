---
title: Cómo agregar un gráfico circular a través de Aspose.Cells
weight: 7700
limit:
description: Aprenda a agregar un gráfico circular.
keywords: [Add pie chart., how to add pie chart in Aspose.Cells., how to add pie chart using Aspose.Cells]
url: /es/tutorial/add-pie-chart-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Aprenda a agregar un gráfico circular con Aspose.Cells" >}}

<p>
En este tutorial, agregaremos un gráfico circular en un archivo de Excel.
</p>

<p>
 Comenzaremos creando un nuevo libro de trabajo usando el<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells biblioteca</a> y agregue un gráfico circular.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: verifique el siguiente código para descubrir cómo agregar un gráfico circular.
//ExStepSummary:0: el siguiente código muestra cómo agregar un gráfico circular, establecer el rango de datos de la serie y establecer el rango de datos de la categoría.
//ExStepImage:0:paso-1.png
//ExStepSummary:1: el siguiente código muestra cómo desactivar la leyenda.
//ExStepImage:1:paso-2.png
//ExStepSummary:2: el siguiente código muestra cómo acceder a las etiquetas de datos, activar los nombres de categorías, activar el formato de porcentaje y establecer la posición.
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

//Agregar gráfico circular, establecer rango de datos de series y establecer rango de datos de categorías
int index = hoja.Charts.Add(ChartType.Pie, 6, 0, 19, 5);
Gráfico gráfico = hoja.Charts[index];
chart.NSeries.Add("B2:B5", verdadero);
chart.NSeries.CategoryData = "A2:A5";

//ExPaso:1-
//Desactivar leyenda
chart.ShowLegend = falso;

//ExPaso:2-
//Accede a las etiquetas de datos, activa los nombres de las categorías, activa el formato de porcentaje y establece la posición
Etiquetas de datos etiquetas de datos = chart.NSeries[0].DataLabels;
dataLabels.ShowCategoryName = verdadero;
dataLabels.ShowPercentage = verdadero;
dataLabels.Position = LabelPositionType.OutsideEnd;

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