---
title: Convierta ODS a XLAM a través de Java 
url: /es/java/conversion/ods-to-xlam/ 
description: Ejemplo de código de conversión Java para formato ODS a archivo XLAM. Los programadores pueden usar este código de ejemplo para exportar hojas de cálculo de Excel y OpenOffice a XLAM dentro de cualquier aplicación basada en Web o escritorio Java.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Convierta ODS a XLAM a través de Java" h2="Conversión de ODS a XLAM Java para convertir una o varias páginas a XLAM mediante la biblioteca Java local." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLAM" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="ODS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Cómo convertir ODS a XLAM usando Java" %}}

 Para renderizar ODS a XLAM, usaremos
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API, que es una plataforma de conversión API for Java rica en funciones, potente y fácil de usar. Puedes descargar su última versión directamente desde
 [Experto](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) 
 e instálelo dentro de su proyecto basado en Maven agregando las siguientes configuraciones al pom.xml.

{{% blocks/products/pf/agp/code-block title="Repositorio" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repositorio.aspose.com/repo/</url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Dependencia" offSpacer="true" %}}

```cs
<dependency>
<groupId>com.aspose</groupId>
<artifactId>aspose-cells</artifactId>
<version>version of aspose-cells API</version>
<classifier>jdk17</classifier>
</dependency>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Pasos para convertir ODS a XLAM a través de Java" %}}

{{% blocks/products/pf/agp/text %}}

 Los desarrolladores de Java pueden convertir fácilmente un archivo ODS a XLAM con solo unas pocas líneas de código.

{{% /blocks/products/pf/agp/text %}}

1. Cargue el archivo ODS con una instancia de la clase Workbook1. Llamar al método Workbook.save1. Pase la ruta de salida con la extensión XLAM y SaveFormat como parámetros1. Compruebe la ruta especificada para el archivo XLAM resultante

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos del sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Antes de ejecutar el código fuente de la conversión Java, asegúrese de cumplir los siguientes requisitos previos.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows o un sistema operativo compatible con Java Runtime Environment para aplicaciones JSP/JSF y aplicaciones de escritorio.- Obtenga la última versión de Aspose.Cells for Java directamente de Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Código fuente de conversión de ODS a XLAM Java" offSpacer="" %}}

```cs
// cargar el archivo ODS en una instancia de Workbook
Workbook book = new Workbook("template.ods");
// guardar SAO como XLAM
book.save("output.xlam", SaveFormat.AUTO);   
   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Demostraciones en vivo de conversión de ODS a XLAM" sectionDescription="[Convertir ODS a XLAM](https://products.aspose.app/cells/conversion/ods-to-xlam) ahora mismo visitando nuestro sitio web de demostraciones en vivo. La demostración en vivo tiene los siguientes beneficios" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No es necesario descargar Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No es necesario escribir ningún código." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Simplemente cargue su archivo ODS, se convertirá instantáneamente a XLAM." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Obtendrá el enlace de descarga." >}}

    {{% blocks/products/pf/agp/content h2="Java Biblioteca de manipulación de hojas de cálculo" %}}

 Excel API se puede usar para crear, editar, convertir y representar formatos de Microsoft Excel en diferentes formatos. Además, se puede usar para gráficos completos, informes escalables y cálculos confiables dentro de las aplicaciones de software. Aspose.Cells es un API independiente y no requiere ningún software como Microsoft u OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODS" readMoreLink="https://docs.fileformat.com/spreadsheet/ods/" >}}

Los archivos con extensión ODS representan el formato de documento de hoja de cálculo OpenDocument que el usuario puede editar. Los datos se almacenan dentro del archivo ODF en filas y columnas. Es un formato basado en XML y es uno de los varios subtipos de la familia Open Document Formats (ODF). El formato se especifica como parte de las especificaciones ODF 1.2 publicadas y mantenidas por OASIS. Varias aplicaciones en Windows, así como en otros sistemas operativos, pueden abrir archivos ODS para editarlos y manipularlos, incluidos Microsoft Excel, NeoOffice y LibreOffice. Los archivos ODS también se pueden convertir a otros formatos de hoja de cálculo, como XLS, XLSX y otros, mediante diferentes aplicaciones.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLAM" readMoreLink="https://docs.fileformat.com/spreadsheet/xlam/" >}}

XLAM es un archivo de complemento habilitado para macros de Excel que se utiliza para agregar nuevas funciones a Excel. Un complemento es un programa complementario que ejecuta código adicional y proporciona funcionalidad adicional para hojas de cálculo de Excel. Los archivos XLAM se almacenan con la extensión .xlam. Los archivos XLAM son archivos basados en XML similares a los formatos de archivo XLSM y XLSX y se guardan con compresión ZIP para reducir el tamaño total del archivo.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones admitidas" subTitle="También puede convertir ODS a muchos otros formatos de archivo, incluidos algunos que se enumeran a continuación." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-bmp/" name="ODS A BMP" description="Imagen de mapa de bits" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-csv/" name="ODS A CSV" description="Valores Separados por Comas" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-dif/" name="ODS A DIF" description="Formato de intercambio de datos" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-emf/" name="ODS A CEM" description="Formato de metarchivo mejorado" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-gif/" name="ODS A GIF" description="Formato de intercambio gráfico" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-html/" name="SAO A HTML" description="Lenguaje de marcado de hipertexto" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-jpeg/" name="ODS A JPEG" description="Imagen JPEG" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-mhtml/" name="ODS A MHTML" description="Formato de archivo de página web" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-pdf/" name="SAO A PDF" description="Formato de Documento Portable" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-png/" name="ODS A PNG" description="Gráficos de red portátiles" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-svg/" name="ODS A SVG" description="gráficas vectoriales escalables" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-tiff/" name="ODS A TIFF" description="Formato de imagen etiquetada" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-tsv/" name="ODS A TSV" description="Valores separados por tabuladores" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-txt/" name="ODS A TXT" description="Documento de texto" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-xlm/" name="ODS A XLM" description="Archivo de macros de Excel" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-xls/" name="ODS A XLS" description="Formato binario de Excel" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-xlsb/" name="ODS A XLSB" description="Archivo de libro de Excel binario" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-xlsx/" name="ODS A XLSX" description="Archivo de Excel OOXML" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-xlt/" name="ODS A XLT" description="Plantilla de Microsoft Excel" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-xltm/" name="SAO A XLTM" description="Plantilla de Excel habilitada para macros" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-xltx/" name="ODS A XLTX" description="Plantilla de Excel OpenXML de Office" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-xps/" name="ODS A XPS" description="Especificaciones de papel XML" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-json/" name="ODS A JSON" description="Notación de objetos de JavaScript" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}