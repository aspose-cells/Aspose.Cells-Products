---
title: Μετατροπή CSV σε XLSB μέσω της εφαρμογής C++ 
weight: 9780
url: /el/cpp/conversion/csv-to-xlsb/ 
description: Δείγμα κώδικα μετατροπής C++ για έγγραφο CSV σε μορφή XLSB. Οι προγραμματιστές μπορούν να χρησιμοποιήσουν αυτόν τον πηγαίο κώδικα για ομαδική μετατροπή CSV σε XLSB σε οποιαδήποτε εφαρμογή C++.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Μετατροπή CSV σε XLSB μέσω C++" h2="Μετατροπή CSV σε XLSB υψηλής απόδοσης με χρήση βιβλιοθήκης C++ χωρίς την ανάγκη εγκατάστασης Microsoft Excel, OpenOffice ή Adobe Acrobat." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSB" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="CSV" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Τρόπος μετατροπής CSV σε XLSB χρησιμοποιώντας το C++" %}}

 Για να μετατρέψουμε το CSV σε XLSB, θα χρησιμοποιήσουμε
 [Aspose.Cells για C++](https://products.aspose.com/cells/cpp) 
 API που είναι μια πλατφόρμα πλούσια σε χαρακτηριστικά, ισχυρή και εύκολη στη χρήση χειρισμό και μετατροπή εγγράφων API για C++. Μπορείτε να κατεβάσετε την τελευταία του έκδοση απευθείας, απλά ανοίξτε
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 διαχειριστής πακέτων, αναζητήστε
 Aspose.Cells.Cpp 
 και εγκαταστήστε. Μπορείτε επίσης να χρησιμοποιήσετε την ακόλουθη εντολή από την Κονσόλα Package Manager.

{{% blocks/products/pf/agp/code-block title="Εντολή" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Βήματα για τη μετατροπή CSV σε XLSB μέσω C++" %}}

{{% blocks/products/pf/agp/text %}}

 Οι προγραμματιστές του C++ μπορούν εύκολα να μετατρέψουν το αρχείο CSV σε XLSB σε λίγες μόνο γραμμές κώδικα.

{{% /blocks/products/pf/agp/text %}}

1. Φορτώστε το αρχείο CSV χρησιμοποιώντας το Factory::CreateIWorkbook.1. Καλέστε τη μέθοδο Save().1. Περάστε τη διαδρομή του αρχείου εξόδου με επέκταση αρχείου (XLSB).1. Το αρχείο XLSB θα αποθηκευτεί στην καθορισμένη διαδρομή.1. Ανοίξτε το αρχείο XLSB σε συμβατό πρόγραμμα.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις συστήματος" %}}

{{% blocks/products/pf/agp/text %}}

 Προτού εκτελέσετε το δείγμα κώδικα μετατροπής C++, βεβαιωθείτε ότι διαθέτετε τις ακόλουθες προϋποθέσεις.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ή συμβατό λειτουργικό σύστημα με C++ Runtime Environment για Windows 32 bit, Windows 64 bit και Linux 64 bit.- Aspose.Cells για C++ DLL που αναφέρεται στο έργο σας.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Πηγαίος κώδικας μετατροπής CSV σε XLSB C++" offSpacer="" %}}

```cs
// Φορτώστε το CSV.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.csv");

// Αποθήκευση σε μορφή XLSB.
wkb->Save(u"convertedFile.xlsb", SaveFormat_Xlsb);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Ζωντανές επιδείξεις μετατροπής CSV σε XLSB" sectionDescription="[Μετατροπή CSV σε XLSB](https://products.aspose.app/cells/conversion/csv-to-xlsb) αυτή τη στιγμή, επισκεπτόμενοι τον ιστότοπο Live Demos. Η ζωντανή επίδειξη έχει τα ακόλουθα πλεονεκτήματα" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Δεν χρειάζεται να κάνετε λήψη του Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Δεν χρειάζεται να γράψετε κανέναν κώδικα." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Απλώς ανεβάστε το αρχείο CSV σας, θα μετατραπεί αμέσως σε XLSB." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Θα λάβετε τον σύνδεσμο λήψης." >}}

    {{% blocks/products/pf/agp/content h2="C++ Βιβλιοθήκη χειρισμού αρχείων Excel" %}}

 Το Excel API μπορεί να χρησιμοποιηθεί για τη δημιουργία, επεξεργασία, μετατροπή και απόδοση μορφών Microsoft Excel σε διαφορετικές μορφές. Επιπλέον, μπορεί να χρησιμοποιηθεί για ολοκληρωμένη χαρτογράφηση, κλιμακούμενη αναφορά και αξιόπιστους υπολογισμούς εντός εφαρμογών λογισμικού. Το Aspose.Cells είναι αυτόνομο API και δεν απαιτεί λογισμικό όπως η Microsoft ή το OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="CSV" readMoreLink="https://docs.fileformat.com/spreadsheet/csv/" >}}

Τα αρχεία με επέκταση CSV (Τιμές διαχωρισμένες με κόμματα) αντιπροσωπεύουν αρχεία απλού κειμένου που περιέχουν εγγραφές δεδομένων με τιμές διαχωρισμένες με κόμμα. Κάθε γραμμή σε ένα αρχείο CSV είναι μια νέα εγγραφή από το σύνολο εγγραφών που περιέχεται στο αρχείο. Τέτοια αρχεία δημιουργούνται όταν η μεταφορά δεδομένων προορίζεται από το ένα σύστημα αποθήκευσης στο άλλο. Δεδομένου ότι όλες οι εφαρμογές μπορούν να αναγνωρίσουν εγγραφές που χωρίζονται με κόμμα, η εισαγωγή τέτοιων αρχείων δεδομένων στη βάση δεδομένων γίνεται πολύ εύκολα. Σχεδόν όλες οι εφαρμογές υπολογιστικών φύλλων όπως το Microsoft Excel ή το OpenOffice Calc μπορούν να εισάγουν CSV χωρίς μεγάλη προσπάθεια. Τα δεδομένα που εισάγονται από τέτοια αρχεία ταξινομούνται σε κελιά ενός υπολογιστικού φύλλου για αναπαράσταση στον χρήστη.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSB" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsb/" >}}

Η μορφή αρχείου XLSB καθορίζει τη Μορφή δυαδικού αρχείου του Excel, η οποία είναι μια συλλογή εγγραφών και δομών που καθορίζουν το περιεχόμενο του βιβλίου εργασίας του Excel. Το περιεχόμενο μπορεί να περιλαμβάνει μη δομημένους ή ημιδομημένους πίνακες αριθμών, κείμενο ή και αριθμούς και κείμενο, τύπους, εξωτερικές συνδέσεις δεδομένων, γραφήματα και εικόνες. Σε αντίθεση με το XLSX (το οποίο βασίζεται σε μορφή αρχείου Open XML), το XLSB αντιπροσωπεύει το δυαδικό αρχείο βιβλίου εργασίας του Excel. Τα αρχεία XLSB μπορούν να διαβαστούν και να γραφτούν ταχύτερα, γεγονός που τα καθιστά χρήσιμα για εργασία με μεγάλα αρχεία. Το XLSB χρησιμοποιείται σπάνια για την αποθήκευση βιβλίων εργασίας, καθώς το XLSX (και παλαιότερα το XLS) είναι οι πιο κοινές μορφές αρχείων που επιλέγονται από τον χρήστη για την αποθήκευση βιβλίων εργασίας. Μπορεί να ανοίξει από το Microsoft Office 2007 και νεότερη έκδοση.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μετατροπές" subTitle="Μπορείτε επίσης να μετατρέψετε το CSV σε πολλές άλλες μορφές αρχείων, συμπεριλαμβανομένων μερικών που αναφέρονται παρακάτω." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-bmp/" name="CSV TO BMP" description="Εικόνα Bitmap" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-dif/" name="CSV TO DIF" description="Μορφή ανταλλαγής δεδομένων" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-emf/" name="CSV ΣΕ EMF" description="Βελτιωμένη μορφή μετα-αρχείου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-gif/" name="CSV ΣΕ GIF" description="Μορφή γραφικής ανταλλαγής" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-html/" name="CSV ΣΕ HTML" description="Γλώσσα σήμανσης υπερκειμένου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-jpeg/" name="CSV ΣΕ JPEG" description="Εικόνα JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-mhtml/" name="CSV ΣΕ MHTML" description="Μορφή αρχείου ιστοσελίδας" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-ods/" name="CSV TO ODS" description="Αρχείο υπολογιστικού φύλλου OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-pdf/" name="CSV ΣΕ PDF" description="Μορφή φορητού εγγράφου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-png/" name="CSV ΣΕ PNG" description="Φορητά γραφικά δικτύου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-svg/" name="CSV ΣΕ SVG" description="Κλιμακόμενα διανυσματικά γραφικά" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-tiff/" name="CSV TO TIFF" description="Με ετικέτα Μορφή εικόνας" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-tsv/" name="CSV TO TSV" description="Τιμές διαχωρισμένες με καρτέλες" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-xls/" name="CSV ΣΕ XLS" description="Δυαδική μορφή Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-xlsm/" name="CSV ΣΕ XLSM" description="Αρχείο υπολογιστικού φύλλου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-xlsx/" name="CSV ΣΕ XLSX" description="Αρχείο Excel OOXML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-xltm/" name="CSV TO XLTM" description="Πρότυπο με δυνατότητα μακροεντολής Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-xltx/" name="CSV ΣΕ XLTX" description="Πρότυπο Office OpenXML Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-xps/" name="CSV ΣΕ XPS" description="Προδιαγραφές χαρτιού XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}