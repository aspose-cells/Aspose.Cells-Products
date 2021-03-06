---
title: Convierta TXT a EMF a través de la aplicación C++ 
url: /es/cpp/conversion/txt-to-emf/ 
description: Ejemplo de código de conversión C++ para documento TXT a formato EMF. Los programadores pueden usar este código fuente para la conversión por lotes de TXT a EMF dentro de cualquier aplicación C++.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Convierte TXT a EMF a través de C++" h2="Conversión de TXT a EMF de alto rendimiento utilizando la biblioteca C++ sin necesidad de instalar Microsoft Excel, OpenOffice o Adobe Acrobat." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="EMF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="TXT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Cómo convertir TXT a EMF usando C++" %}}

 Para convertir TXT a EMF, usaremos
 [Aspose.Cells para C++](https://products.aspose.com/cells/cpp) 
 API, que es una manipulación y conversión de documentos rica en funciones, potente y fácil de usar API para la plataforma C++. Puede descargar su última versión directamente, simplemente abra
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 administrador de paquetes, busque
 Aspose.Cells.cpp 
 e instalar También puede usar el siguiente comando desde la Consola del administrador de paquetes.

{{% blocks/products/pf/agp/code-block title="Dominio" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Pasos para convertir TXT a EMF a través de C++" %}}

{{% blocks/products/pf/agp/text %}}

 Los desarrolladores de C++ pueden convertir fácilmente un archivo TXT a EMF con solo unas pocas líneas de código.

{{% /blocks/products/pf/agp/text %}}

1. Cargue el archivo TXT usando Factory::CreateIWorkbook.1. Seleccione la primera hoja de trabajo.1. Establecer opciones (EMF).1. Iterar a través de cada página de la hoja y renderizar.1. Abra el archivo EMF en un programa compatible.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos del sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Antes de ejecutar el código de ejemplo de conversión C++, asegúrese de cumplir los siguientes requisitos previos.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows o un sistema operativo compatible con C++ Runtime Environment para Windows de 32 bits, Windows de 64 bits y Linux de 64 bits.- Aspose.Cells para C++ DLL a la que se hace referencia en su proyecto.
- Microsoft Windows o un sistema operativo compatible con C++ Runtime Environment para Windows de 32 bits, Windows de 64 bits y Linux de 64 bits.- Aspose.Cells para C++ DLL a la que se hace referencia en su proyecto.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Código fuente de conversión de TXT a EMF C++" offSpacer="" %}}

```cs
// Ruta del directorio de salida.
StringPtr outDir = new String("OutputDirectoryPath");

// Cargue el TXT.
intrusive_ptr<Aspose::Cells::IWorkbook> workbook = Factory::CreateIWorkbook(u"sourceFile.txt");

// Acceda a la primera hoja de trabajo.
intrusive_ptr<Aspose::Cells::IWorksheet> worksheet = workbook->GetIWorksheets()->GetObjectByIndex(0);

// Crear imagen o objeto de opciones de impresión.
intrusive_ptr<Aspose::Cells::Rendering::IImageOrPrintOptions> imgOptions = Factory::CreateIImageOrPrintOptions();

// Especifique el formato de la imagen.
imgOptions->SetImageFormat(Aspose::Cells::Systems::Drawing::Imaging::ImageFormat::GetEmf());

// Especificar resolución horizontal y vertical
imgOptions->SetHorizontalResolution(200);
imgOptions->SetVerticalResolution(200);

// Renderice la hoja con respecto a la imagen especificada o las opciones de impresión.
intrusive_ptr<Aspose::Cells::Rendering::ISheetRender> sr = Factory::CreateISheetRender(worksheet, imgOptions);

// Obtener recuento de páginas.
Aspose::Cells::Systems::Int32 pageCount = sr->GetPageCount();

// Cree un objeto generador de cadenas para concatenaciones de cadenas.
intrusive_ptr<Aspose::Cells::Systems::Text::StringBuilder> sb = new Aspose::Cells::Systems::Text::StringBuilder();

// Renderice cada página a imagen emf una por una.
for (int i = 0; i Clear();
	sb->Append(outDir);
	sb->Append((StringPtr)new String("outputConvertingWorksheetToImageEMF_"));
	sb->Append(i);
	sb->Append((StringPtr)new String(".emf"));

	// Obtenga la ruta de la imagen de salida.
	StringPtr outputEMF = sb->ToString();

	// Convierta la hoja de trabajo a la imagen emf.
	sr->ToImage(i, outputEMF);
}


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Demostraciones en vivo de conversión de TXT a EMF" sectionDescription="[Convertir TXT a EMF](https://products.aspose.app/cells/conversion/txt-to-emf) ahora mismo visitando nuestro sitio web de demostraciones en vivo. La demostración en vivo tiene los siguientes beneficios" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No es necesario descargar Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No es necesario escribir ningún código." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Simplemente cargue su archivo TXT, se convertirá instantáneamente a EMF." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Obtendrá el enlace de descarga." >}}

    {{% blocks/products/pf/agp/content h2="C++ Biblioteca de manipulación de archivos de Excel" %}}

 Excel API se puede usar para crear, editar, convertir y representar formatos de Microsoft Excel en diferentes formatos. Además, se puede usar para gráficos completos, informes escalables y cálculos confiables dentro de las aplicaciones de software. Aspose.Cells es un API independiente y no requiere ningún software como Microsoft u OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="TXT" readMoreLink="https://docs.fileformat.com/word-processing/txt/" >}}

Un archivo con extensión .TXT representa un documento de texto que contiene texto sin formato en forma de líneas. Los párrafos de un documento de texto se reconocen mediante retornos de carro y se utilizan para organizar mejor el contenido del archivo. Un documento de texto estándar se puede abrir en cualquier editor de texto o aplicación de procesamiento de texto en diferentes sistemas operativos. Todo el texto contenido en dicho archivo está en formato legible por humanos y representado por una secuencia de caracteres.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="EMF" readMoreLink="https://docs.fileformat.com/image/emf/" >}}

El formato de metarchivo mejorado (EMF) almacena imágenes gráficas de forma independiente del dispositivo. Los metarchivos de EMF se componen de registros de longitud variable en orden cronológico que pueden representar la imagen almacenada después de analizarla en cualquier dispositivo de salida. Estos registros de longitud variable pueden ser definiciones de objetos encerrados, comandos para dibujar y propiedades gráficas críticas para representar la imagen con precisión. Cuando un dispositivo abre un metarchivo EMF utilizando su propio entorno de gráficos, las proporciones, dimensiones, colores y otras propiedades gráficas de la imagen original siguen siendo las mismas independientemente de la plataforma del dispositivo de apertura.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}