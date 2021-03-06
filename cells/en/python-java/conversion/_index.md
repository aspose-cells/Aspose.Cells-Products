---
title: Microsoft Excel File Conversion via Python 
url: /python/conversion/
description: Convert Excel XLS, XLSX, ODS, CSV to PDF, XPS, HTML, JPEG, HTML and many other popular formats with just few lines of Python code.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel Format Conversion via Python" h2="Import & export Excel files as spreadsheet, web, image and fixed-layout formats" >}}

{{% blocks/products/pf/feature-page-summary %}}
Python Excel Library speeds up spreadsheet programming and conversion processes while supporting popular formats including XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. It also allows to export Excel files to PDF, XPS, HTML, MHTML, Plain Text and popular image formats such as TIFF, JPG, PNG, BMP and SVG.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Convert Excel to XLSX, ODS, SXC & FODS" %}}
Inter-conversion of spreadsheet format only requires loading a spreadsheet with an instance of [Workbook](https://reference.aspose.com/cells/python/asposecells.api/Workbook) and saving back in the desired format while selecting appropriate value from [SaveFormat](https://reference.aspose.com/cells/python/asposecells.api/saveformat) enumeration.
{{% blocks/products/pf/feature-page-code h3="Python Code for Excel File Format Conversion" %}}

```cs
// load the template file
workbook = Workbook("Book1.xls")
  
// save as XLSX, ODS, SXC & FODS formats
workbook.save("output.xlsx", SaveFormat.XLSX);
workbook.save("output.ods", SaveFormat.ODS);
workbook.save("output.scx", SaveFormat.SXC);
workbook.save("output.fods", SaveFormat.FODS);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section  h2="Convert Excel to PDF, XPS, HTML & MD" %}}
Specialized classes are available to control the conversion process for specific output formats such as [PdfSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/PdfSaveOptions) to export Excel files as PDF, [XpsSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/XpsSaveOptions) for Excel to XPS conversion, [HtmlSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/HtmlSaveOptions) to render Excel as HTML and [MarkdownSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/MarkdownSaveOptions) for Excel to Markdown conversion. 
{{% blocks/products/pf/feature-page-code h3="Python Code for Excel to PDF and Web Formats" %}}

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
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert">}}

{{% blocks/products/pf/feature-page-section  h2="Convert JSON to Excel & Excel to JSON" %}}
Python developers can easily load & convert JSON files to Excel in just a few lines of code. Similarly, Excel data can be exported to JSON data.
{{% blocks/products/pf/feature-page-code h3="Python Code for JSON to Excel Conversion" %}}
```cs
//Load your source json file
workbook = Workbook("Data.json")
//save file to xlsx format
workbook.save("output.xlsx")
```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python Code for Excel to JSON Conversion" %}}
```cs
//Load your source xlsx file
workbook = Workbook("input.xlsx")
//save file to json format
workbook.save("Data.json")
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section  h2="Convert Excel Worksheets to JPG, BMP, PNG & GIF" %}}
Each worksheet of an Excel file can be converted to different image formats, call [ImageOrPrintOptions](https://reference.aspose.com/cells/python/asposecells.api/ImageOrPrintOptions).setImageFormat to set the image format. 
{{% blocks/products/pf/feature-page-code h3="Python Code for Excel to Image Conversion" %}}
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

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering">}}

{{% blocks/products/pf/feature-page-section  h2="Convert Excel to Word & PowerPoint" %}}
It is possible to load any spreadsheet and convert it to Word DOCX & PowerPoint PPTX files while using [DocxSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/DocxSaveOptions) & [PptxSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/PptxSaveOptions) classes as demonstrated below.
{{% blocks/products/pf/feature-page-code h3="Python code for Excel to Word & PowerPoint Conversion" %}}
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