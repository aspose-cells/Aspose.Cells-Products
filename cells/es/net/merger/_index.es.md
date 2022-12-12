---
title: Fusión de archivos de Excel API .NET C#

description: Concatene archivos de hojas de cálculo de Excel y OpenOffice con solo unas pocas líneas de código C#.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Combinación de archivos de Microsoft<sup>&reg;</sup> Excel a través de .NET" h2="Combine 2 o más archivos de Excel en una sola hoja de cálculo usando el código C#" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Biblioteca de Excel](/cells/net/) proporciona múltiples formas de combinar libros de trabajo con varios tipos de contenido como fórmulas, datos, imágenes, gráficos, etc. en un solo archivo de hoja de cálculo. Los formatos de archivo admitidos incluyen XLS, XLSX, XLSB, XLT, XLTX, XLTM, ODS, CSV, TSV y más.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Combine archivos de Excel con imágenes y gráficos" %}}
La forma más sencilla de combinar 2 archivos de Excel que tienen imágenes y gráficos es llamando al [Libro de trabajo.Combinar](https://reference.aspose.com/cells/net/aspose.cells/workbook/methods/combine) método. Permite fusionar archivos de Excel de tipo similar en una sola hoja de cálculo.
{{% blocks/products/pf/feature-page-code h3="C# Código para combinar archivos de Excel" %}}

{{< gist "aspose-com-gists" "d7c757e7471bd38006ac0d35d221b2e2" "combine-two-workbooks.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Combinar varios archivos de Excel" %}}
[CellsHelper.MergeFiles](https://reference.aspose.com/cells/net/aspose.cells/cellshelper/methods/mergefiles) El método admite la combinación de datos, estilo y fórmulas de un archivo de Excel en una nueva hoja de cálculo del mismo formato. Es una forma eficiente de fusionar varios archivos mientras usa el almacenamiento en caché. 
{{% blocks/products/pf/feature-page-code h3="C# Código para fusionar varios archivos de Excel" %}}

{{< gist "aspose-com-gists" "d7c757e7471bd38006ac0d35d221b2e2" "merge-several-excel-files.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Combinar archivos de Excel copiando hojas de trabajo" %}}
[Hoja de trabajo.Copiar](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy/index) se puede usar para copiar datos y formato de una hoja de trabajo de origen a otra hoja de trabajo dentro o entre libros de trabajo. El método toma el objeto de la hoja de cálculo de origen como parámetro.
{{% blocks/products/pf/feature-page-code h3="C# Código para copiar hojas de trabajo en archivos de Excel" %}}

{{< gist "aspose-com-gists" "d7c757e7471bd38006ac0d35d221b2e2" "copy-worksheets-across-excel-files.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Merger" >}}
