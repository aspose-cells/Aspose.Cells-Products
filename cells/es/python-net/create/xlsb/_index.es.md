---
title: Crear XLSB - Crear archivo XLSB en Python
description: Aspose Excel. Python Excel. Python Cree un archivo XLSB de forma rápida y sencilla con Aspose.Cells. Genere un archivo XLSB utilizando la biblioteca de Excel Python. Cree XLSB en la biblioteca de Excel Python. Python XLSB Creador.
keywords: [Aspose Python Excel., Python Aspose.Cells., Python Create XLSB file., Generate XLSB file in Python Excel Library., Create XLSB file using Python Excel Library., Write data to XLSB file via Python Excel Library., Create a XLSB file in Python Excel Library., Python Generate a XLSB file., Python XLSB Creater]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Crear archivo XLSB en la biblioteca de Excel Python" h2="Biblioteca Excel Python de alta velocidad para crear archivos XLSB. Utilice nuestra conversión de Excel API para desarrollar software independiente de plataforma de alto nivel en Python." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-python-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSB" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Python" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-python-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/python-net" installationsDocsLink="https://docs.aspose.com/cells/python-net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://releases.aspose.com/cells/python-net/" learnAsLink="https://docs.aspose.com/cells/python-net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Cree un archivo XLSB usando la biblioteca de Excel Python" %}}

¿Cómo crear el archivo XLSB? Con Aspose.Cells for Python a través de la biblioteca de Excel NET, puede crear fácilmente el archivo XLSB mediante programación con unas pocas líneas de código.[Aspose.Cells for Python](https://pypi.org/project/aspose-cells-python/)es capaz de crear aplicaciones multiplataforma con la capacidad de generar, modificar, convertir, renderizar e imprimir todos los archivos de Excel. Python Excel API no solo convierte entre formatos de hojas de cálculo, sino que también puede representar archivos de Excel como imágenes, PDF, HTML, ODS, CSV, SVG, JSON, WORD, PPT y más, lo que lo convierte en una opción perfecta para intercambiar documentos en formatos estándar de la industria.

{{% /blocks/products/pf/agp/content %}}



{{% blocks/products/pf/agp/content h2="Cómo crear XLSB en la biblioteca de Excel Python" %}}

{{% blocks/products/pf/agp/text %}}

 Es fácil para los desarrolladores crear, cargar, modificar y convertir archivos XLSB ejecutando diferentes aplicaciones de informes para el procesamiento de datos en solo unas pocas líneas de código.

{{% /blocks/products/pf/agp/text %}}

1.  Crear una instancia de clase de libro de trabajo.
1.  Acceda a la primera hoja de trabajo del libro de trabajo.
1. Obtenga las celdas deseadas de la hoja de trabajo e ingrese el valor en las celdas.
1.  Utilice el método Guardar para guardar el libro como archivo XLSB.

{{% blocks/products/pf/agp/code-block title="El código de muestra muestra cómo crear el archivo XLSB en la biblioteca de Excel Python." offSpacer="" %}}

```cs

from aspose import pycore
from aspose.cells import Workbook, SaveFormat, FileFormatType

# Create Workbook object.
workbook = Workbook()

# Access the first worksheet of the workbook.
worksheet = workbook.worksheets[0]

# Get the desired cell(s) of the worksheet and input the value into the cell(s).
worksheet.cells.get("A1").put_value("ColumnA")
worksheet.cells.get("B1").put_value("ColumnB")
worksheet.cells.get("A2").put_value("ValueA")
worksheet.cells.get("B2").put_value("ValueB")

# Save the workbook as XLSB file.
workbook.save("output.xlsb")

```

{{% /blocks/products/pf/agp/code-block %}}
{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="Python Biblioteca de Excel para crear el archivo XLSB" %}}

Alojamos nuestros paquetes Python en repositorios PyPi.

{{% blocks/products/pf/agp/text %}}
 Instalar Aspose.Cells for Python desde<a href="https://pypi.org/project/aspose-cells-python/">pypi</a> , use el comando como:<code>$ pip install aspose-cells-python</code>.
{{% /blocks/products/pf/agp/text %}}

{{% blocks/products/pf/agp/text %}}
 Y también puedes seguir el[instrucciones paso a paso](https://docs.aspose.com/cells/python-net/getting-started/) sobre cómo instalar "Aspose.Cells for Python via .NET" en su entorno de desarrollador.
{{% /blocks/products/pf/agp/text %}}
{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="Requisitos del sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Python es independiente de la plataforma API y se puede usar en cualquier plataforma (Windows, Linux), solo asegúrese de que el sistema tenga[Python](https://www.python.org/downloads/) 3.7 o superior.
 
{{% /blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->
    {{< blocks/products/pf/agp/about-file-section >}}
        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSB" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsb/" >}}El formato de archivo XLSB especifica el formato de archivo binario de Excel, que es una colección de registros y estructuras que especifican el contenido del libro de Excel. El contenido puede incluir tablas de números no estructuradas o semiestructuradas, texto o números y texto, fórmulas, conexiones de datos externos, gráficos e imágenes. A diferencia de XLSX (que se basa en el formato de archivo Open XML), XLSB representa un archivo binario de libro de Excel. Los archivos XLSB se pueden leer y escribir más rápido, lo que los hace útiles para trabajar con archivos grandes. XLSB rara vez se usa para almacenar libros de trabajo, ya que XLSX (y anteriormente XLS) son los formatos de archivo seleccionados por el usuario más comunes para guardar libros de trabajo. Se puede abrir mediante Microsoft Office 2007 y superior.{{< /blocks/products/pf/agp/i18n/about-file-text >}}
    {{< /blocks/products/pf/agp/about-file-section >}}
<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Otra generación de hojas de cálculo admitida" subTitle="También puede crear otros formatos de Excel Microsoft, incluidos algunos que se enumeran a continuación." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-net/create/xls/" name="XLS" description="Microsoft Hoja de cálculo de Excel (heredada)" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-net/create/xlsx/" name="XLSX" description="Abrir libro XML" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-net/create/xlsb/" name="XLSB" description="Libro binario de Excel" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-net/create/xlsm/" name="XLSM" description="Hoja de cálculo habilitada para macros" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-net/create/xlt/" name="XLT" description="Plantilla Excel 97 - 2003" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-net/create/xltx/" name="XLTX" description="Plantilla de Excel" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-net/create/xltm/" name="XLTM" description="Plantilla habilitada para macros de Excel" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-net/create/csv/" name="CSV" description="Valores Separados por Comas" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-net/create/tsv/" name="TSV" description="Valores separados por tabulaciones" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-net/create/ods/" name="ODS" description="Hoja de cálculo de OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-net/create/pdf/" name="PDF" description="Formato de Documento Portable" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-net/create/html/" name="HTML" description="Lenguaje de marcado de hipertexto" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
