---
title:  Microsoft Excel-filkonvertering via C#
description: Konvertera Excel XLS, XLSX, ODS, CSV till PDF, XPS, HTML, JPEG, JPEG, 076183, 076183, 8 och bara 1 164 format med 8 andra 4 format kod.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel-formatkonvertering via .NET" h2="Importera och exportera Excel-filer som kalkylblad, webb, bild och format med fast layout" >}}

{{% blocks/products/pf/feature-page-summary %}}
.NET Excel Library snabbar upp kalkylbladsprogrammering och konverteringsprocesser samtidigt som det stöder populära format inklusive XLS, XLSX, XLSM, XLSB, XLTX, 0761607341, 8731, 18, 18, 18, 18, 18, 18, 18, 18, 18, 18, 6193481. Det gör det också möjligt att exportera Excel-filer till PDF, XPS, HTML, MHTML, Plain Text och populära bildformat som TIFF, JPG, PNG, BMP och SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Konvertera Excel till XLSX, ODS, SXC & FODS" %}}
 Interkonvertering av kalkylarksformat kräver bara att ett kalkylblad laddas med en instans av[Arbetsbok](https://reference.aspose.com/cells/net/aspose.cells/workbook) och spara tillbaka i önskat format samtidigt som du väljer lämpligt värde från[SaveFormat](https://reference.aspose.com/cells/net/aspose.cells/saveformat) uppräkning.
{{% blocks/products/pf/feature-page-code h3="C# Kod för konvertering av Excel-filformat" %}}

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


{{% blocks/products/pf/feature-page-section h2="Konvertera Excel till PDF, XPS, HTML & MD" %}}
 Specialiserade klasser finns tillgängliga för att styra konverteringsprocessen för specifika utdataformat som t.ex[PdfSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/pdfsaveoptions) för att exportera Excel-filer som PDF,[XpsSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/xpssaveoptions) för konvertering av Excel till XPS,[HtmlSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/htmlsaveoptions) för att återge Excel som HTML och[MarkdownSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/markdownsaveoptions) för konvertering från Excel till Markdown.
{{% blocks/products/pf/feature-page-code h3="C# Kod för Excel till PDF och webbformat" %}}

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

{{% blocks/products/pf/feature-page-section h2="Konvertera JSON till Excel & Excel till JSON" %}}
 JSON data kan importeras till en instans av[Cells](https://reference.aspose.com/cells/net/aspose.cells/cells) klass med hjälp av[JsonUtility.ImportData](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/importdata)för vidare bearbetning eller enkel konvertering till något av de format som stöds. Liknande,[Arbetsblad](https://reference.aspose.com/cells/net/aspose.cells/worksheet) data kan exporteras som JSON genom att skapa en[Räckvidd](https://reference.aspose.com/cells/net/aspose.cells/range) eller celler och ringer till[JsonUtility.ExportRangeToJson](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/exportrangetojson) metod.
{{% blocks/products/pf/feature-page-code h3="C# Kod för JSON till Excel-konvertering" %}}
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

{{% blocks/products/pf/feature-page-code h3="C# Kod för Excel till JSON Konvertering" %}}
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

{{% blocks/products/pf/feature-page-section h2="Konvertera Excel-kalkylblad till JPG, BMP, PNG och GIF" %}}
 Varje kalkylblad i en Excel-fil kan konverteras till olika bildformat som ställs in av[ImageOrPrintOptions.ImageType](https://reference.aspose.com/cells/net/aspose.cells.rendering/imageorprintoptions/properties/imagetype) fast egendom. Standardvärdet är `ImageFormat.Bmp`.
{{% blocks/products/pf/feature-page-code h3="C# Kod för konvertering av Excel till bild" %}}
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

{{% blocks/products/pf/feature-page-section h2="Konvertera Excel till Word & PowerPoint" %}}
 Det är möjligt att ladda vilket kalkylblad som helst och konvertera det till Word DOCX- och PowerPoint PPTX-filer medan du använder[DocxSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/docxsaveoptions) & [PptxSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/pptxsaveoptions)klasser som visas nedan.
{{% blocks/products/pf/feature-page-code h3="C# kod för Excel till Word & PowerPoint konvertering" %}}
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
