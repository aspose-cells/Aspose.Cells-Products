---
title: Conversión de archivos de Microsoft Excel a través de C# 
url: /es/net/conversion/
description: Convierta Excel XLS, XLSX, ODS, CSV a PDF, XPS, HTML, JPEG, HTML y muchos otros formatos populares con solo unas pocas líneas de código C#.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Conversión de formato Microsoft<sup>&reg;</sup> Excel a través de .NET" h2="Importe y exporte archivos de Excel como hojas de cálculo, web, imágenes y formatos de diseño fijo" >}}

{{% blocks/products/pf/feature-page-summary %}}
.NET La biblioteca de Excel acelera la programación de hojas de cálculo y los procesos de conversión a la vez que admite formatos populares como XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML y ODS. También permite exportar archivos de Excel a PDF, XPS, HTML, MHTML, texto sin formato y formatos de imagen populares como TIFF, JPG, PNG, BMP y SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Convierta Excel a XLSX, ODS, SXC y FODS" %}}
La interconversión del formato de hoja de cálculo solo requiere cargar una hoja de cálculo con una instancia de [Libro de trabajo](https://reference.aspose.com/cells/net/aspose.cells/workbook) y guardar de nuevo en el formato deseado mientras selecciona el valor apropiado de [Guardar formato](https://reference.aspose.com/cells/net/aspose.cells/saveformat) enumeración.
{{% blocks/products/pf/feature-page-code h3="C# Código para conversión de formato de archivo de Excel" %}}

```cs
// cargar el archivo de plantilla
var workbook = new Aspose.Cells.Workbook("template.xls");
// guardar como formatos XLSX, ODS, SXC y FODS
workbook.Save("output.xlsx", Aspose.Cells.SaveFormat.Xlsx);
workbook.Save("output.ods", Aspose.Cells.SaveFormat.Ods);
workbook.Save("output.scx", Aspose.Cells.SaveFormat.Sxc);
workbook.Save("output.fods", Aspose.Cells.SaveFormat.Fods);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Convierta Excel a PDF, XPS, HTML y MD" %}}
Hay clases especializadas disponibles para controlar el proceso de conversión para formatos de salida específicos como [PdfGuardarOpciones](https://reference.aspose.com/cells/net/aspose.cells/pdfsaveoptions) para exportar archivos de Excel como PDF, [XpsSaveOpciones](https://reference.aspose.com/cells/net/aspose.cells/xpssaveoptions) para la conversión de Excel a XPS, [HtmlSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/htmlsaveoptions) para renderizar Excel como HTML y [MarkdownSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/markdownsaveoptions) para la conversión de Excel a Markdown. 
{{% blocks/products/pf/feature-page-code h3="C# Código para Excel a PDF y formatos web" %}}

```cs
// cargar el archivo Excel de la plantilla desde el disco
var book = new Aspose.Cells.Workbook("template.xlsx");
// guardar Excel en formato PDF/A-1a
book.Save("output.pdf", new Aspose.Cells.PdfSaveOptions() { Compliance = PdfComplianceVersion.PdfA1a });
// guarde Excel en XPS con 1 página por hoja de trabajo
book.Save("output.xps", new Aspose.Cells.XpsSaveOptions() { OnePagePerSheet = true });
// guardar Excel en HTML con imágenes como Base64
book.Save("output.html", new Aspose.Cells.HtmlSaveOptions() { ExportImagesAsBase64 = true });
// guarde Excel en Markdown (MD) mientras conserva el formato de celda
book.Save("output.md", new Aspose.Cells.MarkdownSaveOptions() { FormatStrategy = Cells.CellValueFormatStrategy.CellStyle });

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="Convierta JSON a Excel y Excel a JSON" %}}
Los datos JSON se pueden importar a una instancia de [Cells](https://reference.aspose.com/cells/net/aspose.cells/cells) clase con la ayuda de [JsonUtility.ImportData](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/importdata) para su posterior procesamiento o simple conversión a cualquiera de los formatos admitidos. Similarmente, [Hoja de cálculo](https://reference.aspose.com/cells/net/aspose.cells/worksheet) los datos se pueden exportar como JSON creando un [Distancia](https://reference.aspose.com/cells/net/aspose.cells/range) o celdas y llamando al [JsonUtility.ExportRangeToJson](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/exportrangetojson) método.
{{% blocks/products/pf/feature-page-code h3="C# Código para la conversión de JSON a Excel" %}}
```cs
// crear un objeto de libro de trabajo
var workbook = new Cells.Workbook();
var worksheet = workbook.Worksheets[0];
// leer datos JSON del archivo
string jsonInput = File.ReadAllText("Data.json");
// establecer JsonLayoutOptions para tratar matrices como tabla
var options = new Cells.Utility.JsonLayoutOptions();
options.ArrayAsTable = true;
// importar datos JSON a la hoja de trabajo a partir de la celda A1
Cells.Utility.JsonUtility.ImportData(jsonInput, worksheet.Cells, 0, 0, options);
// guardar el archivo resultante en formato XLSX
workbook.Save("output.xlsx", Cells.SaveFormat.Auto); 

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Código para la conversión de Excel a JSON" %}}
```cs
// cargue el archivo XLSX con una instancia de Workbook
var workbook = new Workbook("template.xlsx", new LoadOptions(Cells.LoadFormat.Auto));
// acceda a CellsCollection de la hoja de cálculo que contiene los datos que se van a convertir
var cells = workbook.Worksheets[0].Cells;
// crear y configurar ExportRangeToJsonOptions para opciones avanzadas
var exportOptions = new Utility.ExportRangeToJsonOptions();
// crear un rango de celdas que contengan datos para exportar
var range = cells.CreateRange(0, 0, cells.LastCell.Row + 1, cells.LastCell.Column + 1);
// rango de exportación como datos JSON
string jsonData = Cells.Utility.JsonUtility.ExportRangeToJson(range, exportOptions);
// escribir archivo de datos en disco en formato JSON
System.IO.File.WriteAllText("output.json", jsonData); 

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Convierta hojas de cálculo de Excel a JPG, BMP, PNG y GIF" %}}
Cada hoja de trabajo de un archivo de Excel se puede convertir a diferentes formatos de imagen establecidos por el [ImageOrPrintOptions.ImageType](https://reference.aspose.com/cells/net/aspose.cells.rendering/imageorprintoptions/properties/imagetype) propiedad. El valor predeterminado es `ImageFormat.Bmp`.
{{% blocks/products/pf/feature-page-code h3="C# Código para conversión de Excel a imagen" %}}
```cs
// cargar plantilla de hoja de cálculo
var workbook = new Aspose.Cells.Workbook("template.xlsx");
// crear y establecer una instancia de ImageOrPrintOptions
var options = new Aspose.Cells.Rendering.ImageOrPrintOptions();
options.OnePagePerSheet = true;
// establecer el formato de la imagen de salida
options.ImageType = Aspose.Cells.Drawing.ImageType.Jpeg;
// crear SheetRender para la primera hoja de trabajo en la colección
var render = new Aspose.Cells.Rendering.SheetRender(workbook.Worksheets[0], options);
// renderizar hoja de trabajo a imagen
render.ToImage(0, "output.jpg");

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Convertir Excel a Word y PowerPoint" %}}
Es posible cargar cualquier hoja de cálculo y convertirla a archivos Word DOCX y PowerPoint PPTX mientras se usa [DocxSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/docxsaveoptions) & [PptxGuardarOpciones](https://reference.aspose.com/cells/net/aspose.cells/pptxsaveoptions) clases como se muestra a continuación.
{{% blocks/products/pf/feature-page-code h3="C# código para la conversión de Excel a Word y PowerPoint" %}}
```cs
// cargar el archivo de plantilla
var workbook = new Aspose.Cells.Workbook("template.xlsx");
// guardar hoja de cálculo como DOCX
workbook.Save("output.docx", new Aspose.Cells.DocxSaveOptions());
// guardar hoja de cálculo como PPTX
workbook.Save("output.pptx", new Aspose.Cells.PptxSaveOptions());

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}