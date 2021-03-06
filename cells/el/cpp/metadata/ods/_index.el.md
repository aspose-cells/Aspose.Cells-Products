---
title: Επεξεργασία ή προβολή μεταδεδομένων εγγράφου ODS μέσω C++ 
weight: 1000
url: /el/cpp/metadata/ods/ 
description: C++ παράδειγμα κώδικα για επεξεργασία ή προβολή μεταδεδομένων αρχείου ODS στο C++ Runtime Environment για Windows 32 bit, Windows 64 bit και Linux 64 bit.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Εξαγωγή μεταδεδομένων ODS μέσω C++" h2="Δημιουργήστε τις δικές σας C++ εφαρμογές για να προσθέσετε, να επεξεργαστείτε, να αφαιρέσετε ή να εξαγάγετε μεταδεδομένα από αρχεία ODS χρησιμοποιώντας API από την πλευρά του διακομιστή." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODS" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Τρόπος λήψης μεταδεδομένων ODS χρησιμοποιώντας C++" %}}

 Για να εξαγάγουμε τα μεταδεδομένα ODS, θα χρησιμοποιήσουμε
 [Aspose.Cells για C++](https://products.aspose.com/cells/cpp) 
 API που είναι μια πλατφόρμα εξαγωγής μεταδεδομένων εγγράφων πλούσια σε χαρακτηριστικά, ισχυρή και εύκολη στη χρήση API για C++. Μπορείτε να κατεβάσετε την τελευταία του έκδοση απευθείας, απλά ανοίξτε
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 διαχειριστής πακέτων, αναζητήστε
 **Aspose.Cells.Cpp** 
 και εγκαταστήστε. Μπορείτε επίσης να χρησιμοποιήσετε την ακόλουθη εντολή από την Κονσόλα Package Manager.

{{% blocks/products/pf/agp/code-block title="Εντολή" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Βήματα για την εξαγωγή μεταδεδομένων του ODS μέσω C++" %}}

{{% blocks/products/pf/agp/text %}}

 Πρόσβαση σε χρήσιμες πληροφορίες που είναι αποθηκευμένες στο αρχείο ODS, συμπεριλαμβανομένου του χρόνου λήψης, επεξεργασίας, χρονικής σφραγίδας και ούτω καθεξής.

{{% /blocks/products/pf/agp/text %}}

+ Φορτώστε το αρχείο ODS χρησιμοποιώντας το CreateIWorkbookMetadata
+ Δημιουργήστε επιλογές χρησιμοποιώντας το CreateIMetadataOptions
+ Προσθήκη νέων ιδιοτήτων από τα GetICustomDocumentProperties() και AddIDocumentProperty
+ Αποθήκευση εγγράφου ODS

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις συστήματος" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells για C++ υποστηρίζει σε όλες τις μεγάλες πλατφόρμες και λειτουργικά συστήματα. Βεβαιωθείτε ότι έχετε τις ακόλουθες προϋποθέσεις.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ή συμβατό λειτουργικό σύστημα με C++ Runtime Environment για Windows 32 bit, Windows 64 bit και Linux 64 bit.- Aspose.Cells για C++ DLL που αναφέρεται στο έργο σας.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Εξαγωγή μεταδεδομένων ODS - C++" offSpacer="" %}}

```cs

intrusive_ptr<IMetadataOptions> options = Factory::CreateIMetadataOptions(MetadataType_DocumentProperties);
intrusive_ptr<IWorkbookMetadata> meta = Factory::CreateIWorkbookMetadata(new String("c:\\book1.ods"), options);
meta->GetICustomDocumentProperties()->AddIDocumentProperty(new String("test"), (StringPtr)new String("test"));
meta->Save(new String("c:\\book2.ods"));  


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Σχετικά με Aspose.Cells για C++ API" %}}

 Το Aspose.Cells API μπορεί να χρησιμοποιηθεί για τη δημιουργία, επεξεργασία, μετατροπή και απόδοση μορφών Microsoft Excel σε διαφορετικές μορφές. Επιπλέον, μπορεί να χρησιμοποιηθεί για ολοκληρωμένη χαρτογράφηση, κλιμακούμενη αναφορά και αξιόπιστους υπολογισμούς εντός εφαρμογών λογισμικού. Το Aspose.Cells είναι αυτόνομο API και δεν απαιτεί λογισμικό όπως η Microsoft ή το OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Εξαγωγή μεταδεδομένων του ODS μέσω της διαδικτυακής εφαρμογής" sectionDescription="Προβάλετε και επεξεργαστείτε Μεταδεδομένα σε έγγραφα ODS χρησιμοποιώντας το δικό μας [Live Demos](https://products.aspose.app/cells/metadata) με τα ακόλουθα οφέλη." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Δεν χρειάζεται να κατεβάσετε ή να ρυθμίσετε τίποτα" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Δεν χρειάζεται να γράψετε κανέναν κώδικα" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Απλώς ανεβάστε το αρχείο ODS και επεξεργαστείτε τις ιδιότητες του εγγράφου" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Λάβετε αμέσως τον σύνδεσμο λήψης για το αρχείο που προκύπτει" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODS" readMoreLink="https://docs.fileformat.com/spreadsheet/ods/" >}}
Τα αρχεία με επέκταση ODS αντιπροσωπεύουν τη μορφή εγγράφου υπολογιστικού φύλλου OpenDocument που είναι επεξεργάσιμα από τον χρήστη. Τα δεδομένα αποθηκεύονται μέσα στο αρχείο ODF σε γραμμές και στήλες. Είναι μορφή που βασίζεται σε XML και είναι ένας από τους διάφορους υποτύπους της οικογένειας Μορφές Ανοιχτών Εγγράφων (ODF). Η μορφή καθορίζεται ως μέρος των προδιαγραφών ODF 1.2 που δημοσιεύει και διατηρεί το OASIS. Ένας αριθμός εφαρμογών στα Windows καθώς και σε άλλα λειτουργικά συστήματα μπορούν να ανοίξουν αρχεία ODS για επεξεργασία και χειρισμό, συμπεριλαμβανομένων των Microsoft Excel, NeoOffice και LibreOffice. Τα αρχεία ODS μπορούν επίσης να μετατραπούν σε άλλες μορφές υπολογιστικών φύλλων, όπως XLS, XLSX και άλλα από διαφορετικές εφαρμογές.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μορφές μεταδεδομένων" subTitle="Χρησιμοποιώντας το C++, κάποιος μπορεί επίσης να χειριστεί μεταδεδομένα πολλών άλλων μορφών, συμπεριλαμβανομένων" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/metadata/xls/" name="XLS" description="Δυαδική μορφή Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/metadata/xlsb/" name="XLSB" description="Δυαδικό αρχείο βιβλίου εργασίας Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/metadata/xlsm/" name="XLSM" description="Αρχείο υπολογιστικού φύλλου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/metadata/xlsx/" name="XLSX" description="Αρχείο Excel OOXML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}