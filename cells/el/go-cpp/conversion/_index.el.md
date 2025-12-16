---
title: Microsoft Μετατροπή αρχείου Excel με το Go μέσω C++
description: Aspose.Cells για τη βιβλιοθήκη Go via C++. Μετατρέψτε αρχεία EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL, JPG, PNG και άλλες μορφές με λίγες μόνο γραμμές κώδικα Go via C++.
keywords: [Go via C++ Aspose.Cells., excel to pdf., json to excel., txt to sql., csv to json., json to pdf., xml to excel and Convert files between various formats in Go via C++]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=" Microsoft<sup>&reg;</sup> Μετατροπή εγγράφου Excel με το Go μέσω C++" h2="Αποθήκευση Microsoft<sup>&reg;</sup> αρχείων Excel ως μορφή υπολογιστικού φύλλου, ιστού, εικόνας και σταθερής διάταξης" >}}

{{% blocks/products/pf/feature-page-summary %}}
 Για οποιαδήποτε εφαρμογή ή λύση μετατροπής υπολογιστικών φύλλων,**Μεταβείτε στη Βιβλιοθήκη Excel C++**Επιταχύνει τις διαδικασίες κωδικοποίησης, αυτοματοποίησης και μετατροπής, ενώ παράλληλα χειρίζεται πολλά αρχεία, συμπεριλαμβανομένων των XLSX, XLS, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Επιτρέπει επίσης τη *μετατροπή Excel σε PDF**, XPS, HTML, MHTML, απλό κείμενο και δημοφιλείς εικόνες όπως JPG, TIFF, PNG, BMP και SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Μετατροπή μεταξύ μορφών Excel Microsoft" %}}
 Η μετατροπή μεταξύ μορφών υπολογιστικού φύλλου απαιτεί μόνο τη φόρτωση του υπολογιστικού φύλλου χρησιμοποιώντας το[ΤΕΤΡΑΔΙΟ ΕΡΓΑΣΙΩΝ](https://reference.aspose.com/cells/go-cpp/workbook/) κλάση και την επαναποθήκευσή της στην απαιτούμενη μορφή χρησιμοποιώντας το[Εκτός](https://reference.aspose.com/cells/go-cpp/workbook/save_string/) μέθοδος του[ΤΕΤΡΑΔΙΟ ΕΡΓΑΣΙΩΝ](https://reference.aspose.com/cells/go-cpp//workbook/) τάξη.
{{% blocks/products/pf/feature-page-code h3="Μεταβείτε στο παράδειγμα κώδικα C++ για μετατροπή μορφής αρχείου Excel" %}}

```go

package main

import (
    . "github.com/Aspose-Cells/aspose-cells-go-cpp/v25"
)
// Load the source excel format.
workbook,_:= NewWorkbook_String("src_excel_file.xlsx")
// Save in required output format.
workbook.Save_String("output_excel_format.xlsx")

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Μετατροπή μορφών Excel σε PDF με ρυθμίσεις επιπέδου συμμόρφωσης" %}}
 Μεταβείτε στο C++. Το Excel Automation API υποστηρίζει τη μετατροπή Βιβλίων Εργασίας σε PDF, καθώς και τον ορισμό του επιπέδου συμμόρφωσης και της ημερομηνίας δημιουργίας. Οι προγραμματιστές μπορούν να χρησιμοποιήσουν[Επιλογές Αποθήκευσης Pdf](https://reference.aspose.com/cells/go-cpp/pdfsaveoptions/)για να ορίσετε τη συμμόρφωση PDF. Για μετατροπή, χρησιμοποιήστε τη μέθοδο αποθήκευσης API που έχει την παράμετρο PdfSaveOptions και καθορισμένη διαδρομή αρχείου εξόδου.
{{% blocks/products/pf/feature-page-code h3="Μεταβείτε στο δείγμα κώδικα C++ για μετατροπή Excel σε PDF" %}}

```go

package main

import (
    . "github.com/Aspose-Cells/aspose-cells-go-cpp/v25"
)

workbook, _ := NewWorkbook()
worksheets, _ := workbook.GetWorksheets()
worksheet, _ := worksheets.Get_Int(0)
cells, _ := worksheet.GetCells()
cell, _ := cells.Get_String("A1")
cell.PutValue_Int(5)
cell, _ = cells.Get_String("A2")
cell.PutValue_Int(15)
cell, _ = cells.Get_String("A3")
cell.PutValue_Int(25)
workbook.Save_String("HELLO_Convert.pdf")
println("Finish to convert to PDF , check .pdf file in output folder.")


```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="PDF" >}}

{{% blocks/products/pf/feature-page-section h2="Αποθήκευση Excel σε εικόνες" %}}
**Μεταβείτε μέσω του αναλυτή Excel C++** έχει τη δυνατότητα εξαγωγής δεδομένων με τη μορφή εικόνων. Κάθε φύλλο εργασίας μπορεί να μετατραπεί σε διαφορετικές μορφές εικόνας, συμπεριλαμβανομένων των BMP, JPEG, PNG και GIF, που ορίζονται από το[Απόδοση::ΕπιλογέςΕκτύπωσηςΉΕικόνας](https://reference.aspose.com/cells/go-cpp/sheetrender/toimage_int_string/) Για οποιαδήποτε**Μετατροπή Excel σε εικόνες** περίπτωση, επιλέξτε την σχετική περίπτωση από τους συνδέσμους.
{{% blocks/products/pf/feature-page-code h3="Μεταβείτε στον κωδικό C++ για μετατροπή Excel σε εικόνα" %}}

```go

package main

import (
    . "github.com/Aspose-Cells/aspose-cells-go-cpp/v25"
)

 // Load the XLSX.
    workbook, _ := NewWorkbook("source-excel-file.xlsx")

// Access first worksheet.
    worksheets, _ := workbook.GetWorksheets()
    worksheet, _ := worksheets.Get_Int(0)

// Create image or print options object.
    imgOptions, _ := NewImageOrPrintOptions()

// Specify the image format. Below code is for JPEG
    imgOptions.SetImageType(ImageType_Jpeg)

// Specify horizontal and vertical resolution
    imgOptions.SetHorizontalResolution(200)
    imgOptions.SetVerticalResolution(200)

// Render the sheet with respect to specified image or print options.
    sheetRender, _ := NewSheetRender(worksheet, imgOptions)

// Get page count.
    pageCount, _ := sheetRender.GetPageCount()

// Render each page to jpeg image one by one.
    for i := int32(0); i < pageCount; i++ {
        data, _ := sheetRender.ToImage_Int(i)
        filename := "Image" + string(i) + ".jpg"
        file, _ := os.OpenFile(filename, os.O_WRONLY|os.O_CREATE|os.O_APPEND, 0644)
        defer file.Close()
        file.Write(data)
    }

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xls-to-png csv-to-jpeg tsv-to-png xlsb-to-png xlsx-to-png ods-to-png spreadsheetml-to-bmp tabdelimited-to-gif xlsm-to-bmp xlt-to-gif xltm-to-png xltx-to-gif" >}}

{{< /blocks/products/pf/feature-page-wrap >}}
