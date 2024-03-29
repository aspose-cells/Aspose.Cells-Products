---
title:  Ver formatos de archivos MHT via .NET
description: Código fuente C# para cargar, renderizar y mostrar documentos MHT en plataformas .NET Framework, .NET Core, Windows Azure, Mono o Xamarin.
keywords: [C# Aspose.Cells., c# view MHT files., c# how to render MHT document., c# load and display MHT files., MHT File Viewer using C#]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Visor de archivos MHT for .NET" h2="Vea hojas de cálculo de Excel y OpenOffice, como MHT, sin necesidad de Microsoft Excel u Office Automation." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="DOC" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DOC" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Cómo ver el archivo MHT usando C#" %}}

 Para ver el archivo MHT, usaremos<a href="https://products.aspose.com/cells/net">Aspose.Cells for .NET</a>API, que es una plataforma API para C# rica en funciones, potente y fácil de usar que se puede usar con cualquier visor. Abierto<a href="https://www.nuget.org/packages/aspose.cells">NuGet</a> administrador de paquetes, buscar<b>Aspose.Cells</b> e instalar. También puede utilizar el siguiente comando desde la Consola del Administrador de paquetes.

{{% blocks/products/pf/agp/code-block title="Comando de la consola del administrador de paquetes" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Pasos para ver MHT a través del C#" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells facilita a los desarrolladores ver el archivo MHT con solo unas pocas líneas de código.

{{% /blocks/products/pf/agp/text %}}

1. Cargue el archivo MHT en una instancia de Workbook
1. Cree una instancia de HtmlSaveOptions y establezca la propiedad ExportHeadings en verdadero
1. Guarde el archivo MHT en formato HTML usando el método Workbook.Save
1. Cargue el resultado HTML en el navegador predeterminado con Process.Start


{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos del sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for .NET es compatible con todos los principales sistemas operativos. Solo asegúrese de tener los siguientes requisitos previos.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows o un sistema operativo compatible con .NET Framework, .NET Core, Windows Azure, Mono o plataformas Xamarin
-  Entorno de desarrollo como Microsoft Visual Studio
-  Agregue una referencia a la DLL Aspose.Cells for .NET en su proyecto

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# código de ejemplo para ver el archivo MHT" offSpacer="" %}}

```cs


string output = System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".html";

// load the MHT file in an instance of Workbook
var book = new Aspose.Cells.Workbook("template.mht");
// create an instance of HtmlSaveOptions & set ExportHeadings property to true
var options = new Aspose.Cells.HtmlSaveOptions();
options.ExportHeadings = true;

// save the MHT file in HTML format
book.Save(output, options);
// load resultant HTML in default browser
System.Diagnostics.Process.Start(output);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="" %}}

Aspose.Cells API se puede utilizar para crear, editar, convertir y renderizar Microsoft formatos de Excel a diferentes formatos. Además, se puede utilizar para gráficos completos, informes escalables y cálculos confiables dentro de aplicaciones de software. Aspose.Cells es un API independiente y no requiere ningún software como Microsoft u OpenOffice.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Aplicación gratuita para ver MHT" sectionDescription=" Consulte nuestras demostraciones en vivo para[Ver MHT](https://products.aspose.app/cells/viewer/mht) con los siguientes beneficios." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No es necesario descargar ni configurar nada" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No es necesario escribir ni compilar código" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Simplemente cargue el archivo MHT y presione el botón \"Ver\"" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Descargue el archivo MHT desde el enlace, si es necesario" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="MHT" readMoreLink="https://docs.fileformat.com/web/mht/" >}}
Un archivo con extensión .mht es un formato de archivo de almacenamiento habilitado para MIME que contiene diferentes tipos de datos en un solo archivo. Puede almacenar datos como texto, imágenes, estilos de página en forma de archivos CSS, JavaScript y otros recursos como recursos integrados. Los archivos MHT, que tienen tipo MIME message/rfc822, encapsulan todo el contenido de un archivo HTML como un único archivo para almacenarlo en dispositivos de almacenamiento. Las aplicaciones de software como Microsoft Word le permiten convertir sus documentos WORD a MHT exportándolos como archivos MHT. Los archivos MHT se pueden abrir utilizando navegadores populares como Microsoft Internet Explore y Google Chrome.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
