---
title:  Microsoft Excel 文件转换 via Java
description: Aspose.Cells for Java 图书馆。只需几行 Java 代码即可转换 EXCEL、JSON、PDF、XML、HTML、TXT、TSV、CSV、SQL、JPG、PNG 等格式。
keywords: [Java Aspose.Cells., excel to pdf., excel to json., html to xps., csv to json., json to pdf., xml to excel and Convert files between various formats in Java]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel 文件转换 via Java" h2="将 Microsoft Excel 文档另存为电子表格、Web、图像和固定布局格式" >}}

{{% blocks/products/pf/feature-page-summary %}}
对于任何**Excel转换器**应用程序或解决方案，Java Excel 库可加速电子表格编程和转换过程，同时处理多种格式，包括 XLS、XLSX、XLSM、XLSB、XLTX、XLTM、CSV、SpreadsheetML、0761934 81. 它还允许*将Excel文件转换为PDF**， XPS、HTML、MHTML、纯文本和流行图像格式，例如 TIFF、JPG、PNG、BMP 和 SVG。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Microsoft Excel 格式的相互转换" %}}
电子表格格式的相互转换只需要加载带有实例的电子表格[练习册](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)并以所需的格式保存，同时从中选择适当的值[保存格式](https://reference.aspose.com/cells/java/com.aspose.cells/SaveFormat)枚举。
{{% blocks/products/pf/feature-page-code h3="Java Excel 文件格式转换示例代码" %}}

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


{{% blocks/products/pf/feature-page-section h2="将 Excel 转换为 PDF、XPS、HTML 和 MD" %}}
专门的类可用于控制特定输出格式的转换过程，例如[Pdf保存选项](https://reference.aspose.com/cells/java/com.aspose.cells/PdfSaveOptions)将 Excel 文件转换为 PDF，[Xps保存选项](https://reference.aspose.com/cells/java/com.aspose.cells/XpsSaveOptions)将 Excel 导出为 XPS，[Html保存选项](https://reference.aspose.com/cells/java/com.aspose.cells/HtmlSaveOptions)将 Excel 呈现为 HTML 和[Markdown保存选项](https://reference.aspose.com/cells/java/com.aspose.cells/MarkdownSaveOptions)用于 Excel 到 Markdown 的转换。
{{% blocks/products/pf/feature-page-code h3="Java Excel 到 PDF 和 Web 格式的示例代码" %}}

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

{{% blocks/products/pf/feature-page-section h2="将 JSON 转换为 Excel，并将 Excel 转换为 JSON" %}}
 JSON 数据可以导入到 Workbook 类的实例中[JSONUtility.importData](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility#importData)用于进一步处理或简单转换为任何支持的格式。同样，工作表数据可以通过创建一个导出为JSON[范围](https://reference.aspose.com/cells/java/com.aspose.cells/range)或细胞并调用[导出范围ToJson](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility)方法。
{{% blocks/products/pf/feature-page-code h3="Java JSON 到 Excel 转换的代码" %}}
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

{{% blocks/products/pf/feature-page-code h3="Java Excel 到 JSON 转换的源代码" %}}
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

{{% blocks/products/pf/feature-page-section h2="将 Excel 工作表保存到图像" %}}
每个工作表都可以转换为不同的图像格式，包括 JPG、BMP、PNG 和 GIF，由 ImageType 属性设置。对于任何**将 Excel 转换为图像**案例，从链接中选择相关案例。
{{% blocks/products/pf/feature-page-code h3="Java Excel 到图像转换的代码" %}}
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

{{% blocks/products/pf/feature-page-section h2="将 Microsoft Excel 转换为 Word 和 PowerPoint" %}}
使用时可以加载任何电子表格并将其转换为 Word DOCX 和 PowerPoint PPTX 文件[Docx保存选项](https://reference.aspose.com/cells/java/com.aspose.cells/DocxSaveOptions) & [Pptx保存选项](https://reference.aspose.com/cells/java/com.aspose.cells/PptxSaveOptions)类如下所示。
{{% blocks/products/pf/feature-page-code h3="Java Excel 到 Word 的代码 & PowerPoint 转换" %}}
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
