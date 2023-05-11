---
title: Cree gráficos de Excel y conviértalos en imágenes a través de C++
description: C++ código fuente para dibujar y convertir gráficos o diagramas en Microsoft Excel usando la biblioteca C++
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Cree gráficos de Excel Microsoft<sup>&reg;</sup> y conviértalos en imágenes a través de C++" h2="Convierta gráficos de documentos de Excel en imágenes y cree gráficos que incluyen gráficos circulares, piramidales, de líneas y de burbujas dentro de las aplicaciones basadas en C++." >}}

{{% blocks/products/pf/feature-page-summary %}}

 Usando gráficos de Excel, uno puede obtener una imagen más grande y analizar datos fácilmente para tomar decisiones correctas.[C++ Biblioteca Excel](/cells/es/cpp/) admite la creación de diferentes gráficos enumerados por[enumeración Aspose::Cells::Gráficos::Tipo de gráfico
](https://reference.aspose.com/cells/cpp/namespace/aspose.cells.charts#a2f17e69bcefc754569019185d0621b70) incluyendo gráficos de áreas, de barras, circulares, piramidales, de líneas y de burbujas. Además, para la conversión de gráficos a imágenes, API proporciona un[Método ToImage](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_sparkline#a28d76dd585c48366e1657f2982722ddb) en el formato de imagen requerido.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Crear gráficos de Excel" %}}

 El proceso de creación de un gráfico de Excel es crear una instancia del[Clase de libro de trabajo](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) y seleccione el deseado[Hoja de cálculo](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet_collection#a5574d624796043233420d0e0459ccc43) . Agregue el gráfico usando[Añadir método](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_chart_collection#ab7e8cce835c251a4682605299a6aa068)con parámetros relevantes, incluido el tipo de gráfico. Acceda al gráfico a través de índice y[Agregar](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_series_collection#a8f4dc4d883f32f65b1fb673e2aa7862f) la fuente de datos para el gráfico.

{{% blocks/products/pf/feature-page-code h3="C++ Código para crear gráficos de Excel" %}}

{{< gist "aspose-com-gists" "da2fd423617bf9013a7673870c81d708" "create-excel-chart.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Convertir gráficos en imágenes" %}}


Para el proceso de conversión de gráficos, primero cree un gráfico del tipo relevante utilizando el código anterior o acceda a él desde la hoja correspondiente. Defina la ruta de guardado de salida para la imagen y use el método ToImage para la conversión.

 
{{% blocks/products/pf/feature-page-code h3="C++ Código para convertir gráficos de Excel" %}}

{{< gist "aspose-com-gists" "da2fd423617bf9013a7673870c81d708" "convert-excel-chart-to-image.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}
