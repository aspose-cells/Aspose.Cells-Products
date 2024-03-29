---
title:  Proteger y bloquear ODS documento via Java
weight: 6360
description: Código de muestra Java para bloquear el archivo ODS usando una contraseña en el entorno de ejecución Java para aplicaciones JSP/JSF y aplicaciones de escritorio.
keywords: [Java Aspose.Cells., Java Lock ODS files., Java How to Protect and lock ODS document., Java Protect ODS files., Encrypt ODS Files using Java]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Cifrar ODS archivos via Java" h2="Proteja las hojas de cálculo de Excel con contraseña, incluido el formato ODS, utilizando la biblioteca .NET." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODS" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="ODS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java/" installationsDocsLink="https://docs.aspose.com/cells/java/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java/" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Cómo proteger el archivo ODS usando Java" %}}

 Para proteger el archivo ODS, usaremos
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API, que es una plataforma de cifrado API for Java rica en funciones, potente y fácil de usar. Puede descargar su última versión directamente desde
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) 
 e instálelo dentro de su proyecto basado en Maven agregando las siguientes configuraciones a pom.xml.

{{% blocks/products/pf/agp/code-block title="Aspose.Cells" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
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

{{% blocks/products/pf/agp/feature-section-col title="Pasos para proteger archivos ODS via Java" %}}

{{% blocks/products/pf/agp/text %}}

 La protección de documentos mediante las API Aspose.Cells se puede realizar con solo unas pocas líneas de código.

{{% /blocks/products/pf/agp/text %}}

1.  Cargue el archivo ODS creando una instancia de la clase Workbook
1.  Utilice el método de protección (..) con Tipo de protección y Contraseña
1.  Guarde el archivo ODS protegido mediante el método save()

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos del sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java es compatible con todas las principales plataformas y sistemas operativos. Asegúrese de tener los siguientes requisitos previos.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows o un sistema operativo compatible con Java Runtime Environment para aplicaciones JSP/JSF y aplicaciones de escritorio.
-  Obtenga la última versión de Aspose.Cells for Java directamente desde
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells)  .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Dependencia" offSpacer="" %}}

```cs

// Open the ODS file
Workbook wkb = new Workbook("sourceFile.ods");

// Protect workbook by specifying protection type
wkb.protect(ProtectionType.ALL, "12345");

// Save the ODS file
wkb.save("lockedFile.ods");

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="Acerca de Aspose.Cells for Java API" %}}

 Aspose.Cells API se puede utilizar para crear, editar, convertir y renderizar Microsoft formatos de Excel a diferentes formatos. Además, se puede utilizar para gráficos completos, informes escalables y cálculos confiables dentro de aplicaciones de software. Aspose.Cells es un API independiente y no requiere ningún software como Microsoft u OpenOffice.



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="Aplicación gratuita para proteger ODS" sectionDescription=" Consulte nuestras demostraciones en vivo para[cifrar archivos ODS](https://products.aspose.app/cells/protect/ods) con los siguientes beneficios." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No es necesario descargar ni configurar nada" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No es necesario escribir ni compilar código" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Simplemente cargue el archivo ODS y presione el botón \"Desbloquear\"" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Descargue el archivo ODS resultante desde el enlace" >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODS" readMoreLink="https://docs.fileformat.com/spreadsheet/ods/" >}}
Los archivos con extensión ODS representan el formato de documento de hoja de cálculo OpenDocument que el usuario puede editar. Los datos se almacenan dentro del archivo ODF en filas y columnas. Es un formato basado en XML y es uno de los varios subtipos de la familia de formatos de documentos abiertos (ODF). El formato se especifica como parte de las especificaciones ODF 1.2 publicadas y mantenidas por OASIS. Varias aplicaciones en Windows, así como otros sistemas operativos, pueden abrir archivos ODS para editarlos y manipularlos, incluidos Microsoft Excel, NeoOffice y LibreOffice. Los archivos ODS también se pueden convertir a otros formatos de hojas de cálculo, como XLS, XLSX y otros, mediante diferentes aplicaciones.

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Otros documentos de protección admitidos" subTitle="Usando Java, se pueden proteger otros archivos, incluidos." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/protect/xls/" name="XLS" description="Formato binario de Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/protect/xlsb/" name="XLSB" description="Archivo de libro de Excel binario" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/protect/xlsm/" name="XLSM" description="Archivo de hoja de cálculo" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/protect/xlsx/" name="XLSX" description="Archivo Excel OOXML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
