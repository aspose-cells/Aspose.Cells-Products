---
title: 通過 Python 轉換 Microsoft Excel 文件 

description: 只需幾行 Python 代碼，即可將 Excel XLS、XLSX、ODS、CSV 轉換為 PDF、XPS、HTML、JPEG、HTML 和許多其他流行格式。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> 通過 Python 進行 Excel 格式轉換" h2="將 Excel 文件導入和導出為電子表格、Web、圖像和固定佈局格式" >}}

{{% blocks/products/pf/feature-page-summary %}}
Python Excel 庫可加快電子表格編程和轉換過程，同時支持流行的格式，包括 XLS、XLSX、XLSM、XLSB、XLTX、XLTM、CSV、SpreadsheetML、ODS。它還允許將 Excel 文件導出為 PDF、XPS、HTML、MHTML、純文本和流行的圖像格式，如 TIFF、JPG、PNG、BMP 和 SVG。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="將 Excel 轉換為 XLSX、ODS、SXC 和 FODS" %}}
電子表格格式的相互轉換只需要加載一個帶有實例的電子表格 [工作簿](https://reference.aspose.com/cells/python/asposecells.api/Workbook) 並在選擇適當的值時以所需的格式保存 [保存格式](https://reference.aspose.com/cells/python/asposecells.api/saveformat) 枚舉。
{{% blocks/products/pf/feature-page-code h3="Python Excel 文件格式轉換代碼" %}}

```cs
// 加載模板文件
workbook = Workbook("Book1.xls")
  
// 保存為 XLSX、ODS、SXC 和 FODS 格式
workbook.save("output.xlsx", SaveFormat.XLSX);
workbook.save("output.ods", SaveFormat.ODS);
workbook.save("output.scx", SaveFormat.SXC);
workbook.save("output.fods", SaveFormat.FODS);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="將 Excel 轉換為 PDF、XPS、HTML 和 MD" %}}
可以使用專門的類來控制特定輸出格式的轉換過程，例如 [PdfSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/PdfSaveOptions) 將 Excel 文件導出為 PDF， [XpsSave 選項](https://reference.aspose.com/cells/python/asposecells.api/XpsSaveOptions) 對於 Excel 到 XPS 的轉換， [HtmlSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/HtmlSaveOptions) 將 Excel 呈現為 HTML 和 [MarkdownSave 選項](https://reference.aspose.com/cells/python/asposecells.api/MarkdownSaveOptions) 用於 Excel 到 Markdown 的轉換。 
{{% blocks/products/pf/feature-page-code h3="Python Excel 到 PDF 和 Web 格式的代碼" %}}

```cs
// 從光盤加載模板 Excel 文件
book = Workbook("template.xlsx")

// 以 PDF_A_1_B 格式保存 Excel
pdfOptions = PdfSaveOptions()
pdfOptions.setCompliance(PdfCompliance.PDF_A_1_B)
book.save("output.pdf", pdfOptions);

// 在 XPS 中保存 Excel，每個工作表只有 1 頁
xpsOptions = XpsSaveOptions()
xpsOptions.setOnePagePerSheet(True)
book.save("output.xps", xpsOptions);

// 將帶有圖像的 Excel 保存為 Base64
htmlOptions = HtmlSaveOptions()
htmlOptions.setExportImagesAsBase64(True)
book.save("output.html", htmlOptions);

// 將 Excel 保存在 Markdown (MD) 中，同時保留單元格格式
mdOptions = MarkdownSaveOptions()
mdOptions.setFormatStrategy(CellValueFormatStrategy.CELL_STYLE)
book.save("output.md", mdOptions);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="將 JSON 轉換為 Excel 和 Excel 轉換為 JSON" %}}
Python 開發人員只需幾行代碼即可輕鬆加載 JSON 文件並將其轉換為 Excel。同樣，可以將 Excel 數據導出為 JSON 數據。
{{% blocks/products/pf/feature-page-code h3="Python JSON 到 Excel 轉換的代碼" %}}
```cs
//加載源 json 文件
workbook = Workbook("Data.json")
//將文件保存為 xlsx 格式
workbook.save("output.xlsx")

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python Excel 到 JSON 轉換的代碼" %}}
```cs
//加載源 xlsx 文件
workbook = Workbook("input.xlsx")
//將文件保存為 json 格式
workbook.save("Data.json")

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="將 Excel 工作表轉換為 JPG、BMP、PNG 和 GIF" %}}
Excel 文件的每個工作表都可以轉換為不同的圖像格式，調用 [圖像或打印選項](https://reference.aspose.com/cells/python/asposecells.api/ImageOrPrintOptions).setImageFormat 設置圖像格式。 
{{% blocks/products/pf/feature-page-code h3="Python Excel 到圖像轉換的代碼" %}}
```cs
// 加載模板電子表格
workbook = Workbook("template.xlsx")
// 創建和設置 ImageOrPrintOptions 的實例
options = ImageOrPrintOptions()
// 設置輸出圖像格式
options.setImageFormat(ImageFormat.getPng())
// 為集合中的第一個工作表創建 SheetRender
sheet = workbook.getWorksheets().get(0)
sr = SheetRender(sheet, options)
// 將工作表渲染為圖像
sr.toImage(0, "output.jpg")

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="將 Excel 轉換為 Word 和 PowerPoint" %}}
使用時可以加載任何電子表格並將其轉換為 Word DOCX 和 PowerPoint PPTX 文件 [DocxSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/DocxSaveOptions) & [PptxSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/PptxSaveOptions) 類如下所示。
{{% blocks/products/pf/feature-page-code h3="Python Excel 到 Word 和 PowerPoint 轉換的代碼" %}}
```cs
// 加載模板文件
workbook = Workbook("template.xlsx")

// 將電子表格另存為 DOCX
docxOptions = DocxSaveOptions()
workbook.save("output.docx", docxOptions)

// 將電子表格另存為 PPTX
pptxOptions = PptxSaveOptions()
workbook.save("output.pptx", pptxOptions)

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
