---
title:  Buscar documento TXT sin abrir vía C++
weight: 5090
description: Código de ejemplo C++ para buscar palabras con patrón en el archivo TXT en el entorno de ejecución C++ para Windows de 32 bits, Windows de 64 bits y Linux de 64 bits.
keywords: [C++ Aspose.Cells., C++ search words with pattern in txt file., C++ find words with pattern in txt file., C++ search string with pattern in txt file., C++ find words with pattern in txt file., C++ search words in txt file., C++ find words in txt file., C++ search string in txt file., C++ find string in txt file]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Buscar TXT Formatos en C++" h2="Búsqueda de documentos TXT nativa y de alto rendimiento utilizando API Aspose.Cells for C++ del lado del servidor, sin el uso de ningún software como Microsoft o Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="TXT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Cómo buscar el archivo TXT usando C++" %}}

 Para buscar el archivo TXT, usaremos
 [Aspose.Cells for C++](https://products.aspose.com/cells/cpp) 
API, que es una plataforma de búsqueda de documentos API for C++ rica en funciones, potente y fácil de usar. Puede descargar su última versión directamente, simplemente abra
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 administrador de paquetes, buscar
 **Aspose.Cells.Cpp** 
 e instalar. También puede utilizar el siguiente comando desde la Consola del Administrador de paquetes.

{{% blocks/products/pf/agp/code-block title="Dominio" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Pasos para buscar archivos TXT en C++" %}}

{{% blocks/products/pf/agp/text %}}

 Se puede realizar una búsqueda básica de documentos utilizando las API Aspose.Cells con solo unas pocas líneas de código.

{{% /blocks/products/pf/agp/text %}}

+ Cargue el archivo TXT creando una instancia de una clase de Libro de trabajo.
+ Crear una instancia de la clase ReemplazarOpciones.
+ Establecer el patrón requerido como SetCaseSensitive(valor bool), SetMatchEntireCellContents(valor bool).
Utilice el método Workbook::Replace(...) con opciones relevantes.
+ Guarde el archivo TXT usando el método Workbook::Save(...).

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos del sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for C++ es compatible con todas las principales plataformas y sistemas operativos. Asegúrese de tener los siguientes requisitos previos.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows o un sistema operativo compatible con C++ Runtime Environment para Windows de 32 bits, Windows de 64 bits y Linux de 64 bits.
-  Agregue una referencia a la DLL Aspose.Cells for C++ en su proyecto.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Buscar archivos TXT - C++" offSpacer="" %}}

```cs

Aspose::Cells::Startup();

// Source directory path.
U16String srcDir(u"SourcePath\\");

// Output directory path.
U16String outDir(u"OutputPath\\");

// Load TXT file
Workbook  wkb(srcDir + u"sourceFile.txt");

// Create an instance of the IReplaceOptions class
ReplaceOptions replaceOptions;

// Set case sensitivity option
replaceOptions.SetCaseSensitive(false);

// Set text matching option
replaceOptions.SetMatchEntireCellContents(false);

// Replace text
wkb.Replace(u"Text to find", u"Text replacement", replaceOptions);

// Save as TXT file
wkb.Save(outDir + u"outputFile.txt");

Aspose::Cells::Cleanup();

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="Acerca de Aspose.Cells for C++ API" %}}

 Aspose.Cells API se puede utilizar para crear, editar, convertir y renderizar Microsoft formatos de Excel a diferentes formatos. Además, se puede utilizar para gráficos completos, informes escalables y cálculos confiables dentro de aplicaciones de software. Aspose.Cells es un API independiente y no requiere ningún software como Microsoft u OpenOffice.



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="En línea TXT Buscar demostraciones en vivo" sectionDescription=" Busque texto, palabras y frases dentro de TXT documentos ahora mismo visitando nuestro[Sitio web de demostraciones en vivo](https://products.aspose.app/cells/search). La demostración en vivo tiene los siguientes beneficios" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No es necesario descargar Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No es necesario escribir ningún código." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Simplemente cargue sus archivos TXT." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" El resultado de la búsqueda aparece instantáneamente." >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="TXT " readMoreLink="https://docs.fileformat.com/word-processing/txt/" >}}
Un archivo con extensión .TXT representa un documento de texto que contiene texto sin formato en forma de líneas. Los párrafos de un documento de texto se reconocen mediante retornos de carro y se utilizan para organizar mejor el contenido del archivo. Un documento de texto estándar se puede abrir en cualquier editor de texto o aplicación de procesamiento de textos en diferentes sistemas operativos. Todo el texto contenido en dicho archivo está en formato legible por humanos y representado por una secuencia de caracteres.

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Otros documentos de búsqueda admitidos" subTitle="Usando C++, también se pueden buscar otros archivos, incluidos." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/csv/" name="CSV" description="Valores Separados por Comas" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/ods/" name="ODS" description="Archivo de hoja de cálculo OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/tsv/" name="TSV" description="Valores separados por tabulaciones" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/xls/" name="XLS" description="Formato binario de Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/xlsb/" name="XLSB" description="Archivo de libro de Excel binario" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/xlsm/" name="XLSM" description="Archivo de hoja de cálculo" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
