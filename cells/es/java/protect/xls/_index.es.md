---
title: Proteja y bloquee el documento XLS a través de Java 
weight: 5070
url: /es/java/protect/xls/ 
description: Java código de ejemplo para bloquear el archivo XLS mediante contraseña en Java entorno de tiempo de ejecución para aplicaciones JSP/JSF y aplicaciones de escritorio.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Cifrar archivos XLS a través de Java" h2="Proteja con contraseña las hojas de cálculo de Excel, incluido el formato XLS, utilizando la biblioteca .NET." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLS" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java/" installationsDocsLink="https://docs.aspose.com/cells/java/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java/" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Cómo proteger un archivo XLS usando Java" %}}

 Para proteger el archivo XLS, usaremos
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API, que es una plataforma de cifrado API for Java rica en funciones, potente y fácil de usar. Puedes descargar su última versión directamente desde
 [Experto](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) 
 e instálelo dentro de su proyecto basado en Maven agregando las siguientes configuraciones al pom.xml.

{{% blocks/products/pf/agp/code-block title="Aspose.Cells" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repositorio.aspose.com/repo/</url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Repositorio" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="Pasos para proteger archivos XLS a través de Java" %}}

{{% blocks/products/pf/agp/text %}}

 La protección de documentos con Aspose.Cells API se puede realizar con solo unas pocas líneas de código.

{{% /blocks/products/pf/agp/text %}}

1. Cargue el archivo XLS instanciando la clase Workbook1. Utilice el método protect(..) con ProtectionType y Password1. Guarde el archivo XLS protegido con el método save()
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos del sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java es compatible con todas las principales plataformas y sistemas operativos. Por favor, asegúrese de que tiene los siguientes requisitos previos.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows o un sistema operativo compatible con Java Runtime Environment para aplicaciones JSP/JSF y aplicaciones de escritorio.- Obtenga la última versión de Aspose.Cells for Java directamente desde [Experto](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells)  .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Dependencia" offSpacer="" %}}

```cs

// Abre el archivo XLS
Workbook wkb = new Workbook("sourceFile.xls");

// Proteger el libro de trabajo especificando el tipo de protección
wkb.protect(ProtectionType.ALL, "12345");

// Guarde el archivo XLS
wkb.save("lockedFile.xls");


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="Acerca de Aspose.Cells for Java API" %}}

 Aspose.Cells API se puede usar para crear, editar, convertir y representar formatos de Microsoft Excel en diferentes formatos. Además, se puede usar para gráficos completos, informes escalables y cálculos confiables dentro de las aplicaciones de software. Aspose.Cells es un API independiente y no requiere ningún software como Microsoft u OpenOffice.  



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="Aplicación gratuita para proteger XLS" sectionDescription="Consulte nuestras demostraciones en vivo para [cifrar archivos XLS](https://products.aspose.app/cells/protect/xls) con los siguientes beneficios." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No es necesario descargar ni configurar nada" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No es necesario escribir o compilar código" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Simplemente cargue el archivo XLS y presione el botón \"Desbloquear\"" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Descargue el archivo XLS resultante desde el enlace" >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}
Los archivos con extensión XLS representan el formato de archivo binario de Excel. Estos archivos pueden crearse con Microsoft Excel, así como con otros programas de hojas de cálculo similares, como OpenOffice Calc o Apple Numbers. El archivo guardado por Excel se conoce como Libro de trabajo, donde cada libro de trabajo puede tener una o más hojas de trabajo. Los datos se almacenan y muestran a los usuarios en formato de tabla en la hoja de trabajo y pueden abarcar valores numéricos, datos de texto, fórmulas, conexiones de datos externos, imágenes y gráficos. Las aplicaciones como Microsoft Excel le permiten exportar datos de libros de trabajo a varios formatos diferentes, incluidos PDF, CSV, XLSX, TXT, HTML, XPS y muchos otros. El formato de archivo XLS se reemplazó con un formato más abierto y estructurado, XLSX, con el lanzamiento de Microsoft Excel 2007. Las últimas versiones aún brindan soporte para crear y leer archivos XLS, aunque XLSX es la primera opción de uso ahora.

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Otros documentos de protección admitidos" subTitle="Usando Java, uno puede proteger otros archivos, incluidos." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/protect/ods/" name="SAO" description="Archivo de hoja de cálculo OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/protect/xlsb/" name="XLSB" description="Archivo de libro de Excel binario" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/protect/xlsm/" name="XLSM" description="Archivo de hoja de cálculo" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/protect/xlsx/" name="XLSX" description="Archivo de Excel OOXML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}