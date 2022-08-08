---
title: Conversión de archivos de Microsoft Excel a través de Python 
url: /es/python/conversion/
description: Convierta Excel XLS, XLSX, ODS, CSV a PDF, XPS, HTML, JPEG, HTML y muchos otros formatos populares con solo unas pocas líneas de código Python.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Conversión de formato Microsoft<sup>&reg;</sup> Excel a través de Python" h2="Importe y exporte archivos de Excel como hojas de cálculo, web, imágenes y formatos de diseño fijo" >}}

{{% blocks/products/pf/feature-page-summary %}}
Python La biblioteca de Excel acelera la programación de hojas de cálculo y los procesos de conversión a la vez que admite formatos populares como XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML y ODS. También permite exportar archivos de Excel a PDF, XPS, HTML, MHTML, texto sin formato y formatos de imagen populares como TIFF, JPG, PNG, BMP y SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Convierta Excel a XLSX, ODS, SXC y FODS" %}}
La interconversión del formato de hoja de cálculo solo requiere cargar una hoja de cálculo con una instancia de [Libro de trabajo](https://reference.aspose.com/cells/python/asposecells.api/Workbook) y guardar de nuevo en el formato deseado mientras selecciona el valor apropiado de [Guardar formato](https://reference.aspose.com/cells/python/asposecells.api/saveformat) enumeración.
{{% blocks/products/pf/feature-page-code h3="Python Código para conversión de formato de archivo de Excel" %}}

```cs
// cargar el archivo de plantilla
workbook = Workbook("Book1.xls")
  
// guardar como formatos XLSX, ODS, SXC y FODS
workbook.save("output.xlsx", SaveFormat.XLSX);
workbook.save("output.ods", SaveFormat.ODS);
workbook.save("output.scx", SaveFormat.SXC);
workbook.save("output.fods", SaveFormat.FODS);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Convierta Excel a PDF, XPS, HTML y MD" %}}
Hay clases especializadas disponibles para controlar el proceso de conversión para formatos de salida específicos como [PdfGuardarOpciones](https://reference.aspose.com/cells/python/asposecells.api/PdfSaveOptions) para exportar archivos de Excel como PDF, [XpsSaveOpciones](https://reference.aspose.com/cells/python/asposecells.api/XpsSaveOptions) para la conversión de Excel a XPS, [HtmlSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/HtmlSaveOptions) para renderizar Excel como HTML y [MarkdownSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/MarkdownSaveOptions) para la conversión de Excel a Markdown. 
{{% blocks/products/pf/feature-page-code h3="Python Código para Excel a PDF y formatos web" %}}

```cs
// cargar el archivo Excel de la plantilla desde el disco
book = Workbook("template.xlsx")

// guardar Excel en formato PDF_A_1_B
pdfOptions = PdfSaveOptions()
pdfOptions.setCompliance(PdfCompliance.PDF_A_1_B)
book.save("output.pdf", pdfOptions);

// guarde Excel en XPS con 1 página por hoja de trabajo
xpsOptions = XpsSaveOptions()
xpsOptions.setOnePagePerSheet(True)
book.save("output.xps", xpsOptions);

// guardar Excel en HTML con imágenes como Base64
htmlOptions = HtmlSaveOptions()
htmlOptions.setExportImagesAsBase64(True)
book.save("output.html", htmlOptions);

// guarde Excel en Markdown (MD) mientras conserva el formato de celda
mdOptions = MarkdownSaveOptions()
mdOptions.setFormatStrategy(CellValueFormatStrategy.CELL_STYLE)
book.save("output.md", mdOptions);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="Convierta JSON a Excel y Excel a JSON" %}}
Los desarrolladores de Python pueden cargar y convertir fácilmente archivos JSON a Excel con solo unas pocas líneas de código. Del mismo modo, los datos de Excel se pueden exportar a datos JSON.
{{% blocks/products/pf/feature-page-code h3="Python Código para la conversión de JSON a Excel" %}}
```cs
//Cargue su archivo json fuente
workbook = Workbook("Data.json")
//guardar archivo en formato xlsx
workbook.save("output.xlsx")

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python Código para la conversión de Excel a JSON" %}}
```cs
//Cargue su archivo fuente xlsx
workbook = Workbook("input.xlsx")
//guardar archivo en formato json
workbook.save("Data.json")

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Convierta hojas de cálculo de Excel a JPG, BMP, PNG y GIF" %}}
Cada hoja de trabajo de un archivo de Excel se puede convertir a diferentes formatos de imagen, llame [ImageOrPrintOptions](https://reference.aspose.com/cells/python/asposecells.api/ImageOrPrintOptions).setImageFormat para establecer el formato de la imagen. 
{{% blocks/products/pf/feature-page-code h3="Python Código para conversión de Excel a imagen" %}}
```cs
// cargar plantilla de hoja de cálculo
workbook = Workbook("template.xlsx")
// crear y establecer una instancia de ImageOrPrintOptions
options = ImageOrPrintOptions()
// establecer el formato de la imagen de salida
options.setImageFormat(ImageFormat.getPng())
// crear SheetRender para la primera hoja de trabajo en la colección
sheet = workbook.getWorksheets().get(0)
sr = SheetRender(sheet, options)
// renderizar hoja de trabajo a imagen
sr.toImage(0, "output.jpg")

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Convertir Excel a Word y PowerPoint" %}}
Es posible cargar cualquier hoja de cálculo y convertirla a archivos Word DOCX y PowerPoint PPTX mientras se usa [DocxSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/DocxSaveOptions) & [PptxGuardarOpciones](https://reference.aspose.com/cells/python/asposecells.api/PptxSaveOptions) clases como se muestra a continuación.
{{% blocks/products/pf/feature-page-code h3="Python código para la conversión de Excel a Word y PowerPoint" %}}
```cs
// cargar el archivo de plantilla
workbook = Workbook("template.xlsx")

// guardar hoja de cálculo como DOCX
docxOptions = DocxSaveOptions()
workbook.save("output.docx", docxOptions)

// guardar hoja de cálculo como PPTX
pptxOptions = PptxSaveOptions()
workbook.save("output.pptx", pptxOptions)

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}