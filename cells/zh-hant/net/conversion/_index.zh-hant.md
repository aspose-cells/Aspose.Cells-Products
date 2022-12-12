---
title: 通過 C# 轉換 Microsoft Excel 文件 

description: 只需幾行 C# 代碼，即可將 Excel XLS、XLSX、ODS、CSV 轉換為 PDF、XPS、HTML、JPEG、HTML 和許多其他流行格式。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> 通過 .NET 進行 Excel 格式轉換" h2="將 Excel 文件導入和導出為電子表格、Web、圖像和固定佈局格式" >}}

{{% blocks/products/pf/feature-page-summary %}}
.NET Excel 庫可加快電子表格編程和轉換過程，同時支持流行的格式，包括 XLS、XLSX、XLSM、XLSB、XLTX、XLTM、CSV、SpreadsheetML、ODS。它還允許將 Excel 文件導出為 PDF、XPS、HTML、MHTML、純文本和流行的圖像格式，如 TIFF、JPG、PNG、BMP 和 SVG。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="將 Excel 轉換為 XLSX、ODS、SXC 和 FODS" %}}
電子表格格式的相互轉換只需要加載一個帶有實例的電子表格 [工作簿](https://reference.aspose.com/cells/net/aspose.cells/workbook) 並在選擇適當的值時以所需的格式保存 [保存格式](https://reference.aspose.com/cells/net/aspose.cells/saveformat) 枚舉。
{{% blocks/products/pf/feature-page-code h3="C# Excel 文件格式轉換代碼" %}}

```cs
// 加載模板文件
var workbook = new Aspose.Cells.Workbook("template.xls");
// 保存為 XLSX、ODS、SXC 和 FODS 格式
workbook.Save("output.xlsx", Aspose.Cells.SaveFormat.Xlsx);
workbook.Save("output.ods", Aspose.Cells.SaveFormat.Ods);
workbook.Save("output.scx", Aspose.Cells.SaveFormat.Sxc);
workbook.Save("output.fods", Aspose.Cells.SaveFormat.Fods);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="將 Excel 轉換為 PDF、XPS、HTML 和 MD" %}}
可以使用專門的類來控制特定輸出格式的轉換過程，例如 [PdfSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/pdfsaveoptions) 將 Excel 文件導出為 PDF， [XpsSave 選項](https://reference.aspose.com/cells/net/aspose.cells/xpssaveoptions) 對於 Excel 到 XPS 的轉換， [HtmlSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/htmlsaveoptions) 將 Excel 呈現為 HTML 和 [MarkdownSave 選項](https://reference.aspose.com/cells/net/aspose.cells/markdownsaveoptions) 用於 Excel 到 Markdown 的轉換。 
{{% blocks/products/pf/feature-page-code h3="C# Excel 到 PDF 和 Web 格式的代碼" %}}

```cs
// 從光盤加載模板 Excel 文件
var book = new Aspose.Cells.Workbook("template.xlsx");
// 以 PDF/A-1a 格式保存 Excel
book.Save("output.pdf", new Aspose.Cells.PdfSaveOptions() { Compliance = PdfComplianceVersion.PdfA1a });
// 在 XPS 中保存 Excel，每個工作表只有 1 頁
book.Save("output.xps", new Aspose.Cells.XpsSaveOptions() { OnePagePerSheet = true });
// 將帶有圖像的 Excel 保存為 Base64
book.Save("output.html", new Aspose.Cells.HtmlSaveOptions() { ExportImagesAsBase64 = true });
// 將 Excel 保存在 Markdown (MD) 中，同時保留單元格格式
book.Save("output.md", new Aspose.Cells.MarkdownSaveOptions() { FormatStrategy = Cells.CellValueFormatStrategy.CellStyle });

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="將 JSON 轉換為 Excel 和 Excel 轉換為 JSON" %}}
JSON數據可以導入到一個實例中 [Cells](https://reference.aspose.com/cells/net/aspose.cells/cells) 在幫助下上課 [JsonUtility.ImportData](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/importdata) 用於進一步處理或簡單轉換為任何支持的格式。相似地， [工作表](https://reference.aspose.com/cells/net/aspose.cells/worksheet) 數據可以通過創建一個 JSON 格式導出 [範圍](https://reference.aspose.com/cells/net/aspose.cells/range) 或單元格並調用 [JsonUtility.ExportRangeToJson](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/exportrangetojson) 方法。
{{% blocks/products/pf/feature-page-code h3="C# JSON 到 Excel 轉換的代碼" %}}
```cs
// 創建工作簿對象
var workbook = new Cells.Workbook();
var worksheet = workbook.Worksheets[0];
// 從文件中讀取 JSON 數據
string jsonInput = File.ReadAllText("Data.json");
// 設置 JsonLayoutOptions 將數組視為表
var options = new Cells.Utility.JsonLayoutOptions();
options.ArrayAsTable = true;
// 從單元格 A1 開始將 JSON 數據導入工作表
Cells.Utility.JsonUtility.ImportData(jsonInput, worksheet.Cells, 0, 0, options);
// 以 XLSX 格式保存結果文件
workbook.Save("output.xlsx", Cells.SaveFormat.Auto); 

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Excel 到 JSON 轉換的代碼" %}}
```cs
// 使用 Workbook 實例加載 XLSX 文件
var workbook = new Workbook("template.xlsx", new LoadOptions(Cells.LoadFormat.Auto));
// 訪問包含要轉換的數據的工作表的 CellsCollection
var cells = workbook.Worksheets[0].Cells;
// 為高級選項創建和設置 ExportRangeToJsonOptions
var exportOptions = new Utility.ExportRangeToJsonOptions();
// 創建一系列包含要導出的數據的單元格
var range = cells.CreateRange(0, 0, cells.LastCell.Row + 1, cells.LastCell.Column + 1);
// 將範圍導出為 JSON 數據
string jsonData = Cells.Utility.JsonUtility.ExportRangeToJson(range, exportOptions);
// 以 JSON 格式將數據文件寫入光盤
System.IO.File.WriteAllText("output.json", jsonData); 

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="將 Excel 工作表轉換為 JPG、BMP、PNG 和 GIF" %}}
Excel 文件的每個工作表都可以轉換為由 [ImageOrPrintOptions.ImageType](https://reference.aspose.com/cells/net/aspose.cells.rendering/imageorprintoptions/properties/imagetype) 財產。默認值為`ImageFormat.Bmp`。
{{% blocks/products/pf/feature-page-code h3="C# Excel 到圖像轉換的代碼" %}}
```cs
// 加載模板電子表格
var workbook = new Aspose.Cells.Workbook("template.xlsx");
// 創建和設置 ImageOrPrintOptions 的實例
var options = new Aspose.Cells.Rendering.ImageOrPrintOptions();
options.OnePagePerSheet = true;
// 設置輸出圖像格式
options.ImageType = Aspose.Cells.Drawing.ImageType.Jpeg;
// 為集合中的第一個工作表創建 SheetRender
var render = new Aspose.Cells.Rendering.SheetRender(workbook.Worksheets[0], options);
// 將工作表渲染為圖像
render.ToImage(0, "output.jpg");

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="將 Excel 轉換為 Word 和 PowerPoint" %}}
使用時可以加載任何電子表格並將其轉換為 Word DOCX 和 PowerPoint PPTX 文件 [DocxSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/docxsaveoptions) & [PptxSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/pptxsaveoptions) 類如下所示。
{{% blocks/products/pf/feature-page-code h3="C# Excel 到 Word 和 PowerPoint 轉換的代碼" %}}
```cs
// 加載模板文件
var workbook = new Aspose.Cells.Workbook("template.xlsx");
// 將電子表格另存為 DOCX
workbook.Save("output.docx", new Aspose.Cells.DocxSaveOptions());
// 將電子表格另存為 PPTX
workbook.Save("output.pptx", new Aspose.Cells.PptxSaveOptions());

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
