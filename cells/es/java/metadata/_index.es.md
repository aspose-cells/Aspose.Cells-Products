---
title: Administrar metadatos de archivos de Excel a través de Java

description: Vea, agregue, edite, elimine o extraiga metadatos de archivos de Excel con solo unas pocas líneas de código Java
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Administre metadatos de archivos de Microsoft<sup>&reg;</sup> Excel a través de Java" h2="Vea, agregue, actualice, elimine o extraiga propiedades de archivos de Excel integradas y personalizadas mediante las API Java del lado del servidor." >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java excel API](/cells/java/) admite la gestión de propiedades integradas (definidas por el sistema), como título, nombre del autor, estadísticas del documento, etc., así como propiedades personalizadas (definidas por el usuario) en forma de par de nombre/valor. Hay [clase de libro de trabajo](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) para cargar los archivos, y [Colección de hojas de trabajo](https://reference.aspose.com/cells/java/com.aspose.cells/WorksheetCollection) se ocupa de la colección de hojas de trabajo, así como [clase de hoja de trabajo](https://reference.aspose.com/cells/java/com.aspose.cells/Worksheet) para representar una sola hoja de trabajo. Para acceder a propiedades integradas y personalizadas, BuiltInDocumentProperties, CustomDocumentProperties simplifica el proceso para la gestión de metadatos. 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Administración de propiedades definidas por el sistema" %}}

Para administrar propiedades integradas, API proporciona [BuiltInDocumentProperties](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#BuiltInDocumentProperties)y los programadores pueden acceder fácilmente a una propiedad integrada y actualizar su valor. Según los requisitos de la aplicación, los desarrolladores pueden usar el índice o el nombre de propiedad del [DocumentPropertyCollection](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentPropertyCollection). 

{{% blocks/products/pf/feature-page-code h3="Java Código para gestionar propiedades definidas por el sistema" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "update-system-defined-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Agregar y eliminar metadatos definidos de forma personalizada" %}}

Para manejar propiedades personalizadas, API proporciona [Propiedades del documento personalizado](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#CustomDocumentProperties)y los desarrolladores pueden acceder fácilmente a las propiedades existentes, así como agregar nuevas propiedades usando [añadir método](https://reference.aspose.com/cells/java/com.aspose.cells/customdocumentpropertycollection#add(java.lang.String,%20boolean)) de [CustomDocumentPropertyCollection](https://reference.aspose.com/cells/java/com.aspose.cells/CustomDocumentPropertyCollection) class agrega la propiedad y devuelve una referencia para la nueva propiedad como una [Propiedades.PropiedadDocumento](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentProperty) objeto. La clase DocumentProperty se utiliza para recuperar el nombre, el valor y el tipo de la propiedad del documento como [DocumentoPropiedad.Nombre](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Name), [DocumentoPropiedad.Valor](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Value),  [DocumentProperty.Type](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Type) que devuelve uno de los [Tipo de propiedad](https://reference.aspose.com/cells/java/com.aspose.cells/PropertyType) valores de enumeración. 
 
{{% blocks/products/pf/feature-page-code h3="Java Código para agregar metadatos en un archivo de Excel" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "add-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="Java Código para eliminar propiedad personalizada en archivo de Excel" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "remove-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
