---
title: Convierta MHTML a XML a través de la aplicación C++ 
url: /es/cpp/conversion/mhtml-to-xml/ 
description: Ejemplo de código de conversión C++ para documento MHTML a formato XML. Los programadores pueden usar este código fuente para la conversión por lotes de MHTML a XML dentro de cualquier aplicación C++.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Convierta MHTML a XML a través de C++" h2="Conversión de MHTML a XML de alto rendimiento utilizando la biblioteca C++ sin necesidad de instalar Microsoft Excel, OpenOffice o Adobe Acrobat." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="XML" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="MHTML" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Cómo convertir MHTML a XML usando C++" %}}

 Para convertir MHTML a XML, usaremos
 [Aspose.Cells para C++](https://products.aspose.com/cells/cpp) 
 API, que es una manipulación y conversión de documentos rica en funciones, potente y fácil de usar API para la plataforma C++. Puede descargar su última versión directamente, simplemente abra
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 administrador de paquetes, busque
 Aspose.Cells.cpp 
 e instalar También puede usar el siguiente comando desde la Consola del administrador de paquetes.

{{% blocks/products/pf/agp/code-block title="Dominio" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Pasos para convertir MHTML a XML a través de C++" %}}

{{% blocks/products/pf/agp/text %}}

 Los desarrolladores de C++ pueden convertir fácilmente un archivo MHTML a XML con solo unas pocas líneas de código.

{{% /blocks/products/pf/agp/text %}}

1. Cargue el archivo MHTML usando Factory::CreateIWorkbook.1. Llame al método Guardar().1. Pase la ruta del archivo de salida con la extensión de archivo (XML).1. El archivo XML se guardará en la ruta especificada.1. Abra el archivo XML en un programa compatible.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos del sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Antes de ejecutar el código de ejemplo de conversión C++, asegúrese de cumplir los siguientes requisitos previos.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows o un sistema operativo compatible con C++ Runtime Environment para Windows de 32 bits, Windows de 64 bits y Linux de 64 bits.- Aspose.Cells para C++ DLL a la que se hace referencia en su proyecto.
- Microsoft Windows o un sistema operativo compatible con C++ Runtime Environment para Windows de 32 bits, Windows de 64 bits y Linux de 64 bits.- Aspose.Cells para C++ DLL a la que se hace referencia en su proyecto.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Código fuente de conversión de MHTML a XML C++" offSpacer="" %}}

```cs
// Cargue el MHTML.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.mhtml");

// Guardar en formato XML.
wkb->Save(u"convertedFile.xml", SaveFormat_Xml);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Demostraciones en vivo de conversión de MHTML a XML" sectionDescription="[Convertir MHTML a XML](https://products.aspose.app/cells/conversion/mhtml-to-xml) ahora mismo visitando nuestro sitio web de demostraciones en vivo. La demostración en vivo tiene los siguientes beneficios" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No es necesario descargar Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No es necesario escribir ningún código." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Simplemente cargue su archivo MHTML, se convertirá instantáneamente a XML." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Obtendrá el enlace de descarga." >}}

    {{% blocks/products/pf/agp/content h2="C++ Biblioteca de manipulación de archivos de Excel" %}}

 Excel API se puede usar para crear, editar, convertir y representar formatos de Microsoft Excel en diferentes formatos. Además, se puede usar para gráficos completos, informes escalables y cálculos confiables dentro de las aplicaciones de software. Aspose.Cells es un API independiente y no requiere ningún software como Microsoft u OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="MHTML" readMoreLink="https://docs.fileformat.com/web/mhtml/" >}}

Los archivos con extensión MHTML representan un formato de archivo de página web que puede ser creado por varias aplicaciones diferentes. El formato se conoce como formato de archivo porque guarda el código HTML web y los recursos asociados en un solo archivo. Estos recursos incluyen todo lo relacionado con la página web, como imágenes, applets, animaciones, archivos de audio, etc. Los archivos MHTML se pueden abrir en una variedad de aplicaciones como Internet Explorer y Microsoft Word. Microsoft Windows utiliza el formato de archivo MHTML para registrar escenarios de problemas observados durante el uso de cualquier aplicación en Windows que plantee problemas. El formato de archivo MHTML codifica el contenido de la página de forma similar a las especificaciones definidas en message/rfc822, que son especificaciones relacionadas con el correo electrónico de texto sin formato. Las especificaciones reales del formato se detallan en RFC 2557.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XML" readMoreLink="https://docs.fileformat.com/web/xml/" >}}

XML significa Lenguaje de marcado extensible que es similar a HTML pero diferente en el uso de etiquetas para definir objetos. La idea detrás de la creación del formato de archivo XML era almacenar y transportar datos sin depender de herramientas de software o hardware. Su popularidad se debe a que es legible tanto por humanos como por máquinas. Esto le permite crear protocolos de datos comunes en forma de objetos para ser almacenados y compartidos a través de una red como la World Wide Web (WWW). La "X" en XML es extensible, lo que implica que el lenguaje se puede extender a cualquier número de símbolos según los requisitos del usuario. Es por estas características que muchos formatos de archivo estándar lo utilizan, como Microsoft Open XML, LibreOffice OpenDocument, XHTML y SVG.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones admitidas" subTitle="También puede convertir MHTML a muchos otros formatos de archivo, incluidos algunos que se enumeran a continuación." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-bmp/" name="MHTML A BMP" description="Imagen de mapa de bits" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-csv/" name="MHTML A CSV" description="Valores Separados por Comas" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-dif/" name="MHTML A DIF" description="Formato de intercambio de datos" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-emf/" name="MHTML A CEM" description="Formato de metarchivo mejorado" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-gif/" name="MHTML A GIF" description="Formato de intercambio gráfico" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-html/" name="MHTML A HTML" description="Lenguaje de marcado de hipertexto" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-jpeg/" name="MHTML A JPEG" description="Imagen JPEG" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-ods/" name="MHTML A ODS" description="Archivo de hoja de cálculo OpenDocument" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-pdf/" name="MHTML A PDF" description="Formato de Documento Portable" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-png/" name="MHTML A PNG" description="Gráficos de red portátiles" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-svg/" name="MHTML A SVG" description="gráficas vectoriales escalables" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-tiff/" name="MHTML A TIFF" description="Formato de imagen etiquetada" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-tsv/" name="MHTML A TSV" description="Valores separados por tabuladores" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-xls/" name="MHTML A XLS" description="Formato binario de Excel" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-xlsb/" name="MHTML A XLSB" description="Archivo de libro de Excel binario" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-xlsm/" name="MHTML A XLSM" description="Archivo de hoja de cálculo" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-xlsx/" name="MHTML A XLSX" description="Archivo de Excel OOXML" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-xltm/" name="MHTML A XLTM" description="Plantilla de Excel habilitada para macros" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-xltx/" name="MHTML A XLTX" description="Plantilla de Excel OpenXML de Office" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-xps/" name="MHTML A XPS" description="Especificaciones de papel XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}