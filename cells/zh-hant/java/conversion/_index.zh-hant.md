---
title: 通過 Java 轉換 Microsoft Excel 文件 

description: 只需幾行 Java 代碼，即可將 Excel XLS、XLSX、ODS、CSV 轉換為 PDF、XPS、HTML、JPEG、HTML 和許多其他流行格式。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通過 Java 進行 Microsoft<sup>&reg;</sup> Excel 文件轉換" h2="將 Microsoft Excel 文檔保存為電子表格、Web、圖像和固定佈局格式" >}}

{{% blocks/products/pf/feature-page-summary %}}
對於任何 **Excel 轉換器** 應用程序或解決方案，Java Excel 庫可加快電子表格編程和轉換過程，同時處理多種格式，包括 XLS、XLSX、XLSM、XLSB、XLTX、XLTM、CSV、SpreadsheetML、ODS。它還允許**將 Excel 文件轉換為 PDF**、XPS、HTML、MHTML、純文本和流行的圖像格式，例如 TIFF、JPG、PNG、BMP 和 SVG。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Microsoft Excel 格式的相互轉換" %}}
電子表格格式的相互轉換只需要加載一個帶有實例的電子表格 [工作簿](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 並在選擇適當的值時以所需的格式保存 [保存格式](https://reference.aspose.com/cells/java/com.aspose.cells/SaveFormat) 枚舉。
{{% blocks/products/pf/feature-page-code h3="Java Excel 文件格式轉換的示例代碼" %}}

```cs
// 加載源文件
var wkb = new Workbook("sourceFile.xls");
// 保存為 XLSX、ODS、SXC 和 FODS 格式
wkb.save("xlsx-output.xlsx", SaveFormat.XLSX);
wkb.save("ods-output.ods", SaveFormat.ODS);
wkb.save("scx-output.scx", SaveFormat.SXC);
wkb.save("fods-output.fods", SaveFormat.FODS);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-json xlsx-to-pdf xlsx-to-html xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="將 Excel 轉換為 PDF、XPS、HTML 和 MD" %}}
可以使用專門的類來控制特定輸出格式的轉換過程，例如 [PdfSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/PdfSaveOptions) 將 Excel 文件轉換為 PDF， [XpsSave 選項](https://reference.aspose.com/cells/java/com.aspose.cells/XpsSaveOptions) 將 Excel 導出為 XPS， [HtmlSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/HtmlSaveOptions) 將 Excel 呈現為 HTML 和 [MarkdownSave 選項](https://reference.aspose.com/cells/java/com.aspose.cells/MarkdownSaveOptions) 用於 Excel 到 Markdown 的轉換。 
{{% blocks/products/pf/feature-page-code h3="Java Excel 到 PDF 和 Web 格式的示例代碼" %}}

```cs
// 從光盤加載模板 Excel 文件
var bk = new Workbook("source-file.xlsx");

// 使用 Java 將 Excel 轉換為 PDF
// 創建 PDF 選項
PdfSaveOptions options = new PdfSaveOptions();
options.setCompliance(PdfCompliance.PDF_A_1_A);

bk.save("excel-to-pdf.pdf", options);
// 在 XPS 中保存 Excel
bk.save("output.xps", new XpsSaveOptions());
// 以 HTML 格式保存 Excel
bk.save("output.html", new HtmlSaveOptions());
// 在 Markdown (MD) 中保存 Excel
bk.save("output.md", new MarkdownSaveOptions());

// 在保存為相關格式之前，可以根據自己的選擇設置相關的保存選項

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="將 JSON 轉換為 Excel 並將 Excel 轉換為 JSON" %}}
JSON 數據可以通過以下方式導入到 Workbook 類的實例中 [JSONUtility.importData](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility#importData) 用於進一步處理或簡單轉換為任何支持的格式。同樣，工作表數據可以通過創建一個 JSON 格式導出 [範圍](https://reference.aspose.com/cells/java/com.aspose.cells/range) 或單元格並調用 [exportRangeToJson](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility) 方法。
{{% blocks/products/pf/feature-page-code h3="Java JSON 到 Excel 轉換的代碼" %}}
```cs
Workbook workbook = new Workbook(path + "source-file.xlsx");
Worksheet wks = workbook.getWorksheets().get(0);
		
// 讀取文件
File file = new File(path + "source-data.json");
BufferedReader bufferedReader = new BufferedReader(new FileReader(file));
String jsonInput = "";
String tempString;
while ((tempString = bufferedReader.readLine()) != null) {
	jsonInput = jsonInput + tempString; 
}
bufferedReader.close();
							
// 設置 JsonLayoutOptions
JsonLayoutOptions options = new JsonLayoutOptions();
options.setIgnoreArrayTitle(true);
options.setArrayAsTable(true);

// 導入 JSON 數據
JSONUtility.importData(jsonInput, wks.getCells(), 0, 0, options);

// 保存 Excel 文件
workbook.save(path + "excel-to-json.out.xlsx");

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Java Excel 到 JSON 轉換的源代碼" %}}
```cs
// 使用 Workbook 實例加載 XLSX 文件
Workbook workbook = new Workbook("sourceFile.xlsx");
// 訪問包含要轉換的數據的工作表的 CellsCollection
Cells cells = workbook.getWorksheets().get(0).getCells();
// 為高級選項創建和設置 ExportRangeToJsonOptions
ExportRangeToJsonOptions exportOptions = new ExportRangeToJsonOptions();
// 創建一系列包含要導出的數據的單元格
Range range = cells.createRange(0, 0, cells.getLastCell().getRow() + 1, cells.getLastCell().getColumn() + 1);
// 將範圍導出為 JSON 數據
String jsonData = JsonUtility.exportRangeToJson(range, exportOptions);
// 以 JSON 格式將數據寫入磁盤
BufferedWriter writer = new BufferedWriter(new FileWriter("output.json"));
writer.write(jsonData);
writer.close();    

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="將 Excel 工作表保存到圖像" %}}
每個工作表都可以轉換為不同的圖像格式，包括 JPG、BMP、PNG 和 GIF，由 ImageType 屬性設置。對於任何 **Convert Excel to Images** 案例，請從鏈接中選擇相關案例。
{{% blocks/products/pf/feature-page-code h3="Java Excel 到圖像轉換的代碼" %}}
```cs
// 加載模板電子表格
var wkb = new Workbook("template.xlsx");

// 為 ImageOptions 創建一個對象
ImageOrPrintOptions imgOptions = new ImageOrPrintOptions();

// 設置圖像類型
imgOptions.setImageType(ImageType.PNG);

// 獲取第一個工作表。
Worksheet sheet = wkb.getWorksheets().get(0);

// 為目標工作表創建一個 SheetRender 對象
SheetRender sr = new SheetRender(sheet, imgOptions);
for (int j = 0; j < sr.getPageCount(); j++) {
	// 為工作表生成圖像
	sr.toImage(j, dataDir + "WToImage-out" + j + ".png");
}

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="將 Microsoft Excel 轉換為 Word 和 PowerPoint" %}}
使用時可以加載任何電子表格並將其轉換為 Word DOCX 和 PowerPoint PPTX 文件 [DocxSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/DocxSaveOptions) & [PptxSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/PptxSaveOptions) 類如下所示。
{{% blocks/products/pf/feature-page-code h3="Java Excel 到 Word 和 PowerPoint 轉換的代碼" %}}
```cs
// 加載模板文件
var wkb = new Workbook("template.xlsx");
// 將電子表格另存為 DOCX
wkb.save("output.docx", new DocxSaveOptions());
// 將電子表格另存為 PPTX
wkb.save("output.pptx", new PptxSaveOptions());

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
