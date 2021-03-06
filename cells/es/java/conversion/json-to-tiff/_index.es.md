---
title: Convierta JSON a TIFF a través de Java 
weight: 9840
url: /es/java/conversion/json-to-tiff/ 
description: Ejemplo de código de conversión Java para formato JSON a archivo TIFF. Los programadores pueden usar este código de ejemplo para exportar hojas de cálculo de Excel y OpenOffice a TIFF dentro de cualquier aplicación basada en Web o escritorio Java.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Convierta JSON a TIFF a través de Java" h2="Exporte JSON a formato TIFF a través de Java sin necesidad de herramientas o bibliotecas adicionales." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="TIFF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="JSON" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Cómo convertir JSON a TIFF usando Java" %}}

 Para convertir JSON a TIFF, usaremos
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

{{% blocks/products/pf/agp/feature-section-col title="Pasos para convertir JSON a TIFF a través de Java" %}}

{{% blocks/products/pf/agp/text %}}

 Los desarrolladores de Java pueden convertir fácilmente un archivo JSON a TIFF con solo unas pocas líneas de código.

{{% /blocks/products/pf/agp/text %}}

1. Crear una nueva instancia de la clase Workbook1. Seleccione predeterminado o cualquier hoja de trabajo de la colección1. Cargar datos JSON desde un archivo1. Crear una instancia de JsonLayoutOptions y establecer opciones1. Llame al método JsonUtility.importData para importar datos JSON1. Cree y configure el objeto de ImageOrPrintOptions para la representación TIFF1. Crear SheetRender para renderizar1. Llame al método SheetRender.toImage para guardar el resultado en formato TIFF
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos del sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Antes de ejecutar el código fuente de la conversión Java, asegúrese de cumplir los siguientes requisitos previos.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows o un sistema operativo compatible con Java Runtime Environment para aplicaciones JSP/JSF y aplicaciones de escritorio.- Obtenga la última versión de Aspose.Cells for Java directamente de Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Código fuente de conversión de JSON a TIFF Java" offSpacer="" %}}

