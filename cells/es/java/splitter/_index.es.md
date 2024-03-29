---
title: Divida la hoja de cálculo de Excel en hojas de trabajo en Java
description: Java códigos fuente que explican cómo dividir archivos de Excel Microsoft en varios documentos usando la biblioteca de Excel Java
keywords: [Java Aspose.Cells., Java split excel files., Java how to split excel files into multiple files., Java excel splitter., Java split Cell., Cell splitter using Java]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> División de archivos de Excel via Java" h2="Divida la hoja de cálculo de Excel en hojas de trabajo dentro de aplicaciones basadas en Java" >}}
{{% blocks/products/pf/feature-page-summary %}}
Hay una variedad de escenarios cuando es necesario dividir archivos de Excel como una hoja de cálculo que contiene datos de los estudiantes con asignación de una sola hoja para cada estudiante. Y es necesario dividir cada hoja por estudiante como un archivo separado. Para automatizarla aplicación via Java,[Java Excel API](/cells/es/java/) está ahí para dividir el documento de Excel en hojas. Los formatos admitidos incluyen XLS, XLSX, XLSB, XLSM, ODS.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Dividir documento de Excel en varios archivos" %}}

 La forma más sencilla de dividir un archivo de Excel en una hoja es acceder a todas las hojas, recorrer cada hoja y guardarla una por una en el formato deseado. Para cargar la hoja de trabajo, API proporciona[Libro de trabajo](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) clase.[getWorksheets().getCount()](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#Count) El método obtiene el número total de hojas. Repita cada hoja y use[getWorksheets().get(sheetindex)](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#get) para acceder a una hoja específica. Mueva los datos de la hoja seleccionada al objeto de clase Libro de trabajo recién creado usando[Método de copia](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#copy(com.aspose.cells.Workbook)). Finalmente guárdelo en el formato requerido.

{{% blocks/products/pf/feature-page-code h3="Java Código para dividir archivos de Excel" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-xls-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="Dividir la hoja de cálculo de Excel en paneles" %}}

API también proporciona la funcionalidad de dividir la hoja de cálculo de Excel en diferentes paneles. El proceso es cargar el archivo usando la clase Workbook. Seleccione la primera hoja de trabajo o cualquier hoja requerida proporcionando su índice. Llame a setActiveCell que tenga el índice de celda relevante como parámetro. Y finalmente divida la ventana de la hoja de trabajo en diferentes paneles llamando al método split().

{{% blocks/products/pf/feature-page-code h3="Java Código para dividir una hoja de Excel en una vista de panel" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-excel-spreadsheet-into-panes.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
