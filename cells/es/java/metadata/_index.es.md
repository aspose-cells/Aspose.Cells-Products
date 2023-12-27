---
title: Administrar metadatos de archivos de Excel via Java
description: Vea, agregue, edite, elimine o extraiga metadatos de archivos de Excel con solo unas pocas líneas de código Java
keywords: [Java Aspose.Cells., Java view excel metadata., Java add excel metadata., Java insert excel metadata., Java edit excel metadata., Java remove excel metadata., Java extract excel metadata., Java modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Administrar Microsoft<sup>&reg;</sup> Metadatos del archivo Excel via Java" h2="Vea, agregue, actualice, elimine o extraiga propiedades de archivos de Excel personalizadas e integradas utilizando las API Java del lado del servidor." >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Excel API](/cells/es/java/) admite la gestión de propiedades integradas (definidas por el sistema), como título, nombre del autor, estadísticas del documento, etc., así como propiedades personalizadas (definidas por el usuario) en forma de par nombre/valor. Hay[clase de libro de trabajo](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) para cargar los archivos, y[Colección de hojas de trabajo](https://reference.aspose.com/cells/java/com.aspose.cells/WorksheetCollection) se ocupa de la recopilación de hojas de trabajo, así como[clase de hoja de trabajo](https://reference.aspose.com/cells/java/com.aspose.cells/Worksheet) para representar una sola hoja de trabajo. Para acceder a propiedades integradas y personalizadas, BuiltInDocumentProperties, CustomDocumentProperties simplifica el proceso de gestión de metadatos.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Gestión de propiedades definidas por el sistema" %}}

 Para gestionar propiedades integradas, API proporciona[Propiedades del documento incorporado](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#BuiltInDocumentProperties) y los programadores pueden acceder fácilmente a una propiedad integrada y actualizar su valor. Dependiendo de los requisitos de la aplicación, los desarrolladores pueden usar el índice o el nombre de propiedad del[Colección de propiedades del documento](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentPropertyCollection). 

{{% blocks/products/pf/feature-page-code h3="Java Código para administrar propiedades definidas por el sistema" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "update-system-defined-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Agregar y eliminar metadatos definidos personalizados" %}}

Para manejar propiedades personalizadas, API proporciona[Propiedades de documento personalizado](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#CustomDocumentProperties) , y los desarrolladores pueden acceder fácilmente a las propiedades existentes, así como agregar nuevas propiedades usando[agregar método](https://reference.aspose.com/cells/java/com.aspose.cells/customdocumentpropertycollection#add(java.lang.String,%20boolean) ) de[Colección de propiedades de documentos personalizados](https://reference.aspose.com/cells/java/com.aspose.cells/CustomDocumentPropertyCollection) La clase agrega la propiedad y devuelve una referencia para la nueva propiedad como un[Propiedades.DocumentProperty](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentProperty) objeto. La clase DocumentProperty se utiliza para recuperar el nombre, valor y tipo de la propiedad del documento como[PropiedadDocumento.Nombre](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Name), [Propiedad del documento.Valor](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Value),  [PropiedadDeDocumento.Tipo](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Type) que devuelve uno de los[Tipo de propiedad](https://reference.aspose.com/cells/java/com.aspose.cells/PropertyType) valores de enumeración.
 
{{% blocks/products/pf/feature-page-code h3="Java Código para agregar metadatos en un archivo de Excel" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "add-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="Java Código para eliminar propiedad personalizada en un archivo de Excel" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "remove-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
