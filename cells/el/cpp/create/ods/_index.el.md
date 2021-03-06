---
title: Δημιουργία αρχείων ODS (Openoffice / Lbreoffice) μέσω C++ 
url: /el/cpp/create-ods/ 
description: C++ Δείγμα κώδικα για τη δημιουργία αρχείων ODS (Openoffice / Lbreoffice). Χρησιμοποιήστε αυτόν τον κωδικό για τη δημιουργία αρχείων ODS (Openoffice / Lbreoffice) εντός εφαρμογής που βασίζεται σε C++.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Δημιουργία αρχείου ODS μέσω C++" h2="Δημιουργία υπολογιστικών φύλλων εγγενούς και υψηλής απόδοσης ODS (Openoffice / Lbreoffice) μέσω προγραμματισμού χωρίς το Micorsoft Office χρησιμοποιώντας τη βιβλιοθήκη C++." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODS" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="" %}}

 Η δυναμική δημιουργία αρχείου ODS (Openoffice / Lbreoffice) εντός της εκτελούμενης εφαρμογής είναι εύκολη. Για να δημιουργήσουμε έγγραφα ODS από την αρχή χωρίς να απαιτείται MS Office, θα χρησιμοποιήσουμε
 [Aspose.Cells για C++](https://products.aspose.com/cells/cpp) 
 API που προσφέρει διαφορετικές δυνατότητες για τη δημιουργία, τον χειρισμό και τη μετατροπή εγγράφων χρησιμοποιώντας την πλατφόρμα C++. Οι προγραμματιστές μπορούν εύκολα να βελτιώσουν τον κώδικα για την ενημέρωση δεδομένων κελιών, τη δημιουργία γραφημάτων ή γραφημάτων, καθώς και τη δημιουργία συγκεντρωτικού πίνακα, την προσθήκη τύπων επιπέδου κελιών και άλλα σε υπολογιστικά φύλλα.
{{% /blocks/products/pf/agp/content %}}                                                                             

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Πώς να δημιουργήσετε ODS μέσω C++" %}}

{{% blocks/products/pf/agp/text %}}

 Είναι εύκολο για τους προγραμματιστές να δημιουργήσουν, να φορτώσουν, να τροποποιήσουν και να μετατρέψουν αρχεία ODS εντός εφαρμογών αναφοράς που εκτελούνται για επεξεργασία δεδομένων σε λίγες μόνο γραμμές κώδικα.

{{% /blocks/products/pf/agp/text %}}

1. Δημιουργήστε ένα αντικείμενο της κλάσης IWorkbook.1. Αποκτήστε το πρώτο φύλλο σε ένα αντικείμενο IWorksheet.1. Χρησιμοποιήστε τη μέθοδο IWorksheet->GetICells() για να μεταφέρετε τα κελιά του φύλλου εργασίας σε ένα αντικείμενο ICElls.1. Χρησιμοποιήστε τη μέθοδο ICElls->GetObjectByIndex() για πρόσβαση στο επιθυμητό κελί του φύλλου εργασίας σε ένα αντικείμενο ICEL.1. Χρησιμοποιήστε τη μέθοδο ICEll->PutValue() για να εισαγάγετε τιμή στο κελί.1. Αποθηκεύστε το βιβλίο εργασίας ως αρχείο .ods χρησιμοποιώντας τη μέθοδο Save().
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις συστήματος" %}}

{{% blocks/products/pf/agp/text %}}

Προτού εκτελέσετε το δείγμα πηγαίου κώδικα μετατροπής C++, βεβαιωθείτε ότι διαθέτετε τις ακόλουθες προϋποθέσεις. 

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ή συμβατό λειτουργικό σύστημα με C++ Runtime Environment για Windows 32 bit, Windows 64 bit και Linux 64 bit.- Aspose.Cells για C++ DLL που αναφέρεται στο έργο σας.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Ο παρακάτω πηγαίος κώδικας δείχνει πώς να δημιουργήσετε ένα αρχείο ODS (Openoffice / Lbreoffice) χρησιμοποιώντας το C++." offSpacer="" %}}

```cs

// Δημιουργήστε ένα αντικείμενο της κλάσης IWorkbook.
intrusive_ptr<IWorkbook> wkb = Factory::CreateIWorkbook();

// Αποκτήστε το πρώτο φύλλο σε ένα αντικείμενο IWorksheet.
intrusive_ptr<IWorksheetCollection> wsc = wkb->GetIWorksheets();
intrusive_ptr<IWorksheet> ws = wsc->GetObjectByIndex(0);

// Χρησιμοποιήστε τη μέθοδο IWorksheet->GetICells() για να μεταφέρετε τα κελιά του φύλλου εργασίας σε ένα αντικείμενο ICElls.
intrusive_ptr<ICells> cells = ws->GetICells();

// Χρησιμοποιήστε τη μέθοδο ICElls->GetObjectByIndex() για πρόσβαση στο επιθυμητό κελί του φύλλου εργασίας σε ένα αντικείμενο ICEL.
intrusive_ptr<ICell> cell00 = cells->GetObjectByIndex(0, 0);
intrusive_ptr<ICell> cell01 = cells->GetObjectByIndex(0, 1);
intrusive_ptr<ICell> cell10 = cells->GetObjectByIndex(1, 0);
intrusive_ptr<ICell> cell11 = cells->GetObjectByIndex(1, 1);

// Χρησιμοποιήστε τη μέθοδο ICEll->PutValue() για να εισαγάγετε τιμή στο κελί.
cell00->PutValue(new String("ColumnA"));
cell01->PutValue(new String("ColumnB"));
cell10->PutValue(new String("ValueA"));
cell11->PutValue(new String("ValueB"));

// Αποθήκευση βιβλίου εργασίας στο φάκελο resultFile
wkb->Save(new String("created_one.ods"));


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<!-- aboutfile Starts -->

     
     {{% blocks/products/pf/agp/content h2="" %}}

Μια Βιβλιοθήκη Προγραμματισμού Υπολογιστικών Φύλλων Excel ικανή να δημιουργεί εφαρμογές πολλαπλών πλατφορμών με δυνατότητα δημιουργίας, τροποποίησης, μετατροπής, απόδοσης και εκτύπωσης αρχείων ODS (Openoffice / Lbreoffice). Το C++ Excel API όχι μόνο μετατρέπει μεταξύ μορφών υπολογιστικών φύλλων, αλλά μπορεί επίσης να αποδώσει αρχεία Excel ως εικόνες, PDF, HTML, ODS και άλλα, καθιστώντας έτσι την τέλεια επιλογή για την ανταλλαγή εγγράφων σε τυποποιημένες μορφές του κλάδου.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODS" readMoreLink="https://docs.fileformat.com/spreadsheet/ods/" >}}

       {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< /blocks/products/pf/agp/about-file-section >}}

          

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Άλλα υποστηριζόμενα φύλλα δημιουργίας" subTitle="Μπορείτε επίσης να δημιουργήσετε άλλα αρχεία Microsoft Excel, συμπεριλαμβανομένων μερικών που αναφέρονται παρακάτω." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/create-xls/" name="XLS" description="Υπολογιστικό φύλλο Microsoft Excel (παλαιού τύπου)" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/create-xlsx/" name="XLSX" description="Ανοίξτε το βιβλίο εργασίας XML" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/create-xlsb/" name="XLSB" description="Δυαδικό βιβλίο εργασίας του Excel" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/create-xlsm/" name="XLSM" description="Υπολογιστικό φύλλο με δυνατότητα μακροεντολής" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/create-xlt/" name="XLT" description="Πρότυπο Excel 97 - 2003" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/create-xltx/" name="XLTX" description="Πρότυπο Excel" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/create-xltm/" name="XLTM" description="Πρότυπο με δυνατότητα μακροεντολής Excel" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/create-csv/" name="CSV" description="Τιμές διαχωρισμένες με κόμματα" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/create-tsv/" name="TSV" description="Τιμές διαχωρισμένες με καρτέλες" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/create-ods/" name="ODS" description="Υπολογιστικό φύλλο OpenDocument" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
