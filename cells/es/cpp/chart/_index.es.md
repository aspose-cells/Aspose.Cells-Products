---
title: Cree gráficos de Excel y conviértalos a imágenes a través de C++
description: C++ código fuente para dibujar y convertir gráficos o diagramas en Microsoft Excel usando la biblioteca C++
keywords: [C++ Aspose.Cells., C++ Convert chart to image., C++ Save chart to image., C++ chart to image., create charts in C++., insert charts in C++., manage charts in C++]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Cree gráficos de Excel Microsoft<sup>&reg;</sup> y conviértalos en imágenes mediante C++" h2="Convierta gráficos de documentos de Excel en imágenes y cree gráficos que incluyen gráficos circulares, piramidales, de líneas y de burbujas dentro de aplicaciones basadas en C++." >}}

{{% blocks/products/pf/feature-page-summary %}}

 Con los gráficos de Excel, se puede obtener una visión más amplia y analizar los datos fácilmente para tomar las decisiones correctas.[C++ Biblioteca de Excel](/cells/es/cpp/) admite la creación de diferentes gráficos enumerados por[enumeración Aspose::Cells::Gráficos::Tipo de gráfico
](https://reference.aspose.com/cells/cpp/aspose.cells.charts/charttype/) incluyendo gráficos de áreas, barras, circulares, piramidales, de líneas y de burbujas. Además, para la conversión de gráficos a imágenes, API proporciona una[A la imagen](https://reference.aspose.com/cells/cpp/aspose.cells.charts/chart/toimage/) método en el formato de imagen requerido.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Crear gráficos de Excel" %}}

 El proceso de creación de un gráfico de Excel es crear una instancia del[clase de libro de trabajo](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) y seleccione el deseado[Hoja de cálculo](https://reference.aspose.com/cells/cpp/aspose.cells/worksheet/) . Agregue el gráfico usando[Agregar método](https://reference.aspose.com/cells/cpp/aspose.cells.charts/chartcollection/add/)con parámetros relevantes, incluido el tipo de gráfico. Acceda al gráfico a través del índice y[Agregar](https://reference.aspose.com/cells/cpp/aspose.cells.charts/seriescollection/add/) la fuente de datos para el gráfico.

{{% blocks/products/pf/feature-page-code h3="C++ Código para crear gráficos de Excel" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "create-excel-chart.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Convertir gráficos en imágenes" %}}


Para el proceso de conversión de gráficos, primero cree un gráfico del tipo relevante utilizando el código anterior o acceda a él desde la hoja correspondiente. Defina la ruta para guardar la salida de la imagen y utilice el método ToImage para la conversión.

 
{{% blocks/products/pf/feature-page-code h3="C++ Código para convertir gráficos de Excel" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "convert-excel-chart-to-image.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}
