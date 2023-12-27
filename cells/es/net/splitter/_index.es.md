---
title: Dividir la hoja de cálculo de Excel en hojas en C#
description: C# códigos fuente que explican cómo dividir archivos Microsoft Excel en varios archivos en aplicaciones Visual C#.NET
keywords: [C# Aspose.Cells., C# split excel files., C# how to split excel files into multiple files., C# excel splitter., C# split Cell., Cell splitter using C#]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> División de archivos de Excel via .NET" h2="Divida un solo documento de Excel en diferentes archivos usando el código C# dentro de aplicaciones basadas en .NET" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Biblioteca de Excel](/cells/es/net/) es capaz de dividir documentos de Excel en varias hojas de cálculo dentro de aplicaciones basadas en .NET. Los formatos de archivo admitidos incluyen XLS, XLSX, XLSB, XLSM, ODS.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Dividir documento de Excel en varios archivos" %}}
La forma más sencilla de dividir archivos de Excel en hojas es acceder a todas las hojas a través de[Hojas de trabajo](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/worksheets) , Iterando a través de cada hoja y llamando al[Copiar](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy) método. Finalmente guárdelo en una ruta especificada.

 + Cargue el archivo de Excel con la ruta completa usando[clase de libro de trabajo](https://reference.aspose.com/cells/net/aspose.cells/workbook).
+ Iterar a través de cada hoja
+ Crear un nuevo objeto de clase Libro de trabajo
 + Copiar la hoja vía[Método de copia](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy)
+ Llame al método Save() y pase el nombre del archivo (ruta completa) que tenga el formato SaveFormat correspondiente.

{{% blocks/products/pf/feature-page-code h3="C# Código para dividir archivos de Excel" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="Dividir la hoja de cálculo de Excel en paneles" %}}

 Para dividir la ventana de la hoja de trabajo en paneles, API proporciona[método dividido](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/split) de clase de hoja de trabajo, que proporciona la vista dividida de la hoja de trabajo. Para eliminar la vista dividida, API proporciona[Método RemoveSplit](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/removesplit) . Finalmente guárdelo en una ruta especificada.

{{% blocks/products/pf/feature-page-code h3="C# Código para dividir la ventana de la hoja de cálculo de Excel" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet-into-pane.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C# Código para eliminar la vista panorámica dividida" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "remove-splitted-spreadsheet-pane-view.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
