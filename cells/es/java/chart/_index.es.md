---
title: Cree gráficos de Excel y conviértalos en imágenes a través de Java
url: /es/java/chart/
description: Java código fuente para dibujar y convertir gráficos o diagramas en Microsoft Excel utilizando la biblioteca Java. 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Conversión y creación de gráficos de archivos de Microsoft<sup>&reg;</sup> Excel a través de Java" h2="Convierta gráficos de documentos de Excel en imágenes y cree varios gráficos utilizando las API del lado del servidor dentro de las aplicaciones basadas en Java." >}}


{{% blocks/products/pf/feature-page-summary %}}

El análisis de datos a través de gráficos muestra una imagen más amplia y es fácil tomar decisiones más informadas con información más clara. [Java Biblioteca de Excel](/cells/java/) admite la creación de diferentes gráficos de dibujo enumerados por [Tipo de gráfico](https://reference.aspose.com/cells/java/com.aspose.cells/ChartType) incluyendo gráficos circulares, piramidales, de líneas y de burbujas. Además, también convierte gráficos en imágenes. API proporciona un [Clase de gráficos](https://reference.aspose.com/cells/java/com.aspose.cells/Chart) para representar un único gráfico de Excel.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Convertir gráficos de Excel en imágenes" %}}

El proceso de conversión de gráficos a imágenes, incluidos JPG, PNG, TIFF, BMP, etc., utiliza el [Libro de trabajo](https://reference.aspose.com/java/cells/com.aspose.cells/workbook) clase para cargar el archivo de Excel, seleccione la correspondiente [hoja de trabajo](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet) que contienen los gráficos o iterar a través de cada gráfico en cada hoja de trabajo. Definir [ImageOrPrintOptions](https://reference.aspose.com/cells/java/com.aspose.cells/ImageOrPrintOptions) y renderizar la imagen de salida del gráfico usando [Chart.toImage](https://reference.aspose.com/cells/java/com.aspose.cells/chart#toImage(java.io.OutputStream,%20com.aspose.cells.ImageOrPrintOptions)).


{{% blocks/products/pf/feature-page-code h3="Java Código para convertir un gráfico de Excel en una imagen" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "render-excel-chart-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}


{{% blocks/products/pf/feature-page-section h2="Crear gráficos dentro de un archivo de Excel" %}}

La creación de gráficos con Excel API es simple, ya que API proporciona un conjunto de diferentes clases como Axis, Chart, ChartArea, ChartDataTable, ChartFrame, ChartPoint, ChartPointCollection, ChartCollection, etc. para diferentes tipos de gráficos. El proceso es, Crear objeto de clase Libro de trabajo y seleccione la primera hoja de trabajo o la hoja relevante proporcionando su índice. Para la fuente de datos del gráfico, inserte valores en las celdas de la hoja de trabajo usando [valor ajustado](https://reference.aspose.com/cells/java/com.aspose.cells/cell#Value) método. Utilice la colección de ChartCollection [añadir método](https://reference.aspose.com/cells/java/com.aspose.cells/chartcollection#add(int,%20int,%20int,%20int,%20int)) para agregar el gráfico, defina el tipo de gráfico con la enumeración ChartType. Acceda al nuevo objeto Chart de la colección ChartCollection pasando su índice. Utilizar el [SerieColección](https://reference.aspose.com/cells/java/com.aspose.cells/SeriesCollection) objeto de gráfico para especificar la fuente de datos del gráfico.

{{% blocks/products/pf/feature-page-code h3="Java código para crear gráficos de Excel" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "create-excel-chart-pyramid.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}