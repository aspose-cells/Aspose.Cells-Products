---
title: Convierta XLSB a ODS a través de la aplicación C++ 
weight: 3450
url: /es/cpp/conversion/xlsb-to-ods/ 
description: Ejemplo de código de conversión C++ para documento XLSB a formato ODS. Los programadores pueden usar este código fuente para la conversión por lotes de XLSB a ODS dentro de cualquier aplicación C++.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Convierta XLSB a ODS a través de C++" h2="Conversión de XLSB a ODS de alto rendimiento utilizando la biblioteca C++ sin necesidad de instalar Microsoft Excel, OpenOffice o Adobe Acrobat." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODS" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSB" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Cómo convertir XLSB a ODS usando C++" %}}

 Para convertir XLSB a ODS, usaremos
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

{{% blocks/products/pf/agp/feature-section-col title="Pasos para convertir XLSB a ODS a través de C++" %}}

{{% blocks/products/pf/agp/text %}}

 Los desarrolladores de C++ pueden convertir fácilmente archivos XLSB a ODS con solo unas pocas líneas de código.

{{% /blocks/products/pf/agp/text %}}

1. Cargue el archivo XLSB usando Factory::CreateIWorkbook.1. Llame al método Guardar().1. Pase la ruta del archivo de salida con la extensión de archivo (ODS).1. El archivo ODS se guardará en la ruta especificada.1. Abra el archivo ODS en un programa compatible.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos del sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Antes de ejecutar el código de ejemplo de conversión C++, asegúrese de cumplir los siguientes requisitos previos.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows o un sistema operativo compatible con C++ Runtime Environment para Windows de 32 bits, Windows de 64 bits y Linux de 64 bits.- Aspose.Cells para C++ DLL a la que se hace referencia en su proyecto.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Código fuente de conversión de XLSB a ODS C++" offSpacer="" %}}

```cs
// Cargue el XLSB.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.xlsb");

// Guardar en formato ODS.
wkb->Save(u"convertedFile.ods", SaveFormat_Ods);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Demostraciones en vivo de conversión de XLSB a ODS" sectionDescription="[Convertir XLSB a ODS](https://products.aspose.app/cells/conversion/xlsb-to-ods) ahora mismo visitando nuestro sitio web de demostraciones en vivo. La demostración en vivo tiene los siguientes beneficios" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No es necesario descargar Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No es necesario escribir ningún código." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Simplemente cargue su archivo XLSB, se convertirá instantáneamente a ODS." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Obtendrá el enlace de descarga." >}}

    {{% blocks/products/pf/agp/content h2="C++ Biblioteca de manipulación de archivos de Excel" %}}

 Excel API se puede usar para crear, editar, convertir y representar formatos de Microsoft Excel en diferentes formatos. Además, se puede usar para gráficos completos, informes escalables y cálculos confiables dentro de las aplicaciones de software. Aspose.Cells es un API independiente y no requiere ningún software como Microsoft u OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSB" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsb/" >}}

El formato de archivo XLSB especifica el formato de archivo binario de Excel, que es una colección de registros y estructuras que especifican el contenido del libro de Excel. El contenido puede incluir tablas no estructuradas o semiestructuradas de números, texto o números y texto, fórmulas, conexiones de datos externos, gráficos e imágenes. A diferencia de XLSX (que se basa en el formato de archivo Open XML), XLSB representa un archivo de libro de Excel binario. Los archivos XLSB se pueden leer y escribir más rápido, lo que los hace útiles para trabajar con archivos grandes. XLSB rara vez se usa para almacenar libros de trabajo, ya que XLSX (y anteriormente XLS) son los formatos de archivo más comunes seleccionados por el usuario para guardar libros de trabajo. Se puede abrir con Microsoft Office 2007 y superior.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODS" readMoreLink="https://docs.fileformat.com/spreadsheet/ods/" >}}

Los archivos con extensión ODS representan el formato de documento de hoja de cálculo OpenDocument que el usuario puede editar. Los datos se almacenan dentro del archivo ODF en filas y columnas. Es un formato basado en XML y es uno de los varios subtipos de la familia Open Document Formats (ODF). El formato se especifica como parte de las especificaciones ODF 1.2 publicadas y mantenidas por OASIS. Varias aplicaciones en Windows, así como en otros sistemas operativos, pueden abrir archivos ODS para editarlos y manipularlos, incluidos Microsoft Excel, NeoOffice y LibreOffice. Los archivos ODS también se pueden convertir a otros formatos de hoja de cálculo, como XLS, XLSX y otros, mediante diferentes aplicaciones.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones admitidas" subTitle="También puede convertir XLSB a muchos otros formatos de archivo, incluidos algunos que se enumeran a continuación." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsb-to-bmp/" name="XLSB A BMP" description="Imagen de mapa de bits" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsb-to-csv/" name="XLSB A CSV" description="Valores Separados por Comas" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsb-to-dif/" name="XLSB A DIF" description="Formato de intercambio de datos" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsb-to-emf/" name="XLSB A CEM" description="Formato de metarchivo mejorado" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsb-to-gif/" name="XLSB A GIF" description="Formato de intercambio gráfico" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsb-to-html/" name="XLSB A HTML" description="Lenguaje de marcado de hipertexto" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsb-to-jpeg/" name="XLSB A JPEG" description="Imagen JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsb-to-mhtml/" name="XLSB A MHTML" description="Formato de archivo de página web" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsb-to-pdf/" name="XLSB A PDF" description="Formato de Documento Portable" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsb-to-png/" name="XLSB A PNG" description="Gráficos de red portátiles" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsb-to-svg/" name="XLSB A SVG" description="gráficas vectoriales escalables" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsb-to-tiff/" name="XLSB A TIFF" description="Formato de imagen etiquetada" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsb-to-tsv/" name="XLSB A TSV" description="Valores separados por tabuladores" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsb-to-xls/" name="XLSB A XLS" description="Formato binario de Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsb-to-xlsm/" name="XLSB A XLSM" description="Archivo de hoja de cálculo" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsb-to-xlsx/" name="XLSB A XLSX" description="Archivo de Excel OOXML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsb-to-xltm/" name="XLSB A XLTM" description="Plantilla de Excel habilitada para macros" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsb-to-xltx/" name="XLSB A XLTX" description="Plantilla de Excel OpenXML de Office" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsb-to-xps/" name="XLSB A XPS" description="Especificaciones de papel XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}