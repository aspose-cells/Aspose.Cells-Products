---
title: JavaによるMicrosoftExcelファイル変換 
url: /ja/java/conversion/
description: Excel XLS、XLSX、ODS、CSVをPDF、XPS、HTML、JPEG、HTML、およびその他の多くの一般的な形式に、わずか数行のJavaコードで変換します。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft <sup>＆reg; </sup>JavaによるExcelファイルの変換" h2="Microsoft Excelドキュメントをスプレッドシート、Web、画像、および固定レイアウト形式で保存します" >}}

{{% blocks/products/pf/feature-page-summary %}}
** Excelコンバーター**アプリケーションまたはソリューションの場合、Java Excelライブラリは、XLS、XLSX、XLSM、XLSB、XLTX、XLTM、CSV、SpreadsheetML、ODSなどの複数の形式を処理しながら、スプレッドシートのプログラミングと変換プロセスを高速化します。また、** ExcelファイルをPDF**、XPS、HTML、MHTML、プレーンテキスト、およびTIFF、JPG、PNG、BMP、SVGなどの一般的な画像形式に変換することもできます。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="MicrosoftExcel形式の相互変換" %}}
スプレッドシート形式の相互変換では、次のインスタンスを含むスプレッドシートを読み込むだけで済みます。 [ワークブック](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) から適切な値を選択しながら、目的の形式で保存し直します [SaveFormat](https://apireference.aspose.com/cells/java/com.aspose.cells/SaveFormat) 列挙。
{{% blocks/products/pf/feature-page-code h3="JavaExcelファイル形式変換のサンプルコード" %}}

```cs
// ソースファイルをロードする
var wkb = new Workbook("sourceFile.xls");
// XLSX、ODS、SXC、FODS形式で保存
wkb.save("xlsx-output.xlsx", SaveFormat.XLSX);
wkb.save("ods-output.ods", SaveFormat.ODS);
wkb.save("scx-output.scx", SaveFormat.SXC);
wkb.save("fods-output.fods", SaveFormat.FODS);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-json xlsx-to-pdf xlsx-to-html xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="ExcelをPDF、XPS、HTML、MDに変換する" %}}
特殊なクラスを使用して、次のような特定の出力形式の変換プロセスを制御できます。 [PdfSaveOptions](https://apireference.aspose.com/cells/java/com.aspose.cells/PdfSaveOptions) ExcelファイルをPDFとして変換するには、 [XpsSaveOptions](https://apireference.aspose.com/cells/java/com.aspose.cells/XpsSaveOptions) ExcelをXPSとしてエクスポートするには、 [HtmlSaveOptions](https://apireference.aspose.com/cells/java/com.aspose.cells/HtmlSaveOptions) ExcelをHTMLとしてレンダリングし、 [MarkdownSaveOptions](https://apireference.aspose.com/cells/java/com.aspose.cells/MarkdownSaveOptions) ExcelからMarkdownへの変換用。 
{{% blocks/products/pf/feature-page-code h3="JavaExcelからPDFおよびWeb形式のサンプルコード" %}}

```cs
// ディスクからテンプレートExcelファイルをロードします
var bk = new Workbook("source-file.xlsx");

// Javaを使用してExcelをPDFに変換する
// PDFオプションを作成する
PdfSaveOptions options = new PdfSaveOptions();
options.setCompliance(PdfCompliance.PDF_A_1_A);

bk.save("excel-to-pdf.pdf", options);
// ExcelをXPSに保存する
bk.save("output.xps", new XpsSaveOptions());
// ExcelをHTMLで保存
bk.save("output.html", new HtmlSaveOptions());
// Excelをマークダウン（MD）に保存
bk.save("output.md", new MarkdownSaveOptions());

// 関連する形式で保存する前に、自分の選択で関連する保存オプションを設定できます

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="JSONをExcelに、ExcelをJSONに変換する" %}}
JSONデータは、Workbookクラスのインスタンスにインポートできます。 [JSONUtility.importData](https://apireference.aspose.com/cells/java/com.aspose.cells/jsonutility#importData) さらに処理したり、サポートされている形式に簡単に変換したりできます。同様に、ワークシートデータは、を作成することでJSONとしてエクスポートできます。 [範囲](https://apireference.aspose.com/cells/java/com.aspose.cells/range) またはセルと呼び出し [exportRangeToJson](https://apireference.aspose.com/cells/java/com.aspose.cells/jsonutility) 方法。
{{% blocks/products/pf/feature-page-code h3="JavaJSONからExcelへの変換のコード" %}}
```cs
Workbook workbook = new Workbook(path + "source-file.xlsx");
Worksheet wks = workbook.getWorksheets().get(0);
		
// ファイルを読む
File file = new File(path + "source-data.json");
BufferedReader bufferedReader = new BufferedReader(new FileReader(file));
String jsonInput = "";
String tempString;
while ((tempString = bufferedReader.readLine()) != null) {
	jsonInput = jsonInput + tempString; 
}
bufferedReader.close();
							
// JsonLayoutOptionsを設定します
JsonLayoutOptions options = new JsonLayoutOptions();
options.setIgnoreArrayTitle(true);
options.setArrayAsTable(true);

// JSONデータのインポート
JSONUtility.importData(jsonInput, wks.getCells(), 0, 0, options);

// Excelファイルを保存する
workbook.save(path + "excel-to-json.out.xlsx");

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="JavaExcelからJSONへの変換のソースコード" %}}
```cs
// ワークブックのインスタンスを含むXLSXファイルをロードします
Workbook workbook = new Workbook("sourceFile.xlsx");
// 変換するデータを含むワークシートのCellsCollectionにアクセスします
Cells cells = workbook.getWorksheets().get(0).getCells();
// 詳細オプションのExportRangeToJsonOptionsを作成および設定します
ExportRangeToJsonOptions exportOptions = new ExportRangeToJsonOptions();
// エクスポートするデータを含むセルの範囲を作成します
Range range = cells.createRange(0, 0, cells.getLastCell().getRow() + 1, cells.getLastCell().getColumn() + 1);
// 範囲をJSONデータとしてエクスポート
String jsonData = JsonUtility.exportRangeToJson(range, exportOptions);
// JSON形式でディスクにデータを書き込む
BufferedWriter writer = new BufferedWriter(new FileWriter("output.json"));
writer.write(jsonData);
writer.close();    

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Excelワークシートを画像に保存" %}}
各ワークシートは、ImageTypeプロパティで設定されたJPG、BMP、PNG、GIFなどのさまざまな画像形式に変換できます。 ** Excelを画像に変換**の場合は、リンクから関連するケースを選択してください。
{{% blocks/products/pf/feature-page-code h3="JavaExcelから画像への変換のコード" %}}
```cs
// テンプレートスプレッドシートを読み込む
var wkb = new Workbook("template.xlsx");

// ImageOptionsのオブジェクトを作成します
ImageOrPrintOptions imgOptions = new ImageOrPrintOptions();

// 画像の種類を設定する
imgOptions.setImageType(ImageType.PNG);

// 最初のワークシートを入手します。
Worksheet sheet = wkb.getWorksheets().get(0);

// ターゲットシートのSheetRenderオブジェクトを作成します
SheetRender sr = new SheetRender(sheet, imgOptions);
for (int j = 0; j < sr.getPageCount(); j++) {
	// ワークシートの画像を生成する
	sr.toImage(j, dataDir + "WToImage-out" + j + ".png");
}

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="MicrosoftExcelをWordおよびPowerPointに変換する" %}}
を使用しながら、任意のスプレッドシートをロードして、WordDOCXおよびPowerPointPPTXファイルに変換することができます。 [DocxSaveOptions](https://apireference.aspose.com/cells/java/com.aspose.cells/DocxSaveOptions) ＆ [PptxSaveOptions](https://apireference.aspose.com/cells/java/com.aspose.cells/PptxSaveOptions) 以下に示すようなクラス。
{{% blocks/products/pf/feature-page-code h3="JavaExcelからWordおよびPowerPointへの変換のコード" %}}
```cs
// テンプレートファイルをロードする
var wkb = new Workbook("template.xlsx");
// スプレッドシートをDOCXとして保存
wkb.save("output.docx", new DocxSaveOptions());
// スプレッドシートをPPTXとして保存
wkb.save("output.pptx", new PptxSaveOptions());

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}