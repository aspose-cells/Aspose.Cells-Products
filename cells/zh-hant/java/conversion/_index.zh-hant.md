---
title:  Microsoft Excel 文件轉換 via Java
description: 轉換Excel XLS，XLSX，ODS，CSV至PDF，XPS，HTML，HTML，JPEG，JPEG，HTML和許多其他形式的碼數為076193131313131313。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel 文件轉換 via Java" h2="將 Microsoft Excel 文檔另存為電子表格、Web、圖像和固定佈局格式" >}}

{{% blocks/products/pf/feature-page-summary %}}
對於任何**Excel轉換器**應用程序或解決方案，Java Excel 庫可加快電子表格編程和轉換過程，同時處理多種格式，包括 XLS、XLSX、XLSM、XLSB、XLTX、XLTM、CSV、SpreadsheetML、07619 3481. 它還允許*將 Excel 文件轉換為 PDF**， XPS、HTML、MHTML、純文本和流行的圖像格式，例如 TIFF、JPG、PNG、BMP 和 SVG。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Microsoft Excel格式相互轉換" %}}
電子表格格式的相互轉換只需要加載一個帶有實例的電子表格[工作簿](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)並以所需的格式保存回，同時從中選擇適當的值[保存格式](https://reference.aspose.com/cells/java/com.aspose.cells/SaveFormat)枚舉。
{{% blocks/products/pf/feature-page-code h3="Java Excel文件格式轉換示例代碼" %}}

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


{{% blocks/products/pf/feature-page-section h2="將 Excel 轉換為 PDF、XPS、HTML 和 MD" %}}
專門的類可用於控制特定輸出格式的轉換過程，例如[Pdf保存選項](https://reference.aspose.com/cells/java/com.aspose.cells/PdfSaveOptions)將 Excel 文件轉換為 PDF，[XpsSave選項](https://reference.aspose.com/cells/java/com.aspose.cells/XpsSaveOptions)將 Excel 導出為 XPS，[HtmlSave選項](https://reference.aspose.com/cells/java/com.aspose.cells/HtmlSaveOptions)將 Excel 呈現為 HTML 和[Markdown 保存選項](https://reference.aspose.com/cells/java/com.aspose.cells/MarkdownSaveOptions)用於 Excel 到 Markdown 的轉換。
{{% blocks/products/pf/feature-page-code h3="Java Excel 到 PDF 和 Web 格式的示例代碼" %}}

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

{{% blocks/products/pf/feature-page-section h2="將 JSON 轉換為 Excel 並將 Excel 轉換為 JSON" %}}
 JSON 數據可以導入到Workbook類的實例中[JSONUtility.importData](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility#importData)用於進一步處理或簡單轉換為任何支持的格式。同樣，工作表數據可以通過創建一個導出為 JSON[範圍](https://reference.aspose.com/cells/java/com.aspose.cells/range)或單元格並調用[exportRangeToJson](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility)方法。
{{% blocks/products/pf/feature-page-code h3="Java JSON 到 Excel 轉換的代碼" %}}
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

{{% blocks/products/pf/feature-page-code h3="Java Excel 到 JSON 轉換的源代碼" %}}
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

{{% blocks/products/pf/feature-page-section h2="將 Excel 工作表保存為圖像" %}}
每個工作表都可以轉換為不同的圖像格式，包括 JPG、BMP、PNG 和 GIF，由 ImageType 屬性設置。對於任何**將 Excel 轉換為圖像**案例，從鏈接中選擇相關案例。
{{% blocks/products/pf/feature-page-code h3="Java Excel 到圖像轉換的代碼" %}}
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

{{% blocks/products/pf/feature-page-section h2="將 Microsoft Excel 轉換為 Word 和 PowerPoint" %}}
使用時可以加載任何電子表格並將其轉換為 Word DOCX & PowerPoint PPTX 文件[DocxSave選項](https://reference.aspose.com/cells/java/com.aspose.cells/DocxSaveOptions) & [PptxSave選項](https://reference.aspose.com/cells/java/com.aspose.cells/PptxSaveOptions)類如下所示。
{{% blocks/products/pf/feature-page-code h3="Java Excel 到 Word 的代碼 & PowerPoint 轉換" %}}
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
