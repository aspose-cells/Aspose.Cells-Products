---
title: Crear TABDELIMITED - Crear archivo TABDELIMITED en C#
description: Aspose Excel. C# Cree un archivo TABDELIMITED rápida y fácilmente con Aspose.Cells. Genere un archivo TABDELIMITED usando C#. Cree TABDELIMITED en C#. C# TABDELIMITED Creater.
keywords: [Aspose Excel., C# Aspose.Cells., C# Create TABDELIMITED file., Generate TABDELIMITED file in C#., Create TABDELIMITED file using C#., Write data to TABDELIMITED file via C#., Create a TABDELIMITED file in C#., C# Generate a TABDELIMITED file., C# TABDELIMITED Creater]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Crear archivo TABDELIMITED en C#" h2="Biblioteca C# de alta velocidad para crear TABDELIMITED. Esta es una solución de software profesional para importar y exportar XLSX, PDF y muchos otros formatos en las plataformas .NET Framework, .NET Core o Mono." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="TABDELIMITED" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://releases.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Cree un archivo TABDELIMITADO usando C#" %}}
 ¿Cómo crear un archivo TABDELIMITED? Con la biblioteca Aspose.Cells for .NET, puede crear fácilmente un archivo TABDELIMITED mediante programación con unas pocas líneas de código.[Aspose.Cells for .NET](https://products.aspose.com/cells/net)es capaz de crear aplicaciones multiplataforma con la capacidad de generar, modificar, convertir, renderizar e imprimir todos los archivos de Excel. .NET Excel API no solo convierte entre formatos de hojas de cálculo, sino que también puede representar archivos de Excel como imágenes, PDF, HTML, ODS, CSV, SVG, JSON, WORD, PPT y más, lo que lo convierte en una opción perfecta para intercambiar documentos en formatos estándar de la industria. Abierto[NuGet](https://www.nuget.org/packages/aspose.cells) administrador de paquetes, busque Aspose.Cells e instálelo. También puede utilizar el siguiente comando desde la Consola del Administrador de paquetes.

{{% blocks/products/pf/agp/code-block title="Comando de la consola del administrador de paquetes" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}
 
{{% /blocks/products/pf/agp/content %}}


{{% blocks/products/pf/agp/content h2="Cómo crear TABDELIMITED en C#" %}}

{{% blocks/products/pf/agp/text %}}

Es fácil para los desarrolladores crear, cargar, modificar y convertir archivos TABDELIMITED ejecutando diferentes aplicaciones de informes para el procesamiento de datos en solo unas pocas líneas de código.

{{% /blocks/products/pf/agp/text %}}

1.  Incluya el espacio de nombres en su archivo de clase
1.  Crear una instancia de clase de libro de trabajo.
1.  Acceda a la primera hoja de trabajo del libro de trabajo.
1.  Obtenga las celdas deseadas de la hoja de trabajo e ingrese el valor en las celdas.
1.  Utilice el método Guardar para guardar el libro como archivo TABDELIMITED.

{{% blocks/products/pf/agp/code-block title="El código de muestra muestra cómo crear un archivo TABDELIMITED en C#." offSpacer="" %}}

```cs

// Create Workbook class instance.
Workbook wkb = new Workbook();

// Access the first worksheet of the workbook.
Worksheet sht = wkb.Worksheets[0];

// Get the desired cell(s) of the worksheet.
Cell c00 = sht.Cells["A1"];
Cell c01 = sht.Cells["B1"];
Cell c10 = sht.Cells["A2"];
Cell c11 = sht.Cells["B2"];

// input the value into the cell(s).
c00.PutValue("ColumnA");
c01.PutValue("ColumnB");
c10.PutValue("ValueA");
c11.PutValue("ValueB");

// Save the Workbook as .tsv file.
wkb.Save("created_one.tsv");

```

{{% /blocks/products/pf/agp/code-block %}}
{{% /blocks/products/pf/agp/content %}}


{{% blocks/products/pf/agp/content h2="C# biblioteca para crear un archivo TABDELIMITED" %}}

{{% blocks/products/pf/agp/text %}}

Hay dos opciones alternativas para instalar "Aspose.Cells for .NET" en su sistema. Elija uno que se adapte a sus necesidades y siga las instrucciones paso a paso:

{{% /blocks/products/pf/agp/text %}}

1.  Instalar un[NuGet Paquete](https://www.nuget.org/packages/Aspose.Cells/) . Ver[Documentación](https://docs.aspose.com/cells/net/installation/#install-asposecells-for-net-through-nuget)
1.  Instale la biblioteca usando[Consola del administrador de paquetes](https://docs.aspose.com/cells/net/installation/#install-asposecells-using-the-package-manager-console) dentro del IDE de Visual Studio

{{% /blocks/products/pf/agp/content %}}


{{% blocks/products/pf/agp/content h2="Requisitos del sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Antes de ejecutar el código de ejemplo de conversión .NET, asegúrese de tener los siguientes requisitos previos.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows o un sistema operativo compatible con las plataformas .NET, .NET Core, Windows Azure o Mono.
-  Entorno de desarrollo como Microsoft Visual Studio.
-  Agregue una referencia a la DLL Aspose.Cells for .NET en su proyecto.

{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->
    {{< blocks/products/pf/agp/about-file-section >}}
        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="TABDELIMITED" readMoreLink="https://docs.fileformat.com/spreadsheet/tsv/" >}}Un formato de archivo de valores separados por tabulaciones (TSV) representa datos separados por tabulaciones en formato de texto sin formato. El formato de archivo, similar a CSV, se utiliza para organizar datos de forma estructurada para importar y exportar entre diferentes aplicaciones. El formato se utiliza principalmente para la importación/exportación e intercambio de datos en aplicaciones de hojas de cálculo y bases de datos. Cada registro en un archivo TSV está contenido en una sola línea de archivo de texto donde cada valor de campo está separado por un carácter de tabulación. El tipo de medio para el formato de archivo TSV es texto/valores separados por tabulaciones.{{< /blocks/products/pf/agp/i18n/about-file-text >}}
    {{< /blocks/products/pf/agp/about-file-section >}}
<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Otra generación de hojas de cálculo admitida" subTitle="También puede crear otros formatos de Excel Microsoft, incluidos algunos que se enumeran a continuación." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/xls/" name="XLS" description="Microsoft Hoja de cálculo de Excel (heredada)" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/xlsx/" name="XLSX" description="Abrir libro XML" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/xlsb/" name="XLSB" description="Libro binario de Excel" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/xlsm/" name="XLSM" description="Hoja de cálculo habilitada para macros" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/xlt/" name="XLT" description="Plantilla Excel 97 - 2003" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/xltx/" name="XLTX" description="Plantilla de Excel" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/xltm/" name="XLTM" description="Plantilla habilitada para macros de Excel" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/csv/" name="CSV" description="Valores Separados por Comas" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/tsv/" name="TSV" description="Valores separados por tabulaciones" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/ods/" name="ODS" description="Hoja de cálculo de OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/pdf/" name="PDF" description="Formato de Documento Portable" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/html/" name="HTML" description="Lenguaje de marcado de hipertexto" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
