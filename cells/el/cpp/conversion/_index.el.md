---
title: Μετατροπή αρχείου Microsoft Excel μέσω C++ 
url: /el/cpp/conversion/
description: Μετατρέψτε το Excel XLS, XLSX, ODS, CSV σε PDF, XPS, HTML, JPEG και άλλες μορφές με λίγες μόνο γραμμές κώδικα C++.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Μετατροπή εγγράφου Excel μέσω C++" h2="Αποθήκευση αρχείων Microsoft<sup>&reg;</sup> Excel ως υπολογιστικού φύλλου, ιστού, εικόνας και μορφής σταθερής διάταξης" >}}

{{% blocks/products/pf/feature-page-summary %}}
Για οποιαδήποτε εφαρμογή ή λύση μετατροπέα υπολογιστικών φύλλων, η **C++ Βιβλιοθήκη του Excel** επιταχύνει τις διαδικασίες κωδικοποίησης, αυτοματισμού και μετατροπής ενώ χειρίζεται πολλά αρχεία, όπως XLSX, XLS, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Επιτρέπει επίσης τη **μετατροπή του Excel σε PDF**, XPS, HTML, MHTML, Απλό κείμενο και δημοφιλών εικόνων όπως JPG, TIFF, PNG, BMP και SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Διαμετατροπή μορφών Microsoft Excel" %}}
Η αλληλομετατροπή της μορφής υπολογιστικού φύλλου απαιτεί μόνο τη φόρτωση ενός υπολογιστικού φύλλου με μια παρουσία του [ intrusive_ptr<Aspose::Cells::IWorkbook>](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) δείκτη και αποθήκευση πίσω στην επιθυμητή μορφή χρησιμοποιώντας [Σώσει](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) μέθοδος για [Τάξη IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook).
{{% blocks/products/pf/feature-page-code h3="C++ Παράδειγμα κώδικα για μετατροπή μορφής αρχείου Excel" %}}

```cs

// Φορτώστε την πηγαία μορφή excel.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"src_excel_file.xls");

// Αποθήκευση στην απαιτούμενη μορφή εξόδου.
wkb->Save(u"output_excel_format.xlsx", SaveFormat_Xlsx);


```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Μετατρέψτε τις μορφές του Excel σε PDF με τις ρυθμίσεις επιπέδου συμμόρφωσης" %}}
Το C++ Excel Automation API υποστηρίζει τη μετατροπή Βιβλίων Εργασίας σε PDF, καθώς και υποστήριξη ρύθμισης επιπέδου συμμόρφωσης και ημερομηνίας δημιουργίας. Οι προγραμματιστές μπορούν να χρησιμοποιήσουν [Επιλογές IPdfSave](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_pdf_save_options) μαζί με [Aspose::Cells::Απόδοση](https://reference.aspose.com/cells/cpp/namespace/aspose.cells.rendering) για να ορίσετε τη συμμόρφωση PDF. Για τη μετατροπή, API μέθοδος αποθήκευσης με PdfSaveOptions ως παράμετρο και καθορισμένη διαδρομή αρχείου εξόδου. 
{{% blocks/products/pf/feature-page-code h3="C++ Δείγμα κώδικα για μετατροπή Excel σε PDF" %}}

```cs
// Φορτώστε το δείγμα αρχείου Excel.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sample-convert-excel-to.pdf");

// Δημιουργία αντικειμένου επιλογών αποθήκευσης pdf.
intrusive_ptr<Aspose::Cells::IPdfSaveOptions> pdfSaveOptions = Factory::CreateIPdfSaveOptions();

// Ρυθμίστε τη συμμόρφωση σε PDF/A-1b.
pdfSaveOptions->SetCompliance(Aspose::Cells::Rendering::PdfCompliance_PdfA1b);

// ή PdfCompliance_PdfA1a 
// για κανονικό PDF θα είναι PdfCompliance_None

// Αποθηκεύστε το Έγγραφο του Excel σε μορφή PDF
wkb->Save(u"output-converted-excel-workbook-to.pdf", pdfSaveOptions);



```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="PDF" >}}

