---
title: Convierta TSV en matriz de bytes a través de C# 
weight: 7690
url: /es/net/conversion/tsv-to-byte-array/ 
description: C# Código de muestra para la conversión de TSV a Byte Array. Use este código para la conversión de Excel TSV a Byte Array dentro de VB.NET, Asp.NET o cualquier aplicación basada en .NET.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Convierta TSV en una matriz de bytes a través de C#" h2="Conversión nativa y de alto rendimiento de Microsoft Excel TSV a matriz de bytes o viceversa para el procesamiento de datos de hojas de cálculo utilizando las API .NET del lado del servidor." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PDF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="TSV" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="" %}}

 Byte Array es útil para el procesamiento o almacenamiento de datos. Puede convertir un archivo TSV a Byte Array, así como un documento de **Byte Array a TSV** utilizando el idioma C#. Para convertir TSV a una matriz de bytes, usaremos
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API que ofrece diferentes funciones para la manipulación y conversión de documentos utilizando la plataforma .NET. 
{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Cómo convertir TSV a Byte Array a través de C#" %}}

{{% blocks/products/pf/agp/text %}}

 Es fácil para los desarrolladores cargar y convertir archivos TSV a una matriz de bytes para realizar más tareas de manipulación en solo unas pocas líneas de código.

{{% /blocks/products/pf/agp/text %}}

1. Incluya el espacio de nombres en su archivo de clase1. Cargue el archivo TSV de entrada usando el libro de trabajo1. Inicializar objeto MemoryStream1. Convertir datos de flujo a matriz de bytes1. Procesar datos según sus requisitos
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos del sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Solo asegúrese de que el sistema tenga Microsoft Windows o un sistema operativo compatible con .NET Framework, .NET Core, Windows Azure, Mono o Xamarin Platforms, así como un entorno de desarrollo como Microsoft Visual Studio. 

{{% /blocks/products/pf/agp/text %}}

- Instalar desde la línea de comandos como <code>nuget install Aspose.Cells</code> o a través de Package Manager Console de Visual Studio con <code>Install-Package Aspose.Cells</code>.- Alternativamente, obtenga el instalador MSI fuera de línea o todas las DLL en un archivo ZIP de <a href="https://downloads.aspose.com/cells/net">descargas</a>
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Este código de ejemplo muestra la conversión de TSV a matriz de bytes C#" offSpacer="" %}}

```cs
Workbook workbook = new Workbook("sourceFile.tsv");

//Guarde el libro de trabajo en el flujo de memoria
MemoryStream ms = new MemoryStream();

workbook.Save(ms, SaveFormat.Tsv);

//Leer bytes del flujo de memoria
byte[] byte_array = new byte[ms.Length];
ms.Read(byte_array, 0, byte_array.Length);

// Procese los datos de la matriz de bytes del flujo de memoria según sus requisitos 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<!-- aboutfile Starts -->
      
     {{% blocks/products/pf/agp/content h2="" %}}

Una biblioteca de programación de hojas de cálculo de Excel capaz de crear aplicaciones multiplataforma con la capacidad de generar, modificar, convertir, representar e imprimir todos los archivos de Excel. .NET Excel API no solo convierte entre formatos de hoja de cálculo, también puede representar archivos de Excel, incluidos TSV, como imágenes, PDF, HTML, ODS y más, lo que lo convierte en la elección perfecta para intercambiar documentos en formatos estándar de la industria.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="TSV" readMoreLink="https://docs.fileformat.com/spreadsheet/tsv/" >}}
Un formato de archivo de valores separados por tabulaciones (TSV) representa datos separados con tabulaciones en formato de texto sin formato. El formato de archivo, similar a CSV, se utiliza para la organización de datos de forma estructurada con el fin de importar y exportar entre diferentes aplicaciones. El formato se utiliza principalmente para importar/exportar e intercambiar datos en aplicaciones y bases de datos de hojas de cálculo. Cada registro en un archivo TSV está contenido en una sola línea de archivo de texto donde cada valor de campo está separado por un carácter de tabulación. El tipo de medio para el formato de archivo TSV es texto/valores separados por tabuladores.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

           {{< /blocks/products/pf/agp/about-file-section >}}


<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones admitidas" subTitle="También puede convertir otros formatos de archivo en una matriz de bytes o viceversa, incluidos algunos de los que se enumeran a continuación." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xls-to-byte-array/" name="XLS a matriz de bytes" description="Hoja de cálculo de Microsoft Excel (heredado)" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlsx-to-byte-array/" name="XLSX a matriz de bytes" description="Libro de trabajo XML abierto" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlsb-to-byte-array/" name="XLSB a matriz de bytes" description="Libro binario de Excel" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlsm-to-byte-array/" name="XLSM a matriz de bytes" description="Hoja de cálculo habilitada para macros" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlt-to-byte-array/" name="XLT a matriz de bytes" description="Excel 97 - Plantilla 2003" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xltx-to-byte-array/" name="XLTX a matriz de bytes" description="Plantilla de Excel" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xltm-to-byte-array/" name="XLTM a matriz de bytes" description="Plantilla de Excel habilitada para macros" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/csv-to-byte-array/" name="CSV a matriz de bytes" description="Valores separados por comas" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/tsv-to-byte-array/" name="TSV a matriz de bytes" description="Valores separados por tabuladores" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/ods-to-byte-array/" name="ODS a matriz de bytes" description="Hoja de cálculo de OpenDocument" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xls-to-pdf/" name="XLS a PDF" description="Formato de Documento Portable" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xls-to-html/" name="XLS a HTML" description="Lenguaje de marcado de hipertexto" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlsx-to-pdf/" name="XLSX a XPS" description="Archivo de Excel OOXML de Microsoft Excel" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlsx-to-html/" name="XLSX a HTML" description="Archivo de Excel OOXML" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlsx-to-svg/" name="XLSX a SVG" description="gráficas vectoriales escalables" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xls-to-jpeg/" name="XLS a JPEG" description="Imagen JPEG" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}