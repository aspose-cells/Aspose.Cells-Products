---
title: Agregar o eliminar anotaciones de archivos de Excel a través de C++
description: Agregue o elimine comentarios de anotaciones de datos de hojas de cálculo de Excel y OpenOffice con la biblioteca C++.
keywords: [C++ Aspose.Cells., add excel annotation., insert excel annotation., access excel annotation., remove excel annotation., delete excel annotation., add annotation in excel., insert annotation in excel., access annotation in excel., remove annotation in excel., delete annotation in excel]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Administre Microsoft<sup>&reg;</sup> Anotaciones de archivos de Excel a través de C++" h2="Agregue o elimine notas simples para anotaciones o comentarios dentro de las aplicaciones basadas en C++." >}}
{{% blocks/products/pf/feature-page-summary %}}
[C++ Excel API](/cells/es/cpp/) brinda soporte para administrar anotaciones a nivel de celda agregando, accediendo y eliminando comentarios. API proporciona[Comentario](https://reference.aspose.com/cells/cpp/aspose.cells/comment/) y[Colección de comentarios](https://reference.aspose.com/cells/cpp/aspose.cells/commentcollection/) así como[GetComments()](https://reference.aspose.com/cells/cpp/aspose.cells/worksheet/getcomments/)para manejar comentarios en todos los aspectos. Los formatos de Excel admitidos incluyen ODS, XLS, XLSX, XLSB y XLSM.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Anotaciones de datos de archivos de Excel" %}}
 Manipulación de comentarios en hojas de trabajo: no está limitado el número de comentarios que tiene una hoja en MS Excel. Se puede insertar tanto como sea necesario para la aplicación. El proceso de insertar comentarios es, crear.[Libro de trabajo](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) objeto de clase para cargar un archivo existente y seleccionar la hoja de trabajo donde desea agregar el comentario. Obtenga todos sus comentarios usando getComments(). Añade el comentario usando[Agregar (const char16_t* nombre de celda)](https://reference.aspose.com/cells/cpp/aspose.cells/commentcollection/add/) método. Obtenga el índice de celda y use[Establecer nota](https://reference.aspose.com/cells/cpp/aspose.cells/comment/setnote/) para insertar comentarios. Además, API es capaz de eliminar todos los comentarios. Pocos de los métodos son[ClearComments()](https://reference.aspose.com/cells/cpp/aspose.cells/worksheet/clearcomments/) para Borrar todos los comentarios en la hoja de cálculo del diseñador. Además,***Eliminar en*** Método para eliminar el elemento en un índice específico o con un nombre especificado.

{{% blocks/products/pf/feature-page-code h3="C++ Código para agregar comentarios dentro del archivo Excel" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "add-comment-in-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}
