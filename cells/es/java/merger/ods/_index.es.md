---
title:  Fusionar ODS Archivos via Java
weight: 6270
description: Código de muestra Java para combinar documentos ODS en el entorno de ejecución Java para aplicaciones JSP/JSF y aplicaciones de escritorio.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Fusionar formatos ODS en Java" h2="Fusión de documentos ODS nativa mediante API Java del lado del servidor." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="ODS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Cómo fusionar archivos ODS usando Java" %}}

 Para fusionar el archivo ODS, usaremos[Aspose.Cells for Java](https://products.aspose.com/cells/java) API, que es una plataforma de fusión API for Java rica en funciones, potente y fácil de usar. Puede descargar su última versión directamente desde[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) e instálelo dentro de su proyecto basado en Maven agregando las siguientes configuraciones a pom.xml.

{{% blocks/products/pf/agp/code-block title="Repositorio" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
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

{{% blocks/products/pf/agp/feature-section-col title="Pasos para fusionar archivos ODS en Java" %}}

{{% blocks/products/pf/agp/text %}}

 Un documento básico que se fusiona y concatena con[Aspose.Cells for Java](https://products.aspose.com/cells/java) Las API se pueden crear con solo unas pocas líneas de código.

{{% /blocks/products/pf/agp/text %}}

+ Cargue el primer archivo ODS con una instancia de la clase Workbook.
+ Cargue el segundo documento ODS con una instancia de la clase Workbook.
+ Fusionar archivos usando el método combine().
+ guarde el archivo ODS combinado en la ruta especificada

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos del sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java es compatible con todas las principales plataformas y sistemas operativos. Asegúrese de tener los siguientes requisitos previos.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows o un sistema operativo compatible con Java Runtime Environment para aplicaciones JSP/JSF y aplicaciones de escritorio.
-  Obtenga la última versión de Aspose.Cells for Java directamente desde
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells)  .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Fusionar archivos ODS - Java" offSpacer="" %}}

```cs
// Open the first ODS file.
Workbook odsFile1 = new Workbook("chartsFileWithPath.ods");

// Define the second source book.
// Open the second ODS file.
Workbook odsFile2 = new Workbook("pictureFileWithPath.ods");

// Combining the two workbooks
odsFile1.combine(odsFile2);

// Save the target book file.
odsFile1.save("combinedFileWithPath.ods");  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< blocks/products/pf/agp/demobox sectionTitle="Demostraciones en vivo de fusión en línea ODS" sectionDescription=" Fusione documentos ODS ahora mismo visitando nuestro[Sitio web de demostraciones en vivo](https://products.aspose.app/cells/merger). La demostración en vivo tiene los siguientes beneficios" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No es necesario descargar Aspose API." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No es necesario escribir ningún código." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Simplemente cargue sus archivos ODS." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Se fusionará y concatenará instantáneamente." >}}

{{< /blocks/products/pf/agp/feature-section >}}

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Acerca de Aspose.Cells for Java API" %}}

 Aspose.Cells API se puede utilizar para crear, editar, convertir y renderizar Microsoft formatos de Excel a diferentes formatos. Además, se puede utilizar para gráficos completos, informes escalables y cálculos confiables dentro de aplicaciones de software. Aspose.Cells es un API independiente y no requiere ningún software como Microsoft u OpenOffice.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}


        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODS" readMoreLink="https://docs.fileformat.com/spreadsheet/ods/" >}}
Los archivos con extensión ODS representan el formato de documento de hoja de cálculo OpenDocument que el usuario puede editar. Los datos se almacenan dentro del archivo ODF en filas y columnas. Es un formato basado en XML y es uno de los varios subtipos de la familia de formatos de documentos abiertos (ODF). El formato se especifica como parte de las especificaciones ODF 1.2 publicadas y mantenidas por OASIS. Varias aplicaciones en Windows, así como otros sistemas operativos, pueden abrir archivos ODS para editarlos y manipularlos, incluidos Microsoft Excel, NeoOffice y LibreOffice. Los archivos ODS también se pueden convertir a otros formatos de hojas de cálculo, como XLS, XLSX y otros, mediante diferentes aplicaciones.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Otros formatos de fusión admitidos" subTitle="Con Java, también se pueden combinar muchos otros formatos de archivos, incluidos..." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/csv/" name="CSV" description="Valores Separados por Comas" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/html/" name="HTML" description="Lenguaje de marcado de hipertexto" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/mhtml/" name="MHTML" description="Formato de archivo de página web" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/tsv/" name="TSV" description="Valores separados por tabulaciones" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/txt/" name="TXT" description="Documento de texto" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xls/" name="XLS" description="Formato binario de Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsb/" name="XLSB" description="Archivo de libro de Excel binario" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsm/" name="XLSM" description="Archivo de hoja de cálculo" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsx/" name="XLSX" description="Archivo Excel OOXML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlt/" name="XLT" description="Microsoft Plantilla de Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xltm/" name="XLTM" description="Plantilla habilitada para macros de Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xltx/" name="XLTX" description="Plantilla de Excel OpenXML de Office" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
