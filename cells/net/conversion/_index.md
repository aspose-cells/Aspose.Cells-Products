---
title: Excel File Conversion via C# 
url: /net/conversion/
description: Convert Excel XLS, XLSX, ODS, CSV to PDF, XPS, HTML, JPEG, HTML and many other popular formats with just few lines of C# code.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Excel File Format Conversion via .NET" h2="Export Excel files as spreadsheet, web, image and fixed-layout formats" >}}

{{% blocks/products/pf/feature-page-summary %}}
.NET Excel Library speeds up spreadsheet programming and conversion processes while supporting popular formats including XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. You may also export Excel files to PDF, XPS, HTML, MHTML, Plain Text and popular image formats such as TIFF, JPG, PNG, BMP and SVG.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Convert Excel to Spreadsheets" %}}
Inter-conversion of spreadsheet format only requires loading a spreadsheet with an instance of Workbook and saving back in the desired format while selecting appropriate value from SaveFormat enumeration.
{{% blocks/products/pf/feature-page-code h3="C# code for Excel file conversion" %}}

```cs
// load the template file
var workbook = new Aspose.Cells.Workbook("template.xls");
// save as XLSX, ODS, SXC & FODS formats
workbook.Save("output.xlsx", Aspose.Cells.SaveFormat.Xlsx);
workbook.Save("output.ods", Aspose.Cells.SaveFormat.ODS);
workbook.Save("output.scx", Aspose.Cells.SaveFormat.SXC);
workbook.Save("output.fods", Aspose.Cells.SaveFormat.FODS);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}

{{% blocks/products/pf/feature-page-section  h2="Convert JSON to Excel & Excel to JSON" %}}
JSON data can be imported into an instance of [Cells](https://apireference.aspose.com/cells/net/aspose.cells/cells) class with the help of [JsonUtility.ImportData](https://apireference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/importdata) for further processing or simple conversion to any of the supported formats. Similarly, [Worksheet](https://apireference.aspose.com/cells/net/aspose.cells/worksheet) data can be exported as JSON by creating a [Range](https://apireference.aspose.com/cells/net/aspose.cells/range) or cells and calling the [JsonUtility.ExportRangeToJson](https://apireference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/exportrangetojson) method.
{{% blocks/products/pf/feature-page-code h3="C# code for JSON to Excel conversion" %}}
```cs
// create a Workbook object
var workbook = new Cells.Workbook();
var worksheet = workbook.Worksheets[0];
// read JSON data from file
string jsonInput = File.ReadAllText("Data.json");
// set JsonLayoutOptions to treat Arrays as Table
var options = new Cells.Utility.JsonLayoutOptions();
options.ArrayAsTable = true;
// import JSON data to worksheet starting at cell A1
Cells.Utility.JsonUtility.ImportData(jsonInput, worksheet.Cells, 0, 0, options);
// save resultant file in XLSX format
workbook.Save("output.xlsx", Cells.SaveFormat.Auto); 
```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# code for Excel to JSON conversion" %}}
```cs
// load XLSX file with an instance of Workbook
var workbook = new Workbook("template.xlsx", new LoadOptions(Cells.LoadFormat.Auto));
// access CellsCollection of the worksheet containing data to be converted
var cells = workbook.Worksheets[0].Cells;
// create & set ExportRangeToJsonOptions for advanced options
var exportOptions = new Utility.ExportRangeToJsonOptions();
// create a range of cells containing data to be exported
var range = cells.CreateRange(0, 0, cells.LastCell.Row + 1, cells.LastCell.Column + 1);
// export range as JSON data
string jsonData = Cells.Utility.JsonUtility.ExportRangeToJson(range, exportOptions);
// write data file to disc in JSON format
System.IO.File.WriteAllText("output.json", jsonData); 
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section  h2="Convert Excel Worksheets to JPG, BMP, PNG & GIF" %}}
Each worksheet of an Excel file can be converted to different image formats set by the [ImageOrPrintOptions.ImageType](https://apireference.aspose.com/cells/net/aspose.cells.rendering/imageorprintoptions/properties/imagetype) property. Default value is `ImageFormat.Bmp`.
{{% blocks/products/pf/feature-page-code h3="C# code for Excel to image conversion" %}}
```cs
// load template spreadsheet
var workbook = new Aspose.Cells.Workbook("template.xlsx");
// create & set an instance of ImageOrPrintOptions
var options = new Aspose.Cells.Rendering.ImageOrPrintOptions();
options.OnePagePerSheet = true;
// set output image format
options.ImageType = Aspose.Cells.Drawing.ImageType.Jpeg;
// create SheetRender for first worksheet in the collection
var render = new Aspose.Cells.Rendering.SheetRender(workbook.Worksheets[0], options);
// render worksheet to image
render.ToImage(0, "output.jpeg");
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xls-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif xlsm-to-emf xls-to-bmp xls-to-gif xls-to-emf" >}}

{{% blocks/products/pf/feature-page-section  h2="Convert Excel to Word & PowerPoint" %}}
It is possible to load any spreadsheet and convert it to Word DOCX & PowerPoint PPTX files while using [DocxSaveOptions](https://apireference.aspose.com/cells/net/aspose.cells/docxsaveoptions) & [PptxSaveOptions](https://apireference.aspose.com/cells/net/aspose.cells/pptxsaveoptions) classes as demonstrated below.
{{% blocks/products/pf/feature-page-code h3="C# code for Excel to Word & PowerPoint conversion" %}}
```cs
// load the template file
var workbook = new Aspose.Cells.Workbook("template.xlsx");
// save spreadsheet as DOCX
workbook.Save("output.docx", new Aspose.Cells.DocxSaveOptions());
// save spreadsheet as PPTX
workbook.Save("output.pptx", new Aspose.Cells.PptxSaveOptions());
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-faq %}}

{{< blocks/products/pf/feature-page-faq-item question="Which formats does it support?" answer="More than 35 popular formats are supported at the moment. Those include XLS, XLSX, Markdown, FODS, ODS, HTML, PDF, XPS, DOCX, PPT and more.">}}

{{< blocks/products/pf/feature-page-faq-item odd="true" question="Do you have a demo that I can quickly try?" answer="Yes, please try the live demos for [Conversion](https://products.aspose.app/cells/conversion)">}}
{{% /blocks/products/pf/feature-page-faq %}}

{{% blocks/products/pf/feature-page-about-product h4="About Aspose.Cells" %}}
It is an Excel Spreadsheet Programming API to build cross-platform applications having the ability to generate, modify, convert, render and print spreadsheets without any dependencies. 
{{% /blocks/products/pf/feature-page-about-product %}}