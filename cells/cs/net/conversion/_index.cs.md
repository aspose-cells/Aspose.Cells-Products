---
title:  Microsoft Převod souborů Excel přes C#
description: Převeďte Excel XLS, XLSX, ODS, CSV na PDF, XPS, HTML, HTML, JPEG, JPEG, JPEG, 43 z mnoha dalších 0817 a 16 pouze populárních formátů 1 kód.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Převod formátu Excel via .NET" h2="Importujte a exportujte soubory Excel jako tabulkový procesor, web, obrázky a formáty s pevným rozložením" >}}

{{% blocks/products/pf/feature-page-summary %}}
.NET Excel Library urychluje programování tabulek a procesy převodu a zároveň podporuje oblíbené formáty včetně XLS, XLSX, XLSM, XLSB, XLTX, XLTM, XLTM, XLTM, XLTM, XLTM, XLTM, XLTM, 871 871 3481. Umožňuje také exportovat soubory Excel do PDF, XPS, HTML, MHTML, Plain Textové a oblíbené formáty obrázků, jako jsou TIFF, JPG, PNG, BMP a SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Převést Excel na XLSX, ODS, SXC a FODS" %}}
 Vzájemná konverze formátu tabulky vyžaduje pouze načtení tabulky s instancí[pracovní sešit](https://reference.aspose.com/cells/net/aspose.cells/workbook) a uložení zpět v požadovaném formátu při výběru vhodné hodnoty z[UložitFormát](https://reference.aspose.com/cells/net/aspose.cells/saveformat) výčet.
{{% blocks/products/pf/feature-page-code h3="C# Kód pro převod formátu souboru Excel" %}}

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


{{% blocks/products/pf/feature-page-section h2="Převést Excel na PDF, XPS, HTML a MD" %}}
 K dispozici jsou specializované třídy pro řízení procesu převodu pro konkrétní výstupní formáty, jako je např[Možnosti PdfSave](https://reference.aspose.com/cells/net/aspose.cells/pdfsaveoptions) exportovat soubory Excel jako PDF,[XpsSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/xpssaveoptions) pro převod Excel na XPS,[HtmlSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/htmlsaveoptions) vykreslit Excel jako HTML a[MarkdownSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/markdownsaveoptions) pro převod Excel na Markdown.
{{% blocks/products/pf/feature-page-code h3="C# Kód pro Excel na PDF a webové formáty" %}}

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

{{% blocks/products/pf/feature-page-section h2="Převeďte JSON na Excel a Excel na JSON" %}}
 JSON data lze importovat do instance[Cells](https://reference.aspose.com/cells/net/aspose.cells/cells) třídy s pomocí[JsonUtility.ImportData](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/importdata)pro další zpracování nebo jednoduchý převod do některého z podporovaných formátů. Podobně,[Pracovní list](https://reference.aspose.com/cells/net/aspose.cells/worksheet) data lze exportovat jako JSON vytvořením a[Rozsah](https://reference.aspose.com/cells/net/aspose.cells/range) nebo buňky a volání[JsonUtility.ExportRangeToJson](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/exportrangetojson) metoda.
{{% blocks/products/pf/feature-page-code h3="C# Kód pro převod JSON na Excel" %}}
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

{{% blocks/products/pf/feature-page-code h3="C# Kód pro Excel na JSON Převod" %}}
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

{{% blocks/products/pf/feature-page-section h2="Převést pracovní listy aplikace Excel do formátu JPG, BMP, PNG a GIF" %}}
 Každý list souboru aplikace Excel lze převést do různých formátů obrázků nastavených v[ImageOrPrintOptions.ImageType](https://reference.aspose.com/cells/net/aspose.cells.rendering/imageorprintoptions/properties/imagetype) vlastnictví. Výchozí hodnota je `ImageFormat.Bmp`.
{{% blocks/products/pf/feature-page-code h3="C# Kód pro převod Excelu na obrázek" %}}
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

{{% blocks/products/pf/feature-page-section h2="Převeďte Excel do Wordu a PowerPoint" %}}
 Je možné načíst jakoukoli tabulku a převést ji na soubory Word DOCX a PowerPoint PPTX při používání[DocxSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/docxsaveoptions) & [Možnosti PptxSave](https://reference.aspose.com/cells/net/aspose.cells/pptxsaveoptions)třídy, jak je ukázáno níže.
{{% blocks/products/pf/feature-page-code h3="C# kód pro Excel do Wordu a PowerPoint převod" %}}
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
