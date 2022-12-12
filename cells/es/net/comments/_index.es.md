---
title: Insertar comentarios en Excel a través de .NET

description: C# códigos fuente que explican cómo insertar comentarios en archivos de Microsoft Excel mediante la biblioteca .NET. 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Inserción de comentarios de Microsoft<sup>&reg;</sup> Excel a través de .NET" h2="Cree documentos de Excel e inserte comentarios mediante las API del lado del servidor en aplicaciones basadas en .NET." >}}
{{% blocks/products/pf/feature-page-summary %}}

Puede agregar comentarios a las celdas. Cuando una celda tiene un comentario, aparece un indicador en la esquina de la celda. Los comentarios aparecen cuando pasa el cursor sobre una celda. Estos comentarios se pueden usar para discusión, instrucciones especiales o marcado del contenido del documento. [.NET Biblioteca de Excel](/cells/net/) admite la inserción de comentarios en archivos de Excel. Para esto, el API proporciona un [Comentario](https://reference.aspose.com/cells/net/aspose.cells/comment) clase para el bloque de creación de comentarios.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Insertar comentarios en archivo de Excel" %}}

Insertar comentarios usando Excel API es simple. El proceso es, Crear [clase de libro de trabajo](https://reference.aspose.com/cells/net/aspose.cells/workbook) objeto y seleccione la primera hoja de trabajo o la hoja relevante proporcionando su índice. Inserte los datos de las celdas requeridas usando [Método PutValue](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index). Agregue un comentario a la hoja de trabajo usando [Colección de comentarios](https://reference.aspose.com/cells/net/aspose.cells/commentcollection)'s [Añadir método](https://reference.aspose.com/cells/net/aspose.cells.commentcollection/add/methods/1).

{{% blocks/products/pf/feature-page-code h3="C# Código para insertar comentario en Excel" %}}

{{< gist "aspose-cells-gists" "88c9872508ec3150c552eb5155edf06e" "InsertCommentIntoWorksheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
