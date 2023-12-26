---
title: Microsoft C# 経由の Excel ファイル変換
description: Aspose.Cells for .NET 図書館。わずか数行の C# コードで、EXCEL、JSON、PDF、XML、HTML、TXT、TSV、CSV、SQL、JPG、PNG などの形式を変換します。
keywords: [C# Aspose.Cells., excel to pdf., excel to json., txt to sql., csv to json., json to pdf., xml to excel and Convert files between various formats in C#]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel 形式変換 via .NET" h2="Excel ファイルをスプレッドシート、Web、画像、固定レイアウト形式でインポートおよびエクスポート" >}}

{{% blocks/products/pf/feature-page-summary %}}
.NET Excel ライブラリは、XLS、XLSX、XLSM、XLSB、XLTX、XLTM、CSV、SpreadsheetML、07619348 などの一般的な形式をサポートしながら、スプレッドシートのプログラミングと変換プロセスを高速化します。 1. Excel ファイルを PDF、XPS、HTML、MHTML、Plain にエクスポートすることもできます。 TIFF、JPG、PNG、BMP、SVG などのテキストおよび一般的な画像形式。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel を XLSX、ODS、SXC、FODS に変換" %}}
スプレッドシート形式の相互変換には、次のインスタンスを含むスプレッドシートをロードするだけで済みます。[ワークブック](https://reference.aspose.com/cells/net/aspose.cells/workbook)から適切な値を選択しながら、目的の形式で保存し直します。[保存形式](https://reference.aspose.com/cells/net/aspose.cells/saveformat)列挙。
{{% blocks/products/pf/feature-page-code h3="C# Excel ファイル形式変換用のコード" %}}

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


{{% blocks/products/pf/feature-page-section h2="Excel を PDF、XPS、HTML、MD に変換" %}}
特殊なクラスを使用して、次のような特定の出力形式の変換プロセスを制御できます。[PDF保存オプション](https://reference.aspose.com/cells/net/aspose.cells/pdfsaveoptions)Excel ファイルを PDF としてエクスポートするには、[Xps保存オプション](https://reference.aspose.com/cells/net/aspose.cells/xpssaveoptions) Excel から XPS への変換の場合、[HTML保存オプション](https://reference.aspose.com/cells/net/aspose.cells/htmlsaveoptions)Excel を HTML としてレンダリングし、[マークダウン保存オプション](https://reference.aspose.com/cells/net/aspose.cells/markdownsaveoptions)Excel から Markdown への変換用。
{{% blocks/products/pf/feature-page-code h3="C# Excel から PDF および Web 形式のコード" %}}

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

{{% blocks/products/pf/feature-page-section h2="JSON を Excel に変換し、Excel を JSON に変換" %}}
JSON データをインスタンスにインポートできます。[Cells](https://reference.aspose.com/cells/net/aspose.cells/cells)の助けを借りてクラス[JsonUtility.ImportData](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/importdata)さらに処理したり、サポートされている形式に簡単に変換したりできます。同様に、[ワークシート](https://reference.aspose.com/cells/net/aspose.cells/worksheet)データは、[範囲](https://reference.aspose.com/cells/net/aspose.cells/range)またはセルを呼び出して、[JsonUtility.ExportRangeToJson](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/exportrangetojson)方法。
{{% blocks/products/pf/feature-page-code h3="C# JSONからExcelへの変換コード" %}}
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

{{% blocks/products/pf/feature-page-code h3="C# Excel のコードから JSON への変換" %}}
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

{{% blocks/products/pf/feature-page-section h2="Excel ワークシートを JPG、BMP、PNG、GIF に変換" %}}
Excel ファイルの各ワークシートは、[ImageOrPrintOptions.ImageType](https://reference.aspose.com/cells/net/aspose.cells.rendering/imageorprintoptions/properties/imagetype)財産。デフォルト値は `ImageFormat.Bmp` です。
{{% blocks/products/pf/feature-page-code h3="C# Excel から画像への変換用のコード" %}}
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

{{% blocks/products/pf/feature-page-section h2="Excel を Word に変換 & PowerPoint" %}}
使用中に、任意のスプレッドシートをロードし、Word DOCX & PowerPoint PPTX ファイルに変換することが可能です。[DocxSaveオプション](https://reference.aspose.com/cells/net/aspose.cells/docxsaveoptions) & [Pptx保存オプション](https://reference.aspose.com/cells/net/aspose.cells/pptxsaveoptions)以下に示すようなクラス。
{{% blocks/products/pf/feature-page-code h3="ExcelからWordへのC#コードとPowerPoint変換" %}}
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
