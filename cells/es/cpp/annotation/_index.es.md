---
title: Anotaciones de archivos de Excel a través de C++
url: /es/cpp/annotation/
description: Agregue o elimine comentarios de anotaciones de datos de hojas de cálculo de Excel y OpenOffice con la biblioteca C++.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Administre las anotaciones de archivos de Microsoft<sup>&reg;</sup> Excel a través de C++" h2="Agregue o elimine notas simples para anotaciones o comentarios dentro de las aplicaciones basadas en C++." >}}
{{% blocks/products/pf/feature-page-summary %}}
[C++ excel API](/cells/cpp/) proporciona soporte para administrar anotaciones a nivel de celda agregando, accediendo y eliminando comentarios. API proporciona [IComentario](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_comment) y [ICommentCollection](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection) así como [ObtenerComentarios()](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ae7cce5f85b7b25a1e5c58df1b613ca5a) para el manejo de comentarios en todos los aspectos. Los formatos de Excel compatibles incluyen ODS, XLS, XLSX, XLSB y XLSM.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Anotaciones de datos de archivos de Excel" %}}
Manipulación de comentarios en hojas de trabajo: no está limitado el número de comentarios que tiene una hoja en MS Excel. Uno puede insertar todo lo que necesite la aplicación. El proceso de inserción de comentarios es, crear [ILibro de trabajo](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) objeto de clase para cargar un archivo existente y seleccionar la hoja de trabajo donde desea agregar el comentario. Obtenga todos sus comentarios usando getComments(). Agrega el comentario usando [Agregar](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection#a3f014415e292fa15c6220e9727dad384)(intrusivo_ptr < Aspose::Cells::Systems::String > nombre de la celda) método. Obtenga el índice de celda y use [establecer nota](https://apireference.aspose.com/cells/cpp/com.aspose.cells/comment#Note) para insertar comentarios. Además, API es capaz de eliminar todos los comentarios. Pocos de los métodos son [BorrarComentarios()](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ad4e0ea291ae60fc1b5d815e520edc6c3) a Borra todos los comentarios en la hoja de cálculo del diseñador. Además, [Eliminar en](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet_collection#addabcc7d7d76874694018fb3ba37b72c)(intrusivo_ptr< Aspose::Cells::Systems::String > name) para eliminar el elemento en un índice especificado o con un nombre especificado.

{{% blocks/products/pf/feature-page-code h3="C++ Código para agregar comentarios dentro de un archivo de Excel" %}}

{{< gist "aspose-com-gists" "e144512d2c395c3336f12ce960424686" "add-comment-in-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}