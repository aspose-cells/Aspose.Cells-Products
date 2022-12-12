---
title: PythonによるMicrosoftExcelファイル変換 

description: Excel XLS、XLSX、ODS、CSVをPDF、XPS、HTML、JPEG、HTML、およびその他の多くの一般的な形式に、わずか数行のPythonコードで変換します。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft <sup>＆reg; </sup>PythonによるExcel形式の変換" h2="Excelファイルをスプレッドシート、Web、画像、および固定レイアウト形式でインポートおよびエクスポートします" >}}

{{% blocks/products/pf/feature-page-summary %}}
Python Excelライブラリは、XLS、XLSX、XLSM、XLSB、XLTX、XLTM、CSV、SpreadsheetML、ODSなどの一般的な形式をサポートしながら、スプレッドシートのプログラミングと変換プロセスを高速化します。また、ExcelファイルをPDF、XPS、HTML、MHTML、プレーンテキスト、およびTIFF、JPG、PNG、BMP、SVGなどの一般的な画像形式にエクスポートすることもできます。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="ExcelをXLSX、ODS、SXC、FODSに変換する" %}}
スプレッドシート形式の相互変換では、次のインスタンスを含むスプレッドシートを読み込むだけで済みます。 [ワークブック](https://reference.aspose.com/cells/python/asposecells.api/Workbook) から適切な値を選択しながら、目的の形式で保存し直します [SaveFormat](https://reference.aspose.com/cells/python/asposecells.api/saveformat) 列挙。
{{% blocks/products/pf/feature-page-code h3="PythonExcelファイル形式変換のコード" %}}

```cs
// テンプレートファイルをロードする
workbook = Workbook("Book1.xls")
  
// XLSX、ODS、SXC、FODS形式で保存
workbook.save("output.xlsx", SaveFormat.XLSX);
workbook.save("output.ods", SaveFormat.ODS);
workbook.save("output.scx", SaveFormat.SXC);
workbook.save("output.fods", SaveFormat.FODS);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="ExcelをPDF、XPS、HTML、MDに変換する" %}}
特殊なクラスを使用して、次のような特定の出力形式の変換プロセスを制御できます。 [PdfSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/PdfSaveOptions) ExcelファイルをPDFとしてエクスポートするには、 [XpsSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/XpsSaveOptions) ExcelからXPSへの変換の場合、 [HtmlSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/HtmlSaveOptions) ExcelをHTMLとしてレンダリングし、 [MarkdownSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/MarkdownSaveOptions) ExcelからMarkdownへの変換用。 
{{% blocks/products/pf/feature-page-code h3="PythonExcelからPDFおよびWeb形式へのコード" %}}

```cs
// ディスクからテンプレートExcelファイルをロードします
book = Workbook("template.xlsx")

// ExcelをPDF_A_1_B形式で保存
pdfOptions = PdfSaveOptions()
pdfOptions.setCompliance(PdfCompliance.PDF_A_1_B)
book.save("output.pdf", pdfOptions);

// ワークシートごとに1ページでExcelをXPSに保存
xpsOptions = XpsSaveOptions()
xpsOptions.setOnePagePerSheet(True)
book.save("output.xps", xpsOptions);

// Base64として画像を含むHTMLでExcelを保存します
htmlOptions = HtmlSaveOptions()
htmlOptions.setExportImagesAsBase64(True)
book.save("output.html", htmlOptions);

// セルの書式を保持しながら、ExcelをMarkdown（MD）に保存します
mdOptions = MarkdownSaveOptions()
mdOptions.setFormatStrategy(CellValueFormatStrategy.CELL_STYLE)
book.save("output.md", mdOptions);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="JSONをExcelに、ExcelをJSONに変換する" %}}
Python開発者は、わずか数行のコードでJSONファイルを簡単にロードしてExcelに変換できます。同様に、ExcelデータをJSONデータにエクスポートできます。
{{% blocks/products/pf/feature-page-code h3="PythonJSONからExcelへの変換のコード" %}}
```cs
//ソースjsonファイルをロードします
workbook = Workbook("Data.json")
//ファイルをxlsx形式で保存します
workbook.save("output.xlsx")

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="PythonExcelからJSONへの変換のコード" %}}
```cs
//ソースxlsxファイルをロードします
workbook = Workbook("input.xlsx")
//ファイルをjson形式で保存します
workbook.save("Data.json")

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="ExcelワークシートをJPG、BMP、PNG、GIFに変換します" %}}
Excelファイルの各ワークシートは、さまざまな画像形式に変換できます。 [ImageOrPrintOptions](https://reference.aspose.com/cells/python/asposecells.api/ImageOrPrintOptions).setImageFormatを使用して、画像形式を設定します。 
{{% blocks/products/pf/feature-page-code h3="PythonExcelから画像への変換のコード" %}}
```cs
// テンプレートスプレッドシートを読み込む
workbook = Workbook("template.xlsx")
// ImageOrPrintOptionsのインスタンスを作成および設定します
options = ImageOrPrintOptions()
// 出力画像フォーマットを設定する
options.setImageFormat(ImageFormat.getPng())
// コレクションの最初のワークシートのSheetRenderを作成します
sheet = workbook.getWorksheets().get(0)
sr = SheetRender(sheet, options)
// ワークシートを画像にレンダリング
sr.toImage(0, "output.jpg")

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="ExcelをWordとPowerPointに変換する" %}}
を使用しながら、任意のスプレッドシートをロードして、WordDOCXおよびPowerPointPPTXファイルに変換することができます。 [DocxSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/DocxSaveOptions) ＆ [PptxSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/PptxSaveOptions) 以下に示すようなクラス。
{{% blocks/products/pf/feature-page-code h3="ExcelからWordおよびPowerPointへの変換のPythonコード" %}}
```cs
// テンプレートファイルをロードする
workbook = Workbook("template.xlsx")

// スプレッドシートをDOCXとして保存
docxOptions = DocxSaveOptions()
workbook.save("output.docx", docxOptions)

// スプレッドシートをPPTXとして保存
pptxOptions = PptxSaveOptions()
workbook.save("output.pptx", pptxOptions)

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
