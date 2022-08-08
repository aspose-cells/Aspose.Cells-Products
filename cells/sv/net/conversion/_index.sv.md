---
title: Microsoft Excel-filkonvertering via C# 
url: /sv/net/conversion/
description: Konvertera Excel XLS, XLSX, ODS, CSV till PDF, XPS, HTML, JPEG, HTML och många andra populära format med bara några rader med C#-kod.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel-formatkonvertering via .NET" h2="Importera och exportera Excel-filer som kalkylblad, webb, bild och format med fast layout" >}}

{{% blocks/products/pf/feature-page-summary %}}
.NET Excel Library snabbar upp kalkylarksprogrammering och konverteringsprocesser samtidigt som det stöder populära format inklusive XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Det gör det också möjligt att exportera Excel-filer till PDF, XPS, HTML, MHTML, vanlig text och populära bildformat som TIFF, JPG, PNG, BMP och SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Konvertera Excel till XLSX, ODS, SXC & FODS" %}}
Interkonvertering av kalkylarksformat kräver bara att ett kalkylblad laddas med en instans av [Arbetsbok](https://reference.aspose.com/cells/net/aspose.cells/workbook) och spara tillbaka i önskat format samtidigt som du väljer lämpligt värde från [SaveFormat](https://reference.aspose.com/cells/net/aspose.cells/saveformat) uppräkning.
{{% blocks/products/pf/feature-page-code h3="C# Kod för konvertering av Excel-filformat" %}}

```cs
// ladda mallfilen
var workbook = new Aspose.Cells.Workbook("template.xls");
// spara som XLSX-, ODS-, SXC- och FODS-format
workbook.Save("output.xlsx", Aspose.Cells.SaveFormat.Xlsx);
workbook.Save("output.ods", Aspose.Cells.SaveFormat.Ods);
workbook.Save("output.scx", Aspose.Cells.SaveFormat.Sxc);
workbook.Save("output.fods", Aspose.Cells.SaveFormat.Fods);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Konvertera Excel till PDF, XPS, HTML och MD" %}}
Specialiserade klasser finns tillgängliga för att styra konverteringsprocessen för specifika utdataformat som t.ex [PdfSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/pdfsaveoptions) för att exportera Excel-filer som PDF, [XpsSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/xpssaveoptions) för konvertering av Excel till XPS, [HtmlSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/htmlsaveoptions) att rendera Excel som HTML och [MarkdownSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/markdownsaveoptions) för Excel till Markdown-konvertering. 
{{% blocks/products/pf/feature-page-code h3="C# Kod för Excel till PDF- och webbformat" %}}

```cs
// ladda mall Excel-fil från skiva
var book = new Aspose.Cells.Workbook("template.xlsx");
// spara Excel i PDF/A-1a-format
book.Save("output.pdf", new Aspose.Cells.PdfSaveOptions() { Compliance = PdfComplianceVersion.PdfA1a });
// spara Excel i XPS med 1 sida per kalkylblad
book.Save("output.xps", new Aspose.Cells.XpsSaveOptions() { OnePagePerSheet = true });
// spara Excel i HTML med bilder som Base64
book.Save("output.html", new Aspose.Cells.HtmlSaveOptions() { ExportImagesAsBase64 = true });
// spara Excel i Markdown (MD) samtidigt som du behåller cellformateringen
book.Save("output.md", new Aspose.Cells.MarkdownSaveOptions() { FormatStrategy = Cells.CellValueFormatStrategy.CellStyle });

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="Konvertera JSON till Excel & Excel till JSON" %}}
JSON-data kan importeras till en instans av [Cells](https://reference.aspose.com/cells/net/aspose.cells/cells) klass med hjälp av [JsonUtility.ImportData](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/importdata) för vidare bearbetning eller enkel konvertering till något av de format som stöds. Liknande, [Arbetsblad](https://reference.aspose.com/cells/net/aspose.cells/worksheet) data kan exporteras som JSON genom att skapa en [Räckvidd](https://reference.aspose.com/cells/net/aspose.cells/range) eller celler och ringer till [JsonUtility.ExportRangeToJson](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/exportrangetojson) metod.
{{% blocks/products/pf/feature-page-code h3="C# Kod för JSON till Excel-konvertering" %}}
```cs
// skapa ett arbetsboksobjekt
var workbook = new Cells.Workbook();
var worksheet = workbook.Worksheets[0];
// läsa JSON-data från filen
string jsonInput = File.ReadAllText("Data.json");
// ställ in JsonLayoutOptions för att behandla arrayer som tabell
var options = new Cells.Utility.JsonLayoutOptions();
options.ArrayAsTable = true;
// importera JSON-data till kalkylblad från cell A1
Cells.Utility.JsonUtility.ImportData(jsonInput, worksheet.Cells, 0, 0, options);
// spara den resulterande filen i XLSX-format
workbook.Save("output.xlsx", Cells.SaveFormat.Auto); 

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Kod för Excel till JSON-konvertering" %}}
```cs
// ladda XLSX-fil med en instans av Workbook
var workbook = new Workbook("template.xlsx", new LoadOptions(Cells.LoadFormat.Auto));
// få tillgång till CellsCollection av kalkylbladet som innehåller data som ska konverteras
var cells = workbook.Worksheets[0].Cells;
// skapa & ställ in ExportRangeToJsonOptions för avancerade alternativ
var exportOptions = new Utility.ExportRangeToJsonOptions();
// skapa ett intervall av celler som innehåller data som ska exporteras
var range = cells.CreateRange(0, 0, cells.LastCell.Row + 1, cells.LastCell.Column + 1);
// exportera intervall som JSON-data
string jsonData = Cells.Utility.JsonUtility.ExportRangeToJson(range, exportOptions);
// skriv datafil till skiva i JSON-format
System.IO.File.WriteAllText("output.json", jsonData); 

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Konvertera Excel-kalkylblad till JPG, BMP, PNG och GIF" %}}
Varje kalkylblad i en Excel-fil kan konverteras till olika bildformat som ställs in av [ImageOrPrintOptions.ImageType](https://reference.aspose.com/cells/net/aspose.cells.rendering/imageorprintoptions/properties/imagetype) fast egendom. Standardvärdet är `ImageFormat.Bmp`.
{{% blocks/products/pf/feature-page-code h3="C# Kod för konvertering av Excel till bild" %}}
```cs
// ladda mallkalkylblad
var workbook = new Aspose.Cells.Workbook("template.xlsx");
// skapa och ange en instans av ImageOrPrintOptions
var options = new Aspose.Cells.Rendering.ImageOrPrintOptions();
options.OnePagePerSheet = true;
// ställ in bildformat för utdata
options.ImageType = Aspose.Cells.Drawing.ImageType.Jpeg;
// skapa SheetRender för det första kalkylbladet i samlingen
var render = new Aspose.Cells.Rendering.SheetRender(workbook.Worksheets[0], options);
// rendera kalkylblad till bild
render.ToImage(0, "output.jpg");

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Konvertera Excel till Word & PowerPoint" %}}
Det är möjligt att ladda vilket kalkylblad som helst och konvertera det till Word DOCX- och PowerPoint PPTX-filer medan du använder det [DocxSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/docxsaveoptions) & [PptxSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/pptxsaveoptions) klasser som visas nedan.
{{% blocks/products/pf/feature-page-code h3="C#-kod för konvertering av Excel till Word och PowerPoint" %}}
```cs
// ladda mallfilen
var workbook = new Aspose.Cells.Workbook("template.xlsx");
// spara kalkylblad som DOCX
workbook.Save("output.docx", new Aspose.Cells.DocxSaveOptions());
// spara kalkylblad som PPTX
workbook.Save("output.pptx", new Aspose.Cells.PptxSaveOptions());

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}