---
title:  Microsoft Excel-bestandsconversie via C#
description: Aspose.Cells for .NET bibliotheek. Converteer EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL, JPG, PNG en meer formaten met slechts enkele regels C#-code.
keywords: [C# Aspose.Cells., excel to pdf., excel to json., txt to sql., csv to json., json to pdf., xml to excel and Convert files between various formats in C#]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Conversie van Excel-indeling via .NET" h2="Importeer en exporteer Excel-bestanden als spreadsheet-, web-, afbeeldings- en vaste lay-outformaten" >}}

{{% blocks/products/pf/feature-page-summary %}}
.NET Excel Library versnelt het programmeren en converteren van spreadsheets en ondersteunt populaire formaten, waaronder XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS Het maakt het ook mogelijk om Excel-bestanden te exporteren naar PDF, XPS, HTML, MHTML, Normaal Tekst en populaire afbeeldingsformaten zoals TIFF, JPG, PNG, BMP en SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Converteer Excel naar XLSX, ODS, SXC en FODS" %}}
 Voor de onderlinge conversie van het spreadsheetformaat is alleen het laden van een spreadsheet nodig met een exemplaar van[Werkboek](https://reference.aspose.com/cells/net/aspose.cells/workbook) en weer opslaan in het gewenste formaat terwijl u de juiste waarde selecteert[Formaat opslaan](https://reference.aspose.com/cells/net/aspose.cells/saveformat) opsomming.
{{% blocks/products/pf/feature-page-code h3="C# Code voor conversie van Excel-bestandsindeling" %}}

```cs
// load the template file
var workbook = new Aspose.Cells.Workbook("template.xls");
// save as XLSX, ODS, SXC & FODS formats
workbook.Save("output.xlsx", Aspose.Cells.SaveFormat.Xlsx);
workbook.Save("output.ods", Aspose.Cells.SaveFormat.Ods);
workbook.Save("output.scx", Aspose.Cells.SaveFormat.Sxc);
workbook.Save("output.fods", Aspose.Cells.SaveFormat.Fods);
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Converteer Excel naar PDF, XPS, HTML en MD" %}}
 Er zijn gespecialiseerde klassen beschikbaar om het conversieproces voor specifieke uitvoerformaten zoals[PdfSaveOpties](https://reference.aspose.com/cells/net/aspose.cells/pdfsaveoptions) om Excel-bestanden te exporteren als PDF,[XpsSaveOpties](https://reference.aspose.com/cells/net/aspose.cells/xpssaveoptions) voor conversie van Excel naar XPS,[HtmlSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/htmlsaveoptions) om Excel weer te geven als HTML en[MarkdownSaveOpties](https://reference.aspose.com/cells/net/aspose.cells/markdownsaveoptions) voor conversie van Excel naar Markdown.
{{% blocks/products/pf/feature-page-code h3="C# Code voor Excel naar PDF en webformaten" %}}

```cs
// load template Excel file from disc
var book = new Aspose.Cells.Workbook("template.xlsx");
// save Excel in PDF/A-1a format
book.Save("output.pdf", new Aspose.Cells.PdfSaveOptions() { Compliance = PdfComplianceVersion.PdfA1a });
// save Excel in XPS with 1 page per worksheet
book.Save("output.xps", new Aspose.Cells.XpsSaveOptions() { OnePagePerSheet = true });
// save Excel in HTML with images as Base64
book.Save("output.html", new Aspose.Cells.HtmlSaveOptions() { ExportImagesAsBase64 = true });
// save Excel in Markdown (MD) while retaining cell formatting
book.Save("output.md", new Aspose.Cells.MarkdownSaveOptions() { FormatStrategy = Cells.CellValueFormatStrategy.CellStyle });
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="Converteer JSON naar Excel en Excel naar JSON" %}}
 JSON-gegevens kunnen worden geïmporteerd in een exemplaar van[Cells](https://reference.aspose.com/cells/net/aspose.cells/cells) klas met behulp van[JsonUtility.ImportData](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/importdata) voor verdere verwerking of eenvoudige conversie naar een van de ondersteunde formaten. Op dezelfde manier,[Werkblad](https://reference.aspose.com/cells/net/aspose.cells/worksheet) gegevens kunnen worden geëxporteerd als JSON door een[Bereik](https://reference.aspose.com/cells/net/aspose.cells/range) of cellen en bel de[JsonUtility.ExportRangeToJson](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/exportrangetojson) methode.
{{% blocks/products/pf/feature-page-code h3="C# Code voor JSON naar Excel-conversie" %}}
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

{{% blocks/products/pf/feature-page-code h3="C# Code voor Excel naar JSON Conversie" %}}
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

{{% blocks/products/pf/feature-page-section h2="Converteer Excel-werkbladen naar JPG, BMP, PNG en GIF" %}}
 Elk werkblad van een Excel-bestand kan worden geconverteerd naar verschillende afbeeldingsformaten die zijn ingesteld door de[ImageOrPrintOptions.ImageType](https://reference.aspose.com/cells/net/aspose.cells.rendering/imageorprintoptions/properties/imagetype) eigendom. De standaardwaarde is `ImageFormat.Bmp`.
{{% blocks/products/pf/feature-page-code h3="C# Code voor conversie van Excel naar afbeelding" %}}
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
render.ToImage(0, "output.jpg");
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Converteer Excel naar Word & PowerPoint" %}}
Het is mogelijk om elk spreadsheet te laden en te converteren naar Word DOCX & PowerPoint PPTX bestanden tijdens het gebruik[DocxSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/docxsaveoptions) & [PptxSaveOpties](https://reference.aspose.com/cells/net/aspose.cells/pptxsaveoptions) klassen zoals hieronder gedemonstreerd.
{{% blocks/products/pf/feature-page-code h3="C#-code voor Excel naar Word en PowerPoint-conversie" %}}
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
