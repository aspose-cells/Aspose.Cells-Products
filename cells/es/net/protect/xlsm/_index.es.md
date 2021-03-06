---
title: Proteja y bloquee el documento XLSM a través de .NET 
weight: 7530
url: /es/net/protect/xlsm/ 
description: C# código fuente para bloquear el archivo XLSM mediante contraseña en .NET Framework, .NET Core, Mono o Xamarin Platforms.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Cifrar archivos XLSM a través de C#" h2="Proteja con contraseña las hojas de cálculo de Excel, incluido el formato XLSM, utilizando la biblioteca .NET." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSM" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Cómo proteger un archivo XLSM usando C#" %}}

 Para proteger el archivo XLSM, usaremos
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API, que es una protección de documentos rica en funciones, potente y fácil de usar API para la plataforma C#. Abierto
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 administrador de paquetes, busque
 **Aspose.Cells** 
 e instalar También puede usar el siguiente comando desde la Consola del administrador de paquetes.

{{% blocks/products/pf/agp/code-block title="Aspose.Cells" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Proteger XLSM a través de C#" %}}

{{% blocks/products/pf/agp/text %}}

 Necesitas
 [aspose.cells.dll](https://downloads.aspose.com/cells/net) 
 referenciado en su proyecto para ejecutar el siguiente flujo de trabajo.

{{% /blocks/products/pf/agp/text %}}

1. Instanciar la clase Workbook con la ruta al archivo XLSM1. Obtenga el valor predeterminado o cualquier hoja de trabajo para agregar protección1. Proteger la hoja de trabajo con el método Worksheet.Protect1. Proteger el libro de trabajo con el método Workbook.Protect1. Guardar resultado en formato XLSM
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos del sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for .NET es compatible con todos los principales sistemas operativos. Solo asegúrese de tener los siguientes requisitos previos.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows o un sistema operativo compatible con .NET Framework, .NET Core, Mono o Xamarin Platforms- Entorno de desarrollo como Microsoft Visual Studio- Aspose.Cells for .NET referenciado en su proyecto
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Dominio" offSpacer="" %}}

```cs

// cargar el archivo Excel XLSM 
var book = new Aspose.Cells.Workbook("unlocked.xlsm");

// acceder a la primera hoja de trabajo
var worksheet = book.Worksheets[0];

// proteger la hoja de trabajo con contraseña
worksheet.Protect(Aspose.Cells.ProtectionType.All, "password", null);

// proteger todo el libro de trabajo con contraseña
book.Protect(Aspose.Cells.ProtectionType.All, "password");

// guardar el archivo modificado en el formato predeterminado
book.Save("protected.xlsm");


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Acerca de Aspose.Cells for .NET API" %}}

 Aspose.Cells API se puede usar para crear, editar, convertir y representar formatos de Microsoft Excel en diferentes formatos. Además, se puede usar para gráficos completos, informes escalables y cálculos confiables dentro de las aplicaciones de software. Aspose.Cells es un API independiente y no requiere ningún software como Microsoft u OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Aplicación gratuita para proteger XLSM" sectionDescription="Consulte nuestras demostraciones en vivo para [cifrar archivos XLSM](https://products.aspose.app/cells/protect/xlsm) con los siguientes beneficios." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No es necesario descargar ni configurar nada" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No es necesario escribir o compilar código" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Simplemente cargue el archivo XLSM y presione el botón \"Desbloquear\"" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Descargue el archivo XLSM resultante desde el enlace" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSM" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsm/" >}}
Los archivos con extensión XLSM son un tipo de archivos de hoja de cálculo que admiten macros. Desde el punto de vista de la aplicación, una macro es un conjunto de instrucciones que se utilizan para automatizar procesos. Una macro se usa para registrar los pasos que se realizan repetidamente y facilita la realización de las acciones ejecutando la macro nuevamente. Las macros se programan con Visual Basic para Aplicaciones (VBA) de Microsoft desde el Libro de trabajo de Excel usando el Editor de Visual Basic y se pueden ejecutar/depurar directamente desde allí.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Otros formatos de protección admitidos" subTitle="Usando C#, uno puede proteger fácilmente otros formatos, incluidos." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/ods/" name="SAO" description="Archivo de hoja de cálculo OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/xls/" name="XLS" description="Formato binario de Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/xlsb/" name="XLSB" description="Archivo de libro de Excel binario" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/xlsx/" name="XLSX" description="Archivo de Excel OOXML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}