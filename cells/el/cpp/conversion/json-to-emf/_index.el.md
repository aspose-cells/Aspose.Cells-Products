---
title: Μετατροπή JSON σε EMF μέσω της εφαρμογής C++ 
url: /el/cpp/conversion/json-to-emf/ 
description: Δείγμα κώδικα μετατροπής C++ για έγγραφο JSON σε μορφή EMF. Οι προγραμματιστές μπορούν να χρησιμοποιήσουν αυτόν τον πηγαίο κώδικα για μαζική μετατροπή JSON σε EMF σε οποιαδήποτε εφαρμογή C++.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Μετατροπή JSON σε EMF μέσω C++" h2="Μετατροπή JSON σε EMF υψηλής απόδοσης με χρήση βιβλιοθήκης C++ χωρίς την ανάγκη εγκατάστασης Microsoft Excel, OpenOffice ή Adobe Acrobat." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="EMF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="JSON" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Πώς να μετατρέψετε JSON σε EMF χρησιμοποιώντας C++" %}}

 Για να μετατρέψουμε το JSON σε EMF, θα χρησιμοποιήσουμε
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

{{% blocks/products/pf/agp/feature-section-col title="Βήματα για τη μετατροπή JSON σε EMF μέσω C++" %}}

{{% blocks/products/pf/agp/text %}}

 Οι προγραμματιστές του C++ μπορούν εύκολα να μετατρέψουν το αρχείο JSON σε EMF σε λίγες μόνο γραμμές κώδικα.

{{% /blocks/products/pf/agp/text %}}

1. Φορτώστε το αρχείο JSON χρησιμοποιώντας το Factory::CreateIWorkbook.1. Επιλέξτε το πρώτο φύλλο εργασίας.1. Ορισμός επιλογών (EMF).1. Επανάληψη σε κάθε σελίδα του φύλλου και απόδοση.1. Ανοίξτε το αρχείο EMF σε συμβατό πρόγραμμα.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις συστήματος" %}}

{{% blocks/products/pf/agp/text %}}

 Προτού εκτελέσετε το δείγμα κώδικα μετατροπής C++, βεβαιωθείτε ότι διαθέτετε τις ακόλουθες προϋποθέσεις.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ή συμβατό λειτουργικό σύστημα με C++ Runtime Environment για Windows 32 bit, Windows 64 bit και Linux 64 bit.- Aspose.Cells για C++ DLL που αναφέρεται στο έργο σας.
- Microsoft Windows ή συμβατό λειτουργικό σύστημα με C++ Runtime Environment για Windows 32 bit, Windows 64 bit και Linux 64 bit.- Aspose.Cells για C++ DLL που αναφέρεται στο έργο σας.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Πηγαίος κώδικας μετατροπής JSON σε EMF C++" offSpacer="" %}}

