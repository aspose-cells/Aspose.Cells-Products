---
title: Dividir la hoja de cálculo de Excel sabiamente en C#
url: /es/net/splitter/
description: C# códigos fuente que explican cómo dividir archivos de Microsoft Excel en varios archivos en aplicaciones visuales C#.NET
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="División de archivos de Microsoft<sup>&reg;</sup> Excel a través de .NET" h2="Dividir un solo documento de Excel en diferentes archivos utilizando el código C# dentro de las aplicaciones basadas en .NET" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Biblioteca de Excel](/cells/net/) es capaz de dividir documentos de Excel en múltiples hojas de cálculo dentro de aplicaciones basadas en .NET. Los formatos de archivo admitidos incluyen XLS, XLSX, XLSB, XLSM, ODS.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Dividir documento de Excel en varios archivos" %}}
La forma más sencilla de dividir hojas de archivos de Excel es acceder a todas las hojas a través de [Hojas de trabajo](https://apireference.aspose.com/cells/net/aspose.cells/workbook/properties/worksheets), iterando a través de cada hoja y llamando al [Dupdo](https://apireference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy) método. Finalmente guardándolo en una ruta específica. 

+ Cargue el archivo de Excel con la ruta completa usando [clase de libro de trabajo](https://apireference.aspose.com/cells/net/aspose.cells/workbook).
+ Iterar a través de cada hoja
+ Crear un nuevo objeto de clase Workbook
+ Copiar la hoja vía [método de copia](https://apireference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy)
+ Llame al método Save() y pase el nombre del archivo (ruta completa) con SaveFormat relevante.

{{% blocks/products/pf/feature-page-code h3="C# Código para dividir archivos de Excel" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="Dividir la hoja de cálculo de Excel en paneles" %}}

Para dividir la ventana de la hoja de trabajo en paneles, API proporciona [método de división](https://apireference.aspose.com/cells/net/aspose.cells/worksheet/methods/split) de la clase de hoja de trabajo, que proporciona la vista dividida de la hoja de trabajo. Para eliminar la vista dividida API proporciona [Método RemoveSplit](https://apireference.aspose.com/cells/net/aspose.cells/worksheet/methods/removesplit). Finalmente, guárdelo en una ruta específica. 

{{% blocks/products/pf/feature-page-code h3="C# Código para dividir la ventana de la hoja de cálculo de Excel" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet-into-pane.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C# Código para eliminar la vista panorámica dividida" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "remove-splitted-spreadsheet-pane-view.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
