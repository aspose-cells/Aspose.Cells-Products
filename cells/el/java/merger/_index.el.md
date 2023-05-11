---
title: Συγχώνευση διαφορετικών αρχείων Excel σε ένα ενιαίο στο Java
description: Συγχώνευση αρχείων Excel χρησιμοποιώντας το Java σε πολλαπλά φύλλα ή μεμονωμένα φύλλα. Συγχωνεύστε, συνδυάστε ή συνδέστε έγγραφα Excel στο PDF, στο Images και στο HTML επίσης.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Συγχώνευση αρχείων Excel via Java" h2="Συνδυάστε δύο ή περισσότερα αρχεία Excel σε ένα μόνο υπολογιστικό φύλλο χρησιμοποιώντας τον κωδικό Java" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Βιβλιοθήκη Excel](/cells/el/java/) παρέχει πολλούς τρόπους συνδυασμού βιβλίων εργασίας με διάφορους τύπους περιεχομένου όπως τύπους, εικόνες, δεδομένα, γραφήματα κ.λπ. σε ένα έγγραφο υπολογιστικού φύλλου. Οι υποστηριζόμενες μορφές αρχείων περιλαμβάνουν XLS, XLSX, XLSB, XLT, XLTX, XLTM, ODS, CSV, CSV, CSV, CSV και άλλα.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Συνδυάστε αρχεία Excel με εικόνες και γραφήματα" %}}
 Ο απλούστερος τρόπος για να συνδυάσετε δύο αρχεία Excel με εικόνες και γραφήματα είναι καλώντας το[Τετράδιο εργασιών.συνδυάστε](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#combine(com.aspose.cells.Workbook)) μέθοδος. Επιτρέπει τη συγχώνευση αρχείων Excel παρόμοιου τύπου σε ένα ενιαίο υπολογιστικό φύλλο.
{{% blocks/products/pf/feature-page-code h3="Java Κώδικας για συνδυασμό αρχείων Excel" %}}

```cs
// load first Excel file
var book1 = new Workbook("with-charts.xlsx");
// load second Excel file into a separate instance
var book2 = new Workbook("with-images.xlsx");

// merge two workbooks
book1.combine(book2);
// save the target workbook 
book1.save("combined.xlsx");
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Συγχώνευση πολλών αρχείων Excel" %}}
[CellsHelper.mergeFiles](https://reference.aspose.com/cells/java/com.aspose.cells/cellshelper#mergeFiles) Η μέθοδος υποστηρίζει τη συγχώνευση δεδομένων, στυλ και τύπων ενός αρχείου Excel σε ένα νέο υπολογιστικό φύλλο της ίδιας μορφής. Είναι ένας αποτελεσματικός τρόπος για τη συγχώνευση πολλών αρχείων κατά τη χρήση της προσωρινής αποθήκευσης.
{{% blocks/products/pf/feature-page-code h3="Java Κώδικας για συγχώνευση πολλών αρχείων Excel" %}}

```cs
// create an Array (length=2)
String[] files = new String[2];
// specify file paths to be merged
files[0] = "Book1.xls";
files[1] = "Book2.xls";
// merge the files to save the result
CellsHelper.mergeFiles(files, "cache", "merged.xls");

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Συγχώνευση αρχείων Excel με αντιγραφή φύλλων εργασίας" %}}
[Φύλλο εργασίας.αντίγραφο](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet#copy(com.aspose.cells.Worksheet)) μπορεί να χρησιμοποιηθεί για την αντιγραφή δεδομένων και τη μορφοποίηση από ένα φύλλο εργασίας προέλευσης σε άλλο φύλλο εργασίας εντός ή μεταξύ των βιβλίων εργασίας. Η μέθοδος παίρνει το αντικείμενο του φύλλου εργασίας προέλευσης ως παράμετρο.
{{% blocks/products/pf/feature-page-code h3="Java Κώδικας για την αντιγραφή φύλλων εργασίας μεταξύ των βιβλίων εργασίας" %}}

```cs
// Create a Workbook.
Workbook excelWorkbook0 = new Workbook(dataDir + "book1.xls");

// Create another Workbook.
Workbook excelWorkbook1 = new Workbook();

// Copy the first sheet of the first book into second book.
excelWorkbook1.getWorksheets().get(0).copy(excelWorkbook0.getWorksheets().get(0));

// Save the file.
excelWorkbook1.save(dataDir + "out.xls", FileFormatType.EXCEL_97_TO_2003);
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μορφές συγχώνευσης" subTitle="Χρησιμοποιώντας το Java, το One μπορεί επίσης να συγχωνεύσει πολλές άλλες μορφές αρχείων, συμπεριλαμβανομένων.." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/csv/" name="CSV" description="Τιμές διαχωρισμένες με κόμματα" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/html/" name="HTML" description="Γλώσσα σήμανσης υπερκειμένου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/mhtml/" name="MHTML" description="Μορφή αρχείου ιστοσελίδας" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/ods/" name="ODS" description="Αρχείο Υπολογιστικού Φύλλου OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/tsv/" name="TSV" description="Τιμές διαχωρισμένες με καρτέλες" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/txt/" name="TXT" description="Έγγραφο κειμένου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xls/" name="XLS" description="Δυαδική μορφή Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsb/" name="XLSB" description="Δυαδικό αρχείο βιβλίου εργασίας Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsm/" name="XLSM" description="Αρχείο υπολογιστικού φύλλου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsx/" name="XLSX" description="Αρχείο Excel OOXML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlt/" name="XLT" description="Microsoft Πρότυπο Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xltm/" name="XLTM" description="Πρότυπο με δυνατότητα μακροεντολής Excel" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}