```cs
// leer archivo de datos JSON como cadena
String jsonInput = new String(Files.readAllBytes(Paths.get("data.json")));

// crear un objeto de libro de trabajo en blanco
Workbook workbook = new Workbook();
// acceder a la hoja de cálculo vacía predeterminada
Worksheet worksheet = workbook.getWorksheets().get(0);

// establecer JsonLayoutOptions para formatear
JsonLayoutOptions layoutOptions = new JsonLayoutOptions();
layoutOptions.setArrayAsTable(true);

// importar datos JSON a la hoja de trabajo predeterminada que comienza en la celda A1
JsonUtility.importData(jsonInput, worksheet.getCells(), 0, 0, layoutOptions);

// definir parámetros para la imagen resultante
ImageOrPrintOptions renderingOptions = new ImageOrPrintOptions();
renderingOptions.setOnePagePerSheet(true);
renderingOptions.setImageType(ImageType.TIFF);

// convertir hoja de trabajo a imagen en formato TIFF
SheetRender renderer = new SheetRender(worksheet, renderingOptions);
renderer.toImage(0, "output.tiff");   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Demostraciones en vivo de conversión de JSON a TIFF" sectionDescription="[Convertir JSON a TIFF](https://products.aspose.app/cells/conversion/json-to-tiff) ahora mismo visitando nuestro sitio web de demostraciones en vivo. La demostración en vivo tiene los siguientes beneficios" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No es necesario descargar Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No es necesario escribir ningún código." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Simplemente cargue su archivo JSON, se convertirá instantáneamente a TIFF." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Obtendrá el enlace de descarga." >}}

    {{% blocks/products/pf/agp/content h2="Java Biblioteca de manipulación de hojas de cálculo" %}}

 Excel API se puede usar para crear, editar, convertir y representar formatos de Microsoft Excel en diferentes formatos. Además, se puede usar para gráficos completos, informes escalables y cálculos confiables dentro de las aplicaciones de software. Aspose.Cells es un API independiente y no requiere ningún software como Microsoft u OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="JSON" readMoreLink="https://docs.fileformat.com/web/json/" >}}

JSON (Notación de objetos de JavaScript) es un formato de archivo estándar abierto para compartir datos que utiliza texto legible por humanos para almacenar y transmitir datos. Los archivos JSON se almacenan con la extensión .json. JSON requiere menos formato y es una buena alternativa para XML. JSON se deriva de JavaScript, pero es un formato de datos independiente del idioma. Muchos lenguajes de programación modernos admiten la generación y el análisis de JSON. application/json es el tipo de medio utilizado para JSON.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="TIFF" readMoreLink="https://docs.fileformat.com/image/tiff/" >}}

TIFF o TIF, formato de archivo de imagen etiquetada, representa imágenes de trama diseñadas para su uso en una variedad de dispositivos que cumplen con este estándar de formato de archivo. Es capaz de describir datos de imagen de dos niveles, escala de grises, colores de paleta y a todo color en varios espacios de color. Admite esquemas de compresión con pérdida y sin pérdida para elegir entre el espacio y el tiempo para las aplicaciones que utilizan el formato. El formato es extensible y ha sufrido varias revisiones que permiten la inclusión de una cantidad ilimitada de información privada o de propósito especial. El formato no depende de la máquina y está libre de límites como el procesador, el sistema operativo o los sistemas de archivos.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones admitidas" subTitle="También puede convertir JSON a muchos otros formatos de archivo, incluidos algunos de los que se enumeran a continuación." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/json-to-xls/" name="JSON A XLS" description="Formato binario de Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/json-to-xlsx/" name="JSON A XLSX" description="Archivo de Excel OOXML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/json-to-xlsb/" name="JSON A XLSB" description="Archivo de libro de Excel binario" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/json-to-xlsm/" name="JSON A XLSM" description="Archivo de hoja de cálculo" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/json-to-xlt/" name="JSON A XLT" description="Plantilla de Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/json-to-xltx/" name="JSON A XLTX" description="Plantilla de Excel OpenXML de Office" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/json-to-xltm/" name="JSON A XLTM" description="Plantilla de Excel habilitada para macros" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/json-to-csv/" name="JSON A CSV" description="Valores Separados por Comas" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/json-to-tsv/" name="JSON A TSV" description="Valores separados por tabuladores" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/json-to-txt/" name="JSON A TXT" description="Documento de texto" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/json-to-html/" name="JSON A HTML" description="Lenguaje de marcado de hipertexto" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/json-to-mhtml/" name="JSON A MHTML" description="Formato de archivo de página web" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/json-to-ods/" name="JSON A ODS" description="Archivo de hoja de cálculo OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/json-to-dif/" name="JSON A DIF" description="Formato de intercambio de datos" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/json-to-pdf/" name="JSON A PDF" description="Formato de Documento Portable" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/json-to-xps/" name="JSON A XPS" description="Especificaciones de papel XML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/json-to-svg/" name="JSON A SVG" description="gráficas vectoriales escalables" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/json-to-png/" name="JSON A PNG" description="Gráficos de red portátiles" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/json-to-bmp/" name="JSON A BMP" description="Imagen de mapa de bits" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/json-to-emf/" name="JSON A CEM" description="Formato de metarchivo mejorado" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/json-to-jpeg/" name="JSON A JPEG" description="Imagen JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/json-to-gif/" name="JSON A GIF" description="Formato de intercambio gráfico" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/json-to-md/" name="JSON A MD" description="Lenguaje de rebajas" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/json-to-docx/" name="JSON A DOCX" description="Documento de palabras de Office 2007+" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/json-to-pdf/" name="JSON A PDF" description="Formato de Documento Portable" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}