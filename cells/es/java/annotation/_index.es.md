---
title: Anotaciones de archivos de Excel a través de Java
url: /es/java/annotation/
description: Agregue o elimine anotaciones de datos de hojas de cálculo de Excel y OpenOffice con la biblioteca Java.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Administre las anotaciones de archivos de Microsoft<sup>&reg;</sup> Excel a través de Java" h2="Inserte notas simples para anotaciones o elimine los comentarios a nivel de celda de la hoja de cálculo de Excel dentro de las aplicaciones basadas en Java." >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java excel API](/cells/java/) proporciona soporte para administrar anotaciones a nivel de celda agregando, accediendo y eliminando comentarios. API proporciona [Comentario](https://reference.aspose.com/cells/java/com.aspose.cells/Comment), [Colección de comentarios](https://reference.aspose.com/cells/java/com.aspose.cells/CommentCollection), [Comentario enhebrado](https://reference.aspose.com/cells/java/com.aspose.cells/ThreadedComment) y [ThreadedCommentCollection](https://reference.aspose.com/cells/java/com.aspose.cells/ThreadedCommentCollection) para el manejo de comentarios en todos los aspectos.
Los formatos de archivo compatibles incluyen ODS, XLS, XLSX, XLSB y XLSM.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Anotaciones de datos de archivos de Excel" %}}
Gestión de comentarios en hojas de trabajo: no hay ningún límite en cuanto a la cantidad de comentarios que tiene una hoja en MS Excel. Se puede agregar tanto como de requisito de aplicación. El proceso de agregar comentarios es crear [Libro de trabajo](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) objeto de clase o cargar un archivo existente usando la clase Workbook. Accede a todos sus comentarios usando getComments(). Obtenga el índice de celda y use [establecer nota](https://reference.aspose.com/cells/java/com.aspose.cells/comment#Note) para insertar comentarios. Además, API es capaz de eliminar todos los comentarios. 

{{% blocks/products/pf/feature-page-code h3="Java Código para agregar comentarios dentro de un archivo de Excel" %}}

{{< gist "aspose-com-gists" "1b223bbd23b1c5b3fb5c96614e5584c6" "add-comments-excel-file.java" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Java Código para eliminar comentarios dentro de un archivo de Excel" %}}

{{< gist "aspose-com-gists" "1b223bbd23b1c5b3fb5c96614e5584c6" "remove-annotation-in-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}