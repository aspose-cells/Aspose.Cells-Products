---
title: 通过 Java 转换 Microsoft Excel 文件 
url: /zh/java/conversion/
description: 只需几行 Java 代码，即可将 Excel XLS、XLSX、ODS、CSV 转换为 PDF、XPS、HTML、JPEG、HTML 和许多其他流行格式。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 Java 进行 Microsoft<sup>&reg;</sup> Excel 文件转换" h2="将 Microsoft Excel 文档保存为电子表格、Web、图像和固定布局格式" >}}

{{% blocks/products/pf/feature-page-summary %}}
对于任何 **Excel 转换器** 应用程序或解决方案，Java Excel 库可加快电子表格编程和转换过程，同时处理多种格式，包括 XLS、XLSX、XLSM、XLSB、XLTX、XLTM、CSV、SpreadsheetML、ODS。它还允许**将 Excel 文件转换为 PDF**、XPS、HTML、MHTML、纯文本和流行的图像格式，例如 TIFF、JPG、PNG、BMP 和 SVG。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Microsoft Excel 格式的相互转换" %}}
电子表格格式的相互转换只需要加载一个带有实例的电子表格 [工作簿](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 并在选择适当的值时以所需的格式保存 [保存格式](https://reference.aspose.com/cells/java/com.aspose.cells/SaveFormat) 枚举。
{{% blocks/products/pf/feature-page-code h3="Java Excel 文件格式转换的示例代码" %}}

```cs
// 加载源文件
var wkb = new Workbook("sourceFile.xls");
// 保存为 XLSX、ODS、SXC 和 FODS 格式
wkb.save("xlsx-output.xlsx", SaveFormat.XLSX);
wkb.save("ods-output.ods", SaveFormat.ODS);
wkb.save("scx-output.scx", SaveFormat.SXC);
wkb.save("fods-output.fods", SaveFormat.FODS);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-json xlsx-to-pdf xlsx-to-html xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="将 Excel 转换为 PDF、XPS、HTML 和 MD" %}}
可以使用专门的类来控制特定输出格式的转换过程，例如 [PdfSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/PdfSaveOptions) 将 Excel 文件转换为 PDF， [XpsSave 选项](https://reference.aspose.com/cells/java/com.aspose.cells/XpsSaveOptions) 将 Excel 导出为 XPS， [HtmlSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/HtmlSaveOptions) 将 Excel 呈现为 HTML 和 [MarkdownSave 选项](https://reference.aspose.com/cells/java/com.aspose.cells/MarkdownSaveOptions) 用于 Excel 到 Markdown 的转换。 
{{% blocks/products/pf/feature-page-code h3="Java Excel 到 PDF 和 Web 格式的示例代码" %}}

```cs
// 从光盘加载模板 Excel 文件
var bk = new Workbook("source-file.xlsx");

// 使用 Java 将 Excel 转换为 PDF
// 创建 PDF 选项
PdfSaveOptions options = new PdfSaveOptions();
options.setCompliance(PdfCompliance.PDF_A_1_A);

bk.save("excel-to-pdf.pdf", options);
// 在 XPS 中保存 Excel
bk.save("output.xps", new XpsSaveOptions());
// 以 HTML 格式保存 Excel
bk.save("output.html", new HtmlSaveOptions());
// 在 Markdown (MD) 中保存 Excel
bk.save("output.md", new MarkdownSaveOptions());

// 在保存为相关格式之前，可以根据自己的选择设置相关的保存选项

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="将 JSON 转换为 Excel 并将 Excel 转换为 JSON" %}}
JSON 数据可以通过以下方式导入到 Workbook 类的实例中 [JSONUtility.importData](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility#importData) 用于进一步处理或简单转换为任何支持的格式。同样，工作表数据可以通过创建一个 JSON 格式导出 [范围](https://reference.aspose.com/cells/java/com.aspose.cells/range) 或单元格并调用 [exportRangeToJson](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility) 方法。
{{% blocks/products/pf/feature-page-code h3="Java JSON 到 Excel 转换的代码" %}}
```cs
Workbook workbook = new Workbook(path + "source-file.xlsx");
Worksheet wks = workbook.getWorksheets().get(0);
		
// 读取文件
File file = new File(path + "source-data.json");
BufferedReader bufferedReader = new BufferedReader(new FileReader(file));
String jsonInput = "";
String tempString;
while ((tempString = bufferedReader.readLine()) != null) {
	jsonInput = jsonInput + tempString; 
}
bufferedReader.close();
							
// 设置 JsonLayoutOptions
JsonLayoutOptions options = new JsonLayoutOptions();
options.setIgnoreArrayTitle(true);
options.setArrayAsTable(true);

// 导入 JSON 数据
JSONUtility.importData(jsonInput, wks.getCells(), 0, 0, options);

// 保存 Excel 文件
workbook.save(path + "excel-to-json.out.xlsx");

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Java Excel 到 JSON 转换的源代码" %}}
```cs
// 使用 Workbook 实例加载 XLSX 文件
Workbook workbook = new Workbook("sourceFile.xlsx");
// 访问包含要转换的数据的工作表的 CellsCollection
Cells cells = workbook.getWorksheets().get(0).getCells();
// 为高级选项创建和设置 ExportRangeToJsonOptions
ExportRangeToJsonOptions exportOptions = new ExportRangeToJsonOptions();
// 创建一系列包含要导出的数据的单元格
Range range = cells.createRange(0, 0, cells.getLastCell().getRow() + 1, cells.getLastCell().getColumn() + 1);
// 将范围导出为 JSON 数据
String jsonData = JsonUtility.exportRangeToJson(range, exportOptions);
// 以 JSON 格式将数据写入磁盘
BufferedWriter writer = new BufferedWriter(new FileWriter("output.json"));
writer.write(jsonData);
writer.close();    

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="将 Excel 工作表保存到图像" %}}
每个工作表都可以转换为不同的图像格式，包括 JPG、BMP、PNG 和 GIF，由 ImageType 属性设置。对于任何 **Convert Excel to Images** 案例，请从链接中选择相关案例。
{{% blocks/products/pf/feature-page-code h3="Java Excel 到图像转换的代码" %}}
```cs
// 加载模板电子表格
var wkb = new Workbook("template.xlsx");

// 为 ImageOptions 创建一个对象
ImageOrPrintOptions imgOptions = new ImageOrPrintOptions();

// 设置图像类型
imgOptions.setImageType(ImageType.PNG);

// 获取第一个工作表。
Worksheet sheet = wkb.getWorksheets().get(0);

// 为目标工作表创建一个 SheetRender 对象
SheetRender sr = new SheetRender(sheet, imgOptions);
for (int j = 0; j < sr.getPageCount(); j++) {
	// 为工作表生成图像
	sr.toImage(j, dataDir + "WToImage-out" + j + ".png");
}

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="将 Microsoft Excel 转换为 Word 和 PowerPoint" %}}
使用时可以加载任何电子表格并将其转换为 Word DOCX 和 PowerPoint PPTX 文件 [DocxSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/DocxSaveOptions) & [PptxSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/PptxSaveOptions) 类如下所示。
{{% blocks/products/pf/feature-page-code h3="Java Excel 到 Word 和 PowerPoint 转换的代码" %}}
```cs
// 加载模板文件
var wkb = new Workbook("template.xlsx");
// 将电子表格另存为 DOCX
wkb.save("output.docx", new DocxSaveOptions());
// 将电子表格另存为 PPTX
wkb.save("output.pptx", new PptxSaveOptions());

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}