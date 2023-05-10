---
title: Microsoft Python via NET を使用した Excel ファイル変換
description: Excel XLS、XLSX、ODS、CSVからXPS、XPS、HTML、JPEG、HTML、およびHTML、およびPythonコードのほんの一部のラインを持つ他の人気のある形式のある形式を変えてください。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Python 経由の Excel 形式変換" h2="Excel ファイルをスプレッドシート、Web、画像、固定レイアウト形式でインポートおよびエクスポート" >}}

{{% blocks/products/pf/feature-page-summary %}}
Python Excel ライブラリは、XLS、XLSX、XLSM、XLSB、XLTX、XLTM、CSV、SpreadsheetML、ODS などの一般的な形式をサポートしながら、スプレッドシートのプログラミングと変換プロセスを高速化します。 Excel ファイルを PDF、XPS、HTML、MHTML、Plain にエクスポートすることもできます。 TIFF、JPG、PNG、BMP、SVG などのテキストおよび一般的な画像形式。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel を XLSX、ODS、SXC、FODS に変換" %}}
スプレッドシート形式の相互変換には、次のインスタンスを含むスプレッドシートをロードするだけで済みます。[ワークブック](https://reference.aspose.com/cells/python-net/aspose.cells/workbook/)から適切な値を選択しながら、目的の形式で保存し直します。[保存形式](https://reference.aspose.com/cells/python-net/aspose.cells/saveformat/)列挙。
{{% blocks/products/pf/feature-page-code h3="Python Excel ファイル形式変換用のコード" %}}

```cs
// load the template file
workbook = Workbook("Book1.xls")
  
// save as XLSX, ODS, SXC & FODS formats
workbook.save("output.xlsx", SaveFormat.XLSX);
workbook.save("output.ods", SaveFormat.ODS);
workbook.save("output.sxc", SaveFormat.SXC);
workbook.save("output.fods", SaveFormat.FODS);
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Excel を PDF、XPS、HTML、MD に変換" %}}
特殊なクラスを使用して、次のような特定の出力形式の変換プロセスを制御できます。[PDF保存オプション](https://reference.aspose.com/cells/python-net/aspose.cells/pdfsaveoptions/)Excel ファイルを PDF としてエクスポートするには、[Xps保存オプション](https://reference.aspose.com/cells/python-net/aspose.cells/xpssaveoptions/) Excel から XPS への変換の場合、[HTML保存オプション](https://reference.aspose.com/cells/python-net/aspose.cells/htmlsaveoptions/)Excel を HTML としてレンダリングし、[マークダウン保存オプション](https://reference.aspose.com/cells/python-net/aspose.cells/markdownsaveoptions/)Excel から Markdown への変換用。
{{% blocks/products/pf/feature-page-code h3="Python Excel から PDF および Web 形式のコード" %}}

```cs
// load template Excel file from disc
book = Workbook("template.xlsx")

// save Excel in PDF_A_1_B format
pdfOptions = PdfSaveOptions()
pdfOptions.setCompliance(PdfCompliance.PDF_A_1_B)
book.save("output.pdf", pdfOptions);

// save Excel in XPS with 1 page per worksheet
xpsOptions = XpsSaveOptions()
xpsOptions.setOnePagePerSheet(True)
book.save("output.xps", xpsOptions);

// save Excel in HTML with images as Base64
htmlOptions = HtmlSaveOptions()
htmlOptions.setExportImagesAsBase64(True)
book.save("output.html", htmlOptions);

// save Excel in Markdown (MD) while retaining cell formatting
mdOptions = MarkdownSaveOptions()
mdOptions.setFormatStrategy(CellValueFormatStrategy.CELL_STYLE)
book.save("output.md", mdOptions);
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="JSON を Excel に変換し、Excel を JSON に変換" %}}
Python 開発者は、わずか数行のコードで JSON ファイルを Excel に簡単にロードして変換できます。同様に、Excel データを JSON データにエクスポートできます。
{{% blocks/products/pf/feature-page-code h3="Python JSONからExcelへの変換コード" %}}
```cs
//Load your source json file
workbook = Workbook("Data.json")
//save file to xlsx format
workbook.save("output.xlsx")
```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python Excel のコードから JSON への変換" %}}
```cs
//Load your source xlsx file
workbook = Workbook("input.xlsx")
//save file to json format
workbook.save("Data.json")
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Excel ワークシートを JPG、BMP、PNG、GIF に変換" %}}
 Excel ファイルの各ワークシートは、さまざまな画像形式に変換できます。[画像または印刷オプション](https://reference.aspose.com/cells/python-net/aspose.cells.rendering/imageorprintoptions/) .setImageFormat 画像形式を設定します。
{{% blocks/products/pf/feature-page-code h3="Python Excel から画像への変換用のコード" %}}
```cs
// load template spreadsheet
workbook = Workbook("template.xlsx")
// create & set an instance of ImageOrPrintOptions
options = ImageOrPrintOptions()
// set output image format
options.setImageFormat(ImageFormat.getPng())
// create SheetRender for first worksheet in the collection
sheet = workbook.getWorksheets().get(0)
sr = SheetRender(sheet, options)
// render worksheet to image
sr.toImage(0, "output.jpg")
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Excel を Word に変換 & PowerPoint" %}}
使用中に、任意のスプレッドシートをロードし、Word DOCX & PowerPoint PPTX ファイルに変換することが可能です。[DocxSaveオプション](https://reference.aspose.com/cells/python-net/aspose.cells/docxsaveoptions/) & [Pptx保存オプション](https://reference.aspose.com/cells/python-net/aspose.cells/pptxsaveoptions/)以下に示すようなクラス。
{{% blocks/products/pf/feature-page-code h3="ExcelからWordへのPythonコードとPowerPoint変換" %}}
```cs
// load the template file
workbook = Workbook("template.xlsx")

// save spreadsheet as DOCX
docxOptions = DocxSaveOptions()
workbook.save("output.docx", docxOptions)

// save spreadsheet as PPTX
pptxOptions = PptxSaveOptions()
workbook.save("output.pptx", pptxOptions)
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xls-to-docx xlsx-to-docx xlsb-to-docx xlsm-to-docx html-to-docx mhtml-to-docx ods-to-docx tsv-to-docx csv-to-docx json-to-docx numbers-to-docx prn-to-docx xlt-to-docx xltx-to-docx xltm-to-docx ots-to-docx sxc-to-docx png-to-docx jpg-to-docx txt-to-docx xls-to-pptx xlsx-to-pptx xlsb-to-pptx xlsm-to-pptx html-to-pptx mhtml-to-pptx ods-to-pptx tsv-to-pptx csv-to-pptx json-to-pptx numbers-to-pptx prn-to-pptx xlt-to-pptx xltx-to-pptx xltm-to-pptx ots-to-pptx sxc-to-pptx png-to-pptx jpg-to-pptx txt-to-pptx" >}}
