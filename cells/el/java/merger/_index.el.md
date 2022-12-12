---
title: Συγχώνευση διαφορετικών αρχείων Excel σε ένα σε ένα σε Java

description: Συγχώνευση αρχείων Excel χρησιμοποιώντας το Java σε πολλαπλά φύλλα ή μεμονωμένα φύλλα. Συγχωνεύστε, συνδυάστε ή συνδέστε έγγραφα Excel σε PDF, Εικόνες και HTML επίσης.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Συγχώνευση αρχείων Excel μέσω Java" h2="Συνδυάστε δύο ή περισσότερα αρχεία Excel σε ένα μόνο υπολογιστικό φύλλο χρησιμοποιώντας τον κώδικα Java" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Βιβλιοθήκη Excel](/cells/java/) παρέχει πολλούς τρόπους συνδυασμού βιβλίων εργασίας με διάφορους τύπους περιεχομένου όπως τύπους, εικόνες, δεδομένα, γραφήματα κ.λπ. σε ένα έγγραφο υπολογιστικού φύλλου. Οι υποστηριζόμενες μορφές αρχείων περιλαμβάνουν XLS, XLSX, XLSB, XLT, XLTX, XLTM, ODS, CSV, TSV και άλλα.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Συνδυάστε αρχεία Excel με εικόνες και γραφήματα" %}}
Ο απλούστερος τρόπος για να συνδυάσετε δύο αρχεία Excel με εικόνες και γραφήματα είναι καλώντας το [Τετράδιο εργασιών.συνδυάστε](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#combine(com.aspose.cells.Workbook)) μέθοδος. Επιτρέπει τη συγχώνευση αρχείων Excel παρόμοιου τύπου σε ένα ενιαίο υπολογιστικό φύλλο.
{{% blocks/products/pf/feature-page-code h3="Java Κώδικας για συνδυασμό αρχείων Excel" %}}

```cs
// φορτώστε το πρώτο αρχείο Excel
var book1 = new Workbook("with-charts.xlsx");
// φορτώστε το δεύτερο αρχείο Excel σε ξεχωριστή παρουσία
var book2 = new Workbook("with-images.xlsx");

// συγχωνεύστε δύο βιβλία εργασίας
book1.combine(book2);
// αποθηκεύστε το βιβλίο εργασίας προορισμού 
book1.save("combined.xlsx");

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Συγχώνευση πολλών αρχείων Excel" %}}
[CellsHelper.mergeFiles](https://reference.aspose.com/cells/java/com.aspose.cells/cellshelper#mergeFiles) Η μέθοδος υποστηρίζει τη συγχώνευση δεδομένων, στυλ και τύπων ενός αρχείου Excel σε ένα νέο υπολογιστικό φύλλο της ίδιας μορφής. Είναι ένας αποτελεσματικός τρόπος για τη συγχώνευση πολλών αρχείων κατά τη χρήση της προσωρινής αποθήκευσης. 
{{% blocks/products/pf/feature-page-code h3="Java Κώδικας για συγχώνευση πολλών αρχείων Excel" %}}

```cs
// δημιουργία πίνακα (μήκος=2)
String[] files = new String[2];
// καθορίστε διαδρομές αρχείου προς συγχώνευση
files[0] = "Book1.xls";
files[1] = "Book2.xls";
// συγχωνεύστε τα αρχεία για να αποθηκεύσετε το αποτέλεσμα
CellsHelper.mergeFiles(files, "cache", "merged.xls");


```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Συγχώνευση αρχείων Excel με αντιγραφή φύλλων εργασίας" %}}
[Φύλλο εργασίας.αντίγραφο](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet#copy(com.aspose.cells.Worksheet)μπορεί να χρησιμοποιηθεί για την αντιγραφή δεδομένων και τη μορφοποίηση από ένα φύλλο εργασίας προέλευσης σε άλλο φύλλο εργασίας εντός ή μεταξύ των βιβλίων εργασίας. Η μέθοδος λαμβάνει το αντικείμενο του φύλλου εργασίας προέλευσης ως παράμετρο.
{{% blocks/products/pf/feature-page-code h3="Java Κώδικας για την αντιγραφή φύλλων εργασίας μεταξύ των βιβλίων εργασίας" %}}

```cs
// Δημιουργήστε ένα βιβλίο εργασίας.
Workbook excelWorkbook0 = new Workbook(dataDir + "book1.xls");

// Δημιουργήστε ένα άλλο βιβλίο εργασίας.
Workbook excelWorkbook1 = new Workbook();

// Αντιγράψτε το πρώτο φύλλο του πρώτου βιβλίου σε δεύτερο βιβλίο.
excelWorkbook1.getWorksheets().get(0).copy(excelWorkbook0.getWorksheets().get(0));

// Αποθηκεύστε το αρχείο.
excelWorkbook1.save(dataDir + "out.xls", FileFormatType.EXCEL_97_TO_2003);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Merger" >}}
