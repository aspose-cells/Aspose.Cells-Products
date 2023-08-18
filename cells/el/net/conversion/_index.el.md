---
title:  Microsoft Μετατροπή αρχείου Excel μέσω C#
description: Μετατρέψτε το Excel XLS, XLSX, ODS, CSV σε PDF, XPS, HTML, JPEG, JPEG, JPEG, 438 με πολλές άλλες 334 δημοφιλείς μορφές και 076 076 81 κωδικός.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Μετατροπή μορφής Excel via .NET" h2="Εισαγωγή και εξαγωγή αρχείων Excel ως υπολογιστικού φύλλου, ιστού, εικόνας και μορφής σταθερής διάταξης" >}}

{{% blocks/products/pf/feature-page-summary %}}
.NET Η Βιβλιοθήκη Excel επιταχύνει τον προγραμματισμό υπολογιστικών φύλλων και τις διαδικασίες μετατροπής ενώ υποστηρίζει δημοφιλείς μορφές, συμπεριλαμβανομένων XLS, XLSX, XLSM, XLSB, XLTX, XLTX, 076113418 ODS. Επιτρέπει επίσης την εξαγωγή αρχείων Excel σε PDF, XPS, HTML, MHTML, Απλό Κείμενο και δημοφιλείς μορφές εικόνας όπως TIFF, JPG, PNG, BMP και SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Μετατροπή Excel σε XLSX, ODS, SXC & FODS" %}}
 Η αλληλομετατροπή της μορφής υπολογιστικού φύλλου απαιτεί μόνο τη φόρτωση ενός υπολογιστικού φύλλου με μια παρουσία του[ΤΕΤΡΑΔΙΟ ΕΡΓΑΣΙΩΝ](https://reference.aspose.com/cells/net/aspose.cells/workbook) και αποθηκεύστε ξανά στην επιθυμητή μορφή ενώ επιλέγετε την κατάλληλη τιμή από[SaveFormat](https://reference.aspose.com/cells/net/aspose.cells/saveformat) απαρίθμηση.
{{% blocks/products/pf/feature-page-code h3="C# Κώδικας για μετατροπή μορφής αρχείου Excel" %}}

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


{{% blocks/products/pf/feature-page-section h2="Μετατροπή Excel σε PDF, XPS, HTML & MD" %}}
 Διατίθενται εξειδικευμένες κλάσεις για τον έλεγχο της διαδικασίας μετατροπής για συγκεκριμένες μορφές εξόδου, όπως π.χ[PdfSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/pdfsaveoptions) για εξαγωγή αρχείων Excel ως PDF,[XpsSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/xpssaveoptions) για μετατροπή Excel σε XPS,[HtmlSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/htmlsaveoptions) για απόδοση του Excel ως HTML και[MarkdownSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/markdownsaveoptions) για τη μετατροπή Excel σε Markdown.
{{% blocks/products/pf/feature-page-code h3="C# Κώδικας για Excel σε PDF και Μορφές Ιστού" %}}

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

{{% blocks/products/pf/feature-page-section h2="Μετατροπή JSON σε Excel & Excel σε JSON" %}}
 Τα δεδομένα JSON μπορούν να εισαχθούν σε μια παρουσία του[Cells](https://reference.aspose.com/cells/net/aspose.cells/cells) τάξη με τη βοήθεια του[JsonUtility.ImportData](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/importdata)για περαιτέρω επεξεργασία ή απλή μετατροπή σε οποιαδήποτε από τις υποστηριζόμενες μορφές. Ομοίως,[Φύλλο εργασίας](https://reference.aspose.com/cells/net/aspose.cells/worksheet) τα δεδομένα μπορούν να εξαχθούν ως JSON δημιουργώντας ένα[Εύρος](https://reference.aspose.com/cells/net/aspose.cells/range) ή κελιά και καλώντας το[JsonUtility.ExportRangeToJson](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/exportrangetojson) μέθοδος.
{{% blocks/products/pf/feature-page-code h3="C# Κωδικός για JSON Μετατροπή σε Excel" %}}
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

{{% blocks/products/pf/feature-page-code h3="C# Μετατροπή κώδικα για Excel σε JSON" %}}
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

{{% blocks/products/pf/feature-page-section h2="Μετατροπή φύλλων εργασίας Excel σε JPG, BMP, PNG & GIF" %}}
 Κάθε φύλλο εργασίας ενός αρχείου Excel μπορεί να μετατραπεί σε διαφορετικές μορφές εικόνας που ορίζονται από το[ImageOrPrintOptions.ImageType](https://reference.aspose.com/cells/net/aspose.cells.rendering/imageorprintoptions/properties/imagetype) ιδιοκτησία. Η προεπιλεγμένη τιμή είναι `ImageFormat.Bmp`.
{{% blocks/products/pf/feature-page-code h3="C# Κώδικας για Μετατροπή Excel σε Εικόνα" %}}
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

{{% blocks/products/pf/feature-page-section h2="Μετατροπή Excel σε Word & PowerPoint" %}}
 Είναι δυνατή η φόρτωση οποιουδήποτε υπολογιστικού φύλλου και η μετατροπή του σε αρχεία Word DOCX & PowerPoint PPTX κατά τη χρήση[DocxSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/docxsaveoptions) & [PptxSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/pptxsaveoptions)τάξεις όπως παρουσιάζεται παρακάτω.
{{% blocks/products/pf/feature-page-code h3="C# κώδικας για Excel σε Word & PowerPoint Μετατροπή" %}}
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
