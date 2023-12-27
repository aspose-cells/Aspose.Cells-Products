---
title:  Microsoft Conversion de fichiers Excel via C#
description: Aspose.Cells for .NET bibliothèque. Convertissez les formats EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL, JPG, PNG et plus avec seulement quelques lignes de code C#.
keywords: [C# Aspose.Cells., excel to pdf., excel to json., txt to sql., csv to json., json to pdf., xml to excel and Convert files between various formats in C#]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Conversion du format Excel via .NET" h2="Importez et exportez des fichiers Excel aux formats tableur, Web, image et mise en page fixe" >}}

{{% blocks/products/pf/feature-page-summary %}}
La bibliothèque Excel .NET accélère les processus de programmation et de conversion des feuilles de calcul tout en prenant en charge les formats populaires, notamment XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Il permet également d'exporter des fichiers Excel vers PDF, XPS, HTML, MHTML, Plain Formats de texte et d’image populaires tels que TIFF, JPG, PNG, BMP et SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Convertir Excel en XLSX, ODS, SXC et FODS" %}}
 L'interconversion du format de feuille de calcul nécessite uniquement le chargement d'une feuille de calcul avec une instance de[Cahier d'exercices](https://reference.aspose.com/cells/net/aspose.cells/workbook) et sauvegarder dans le format souhaité tout en sélectionnant la valeur appropriée dans[EnregistrerFormat](https://reference.aspose.com/cells/net/aspose.cells/saveformat) énumération.
{{% blocks/products/pf/feature-page-code h3="C# Code pour la conversion du format de fichier Excel" %}}

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


{{% blocks/products/pf/feature-page-section h2="Convertir Excel en PDF, XPS, HTML et MD" %}}
 Des cours spécialisés sont disponibles pour contrôler le processus de conversion pour des formats de sortie spécifiques tels que[Options d'enregistrement PDF](https://reference.aspose.com/cells/net/aspose.cells/pdfsaveoptions) pour exporter des fichiers Excel sous le numéro PDF,[XpsSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/xpssaveoptions) pour la conversion Excel en XPS,[HtmlSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/htmlsaveoptions) pour afficher Excel sous la forme HTML et[MarkdownSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/markdownsaveoptions) pour la conversion Excel vers Markdown.
{{% blocks/products/pf/feature-page-code h3="C# Code pour Excel aux formats PDF et Web" %}}

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

{{% blocks/products/pf/feature-page-section h2="Convertir JSON en Excel et Excel en JSON" %}}
 Les données JSON peuvent être importées dans une instance de[Cells](https://reference.aspose.com/cells/net/aspose.cells/cells) cours avec l'aide de[JsonUtility.ImportData](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/importdata) pour un traitement ultérieur ou une simple conversion vers l’un des formats pris en charge. De la même manière,[Feuille de travail](https://reference.aspose.com/cells/net/aspose.cells/worksheet) les données peuvent être exportées sous JSON en créant un[Gamme](https://reference.aspose.com/cells/net/aspose.cells/range) ou des cellules et en appelant le[JsonUtility.ExportRangeToJson](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/exportrangetojson) méthode.
{{% blocks/products/pf/feature-page-code h3="C# Code pour la conversion JSON en Excel" %}}
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

{{% blocks/products/pf/feature-page-code h3="Code C# pour la conversion Excel vers JSON" %}}
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

{{% blocks/products/pf/feature-page-section h2="Convertir des feuilles de calcul Excel en JPG, BMP, PNG et GIF" %}}
 Chaque feuille de calcul d'un fichier Excel peut être convertie en différents formats d'image définis par le[ImageOrPrintOptions.ImageType](https://reference.aspose.com/cells/net/aspose.cells.rendering/imageorprintoptions/properties/imagetype) propriété. La valeur par défaut est `ImageFormat.Bmp`.
{{% blocks/products/pf/feature-page-code h3="C# Code pour la conversion d\'Excel en image" %}}
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

{{% blocks/products/pf/feature-page-section h2="Convertir Excel en Word & PowerPoint" %}}
Il est possible de charger n'importe quelle feuille de calcul et de la convertir en fichiers Word DOCX et PowerPoint PPTX tout en utilisant[DocxSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/docxsaveoptions) & [PptxSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/pptxsaveoptions) cours comme démontré ci-dessous.
{{% blocks/products/pf/feature-page-code h3="Code C# pour la conversion Excel vers Word et PowerPoint" %}}
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
