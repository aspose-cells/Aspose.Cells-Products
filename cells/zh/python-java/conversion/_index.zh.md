---
title: Microsoft Excel文件转换使用Python via Java
description: 转换Excel XLS，XLSX，ODS，CSV至PDF，XPS，HTML，HTML，JPEG，JPEG，HTML和许多其他形式的码数为076193131313131313。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel格式转换通过Python" h2="将 Excel 文件导入和导出为电子表格、Web、图像和固定布局格式" >}}

{{% blocks/products/pf/feature-page-summary %}}
Python Excel 库加快电子表格编程和转换过程，同时支持流行格式，包括 XLS、XLSX、XLSM、XLSB、XLTX、XLTM、CSV、SpreadsheetML、ODS .它也允许导出Excel文件到PDF, XPS, HTML, MHTML, Plain文本和流行的图像格式，例如 TIFF、JPG、PNG、BMP 和 SVG。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="将 Excel 转换为 XLSX、ODS、SXC 和 FODS" %}}
电子表格格式的相互转换只需要加载一个带有实例的电子表格[工作簿](https://reference.aspose.com/cells/python/asposecells.api/Workbook)并以所需的格式保存回，同时从中选择适当的值[保存格式](https://reference.aspose.com/cells/python/asposecells.api/saveformat)枚举。
{{% blocks/products/pf/feature-page-code h3="Python Excel文件格式转换代码" %}}

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


{{% blocks/products/pf/feature-page-section h2="将 Excel 转换为 PDF、XPS、HTML 和 MD" %}}
专门的类可用于控制特定输出格式的转换过程，例如[Pdf保存选项](https://reference.aspose.com/cells/python/asposecells.api/PdfSaveOptions)将 Excel 文件导出为 PDF，[XpsSave选项](https://reference.aspose.com/cells/python/asposecells.api/XpsSaveOptions)对于 Excel 到 XPS 的转换，[HtmlSave选项](https://reference.aspose.com/cells/python/asposecells.api/HtmlSaveOptions)将 Excel 呈现为 HTML 和[Markdown 保存选项](https://reference.aspose.com/cells/python/asposecells.api/MarkdownSaveOptions)用于 Excel 到 Markdown 的转换。
{{% blocks/products/pf/feature-page-code h3="Python Excel 到 PDF 和 Web 格式的代码" %}}

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

{{% blocks/products/pf/feature-page-section h2="将 JSON 转换为 Excel 并将 Excel 转换为 JSON" %}}
Python 开发人员只需几行代码即可轻松加载 JSON 文件并将其转换为 Excel。同样可以将Excel数据导出为JSON数据。
{{% blocks/products/pf/feature-page-code h3="Python JSON 到 Excel 转换的代码" %}}
```cs
//Load your source json file
workbook = Workbook("Data.json")
//save file to xlsx format
workbook.save("output.xlsx")
```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python Excel 到 JSON 转换的代码" %}}
```cs
//Load your source xlsx file
workbook = Workbook("input.xlsx")
//save file to json format
workbook.save("Data.json")
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="将 Excel 工作表转换为 JPG，BMP、PNG 和 GIF" %}}
 Excel文件的每个工作表都可以转换为不同的图像格式，调用[图像或打印选项](https://reference.aspose.com/cells/python/asposecells.api/ImageOrPrintOptions).setImageFormat 设置图像格式。
{{% blocks/products/pf/feature-page-code h3="Python Excel 到图像转换的代码" %}}
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

{{% blocks/products/pf/feature-page-section h2="将 Excel 转换为 Word & PowerPoint" %}}
使用时可以加载任何电子表格并将其转换为 Word DOCX & PowerPoint PPTX 文件[DocxSave选项](https://reference.aspose.com/cells/python/asposecells.api/DocxSaveOptions) & [PptxSave选项](https://reference.aspose.com/cells/python/asposecells.api/PptxSaveOptions)类如下所示。
{{% blocks/products/pf/feature-page-code h3="Excel 到 Word 的 Python 代码 & PowerPoint 转换" %}}
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

{{< blocks/products/pf/feature-page-options pairs="xls-to-pptx xlsx-to-pptx xlsb-to-pptx xlsm-to-pptx html-to-pptx mhtml-to-pptx ods-to-pptx tsv-to-pptx csv-to-pptx json-to-pptx numbers-to-pptx prn-to-pptx xlt-to-pptx xltx-to-pptx xltm-to-pptx ots-to-pptx sxc-to-pptx png-to-pptx jpg-to-pptx txt-to-pptx xls-to-docx xlsx-to-docx xlsb-to-docx xlsm-to-docx html-to-docx mhtml-to-docx ods-to-docx tsv-to-docx csv-to-docx json-to-docx numbers-to-docx prn-to-docx xlt-to-docx xltx-to-docx xltm-to-docx ots-to-docx sxc-to-docx png-to-docx jpg-to-docx txt-to-docx" >}}
