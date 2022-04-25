---
title: Combinar diferentes archivos de Excel en uno solo en Java
url: /es/java/merger/
description: Combine archivos de Excel usando Java en varias hojas o en una sola hoja. Combine, combine o concatene documentos de Excel en PDF, imágenes y HTML también.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Combinación de archivos de Microsoft<sup>&reg;</sup> Excel a través de Java" h2="Combine dos o más archivos de Excel en una sola hoja de cálculo usando el código Java" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Biblioteca de Excel](/cells/java/) proporciona múltiples formas de combinar libros de trabajo con varios tipos de contenido como fórmulas, imágenes, datos, gráficos, etc. en un solo documento de hoja de cálculo. Los formatos de archivo admitidos incluyen XLS, XLSX, XLSB, XLT, XLTX, XLTM, ODS, CSV, TSV y más.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Combine archivos de Excel con imágenes y gráficos" %}}
La forma más sencilla de combinar dos archivos de Excel que tienen imágenes y gráficos es llamando al [Workbook.combine](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#combine(com.aspose.cells.Workbook)) método. Permite fusionar archivos de Excel de tipo similar en una sola hoja de cálculo.
{{% blocks/products/pf/feature-page-code h3="Java Código para combinar archivos de Excel" %}}

```cs
// cargar el primer archivo de Excel
var book1 = new Workbook("with-charts.xlsx");
// cargue el segundo archivo de Excel en una instancia separada
var book2 = new Workbook("with-images.xlsx");

// combinar dos libros de trabajo
book1.combine(book2);
// guardar el libro de destino 
book1.save("combined.xlsx");

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Combinar varios archivos de Excel" %}}
[CellsHelper.mergeFiles](https://apireference.aspose.com/cells/java/com.aspose.cells/cellshelper#mergeFiles) El método admite la combinación de datos, estilo y fórmulas de un archivo de Excel en una nueva hoja de cálculo del mismo formato. Es una forma eficiente de fusionar varios archivos mientras usa el almacenamiento en caché. 
{{% blocks/products/pf/feature-page-code h3="Java Código para fusionar varios archivos de Excel" %}}

```cs
// crear una matriz (longitud = 2)
String[] files = new String[2];
// especificar las rutas de los archivos que se fusionarán
files[0] = "Book1.xls";
files[1] = "Book2.xls";
// combinar los archivos para guardar el resultado
CellsHelper.mergeFiles(files, "cache", "merged.xls");


```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Combinar archivos de Excel copiando hojas de trabajo" %}}
[Hoja de trabajo.copia](https://apireference.aspose.com/cells/java/com.aspose.cells/worksheet#copy(com.aspose.cells.Worksheet)se puede usar para copiar datos y formato de una hoja de trabajo de origen a otra hoja de trabajo dentro o entre libros de trabajo. El método toma el objeto de la hoja de cálculo de origen como parámetro.
{{% blocks/products/pf/feature-page-code h3="Java Código para copiar hojas de trabajo entre libros de trabajo" %}}

```cs
// Crear un libro de trabajo.
Workbook excelWorkbook0 = new Workbook(dataDir + "book1.xls");

// Cree otro libro de trabajo.
Workbook excelWorkbook1 = new Workbook();

// Copie la primera hoja del primer libro en el segundo libro.
excelWorkbook1.getWorksheets().get(0).copy(excelWorkbook0.getWorksheets().get(0));

// Guarda el archivo.
excelWorkbook1.save(dataDir + "out.xls", FileFormatType.EXCEL_97_TO_2003);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Merger" >}}