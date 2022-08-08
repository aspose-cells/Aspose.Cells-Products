---
title: 通过 Python 转换 Microsoft Excel 文件 
url: /zh/python/conversion/
description: 只需几行 Python 代码，即可将 Excel XLS、XLSX、ODS、CSV 转换为 PDF、XPS、HTML、JPEG、HTML 和许多其他流行格式。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> 通过 Python 进行 Excel 格式转换" h2="将 Excel 文件导入和导出为电子表格、Web、图像和固定布局格式" >}}

{{% blocks/products/pf/feature-page-summary %}}
Python Excel 库可加快电子表格编程和转换过程，同时支持流行的格式，包括 XLS、XLSX、XLSM、XLSB、XLTX、XLTM、CSV、SpreadsheetML、ODS。它还允许将 Excel 文件导出为 PDF、XPS、HTML、MHTML、纯文本和流行的图像格式，如 TIFF、JPG、PNG、BMP 和 SVG。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="将 Excel 转换为 XLSX、ODS、SXC 和 FODS" %}}
电子表格格式的相互转换只需要加载一个带有实例的电子表格 [工作簿](https://reference.aspose.com/cells/python/asposecells.api/Workbook) 并在选择适当的值时以所需的格式保存 [保存格式](https://reference.aspose.com/cells/python/asposecells.api/saveformat) 枚举。
{{% blocks/products/pf/feature-page-code h3="Python Excel 文件格式转换代码" %}}

```cs
// 加载模板文件
workbook = Workbook("Book1.xls")
  
// 保存为 XLSX、ODS、SXC 和 FODS 格式
workbook.save("output.xlsx", SaveFormat.XLSX);
workbook.save("output.ods", SaveFormat.ODS);
workbook.save("output.scx", SaveFormat.SXC);
workbook.save("output.fods", SaveFormat.FODS);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="将 Excel 转换为 PDF、XPS、HTML 和 MD" %}}
可以使用专门的类来控制特定输出格式的转换过程，例如 [PdfSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/PdfSaveOptions) 将 Excel 文件导出为 PDF， [XpsSave 选项](https://reference.aspose.com/cells/python/asposecells.api/XpsSaveOptions) 对于 Excel 到 XPS 的转换， [HtmlSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/HtmlSaveOptions) 将 Excel 呈现为 HTML 和 [MarkdownSave 选项](https://reference.aspose.com/cells/python/asposecells.api/MarkdownSaveOptions) 用于 Excel 到 Markdown 的转换。 
{{% blocks/products/pf/feature-page-code h3="Python Excel 到 PDF 和 Web 格式的代码" %}}

```cs
// 从光盘加载模板 Excel 文件
book = Workbook("template.xlsx")

// 以 PDF_A_1_B 格式保存 Excel
pdfOptions = PdfSaveOptions()
pdfOptions.setCompliance(PdfCompliance.PDF_A_1_B)
book.save("output.pdf", pdfOptions);

// 在 XPS 中保存 Excel，每个工作表只有 1 页
xpsOptions = XpsSaveOptions()
xpsOptions.setOnePagePerSheet(True)
book.save("output.xps", xpsOptions);

// 将带有图像的 Excel 保存为 Base64
htmlOptions = HtmlSaveOptions()
htmlOptions.setExportImagesAsBase64(True)
book.save("output.html", htmlOptions);

// 将 Excel 保存在 Markdown (MD) 中，同时保留单元格格式
mdOptions = MarkdownSaveOptions()
mdOptions.setFormatStrategy(CellValueFormatStrategy.CELL_STYLE)
book.save("output.md", mdOptions);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="将 JSON 转换为 Excel 和 Excel 转换为 JSON" %}}
Python 开发人员只需几行代码即可轻松加载 JSON 文件并将其转换为 Excel。同样，可以将 Excel 数据导出为 JSON 数据。
{{% blocks/products/pf/feature-page-code h3="Python JSON 到 Excel 转换的代码" %}}
```cs
//加载源 json 文件
workbook = Workbook("Data.json")
//将文件保存为 xlsx 格式
workbook.save("output.xlsx")

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python Excel 到 JSON 转换的代码" %}}
```cs
//加载源 xlsx 文件
workbook = Workbook("input.xlsx")
//将文件保存为 json 格式
workbook.save("Data.json")

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="将 Excel 工作表转换为 JPG、BMP、PNG 和 GIF" %}}
Excel 文件的每个工作表都可以转换为不同的图像格式，调用 [图像或打印选项](https://reference.aspose.com/cells/python/asposecells.api/ImageOrPrintOptions).setImageFormat 设置图像格式。 
{{% blocks/products/pf/feature-page-code h3="Python Excel 到图像转换的代码" %}}
```cs
// 加载模板电子表格
workbook = Workbook("template.xlsx")
// 创建和设置 ImageOrPrintOptions 的实例
options = ImageOrPrintOptions()
// 设置输出图像格式
options.setImageFormat(ImageFormat.getPng())
// 为集合中的第一个工作表创建 SheetRender
sheet = workbook.getWorksheets().get(0)
sr = SheetRender(sheet, options)
// 将工作表渲染为图像
sr.toImage(0, "output.jpg")

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="将 Excel 转换为 Word 和 PowerPoint" %}}
使用时可以加载任何电子表格并将其转换为 Word DOCX 和 PowerPoint PPTX 文件 [DocxSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/DocxSaveOptions) & [PptxSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/PptxSaveOptions) 类如下所示。
{{% blocks/products/pf/feature-page-code h3="Python Excel 到 Word 和 PowerPoint 转换的代码" %}}
```cs
// 加载模板文件
workbook = Workbook("template.xlsx")

// 将电子表格另存为 DOCX
docxOptions = DocxSaveOptions()
workbook.save("output.docx", docxOptions)

// 将电子表格另存为 PPTX
pptxOptions = PptxSaveOptions()
workbook.save("output.pptx", pptxOptions)

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}