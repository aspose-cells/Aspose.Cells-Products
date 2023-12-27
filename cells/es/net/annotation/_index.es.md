---
title: Agregar o quitar anotaciones de archivos de Excel NET C#
description: Agregue o elimine anotaciones de datos de hojas de cálculo de Excel y OpenOffice con solo unas pocas líneas de código C#.
keywords: [C# Aspose.Cells., add excel annotation., insert excel annotation., access excel annotation., remove excel annotation., delete excel annotation., add annotation in excel., insert annotation in excel., access annotation in excel., remove annotation in excel., delete annotation in excel]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Eliminar Microsoft<sup>&reg;</sup> Anotaciones de archivos de Excel via .NET" h2="Agregue o elimine anotaciones de archivos de Excel utilizando el código C# dentro de aplicaciones basadas en .NET." >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Biblioteca de Excel](/cells/es/net/) brinda soporte para administrar anotaciones a nivel de celda agregando, accediendo y eliminando comentarios. Utilizando comentarios a nivel de celda, se puede almacenar información relevante para los usuarios finales. Los formatos de archivo admitidos incluyen ODS, XLS, XLSX, XLSB y XLSM.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Anotaciones de datos de archivos de Excel" %}}
 Gestión de comentarios en hojas de trabajo: no hay ningún límite en cuanto a la cantidad de comentarios que tiene una hoja en MS Excel. Se puede agregar tanto como sea necesario según los requisitos de la aplicación. Usaremos el[Clase de comentario](https://reference.aspose.com/cells/net/aspose.cells/comment)para toda esta funcionalidad.

+ Cargar archivo de Excel usando el objeto de clase Workbook
+ Acceda a la Hoja de Trabajo relevante y su índice Cell relevante
+ Llama a RemoveAt con el Id Cell para eliminarlo
 + Uso[Propiedad de nota](https://reference.aspose.com/cells/net/aspose.cells/comment/properties/note) para agregar contenido de comentarios
+ Guarde el libro antes y después de llamar al método RemoveAt para comparar

{{% blocks/products/pf/feature-page-code h3="C# Código para Acceder, Insertar y Eliminar Archivos Excel Cell Comentarios" %}}


{{< gist "aspose-com-gists" "e3dcb9c341b81d4db3a404ca7cd6e4cf" "access-insert-and-delete-excel-files-cell-comments.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}
