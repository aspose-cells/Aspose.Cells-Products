---
title: Μετατροπή HTML σε XLSX μέσω της εφαρμογής C++ 
weight: 9770
url: /el/cpp/conversion/html-to-xlsx/ 
description: Δείγμα κώδικα μετατροπής C++ για έγγραφο HTML σε μορφή XLSX. Οι προγραμματιστές μπορούν να χρησιμοποιήσουν αυτόν τον πηγαίο κώδικα για ομαδική μετατροπή HTML σε XLSX σε οποιαδήποτε εφαρμογή C++.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Μετατροπή HTML σε XLSX μέσω C++" h2="Μετατροπή HTML σε XLSX υψηλής απόδοσης με χρήση βιβλιοθήκης C++ χωρίς την ανάγκη εγκατάστασης Microsoft Excel, OpenOffice ή Adobe Acrobat." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="HTML" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Πώς να μετατρέψετε HTML σε XLSX χρησιμοποιώντας C++" %}}

 Για να μετατρέψουμε την HTML σε XLSX, θα χρησιμοποιήσουμε
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

{{% blocks/products/pf/agp/feature-section-col title="Βήματα για τη μετατροπή HTML σε XLSX μέσω C++" %}}

{{% blocks/products/pf/agp/text %}}

 Οι προγραμματιστές του C++ μπορούν εύκολα να μετατρέψουν το αρχείο HTML σε XLSX σε λίγες μόνο γραμμές κώδικα.

{{% /blocks/products/pf/agp/text %}}

1. Φόρτωση αρχείου HTML χρησιμοποιώντας το Factory::CreateIWorkbook.1. Καλέστε τη μέθοδο Save().1. Περάστε τη διαδρομή του αρχείου εξόδου με επέκταση αρχείου (XLSX).1. Το αρχείο XLSX θα αποθηκευτεί στην καθορισμένη διαδρομή.1. Ανοίξτε το αρχείο XLSX σε συμβατό πρόγραμμα.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις συστήματος" %}}

{{% blocks/products/pf/agp/text %}}

 Προτού εκτελέσετε το δείγμα κώδικα μετατροπής C++, βεβαιωθείτε ότι διαθέτετε τις ακόλουθες προϋποθέσεις.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ή συμβατό λειτουργικό σύστημα με C++ Runtime Environment για Windows 32 bit, Windows 64 bit και Linux 64 bit.- Aspose.Cells για C++ DLL που αναφέρεται στο έργο σας.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Πηγαίος κώδικας μετατροπής HTML σε XLSX C++" offSpacer="" %}}

