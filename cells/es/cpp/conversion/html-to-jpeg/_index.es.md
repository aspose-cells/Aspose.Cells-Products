---
title: Convierta HTML a JPEG a través de la aplicación C++ 
weight: 7270
url: /es/cpp/conversion/html-to-jpeg/ 
description: Ejemplo de código de conversión C++ para documento HTML a formato JPEG. Los programadores pueden usar este código fuente para la conversión por lotes de HTML a JPEG dentro de cualquier aplicación C++.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Convierte HTML a JPEG a través de C++" h2="Conversión de HTML a JPEG de alto rendimiento utilizando la biblioteca C++ sin necesidad de instalar Microsoft Excel, OpenOffice o Adobe Acrobat." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="JPEG" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="HTML" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Cómo convertir HTML a JPEG usando C++" %}}

 Para convertir HTML a JPEG, usaremos
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

{{% blocks/products/pf/agp/feature-section-col title="Pasos para convertir HTML a JPEG a través de C++" %}}

{{% blocks/products/pf/agp/text %}}

 Los desarrolladores de C++ pueden convertir fácilmente un archivo HTML a JPEG con solo unas pocas líneas de código.

{{% /blocks/products/pf/agp/text %}}

1. Cargue el archivo HTML usando Factory::CreateIWorkbook.1. Seleccione la primera hoja de trabajo.1. Establecer opciones (JPEG).1. Iterar a través de cada página de la hoja y renderizar.1. Abra el archivo JPEG en un programa compatible.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos del sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Antes de ejecutar el código de ejemplo de conversión C++, asegúrese de cumplir los siguientes requisitos previos.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows o un sistema operativo compatible con C++ Runtime Environment para Windows de 32 bits, Windows de 64 bits y Linux de 64 bits.- Aspose.Cells para C++ DLL a la que se hace referencia en su proyecto.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Código fuente de conversión de HTML a JPEG C++" offSpacer="" %}}