```cs
// Διαδρομή καταλόγου εξόδου.
StringPtr outDir = new String("OutputDirectoryPath");

// Φορτώστε το JSON.
intrusive_ptr<Aspose::Cells::IWorkbook> workbook = Factory::CreateIWorkbook(u"sourceFile.json");

// Πρόσβαση στο πρώτο φύλλο εργασίας.
intrusive_ptr<Aspose::Cells::IWorksheet> worksheet = workbook->GetIWorksheets()->GetObjectByIndex(0);

// Δημιουργία αντικειμένου επιλογών εικόνας ή εκτύπωσης.
intrusive_ptr<Aspose::Cells::Rendering::IImageOrPrintOptions> imgOptions = Factory::CreateIImageOrPrintOptions();

// Καθορίστε τη μορφή εικόνας.
imgOptions->SetImageFormat(Aspose::Cells::Systems::Drawing::Imaging::ImageFormat::GetEmf());

// Καθορίστε την οριζόντια και κάθετη ανάλυση
imgOptions->SetHorizontalResolution(200);
imgOptions->SetVerticalResolution(200);

// Αποδώστε το φύλλο σε σχέση με καθορισμένες επιλογές εικόνας ή εκτύπωσης.
intrusive_ptr<Aspose::Cells::Rendering::ISheetRender> sr = Factory::CreateISheetRender(worksheet, imgOptions);

// Λάβετε τον αριθμό σελίδων.
Aspose::Cells::Systems::Int32 pageCount = sr->GetPageCount();

// Δημιουργήστε αντικείμενο δημιουργίας συμβολοσειρών για συνενώσεις συμβολοσειρών.
intrusive_ptr<Aspose::Cells::Systems::Text::StringBuilder> sb = new Aspose::Cells::Systems::Text::StringBuilder();

// Αποδώστε κάθε σελίδα σε εικόνα emf μία προς μία.
for (int i = 0; i Clear();
	sb->Append(outDir);
	sb->Append((StringPtr)new String("outputConvertingWorksheetToImageEMF_"));
	sb->Append(i);
	sb->Append((StringPtr)new String(".emf"));

	// Λάβετε τη διαδρομή εικόνας εξόδου.
	StringPtr outputEMF = sb->ToString();

	// Μετατροπή φύλλου εργασίας σε εικόνα emf.
	sr->ToImage(i, outputEMF);
}


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Ζωντανές επιδείξεις μετατροπής JSON σε EMF" sectionDescription="[Μετατροπή JSON σε EMF](https://products.aspose.app/cells/conversion/json-to-emf) αυτή τη στιγμή, επισκεπτόμενοι τον ιστότοπο Live Demos. Η ζωντανή επίδειξη έχει τα ακόλουθα πλεονεκτήματα" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Δεν χρειάζεται να κάνετε λήψη του Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Δεν χρειάζεται να γράψετε κανέναν κώδικα." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Απλώς ανεβάστε το αρχείο JSON σας, θα μετατραπεί αμέσως σε EMF." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Θα λάβετε τον σύνδεσμο λήψης." >}}

    {{% blocks/products/pf/agp/content h2="C++ Βιβλιοθήκη χειρισμού αρχείων Excel" %}}

 Το Excel API μπορεί να χρησιμοποιηθεί για τη δημιουργία, επεξεργασία, μετατροπή και απόδοση μορφών Microsoft Excel σε διαφορετικές μορφές. Επιπλέον, μπορεί να χρησιμοποιηθεί για ολοκληρωμένη χαρτογράφηση, κλιμακούμενη αναφορά και αξιόπιστους υπολογισμούς εντός εφαρμογών λογισμικού. Το Aspose.Cells είναι αυτόνομο API και δεν απαιτεί λογισμικό όπως η Microsoft ή το OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="JSON" readMoreLink="https://docs.fileformat.com/web/json/" >}}

Το JSON (JavaScript Object Notation) είναι μια ανοιχτή τυπική μορφή αρχείου για κοινή χρήση δεδομένων που χρησιμοποιεί κείμενο αναγνώσιμο από τον άνθρωπο για την αποθήκευση και τη μετάδοση δεδομένων. Τα αρχεία JSON αποθηκεύονται με την επέκταση .json. Το JSON απαιτεί λιγότερη μορφοποίηση και είναι μια καλή εναλλακτική για XML. Το JSON προέρχεται από JavaScript αλλά είναι μια μορφή δεδομένων ανεξάρτητη από τη γλώσσα. Η δημιουργία και η ανάλυση του JSON υποστηρίζεται από πολλές σύγχρονες γλώσσες προγραμματισμού. application/json είναι ο τύπος μέσου που χρησιμοποιείται για το JSON.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="EMF" readMoreLink="https://docs.fileformat.com/image/emf/" >}}

Η βελτιωμένη μορφή μετα-αρχείου (EMF) αποθηκεύει γραφικές εικόνες ανεξάρτητα από τη συσκευή. Τα μετααρχεία του EMF αποτελούνται από εγγραφές μεταβλητού μήκους με χρονολογική σειρά που μπορούν να αποδώσουν την αποθηκευμένη εικόνα μετά την ανάλυση σε οποιαδήποτε συσκευή εξόδου. Αυτές οι εγγραφές μεταβλητού μήκους μπορεί να είναι ορισμοί εσώκλειστων αντικειμένων, εντολές για σχέδιο και ιδιότητες γραφικών που είναι κρίσιμες για την ακριβή απόδοση της εικόνας. Όταν μια συσκευή ανοίγει ένα μετααρχείο EMF χρησιμοποιώντας το δικό της περιβάλλον γραφικών, οι αναλογίες, οι διαστάσεις, τα χρώματα και άλλες γραφικές ιδιότητες της αρχικής εικόνας παραμένουν ίδιες ανεξάρτητα από την πλατφόρμα της συσκευής ανοίγματος.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}