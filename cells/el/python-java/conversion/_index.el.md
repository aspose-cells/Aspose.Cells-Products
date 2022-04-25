---
title: Μετατροπή αρχείου Microsoft Excel μέσω Python 
url: /el/python/conversion/
description: Μετατρέψτε το Excel XLS, XLSX, ODS, CSV σε PDF, XPS, HTML, JPEG, HTML και πολλές άλλες δημοφιλείς μορφές με λίγες μόνο γραμμές κώδικα Python.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Μετατροπή μορφής Excel μέσω Python" h2="Εισαγωγή και εξαγωγή αρχείων Excel ως υπολογιστικού φύλλου, ιστού, εικόνας και μορφής σταθερής διάταξης" >}}

{{% blocks/products/pf/feature-page-summary %}}
Python Η Βιβλιοθήκη Excel επιταχύνει τον προγραμματισμό υπολογιστικών φύλλων και τις διαδικασίες μετατροπής ενώ υποστηρίζει δημοφιλείς μορφές, όπως XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Επιτρέπει επίσης την εξαγωγή αρχείων Excel σε PDF, XPS, HTML, MHTML, Απλό κείμενο και δημοφιλείς μορφές εικόνας όπως TIFF, JPG, PNG, BMP και SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Μετατρέψτε το Excel σε XLSX, ODS, SXC & FODS" %}}
Η αλληλομετατροπή της μορφής υπολογιστικού φύλλου απαιτεί μόνο τη φόρτωση ενός υπολογιστικού φύλλου με μια παρουσία του [ΤΕΤΡΑΔΙΟ ΕΡΓΑΣΙΩΝ](https://apireference.aspose.com/cells/python/asposecells.api/Workbook) και αποθηκεύστε ξανά στην επιθυμητή μορφή ενώ επιλέγετε την κατάλληλη τιμή από [SaveFormat](https://apireference.aspose.com/cells/python/asposecells.api/saveformat) απαρίθμηση.
{{% blocks/products/pf/feature-page-code h3="Python Κώδικας για μετατροπή μορφής αρχείου Excel" %}}

```cs
// φορτώστε το αρχείο προτύπου
workbook = Workbook("Book1.xls")
  
// αποθήκευση ως μορφές XLSX, ODS, SXC & FODS
workbook.save("output.xlsx", SaveFormat.XLSX);
workbook.save("output.ods", SaveFormat.ODS);
workbook.save("output.scx", SaveFormat.SXC);
workbook.save("output.fods", SaveFormat.FODS);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Μετατρέψτε το Excel σε PDF, XPS, HTML & MD" %}}
Διατίθενται εξειδικευμένες κλάσεις για τον έλεγχο της διαδικασίας μετατροπής για συγκεκριμένες μορφές εξόδου, όπως π.χ [Επιλογές PdfSave](https://apireference.aspose.com/cells/python/asposecells.api/PdfSaveOptions) για εξαγωγή αρχείων Excel ως PDF, [XpsSaveOptions](https://apireference.aspose.com/cells/python/asposecells.api/XpsSaveOptions) για μετατροπή Excel σε XPS, [HtmlSaveOptions](https://apireference.aspose.com/cells/python/asposecells.api/HtmlSaveOptions) για απόδοση του Excel ως HTML και [MarkdownSaveOptions](https://apireference.aspose.com/cells/python/asposecells.api/MarkdownSaveOptions) για τη μετατροπή Excel σε Markdown. 
{{% blocks/products/pf/feature-page-code h3="Python Κώδικας για Excel σε μορφή PDF και Web" %}}

```cs
// φόρτωση προτύπου αρχείου Excel από δίσκο
book = Workbook("template.xlsx")

// αποθηκεύστε το Excel σε μορφή PDF_A_1_B
pdfOptions = PdfSaveOptions()
pdfOptions.setCompliance(PdfCompliance.PDF_A_1_B)
book.save("output.pdf", pdfOptions);

// αποθηκεύστε το Excel σε XPS με 1 σελίδα ανά φύλλο εργασίας
xpsOptions = XpsSaveOptions()
xpsOptions.setOnePagePerSheet(True)
book.save("output.xps", xpsOptions);

// αποθηκεύστε το Excel σε HTML με εικόνες ως Base64
htmlOptions = HtmlSaveOptions()
htmlOptions.setExportImagesAsBase64(True)
book.save("output.html", htmlOptions);

// αποθηκεύστε το Excel στο Markdown (MD) διατηρώντας παράλληλα τη μορφοποίηση κελιών
mdOptions = MarkdownSaveOptions()
mdOptions.setFormatStrategy(CellValueFormatStrategy.CELL_STYLE)
book.save("output.md", mdOptions);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="Μετατροπή JSON σε Excel και Excel σε JSON" %}}
Οι προγραμματιστές του Python μπορούν εύκολα να φορτώσουν και να μετατρέψουν αρχεία JSON σε Excel σε λίγες μόνο γραμμές κώδικα. Ομοίως, τα δεδομένα του Excel μπορούν να εξαχθούν σε δεδομένα JSON.
{{% blocks/products/pf/feature-page-code h3="Python Κώδικας για μετατροπή JSON σε Excel" %}}
```cs
//Φορτώστε το αρχείο προέλευσης json
workbook = Workbook("Data.json")
//αποθήκευση αρχείου σε μορφή xlsx
workbook.save("output.xlsx")

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python Κώδικας για Μετατροπή Excel σε JSON" %}}
```cs
//Φορτώστε το αρχείο πηγής xlsx
workbook = Workbook("input.xlsx")
//αποθήκευση αρχείου σε μορφή json
workbook.save("Data.json")

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Μετατρέψτε τα φύλλα εργασίας του Excel σε JPG, BMP, PNG & GIF" %}}
Κάθε φύλλο εργασίας ενός αρχείου Excel μπορεί να μετατραπεί σε διαφορετικές μορφές εικόνας, καλέστε [ImageOrPrintOptions](https://apireference.aspose.com/cells/python/asposecells.api/ImageOrPrintOptions).setImageFormat για να ορίσετε τη μορφή εικόνας. 
{{% blocks/products/pf/feature-page-code h3="Python Κώδικας για Μετατροπή Excel σε Εικόνα" %}}
```cs
// φόρτωση υπολογιστικού φύλλου προτύπου
workbook = Workbook("template.xlsx")
// δημιουργήστε και ορίστε μια παρουσία του ImageOrPrintOptions
options = ImageOrPrintOptions()
// ορίστε τη μορφή εικόνας εξόδου
options.setImageFormat(ImageFormat.getPng())
// δημιουργήστε το SheetRender για το πρώτο φύλλο εργασίας της συλλογής
sheet = workbook.getWorksheets().get(0)
sr = SheetRender(sheet, options)
// απόδοση φύλλου εργασίας σε εικόνα
sr.toImage(0, "output.jpg")

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Μετατροπή Excel σε Word & PowerPoint" %}}
Είναι δυνατή η φόρτωση οποιουδήποτε υπολογιστικού φύλλου και η μετατροπή του σε αρχεία Word DOCX & PowerPoint PPTX κατά τη χρήση [DocxSaveOptions](https://apireference.aspose.com/cells/python/asposecells.api/DocxSaveOptions) & [PptxSaveOptions](https://apireference.aspose.com/cells/python/asposecells.api/PptxSaveOptions) τάξεις όπως φαίνεται παρακάτω.
{{% blocks/products/pf/feature-page-code h3="Python κώδικας για μετατροπή Excel σε Word και PowerPoint" %}}
```cs
// φορτώστε το αρχείο προτύπου
workbook = Workbook("template.xlsx")

// αποθήκευση υπολογιστικού φύλλου ως DOCX
docxOptions = DocxSaveOptions()
workbook.save("output.docx", docxOptions)

// αποθήκευση υπολογιστικού φύλλου ως PPTX
pptxOptions = PptxSaveOptions()
workbook.save("output.pptx", pptxOptions)

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}