```cs
// Φορτώστε το HTML.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.html");

// Αποθήκευση σε μορφή XLSX.
wkb->Save(u"convertedFile.xlsx", SaveFormat_Xlsx);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Ζωντανές επιδείξεις μετατροπής HTML σε XLSX" sectionDescription="[Μετατροπή HTML σε XLSX](https://products.aspose.app/cells/conversion/html-to-xlsx) αυτή τη στιγμή, επισκεπτόμενοι τον ιστότοπο Live Demos. Η ζωντανή επίδειξη έχει τα ακόλουθα πλεονεκτήματα" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Δεν χρειάζεται να κάνετε λήψη του Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Δεν χρειάζεται να γράψετε κανέναν κώδικα." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Απλώς ανεβάστε το αρχείο HTML σας, θα μετατραπεί αμέσως σε XLSX." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Θα λάβετε τον σύνδεσμο λήψης." >}}

    {{% blocks/products/pf/agp/content h2="C++ Βιβλιοθήκη χειρισμού αρχείων Excel" %}}

 Το Excel API μπορεί να χρησιμοποιηθεί για τη δημιουργία, επεξεργασία, μετατροπή και απόδοση μορφών Microsoft Excel σε διαφορετικές μορφές. Επιπλέον, μπορεί να χρησιμοποιηθεί για ολοκληρωμένη χαρτογράφηση, κλιμακούμενη αναφορά και αξιόπιστους υπολογισμούς εντός εφαρμογών λογισμικού. Το Aspose.Cells είναι αυτόνομο API και δεν απαιτεί λογισμικό όπως η Microsoft ή το OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="HTML" readMoreLink="https://docs.fileformat.com/web/html/" >}}

Η HTML (Hyper Text Markup Language) είναι η επέκταση για ιστοσελίδες που δημιουργούνται για εμφάνιση σε προγράμματα περιήγησης. Γνωστή ως γλώσσα του Ιστού, η HTML έχει εξελιχθεί με απαιτήσεις νέων απαιτήσεων πληροφοριών που πρέπει να εμφανίζονται ως μέρος ιστοσελίδων. Η τελευταία παραλλαγή είναι γνωστή ως HTML 5 που δίνει μεγάλη ευελιξία στην εργασία με τη γλώσσα. Οι σελίδες HTML είτε λαμβάνονται από τον διακομιστή, όπου φιλοξενούνται, είτε μπορούν να φορτωθούν και από το τοπικό σύστημα. Κάθε σελίδα HTML αποτελείται από στοιχεία HTML όπως φόρμες, κείμενο, εικόνες, κινούμενα σχέδια, σύνδεσμοι κ.λπ. Αυτά τα στοιχεία αντιπροσωπεύονται από ετικέτες όπως img, a, p και πολλές άλλες όπου κάθε ετικέτα έχει αρχή και τέλος. Μπορεί επίσης να ενσωματώσει εφαρμογές γραμμένες σε γλώσσες δέσμης ενεργειών όπως JavaScript και Style Sheets (CSS) για συνολική αναπαράσταση διάταξης.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSX" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsx/" >}}

Το XLSX είναι μια πολύ γνωστή μορφή για έγγραφα του Microsoft Excel που εισήχθη από τη Microsoft με την κυκλοφορία του Microsoft Office 2007. Με βάση τη δομή που οργανώθηκε σύμφωνα με τις συμβάσεις ανοιχτής συσκευασίας, όπως περιγράφεται στο Μέρος 2 του προτύπου OOXML ECMA-376, η νέα μορφή είναι ένα πακέτο zip που περιέχει έναν αριθμό αρχείων XML. Η υποκείμενη δομή και τα αρχεία μπορούν να εξεταστούν απλά αποσυμπιέζοντας το αρχείο .xlsx.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μετατροπές" subTitle="Μπορείτε επίσης να μετατρέψετε HTML σε πολλές άλλες μορφές αρχείων, συμπεριλαμβανομένων μερικών που αναφέρονται παρακάτω." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-bmp/" name="HTML ΣΕ BMP" description="Εικόνα Bitmap" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-csv/" name="HTML ΣΕ CSV" description="Τιμές διαχωρισμένες με κόμματα" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-dif/" name="HTML ΣΕ ΔΙΑΦ" description="Μορφή ανταλλαγής δεδομένων" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-emf/" name="HTML ΣΕ EMF" description="Βελτιωμένη μορφή μετα-αρχείου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-gif/" name="HTML ΣΕ GIF" description="Μορφή γραφικής ανταλλαγής" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-jpeg/" name="HTML ΣΕ JPEG" description="Εικόνα JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-mhtml/" name="HTML ΣΕ MHTML" description="Μορφή αρχείου ιστοσελίδας" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-ods/" name="HTML TO ODS" description="Αρχείο υπολογιστικού φύλλου OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-pdf/" name="HTML ΣΕ PDF" description="Μορφή φορητού εγγράφου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-png/" name="HTML ΣΕ PNG" description="Φορητά γραφικά δικτύου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-svg/" name="HTML ΣΕ SVG" description="Κλιμακόμενα διανυσματικά γραφικά" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-tiff/" name="HTML TO TIFF" description="Με ετικέτα Μορφή εικόνας" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-tsv/" name="HTML TO TSV" description="Τιμές διαχωρισμένες με καρτέλες" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-xls/" name="HTML ΣΕ XLS" description="Δυαδική μορφή Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-xlsb/" name="HTML ΣΕ XLSB" description="Δυαδικό αρχείο βιβλίου εργασίας Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-xlsm/" name="HTML ΣΕ XLSM" description="Αρχείο υπολογιστικού φύλλου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-xltm/" name="HTML ΣΕ XLTM" description="Πρότυπο με δυνατότητα μακροεντολής Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-xltx/" name="HTML ΣΕ XLTX" description="Πρότυπο Office OpenXML Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-xps/" name="HTML ΣΕ XPS" description="Προδιαγραφές χαρτιού XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}