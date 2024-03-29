---
title:  Desbloquear XLSB documento via .NET
weight: 6410
description: Código fuente C# para desbloquear el archivo XLSB protegido con contraseña en .NET Framework, .NET Core, Mono o plataformas Xamarin.
keywords: [C# Aspose.Cells., c# unlock XLSB files., c# how to unlock XLSB document., c# unprotect XLSB files., remove protection from XLSB files., decrypt XLSB Files using C#]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Desbloquear hoja de cálculo XLSB a través de C#" h2="Elimine la protección de XLSB usando la biblioteca .NET." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSB" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSB" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Cómo desbloquear el archivo XLSB usando C#" %}}

 Para eliminar el archivo de protección XLSB, usaremos
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API, que es una protección de documentos API rica en funciones, potente y fácil de usar para la plataforma C#. Abierto
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 administrador de paquetes, buscar
 **Aspose.Cells** 
 e instalar. También puede utilizar el siguiente comando desde la Consola del Administrador de paquetes.

{{% blocks/products/pf/agp/code-block title="Aspose.Cells" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Desbloquear XLSB a través de C#" %}}

{{% blocks/products/pf/agp/text %}}

 Necesitas
 [aspose.cells.dll](https://downloads.aspose.com/cells/net) 
 referenciado en su proyecto para ejecutar el siguiente flujo de trabajo.

{{% /blocks/products/pf/agp/text %}}

1.  Crear una instancia de la clase Workbook con la ruta al archivo protegido XLSB
1.  Obtenga la hoja de trabajo predeterminada o cualquier hoja de trabajo para eliminar la protección
1.  Eliminar la protección de la hoja de trabajo con el método Worksheet.Unprotect
1.  Eliminar la protección del libro de trabajo con el método Workbook.Unprotect
1.  Guardar resultado en formato XLSB

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos del sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for .NET es compatible con todos los principales sistemas operativos. Solo asegúrese de tener los siguientes requisitos previos.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows o un sistema operativo compatible con .NET Framework, .NET Core, Mono o plataformas Xamarin
-  Entorno de desarrollo como Microsoft Visual Studio
-  Agregue una referencia a la DLL Aspose.Cells for .NET en su proyecto

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Dominio" offSpacer="" %}}

```cs

// instantiate a Workbook object with protected XLSB file
var workbook = new Aspose.Cells.Workbook("protected.xlsb");

// access the default worksheet in the Excel file
var worksheet = workbook.Worksheets[0];

// unprotect worksheet without a password
worksheet.Unprotect();

// unprotect workbook with password
workbook.Unprotect("password");

// save the result back in XLSB format
workbook.Save("unprotected.xlsb", Aspose.Cells.SaveFormat.Auto);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Acerca de Aspose.Cells for .NET API" %}}

 Aspose.Cells API se puede utilizar para crear, editar, convertir y renderizar Microsoft formatos de Excel a diferentes formatos. Además, se puede utilizar para gráficos completos, informes escalables y cálculos confiables dentro de aplicaciones de software. Aspose.Cells es un API independiente y no requiere ningún software como Microsoft u OpenOffice.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Aplicación gratuita para desbloquear XLSB" sectionDescription=" Consulte nuestras demostraciones en vivo para[desbloquear archivos XLSB](https://products.aspose.app/cells/unlock/xlsb) con los siguientes beneficios." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No es necesario descargar ni configurar nada" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No es necesario escribir ni compilar código" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Simplemente cargue el archivo XLSB y presione el botón \"Desbloquear\"" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Descargue el archivo XLSB resultante desde el enlace" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSB" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsb/" >}}
El formato de archivo XLSB especifica el formato de archivo binario de Excel, que es una colección de registros y estructuras que especifican el contenido del libro de Excel. El contenido puede incluir tablas de números no estructuradas o semiestructuradas, texto o números y texto, fórmulas, conexiones de datos externos, gráficos e imágenes. A diferencia de XLSX (que se basa en el formato de archivo Open XML), XLSB representa un archivo binario de libro de Excel. Los archivos XLSB se pueden leer y escribir más rápido, lo que los hace útiles para trabajar con archivos grandes. XLSB rara vez se usa para almacenar libros de trabajo, ya que XLSX (y anteriormente XLS) son los formatos de archivo seleccionados por el usuario más comunes para guardar libros de trabajo. Se puede abrir mediante Microsoft Office 2007 y superior.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Otros formatos de desbloqueo admitidos" subTitle="Con C#, se puede eliminar fácilmente la protección/desbloqueo de diferentes formatos, incluido." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/unlock/ods/" name="ODS" description="Archivo de hoja de cálculo OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/unlock/xls/" name="XLS" description="Formato binario de Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/unlock/xlsm/" name="XLSM" description="Archivo de hoja de cálculo" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/unlock/xlsx/" name="XLSX" description="Archivo Excel OOXML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
