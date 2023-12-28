---
title:  Microsoft Μετατροπή αρχείου Excel μέσω C++
description: Aspose.Cells for C++ βιβλιοθήκη. Μετατρέψτε το EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL, JPG, PNG με λίγες μόνο 61 σειρές από 84 σειρές από 84 σειρές και περισσότερες μορφές κωδικών.
keywords: [C++ Aspose.Cells., excel to pdf., json to excel., txt to sql., csv to json., json to pdf., xml to excel and Convert files between various formats in C++]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Μετατροπή εγγράφου Excel μέσω C++" h2="Αποθήκευση Microsoft<sup>&reg;</sup> αρχείων Excel ως υπολογιστικού φύλλου, ιστού, εικόνας και μορφής σταθερής διάταξης" >}}

{{% blocks/products/pf/feature-page-summary %}}
 Για οποιαδήποτε εφαρμογή ή λύση μετατροπέα υπολογιστικών φύλλων,**C++ Βιβλιοθήκη Excel** επιταχύνει την κωδικοποίηση, τον αυτοματισμό και τις διαδικασίες μετατροπής κατά το χειρισμό πολλών αρχείων, συμπεριλαμβανομένων των XLSX, XLS, XLSM, XLSB, XLTX, XLTM, XLTM, 07614,16341, XLTM, 076140348. *μετατροπή Excel σε PDF**, XPS, HTML, MHTML, Απλό Κείμενο και δημοφιλείς εικόνες όπως JPG, TIFF, PNG, BMP και SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Διαμετατροπή μορφών Excel Microsoft" %}}
 Η μετατροπή μεταξύ μορφών υπολογιστικού φύλλου απαιτεί μόνο τη φόρτωση του υπολογιστικού φύλλου χρησιμοποιώντας το[ΤΕΤΡΑΔΙΟ ΕΡΓΑΣΙΩΝ](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) κλάση και αποθηκεύστε το ξανά στην απαιτούμενη μορφή χρησιμοποιώντας το[Αποθηκεύσετε](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/save/) μέθοδος του[ΤΕΤΡΑΔΙΟ ΕΡΓΑΣΙΩΝ](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) τάξη.
{{% blocks/products/pf/feature-page-code h3="C++ Παράδειγμα κώδικα για μετατροπή μορφής αρχείου Excel" %}}

```cpp

Aspose::Cells::Startup();

// Load the source excel format.
Workbook wkb(u"src_excel_file.xls");
// Save in required output format.
wkb.Save(u"output_excel_format.xlsx", SaveFormat::Xlsx);

Aspose::Cells::Cleanup();

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Μετατρέψτε τις μορφές Excel σε PDF με τις ρυθμίσεις επιπέδου συμμόρφωσης" %}}
C++ Το Excel Automation API υποστηρίζει τη μετατροπή των Βιβλίων εργασίας σε PDF, καθώς και τη ρύθμιση υποστήριξης του επιπέδου συμμόρφωσης και της ημερομηνίας δημιουργίας. Οι προγραμματιστές μπορούν να χρησιμοποιήσουν[PdfSaveOptions](https://reference.aspose.com/cells/cpp/aspose.cells/pdfsaveoptions/) μαζί με[Aspose::Cells::Απόδοση](https://reference.aspose.com/cells/cpp/aspose.cells.rendering/) για να ορίσετε τη συμμόρφωση PDF. Για τη μετατροπή, η μέθοδος αποθήκευσης API έχει ως παράμετρο το PdfSaveOptions και καθορισμένη διαδρομή αρχείου εξόδου.
{{% blocks/products/pf/feature-page-code h3="C++ Δείγμα κώδικα για μετατροπή Excel σε PDF" %}}

```cpp

Aspose::Cells::Startup();

// Load the sample Excel file.
Workbook wkb(u"sample-convert-excel-to.pdf");
// Create pdf save options object.
PdfSaveOptions pdfSaveOptions;

// Set the compliance to PDF/A-1b.
pdfSaveOptions.SetCompliance(PdfCompliance::PdfA1b);

// or PdfCompliance::PdfA1a
// for normal PDF it will be PdfCompliance::None

// Save the Excel Document in PDF format
wkb.Save(u"output-converted-excel-workbook-to.pdf", pdfSaveOptions);

Aspose::Cells::Cleanup();

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="PDF" >}}

{{% blocks/products/pf/feature-page-section h2="Αποθηκεύστε το Excel στις Εικόνες" %}}
**C++ Excel Parser** έχει τη δυνατότητα εξαγωγής δεδομένων σε μορφή εικόνων. Κάθε φύλλο εργασίας μπορεί να μετατραπεί σε διαφορετικές μορφές εικόνας, συμπεριλαμβανομένων των BMP, JPEG, PNG και GIF, που ορίζονται από το[Rendering::ImageOrPrintOptions](https://reference.aspose.com/cells/cpp/aspose.cells.rendering/imageorprintoptions/) . Για κάθε**Μετατροπή Excel σε Εικόνες** περίπτωση, επιλέξτε τη σχετική περίπτωση από συνδέσμους.
{{% blocks/products/pf/feature-page-code h3="C++ Κώδικας για Μετατροπή Excel σε Εικόνα" %}}

```cpp

Aspose::Cells::Startup();

// Load the XLSX.
Aspose::Cells::Workbook wkb(u"source-excel-file.xlsx");

// Access first worksheet.
Aspose::Cells::Worksheet wks = wkb.GetWorksheets().Get(0);

// Create image or print options object.
Aspose::Cells::Rendering::ImageOrPrintOptions imgOptions;

// Specify the image format. Below code is for JPEG
imgOptions.SetImageType(ImageType::Jpeg);

// For other images like GIF, BMP and PNG one can use ImageType::Gif, ImageType::Bmp and ImageType::Png respectively 

// Specify horizontal and vertical resolution
imgOptions.SetHorizontalResolution(200);
imgOptions.SetVerticalResolution(200);

// Render the sheet with respect to specified image or print options.
Aspose::Cells::Rendering::SheetRender sr(wks, imgOptions);

// Get page count.
int pageCount = sr.GetPageCount();

std::string sb = "";
// Render each page to jpeg image one by one.
for (int i = 0; i < pageCount; i++) {
	sb = ""; 
	sb += "ImagesOutputDirectoryPath/";
	sb += "outputConvertingWorksheetToImageJPEG_";
	sb += std::to_string(i);
	sb += ".jpeg";
	// Get the output image path.
	U16String outputJPEG(sb.c_str());
	// Convert worksheet to image.
	sr.ToImage(i, outputJPEG);
}

Aspose::Cells::Cleanup();
	
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xls-to-png csv-to-jpeg tsv-to-png xlsb-to-png xlsx-to-png ods-to-png spreadsheetml-to-bmp tabdelimited-to-gif xlsm-to-bmp xlt-to-gif xltm-to-png xltx-to-gif" >}}
