---
title: Microsoft Excel-bestandsconversie via C# 

description: Converteer Excel XLS, XLSX, ODS, CSV naar PDF, XPS, HTML, JPEG, HTML en vele andere populaire formaten met slechts enkele regels C# code.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel-formaatconversie via .NET" h2="Importeer en exporteer Excel-bestanden als spreadsheet-, web-, afbeeldings- en vaste-layoutformaten" >}}

{{% blocks/products/pf/feature-page-summary %}}
.NET Excel Library versnelt de programmeer- en conversieprocessen van spreadsheets en ondersteunt populaire indelingen zoals XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML en ODS. Het maakt het ook mogelijk om Excel-bestanden te exporteren naar PDF, XPS, HTML, MHTML, platte tekst en populaire afbeeldingsformaten zoals TIFF, JPG, PNG, BMP en SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Converteer Excel naar XLSX, ODS, SXC & FODS" %}}
Interconversie van spreadsheetformaat vereist alleen het laden van een spreadsheet met een instantie van [Werkboek](https://reference.aspose.com/cells/net/aspose.cells/workbook) en terug opslaan in het gewenste formaat terwijl u de juiste waarde selecteert uit [OpslaanFormaat](https://reference.aspose.com/cells/net/aspose.cells/saveformat) opsomming.
{{% blocks/products/pf/feature-page-code h3="C# Code voor conversie van Excel-bestandsindeling" %}}

```cs
// laad het sjabloonbestand
var workbook = new Aspose.Cells.Workbook("template.xls");
// opslaan als XLSX-, ODS-, SXC- en FODS-indelingen
workbook.Save("output.xlsx", Aspose.Cells.SaveFormat.Xlsx);
workbook.Save("output.ods", Aspose.Cells.SaveFormat.Ods);
workbook.Save("output.scx", Aspose.Cells.SaveFormat.Sxc);
workbook.Save("output.fods", Aspose.Cells.SaveFormat.Fods);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Converteer Excel naar PDF, XPS, HTML & MD" %}}
Er zijn gespecialiseerde klassen beschikbaar om het conversieproces voor specifieke uitvoerformaten te regelen, zoals: [PdfOpslaanOpties](https://reference.aspose.com/cells/net/aspose.cells/pdfsaveoptions) om Excel-bestanden als PDF te exporteren, [XpsSave-opties](https://reference.aspose.com/cells/net/aspose.cells/xpssaveoptions) voor Excel naar XPS-conversie, [HtmlOpslaanOpties](https://reference.aspose.com/cells/net/aspose.cells/htmlsaveoptions) om Excel weer te geven als HTML en [MarkdownOpslaanOpties](https://reference.aspose.com/cells/net/aspose.cells/markdownsaveoptions) voor Excel naar Markdown-conversie. 
{{% blocks/products/pf/feature-page-code h3="C# Code voor Excel naar PDF en webformaten" %}}

```cs
// laad sjabloon Excel-bestand van schijf
var book = new Aspose.Cells.Workbook("template.xlsx");
// sla Excel op in PDF/A-1a-formaat
book.Save("output.pdf", new Aspose.Cells.PdfSaveOptions() { Compliance = PdfComplianceVersion.PdfA1a });
// sla Excel op in XPS met 1 pagina per werkblad
book.Save("output.xps", new Aspose.Cells.XpsSaveOptions() { OnePagePerSheet = true });
// sla Excel op in HTML met afbeeldingen als Base64
book.Save("output.html", new Aspose.Cells.HtmlSaveOptions() { ExportImagesAsBase64 = true });
// sla Excel op in Markdown (MD) met behoud van celopmaak
book.Save("output.md", new Aspose.Cells.MarkdownSaveOptions() { FormatStrategy = Cells.CellValueFormatStrategy.CellStyle });

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="Converteer JSON naar Excel en Excel naar JSON" %}}
JSON-gegevens kunnen worden geïmporteerd in een instantie van: [Cells](https://reference.aspose.com/cells/net/aspose.cells/cells) klas met hulp van [JsonUtility.ImportData](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/importdata) voor verdere verwerking of eenvoudige conversie naar een van de ondersteunde formaten. evenzo, [werkblad](https://reference.aspose.com/cells/net/aspose.cells/worksheet) gegevens kunnen worden geëxporteerd als JSON door een [Bereik](https://reference.aspose.com/cells/net/aspose.cells/range) of cellen en bellen met de [JsonUtility.ExportRangeToJson](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/exportrangetojson) methode.
{{% blocks/products/pf/feature-page-code h3="C# Code voor JSON naar Excel-conversie" %}}
```cs
// maak een werkmapobject
var workbook = new Cells.Workbook();
var worksheet = workbook.Worksheets[0];
// lees JSON-gegevens uit bestand
string jsonInput = File.ReadAllText("Data.json");
// stel JsonLayoutOptions in om arrays als tabel te behandelen
var options = new Cells.Utility.JsonLayoutOptions();
options.ArrayAsTable = true;
// importeer JSON-gegevens naar werkblad vanaf cel A1
Cells.Utility.JsonUtility.ImportData(jsonInput, worksheet.Cells, 0, 0, options);
// sla het resulterende bestand op in XLSX-indeling
workbook.Save("output.xlsx", Cells.SaveFormat.Auto); 

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Code voor Excel naar JSON-conversie" %}}
```cs
// laad XLSX-bestand met een exemplaar van Workbook
var workbook = new Workbook("template.xlsx", new LoadOptions(Cells.LoadFormat.Auto));
// toegang tot CellsVerzameling van het werkblad met gegevens die moeten worden geconverteerd
var cells = workbook.Worksheets[0].Cells;
// maak en stel ExportRangeToJsonOptions in voor geavanceerde opties
var exportOptions = new Utility.ExportRangeToJsonOptions();
// maak een celbereik met gegevens om te exporteren
var range = cells.CreateRange(0, 0, cells.LastCell.Row + 1, cells.LastCell.Column + 1);
// bereik exporteren als JSON-gegevens
string jsonData = Cells.Utility.JsonUtility.ExportRangeToJson(range, exportOptions);
// schrijf gegevensbestand naar schijf in JSON-indeling
System.IO.File.WriteAllText("output.json", jsonData); 

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Converteer Excel-werkbladen naar JPG, BMP, PNG & GIF" %}}
Elk werkblad van een Excel-bestand kan worden geconverteerd naar verschillende afbeeldingsindelingen die zijn ingesteld door de [ImageOrPrintOptions.ImageType](https://reference.aspose.com/cells/net/aspose.cells.rendering/imageorprintoptions/properties/imagetype) eigendom. De standaardwaarde is `ImageFormat.Bmp`.
{{% blocks/products/pf/feature-page-code h3="C# Code voor conversie van Excel naar afbeelding" %}}
```cs
// laad sjabloonspreadsheet
var workbook = new Aspose.Cells.Workbook("template.xlsx");
// maak en stel een instantie van ImageOrPrintOptions in
var options = new Aspose.Cells.Rendering.ImageOrPrintOptions();
options.OnePagePerSheet = true;
// uitvoerbeeldformaat instellen
options.ImageType = Aspose.Cells.Drawing.ImageType.Jpeg;
// maak SheetRender voor het eerste werkblad in de verzameling
var render = new Aspose.Cells.Rendering.SheetRender(workbook.Worksheets[0], options);
// werkblad naar afbeelding renderen
render.ToImage(0, "output.jpg");

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Converteer Excel naar Word & PowerPoint" %}}
Het is mogelijk om elke spreadsheet te laden en deze te converteren naar Word DOCX & PowerPoint PPTX-bestanden tijdens gebruik [DocxSave-opties](https://reference.aspose.com/cells/net/aspose.cells/docxsaveoptions) & [PptxOpslaanOpties](https://reference.aspose.com/cells/net/aspose.cells/pptxsaveoptions) klassen zoals hieronder getoond.
{{% blocks/products/pf/feature-page-code h3="C# code voor conversie van Excel naar Word en PowerPoint" %}}
```cs
// laad het sjabloonbestand
var workbook = new Aspose.Cells.Workbook("template.xlsx");
// spreadsheet opslaan als DOCX
workbook.Save("output.docx", new Aspose.Cells.DocxSaveOptions());
// spreadsheet opslaan als PPTX
workbook.Save("output.pptx", new Aspose.Cells.PptxSaveOptions());

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
