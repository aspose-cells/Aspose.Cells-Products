---
title: Anotaciones de archivos de Excel NET C#
description: Agregue o elimine anotaciones de datos de hojas de cálculo de Excel y OpenOffice con solo unas pocas líneas de código C#.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Eliminar Microsoft<sup>&reg;</sup> Anotaciones de archivos de Excel via .NET" h2="Agregue o elimine anotaciones de archivos de Excel usando el código C# dentro de las aplicaciones basadas en .NET." >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Biblioteca Excel](/cells/es/net/) proporciona soporte para administrar anotaciones a nivel de celda agregando, accediendo y eliminando comentarios. Usando comentarios a nivel de celda, se puede almacenar información relevante para los usuarios finales. Los formatos de archivo admitidos incluyen ODS, XLS, XLSX, XLSB y XLSM.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Anotaciones de datos de archivos de Excel" %}}
 Gestión de comentarios en hojas de trabajo: no hay ningún límite en cuanto a la cantidad de comentarios que tiene una hoja en MS Excel. Se puede agregar tanto como de requisito de aplicación. Usaremos el[Clase de comentario](https://reference.aspose.com/cells/net/aspose.cells/comment)para toda esta funcionalidad.

+ Cargar archivo de Excel usando el objeto de clase Workbook
+ Acceda a la hoja de trabajo correspondiente y su índice Cell correspondiente
+ Llame a RemoveAt con la identificación Cell para eliminarlo
 + Uso[Nota propiedad](https://reference.aspose.com/cells/net/aspose.cells/comment/properties/note) para agregar contenido de comentarios
+ Guarde el libro de trabajo antes y después de llamar al método RemoveAt para comparar

{{% blocks/products/pf/feature-page-code h3="C# Código para Acceder, Insertar y Eliminar Archivos Excel Cell Comentarios" %}}


{{< gist "aspose-com-gists" "e3dcb9c341b81d4db3a404ca7cd6e4cf" "access-insert-and-delete-excel-files-cell-comments.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}
