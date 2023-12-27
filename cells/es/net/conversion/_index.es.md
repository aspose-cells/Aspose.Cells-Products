---
title:  Microsoft Conversión de archivos de Excel a través de C#
description: Aspose.Cells for .NET biblioteca. Convierta EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL, JPG, PNG y más formatos con solo unas pocas líneas de código C#.
keywords: [C# Aspose.Cells., excel to pdf., excel to json., txt to sql., csv to json., json to pdf., xml to excel and Convert files between various formats in C#]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Conversión de formato Excel via .NET" h2="Importe y exporte archivos de Excel como formatos de hoja de cálculo, web, imágenes y diseño fijo" >}}

{{% blocks/products/pf/feature-page-summary %}}
.NET La biblioteca de Excel acelera los procesos de conversión y programación de hojas de cálculo y admite formatos populares, incluidos XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, 07619348. 1. También permite exportar archivos de Excel a PDF, XPS, HTML, MHTML, Plain Formatos de texto e imágenes populares como TIFF, JPG, PNG, BMP y SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Convierta Excel a XLSX, ODS, SXC y FODS" %}}
 La interconversión de formato de hoja de cálculo solo requiere cargar una hoja de cálculo con una instancia de[Libro de trabajo](https://reference.aspose.com/cells/net/aspose.cells/workbook) y guardarlo nuevamente en el formato deseado mientras selecciona el valor apropiado de[Guardar formato](https://reference.aspose.com/cells/net/aspose.cells/saveformat) enumeración.
{{% blocks/products/pf/feature-page-code h3="C# Código para la conversión de formato de archivo de Excel" %}}

```cs
// load the template file
var workbook = new Aspose.Cells.Workbook("template.xls");
// save as XLSX, ODS, SXC & FODS formats
workbook.Save("output.xlsx", Aspose.Cells.SaveFormat.Xlsx);
workbook.Save("output.ods", Aspose.Cells.SaveFormat.Ods);
workbook.Save("output.scx", Aspose.Cells.SaveFormat.Sxc);
workbook.Save("output.fods", Aspose.Cells.SaveFormat.Fods);
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Convierta Excel a PDF, XPS, HTML y MD" %}}
 Hay clases especializadas disponibles para controlar el proceso de conversión para formatos de salida específicos, como[Opciones de guardar PDF](https://reference.aspose.com/cells/net/aspose.cells/pdfsaveoptions) para exportar archivos de Excel como PDF,[XpsGuardarOpciones](https://reference.aspose.com/cells/net/aspose.cells/xpssaveoptions) para conversión de Excel a XPS,[HtmlSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/htmlsaveoptions) para representar Excel como HTML y[Opciones de ahorro de rebajas](https://reference.aspose.com/cells/net/aspose.cells/markdownsaveoptions) para la conversión de Excel a Markdown.
{{% blocks/products/pf/feature-page-code h3="C# Código para Excel al PDF y Formatos Web" %}}

```cs
// load template Excel file from disc
var book = new Aspose.Cells.Workbook("template.xlsx");
// save Excel in PDF/A-1a format
book.Save("output.pdf", new Aspose.Cells.PdfSaveOptions() { Compliance = PdfComplianceVersion.PdfA1a });
// save Excel in XPS with 1 page per worksheet
book.Save("output.xps", new Aspose.Cells.XpsSaveOptions() { OnePagePerSheet = true });
// save Excel in HTML with images as Base64
book.Save("output.html", new Aspose.Cells.HtmlSaveOptions() { ExportImagesAsBase64 = true });
// save Excel in Markdown (MD) while retaining cell formatting
book.Save("output.md", new Aspose.Cells.MarkdownSaveOptions() { FormatStrategy = Cells.CellValueFormatStrategy.CellStyle });
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="Convertir JSON a Excel y Excel a JSON" %}}
 Los datos JSON se pueden importar a una instancia de[Cells](https://reference.aspose.com/cells/net/aspose.cells/cells) clase con la ayuda de[JsonUtility.Importar datos](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/importdata) para su posterior procesamiento o simple conversión a cualquiera de los formatos soportados. Similarmente,[Hoja de cálculo](https://reference.aspose.com/cells/net/aspose.cells/worksheet) Los datos se pueden exportar como JSON creando un[Rango](https://reference.aspose.com/cells/net/aspose.cells/range) o celdas y llamando al[JsonUtility.ExportRangeToJson](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/exportrangetojson) método.
{{% blocks/products/pf/feature-page-code h3="C# Código para conversión de JSON a Excel" %}}
```cs
// create a Workbook object
var workbook = new Cells.Workbook();
var worksheet = workbook.Worksheets[0];
// read JSON data from file
string jsonInput = File.ReadAllText("Data.json");
// set JsonLayoutOptions to treat Arrays as Table
var options = new Cells.Utility.JsonLayoutOptions();
options.ArrayAsTable = true;
// import JSON data to worksheet starting at cell A1
Cells.Utility.JsonUtility.ImportData(jsonInput, worksheet.Cells, 0, 0, options);
// save resultant file in XLSX format
workbook.Save("output.xlsx", Cells.SaveFormat.Auto); 
```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Código C# para conversión de Excel a JSON" %}}
```cs
// load XLSX file with an instance of Workbook
var workbook = new Workbook("template.xlsx", new LoadOptions(Cells.LoadFormat.Auto));
// access CellsCollection of the worksheet containing data to be converted
var cells = workbook.Worksheets[0].Cells;
// create & set ExportRangeToJsonOptions for advanced options
var exportOptions = new Utility.ExportRangeToJsonOptions();
// create a range of cells containing data to be exported
var range = cells.CreateRange(0, 0, cells.LastCell.Row + 1, cells.LastCell.Column + 1);
// export range as JSON data
string jsonData = Cells.Utility.JsonUtility.ExportRangeToJson(range, exportOptions);
// write data file to disc in JSON format
System.IO.File.WriteAllText("output.json", jsonData); 
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Convierta hojas de cálculo de Excel a JPG, BMP, PNG y GIF" %}}
 Cada hoja de cálculo de un archivo Excel se puede convertir a diferentes formatos de imagen establecidos por el[ImageOrPrintOptions.ImageType](https://reference.aspose.com/cells/net/aspose.cells.rendering/imageorprintoptions/properties/imagetype) propiedad. El valor predeterminado es `ImageFormat.Bmp`.
{{% blocks/products/pf/feature-page-code h3="C# Código para conversión de Excel a imagen" %}}
```cs
// load template spreadsheet
var workbook = new Aspose.Cells.Workbook("template.xlsx");
// create & set an instance of ImageOrPrintOptions
var options = new Aspose.Cells.Rendering.ImageOrPrintOptions();
options.OnePagePerSheet = true;
// set output image format
options.ImageType = Aspose.Cells.Drawing.ImageType.Jpeg;
// create SheetRender for first worksheet in the collection
var render = new Aspose.Cells.Rendering.SheetRender(workbook.Worksheets[0], options);
// render worksheet to image
render.ToImage(0, "output.jpg");
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Convertir Excel a Word y PowerPoint" %}}
Es posible cargar cualquier hoja de cálculo y convertirla a archivos Word DOCX y PowerPoint PPTX mientras se usa[Opciones de DocxSave](https://reference.aspose.com/cells/net/aspose.cells/docxsaveoptions) & [PptxGuardarOpciones](https://reference.aspose.com/cells/net/aspose.cells/pptxsaveoptions) clases como se demuestra a continuación.
{{% blocks/products/pf/feature-page-code h3="Código C# para conversión de Excel a Word y conversión PowerPoint" %}}
```cs
// load the template file
var workbook = new Aspose.Cells.Workbook("template.xlsx");
// save spreadsheet as DOCX
workbook.Save("output.docx", new Aspose.Cells.DocxSaveOptions());
// save spreadsheet as PPTX
workbook.Save("output.pptx", new Aspose.Cells.PptxSaveOptions());
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
