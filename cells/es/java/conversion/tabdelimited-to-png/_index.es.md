---
title: Convertir TABDELIMITED a PNG a través de Java 
url: /es/java/conversion/tabdelimited-to-png/ 
description: Ejemplo de código de conversión Java para formato TABDELIMITED a archivo PNG. Los programadores pueden usar este código de ejemplo para exportar hojas de cálculo de Excel y OpenOffice a PNG dentro de cualquier aplicación basada en Web o Desktop Java.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Convertir TABDELIMITED a PNG a través de Java" h2="Conversión de TABDELIMITED a PNG Java para convertir una o varias páginas a PNG mediante la biblioteca local Java." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PNG" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="TABDELIMITED" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Cómo convertir TABDELIMITED a PNG usando Java" %}}

 Para convertir TABDELIMITED en PNG, usaremos
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

{{% blocks/products/pf/agp/feature-section-col title="Pasos para convertir TABDELIMITED a PNG a través de Java" %}}

{{% blocks/products/pf/agp/text %}}

 Los desarrolladores de Java pueden convertir fácilmente archivos TABDELIMITED a PNG con solo unas pocas líneas de código.

{{% /blocks/products/pf/agp/text %}}

1. Cargue el archivo TABDELIMITED con una instancia de Workbook1. Seleccione predeterminado o cualquier hoja de trabajo de la colección1. Crear y establecer el objeto de ImageOrPrintOptions1. Cree SheetRender con objetos Worksheet e ImageOrPrintOptions1. Llame al método SheetRender.toImage para guardar el resultado en formato PNG

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos del sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Antes de ejecutar el código fuente de la conversión Java, asegúrese de cumplir los siguientes requisitos previos.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows o un sistema operativo compatible con Java Runtime Environment para aplicaciones JSP/JSF y aplicaciones de escritorio.- Obtenga la última versión de Aspose.Cells for Java directamente de Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="TABDELIMITED a PNG Java Código fuente de conversión" offSpacer="" %}}

```cs
// cargue el archivo TABDELIMITED para ser renderizado
Workbook workbook = new Workbook("sourceFile.tabdelimited");
// acceder a la hoja de trabajo predeterminada de la colección
Worksheet worksheet = workbook.getWorksheets().get(0);
// definir parámetros para la imagen resultante
ImageOrPrintOptions options = new ImageOrPrintOptions();
options.setOnePagePerSheet(true);
options.setImageType(ImageType.PNG);
// convertir hoja de trabajo a imagen en formato PNG
SheetRender renderer = new SheetRender(worksheet, options);
renderer.toImage(0, "output.png");   
   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="TABDELIMITED a PNG Conversión Demostraciones en vivo" sectionDescription="[Convertir TABDELIMITED a PNG](https://products.aspose.app/cells/conversion/tabdelimited-to-png) ahora mismo visitando nuestro sitio web de demostraciones en vivo. La demostración en vivo tiene los siguientes beneficios" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No es necesario descargar Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No es necesario escribir ningún código." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Simplemente cargue su archivo TABDELIMITED, se convertirá instantáneamente a PNG." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Obtendrá el enlace de descarga." >}}

    {{% blocks/products/pf/agp/content h2="Java Biblioteca de manipulación de hojas de cálculo" %}}

 Excel API se puede usar para crear, editar, convertir y representar formatos de Microsoft Excel en diferentes formatos. Además, se puede usar para gráficos completos, informes escalables y cálculos confiables dentro de las aplicaciones de software. Aspose.Cells es un API independiente y no requiere ningún software como Microsoft u OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="TABDELIMITED" readMoreLink="/{{tabdelimited_url}}" >}}

{{tabdelimited}}

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PNG" readMoreLink="https://docs.fileformat.com/image/png/" >}}

PNG, Portable Network Graphics, se refiere a un tipo de formato de archivo de imagen de trama que utiliza compresión sin pérdidas. Este formato de archivo se creó como reemplazo del formato de intercambio de gráficos (GIF) y no tiene limitaciones de derechos de autor. Sin embargo, el formato de archivo PNG no admite animaciones. El formato de archivo PNG admite la compresión de imágenes sin pérdida que lo hace popular entre sus usuarios. Con el paso del tiempo, PNG se ha convertido en uno de los formatos de archivo de imagen más utilizados. Casi todos los sistemas operativos tienen soporte para abrir archivos PNG. Por ejemplo, el visor de Microsoft Windows tiene la capacidad de abrir archivos PNG ya que el sistema operativo tiene soporte disponible de forma predeterminada como parte de la instalación.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}