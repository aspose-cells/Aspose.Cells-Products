---
title: Administrar metadatos de archivos de Excel con Go a través de C++
description: Ver, agregar, editar, eliminar o extraer metadatos de archivos de Excel usando Go a través de la biblioteca C++
keywords: [Go via C++ Aspose.Cells., Go via C++ view excel metadata., Go via C++ add excel metadata., Go via C++ insert excel metadata., Go via C++ edit excel metadata., Go via C++ remove excel metadata., Go via C++ extract excel metadata., Go via C++ modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Administrar metadatos del documento de Excel Microsoft<sup>&reg;</sup> a través de Go mediante C++" h2="Ver, insertar, actualizar, eliminar o extraer propiedades de documentos de Excel personalizadas e integradas dentro de las aplicaciones C++." >}}
{{% blocks/products/pf/feature-page-summary %}}
 Metadatos en Excel: cómo ver, insertar y eliminar metadatos de archivos de Excel.[Ir a través de C++ Biblioteca de Excel](/cells/es/go-cpp/)Facilitates es fácil de usar, ya que admite propiedades integradas o definidas por el sistema, como nombre del autor, título, estadísticas del documento, etc., necesarias para comprobar cuándo se modificó o guardó el archivo por última vez, junto con propiedades personalizadas o definidas por el usuario en forma de pares nombre/valor. Para automatizar el proceso, la biblioteca permite la creación y el mantenimiento de grandes archivos Excel con metadatos.[Libro de trabajo](https://reference.aspose.com/cells/go-cpp/workbook/) La clase abre un libro de trabajo por ruta, por flujo y por un tipo de formato de archivo especial. Por lo tanto, carga el archivo con el método apropiado para su posterior procesamiento. A continuación se listan algunas de las posibilidades, y los desarrolladores pueden mejorar fácilmente su código según los requisitos de la aplicación.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Leer y actualizar propiedades integradas" %}}

 Para automatizar las propiedades integradas, API proporciona[GetBuiltInDocumentProperties()](https://reference.aspose.com/cells/go-cpp/workbook/getbuiltindocumentproperties/)Método que devuelve una colección DocumentProperties que representa todas las propiedades integradas del documento de la hoja de cálculo. Tras acceder a todas las propiedades integradas, acceda a las propiedades relevantes mediante métodos como GetTitle(), GetSubject(), etc. Para actualizar las propiedades, API proporciona métodos como SetTitle, SetSubject, SetAuthor, SetComments, etc. Consulte[colección de propiedades de documento incorporadas](https://reference.aspose.com/cells/go-cpp/workbook/getbuiltindocumentproperties/) para la función requerida.

{{% blocks/products/pf/feature-page-code h3="Vaya al código C++ para leer las propiedades definidas por el sistema" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "read-system-defined-properties.go" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Vaya al código C++ para actualizar las propiedades integradas" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "update-built-in-properties.go" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Ver y agregar propiedades definidas personalizadas" %}}

 Para gestionar propiedades personalizadas, se proporciona API[Libro de trabajo::ObtenerPropiedadesDeDocumentoPersonalizado](https://reference.aspose.com/cells/go-cpp/workbook/getcustomdocumentproperties/)Que devuelve toda la colección de propiedades personalizadas del documento de la hoja de cálculo. Al acceder a las propiedades personalizadas mediante este método, los desarrolladores pueden usar métodos relevantes para agregar propiedades como AddIDocumentProperty y AddLinkToContentProperty, y, de forma similar, usar UpdateLinkedPropertyValue y UpdateLinkedRange para actualizar el valor de la propiedad personalizada del documento que se vincula al contenido y al rango vinculado, respectivamente. Los desarrolladores pueden usar el método relevante desde[colección de propiedades de documentos personalizados](https://reference.aspose.com/cells/go-cpp/workbook/getcustomdocumentproperties/).

{{% blocks/products/pf/feature-page-code h3="Ingrese el código C++ para ver propiedades personalizadas" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "view-custom-properties.go" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="Vaya al código C++ para agregar metadatos en un archivo de Excel" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "add-custom-property.go" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< /blocks/products/pf/feature-page-wrap >}}