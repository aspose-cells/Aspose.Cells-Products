---
title: Μετατροπή αρχείου Microsoft Excel μέσω C# 
url: /el/net/conversion/
description: Μετατρέψτε το Excel XLS, XLSX, ODS, CSV σε PDF, XPS, HTML, JPEG, HTML και πολλές άλλες δημοφιλείς μορφές με λίγες μόνο γραμμές κώδικα C#.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Μετατροπή μορφής Excel μέσω .NET" h2="Εισαγωγή και εξαγωγή αρχείων Excel ως υπολογιστικού φύλλου, ιστού, εικόνας και μορφής σταθερής διάταξης" >}}

{{% blocks/products/pf/feature-page-summary %}}
.NET Η Βιβλιοθήκη Excel επιταχύνει τον προγραμματισμό υπολογιστικών φύλλων και τις διαδικασίες μετατροπής ενώ υποστηρίζει δημοφιλείς μορφές, όπως XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Επιτρέπει επίσης την εξαγωγή αρχείων Excel σε PDF, XPS, HTML, MHTML, Απλό κείμενο και δημοφιλείς μορφές εικόνας όπως TIFF, JPG, PNG, BMP και SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Μετατρέψτε το Excel σε XLSX, ODS, SXC & FODS" %}}
Η αλληλομετατροπή της μορφής υπολογιστικού φύλλου απαιτεί μόνο τη φόρτωση ενός υπολογιστικού φύλλου με μια παρουσία του [ΤΕΤΡΑΔΙΟ ΕΡΓΑΣΙΩΝ](https://reference.aspose.com/cells/net/aspose.cells/workbook) και αποθηκεύστε ξανά στην επιθυμητή μορφή ενώ επιλέγετε την κατάλληλη τιμή από [SaveFormat](https://reference.aspose.com/cells/net/aspose.cells/saveformat) απαρίθμηση.
{{% blocks/products/pf/feature-page-code h3="C# Κώδικας για μετατροπή μορφής αρχείου Excel" %}}

```cs
// φορτώστε το αρχείο προτύπου
var workbook = new Aspose.Cells.Workbook("template.xls");
// αποθήκευση ως μορφές XLSX, ODS, SXC & FODS
workbook.Save("output.xlsx", Aspose.Cells.SaveFormat.Xlsx);
workbook.Save("output.ods", Aspose.Cells.SaveFormat.Ods);
workbook.Save("output.scx", Aspose.Cells.SaveFormat.Sxc);
workbook.Save("output.fods", Aspose.Cells.SaveFormat.Fods);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Μετατρέψτε το Excel σε PDF, XPS, HTML & MD" %}}
Διατίθενται εξειδικευμένες κλάσεις για τον έλεγχο της διαδικασίας μετατροπής για συγκεκριμένες μορφές εξόδου, όπως π.χ [Επιλογές PdfSave](https://reference.aspose.com/cells/net/aspose.cells/pdfsaveoptions) για εξαγωγή αρχείων Excel ως PDF, [XpsSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/xpssaveoptions) για μετατροπή Excel σε XPS, [HtmlSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/htmlsaveoptions) για απόδοση του Excel ως HTML και [MarkdownSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/markdownsaveoptions) για τη μετατροπή Excel σε Markdown. 
{{% blocks/products/pf/feature-page-code h3="C# Κώδικας για Excel σε μορφή PDF και Web" %}}

```cs
// φόρτωση προτύπου αρχείου Excel από δίσκο
var book = new Aspose.Cells.Workbook("template.xlsx");
// αποθηκεύστε το Excel σε μορφή PDF/A-1a
book.Save("output.pdf", new Aspose.Cells.PdfSaveOptions() { Compliance = PdfComplianceVersion.PdfA1a });
// αποθηκεύστε το Excel σε XPS με 1 σελίδα ανά φύλλο εργασίας
book.Save("output.xps", new Aspose.Cells.XpsSaveOptions() { OnePagePerSheet = true });
// αποθηκεύστε το Excel σε HTML με εικόνες ως Base64
book.Save("output.html", new Aspose.Cells.HtmlSaveOptions() { ExportImagesAsBase64 = true });
// αποθηκεύστε το Excel στο Markdown (MD) διατηρώντας παράλληλα τη μορφοποίηση κελιών
book.Save("output.md", new Aspose.Cells.MarkdownSaveOptions() { FormatStrategy = Cells.CellValueFormatStrategy.CellStyle });

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="Μετατροπή JSON σε Excel και Excel σε JSON" %}}
Τα δεδομένα JSON μπορούν να εισαχθούν σε μια παρουσία του [Cells](https://reference.aspose.com/cells/net/aspose.cells/cells) τάξη με τη βοήθεια του [JsonUtility.ImportData](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/importdata) για περαιτέρω επεξεργασία ή απλή μετατροπή σε οποιαδήποτε από τις υποστηριζόμενες μορφές. Ομοίως, [Φύλλο εργασίας](https://reference.aspose.com/cells/net/aspose.cells/worksheet) Τα δεδομένα μπορούν να εξαχθούν ως JSON δημιουργώντας ένα [Εύρος](https://reference.aspose.com/cells/net/aspose.cells/range) ή κελιά και καλώντας το [JsonUtility.ExportRangeToJson](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/exportrangetojson) μέθοδος.
{{% blocks/products/pf/feature-page-code h3="C# Κώδικας για μετατροπή JSON σε Excel" %}}
```cs
// δημιουργήστε ένα αντικείμενο βιβλίου εργασίας
var workbook = new Cells.Workbook();
var worksheet = workbook.Worksheets[0];
// ανάγνωση δεδομένων JSON από το αρχείο
string jsonInput = File.ReadAllText("Data.json");
// ορίστε το JsonLayoutOptions να αντιμετωπίζει τους Πίνακες ως Πίνακες
var options = new Cells.Utility.JsonLayoutOptions();
options.ArrayAsTable = true;
// Εισαγάγετε δεδομένα JSON στο φύλλο εργασίας ξεκινώντας από το κελί A1
Cells.Utility.JsonUtility.ImportData(jsonInput, worksheet.Cells, 0, 0, options);
// αποθηκεύστε το αρχείο που προκύπτει σε μορφή XLSX
workbook.Save("output.xlsx", Cells.SaveFormat.Auto); 

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Κώδικας για Μετατροπή Excel σε JSON" %}}
```cs
// φορτώστε το αρχείο XLSX με μια παρουσία του βιβλίου εργασίας
var workbook = new Workbook("template.xlsx", new LoadOptions(Cells.LoadFormat.Auto));
// πρόσβαση CellsCollection του φύλλου εργασίας που περιέχει δεδομένα προς μετατροπή
var cells = workbook.Worksheets[0].Cells;
// δημιουργία και ρύθμιση ExportRangeToJsonOptions για σύνθετες επιλογές
var exportOptions = new Utility.ExportRangeToJsonOptions();
// δημιουργήστε μια σειρά κελιών που περιέχουν δεδομένα προς εξαγωγή
var range = cells.CreateRange(0, 0, cells.LastCell.Row + 1, cells.LastCell.Column + 1);
// εξαγωγή εύρους ως δεδομένα JSON
string jsonData = Cells.Utility.JsonUtility.ExportRangeToJson(range, exportOptions);
// εγγραφή αρχείου δεδομένων σε δίσκο σε μορφή JSON
System.IO.File.WriteAllText("output.json", jsonData); 

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Μετατρέψτε τα φύλλα εργασίας του Excel σε JPG, BMP, PNG & GIF" %}}
Κάθε φύλλο εργασίας ενός αρχείου Excel μπορεί να μετατραπεί σε διαφορετικές μορφές εικόνας που ορίζονται από το [ImageOrPrintOptions.ImageType](https://reference.aspose.com/cells/net/aspose.cells.rendering/imageorprintoptions/properties/imagetype) ιδιοκτησία. Η προεπιλεγμένη τιμή είναι "ImageFormat.Bmp".
{{% blocks/products/pf/feature-page-code h3="C# Κώδικας για Μετατροπή Excel σε Εικόνα" %}}
```cs
// φόρτωση υπολογιστικού φύλλου προτύπου
var workbook = new Aspose.Cells.Workbook("template.xlsx");
// δημιουργήστε και ορίστε μια παρουσία του ImageOrPrintOptions
var options = new Aspose.Cells.Rendering.ImageOrPrintOptions();
options.OnePagePerSheet = true;
// ορίστε τη μορφή εικόνας εξόδου
options.ImageType = Aspose.Cells.Drawing.ImageType.Jpeg;
// δημιουργήστε το SheetRender για το πρώτο φύλλο εργασίας της συλλογής
var render = new Aspose.Cells.Rendering.SheetRender(workbook.Worksheets[0], options);
// απόδοση φύλλου εργασίας σε εικόνα
render.ToImage(0, "output.jpg");

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Μετατροπή Excel σε Word & PowerPoint" %}}
Είναι δυνατή η φόρτωση οποιουδήποτε υπολογιστικού φύλλου και η μετατροπή του σε αρχεία Word DOCX & PowerPoint PPTX κατά τη χρήση [DocxSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/docxsaveoptions) & [PptxSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/pptxsaveoptions) τάξεις όπως φαίνεται παρακάτω.
{{% blocks/products/pf/feature-page-code h3="C# κώδικας για μετατροπή Excel σε Word και PowerPoint" %}}
```cs
// φορτώστε το αρχείο προτύπου
var workbook = new Aspose.Cells.Workbook("template.xlsx");
// αποθήκευση υπολογιστικού φύλλου ως DOCX
workbook.Save("output.docx", new Aspose.Cells.DocxSaveOptions());
// αποθήκευση υπολογιστικού φύλλου ως PPTX
workbook.Save("output.pptx", new Aspose.Cells.PptxSaveOptions());

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}