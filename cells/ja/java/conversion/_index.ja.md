---
title: Microsoft Excel ファイル変換 via Java
description: Excel XLS、XLSX、ODS、CSVからXPS、XPS、HTML、JPEG、HTML、およびHTML、およびJavaコードのほんの一部のラインを持つ他の人気のある形式のある形式を変えてください。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel ファイルの変換 via Java" h2="Microsoft Excel ドキュメントをスプレッドシート、Web、画像、固定レイアウト形式で保存" >}}

{{% blocks/products/pf/feature-page-summary %}}
どれについても**Excelコンバーター**アプリケーションまたはソリューション、Java Excel ライブラリは、XLS、XLSX、XLSM、XLSB、XLTX、XLTM、CSV、SpreadsheetML、07619 などの複数の形式を処理しながら、スプレッドシートのプログラミングと変換プロセスを高速化します。 3481. *Excel ファイルを PDF** に変換することもできます。 XPS、HTML、MHTML、プレーン テキスト、および TIFF、JPG、PNG、BMP、SVG などの一般的な画像形式。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Microsoft Excel 形式の相互変換" %}}
スプレッドシート形式の相互変換には、次のインスタンスを含むスプレッドシートをロードするだけで済みます。[ワークブック](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)から適切な値を選択しながら、目的の形式で保存し直します。[保存形式](https://reference.aspose.com/cells/java/com.aspose.cells/SaveFormat)列挙。
{{% blocks/products/pf/feature-page-code h3="Java Excel ファイル形式変換のコード例" %}}

```cs
// load the source file
var wkb = new Workbook("sourceFile.xls");
// save as XLSX, ODS, SXC & FODS formats
wkb.save("xlsx-output.xlsx", SaveFormat.XLSX);
wkb.save("ods-output.ods", SaveFormat.ODS);
wkb.save("scx-output.scx", SaveFormat.SXC);
wkb.save("fods-output.fods", SaveFormat.FODS);
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-json xlsx-to-pdf xlsx-to-html xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Excel を PDF、XPS、HTML、MD に変換" %}}
特殊なクラスを使用して、次のような特定の出力形式の変換プロセスを制御できます。[PDF保存オプション](https://reference.aspose.com/cells/java/com.aspose.cells/PdfSaveOptions)Excel ファイルを PDF として変換するには、[Xps保存オプション](https://reference.aspose.com/cells/java/com.aspose.cells/XpsSaveOptions)Excel を XPS としてエクスポートするには、[HTML保存オプション](https://reference.aspose.com/cells/java/com.aspose.cells/HtmlSaveOptions)Excel を HTML としてレンダリングし、[マークダウン保存オプション](https://reference.aspose.com/cells/java/com.aspose.cells/MarkdownSaveOptions)Excel から Markdown への変換用。
{{% blocks/products/pf/feature-page-code h3="Java Excel から PDF および Web フォーマットのサンプル コード" %}}

```cs
// load template Excel file from disc
var bk = new Workbook("source-file.xlsx");

// convert Excel to PDF using Java
// Create PDF options
PdfSaveOptions options = new PdfSaveOptions();
options.setCompliance(PdfCompliance.PDF_A_1_A);

bk.save("excel-to-pdf.pdf", options);
// save Excel in XPS
bk.save("output.xps", new XpsSaveOptions());
// save Excel in HTML
bk.save("output.html", new HtmlSaveOptions());
// save Excel in Markdown (MD)
bk.save("output.md", new MarkdownSaveOptions());

// one can set relevant save options as of his choice before saving into relevant format
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="JSON を Excel に変換し、Excel を JSON に変換します" %}}
JSON データは、次の助けを借りて Workbook クラスのインスタンスにインポートできます。[JSONUtility.importData](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility#importData)さらに処理したり、サポートされている形式に簡単に変換したりできます。同様に、ワークシート データは、[範囲](https://reference.aspose.com/cells/java/com.aspose.cells/range)またはセルを呼び出して、[importRangeToJson](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility)方法。
{{% blocks/products/pf/feature-page-code h3="Java JSONからExcelへの変換コード" %}}
```cs
Workbook workbook = new Workbook(path + "source-file.xlsx");
Worksheet wks = workbook.getWorksheets().get(0);
		
// Read File
File file = new File(path + "source-data.json");
BufferedReader bufferedReader = new BufferedReader(new FileReader(file));
String jsonInput = "";
String tempString;
while ((tempString = bufferedReader.readLine()) != null) {
	jsonInput = jsonInput + tempString; 
}
bufferedReader.close();
							
// Set JsonLayoutOptions
JsonLayoutOptions options = new JsonLayoutOptions();
options.setIgnoreArrayTitle(true);
options.setArrayAsTable(true);

// Import JSON Data
JSONUtility.importData(jsonInput, wks.getCells(), 0, 0, options);

// Save Excel file
workbook.save(path + "excel-to-json.out.xlsx");
```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Excel の Java ソース コードから JSON への変換" %}}
```cs
// load XLSX file with an instance of Workbook
Workbook workbook = new Workbook("sourceFile.xlsx");
// access CellsCollection of the worksheet containing data to be converted
Cells cells = workbook.getWorksheets().get(0).getCells();
// create & set ExportRangeToJsonOptions for advanced options
ExportRangeToJsonOptions exportOptions = new ExportRangeToJsonOptions();
// create a range of cells containing data to be exported
Range range = cells.createRange(0, 0, cells.getLastCell().getRow() + 1, cells.getLastCell().getColumn() + 1);
// export range as JSON data
String jsonData = JsonUtility.exportRangeToJson(range, exportOptions);
// write data to disc in JSON format
BufferedWriter writer = new BufferedWriter(new FileWriter("output.json"));
writer.write(jsonData);
writer.close();    
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Excel ワークシートを画像として保存" %}}
各ワークシートは、ImageType プロパティで設定された JPG、BMP、PNG、GIF などのさまざまな画像形式に変換できます。どれについても**Excelを画像に変換**ケースの場合は、リンクから該当するケースを選択してください。
{{% blocks/products/pf/feature-page-code h3="Java Excel から画像への変換用のコード" %}}
```cs
// load template spreadsheet
var wkb = new Workbook("template.xlsx");

// Create an object for ImageOptions
ImageOrPrintOptions imgOptions = new ImageOrPrintOptions();

// Set the image type
imgOptions.setImageType(ImageType.PNG);

// Get the first worksheet.
Worksheet sheet = wkb.getWorksheets().get(0);

// Create a SheetRender object for the target sheet
SheetRender sr = new SheetRender(sheet, imgOptions);
for (int j = 0; j < sr.getPageCount(); j++) {
	// Generate an image for the worksheet
	sr.toImage(j, dataDir + "WToImage-out" + j + ".png");
}
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Microsoft Excel を Word に変換し、PowerPoint" %}}
使用中に、任意のスプレッドシートをロードし、Word DOCX & PowerPoint PPTX ファイルに変換することが可能です。[DocxSaveオプション](https://reference.aspose.com/cells/java/com.aspose.cells/DocxSaveOptions) & [Pptx保存オプション](https://reference.aspose.com/cells/java/com.aspose.cells/PptxSaveOptions)以下に示すようなクラス。
{{% blocks/products/pf/feature-page-code h3="Java Excel から Word へのコードと PowerPoint 変換" %}}
```cs
// load the template file
var wkb = new Workbook("template.xlsx");
// save spreadsheet as DOCX
wkb.save("output.docx", new DocxSaveOptions());
// save spreadsheet as PPTX
wkb.save("output.pptx", new PptxSaveOptions());
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
