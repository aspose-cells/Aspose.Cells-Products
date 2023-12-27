---
title: Cree gráficos de Excel y conviértalos en imágenes via Java
description:  Java código fuente para dibujar y convertir gráficos o diagramas en Microsoft Excel usando la biblioteca Java.
keywords: [Java Aspose.Cells., Java Convert chart to image., Java Save chart to image., Java chart to image., create charts in Java., insert charts in Java., manage charts in Java]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Conversión y creación de gráficos de archivos de Excel via Java" h2="Convierta gráficos de documentos de Excel en imágenes y cree varios gráficos utilizando API del lado del servidor dentro de aplicaciones basadas en Java." >}}


{{% blocks/products/pf/feature-page-summary %}}

 El análisis de datos mediante gráficos muestra el panorama más amplio y es fácil tomar decisiones más informadas con conocimientos más claros.[Java Biblioteca de Excel](/cells/es/java/) admite el dibujo de diferentes creaciones de gráficos enumeradas por[Tipo de gráfico](https://reference.aspose.com/cells/java/com.aspose.cells/ChartType) incluidos gráficos circulares, piramidales, de líneas y de burbujas. Además, también convierte gráficos en imágenes. API proporciona un[Clase de gráficos](https://reference.aspose.com/cells/java/com.aspose.cells/Chart) para representar un único gráfico de Excel.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Convertir gráficos de Excel en imágenes" %}}

 El proceso de conversión de gráficos a imágenes, incluidos JPG, PNG, TIFF, BMP, etc., es utilizar el[Libro de trabajo](https://reference.aspose.com/java/cells/com.aspose.cells/workbook) clase para cargar el archivo Excel, seleccione el archivo relevante[grupo de trabajo](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet) que contiene los gráficos o iterar a través de cada gráfico en cada hoja de trabajo. Definir[Opciones de imagen o impresión](https://reference.aspose.com/cells/java/com.aspose.cells/ImageOrPrintOptions) y renderizar la imagen de salida del gráfico usando[Gráfico.aImagen](https://reference.aspose.com/cells/java/com.aspose.cells/chart#toImage(java.io.OutputStream,%20com.aspose.cells.ImageOrPrintOptions)).


{{% blocks/products/pf/feature-page-code h3="Java Código para convertir un gráfico de Excel en una imagen" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "render-excel-chart-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}


{{% blocks/products/pf/feature-page-section h2="Crear gráficos dentro de un archivo de Excel" %}}

Crear gráficos con Excel API es simple, ya que API proporciona un conjunto de diferentes clases como Axis, Chart, ChartArea, ChartDataTable, ChartFrame, ChartPoint, ChartPointCollection, ChartCollection, etc. para diferentes tipos de gráficos. El proceso es Crear un objeto de clase Libro de trabajo y seleccionar la primera hoja de trabajo o la hoja relevante proporcionando su índice. Para la fuente de datos del gráfico, inserte valores en las celdas de la hoja de trabajo usando[valor ajustado](https://reference.aspose.com/cells/java/com.aspose.cells/cell#Value) método. Utilice la colección ChartCollection[agregar método](https://reference.aspose.com/cells/java/com.aspose.cells/chartcollection#add(int,%20int,%20int,%20int,%20int) ) para agregar el gráfico, defina el tipo de gráfico con la enumeración ChartType. Acceda al nuevo objeto Chart de la colección ChartCollection pasando su índice. Utilizar el[SerieColección](https://reference.aspose.com/cells/java/com.aspose.cells/SeriesCollection) objeto de gráfico para especificar la fuente de datos del gráfico.

{{% blocks/products/pf/feature-page-code h3="Java Código para crear gráficos de Excel" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "create-excel-chart-pyramid.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
