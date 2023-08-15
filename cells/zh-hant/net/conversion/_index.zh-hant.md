---
title: Microsoft Excel 文件轉換通過 C#
description: 轉換Excel XLS，XLSX，ODS，CSV至PDF，XPS，HTML，HTML，JPEG，JPEG，HTML和許多其他形式的碼數為076193131313131313。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel 格式轉換 via .NET" h2="將 Excel 文件導入和導出為電子表格、Web、圖像和固定佈局格式" >}}

{{% blocks/products/pf/feature-page-summary %}}
.NET Excel 庫可加快電子表格編程和轉換過程，同時支持流行格式，包括XLS、XLSX、XLSM、XLSB、XLTX、XLTM、CSV、SpreadsheetML、ODS . 它還允許將Excel文件導出到PDF、XPS、HTML、 MHTML、Plain文本和流行的圖像格式，例如 TIFF、JPG、PNG、BMP 和 SVG。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="將 Excel 轉換為 XLSX、ODS、SXC 和 FODS" %}}
電子表格格式的相互轉換只需要加載帶有實例的電子表格[練習冊](https://reference.aspose.com/cells/net/aspose.cells/workbook)並以所需的格式保存，同時從中選擇適當的值[保存格式](https://reference.aspose.com/cells/net/aspose.cells/saveformat)枚舉。
{{% blocks/products/pf/feature-page-code h3="C# Excel文件格式轉換代碼" %}}

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


{{% blocks/products/pf/feature-page-section h2="將 Excel 轉換為 PDF、XPS、HTML 和 MD" %}}
專門的類可用於控制特定輸出格式的轉換過程，例如[Pdf保存選項](https://reference.aspose.com/cells/net/aspose.cells/pdfsaveoptions)將 Excel 文件導出為 PDF，[Xps保存選項](https://reference.aspose.com/cells/net/aspose.cells/xpssaveoptions)對於 Excel 到 XPS 的轉換，[Html保存選項](https://reference.aspose.com/cells/net/aspose.cells/htmlsaveoptions)將 Excel 呈現為 HTML 和[Markdown保存選項](https://reference.aspose.com/cells/net/aspose.cells/markdownsaveoptions)用於 Excel 到 Markdown 的轉換。
{{% blocks/products/pf/feature-page-code h3="C# Excel 代碼到 PDF 和 Web 格式" %}}

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

{{% blocks/products/pf/feature-page-section h2="將 JSON 轉換為 Excel & Excel 為 JSON" %}}
 JSON 數據可以導入到實例中[Cells](https://reference.aspose.com/cells/net/aspose.cells/cells)類的幫助下[JsonUtility.ImportData](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/importdata)用於進一步處理或簡單轉換為任何支持的格式。相似地，[工作表](https://reference.aspose.com/cells/net/aspose.cells/worksheet)數據可以通過創建一個導出為JSON[範圍](https://reference.aspose.com/cells/net/aspose.cells/range)或細胞並調用[JsonUtility.ExportRangeToJson](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/exportrangetojson)方法。
{{% blocks/products/pf/feature-page-code h3="C# JSON 到 Excel 轉換的代碼" %}}
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

{{% blocks/products/pf/feature-page-code h3="C# Excel 代碼到 JSON 轉換" %}}
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

{{% blocks/products/pf/feature-page-section h2="將 Excel 工作表轉換為 JPG、BMP、PNG 和 GIF" %}}
 Excel文件的每個工作表都可以轉換為由設置的不同圖像格式[ImageOrPrintOptions.ImageType](https://reference.aspose.com/cells/net/aspose.cells.rendering/imageorprintoptions/properties/imagetype)財產。默認值為 `ImageFormat.Bmp`。
{{% blocks/products/pf/feature-page-code h3="C# Excel 到圖像轉換的代碼" %}}
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

{{% blocks/products/pf/feature-page-section h2="將 Excel 轉換為 Word & PowerPoint" %}}
使用時可以加載任何電子表格並將其轉換為 Word DOCX 和 PowerPoint PPTX 文件[Docx保存選項](https://reference.aspose.com/cells/net/aspose.cells/docxsaveoptions) & [Pptx保存選項](https://reference.aspose.com/cells/net/aspose.cells/pptxsaveoptions)類如下所示。
{{% blocks/products/pf/feature-page-code h3="C# Excel 到 Word 代碼 & PowerPoint 轉換" %}}
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
