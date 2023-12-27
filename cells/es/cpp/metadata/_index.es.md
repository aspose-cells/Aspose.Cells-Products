---
title: Administre metadatos de archivos de Excel a través de C++
description: Ver, agregar, editar, eliminar o extraer metadatos de archivos de Excel usando la biblioteca C++
keywords: [C++ Aspose.Cells., C++ view excel metadata., C++ add excel metadata., C++ insert excel metadata., C++ edit excel metadata., C++ remove excel metadata., C++ extract excel metadata., C++ modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Administre Microsoft<sup>&reg;</sup> Metadatos de documentos de Excel a través de C++" h2="Vea, inserte, actualice, elimine o extraiga propiedades de documentos de Excel personalizadas e integradas dentro de las aplicaciones C++." >}}
{{% blocks/products/pf/feature-page-summary %}}
 Metadatos en Excel: cómo ver, insertar y eliminar metadatos de archivos de Excel.[C++ Biblioteca de Excel](/cells/es/cpp/) facilita de manera fácil al admitir las propiedades integradas/definidas por el sistema, como el nombre del autor, el título, las estadísticas del documento, etc., necesarias en algún momento, como verificar cuándo se modificó o guardó por última vez el archivo junto con las propiedades personalizadas/definidas por el usuario en forma de pares nombre/valor. Para automatizar el proceso, la biblioteca admite la creación y el mantenimiento de grandes archivos de metadatos de Excel.[Libro de trabajo](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/)clase Abre un libro de trabajo por ruta, por secuencia y por FileFormatType especial. Así que cargue el archivo con el método apropiado para su posterior procesamiento. Pocas de las posibilidades que se enumeran a continuación y los desarrolladores pueden mejorar fácilmente su código según los requisitos de la aplicación.
 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Leer y actualizar propiedades integradas" %}}

 Para automatizar las propiedades integradas, API proporciona[GetBuiltInDocumentProperties()](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/getbuiltindocumentproperties/) Método que devuelve una colección DocumentProperties que representa todas las propiedades del documento integradas de la hoja de cálculo. Después de acceder a todas las propiedades integradas, acceda a las propiedades relevantes utilizando métodos relevantes como GetTitle(), GetSubject(), etc. Para actualizar las propiedades, API proporciona métodos como SetTitle, SetSubject, SetAuthor, SetComments, etc.[colección de propiedades de documentos incorporada](https://reference.aspose.com/cells/cpp/aspose.cells.properties/builtindocumentpropertycollection/) para la función requerida.

{{% blocks/products/pf/feature-page-code h3="C++ Código para leer propiedades definidas por el sistema" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "read-system-defined-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C++ Código para actualizar las propiedades integradas" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "update-built-in-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Ver y agregar propiedades definidas personalizadas" %}}

Para manejar propiedades personalizadas, API proporciona[Libro de trabajo::GetCustomDocumentProperties](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/getcustomdocumentproperties/) que devuelve toda la colección de propiedades de documentos personalizados de la hoja de cálculo. En primer lugar, al acceder a las propiedades personalizadas a través de este método, los desarrolladores pueden usar métodos relevantes para agregar propiedades como AddIDocumentProperty, AddLinkToContentProperty y, de manera similar, usar UpdateLinkedPropertyValue, UpdateLinkedRange para actualizar el valor de la propiedad del documento personalizado que vincula al contenido y al rango vinculado respectivamente. Los desarrolladores pueden utilizar métodos relevantes de[colección de propiedades de documentos personalizados](https://reference.aspose.com/cells/cpp/aspose.cells.properties/customdocumentpropertycollection/).

{{% blocks/products/pf/feature-page-code h3="C++ Código para ver propiedades personalizadas" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "view-custom-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C++ Código para agregar metadatos en un archivo de Excel" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "add-custom-property.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
