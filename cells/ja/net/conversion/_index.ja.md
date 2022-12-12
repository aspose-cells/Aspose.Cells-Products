---
title: C#によるMicrosoftExcelファイル変換 

description: Excel XLS、XLSX、ODS、CSVをPDF、XPS、HTML、JPEG、HTML、およびその他の多くの一般的な形式に、わずか数行のC#コードで変換します。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft <sup>＆reg; </sup>.NETによるExcel形式の変換" h2="Excelファイルをスプレッドシート、Web、画像、および固定レイアウト形式でインポートおよびエクスポートします" >}}

{{% blocks/products/pf/feature-page-summary %}}
.NET Excelライブラリは、XLS、XLSX、XLSM、XLSB、XLTX、XLTM、CSV、SpreadsheetML、ODSなどの一般的な形式をサポートしながら、スプレッドシートのプログラミングと変換プロセスを高速化します。また、ExcelファイルをPDF、XPS、HTML、MHTML、プレーンテキスト、およびTIFF、JPG、PNG、BMP、SVGなどの一般的な画像形式にエクスポートすることもできます。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="ExcelをXLSX、ODS、SXC、FODSに変換する" %}}
スプレッドシート形式の相互変換では、次のインスタンスを含むスプレッドシートを読み込むだけで済みます。 [ワークブック](https://reference.aspose.com/cells/net/aspose.cells/workbook) から適切な値を選択しながら、目的の形式で保存し直します [SaveFormat](https://reference.aspose.com/cells/net/aspose.cells/saveformat) 列挙。
{{% blocks/products/pf/feature-page-code h3="C#Excelファイル形式変換のコード" %}}

```cs
// テンプレートファイルをロードする
var workbook = new Aspose.Cells.Workbook("template.xls");
// XLSX、ODS、SXC、FODS形式で保存
workbook.Save("output.xlsx", Aspose.Cells.SaveFormat.Xlsx);
workbook.Save("output.ods", Aspose.Cells.SaveFormat.Ods);
workbook.Save("output.scx", Aspose.Cells.SaveFormat.Sxc);
workbook.Save("output.fods", Aspose.Cells.SaveFormat.Fods);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="ExcelをPDF、XPS、HTML、MDに変換する" %}}
特殊なクラスを使用して、次のような特定の出力形式の変換プロセスを制御できます。 [PdfSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/pdfsaveoptions) ExcelファイルをPDFとしてエクスポートするには、 [XpsSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/xpssaveoptions) ExcelからXPSへの変換の場合、 [HtmlSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/htmlsaveoptions) ExcelをHTMLとしてレンダリングし、 [MarkdownSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/markdownsaveoptions) ExcelからMarkdownへの変換用。 
{{% blocks/products/pf/feature-page-code h3="C#ExcelからPDFおよびWeb形式へのコード" %}}

```cs
// ディスクからテンプレートExcelファイルをロードします
var book = new Aspose.Cells.Workbook("template.xlsx");
// ExcelをPDF/A-1a形式で保存
book.Save("output.pdf", new Aspose.Cells.PdfSaveOptions() { Compliance = PdfComplianceVersion.PdfA1a });
// ワークシートごとに1ページでExcelをXPSに保存
book.Save("output.xps", new Aspose.Cells.XpsSaveOptions() { OnePagePerSheet = true });
// Base64として画像を含むHTMLでExcelを保存します
book.Save("output.html", new Aspose.Cells.HtmlSaveOptions() { ExportImagesAsBase64 = true });
// セルの書式を保持しながら、ExcelをMarkdown（MD）に保存します
book.Save("output.md", new Aspose.Cells.MarkdownSaveOptions() { FormatStrategy = Cells.CellValueFormatStrategy.CellStyle });

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="JSONをExcelに、ExcelをJSONに変換する" %}}
JSONデータは次のインスタンスにインポートできます [Cells](https://reference.aspose.com/cells/net/aspose.cells/cells) の助けを借りてクラス [JsonUtility.ImportData](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/importdata) さらに処理したり、サポートされている形式に簡単に変換したりできます。同様に、 [ワークシート](https://reference.aspose.com/cells/net/aspose.cells/worksheet) データをJSONとしてエクスポートするには、 [範囲](https://reference.aspose.com/cells/net/aspose.cells/range) またはセルと呼び出し [JsonUtility.ExportRangeToJson](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/exportrangetojson) 方法。
{{% blocks/products/pf/feature-page-code h3="C#JSONからExcelへの変換のコード" %}}
```cs
// Workbookオブジェクトを作成する
var workbook = new Cells.Workbook();
var worksheet = workbook.Worksheets[0];
// ファイルからJSONデータを読み取る
string jsonInput = File.ReadAllText("Data.json");
// 配列をテーブルとして扱うようにJsonLayoutOptionsを設定します
var options = new Cells.Utility.JsonLayoutOptions();
options.ArrayAsTable = true;
// セルA1から始まるワークシートにJSONデータをインポートします
Cells.Utility.JsonUtility.ImportData(jsonInput, worksheet.Cells, 0, 0, options);
// 結果のファイルをXLSX形式で保存します
workbook.Save("output.xlsx", Cells.SaveFormat.Auto); 

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C#ExcelからJSONへの変換のコード" %}}
```cs
// ワークブックのインスタンスを含むXLSXファイルをロードします
var workbook = new Workbook("template.xlsx", new LoadOptions(Cells.LoadFormat.Auto));
// 変換するデータを含むワークシートのCellsCollectionにアクセスします
var cells = workbook.Worksheets[0].Cells;
// 詳細オプションのExportRangeToJsonOptionsを作成および設定します
var exportOptions = new Utility.ExportRangeToJsonOptions();
// エクスポートするデータを含むセルの範囲を作成します
var range = cells.CreateRange(0, 0, cells.LastCell.Row + 1, cells.LastCell.Column + 1);
// 範囲をJSONデータとしてエクスポート
string jsonData = Cells.Utility.JsonUtility.ExportRangeToJson(range, exportOptions);
// データファイルをJSON形式でディスクに書き込む
System.IO.File.WriteAllText("output.json", jsonData); 

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="ExcelワークシートをJPG、BMP、PNG、GIFに変換します" %}}
Excelファイルの各ワークシートは、によって設定されたさまざまな画像形式に変換できます。 [ImageOrPrintOptions.ImageType](https://reference.aspose.com/cells/net/aspose.cells.rendering/imageorprintoptions/properties/imagetype) 財産。デフォルト値は`ImageFormat.Bmp`です。
{{% blocks/products/pf/feature-page-code h3="C#Excelから画像への変換のコード" %}}
```cs
// テンプレートスプレッドシートを読み込む
var workbook = new Aspose.Cells.Workbook("template.xlsx");
// ImageOrPrintOptionsのインスタンスを作成および設定します
var options = new Aspose.Cells.Rendering.ImageOrPrintOptions();
options.OnePagePerSheet = true;
// 出力画像フォーマットを設定する
options.ImageType = Aspose.Cells.Drawing.ImageType.Jpeg;
// コレクションの最初のワークシートのSheetRenderを作成します
var render = new Aspose.Cells.Rendering.SheetRender(workbook.Worksheets[0], options);
// ワークシートを画像にレンダリング
render.ToImage(0, "output.jpg");

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="ExcelをWordとPowerPointに変換する" %}}
を使用しながら、任意のスプレッドシートをロードして、WordDOCXおよびPowerPointPPTXファイルに変換することができます。 [DocxSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/docxsaveoptions) ＆ [PptxSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/pptxsaveoptions) 以下に示すようなクラス。
{{% blocks/products/pf/feature-page-code h3="ExcelからWordおよびPowerPointへの変換のC#コード" %}}
```cs
// テンプレートファイルをロードする
var workbook = new Aspose.Cells.Workbook("template.xlsx");
// スプレッドシートをDOCXとして保存
workbook.Save("output.docx", new Aspose.Cells.DocxSaveOptions());
// スプレッドシートをPPTXとして保存
workbook.Save("output.pptx", new Aspose.Cells.PptxSaveOptions());

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
