---
title: Convierta XLS a JPG a través de la aplicación C++ 
url: /es/cpp/conversion/xls-to-jpg/ 
description: Ejemplo de código de conversión C++ para documento XLS a formato JPG. Los programadores pueden usar este código fuente para la conversión por lotes de XLS a JPG dentro de cualquier aplicación C++.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Convierte XLS a JPG a través de C++" h2="Conversión de XLS a JPG de alto rendimiento utilizando la biblioteca C++ sin necesidad de instalar Microsoft Excel, OpenOffice o Adobe Acrobat." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="JPG" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Cómo convertir XLS a JPG usando C++" %}}

 Para convertir XLS a JPG, usaremos
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

{{% blocks/products/pf/agp/feature-section-col title="Pasos para convertir XLS a JPG a través de C++" %}}

{{% blocks/products/pf/agp/text %}}

 Los desarrolladores de C++ pueden convertir fácilmente un archivo XLS a JPG con solo unas pocas líneas de código.

{{% /blocks/products/pf/agp/text %}}

1. Cargue el archivo XLS usando Factory::CreateIWorkbook.1. Llame al método Guardar().1. Pase la ruta del archivo de salida con la extensión de archivo (JPG).1. El archivo JPG se guardará en la ruta especificada.1. Abra el archivo JPG en un programa compatible.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos del sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Antes de ejecutar el código de ejemplo de conversión C++, asegúrese de cumplir los siguientes requisitos previos.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows o un sistema operativo compatible con C++ Runtime Environment para Windows de 32 bits, Windows de 64 bits y Linux de 64 bits.- Aspose.Cells para C++ DLL a la que se hace referencia en su proyecto.
- Microsoft Windows o un sistema operativo compatible con C++ Runtime Environment para Windows de 32 bits, Windows de 64 bits y Linux de 64 bits.- Aspose.Cells para C++ DLL a la que se hace referencia en su proyecto.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Código fuente de conversión de XLS a JPG C++" offSpacer="" %}}

```cs
// Cargue el XLS.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.xls");

// Guardar en formato JPG.
wkb->Save(u"convertedFile.jpg", SaveFormat_Jpg);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Demostraciones en vivo de conversión de XLS a JPG" sectionDescription="[Convertir XLS a JPG](https://products.aspose.app/cells/conversion/xls-to-jpg) ahora mismo visitando nuestro sitio web de demostraciones en vivo. La demostración en vivo tiene los siguientes beneficios" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No es necesario descargar Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No es necesario escribir ningún código." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Simplemente cargue su archivo XLS, se convertirá instantáneamente a JPG." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Obtendrá el enlace de descarga." >}}

    {{% blocks/products/pf/agp/content h2="C++ Biblioteca de manipulación de archivos de Excel" %}}

 Excel API se puede usar para crear, editar, convertir y representar formatos de Microsoft Excel en diferentes formatos. Además, se puede usar para gráficos completos, informes escalables y cálculos confiables dentro de las aplicaciones de software. Aspose.Cells es un API independiente y no requiere ningún software como Microsoft u OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}

Los archivos con extensión XLS representan el formato de archivo binario de Excel. Estos archivos pueden crearse con Microsoft Excel, así como con otros programas de hojas de cálculo similares, como OpenOffice Calc o Apple Numbers. El archivo guardado por Excel se conoce como Libro de trabajo, donde cada libro de trabajo puede tener una o más hojas de trabajo. Los datos se almacenan y muestran a los usuarios en formato de tabla en la hoja de trabajo y pueden abarcar valores numéricos, datos de texto, fórmulas, conexiones de datos externos, imágenes y gráficos. Las aplicaciones como Microsoft Excel le permiten exportar datos de libros de trabajo a varios formatos diferentes, incluidos PDF, CSV, XLSX, TXT, HTML, XPS y muchos otros. El formato de archivo XLS se reemplazó con un formato más abierto y estructurado, XLSX, con el lanzamiento de Microsoft Excel 2007. Las últimas versiones aún brindan soporte para crear y leer archivos XLS, aunque XLSX es la primera opción de uso ahora.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="JPG" readMoreLink="https://docs.fileformat.com/image/jpeg/" >}}

Un JPEG es un tipo de formato de imagen que se guarda mediante el método de compresión con pérdida. La imagen de salida, como resultado de la compresión, es un equilibrio entre el tamaño de almacenamiento y la calidad de la imagen. Los usuarios pueden ajustar el nivel de compresión para lograr el nivel de calidad deseado y al mismo tiempo reducir el tamaño de almacenamiento. La calidad de la imagen se ve afectada de manera insignificante si se aplica una compresión de 10:1 a la imagen. Cuanto mayor sea el valor de compresión, mayor será la degradación de la calidad de la imagen.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones admitidas" subTitle="También puede convertir XLS a muchos otros formatos de archivo, incluidos algunos que se enumeran a continuación." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-bmp/" name="XLS A BMP" description="Imagen de mapa de bits" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-csv/" name="XLS A CSV" description="Valores Separados por Comas" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-dif/" name="XLS A DIF" description="Formato de intercambio de datos" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-emf/" name="XLS A CEM" description="Formato de metarchivo mejorado" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-gif/" name="XLS A GIF" description="Formato de intercambio gráfico" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-html/" name="XLS A HTML" description="Lenguaje de marcado de hipertexto" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-jpeg/" name="XLS A JPEG" description="Imagen JPEG" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-mhtml/" name="XLS A MHTML" description="Formato de archivo de página web" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-ods/" name="XLS A ODS" description="Archivo de hoja de cálculo OpenDocument" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-pdf/" name="XLS A PDF" description="Formato de Documento Portable" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-png/" name="XLS A PNG" description="Gráficos de red portátiles" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-svg/" name="XLS A SVG" description="gráficas vectoriales escalables" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-tiff/" name="XLS A TIFF" description="Formato de imagen etiquetada" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-tsv/" name="XLS A TSV" description="Valores separados por tabuladores" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-xlsb/" name="XLS A XLSB" description="Archivo de libro de Excel binario" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-xlsm/" name="XLS A XLSM" description="Archivo de hoja de cálculo" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-xlsx/" name="XLS A XLSX" description="Archivo de Excel OOXML" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-xltm/" name="XLS A XLTM" description="Plantilla de Excel habilitada para macros" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-xltx/" name="XLS A XLTX" description="Plantilla de Excel OpenXML de Office" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-xps/" name="XLS A XPS" description="Especificaciones de papel XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}