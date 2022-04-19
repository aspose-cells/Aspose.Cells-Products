---
title: Divida la hoja de cálculo de Excel en hojas de trabajo en Java
url: /es/java/splitter/
description: Java códigos fuente que explican cómo dividir archivos de Microsoft Excel en varios documentos utilizando la biblioteca de Java Excel
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="División de archivos de Microsoft<sup>&reg;</sup> Excel a través de Java" h2="Divida la hoja de cálculo de Excel en hojas de trabajo dentro de las aplicaciones basadas en Java" >}}
{{% blocks/products/pf/feature-page-summary %}}
Hay una variedad de escenarios, cuando es necesario dividir archivos de Excel como una hoja de cálculo que contiene datos de estudiantes con asignación de una sola hoja para cada estudiante. Y es necesario dividir cada hoja por estudiante como un archivo separado. Para automatizarlo a través de la aplicación Java, [Java excel API](/cells/java/) está ahí para dividir el documento de Excel en hojas. Los formatos admitidos incluyen XLS, XLSX, XLSB, XLSM, ODS. 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Dividir documento de Excel en varios archivos" %}}

La forma más sencilla de dividir un archivo de Excel en una hoja es acceder a todas las hojas, recorrer cada hoja y guardar una por una en el formato deseado. Para cargar la hoja de trabajo, API proporciona [Libro de trabajo](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) clase. [getWorksheets().getCount()](https://apireference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#Count) método obtiene el número total de hojas. Iterar a través de cada hoja y usar [getWorksheets().get(sheetindex)](https://apireference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#get) para acceder a la hoja específica. Mueva los datos de la hoja seleccionada al objeto de clase de libro de trabajo recién creado usando [método de copia](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#copy(com.aspose.cells.Workbook)). Finalmente guárdelo en el formato requerido.

{{% blocks/products/pf/feature-page-code h3="Java Código para dividir archivos de Excel" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-xls-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="Dividir la hoja de cálculo de Excel en paneles" %}}

API también proporciona la funcionalidad de dividir la hoja de cálculo de Excel en diferentes paneles. El proceso es, cargar el archivo usando la clase Workbook. Seleccione la primera hoja de trabajo o cualquier hoja requerida proporcionando su índice. Llame al setActiveCell que tiene el índice de celda relevante como parámetro. Y finalmente divida la ventana de la hoja de trabajo en diferentes paneles llamando al método split().

{{% blocks/products/pf/feature-page-code h3="Java Código para dividir la hoja de Excel en la vista de panel" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-excel-spreadsheet-into-panes.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}