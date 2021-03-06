---
title: Μετατρέψτε το XLSM σε EMF μέσω της εφαρμογής C++ 
url: /el/cpp/conversion/xlsm-to-emf/ 
description: Δείγμα κώδικα μετατροπής C++ για έγγραφο XLSM σε μορφή EMF. Οι προγραμματιστές μπορούν να χρησιμοποιήσουν αυτόν τον πηγαίο κώδικα για μαζική μετατροπή XLSM σε EMF σε οποιαδήποτε εφαρμογή C++.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Μετατροπή XLSM σε EMF μέσω C++" h2="Μετατροπή XLSM σε EMF υψηλής απόδοσης με χρήση της βιβλιοθήκης C++ χωρίς την ανάγκη εγκατάστασης Microsoft Excel, OpenOffice ή Adobe Acrobat." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="EMF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Πώς να μετατρέψετε το XLSM σε EMF χρησιμοποιώντας το C++" %}}

 Για να μετατρέψουμε το XLSM σε EMF, θα χρησιμοποιήσουμε
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

{{% blocks/products/pf/agp/feature-section-col title="Βήματα για τη μετατροπή XLSM σε EMF μέσω C++" %}}

{{% blocks/products/pf/agp/text %}}

 Οι προγραμματιστές του C++ μπορούν εύκολα να μετατρέψουν το αρχείο XLSM σε EMF σε λίγες μόνο γραμμές κώδικα.

{{% /blocks/products/pf/agp/text %}}

1. Φορτώστε το αρχείο XLSM χρησιμοποιώντας το Factory::CreateIWorkbook.1. Επιλέξτε το πρώτο φύλλο εργασίας.1. Ορισμός επιλογών (EMF).1. Επανάληψη σε κάθε σελίδα του φύλλου και απόδοση.1. Ανοίξτε το αρχείο EMF σε συμβατό πρόγραμμα.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις συστήματος" %}}

{{% blocks/products/pf/agp/text %}}

 Προτού εκτελέσετε το δείγμα κώδικα μετατροπής C++, βεβαιωθείτε ότι διαθέτετε τις ακόλουθες προϋποθέσεις.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ή συμβατό λειτουργικό σύστημα με C++ Runtime Environment για Windows 32 bit, Windows 64 bit και Linux 64 bit.- Aspose.Cells για C++ DLL που αναφέρεται στο έργο σας.
- Microsoft Windows ή συμβατό λειτουργικό σύστημα με C++ Runtime Environment για Windows 32 bit, Windows 64 bit και Linux 64 bit.- Aspose.Cells για C++ DLL που αναφέρεται στο έργο σας.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Πηγαίος κώδικας μετατροπής XLSM σε EMF C++" offSpacer="" %}}

```cs
// Διαδρομή καταλόγου εξόδου.
StringPtr outDir = new String("OutputDirectoryPath");

// Φορτώστε το XLSM.
intrusive_ptr<Aspose::Cells::IWorkbook> workbook = Factory::CreateIWorkbook(u"sourceFile.xlsm");

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

{{< blocks/products/pf/agp/demobox sectionTitle="Ζωντανές επιδείξεις μετατροπής XLSM σε EMF" sectionDescription="[Μετατροπή XLSM σε EMF](https://products.aspose.app/cells/conversion/xlsm-to-emf) αυτή τη στιγμή, επισκεπτόμενοι τον ιστότοπο Live Demos. Η ζωντανή επίδειξη έχει τα ακόλουθα πλεονεκτήματα" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Δεν χρειάζεται να κάνετε λήψη του Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Δεν χρειάζεται να γράψετε κανέναν κώδικα." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Απλώς ανεβάστε το αρχείο XLSM, θα μετατραπεί αμέσως σε EMF." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Θα λάβετε τον σύνδεσμο λήψης." >}}

    {{% blocks/products/pf/agp/content h2="C++ Βιβλιοθήκη χειρισμού αρχείων Excel" %}}

 Το Excel API μπορεί να χρησιμοποιηθεί για τη δημιουργία, επεξεργασία, μετατροπή και απόδοση μορφών Microsoft Excel σε διαφορετικές μορφές. Επιπλέον, μπορεί να χρησιμοποιηθεί για ολοκληρωμένη χαρτογράφηση, κλιμακούμενη αναφορά και αξιόπιστους υπολογισμούς εντός εφαρμογών λογισμικού. Το Aspose.Cells είναι αυτόνομο API και δεν απαιτεί λογισμικό όπως η Microsoft ή το OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSM" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsm/" >}}

Τα αρχεία με επέκταση XLSM είναι ένας τύπος αρχείων υπολογιστικού φύλλου που υποστηρίζουν μακροεντολές. Από την άποψη της εφαρμογής, μια Μακροεντολή είναι ένα σύνολο οδηγιών που χρησιμοποιούνται για την αυτοματοποίηση των διαδικασιών. Μια μακροεντολή χρησιμοποιείται για την καταγραφή των βημάτων που εκτελούνται επανειλημμένα και διευκολύνει την εκτέλεση των ενεργειών εκτελώντας ξανά τη μακροεντολή. Οι μακροεντολές προγραμματίζονται με τη Visual Basic για Εφαρμογές (VBA) της Microsoft μέσα από το Βιβλίο εργασίας του Excel χρησιμοποιώντας τον Επεξεργαστή Visual Basic και μπορούν να εκτελεστούν/εντοπιστούν σφάλματα απευθείας από εκεί.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="EMF" readMoreLink="https://docs.fileformat.com/image/emf/" >}}

Η βελτιωμένη μορφή μετα-αρχείου (EMF) αποθηκεύει γραφικές εικόνες ανεξάρτητα από τη συσκευή. Τα μετααρχεία του EMF αποτελούνται από εγγραφές μεταβλητού μήκους με χρονολογική σειρά που μπορούν να αποδώσουν την αποθηκευμένη εικόνα μετά την ανάλυση σε οποιαδήποτε συσκευή εξόδου. Αυτές οι εγγραφές μεταβλητού μήκους μπορεί να είναι ορισμοί εσώκλειστων αντικειμένων, εντολές για σχέδιο και ιδιότητες γραφικών που είναι κρίσιμες για την ακριβή απόδοση της εικόνας. Όταν μια συσκευή ανοίγει ένα μετααρχείο EMF χρησιμοποιώντας το δικό της περιβάλλον γραφικών, οι αναλογίες, οι διαστάσεις, τα χρώματα και άλλες γραφικές ιδιότητες της αρχικής εικόνας παραμένουν ίδιες ανεξάρτητα από την πλατφόρμα της συσκευής ανοίγματος.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}