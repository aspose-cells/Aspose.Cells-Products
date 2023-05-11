---
title: Administrar metadatos de archivos de Excel via .NET C#
description: Vea, agregue, edite, elimine o extraiga metadatos de archivos de Excel con solo unas pocas líneas de código C#
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Administrar Microsoft<sup>&reg;</sup> Metadatos de archivos de Excel via .NET" h2="Vea, agregue, actualice, elimine o extraiga propiedades de archivos de Excel integradas y personalizadas utilizando las API .NET del lado del servidor." >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET excel API](/cells/es/net/) admite la gestión de propiedades definidas por el sistema (incorporadas), como el título, el nombre del autor, las estadísticas del documento, etc., así como las propiedades definidas por el usuario (personalizadas) en forma de par nombre-valor. Hay[clase de libro de trabajo](https://reference.aspose.com/cells/net/aspose.cells/workbook) para cargar los archivos, y[Colección de hojas de trabajo](https://reference.aspose.com/cells/net/aspose.cells/worksheetcollection) se ocupa de la colección de hojas de trabajo, así como[clase de hoja de trabajo](https://reference.aspose.com/cells/net/aspose.cells/worksheet) para representar una sola hoja de trabajo. Junto con estas clases, BuiltInDocumentProperties, CustomDocumentProperties simplifica el proceso para la administración de metadatos.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Gestión de propiedades integradas" %}}

 Para administrar propiedades definidas por el sistema, API proporciona[BuiltInDocumentProperties](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/builtindocumentproperties) y los programadores pueden acceder fácilmente a una propiedad integrada y actualizar su valor. Según los requisitos de la aplicación, los desarrolladores pueden usar el índice o el nombre de propiedad del[DocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/documentpropertycollection). 

{{% blocks/products/pf/feature-page-code h3="C# Código para administrar las propiedades integradas" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "manage-system-defined-excel-file-metadata.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Gestión de propiedades definidas personalizadas" %}}

 Para administrar propiedades definidas por el usuario, API proporciona[Propiedades del documento personalizado](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/customdocumentproperties) y los desarrolladores pueden acceder fácilmente a las propiedades ya agregadas, así como agregar nuevas propiedades. Para agregar propiedades personalizadas,[Añadir método](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection/methods/add/index) de[CustomDocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection) class agrega la propiedad y devuelve una referencia para la nueva propiedad como una[Propiedades.PropiedadDocumento](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty) objeto. La clase DocumentProperty se utiliza para recuperar el nombre, el valor y el tipo de la propiedad del documento como[DocumentoPropiedad.Nombre](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/name), [DocumentoPropiedad.Valor](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/value),  [DocumentProperty.Type](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/type) que devuelve uno de los[Tipo de propiedad](https://reference.aspose.com/cells/net/aspose.cells.properties/propertytype) valores de enumeración.
 
{{% blocks/products/pf/feature-page-code h3="C# Código para agregar metadatos en un archivo de Excel" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "add-metadata-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="C# Código para eliminar propiedad personalizada en archivo de Excel" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "remove-custom-properties-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
