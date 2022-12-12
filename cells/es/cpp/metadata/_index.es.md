---
title: Administrar metadatos de archivos de Excel a través de C++

description: Ver, agregar, editar, eliminar o extraer metadatos de archivos de Excel usando la biblioteca C++
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Administre metadatos de documentos de Microsoft<sup>&reg;</sup> Excel a través de C++" h2="Vea, inserte, actualice, elimine o extraiga propiedades de documentos de Excel integradas y personalizadas dentro de C++ aplicaciones." >}}
{{% blocks/products/pf/feature-page-summary %}}
Metadatos en Excel: cómo ver, insertar y eliminar metadatos de archivos de Excel. [C++ Biblioteca de Excel](/cells/cpp/) faclitates es fácil al admitir las propiedades integradas/definidas por el sistema, como el nombre del autor, el título, las estadísticas del documento, etc. pares nombre/valor. Para automatizar el proceso, la biblioteca admite la creación y el mantenimiento de grandes archivos de metadatos de Excel. [Método CreateIWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8) de [Clase de fábrica](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory) Abra un libro de trabajo por ruta, por secuencia y por tipo de formato de archivo especial. Así que cargue el archivo con el método apropiado para su posterior procesamiento. Algunas de las posibilidades enumeradas a continuación y los desarrolladores pueden mejorar fácilmente su código de acuerdo con los requisitos de la aplicación. 
 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Leer y actualizar propiedades integradas" %}}

Para automatizar las propiedades integradas, API proporciona [GetIBuiltInDocumentProperties()](https://reference.aspose.com/cells/cpp/class/aspose.cells.metadata.i_workbook_metadata) método que devuelve una colección DocumentProperties que representa todas las propiedades de documento integradas de la hoja de cálculo. Después de acceder a todas las propiedades integradas, acceda a las propiedades relevantes mediante el método correspondiente, como GetTitle(), GetSubject(), etc. Para actualizar las propiedades, API proporciona métodos como SetTitle, SetSubject, SetAuthor, SetComments, etc. [colección de propiedades de documentos integrados](https://reference.aspose.com/cells/cpp/class/aspose.cells.properties.i_built_in_document_property_collection) para la función requerida.

{{% blocks/products/pf/feature-page-code h3="C++ Código para leer propiedades definidas por el sistema" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "read-system-defined-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C++ Código para actualizar las propiedades integradas" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "update-built-in-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Ver y agregar propiedades definidas personalizadas" %}}

Para manejar propiedades personalizadas, API proporciona [IWorkbookMetadata::GetICustomDocumentProperties](https://reference.aspose.com/cells/cpp/class/aspose.cells.metadata.i_workbook_metadata#a69f0226813ce18c03ebc13b8ca691e79) que devuelve toda la colección de propiedades de documentos personalizados de la hoja de cálculo. En primer lugar, al acceder a las propiedades personalizadas a través de este método, los desarrolladores pueden usar métodos relevantes para agregar propiedades como AddIDocumentProperty, AddLinkToContentProperty y, de manera similar, usar UpdateLinkedPropertyValue, UpdateLinkedRange para actualizar el valor de la propiedad del documento personalizado que se vincula al contenido y al rango vinculado, respectivamente. Los desarrolladores pueden usar el método relevante de [colección de propiedades de documentos personalizados](https://reference.aspose.com/cells/cpp/class/aspose.cells.properties.i_custom_document_property_collection).

{{% blocks/products/pf/feature-page-code h3="C++ Código para ver propiedades personalizadas" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "view-custom-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C++ Código para agregar metadatos en un archivo de Excel" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "add-custom-property.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
