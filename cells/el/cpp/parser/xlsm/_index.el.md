---
title: Εξαγωγή κειμένου και εικόνων από το έγγραφο XLSM μέσω του C++
weight: 570
description: C++ παράδειγμα κώδικα για εξαγωγή κειμένου και εικόνων από το αρχείο XLSM στο C++ Runtime Environment για Windows 32 bit, Windows 64 bit και Linux 64 bit.
keywords: [C++ Aspose.Cells., C++ Extract text and images from XLSM file., C++ How to Parse XLSM File., C++ Extract text from XLSM file., Extract images from XLSM file using C++]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Ανάλυση XLSM Μορφές σε C++" h2="Εγγενής και υψηλής απόδοσης ανάλυση εγγράφων XLSM με χρήση API Aspose.Cells for C++ από την πλευρά του διακομιστή, χωρίς τη χρήση οποιουδήποτε λογισμικού όπως το Microsoft ή το Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLSM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Πώς να αναλύσετε το αρχείο XLSM χρησιμοποιώντας το C++" %}}

 Για να αναλύσουμε το αρχείο XLSM, θα χρησιμοποιήσουμε[Aspose.Cells for C++](https://products.aspose.com/cells/cpp) API το οποίο είναι μια πλούσια σε χαρακτηριστικά, ισχυρή και εύκολη στη χρήση πλατφόρμα ανάλυσης εγγράφων API for C++. Μπορείτε να κατεβάσετε την τελευταία του έκδοση απευθείας, απλά ανοίξτε[NuGet](https://www.nuget.org/packages/aspose.cells) διαχειριστής πακέτων, αναζητήστε**Aspose.Cells.Cpp** και εγκαταστήστε. Μπορείτε επίσης να χρησιμοποιήσετε την ακόλουθη εντολή από την Κονσόλα Package Manager.

{{% blocks/products/pf/agp/code-block title="Εντολή" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Βήματα για την ανάλυση αρχείων XLSM στο C++" %}}

{{% blocks/products/pf/agp/text %}}

 Ένα βασικό έγγραφο ανάλυσης με[Aspose.Cells for C++](https://products.aspose.com/cells/cpp)Τα API μπορούν να γίνουν με λίγες μόνο γραμμές κώδικα. Ανάλυση κειμένου και εικόνων από Microsoft Excel XLS, XLSX, XLSM, XLSB και OpenDocument ODS.

{{% /blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις συστήματος" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for C++ υποστηρίζει σε όλες τις μεγάλες πλατφόρμες και λειτουργικά συστήματα. Βεβαιωθείτε ότι έχετε τις ακόλουθες προϋποθέσεις.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows ή συμβατό λειτουργικό σύστημα με C++ Runtime Environment για Windows 32 bit, Windows 64 bit και Linux 64 bit.
-  Προσθέστε αναφορά στο DLL Aspose.Cells for C++ στο έργο σας.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Ανάλυση αρχείων XLSM - C++" offSpacer="" %}}

```cs

Aspose::Cells::Startup();

// extract images from Worksheets 
// open a template Excel file
Workbook workbook(u"sampleExtractImagesFromWorksheets.xlsm");

// get the first worksheet
Worksheet worksheet = workbook.GetWorksheets().Get(0);

// get the first Picture in the first worksheet
Picture pic = worksheet.GetPictures().Get(0);

// Note: you may evaluate the image format before specifying the image path
// define ImageOrPrintOptions
ImageOrPrintOptions printoption;

// specify the image format
printoption.SetImageType(ImageType::Jpeg);

// save the image
pic.ToImage(u"outputExtractImagesFromWorksheets.jpg", printoption);

Aspose::Cells::Cleanup();

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="Σχετικά με Aspose.Cells for C++ API" %}}

 Aspose.Cells API μπορεί να χρησιμοποιηθεί για τη δημιουργία, επεξεργασία, μετατροπή και απόδοση μορφών Excel Microsoft σε διαφορετικές μορφές. Επιπλέον, μπορεί να χρησιμοποιηθεί για ολοκληρωμένη χαρτογράφηση, κλιμακούμενη αναφορά και αξιόπιστους υπολογισμούς εντός εφαρμογών λογισμικού. Το Aspose.Cells είναι ένα αυτόνομο API και δεν απαιτεί λογισμικό όπως το Microsoft ή το OpenOffice.



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="Online XLSM Parser Live Demos" sectionDescription="Εξάγετε κείμενο και εικόνες από έγγραφα XLSM τώρα, επισκεπτόμενοι το δικό μας[Ζωντανή ιστοσελίδα Demos](https://products.aspose.app/cells/parser). Η ζωντανή επίδειξη έχει τα ακόλουθα πλεονεκτήματα" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Δεν χρειάζεται να κατεβάσετε το Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Δεν χρειάζεται να γράψετε κανέναν κώδικα." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Απλώς ανεβάστε τα XLSM αρχεία σας." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Θα αναλυθεί αμέσως." >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSM" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsm/" >}}
Τα αρχεία με επέκταση XLSM είναι ένας τύπος αρχείων υπολογιστικών φύλλων που υποστηρίζουν μακροεντολές. Από την άποψη της εφαρμογής, μια Μακροεντολή είναι ένα σύνολο οδηγιών που χρησιμοποιούνται για την αυτοματοποίηση των διαδικασιών. Μια μακροεντολή χρησιμοποιείται για την καταγραφή των βημάτων που εκτελούνται επανειλημμένα και διευκολύνει την εκτέλεση των ενεργειών εκτελώντας ξανά τη μακροεντολή. Οι μακροεντολές προγραμματίζονται με το Visual Basic for Applications (VBA) του Microsoft μέσα από το Βιβλίο εργασίας του Excel χρησιμοποιώντας τον Επεξεργαστή Visual Basic και μπορούν να εκτελεστούν/εντοπιστούν σφάλματα απευθείας από εκεί.

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Άλλα υποστηριζόμενα έγγραφα ανάλυσης" subTitle="Χρησιμοποιώντας το C++, μπορεί κανείς εύκολα να αναλύσει άλλες μορφές, συμπεριλαμβανομένων." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/parser/ods/" name="ODS" description="Αρχείο Υπολογιστικού Φύλλου OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/parser/xls/" name="XLS" description="Δυαδική μορφή Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/parser/xlsb/" name="XLSB" description="Δυαδικό αρχείο βιβλίου εργασίας Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/parser/xlsx/" name="XLSX" description="Αρχείο Excel OOXML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
