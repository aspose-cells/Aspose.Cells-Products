---
title: Δημιουργία HTM - Δημιουργία αρχείου HTM στο C++
description:  Aspose Excel. C++ Δημιουργήστε αρχείο HTM γρήγορα και εύκολα με το Aspose.Cells. Δημιουργήστε αρχείο HTM χρησιμοποιώντας το C++. Δημιουργήστε HTM στο C++. C++ HTM Creater.
keywords: [Aspose Excel., C++ Aspose.Cells., C++ Create HTM file., Generate HTM file in C++., Create HTM file using C++., Write data to HTM file via C++., Create a HTM file in C++., C++ Generate a HTM file., C++ HTM Creater]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Δημιουργήστε αρχείο HTM στο C++" h2="Δημιουργία εγγενούς και υψηλής απόδοσης αρχείου HTM μέσω προγραμματισμού χωρίς Micorsoft Office χρησιμοποιώντας τη βιβλιοθήκη C++." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="HTM" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://releases.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Δημιουργήστε αρχείο HTM χρησιμοποιώντας το C++" %}}

 Πώς να δημιουργήσετε αρχείο HTM; Με τη βιβλιοθήκη Aspose.Cells for C++, μπορείτε εύκολα να δημιουργήσετε αρχείο HTM μέσω προγραμματισμού με λίγες γραμμές κώδικα.[Aspose.Cells for C++](https://products.aspose.com/cells/cpp) έχει τη δυνατότητα δημιουργίας εφαρμογών πολλαπλών πλατφορμών με δυνατότητα δημιουργίας, τροποποίησης, μετατροπής, απόδοσης και εκτύπωσης όλων των αρχείων Excel. C++ Το Excel API όχι μόνο μετατρέπει μεταξύ μορφών υπολογιστικών φύλλων, αλλά μπορεί επίσης να αποδώσει αρχεία Excel ως εικόνες, PDF, HTML, ODS, CSV, SVG, JSON, WORD, PPT και άλλα, καθιστώντας έτσι την τέλεια επιλογή για την ανταλλαγή εγγράφων σε βιομηχανικές τυποποιημένες μορφές. Μπορείτε να κατεβάσετε την τελευταία του έκδοση απευθείας, απλά ανοίξτε[NuGet](https://www.nuget.org/packages/Aspose.Cells.Cpp/) διαχειριστής πακέτων, αναζητήστε Aspose.Cells.Cpp και εγκαταστήστε. Μπορείτε επίσης να χρησιμοποιήσετε την ακόλουθη εντολή από την Κονσόλα Package Manager.

{{% blocks/products/pf/agp/code-block title="Εντολή" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}                                                                             


{{% blocks/products/pf/agp/content h2="Πώς να δημιουργήσετε HTM στο C++" %}}

{{% blocks/products/pf/agp/text %}}

 Είναι εύκολο για τους προγραμματιστές να δημιουργήσουν, να φορτώσουν, να τροποποιήσουν και να μετατρέψουν αρχεία HTM εντός εφαρμογών αναφοράς που εκτελούνται για επεξεργασία δεδομένων σε λίγες μόνο γραμμές κώδικα.

{{% /blocks/products/pf/agp/text %}}

1.  Δημιουργήστε ένα αντικείμενο της κλάσης Βιβλίο εργασίας.
1.  Αποκτήστε το πρώτο φύλλο σε ένα αντικείμενο φύλλου εργασίας.
1.  Χρησιμοποιήστε τη μέθοδο Worksheet.GetCells() για να μεταφέρετε τα κελιά του φύλλου εργασίας σε ένα αντικείμενο Cells.
1. Χρησιμοποιήστε τη μέθοδο Cells.Get() για πρόσβαση στο επιθυμητό κελί του φύλλου εργασίας σε ένα αντικείμενο Cell.
1.  Χρησιμοποιήστε τη μέθοδο Cell.PutValue() για να εισαγάγετε τιμή στο κελί.
1.  Αποθηκεύστε το βιβλίο εργασίας ως αρχείο .htm χρησιμοποιώντας τη μέθοδο Save().

{{% blocks/products/pf/agp/code-block title="Το δείγμα κώδικα δείχνει πώς να δημιουργήσετε αρχείο HTM στο C++." offSpacer="" %}}

```cs
Aspose::Cells::Startup();

// Create an object of the Workbook class.
Workbook wkb;
// Get the first sheet into an Worksheet object.
WorksheetCollection wsc = wkb.GetWorksheets();
Worksheet ws = wsc.Get(0);


// Use Worksheet.GetCells() method to get the cells of the worksheet into an Cells object.
Cells cells = ws.GetCells();


// Use Cells.Get() method to access the desired cell of the worksheet into an Cell object.
Cell cell00 = cells.Get(0, 0);
Cell cell01 = cells.Get(0, 1);
Cell cell10 = cells.Get(1, 0);
Cell cell11 = cells.Get(1, 1);


// Use Cell.PutValue() method to input value into the cell.
cell00.PutValue(u"ColumnA");
cell01.PutValue(u"ColumnB");
cell10.PutValue(u"ValueA");
cell11.PutValue(u"ValueB");


// Save workbook to resultFile folder
wkb.Save(u"created_one.htm");

Aspose::Cells::Cleanup();

```

{{% /blocks/products/pf/agp/code-block %}}
{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="C++ βιβλιοθήκη για τη δημιουργία αρχείου HTM" %}}

{{% blocks/products/pf/agp/text %}}

Υπάρχουν τρεις επιλογές για να εγκαταστήσετε το "Aspose.Cells for C++" στο σύστημά σας. Επιλέξτε αυτό που μοιάζει με τις ανάγκες σας και ακολουθήστε τις οδηγίες βήμα προς βήμα:

{{% /blocks/products/pf/agp/text %}}

1.  Εγκαταστήστε α[NuGet Πακέτο](https://www.nuget.org/packages/Aspose.Cells.Cpp/) . Βλέπω[Τεκμηρίωση](https://docs.aspose.com/cells/cpp/installation/#using-nuget-package-manager)
1.  Εγκαταστήστε τη βιβλιοθήκη χρησιμοποιώντας τους φακέλους Include και lib. Βλέπω[Τεκμηρίωση](https://docs.aspose.com/cells/cpp/installation/#using-include-and-lib-folders)
1.  Εγκαταστήστε το Aspose.Cells for C++ σε Linux. Βλέπω[Τεκμηρίωση](https://docs.aspose.com/cells/cpp/installation/#installing-asposecells-for-c-in-linux)

{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="Απαιτήσεις συστήματος" %}}

{{% blocks/products/pf/agp/text %}}

 Πριν εκτελέσετε το δείγμα πηγαίου κώδικα μετατροπής C++, βεβαιωθείτε ότι διαθέτετε τις ακόλουθες προϋποθέσεις.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ή συμβατό λειτουργικό σύστημα με C++ Runtime Environment για Windows 32 bit, Windows 64 bit και Linux 64 bit.
- Προσθέστε αναφορά στο DLL Aspose.Cells for C++ στο έργο σας.

{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->
    {{< blocks/products/pf/agp/about-file-section >}}
        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="HTM" readMoreLink="https://docs.fileformat.com/web/htm/" >}}Τα αρχεία με επέκταση .htm αντιπροσωπεύουν τη γλώσσα σήμανσης υπερκειμένου για τη δημιουργία ιστοσελίδων για εμφάνιση σε προγράμματα περιήγησης ιστού όπως Google Chrome, Internet Explorer, Firefox και μια σειρά άλλων. Καθορίζει τις σημάνσεις για τη δημιουργία στατικών σελίδων που θα δημοσιευτούν στον Παγκόσμιο Ιστό (WWW) για πρόσβαση από άλλους. Αυτές οι σημάνσεις λένε στα προγράμματα περιήγησης πώς να εμφανίζουν τα περιεχόμενα μιας ιστοσελίδας. Τέτοιες σελίδες μπορεί να περιέχουν απλό κείμενο, εικόνες, υπερσυνδέσμους προς άλλες σελίδες, βίντεο και άλλες πληροφορίες πολυμέσων. Όταν δημοσιεύεται μια ιστοσελίδα, μπορείτε να ρίξετε μια ματιά στον κώδικα σήμανσης πίσω από αυτήν, προβάλλοντας την πηγή της σελίδας της. Τα σύγχρονα προγράμματα περιήγησης επιτρέπουν την επιθεώρηση κάθε ενότητας μιας ιστοσελίδας όπου έχει επεξεργαστεί κάθε υποδιαίρεση ή στοιχείο σήμανσης στην πηγή HTM.{{< /blocks/products/pf/agp/i18n/about-file-text >}}
    {{< /blocks/products/pf/agp/about-file-section >}}
<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Άλλα υποστηριζόμενα φύλλα δημιουργίας" subTitle="Μπορείτε επίσης να δημιουργήσετε άλλα αρχεία Excel Microsoft, συμπεριλαμβανομένων μερικών που αναφέρονται παρακάτω." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/create/xls/" name="XLS" description="Microsoft Υπολογιστικό φύλλο Excel (παλαιού τύπου)" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/create/xlsx/" name="XLSX" description="Ανοίξτε το βιβλίο εργασίας XML" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/create/xlsb/" name="XLSB" description="Δυαδικό βιβλίο εργασίας του Excel" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/create/xlsm/" name="XLSM" description="Υπολογιστικό φύλλο με δυνατότητα μακροεντολής" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/create/xlt/" name="XLT" description="Πρότυπο Excel 97 - 2003" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/create/xltx/" name="XLTX" description="Πρότυπο Excel" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/create/xltm/" name="XLTM" description="Πρότυπο με δυνατότητα μακροεντολής Excel" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/create/csv/" name="CSV" description="Τιμές διαχωρισμένες με κόμματα" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/create/tsv/" name="TSV" description="Τιμές διαχωρισμένες με καρτέλες" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/create/ods/" name="ODS" description="Υπολογιστικό φύλλο OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/create/pdf/" name="PDF" description="Μορφή φορητού εγγράφου" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/create/html/" name="HTML" description="Γλώσσα σήμανσης υπερκειμένου" >}} 


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
