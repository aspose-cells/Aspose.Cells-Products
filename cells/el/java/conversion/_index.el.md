---
title: Μετατροπή αρχείου Microsoft Excel μέσω Java 

description: Μετατρέψτε το Excel XLS, XLSX, ODS, CSV σε PDF, XPS, HTML, JPEG, HTML και πολλές άλλες δημοφιλείς μορφές με λίγες μόνο γραμμές κώδικα Java.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Μετατροπή αρχείων Excel μέσω Java" h2="Αποθηκεύστε έγγραφα του Microsoft Excel ως υπολογιστικά φύλλα, ιστούς, εικόνες και μορφές σταθερής διάταξης" >}}

{{% blocks/products/pf/feature-page-summary %}}
Για οποιαδήποτε εφαρμογή ή λύση **μετατροπέα Excel**, η Java Βιβλιοθήκη Excel επιταχύνει τον προγραμματισμό υπολογιστικών φύλλων και τις διαδικασίες μετατροπής ενώ χειρίζεται πολλές μορφές, όπως XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Επιτρέπει επίσης τη **μετατροπή αρχείων Excel σε PDF**, XPS, HTML, MHTML, Απλό κείμενο και δημοφιλείς μορφές εικόνας όπως TIFF, JPG, PNG, BMP και SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Διαμετατροπή μορφών Microsoft Excel" %}}
Η αλληλομετατροπή της μορφής υπολογιστικού φύλλου απαιτεί μόνο τη φόρτωση ενός υπολογιστικού φύλλου με μια παρουσία του [ΤΕΤΡΑΔΙΟ ΕΡΓΑΣΙΩΝ](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) και αποθηκεύστε ξανά στην επιθυμητή μορφή ενώ επιλέγετε την κατάλληλη τιμή από [SaveFormat](https://reference.aspose.com/cells/java/com.aspose.cells/SaveFormat) απαρίθμηση.
{{% blocks/products/pf/feature-page-code h3="Java Παράδειγμα κώδικα για μετατροπή μορφής αρχείου Excel" %}}

```cs
// φορτώστε το αρχείο προέλευσης
var wkb = new Workbook("sourceFile.xls");
// αποθήκευση ως μορφές XLSX, ODS, SXC & FODS
wkb.save("xlsx-output.xlsx", SaveFormat.XLSX);
wkb.save("ods-output.ods", SaveFormat.ODS);
wkb.save("scx-output.scx", SaveFormat.SXC);
wkb.save("fods-output.fods", SaveFormat.FODS);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-json xlsx-to-pdf xlsx-to-html xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Μετατρέψτε το Excel σε PDF, XPS, HTML & MD" %}}
Διατίθενται εξειδικευμένες κλάσεις για τον έλεγχο της διαδικασίας μετατροπής για συγκεκριμένες μορφές εξόδου, όπως π.χ [Επιλογές PdfSave](https://reference.aspose.com/cells/java/com.aspose.cells/PdfSaveOptions) για να μετατρέψετε αρχεία Excel σε PDF, [XpsSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/XpsSaveOptions) για εξαγωγή του Excel ως XPS, [HtmlSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/HtmlSaveOptions) για απόδοση του Excel ως HTML και [MarkdownSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/MarkdownSaveOptions) για τη μετατροπή Excel σε Markdown. 
{{% blocks/products/pf/feature-page-code h3="Java Δείγμα κώδικα για μορφές Excel σε PDF και Web" %}}

```cs
// φόρτωση προτύπου αρχείου Excel από δίσκο
var bk = new Workbook("source-file.xlsx");

// μετατρέψτε το Excel σε PDF χρησιμοποιώντας Java
// Δημιουργία επιλογών PDF
PdfSaveOptions options = new PdfSaveOptions();
options.setCompliance(PdfCompliance.PDF_A_1_A);

bk.save("excel-to-pdf.pdf", options);
// αποθηκεύστε το Excel σε XPS
bk.save("output.xps", new XpsSaveOptions());
// αποθηκεύστε το Excel σε HTML
bk.save("output.html", new HtmlSaveOptions());
// αποθήκευση του Excel στο Markdown (MD)
bk.save("output.md", new MarkdownSaveOptions());

// μπορεί κανείς να ορίσει τις σχετικές επιλογές αποθήκευσης της επιλογής του πριν από την αποθήκευση σε σχετική μορφή

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="Μετατροπή JSON σε Excel και Excel σε JSON" %}}
Τα δεδομένα JSON μπορούν να εισαχθούν σε μια παρουσία της κλάσης Βιβλίο εργασίας με τη βοήθεια του [JSONUtility.importData](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility#importData) για περαιτέρω επεξεργασία ή απλή μετατροπή σε οποιαδήποτε από τις υποστηριζόμενες μορφές. Ομοίως, τα δεδομένα του φύλλου εργασίας μπορούν να εξαχθούν ως JSON δημιουργώντας ένα [Εύρος](https://reference.aspose.com/cells/java/com.aspose.cells/range) ή κελιά και καλώντας το [exportRangeToJson](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility) μέθοδος.
{{% blocks/products/pf/feature-page-code h3="Java Κώδικας για μετατροπή JSON σε Excel" %}}
```cs
Workbook workbook = new Workbook(path + "source-file.xlsx");
Worksheet wks = workbook.getWorksheets().get(0);
		
// Διαβάστε το Αρχείο
File file = new File(path + "source-data.json");
BufferedReader bufferedReader = new BufferedReader(new FileReader(file));
String jsonInput = "";
String tempString;
while ((tempString = bufferedReader.readLine()) != null) {
	jsonInput = jsonInput + tempString; 
}
bufferedReader.close();
							
// Ορίστε το JsonLayoutOptions
JsonLayoutOptions options = new JsonLayoutOptions();
options.setIgnoreArrayTitle(true);
options.setArrayAsTable(true);

// Εισαγωγή δεδομένων JSON
JSONUtility.importData(jsonInput, wks.getCells(), 0, 0, options);

// Αποθήκευση αρχείου Excel
workbook.save(path + "excel-to-json.out.xlsx");

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Java Πηγαίος κώδικας για Μετατροπή Excel σε JSON" %}}
```cs
// φορτώστε το αρχείο XLSX με μια παρουσία του βιβλίου εργασίας
Workbook workbook = new Workbook("sourceFile.xlsx");
// πρόσβαση CellsCollection του φύλλου εργασίας που περιέχει δεδομένα προς μετατροπή
Cells cells = workbook.getWorksheets().get(0).getCells();
// δημιουργία και ρύθμιση ExportRangeToJsonOptions για σύνθετες επιλογές
ExportRangeToJsonOptions exportOptions = new ExportRangeToJsonOptions();
// δημιουργήστε μια σειρά κελιών που περιέχουν δεδομένα προς εξαγωγή
Range range = cells.createRange(0, 0, cells.getLastCell().getRow() + 1, cells.getLastCell().getColumn() + 1);
// εξαγωγή εύρους ως δεδομένα JSON
String jsonData = JsonUtility.exportRangeToJson(range, exportOptions);
// εγγραφή δεδομένων σε δίσκο σε μορφή JSON
BufferedWriter writer = new BufferedWriter(new FileWriter("output.json"));
writer.write(jsonData);
writer.close();    

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Αποθηκεύστε τα φύλλα εργασίας του Excel στις εικόνες" %}}
Κάθε φύλλο εργασίας μπορεί να μετατραπεί σε διαφορετικές μορφές εικόνας, συμπεριλαμβανομένων JPG, BMP, PNG & GIF, που ορίζονται από την ιδιότητα ImageType. Για οποιαδήποτε περίπτωση **Μετατροπή Excel σε Εικόνες**, επιλέξτε τη σχετική περίπτωση από συνδέσμους.
{{% blocks/products/pf/feature-page-code h3="Java Κώδικας για Μετατροπή Excel σε Εικόνα" %}}
```cs
// φόρτωση υπολογιστικού φύλλου προτύπου
var wkb = new Workbook("template.xlsx");

// Δημιουργήστε ένα αντικείμενο για το ImageOptions
ImageOrPrintOptions imgOptions = new ImageOrPrintOptions();

// Ορίστε τον τύπο εικόνας
imgOptions.setImageType(ImageType.PNG);

// Λάβετε το πρώτο φύλλο εργασίας.
Worksheet sheet = wkb.getWorksheets().get(0);

// Δημιουργήστε ένα αντικείμενο SheetRender για το φύλλο προορισμού
SheetRender sr = new SheetRender(sheet, imgOptions);
for (int j = 0; j < sr.getPageCount(); j++) {
	// Δημιουργήστε μια εικόνα για το φύλλο εργασίας
	sr.toImage(j, dataDir + "WToImage-out" + j + ".png");
}

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Μετατρέψτε το Microsoft Excel σε Word και PowerPoint" %}}
Είναι δυνατή η φόρτωση οποιουδήποτε υπολογιστικού φύλλου και η μετατροπή του σε αρχεία Word DOCX & PowerPoint PPTX κατά τη χρήση [DocxSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/DocxSaveOptions) & [PptxSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/PptxSaveOptions) τάξεις όπως φαίνεται παρακάτω.
{{% blocks/products/pf/feature-page-code h3="Java Κώδικας για Excel σε Word και Μετατροπή PowerPoint" %}}
```cs
// φορτώστε το αρχείο προτύπου
var wkb = new Workbook("template.xlsx");
// αποθήκευση υπολογιστικού φύλλου ως DOCX
wkb.save("output.docx", new DocxSaveOptions());
// αποθήκευση υπολογιστικού φύλλου ως PPTX
wkb.save("output.pptx", new PptxSaveOptions());

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
