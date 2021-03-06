---
title: Desbloquear documento XLSX a través de C++ 
weight: 3680
url: /es/cpp/unlock/xlsx/ 
description: C++ código de ejemplo para desbloquear el archivo XLSX protegido con contraseña en C++ entorno de tiempo de ejecución para Windows de 32 bits, Windows de 64 bits y Linux de 64 bits.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Desbloquear archivos XLSX a través de C++" h2="Elimine la protección de las hojas de cálculo de Excel, incluido el archivo XLSX, utilizando la biblioteca C++." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSX" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Cómo quitar la protección del archivo XLSX usando C++" %}}

 Para desbloquear el archivo XLSX, usaremos
 [Aspose.Cells para C++](https://products.aspose.com/cells/cpp) 
 API, que es una protección de documentos rica en funciones, potente y fácil de usar API para la plataforma C++. Puede descargar su última versión directamente, simplemente abra
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 administrador de paquetes, busque
 **Aspose.Cells.Cpp** 
 e instalar También puede usar el siguiente comando desde la Consola del administrador de paquetes.

{{% blocks/products/pf/agp/code-block title="Aspose.Cells" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Desbloquear XLSX a través de C++" %}}

{{% blocks/products/pf/agp/text %}}

 Necesitas
 [aspose.cells.dll](https://downloads.aspose.com/cells/cpp) 
 referenciado en su proyecto para ejecutar el siguiente flujo de trabajo.

{{% /blocks/products/pf/agp/text %}}

1. Cargue el archivo bloqueado XLSX usando CreateIWorkbook.1. Llame a la función Unprotect() para desbloquear.1. Establezca la contraseña en NULL usando SetPassword.1. Guarde el archivo XLSX en una ubicación específica.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos del sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells para C++ es compatible con todas las principales plataformas y sistemas operativos. Por favor, asegúrese de que tiene los siguientes requisitos previos.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows o un sistema operativo compatible con C++ Runtime Environment para Windows de 32 bits, Windows de 64 bits y Linux de 64 bits.- Aspose.Cells para C++ DLL a la que se hace referencia en su proyecto.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Dominio" offSpacer="" %}}

```cs

// Ruta del directorio de origen.
StringPtr srcDir = new String("SourceDirectory\\");

// Ruta del directorio de salida.
StringPtr outDir = new String("OutputDirectory\\");

// Cargar archivo XLSX
intrusive_ptr<IWorkbook> workbook = Factory::CreateIWorkbook(srcDir->StringAppend(new String("sampleExcelFileProtected.xlsx")));

// Desproteger libro de trabajo
workbook->Unprotect(new String("12345"));

// Establecer contraseña en nulo
workbook->GetISettings()->SetPassword(NULL);

// Guarde el archivo XLSX
workbook->Save(outDir->StringAppend(new String("sampleExcelFileUnprotected_out.xlsx")));


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Acerca de Aspose.Cells para C++ API" %}}

 Aspose.Cells API se puede usar para crear, editar, convertir y representar formatos de Microsoft Excel en diferentes formatos. Además, se puede usar para gráficos completos, informes escalables y cálculos confiables dentro de las aplicaciones de software. Aspose.Cells es un API independiente y no requiere ningún software como Microsoft u OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Aplicación gratuita para desbloquear XLSX" sectionDescription="Consulte nuestras demostraciones en vivo para [desbloquear archivos XLSX](https://products.aspose.app/cells/unlock/xlsx) con los siguientes beneficios." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No es necesario descargar ni configurar nada" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No es necesario escribir o compilar código" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Simplemente cargue el archivo XLSX y presione el botón \"Desbloquear\"" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Descargue el archivo XLSX resultante desde el enlace" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSX" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsx/" >}}
XLSX es un formato muy conocido para documentos de Microsoft Excel que introdujo Microsoft con el lanzamiento de Microsoft Office 2007. Basado en una estructura organizada de acuerdo con las Convenciones de Empaquetado Abierto como se describe en la Parte 2 del estándar OOXML ECMA-376, el nuevo formato es un paquete zip que contiene varios archivos XML. La estructura subyacente y los archivos se pueden examinar simplemente descomprimiendo el archivo .xlsx.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Otros formatos de desbloqueo admitidos" subTitle="Usando C++, uno puede eliminar fácilmente la protección/desbloqueo de diferentes formatos, incluidos." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/unlock/ods/" name="SAO" description="Archivo de hoja de cálculo OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/unlock/xls/" name="XLS" description="Formato binario de Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/unlock/xlsb/" name="XLSB" description="Archivo de libro de Excel binario" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/unlock/xlsm/" name="XLSM" description="Archivo de hoja de cálculo" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}