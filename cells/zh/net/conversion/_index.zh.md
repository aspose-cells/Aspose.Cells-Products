---
title: 通过 C# 转换 Microsoft Excel 文件 
url: /zh/net/conversion/
description: 只需几行 C# 代码，即可将 Excel XLS、XLSX、ODS、CSV 转换为 PDF、XPS、HTML、JPEG、HTML 和许多其他流行格式。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> 通过 .NET 进行 Excel 格式转换" h2="将 Excel 文件导入和导出为电子表格、Web、图像和固定布局格式" >}}

{{% blocks/products/pf/feature-page-summary %}}
.NET Excel 库可加快电子表格编程和转换过程，同时支持流行的格式，包括 XLS、XLSX、XLSM、XLSB、XLTX、XLTM、CSV、SpreadsheetML、ODS。它还允许将 Excel 文件导出为 PDF、XPS、HTML、MHTML、纯文本和流行的图像格式，如 TIFF、JPG、PNG、BMP 和 SVG。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="将 Excel 转换为 XLSX、ODS、SXC 和 FODS" %}}
电子表格格式的相互转换只需要加载一个带有实例的电子表格 [工作簿](https://reference.aspose.com/cells/net/aspose.cells/workbook) 并在选择适当的值时以所需的格式保存 [保存格式](https://reference.aspose.com/cells/net/aspose.cells/saveformat) 枚举。
{{% blocks/products/pf/feature-page-code h3="C# Excel 文件格式转换代码" %}}

```cs
// 加载模板文件
var workbook = new Aspose.Cells.Workbook("template.xls");
// 保存为 XLSX、ODS、SXC 和 FODS 格式
workbook.Save("output.xlsx", Aspose.Cells.SaveFormat.Xlsx);
workbook.Save("output.ods", Aspose.Cells.SaveFormat.Ods);
workbook.Save("output.scx", Aspose.Cells.SaveFormat.Sxc);
workbook.Save("output.fods", Aspose.Cells.SaveFormat.Fods);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="将 Excel 转换为 PDF、XPS、HTML 和 MD" %}}
可以使用专门的类来控制特定输出格式的转换过程，例如 [PdfSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/pdfsaveoptions) 将 Excel 文件导出为 PDF， [XpsSave 选项](https://reference.aspose.com/cells/net/aspose.cells/xpssaveoptions) 对于 Excel 到 XPS 的转换， [HtmlSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/htmlsaveoptions) 将 Excel 呈现为 HTML 和 [MarkdownSave 选项](https://reference.aspose.com/cells/net/aspose.cells/markdownsaveoptions) 用于 Excel 到 Markdown 的转换。 
{{% blocks/products/pf/feature-page-code h3="C# Excel 到 PDF 和 Web 格式的代码" %}}

```cs
// 从光盘加载模板 Excel 文件
var book = new Aspose.Cells.Workbook("template.xlsx");
// 以 PDF/A-1a 格式保存 Excel
book.Save("output.pdf", new Aspose.Cells.PdfSaveOptions() { Compliance = PdfComplianceVersion.PdfA1a });
// 在 XPS 中保存 Excel，每个工作表只有 1 页
book.Save("output.xps", new Aspose.Cells.XpsSaveOptions() { OnePagePerSheet = true });
// 将带有图像的 Excel 保存为 Base64
book.Save("output.html", new Aspose.Cells.HtmlSaveOptions() { ExportImagesAsBase64 = true });
// 将 Excel 保存在 Markdown (MD) 中，同时保留单元格格式
book.Save("output.md", new Aspose.Cells.MarkdownSaveOptions() { FormatStrategy = Cells.CellValueFormatStrategy.CellStyle });

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="将 JSON 转换为 Excel 和 Excel 转换为 JSON" %}}
JSON数据可以导入到一个实例中 [Cells](https://reference.aspose.com/cells/net/aspose.cells/cells) 在帮助下上课 [JsonUtility.ImportData](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/importdata) 用于进一步处理或简单转换为任何支持的格式。相似地， [工作表](https://reference.aspose.com/cells/net/aspose.cells/worksheet) 数据可以通过创建一个 JSON 格式导出 [范围](https://reference.aspose.com/cells/net/aspose.cells/range) 或单元格并调用 [JsonUtility.ExportRangeToJson](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/exportrangetojson) 方法。
{{% blocks/products/pf/feature-page-code h3="C# JSON 到 Excel 转换的代码" %}}
```cs
// 创建工作簿对象
var workbook = new Cells.Workbook();
var worksheet = workbook.Worksheets[0];
// 从文件中读取 JSON 数据
string jsonInput = File.ReadAllText("Data.json");
// 设置 JsonLayoutOptions 将数组视为表
var options = new Cells.Utility.JsonLayoutOptions();
options.ArrayAsTable = true;
// 从单元格 A1 开始将 JSON 数据导入工作表
Cells.Utility.JsonUtility.ImportData(jsonInput, worksheet.Cells, 0, 0, options);
// 以 XLSX 格式保存结果文件
workbook.Save("output.xlsx", Cells.SaveFormat.Auto); 

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Excel 到 JSON 转换的代码" %}}
```cs
// 使用 Workbook 实例加载 XLSX 文件
var workbook = new Workbook("template.xlsx", new LoadOptions(Cells.LoadFormat.Auto));
// 访问包含要转换的数据的工作表的 CellsCollection
var cells = workbook.Worksheets[0].Cells;
// 为高级选项创建和设置 ExportRangeToJsonOptions
var exportOptions = new Utility.ExportRangeToJsonOptions();
// 创建一系列包含要导出的数据的单元格
var range = cells.CreateRange(0, 0, cells.LastCell.Row + 1, cells.LastCell.Column + 1);
// 将范围导出为 JSON 数据
string jsonData = Cells.Utility.JsonUtility.ExportRangeToJson(range, exportOptions);
// 以 JSON 格式将数据文件写入光盘
System.IO.File.WriteAllText("output.json", jsonData); 

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="将 Excel 工作表转换为 JPG、BMP、PNG 和 GIF" %}}
Excel 文件的每个工作表都可以转换为由 [ImageOrPrintOptions.ImageType](https://reference.aspose.com/cells/net/aspose.cells.rendering/imageorprintoptions/properties/imagetype) 财产。默认值为`ImageFormat.Bmp`。
{{% blocks/products/pf/feature-page-code h3="C# Excel 到图像转换的代码" %}}
```cs
// 加载模板电子表格
var workbook = new Aspose.Cells.Workbook("template.xlsx");
// 创建和设置 ImageOrPrintOptions 的实例
var options = new Aspose.Cells.Rendering.ImageOrPrintOptions();
options.OnePagePerSheet = true;
// 设置输出图像格式
options.ImageType = Aspose.Cells.Drawing.ImageType.Jpeg;
// 为集合中的第一个工作表创建 SheetRender
var render = new Aspose.Cells.Rendering.SheetRender(workbook.Worksheets[0], options);
// 将工作表渲染为图像
render.ToImage(0, "output.jpg");

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="将 Excel 转换为 Word 和 PowerPoint" %}}
使用时可以加载任何电子表格并将其转换为 Word DOCX 和 PowerPoint PPTX 文件 [DocxSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/docxsaveoptions) & [PptxSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/pptxsaveoptions) 类如下所示。
{{% blocks/products/pf/feature-page-code h3="C# Excel 到 Word 和 PowerPoint 转换的代码" %}}
```cs
// 加载模板文件
var workbook = new Aspose.Cells.Workbook("template.xlsx");
// 将电子表格另存为 DOCX
workbook.Save("output.docx", new Aspose.Cells.DocxSaveOptions());
// 将电子表格另存为 PPTX
workbook.Save("output.pptx", new Aspose.Cells.PptxSaveOptions());

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}