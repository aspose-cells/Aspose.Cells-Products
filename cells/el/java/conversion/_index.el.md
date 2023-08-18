---
title:  Microsoft Μετατροπή αρχείου Excel via Java
description: Μετατρέψτε το Excel XLS, XLSX, ODS, CSV σε PDF, XPS, HTML, JPEG, JPEG, JPEG, 438 με πολλές άλλες 334 δημοφιλείς μορφές και 076 076 81 κωδικός.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Μετατροπή αρχείων Excel via Java" h2="Αποθήκευση Microsoft εγγράφων Excel ως υπολογιστικού φύλλου, ιστού, εικόνας και μορφής σταθερής διάταξης" >}}

{{% blocks/products/pf/feature-page-summary %}}
 Για κάθε**Μετατροπέας Excel**εφαρμογή ή λύση, Java Η Βιβλιοθήκη Excel επιταχύνει τον προγραμματισμό υπολογιστικών φύλλων και τις διαδικασίες μετατροπής ενώ χειρίζεται πολλαπλές μορφές, συμπεριλαμβανομένων XLS, XLSX, XLSM, XLSB, XLTX, XLTX, XLTX, XLTX, XLTX, XLTX, XLTX, XLS 81, ODS. Επιτρέπει επίσης τη *μετατροπή αρχείων Excel σε PDF**, XPS, HTML, MHTML, Απλό κείμενο και δημοφιλείς μορφές εικόνας όπως TIFF, JPG, PNG, BMP και SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Διαμετατροπή μορφών Excel Microsoft" %}}
 Η αλληλομετατροπή της μορφής υπολογιστικού φύλλου απαιτεί μόνο τη φόρτωση ενός υπολογιστικού φύλλου με μια παρουσία του[ΤΕΤΡΑΔΙΟ ΕΡΓΑΣΙΩΝ](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) και αποθηκεύστε ξανά στην επιθυμητή μορφή ενώ επιλέγετε την κατάλληλη τιμή από[SaveFormat](https://reference.aspose.com/cells/java/com.aspose.cells/SaveFormat) απαρίθμηση.
{{% blocks/products/pf/feature-page-code h3="Java Παράδειγμα κώδικα για μετατροπή μορφής αρχείου Excel" %}}

```cs
// load the source file
var wkb = new Workbook("sourceFile.xls");
// save as XLSX, ODS, SXC & FODS formats
wkb.save("xlsx-output.xlsx", SaveFormat.XLSX);
wkb.save("ods-output.ods", SaveFormat.ODS);
wkb.save("scx-output.scx", SaveFormat.SXC);
wkb.save("fods-output.fods", SaveFormat.FODS);
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-json xlsx-to-pdf xlsx-to-html xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Μετατροπή Excel σε PDF, XPS, HTML & MD" %}}
 Διατίθενται εξειδικευμένες κλάσεις για τον έλεγχο της διαδικασίας μετατροπής για συγκεκριμένες μορφές εξόδου, όπως π.χ[PdfSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/PdfSaveOptions) για να μετατρέψετε αρχεία Excel ως PDF,[XpsSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/XpsSaveOptions) για εξαγωγή του Excel ως XPS,[HtmlSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/HtmlSaveOptions) για απόδοση του Excel ως HTML και[MarkdownSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/MarkdownSaveOptions) για τη μετατροπή Excel σε Markdown.
{{% blocks/products/pf/feature-page-code h3="Java Δείγμα κώδικα για Excel σε PDF και Μορφές Ιστού" %}}

```cs
// load template Excel file from disc
var bk = new Workbook("source-file.xlsx");

// convert Excel to PDF using Java
// Create PDF options
PdfSaveOptions options = new PdfSaveOptions();
options.setCompliance(PdfCompliance.PDF_A_1_A);

bk.save("excel-to-pdf.pdf", options);
// save Excel in XPS
bk.save("output.xps", new XpsSaveOptions());
// save Excel in HTML
bk.save("output.html", new HtmlSaveOptions());
// save Excel in Markdown (MD)
bk.save("output.md", new MarkdownSaveOptions());

// one can set relevant save options as of his choice before saving into relevant format
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="Μετατροπή JSON σε Excel και Excel σε JSON" %}}
 Τα δεδομένα JSON μπορούν να εισαχθούν σε μια παρουσία της κλάσης Βιβλίο εργασίας με τη βοήθεια[JSONUtility.importData](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility#importData) για περαιτέρω επεξεργασία ή απλή μετατροπή σε οποιαδήποτε από τις υποστηριζόμενες μορφές. Ομοίως, τα δεδομένα του φύλλου εργασίας μπορούν να εξαχθούν ως JSON δημιουργώντας ένα[Εύρος](https://reference.aspose.com/cells/java/com.aspose.cells/range) ή κελιά και καλώντας το[exportRangeToJson](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility) μέθοδος.
{{% blocks/products/pf/feature-page-code h3="Java Κωδικός για JSON Μετατροπή σε Excel" %}}
```cs
Workbook workbook = new Workbook(path + "source-file.xlsx");
Worksheet wks = workbook.getWorksheets().get(0);
		
// Read File
File file = new File(path + "source-data.json");
BufferedReader bufferedReader = new BufferedReader(new FileReader(file));
String jsonInput = "";
String tempString;
while ((tempString = bufferedReader.readLine()) != null) {
	jsonInput = jsonInput + tempString; 
}
bufferedReader.close();
							
// Set JsonLayoutOptions
JsonLayoutOptions options = new JsonLayoutOptions();
options.setIgnoreArrayTitle(true);
options.setArrayAsTable(true);

// Import JSON Data
JSONUtility.importData(jsonInput, wks.getCells(), 0, 0, options);

// Save Excel file
workbook.save(path + "excel-to-json.out.xlsx");
```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Java Μετατροπή πηγαίου κώδικα για Excel σε JSON" %}}
```cs
// load XLSX file with an instance of Workbook
Workbook workbook = new Workbook("sourceFile.xlsx");
// access CellsCollection of the worksheet containing data to be converted
Cells cells = workbook.getWorksheets().get(0).getCells();
// create & set ExportRangeToJsonOptions for advanced options
ExportRangeToJsonOptions exportOptions = new ExportRangeToJsonOptions();
// create a range of cells containing data to be exported
Range range = cells.createRange(0, 0, cells.getLastCell().getRow() + 1, cells.getLastCell().getColumn() + 1);
// export range as JSON data
String jsonData = JsonUtility.exportRangeToJson(range, exportOptions);
// write data to disc in JSON format
BufferedWriter writer = new BufferedWriter(new FileWriter("output.json"));
writer.write(jsonData);
writer.close();    
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Αποθηκεύστε τα φύλλα εργασίας του Excel στις εικόνες" %}}
 Κάθε φύλλο εργασίας μπορεί να μετατραπεί σε διαφορετικές μορφές εικόνας, συμπεριλαμβανομένων των JPG, BMP, PNG & GIF, που ορίζονται από την ιδιότητα ImageType. Για κάθε**Μετατροπή Excel σε Εικόνες** περίπτωση, επιλέξτε τη σχετική περίπτωση από συνδέσμους.
{{% blocks/products/pf/feature-page-code h3="Java Κώδικας για Μετατροπή Excel σε Εικόνα" %}}
```cs
// load template spreadsheet
var wkb = new Workbook("template.xlsx");

// Create an object for ImageOptions
ImageOrPrintOptions imgOptions = new ImageOrPrintOptions();

// Set the image type
imgOptions.setImageType(ImageType.PNG);

// Get the first worksheet.
Worksheet sheet = wkb.getWorksheets().get(0);

// Create a SheetRender object for the target sheet
SheetRender sr = new SheetRender(sheet, imgOptions);
for (int j = 0; j < sr.getPageCount(); j++) {
	// Generate an image for the worksheet
	sr.toImage(j, dataDir + "WToImage-out" + j + ".png");
}
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Μετατρέψτε το Microsoft Excel σε Word και PowerPoint" %}}
 Είναι δυνατή η φόρτωση οποιουδήποτε υπολογιστικού φύλλου και η μετατροπή του σε αρχεία Word DOCX & PowerPoint PPTX κατά τη χρήση[DocxSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/DocxSaveOptions) & [PptxSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/PptxSaveOptions)τάξεις όπως παρουσιάζεται παρακάτω.
{{% blocks/products/pf/feature-page-code h3="Java Κώδικας για Excel σε Word & PowerPoint Μετατροπή" %}}
```cs
// load the template file
var wkb = new Workbook("template.xlsx");
// save spreadsheet as DOCX
wkb.save("output.docx", new DocxSaveOptions());
// save spreadsheet as PPTX
wkb.save("output.pptx", new PptxSaveOptions());
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