{{% blocks/products/pf/feature-page-section h2="Αποθηκεύστε το Excel στις Εικόνες" %}}
Το **C++ Excel Parser** έχει τη δυνατότητα εξαγωγής δεδομένων με τη μορφή εικόνων. Κάθε φύλλο εργασίας μπορεί να μετατραπεί σε διαφορετικές μορφές εικόνας, συμπεριλαμβανομένων BMP, JPEG, PNG και GIF, που ορίζονται από το [Rendering::IImageOrPrintOptions](https://reference.aspose.com/cells/cpp/class/aspose.cells.rendering.i_image_or_print_options). Για οποιαδήποτε περίπτωση **Μετατροπή Excel σε Εικόνες**, επιλέξτε τη σχετική περίπτωση από συνδέσμους.
{{% blocks/products/pf/feature-page-code h3="C++ Κώδικας για Μετατροπή Excel σε Εικόνα" %}}

```cs
// Διαδρομή καταλόγου εξόδου.
StringPtr outDir = new String("ImagesOutputDirectoryPath");

// Φορτώστε το XLSX.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"source-excel-file.xlsx");

// Πρόσβαση στο πρώτο φύλλο εργασίας.
intrusive_ptr<Aspose::Cells::IWorksheet> wks = wkb->GetIWorksheets()->GetObjectByIndex(0);

// Δημιουργία αντικειμένου επιλογών εικόνας ή εκτύπωσης.
intrusive_ptr<Aspose::Cells::Rendering::IImageOrPrintOptions> imgOptions = Factory::CreateIImageOrPrintOptions();

// Καθορίστε τη μορφή εικόνας. Ο παρακάτω κώδικας είναι για JPEG
imgOptions->SetImageFormat(Aspose::Cells::Systems::Drawing::Imaging::ImageFormat::GetJpeg());

// Για άλλες εικόνες όπως GIF, BMP και PNG μπορείτε να χρησιμοποιήσετε τα GetGif(), GetBmp() και GetPng() αντίστοιχα 

// Καθορίστε την οριζόντια και κάθετη ανάλυση
imgOptions->SetHorizontalResolution(200);
imgOptions->SetVerticalResolution(200);

// Αποδώστε το φύλλο σε σχέση με καθορισμένες επιλογές εικόνας ή εκτύπωσης.
intrusive_ptr<Aspose::Cells::Rendering::ISheetRender> sr = Factory::CreateISheetRender(wks, imgOptions);

// Λάβετε τον αριθμό σελίδων.
Aspose::Cells::Systems::Int32 pageCount = sr->GetPageCount();

// Δημιουργήστε αντικείμενο δημιουργίας συμβολοσειρών για συνενώσεις συμβολοσειρών.
intrusive_ptr<Aspose::Cells::Systems::Text::StringBuilder> sb = new Aspose::Cells::Systems::Text::StringBuilder();

// Αποδώστε κάθε σελίδα σε εικόνα jpeg μία προς μία.
for (int i = 0; i < pageCount; i++){
	// Διαγράψτε το εργαλείο δημιουργίας συμβολοσειρών και δημιουργήστε διαδρομή εικόνας εξόδου με συνενώσεις συμβολοσειρών.
	sb->Clear();
	sb->Append(outDir);
	sb->Append((StringPtr)new String("outputConvertingWorksheetToImageJPEG_"));
	sb->Append(i);
	sb->Append((StringPtr)new String(".jpeg"));
	// Λάβετε τη διαδρομή εικόνας εξόδου.
	StringPtr outputJPEG = sb->ToString();
	// Μετατροπή φύλλου εργασίας σε εικόνα.
	sr->ToImage(i, outputJPEG);
}

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xls-to-png csv-to-jpeg tsv-to-png xlsb-to-png xlsx-to-png ods-to-png spreadsheetml-to-bmp tabdelimited-to-gif xlsm-to-bmp xlt-to-gif xltm-to-png xltx-to-gif" >}}