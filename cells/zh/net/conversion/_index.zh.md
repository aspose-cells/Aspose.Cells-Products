---
title: Microsoft Excel 文件转换通过 C#
description: Aspose.Cells for .NET 图书馆。只需几行 C# 代码即可转换 EXCEL、JSON、PDF、XML、HTML、TXT、TSV、CSV、SQL、JPG、PNG 等格式。
keywords: [C# Aspose.Cells., excel to pdf., excel to json., txt to sql., csv to json., json to pdf., xml to excel and Convert files between various formats in C#]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel 格式转换 via .NET" h2="将 Excel 文件导入和导出为电子表格、Web、图像和固定布局格式" >}}

{{% blocks/products/pf/feature-page-summary %}}
.NET Excel 库可加快电子表格编程和转换过程，同时支持流行格式，包括 XLS、XLSX、XLSM、XLSB、XLTX、XLTM、CSV、SpreadsheetML、ODS。还允许将 Excel 文件导出到 PDF、XPS、HTML、MHTML、Plain文本和流行的图像格式，例如 TIFF、JPG、PNG、BMP 和 SVG。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="将 Excel 转换为 XLSX、ODS、SXC 和 FODS" %}}
电子表格格式的相互转换只需要加载带有实例的电子表格[练习册](https://reference.aspose.com/cells/net/aspose.cells/workbook)并以所需的格式保存，同时从中选择适当的值[保存格式](https://reference.aspose.com/cells/net/aspose.cells/saveformat)枚举。
{{% blocks/products/pf/feature-page-code h3="C# Excel文件格式转换代码" %}}

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


{{% blocks/products/pf/feature-page-section h2="将 Excel 转换为 PDF、XPS、HTML 和 MD" %}}
专门的类可用于控制特定输出格式的转换过程，例如[Pdf保存选项](https://reference.aspose.com/cells/net/aspose.cells/pdfsaveoptions)将 Excel 文件导出为 PDF，[Xps保存选项](https://reference.aspose.com/cells/net/aspose.cells/xpssaveoptions)对于 Excel 到 XPS 的转换，[Html保存选项](https://reference.aspose.com/cells/net/aspose.cells/htmlsaveoptions)将 Excel 呈现为 HTML 和[Markdown保存选项](https://reference.aspose.com/cells/net/aspose.cells/markdownsaveoptions)用于 Excel 到 Markdown 的转换。
{{% blocks/products/pf/feature-page-code h3="C# Excel 代码到 PDF 和 Web 格式" %}}

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

{{% blocks/products/pf/feature-page-section h2="将 JSON 转换为 Excel & Excel 为 JSON" %}}
 JSON 数据可以导入到实例中[Cells](https://reference.aspose.com/cells/net/aspose.cells/cells)类的帮助下[JsonUtility.ImportData](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/importdata)用于进一步处理或简单转换为任何支持的格式。相似地，[工作表](https://reference.aspose.com/cells/net/aspose.cells/worksheet)数据可以通过创建一个导出为JSON[范围](https://reference.aspose.com/cells/net/aspose.cells/range)或细胞并调用[JsonUtility.ExportRangeToJson](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/exportrangetojson)方法。
{{% blocks/products/pf/feature-page-code h3="C# JSON 到 Excel 转换的代码" %}}
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

{{% blocks/products/pf/feature-page-code h3="C# Excel 代码到 JSON 转换" %}}
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

{{% blocks/products/pf/feature-page-section h2="将 Excel 工作表转换为 JPG、BMP、PNG 和 GIF" %}}
 Excel文件的每个工作表都可以转换为由设置的不同图像格式[ImageOrPrintOptions.ImageType](https://reference.aspose.com/cells/net/aspose.cells.rendering/imageorprintoptions/properties/imagetype)财产。默认值为 `ImageFormat.Bmp`。
{{% blocks/products/pf/feature-page-code h3="C# Excel 到图像转换的代码" %}}
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

{{% blocks/products/pf/feature-page-section h2="将 Excel 转换为 Word & PowerPoint" %}}
使用时可以加载任何电子表格并将其转换为 Word DOCX 和 PowerPoint PPTX 文件[Docx保存选项](https://reference.aspose.com/cells/net/aspose.cells/docxsaveoptions) & [Pptx保存选项](https://reference.aspose.com/cells/net/aspose.cells/pptxsaveoptions)类如下所示。
{{% blocks/products/pf/feature-page-code h3="C# Excel 到 Word 代码 & PowerPoint 转换" %}}
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
