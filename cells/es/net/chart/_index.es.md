---
title: Creación de gráficos de Excel y conversión a imágenes a través de .NET

description: C# código fuente para dibujar y convertir gráficos o diagramas en Microsoft Excel utilizando la biblioteca .NET. 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Creación y conversión de gráficos de archivos de Microsoft<sup>&reg;</sup> Excel a través de .NET" h2="Cree gráficos de documentos de Excel y conviértalos en imágenes usando las API del lado del servidor dentro de las aplicaciones basadas en .NET." >}}
{{% blocks/products/pf/feature-page-summary %}}
Dibujar gráficos es un arte para mostrar datos gráficamente para facilitar el análisis. [.NET Biblioteca de Excel](/cells/net/) admite gráficos de dibujo dentro de archivos de Excel. API admite la creación de diferentes gráficos enumerados en [Enumeración de tipo de gráfico](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype) incluyendo gráficos circulares, piramidales, de líneas y de burbujas. Además, también convierte gráficos en imágenes. API proporciona un [Clase de gráficos](https://reference.aspose.com/cells/net/aspose.cells.charts) para bloques de creación de gráficos.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Crear gráficos dentro de un archivo de Excel" %}}

Crear gráficos usando Excel API es simple. El proceso es, Crear [clase de libro de trabajo](https://reference.aspose.com/cells/net/aspose.cells/workbook) objeto y seleccione la primera hoja de trabajo o la hoja relevante proporcionando su índice. Inserte los datos de las celdas requeridas usando [Método PutValue](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index). Agregue un gráfico a la hoja de trabajo usando la colección Charts [Añadir método](https://reference.aspose.com/cells/net/aspose.cells.charts/chartcollection/methods/add). Especifica el [Tipo de gráfico](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype) de la enumeración ChartType.
{{% blocks/products/pf/feature-page-code h3="C# código para crear gráficos de Excel" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "create-excel-chart.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section h2="Convertir gráficos de Excel en imágenes" %}}

El proceso de conversión de gráficos a imágenes es, use la clase Workbook para cargar el archivo de Excel, seleccione la hoja de trabajo relevante que contiene los gráficos y llame al [método a la imagen](https://reference.aspose.com/cells/net/aspose.cells.charts.chart/toimage/methods/7) para la conversión.

{{% blocks/products/pf/feature-page-code h3="C# Código para convertir un gráfico de Excel en una imagen" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "convert-xlsx-file-chart-to-images.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}
