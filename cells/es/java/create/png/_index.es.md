---
title: Crear PNG - Crear archivo PNG en Java
description: Aspose Excel. Java Cree un archivo PNG rápida y fácilmente con Aspose.Cells. Genere un archivo PNG usando Java. Cree PNG en Java. Java PNG Creater.
keywords: [Aspose Excel., Java Aspose.Cells., Java Create PNG file., Generate PNG file in Java., Create PNG file using Java., Write data to PNG file via Java., Create a PNG file in Java., Java Generate a PNG file., Java PNG Creater]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Crear archivo PNG en Java" h2="Biblioteca Java de alta velocidad para crear archivos PNG. Esta es una solución de software profesional para importar y exportar XLSX, PDF y muchos otros formatos utilizando Java." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PNG" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://releases.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Crear archivo PNG usando Java" %}}

 ¿Cómo crear el archivo PNG? Con la biblioteca Aspose.Cells for Java, puede crear fácilmente el archivo PNG mediante programación con unas pocas líneas de código.[Aspose.Cells for Java](https://products.aspose.com/cells/java)es capaz de crear aplicaciones multiplataforma con la capacidad de generar, modificar, convertir, renderizar e imprimir todos los archivos de Excel. Java Excel API no solo convierte entre formatos de hojas de cálculo, sino que también puede representar archivos de Excel como imágenes, PDF, HTML, ODS, CSV, SVG, JSON, WORD, PPT y más, lo que lo convierte en una opción perfecta para intercambiar documentos en formatos estándar de la industria. Puede descargar su última versión directamente desde[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) e instálelo dentro de su proyecto basado en Maven agregando las siguientes configuraciones a pom.xml.

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



{{% blocks/products/pf/agp/content h2="Cómo crear PNG en Java" %}}

{{% blocks/products/pf/agp/text %}}

 Es fácil para los desarrolladores crear, cargar, modificar y convertir archivos PNG ejecutando diferentes aplicaciones de informes para el procesamiento de datos en solo unas pocas líneas de código.

{{% /blocks/products/pf/agp/text %}}

1.  Crear una instancia de[clase de libro de trabajo](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook).
1.  Acceda a la hoja de trabajo relevante utilizando el método getWorksheets.get().
1.  Seleccione la celda relevante, ingrese el valor en la celda deseada usando el nombre de la celda, como A1, B3, etc.
1. Guarde el libro de trabajo en formato PNG utilizando el método save().

{{% blocks/products/pf/agp/code-block title="El código de muestra muestra cómo crear el archivo PNG en Java." offSpacer="" %}}

```cs

// Create a new workbook
Workbook wkb = new Workbook();

// Access the first worksheet of the workbook.
Worksheet worksheet = wkb.getWorksheets().get(0);

// Add relevant content in the cell
worksheet.getCells().get("A1").putValue("ColumnA");
worksheet.getCells().get("B1").putValue("ColumnB")
worksheet.getCells().get("A2").putValue("ValueA")
worksheet.getCells().get("B2").putValue("ValueB")

// Save the workbook as PNG file
wkb.save("Excel.png"); 

// To enhance the code for further functionalities here are more functions
// getCells() and setValue for modifying the cell content
// getCharts().add() to add charts
// getPivotTables().add() for creating a Pivot Table
// getCells().get(int cell id).setFormula for adding cell level formula

```

{{% /blocks/products/pf/agp/code-block %}}
{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="Biblioteca Java para crear el archivo PNG" %}}
{{% blocks/products/pf/agp/text %}}

 Alojamos nuestros paquetes Java en[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) repositorios. 'Aspose.Cells for Java' es un archivo JAR común que contiene código de bytes. Por favor sigue el[instrucciones paso a paso](https://docs.aspose.com/cells/java/installation/) sobre cómo instalarlo en su entorno de desarrollador Java.

{{% /blocks/products/pf/agp/text %}}
{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="Requisitos del sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Antes de ejecutar el código fuente de muestra de conversión Java, asegúrese de cumplir los siguientes requisitos previos.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows o un sistema operativo compatible con Java Runtime Environment para aplicaciones JSP/JSF y aplicaciones de escritorio.
- Aspose.Cells for Java admite las siguientes versiones de Java: J2SE 6.0 (1.6), J2SE 7.0 (1.7) o superior.
- [Obtenga la última versión de Aspose.Cells for Java directamente desde Maven.](https://docs.aspose.com/cells/java/installation/) 

{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->
    {{< blocks/products/pf/agp/about-file-section >}}
        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PNG" readMoreLink="https://docs.fileformat.com/image/png/" >}}Un archivo PNG (Portable Network Graphics) es un formato de archivo de imagen rasterizada que utiliza compresión sin pérdidas. Este formato de archivo se creó como reemplazo del formato de intercambio de gráficos (GIF) y no tiene limitaciones de derechos de autor. Sin embargo, el formato de archivo PNG no admite animaciones. El formato de archivo PNG admite la compresión de imágenes sin pérdidas, lo que lo hace popular entre sus usuarios. Con el paso del tiempo, PNG ha evolucionado como uno de los formatos de archivos de imágenes más utilizados.{{< /blocks/products/pf/agp/i18n/about-file-text >}}
    {{< /blocks/products/pf/agp/about-file-section >}}
<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Otra generación de hojas de cálculo admitida" subTitle="También puede crear otros formatos de Excel Microsoft, incluidos algunos que se enumeran a continuación." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create/xls/" name="XLS" description="Microsoft Hoja de cálculo de Excel (heredada)" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create/xlsx/" name="XLSX" description="Abrir libro XML" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create/xlsb/" name="XLSB" description="Libro binario de Excel" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create/xlsm/" name="XLSM" description="Hoja de cálculo habilitada para macros" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create/xlt/" name="XLT" description="Plantilla Excel 97 - 2003" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create/xltx/" name="XLTX" description="Plantilla de Excel" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create/xltm/" name="XLTM" description="Plantilla habilitada para macros de Excel" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create/csv/" name="CSV" description="Valores Separados por Comas" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create/tsv/" name="TSV" description="Valores separados por tabulaciones" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create/ods/" name="ODS" description="Hoja de cálculo de OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create/pdf/" name="PDF" description="Formato de Documento Portable" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create/html/" name="HTML" description="Lenguaje de marcado de hipertexto" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