```cs
// Ruta del directorio de salida.
StringPtr outDir = new String("OutputDirectoryPath");

// Cargue el HTML.
intrusive_ptr<Aspose::Cells::IWorkbook> workbook = Factory::CreateIWorkbook(u"sourceFile.html");

// Acceda a la primera hoja de trabajo.
intrusive_ptr<Aspose::Cells::IWorksheet> worksheet = workbook->GetIWorksheets()->GetObjectByIndex(0);

// Crear imagen o objeto de opciones de impresión.
intrusive_ptr<Aspose::Cells::Rendering::IImageOrPrintOptions> imgOptions = Factory::CreateIImageOrPrintOptions();

// Especifique el formato de la imagen.
imgOptions->SetImageFormat(Aspose::Cells::Systems::Drawing::Imaging::ImageFormat::GetJpeg());

// Especificar resolución horizontal y vertical
imgOptions->SetHorizontalResolution(200);
imgOptions->SetVerticalResolution(200);

// Renderice la hoja con respecto a la imagen especificada o las opciones de impresión.
intrusive_ptr<Aspose::Cells::Rendering::ISheetRender> sr = Factory::CreateISheetRender(worksheet, imgOptions);

// Obtener recuento de páginas.
Aspose::Cells::Systems::Int32 pageCount = sr->GetPageCount();

// Cree un objeto generador de cadenas para concatenaciones de cadenas.
intrusive_ptr<Aspose::Cells::Systems::Text::StringBuilder> sb = new Aspose::Cells::Systems::Text::StringBuilder();

// Renderice cada página a imagen jpeg una por una.
for (int i = 0; i Clear();
	sb->Append(outDir);
	sb->Append((StringPtr)new String("outputConvertingWorksheetToImageJPEG_"));
	sb->Append(i);
	sb->Append((StringPtr)new String(".jpeg"));

	// Obtenga la ruta de la imagen de salida.
	StringPtr outputJPEG = sb->ToString();

	// Convierta la hoja de trabajo en una imagen jpeg.
	sr->ToImage(i, outputJPEG);
}


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Demostraciones en vivo de conversión de HTML a JPEG" sectionDescription="[Convertir HTML a JPEG](https://products.aspose.app/cells/conversion/html-to-jpeg) ahora mismo visitando nuestro sitio web de demostraciones en vivo. La demostración en vivo tiene los siguientes beneficios" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No es necesario descargar Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No es necesario escribir ningún código." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Simplemente cargue su archivo HTML, se convertirá instantáneamente a JPEG." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Obtendrá el enlace de descarga." >}}

    {{% blocks/products/pf/agp/content h2="C++ Biblioteca de manipulación de archivos de Excel" %}}

 Excel API se puede usar para crear, editar, convertir y representar formatos de Microsoft Excel en diferentes formatos. Además, se puede usar para gráficos completos, informes escalables y cálculos confiables dentro de las aplicaciones de software. Aspose.Cells es un API independiente y no requiere ningún software como Microsoft u OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="HTML" readMoreLink="https://docs.fileformat.com/web/html/" >}}

HTML (Hyper Text Markup Language) es la extensión de las páginas web creadas para mostrarse en los navegadores. Conocido como el lenguaje de la web, HTML ha evolucionado con los requisitos de nuevos requisitos de información para mostrarse como parte de las páginas web. La última variante se conoce como HTML 5 que brinda mucha flexibilidad para trabajar con el lenguaje. Las páginas HTML se reciben del servidor, donde están alojadas, o también se pueden cargar desde el sistema local. Cada página HTML se compone de elementos HTML como formularios, texto, imágenes, animaciones, enlaces, etc. Estos elementos están representados por etiquetas como img, a, p y varias otras donde cada etiqueta tiene un inicio y un final. También puede incrustar aplicaciones escritas en lenguajes de secuencias de comandos como JavaScript y hojas de estilo (CSS) para la representación general del diseño.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="JPEG" readMoreLink="https://docs.fileformat.com/image/jpeg/" >}}

Un JPEG es un tipo de formato de imagen que se guarda mediante el método de compresión con pérdida. La imagen de salida, como resultado de la compresión, es un equilibrio entre el tamaño de almacenamiento y la calidad de la imagen. Los usuarios pueden ajustar el nivel de compresión para lograr el nivel de calidad deseado y al mismo tiempo reducir el tamaño de almacenamiento. La calidad de la imagen se ve afectada de manera insignificante si se aplica una compresión de 10:1 a la imagen. Cuanto mayor sea el valor de compresión, mayor será la degradación de la calidad de la imagen. El formato de archivo de imagen JPEG fue estandarizado por el Grupo Conjunto de Expertos Fotográficos y, de ahí, el nombre JPEG. El formato ha sido el elegido para almacenar y transmitir imágenes fotográficas en la web. Casi todos los sistemas operativos ahora tienen visores que admiten la visualización de imágenes JPEG, que a menudo también se almacenan con la extensión JPG. Incluso los navegadores web admiten la visualización de imágenes JPEG.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones admitidas" subTitle="También puede convertir HTML en muchos otros formatos de archivo, incluidos algunos de los que se enumeran a continuación." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-bmp/" name="HTML A BMP" description="Imagen de mapa de bits" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-csv/" name="HTML A CSV" description="Valores Separados por Comas" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-dif/" name="HTML A DIF" description="Formato de intercambio de datos" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-emf/" name="HTML A CEM" description="Formato de metarchivo mejorado" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-gif/" name="HTML A GIF" description="Formato de intercambio gráfico" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-mhtml/" name="HTML A MHTML" description="Formato de archivo de página web" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-ods/" name="HTML A SAO" description="Archivo de hoja de cálculo OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-pdf/" name="HTML A PDF" description="Formato de Documento Portable" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-png/" name="HTML A PNG" description="Gráficos de red portátiles" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-svg/" name="HTML A SVG" description="gráficas vectoriales escalables" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-tiff/" name="HTML A TIFF" description="Formato de imagen etiquetada" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-tsv/" name="HTML A TSV" description="Valores separados por tabuladores" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-xls/" name="HTML A XLS" description="Formato binario de Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-xlsb/" name="HTML A XLSB" description="Archivo de libro de Excel binario" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-xlsm/" name="HTML A XLSM" description="Archivo de hoja de cálculo" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-xlsx/" name="HTML A XLSX" description="Archivo de Excel OOXML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-xltm/" name="HTML A XLTM" description="Plantilla de Excel habilitada para macros" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-xltx/" name="HTML A XLTX" description="Plantilla de Excel OpenXML de Office" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-xps/" name="HTML A XPS" description="Especificaciones de papel XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}