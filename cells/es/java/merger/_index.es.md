---
title: Combinar diferentes archivos de Excel en uno solo en Java
description: Combine archivos de Excel usando Java en varias hojas o en una sola hoja. Combine, combine o concatene documentos de Excel en PDF, Imágenes y HTML también.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Combinación de archivos de Excel via Java" h2="Combine dos o más archivos de Excel en una sola hoja de cálculo usando el código Java" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Biblioteca Excel](/cells/es/java/) proporciona múltiples formas de combinar libros de trabajo con varios tipos de contenido como fórmulas, imágenes, datos, gráficos, etc. en un solo documento de hoja de cálculo. Los formatos de archivo admitidos incluyen XLS, XLSX, XLSB, XLT, XLTX, XLTM, ODS, CSV, TSV y más.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Combine archivos de Excel con imágenes y gráficos" %}}
 La forma más sencilla de combinar dos archivos de Excel que tienen imágenes y gráficos es llamando al[Workbook.combine](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#combine(com.aspose.cells.Workbook)) método. Permite fusionar archivos de Excel de tipo similar en una sola hoja de cálculo.
{{% blocks/products/pf/feature-page-code h3="Java Código para combinar archivos de Excel" %}}

```cs
// load first Excel file
var book1 = new Workbook("with-charts.xlsx");
// load second Excel file into a separate instance
var book2 = new Workbook("with-images.xlsx");

// merge two workbooks
book1.combine(book2);
// save the target workbook 
book1.save("combined.xlsx");
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Combinar varios archivos de Excel" %}}
[CellsHelper.mergeFiles](https://reference.aspose.com/cells/java/com.aspose.cells/cellshelper#mergeFiles)El método admite la combinación de datos, estilo y fórmulas de un archivo de Excel en una nueva hoja de cálculo del mismo formato. Es una forma eficiente de fusionar varios archivos mientras usa el almacenamiento en caché.
{{% blocks/products/pf/feature-page-code h3="Java Código para fusionar varios archivos de Excel" %}}

```cs
// create an Array (length=2)
String[] files = new String[2];
// specify file paths to be merged
files[0] = "Book1.xls";
files[1] = "Book2.xls";
// merge the files to save the result
CellsHelper.mergeFiles(files, "cache", "merged.xls");

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Combinar archivos de Excel copiando hojas de trabajo" %}}
[Hoja de trabajo.copia](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet#copy(com.aspose.cells.Worksheet)) se puede usar para copiar datos y formato de una hoja de trabajo de origen a otra hoja de trabajo dentro o entre libros de trabajo. El método toma el objeto de la hoja de cálculo de origen como parámetro.
{{% blocks/products/pf/feature-page-code h3="Java Código para copiar hojas de trabajo entre libros de trabajo" %}}

```cs
// Create a Workbook.
Workbook excelWorkbook0 = new Workbook(dataDir + "book1.xls");

// Create another Workbook.
Workbook excelWorkbook1 = new Workbook();

// Copy the first sheet of the first book into second book.
excelWorkbook1.getWorksheets().get(0).copy(excelWorkbook0.getWorksheets().get(0));

// Save the file.
excelWorkbook1.save(dataDir + "out.xls", FileFormatType.EXCEL_97_TO_2003);
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/other-supported-section title="Otros formatos de fusión admitidos" subTitle="Con Java, también se pueden fusionar muchos otros formatos de archivo, incluidos .." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/csv/" name="CSV" description="Valores Separados por Comas" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/html/" name="HTML" description="Lenguaje de marcado de hipertexto" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/mhtml/" name="MHTML" description="Formato de archivo de página web" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/ods/" name="ODS" description="Archivo de hoja de cálculo OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/tsv/" name="TSV" description="Valores separados por tabuladores" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/txt/" name="TXT" description="Documento de texto" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xls/" name="XLS" description="Formato binario de Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsb/" name="XLSB" description="Archivo de libro de Excel binario" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsm/" name="XLSM" description="Archivo de hoja de cálculo" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsx/" name="XLSX" description="Archivo de Excel OOXML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlt/" name="XLT" description="Microsoft Plantilla de Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xltm/" name="XLTM" description="Plantilla de Excel habilitada para macros" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}
