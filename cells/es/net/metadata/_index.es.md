---
title: Administrar metadatos de archivos de Excel via .NET C#
description: Vea, agregue, edite, elimine o extraiga metadatos de archivos de Excel con solo unas pocas líneas de código C#
keywords: [C# Aspose.Cells., c# view excel metadata., c# add excel metadata., c# insert excel metadata., c# edit excel metadata., c# remove excel metadata., c# extract excel metadata., c# modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Administrar Microsoft<sup>&reg;</sup> Metadatos del archivo Excel via .NET" h2="Vea, agregue, actualice, elimine o extraiga propiedades de archivos de Excel integradas y personalizadas utilizando las API .NET del lado del servidor." >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Excel API](/cells/es/net/) admite la gestión de propiedades definidas por el sistema (integradas), como título, nombre del autor, estadísticas del documento, etc., así como propiedades definidas por el usuario (personalizadas) en forma de par nombre-valor. Hay[clase de libro de trabajo](https://reference.aspose.com/cells/net/aspose.cells/workbook) para cargar los archivos, y[Colección de hojas de trabajo](https://reference.aspose.com/cells/net/aspose.cells/worksheetcollection) se ocupa de la recopilación de hojas de trabajo, así como[clase de hoja de trabajo](https://reference.aspose.com/cells/net/aspose.cells/worksheet) para representar una sola hoja de trabajo. Junto con estas clases, BuiltInDocumentProperties, CustomDocumentProperties simplifica el proceso de gestión de metadatos.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Administrar propiedades integradas" %}}

 Para administrar propiedades definidas por el sistema, API proporciona[Propiedades del documento incorporado](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/builtindocumentproperties) y los programadores pueden acceder fácilmente a una propiedad integrada y actualizar su valor. Dependiendo de los requisitos de la aplicación, los desarrolladores pueden usar el índice o el nombre de propiedad del[Colección de propiedades del documento](https://reference.aspose.com/cells/net/aspose.cells.properties/documentpropertycollection). 

{{% blocks/products/pf/feature-page-code h3="C# Código para administrar propiedades integradas" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "manage-system-defined-excel-file-metadata.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Administrar propiedades definidas personalizadas" %}}

 Para administrar propiedades definidas por el usuario, API proporciona[Propiedades de documento personalizado](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/customdocumentproperties) , y los desarrolladores pueden acceder fácilmente a propiedades ya agregadas, así como agregar nuevas propiedades. Para agregar propiedades personalizadas,[Agregar método](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection/methods/add/index) de[Colección de propiedades de documentos personalizados](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection) La clase agrega la propiedad y devuelve una referencia para la nueva propiedad como un[Propiedades.DocumentProperty](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty) objeto. La clase DocumentProperty se utiliza para recuperar el nombre, valor y tipo de la propiedad del documento como[PropiedadDocumento.Nombre](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/name), [Propiedad del documento.Valor](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/value),  [PropiedadDeDocumento.Tipo](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/type) que devuelve uno de los[Tipo de propiedad](https://reference.aspose.com/cells/net/aspose.cells.properties/propertytype) valores de enumeración.
 
{{% blocks/products/pf/feature-page-code h3="C# Código para agregar metadatos en un archivo de Excel" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "add-metadata-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="C# Código para eliminar propiedad personalizada en un archivo Excel" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "remove-custom-properties-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
